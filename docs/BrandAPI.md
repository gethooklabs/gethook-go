# \BrandAPI

All URIs are relative to *http://localhost:8080*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetBrandSettings**](BrandAPI.md#GetBrandSettings) | **Get** /v1/brand-settings | Get brand settings
[**UpsertBrandSettings**](BrandAPI.md#UpsertBrandSettings) | **Post** /v1/brand-settings | Upsert brand settings



## GetBrandSettings

> BrandSettings GetBrandSettings(ctx).Execute()

Get brand settings

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
	resp, r, err := apiClient.BrandAPI.GetBrandSettings(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandAPI.GetBrandSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBrandSettings`: BrandSettings
	fmt.Fprintf(os.Stdout, "Response from `BrandAPI.GetBrandSettings`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetBrandSettingsRequest struct via the builder pattern


### Return type

[**BrandSettings**](BrandSettings.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpsertBrandSettings

> BrandSettings UpsertBrandSettings(ctx).UpsertBrandSettingsRequest(upsertBrandSettingsRequest).Execute()

Upsert brand settings



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
	upsertBrandSettingsRequest := *openapiclient.NewUpsertBrandSettingsRequest() // UpsertBrandSettingsRequest | Brand settings

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandAPI.UpsertBrandSettings(context.Background()).UpsertBrandSettingsRequest(upsertBrandSettingsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandAPI.UpsertBrandSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpsertBrandSettings`: BrandSettings
	fmt.Fprintf(os.Stdout, "Response from `BrandAPI.UpsertBrandSettings`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpsertBrandSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **upsertBrandSettingsRequest** | [**UpsertBrandSettingsRequest**](UpsertBrandSettingsRequest.md) | Brand settings | 

### Return type

[**BrandSettings**](BrandSettings.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

