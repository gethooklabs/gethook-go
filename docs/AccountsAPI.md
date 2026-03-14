# \AccountsAPI

All URIs are relative to *http://localhost:8080*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAccount**](AccountsAPI.md#CreateAccount) | **Post** /v1/accounts | Create account



## CreateAccount

> AccountBootstrapData CreateAccount(ctx).CreateAccountRequest(createAccountRequest).Execute()

Create account



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
	createAccountRequest := *openapiclient.NewCreateAccountRequest("My Company") // CreateAccountRequest | Account name

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountsAPI.CreateAccount(context.Background()).CreateAccountRequest(createAccountRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountsAPI.CreateAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAccount`: AccountBootstrapData
	fmt.Fprintf(os.Stdout, "Response from `AccountsAPI.CreateAccount`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createAccountRequest** | [**CreateAccountRequest**](CreateAccountRequest.md) | Account name | 

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

