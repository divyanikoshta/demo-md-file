# Mock-api

### Objective

    ⦁	Objective of mock api server is to imitates a real API server by providing realistic mock API responses to requests.
    
### Approach

    ⦁	Used miragjs as mocking server.
    ⦁	Open api 3.0 (swagger spec) is used for defining all the  end points, that will be Provided by the person working on backend.
    ⦁	Open api docs (swagger spec) path is "\src\mock_apis\index.json". 
    ⦁	server.js file is responsible for dynamically creating all the end points provided in the swagger spec. server.js file will be inside src folder. 
    ⦁	createServer is used to create the instance of the miragejs server. All the end point are written inside the routes() method in server.js file.
    ⦁	Response code of any end point can be changed using overrideResCode object in server.js file.
    ⦁	These mock apis will be return the example as it's response.

 #### Why Mirgejs
    ⦁   Mirage runs in the browser alongside your frontend code, so getting it running in your dev environment and using it to run tests on your CI servers is simpler – no extra processes to manage or reset.
    ⦁   Mirage resets its state on every browser reload.



![mock api workflow](/assets/mock_api_workflow.png "mock api workflow")

![server.js workflow](/assets/mock_api_serverjs_workflow.png "server.js workflow")


