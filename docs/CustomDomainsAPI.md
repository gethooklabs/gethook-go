# \CustomDomainsAPI

All URIs are relative to *http://localhost:8080*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateCustomDomain**](CustomDomainsAPI.md#CreateCustomDomain) | **Post** /v1/custom-domains | Create custom domain
[**ListCustomDomains**](CustomDomainsAPI.md#ListCustomDomains) | **Get** /v1/custom-domains | List custom domains



## CreateCustomDomain

> CustomDomain CreateCustomDomain(ctx).CreateCustomDomainRequest(createCustomDomainRequest).Execute()

Create custom domain

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
	createCustomDomainRequest := *openapiclient.NewCreateCustomDomainRequest("webhooks.example.com") // CreateCustomDomainRequest | Domain details

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomDomainsAPI.CreateCustomDomain(context.Background()).CreateCustomDomainRequest(createCustomDomainRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomDomainsAPI.CreateCustomDomain``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCustomDomain`: CustomDomain
	fmt.Fprintf(os.Stdout, "Response from `CustomDomainsAPI.CreateCustomDomain`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateCustomDomainRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCustomDomainRequest** | [**CreateCustomDomainRequest**](CreateCustomDomainRequest.md) | Domain details | 

### Return type

[**CustomDomain**](CustomDomain.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCustomDomains

> []CustomDomain ListCustomDomains(ctx).Execute()

List custom domains

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
	resp, r, err := apiClient.CustomDomainsAPI.ListCustomDomains(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomDomainsAPI.ListCustomDomains``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCustomDomains`: []CustomDomain
	fmt.Fprintf(os.Stdout, "Response from `CustomDomainsAPI.ListCustomDomains`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListCustomDomainsRequest struct via the builder pattern


### Return type

[**[]CustomDomain**](CustomDomain.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

