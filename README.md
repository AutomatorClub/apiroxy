# apiroxy
CLI tool that should simplify interactions with REST API's. API definition is described as a configuration file in simplple and human readable YAML format. This tool will handle API's authentification and provide drfault values so user can set bare minimum for successful API call. It will be possible to specify multiple api configurations and set filters and mappers between REST API calls, so in one step cli will read data from API, filter or map fields to next API schema and will make a POST request. 

# Test data

There is a mock API for tool to read data from https://mockend.com/
Following URL will generate test data for a user
```
curl -s https://mockend.com/AutomatorClub/apiroxy/user
[
        {
                "age": 77,
                "avatarUrl": "https://i.pravatar.cc/150?u=35617",
                "color": "#60\u000047E",
                "email": "#svmqkb@uvxyl.bi",
                "id": 1,
                "isPublic": true,
                "name": "RhuZicvVd7",
                "statusMessage": "watching Netflix"
        },
        {
                "age": 48,
                "avatarUrl": "https://i.pravatar.cc/150?u=30935",
                "color": "#8758\u0000B",
                "email": "#zlzbabb@cpffm.sw",
                "id": 2,
                "isPublic": true,
                "name": "hBDBonm35k",
                "statusMessage": "watching Netflix"
        }
]
```
