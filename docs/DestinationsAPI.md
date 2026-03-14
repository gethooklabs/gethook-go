# \DestinationsAPI

All URIs are relative to *http://localhost:8080*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateDestination**](DestinationsAPI.md#CreateDestination) | **Post** /v1/destinations | Create destination
[**GetDestination**](DestinationsAPI.md#GetDestination) | **Get** /v1/destinations/{id} | Get destination
[**ListDestinationPresets**](DestinationsAPI.md#ListDestinationPresets) | **Get** /v1/destination-presets | List destination presets
[**ListDestinations**](DestinationsAPI.md#ListDestinations) | **Get** /v1/destinations | List destinations
[**RotateDestinationSecret**](DestinationsAPI.md#RotateDestinationSecret) | **Post** /v1/destinations/{id}/rotate-secret | Rotate destination signing secret
[**UpdateDestination**](DestinationsAPI.md#UpdateDestination) | **Patch** /v1/destinations/{id} | Update destination



## CreateDestination

> Destination CreateDestination(ctx).CreateDestinationRequest(createDestinationRequest).Execute()

Create destination



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
	createDestinationRequest := *openapiclient.NewCreateDestinationRequest("My endpoint", "https://example.com/webhooks") // CreateDestinationRequest | Destination config

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DestinationsAPI.CreateDestination(context.Background()).CreateDestinationRequest(createDestinationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DestinationsAPI.CreateDestination``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDestination`: Destination
	fmt.Fprintf(os.Stdout, "Response from `DestinationsAPI.CreateDestination`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDestinationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createDestinationRequest** | [**CreateDestinationRequest**](CreateDestinationRequest.md) | Destination config | 

### Return type

[**Destination**](Destination.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDestination

> Destination GetDestination(ctx, id).Execute()

Get destination

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
	id := "id_example" // string | Destination UUID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DestinationsAPI.GetDestination(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DestinationsAPI.GetDestination``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDestination`: Destination
	fmt.Fprintf(os.Stdout, "Response from `DestinationsAPI.GetDestination`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Destination UUID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDestinationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Destination**](Destination.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDestinationPresets

> []DestinationPreset ListDestinationPresets(ctx).Execute()

List destination presets

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
	resp, r, err := apiClient.DestinationsAPI.ListDestinationPresets(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DestinationsAPI.ListDestinationPresets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDestinationPresets`: []DestinationPreset
	fmt.Fprintf(os.Stdout, "Response from `DestinationsAPI.ListDestinationPresets`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListDestinationPresetsRequest struct via the builder pattern


### Return type

[**[]DestinationPreset**](DestinationPreset.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDestinations

> []Destination ListDestinations(ctx).Execute()

List destinations

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
	resp, r, err := apiClient.DestinationsAPI.ListDestinations(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DestinationsAPI.ListDestinations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDestinations`: []Destination
	fmt.Fprintf(os.Stdout, "Response from `DestinationsAPI.ListDestinations`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListDestinationsRequest struct via the builder pattern


### Return type

[**[]Destination**](Destination.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RotateDestinationSecret

> map[string]interface{} RotateDestinationSecret(ctx, id).Body(body).Execute()

Rotate destination signing secret

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
	id := "id_example" // string | Destination UUID
	body := map[string]interface{}{ ... } // map[string]interface{} | New signing secret

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DestinationsAPI.RotateDestinationSecret(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DestinationsAPI.RotateDestinationSecret``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RotateDestinationSecret`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `DestinationsAPI.RotateDestinationSecret`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Destination UUID | 

### Other Parameters

Other parameters are passed through a pointer to a apiRotateDestinationSecretRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **map[string]interface{}** | New signing secret | 

### Return type

**map[string]interface{}**

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDestination

> Destination UpdateDestination(ctx, id).UpdateDestinationRequest(updateDestinationRequest).Execute()

Update destination

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
	id := "id_example" // string | Destination UUID
	updateDestinationRequest := *openapiclient.NewUpdateDestinationRequest() // UpdateDestinationRequest | Fields to update

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DestinationsAPI.UpdateDestination(context.Background(), id).UpdateDestinationRequest(updateDestinationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DestinationsAPI.UpdateDestination``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDestination`: Destination
	fmt.Fprintf(os.Stdout, "Response from `DestinationsAPI.UpdateDestination`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Destination UUID | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDestinationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateDestinationRequest** | [**UpdateDestinationRequest**](UpdateDestinationRequest.md) | Fields to update | 

### Return type

[**Destination**](Destination.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

