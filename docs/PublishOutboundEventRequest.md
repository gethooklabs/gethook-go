# PublishOutboundEventRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EventType** | Pointer to **string** |  | [optional] 
**ExternalEventId** | Pointer to **string** |  | [optional] 
**Payload** | **string** |  | 

## Methods

### NewPublishOutboundEventRequest

`func NewPublishOutboundEventRequest(payload string, ) *PublishOutboundEventRequest`

NewPublishOutboundEventRequest instantiates a new PublishOutboundEventRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublishOutboundEventRequestWithDefaults

`func NewPublishOutboundEventRequestWithDefaults() *PublishOutboundEventRequest`

NewPublishOutboundEventRequestWithDefaults instantiates a new PublishOutboundEventRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEventType

`func (o *PublishOutboundEventRequest) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *PublishOutboundEventRequest) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *PublishOutboundEventRequest) SetEventType(v string)`

SetEventType sets EventType field to given value.

### HasEventType

`func (o *PublishOutboundEventRequest) HasEventType() bool`

HasEventType returns a boolean if a field has been set.

### GetExternalEventId

`func (o *PublishOutboundEventRequest) GetExternalEventId() string`

GetExternalEventId returns the ExternalEventId field if non-nil, zero value otherwise.

### GetExternalEventIdOk

`func (o *PublishOutboundEventRequest) GetExternalEventIdOk() (*string, bool)`

GetExternalEventIdOk returns a tuple with the ExternalEventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalEventId

`func (o *PublishOutboundEventRequest) SetExternalEventId(v string)`

SetExternalEventId sets ExternalEventId field to given value.

### HasExternalEventId

`func (o *PublishOutboundEventRequest) HasExternalEventId() bool`

HasExternalEventId returns a boolean if a field has been set.

### GetPayload

`func (o *PublishOutboundEventRequest) GetPayload() string`

GetPayload returns the Payload field if non-nil, zero value otherwise.

### GetPayloadOk

`func (o *PublishOutboundEventRequest) GetPayloadOk() (*string, bool)`

GetPayloadOk returns a tuple with the Payload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayload

`func (o *PublishOutboundEventRequest) SetPayload(v string)`

SetPayload sets Payload field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


