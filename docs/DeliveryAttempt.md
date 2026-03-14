# DeliveryAttempt

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AttemptNumber** | **int32** |  | 
**DestinationId** | **string** |  | 
**ErrorMessage** | Pointer to **string** |  | [optional] 
**EventId** | **string** |  | 
**FinishedAt** | Pointer to **string** |  | [optional] 
**Id** | **string** |  | 
**LatencyMs** | Pointer to **int32** |  | [optional] 
**Outcome** | [**AttemptOutcome**](AttemptOutcome.md) |  | 
**ResponseBody** | Pointer to **string** |  | [optional] 
**ResponseStatus** | Pointer to **int32** |  | [optional] 
**StartedAt** | **string** |  | 

## Methods

### NewDeliveryAttempt

`func NewDeliveryAttempt(attemptNumber int32, destinationId string, eventId string, id string, outcome AttemptOutcome, startedAt string, ) *DeliveryAttempt`

NewDeliveryAttempt instantiates a new DeliveryAttempt object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeliveryAttemptWithDefaults

`func NewDeliveryAttemptWithDefaults() *DeliveryAttempt`

NewDeliveryAttemptWithDefaults instantiates a new DeliveryAttempt object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAttemptNumber

`func (o *DeliveryAttempt) GetAttemptNumber() int32`

GetAttemptNumber returns the AttemptNumber field if non-nil, zero value otherwise.

### GetAttemptNumberOk

`func (o *DeliveryAttempt) GetAttemptNumberOk() (*int32, bool)`

GetAttemptNumberOk returns a tuple with the AttemptNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttemptNumber

`func (o *DeliveryAttempt) SetAttemptNumber(v int32)`

SetAttemptNumber sets AttemptNumber field to given value.


### GetDestinationId

`func (o *DeliveryAttempt) GetDestinationId() string`

GetDestinationId returns the DestinationId field if non-nil, zero value otherwise.

### GetDestinationIdOk

`func (o *DeliveryAttempt) GetDestinationIdOk() (*string, bool)`

GetDestinationIdOk returns a tuple with the DestinationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationId

`func (o *DeliveryAttempt) SetDestinationId(v string)`

SetDestinationId sets DestinationId field to given value.


### GetErrorMessage

`func (o *DeliveryAttempt) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *DeliveryAttempt) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *DeliveryAttempt) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *DeliveryAttempt) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### GetEventId

`func (o *DeliveryAttempt) GetEventId() string`

GetEventId returns the EventId field if non-nil, zero value otherwise.

### GetEventIdOk

`func (o *DeliveryAttempt) GetEventIdOk() (*string, bool)`

GetEventIdOk returns a tuple with the EventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventId

`func (o *DeliveryAttempt) SetEventId(v string)`

SetEventId sets EventId field to given value.


### GetFinishedAt

`func (o *DeliveryAttempt) GetFinishedAt() string`

GetFinishedAt returns the FinishedAt field if non-nil, zero value otherwise.

### GetFinishedAtOk

`func (o *DeliveryAttempt) GetFinishedAtOk() (*string, bool)`

GetFinishedAtOk returns a tuple with the FinishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishedAt

`func (o *DeliveryAttempt) SetFinishedAt(v string)`

SetFinishedAt sets FinishedAt field to given value.

### HasFinishedAt

`func (o *DeliveryAttempt) HasFinishedAt() bool`

HasFinishedAt returns a boolean if a field has been set.

### GetId

`func (o *DeliveryAttempt) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DeliveryAttempt) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DeliveryAttempt) SetId(v string)`

SetId sets Id field to given value.


### GetLatencyMs

`func (o *DeliveryAttempt) GetLatencyMs() int32`

GetLatencyMs returns the LatencyMs field if non-nil, zero value otherwise.

### GetLatencyMsOk

`func (o *DeliveryAttempt) GetLatencyMsOk() (*int32, bool)`

GetLatencyMsOk returns a tuple with the LatencyMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatencyMs

`func (o *DeliveryAttempt) SetLatencyMs(v int32)`

SetLatencyMs sets LatencyMs field to given value.

### HasLatencyMs

`func (o *DeliveryAttempt) HasLatencyMs() bool`

HasLatencyMs returns a boolean if a field has been set.

### GetOutcome

`func (o *DeliveryAttempt) GetOutcome() AttemptOutcome`

GetOutcome returns the Outcome field if non-nil, zero value otherwise.

### GetOutcomeOk

`func (o *DeliveryAttempt) GetOutcomeOk() (*AttemptOutcome, bool)`

GetOutcomeOk returns a tuple with the Outcome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcome

`func (o *DeliveryAttempt) SetOutcome(v AttemptOutcome)`

SetOutcome sets Outcome field to given value.


### GetResponseBody

`func (o *DeliveryAttempt) GetResponseBody() string`

GetResponseBody returns the ResponseBody field if non-nil, zero value otherwise.

### GetResponseBodyOk

`func (o *DeliveryAttempt) GetResponseBodyOk() (*string, bool)`

GetResponseBodyOk returns a tuple with the ResponseBody field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseBody

`func (o *DeliveryAttempt) SetResponseBody(v string)`

SetResponseBody sets ResponseBody field to given value.

### HasResponseBody

`func (o *DeliveryAttempt) HasResponseBody() bool`

HasResponseBody returns a boolean if a field has been set.

### GetResponseStatus

`func (o *DeliveryAttempt) GetResponseStatus() int32`

GetResponseStatus returns the ResponseStatus field if non-nil, zero value otherwise.

### GetResponseStatusOk

`func (o *DeliveryAttempt) GetResponseStatusOk() (*int32, bool)`

GetResponseStatusOk returns a tuple with the ResponseStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseStatus

`func (o *DeliveryAttempt) SetResponseStatus(v int32)`

SetResponseStatus sets ResponseStatus field to given value.

### HasResponseStatus

`func (o *DeliveryAttempt) HasResponseStatus() bool`

HasResponseStatus returns a boolean if a field has been set.

### GetStartedAt

`func (o *DeliveryAttempt) GetStartedAt() string`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *DeliveryAttempt) GetStartedAtOk() (*string, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *DeliveryAttempt) SetStartedAt(v string)`

SetStartedAt sets StartedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


