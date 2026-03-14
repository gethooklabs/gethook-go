# \OutboundEventsAPI

All URIs are relative to *http://localhost:8080*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetOutboundEvent**](OutboundEventsAPI.md#GetOutboundEvent) | **Get** /v1/outbound-events/{id} | Get outbound event
[**ListOutboundEvents**](OutboundEventsAPI.md#ListOutboundEvents) | **Get** /v1/outbound-events | List outbound events
[**PublishOutboundEvent**](OutboundEventsAPI.md#PublishOutboundEvent) | **Post** /v1/outbound-events | Publish outbound event
[**ReplayOutboundEvent**](OutboundEventsAPI.md#ReplayOutboundEvent) | **Post** /v1/outbound-events/{id}/replay | Replay outbound event



## GetOutboundEvent

> EventDetailData GetOutboundEvent(ctx, id).Execute()

Get outbound event

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
	id := "id_example" // string | Event UUID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OutboundEventsAPI.GetOutboundEvent(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OutboundEventsAPI.GetOutboundEvent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOutboundEvent`: EventDetailData
	fmt.Fprintf(os.Stdout, "Response from `OutboundEventsAPI.GetOutboundEvent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Event UUID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetOutboundEventRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EventDetailData**](EventDetailData.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListOutboundEvents

> EventListData ListOutboundEvents(ctx).Limit(limit).Offset(offset).Execute()

List outbound events

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
	limit := int32(56) // int32 | Max results (default 25, max 200) (optional)
	offset := int32(56) // int32 | Pagination offset (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OutboundEventsAPI.ListOutboundEvents(context.Background()).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OutboundEventsAPI.ListOutboundEvents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListOutboundEvents`: EventListData
	fmt.Fprintf(os.Stdout, "Response from `OutboundEventsAPI.ListOutboundEvents`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListOutboundEventsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** | Max results (default 25, max 200) | 
 **offset** | **int32** | Pagination offset | 

### Return type

[**EventListData**](EventListData.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PublishOutboundEvent

> PublishOutboundData PublishOutboundEvent(ctx).PublishOutboundEventRequest(publishOutboundEventRequest).Execute()

Publish outbound event



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
	publishOutboundEventRequest := *openapiclient.NewPublishOutboundEventRequest("{\"order_id\":\"123\"}") // PublishOutboundEventRequest | Event payload

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OutboundEventsAPI.PublishOutboundEvent(context.Background()).PublishOutboundEventRequest(publishOutboundEventRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OutboundEventsAPI.PublishOutboundEvent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PublishOutboundEvent`: PublishOutboundData
	fmt.Fprintf(os.Stdout, "Response from `OutboundEventsAPI.PublishOutboundEvent`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPublishOutboundEventRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **publishOutboundEventRequest** | [**PublishOutboundEventRequest**](PublishOutboundEventRequest.md) | Event payload | 

### Return type

[**PublishOutboundData**](PublishOutboundData.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReplayOutboundEvent

> ReplayEventData ReplayOutboundEvent(ctx, id).Execute()

Replay outbound event

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
	id := "id_example" // string | Event UUID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OutboundEventsAPI.ReplayOutboundEvent(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OutboundEventsAPI.ReplayOutboundEvent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReplayOutboundEvent`: ReplayEventData
	fmt.Fprintf(os.Stdout, "Response from `OutboundEventsAPI.ReplayOutboundEvent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Event UUID | 

### Other Parameters

Other parameters are passed through a pointer to a apiReplayOutboundEventRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ReplayEventData**](ReplayEventData.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

