# \AuthAPI

All URIs are relative to *http://localhost:8080*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Login**](AuthAPI.md#Login) | **Post** /v1/auth/login | Login with email and password
[**Register**](AuthAPI.md#Register) | **Post** /v1/auth/register | Register with email and password



## Login

> AccountBootstrapData Login(ctx).LoginRequest(loginRequest).Execute()

Login with email and password



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
	loginRequest := *openapiclient.NewLoginRequest("admin@example.com", "supersecret") // LoginRequest | Login credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthAPI.Login(context.Background()).LoginRequest(loginRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthAPI.Login``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Login`: AccountBootstrapData
	fmt.Fprintf(os.Stdout, "Response from `AuthAPI.Login`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiLoginRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **loginRequest** | [**LoginRequest**](LoginRequest.md) | Login credentials | 

### Return type

[**AccountBootstrapData**](AccountBootstrapData.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Register

> AccountBootstrapData Register(ctx).RegisterRequest(registerRequest).Execute()

Register with email and password



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
	registerRequest := *openapiclient.NewRegisterRequest("admin@example.com", "My Company", "supersecret") // RegisterRequest | Registration details

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthAPI.Register(context.Background()).RegisterRequest(registerRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthAPI.Register``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Register`: AccountBootstrapData
	fmt.Fprintf(os.Stdout, "Response from `AuthAPI.Register`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegisterRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **registerRequest** | [**RegisterRequest**](RegisterRequest.md) | Registration details | 

### Return type

[**AccountBootstrapData**](AccountBootstrapData.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

