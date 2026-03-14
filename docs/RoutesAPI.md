# \RoutesAPI

All URIs are relative to *http://localhost:8080*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateRoute**](RoutesAPI.md#CreateRoute) | **Post** /v1/routes | Create route
[**ListRoutes**](RoutesAPI.md#ListRoutes) | **Get** /v1/routes | List routes



## CreateRoute

> Route CreateRoute(ctx).CreateRouteRequest(createRouteRequest).Execute()

Create route



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	createRouteRequest := *openapiclient.NewCreateRouteRequest("uuid") // CreateRouteRequest | Route config

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RoutesAPI.CreateRoute(context.Background()).CreateRouteRequest(createRouteRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RoutesAPI.CreateRoute``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateRoute`: Route
	fmt.Fprintf(os.Stdout, "Response from `RoutesAPI.CreateRoute`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateRouteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createRouteRequest** | [**CreateRouteRequest**](CreateRouteRequest.md) | Route config | 

### Return type

[**Route**](Route.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListRoutes

> []Route ListRoutes(ctx).Execute()

List routes

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RoutesAPI.ListRoutes(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RoutesAPI.ListRoutes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListRoutes`: []Route
	fmt.Fprintf(os.Stdout, "Response from `RoutesAPI.ListRoutes`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListRoutesRequest struct via the builder pattern


### Return type

[**[]Route**](Route.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

