# Event

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | **string** |  | 
**AttemptsCount** | **int32** |  | 
**Body** | **string** |  | 
**CreatedAt** | **string** |  | 
**CreatedBy** | Pointer to **string** |  | [optional] 
**Direction** | [**Direction**](Direction.md) |  | 
**EventType** | Pointer to **string** |  | [optional] 
**ExternalEventId** | Pointer to **string** |  | [optional] 
**FinalState** | Pointer to **string** |  | [optional] 
**Headers** | **map[string]interface{}** |  | 
**Id** | **string** |  | 
**NextAttemptAt** | Pointer to **string** |  | [optional] 
**PayloadHash** | Pointer to **string** |  | [optional] 
**ReceivedAt** | **string** |  | 
**SourceId** | Pointer to **string** |  | [optional] 
**Status** | [**EventStatus**](EventStatus.md) |  | 

## Methods

### NewEvent

`func NewEvent(accountId string, attemptsCount int32, body string, createdAt string, direction Direction, headers map[string]interface{}, id string, receivedAt string, status EventStatus, ) *Event`

NewEvent instantiates a new Event object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEventWithDefaults

`func NewEventWithDefaults() *Event`

NewEventWithDefaults instantiates a new Event object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *Event) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *Event) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *Event) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.


### GetAttemptsCount

`func (o *Event) GetAttemptsCount() int32`

GetAttemptsCount returns the AttemptsCount field if non-nil, zero value otherwise.

### GetAttemptsCountOk

`func (o *Event) GetAttemptsCountOk() (*int32, bool)`

GetAttemptsCountOk returns a tuple with the AttemptsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttemptsCount

`func (o *Event) SetAttemptsCount(v int32)`

SetAttemptsCount sets AttemptsCount field to given value.


### GetBody

`func (o *Event) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *Event) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *Event) SetBody(v string)`

SetBody sets Body field to given value.


### GetCreatedAt

`func (o *Event) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Event) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Event) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCreatedBy

`func (o *Event) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *Event) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *Event) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *Event) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### GetDirection

`func (o *Event) GetDirection() Direction`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *Event) GetDirectionOk() (*Direction, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *Event) SetDirection(v Direction)`

SetDirection sets Direction field to given value.


### GetEventType

`func (o *Event) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *Event) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *Event) SetEventType(v string)`

SetEventType sets EventType field to given value.

### HasEventType

`func (o *Event) HasEventType() bool`

HasEventType returns a boolean if a field has been set.

### GetExternalEventId

`func (o *Event) GetExternalEventId() string`

GetExternalEventId returns the ExternalEventId field if non-nil, zero value otherwise.

### GetExternalEventIdOk

`func (o *Event) GetExternalEventIdOk() (*string, bool)`

GetExternalEventIdOk returns a tuple with the ExternalEventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalEventId

`func (o *Event) SetExternalEventId(v string)`

SetExternalEventId sets ExternalEventId field to given value.

### HasExternalEventId

`func (o *Event) HasExternalEventId() bool`

HasExternalEventId returns a boolean if a field has been set.

### GetFinalState

`func (o *Event) GetFinalState() string`

GetFinalState returns the FinalState field if non-nil, zero value otherwise.

### GetFinalStateOk

`func (o *Event) GetFinalStateOk() (*string, bool)`

GetFinalStateOk returns a tuple with the FinalState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinalState

`func (o *Event) SetFinalState(v string)`

SetFinalState sets FinalState field to given value.

### HasFinalState

`func (o *Event) HasFinalState() bool`

HasFinalState returns a boolean if a field has been set.

### GetHeaders

`func (o *Event) GetHeaders() map[string]interface{}`

GetHeaders returns the Headers field if non-nil, zero value otherwise.

### GetHeadersOk

`func (o *Event) GetHeadersOk() (*map[string]interface{}, bool)`

GetHeadersOk returns a tuple with the Headers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeaders

`func (o *Event) SetHeaders(v map[string]interface{})`

SetHeaders sets Headers field to given value.


### GetId

`func (o *Event) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Event) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Event) SetId(v string)`

SetId sets Id field to given value.


### GetNextAttemptAt

`func (o *Event) GetNextAttemptAt() string`

GetNextAttemptAt returns the NextAttemptAt field if non-nil, zero value otherwise.

### GetNextAttemptAtOk

`func (o *Event) GetNextAttemptAtOk() (*string, bool)`

GetNextAttemptAtOk returns a tuple with the NextAttemptAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextAttemptAt

`func (o *Event) SetNextAttemptAt(v string)`

SetNextAttemptAt sets NextAttemptAt field to given value.

### HasNextAttemptAt

`func (o *Event) HasNextAttemptAt() bool`

HasNextAttemptAt returns a boolean if a field has been set.

### GetPayloadHash

`func (o *Event) GetPayloadHash() string`

GetPayloadHash returns the PayloadHash field if non-nil, zero value otherwise.

### GetPayloadHashOk

`func (o *Event) GetPayloadHashOk() (*string, bool)`

GetPayloadHashOk returns a tuple with the PayloadHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayloadHash

`func (o *Event) SetPayloadHash(v string)`

SetPayloadHash sets PayloadHash field to given value.

### HasPayloadHash

`func (o *Event) HasPayloadHash() bool`

HasPayloadHash returns a boolean if a field has been set.

### GetReceivedAt

`func (o *Event) GetReceivedAt() string`

GetReceivedAt returns the ReceivedAt field if non-nil, zero value otherwise.

### GetReceivedAtOk

`func (o *Event) GetReceivedAtOk() (*string, bool)`

GetReceivedAtOk returns a tuple with the ReceivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceivedAt

`func (o *Event) SetReceivedAt(v string)`

SetReceivedAt sets ReceivedAt field to given value.


### GetSourceId

`func (o *Event) GetSourceId() string`

GetSourceId returns the SourceId field if non-nil, zero value otherwise.

### GetSourceIdOk

`func (o *Event) GetSourceIdOk() (*string, bool)`

GetSourceIdOk returns a tuple with the SourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceId

`func (o *Event) SetSourceId(v string)`

SetSourceId sets SourceId field to given value.

### HasSourceId

`func (o *Event) HasSourceId() bool`

HasSourceId returns a boolean if a field has been set.

### GetStatus

`func (o *Event) GetStatus() EventStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Event) GetStatusOk() (*EventStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Event) SetStatus(v EventStatus)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


