# CreateRouteRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DestinationId** | **string** |  | 
**EventTypePattern** | Pointer to **string** |  | [optional] 
**SourceId** | Pointer to **string** |  | [optional] 

## Methods

### NewCreateRouteRequest

`func NewCreateRouteRequest(destinationId string, ) *CreateRouteRequest`

NewCreateRouteRequest instantiates a new CreateRouteRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateRouteRequestWithDefaults

`func NewCreateRouteRequestWithDefaults() *CreateRouteRequest`

NewCreateRouteRequestWithDefaults instantiates a new CreateRouteRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestinationId

`func (o *CreateRouteRequest) GetDestinationId() string`

GetDestinationId returns the DestinationId field if non-nil, zero value otherwise.

### GetDestinationIdOk

`func (o *CreateRouteRequest) GetDestinationIdOk() (*string, bool)`

GetDestinationIdOk returns a tuple with the DestinationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationId

`func (o *CreateRouteRequest) SetDestinationId(v string)`

SetDestinationId sets DestinationId field to given value.


### GetEventTypePattern

`func (o *CreateRouteRequest) GetEventTypePattern() string`

GetEventTypePattern returns the EventTypePattern field if non-nil, zero value otherwise.

### GetEventTypePatternOk

`func (o *CreateRouteRequest) GetEventTypePatternOk() (*string, bool)`

GetEventTypePatternOk returns a tuple with the EventTypePattern field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventTypePattern

`func (o *CreateRouteRequest) SetEventTypePattern(v string)`

SetEventTypePattern sets EventTypePattern field to given value.

### HasEventTypePattern

`func (o *CreateRouteRequest) HasEventTypePattern() bool`

HasEventTypePattern returns a boolean if a field has been set.

### GetSourceId

`func (o *CreateRouteRequest) GetSourceId() string`

GetSourceId returns the SourceId field if non-nil, zero value otherwise.

### GetSourceIdOk

`func (o *CreateRouteRequest) GetSourceIdOk() (*string, bool)`

GetSourceIdOk returns a tuple with the SourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceId

`func (o *CreateRouteRequest) SetSourceId(v string)`

SetSourceId sets SourceId field to given value.

### HasSourceId

`func (o *CreateRouteRequest) HasSourceId() bool`

HasSourceId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


