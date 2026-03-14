# EventDetailData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Attempts** | [**[]DeliveryAttempt**](DeliveryAttempt.md) |  | 
**Event** | [**Event**](Event.md) |  | 

## Methods

### NewEventDetailData

`func NewEventDetailData(attempts []DeliveryAttempt, event Event, ) *EventDetailData`

NewEventDetailData instantiates a new EventDetailData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEventDetailDataWithDefaults

`func NewEventDetailDataWithDefaults() *EventDetailData`

NewEventDetailDataWithDefaults instantiates a new EventDetailData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAttempts

`func (o *EventDetailData) GetAttempts() []DeliveryAttempt`

GetAttempts returns the Attempts field if non-nil, zero value otherwise.

### GetAttemptsOk

`func (o *EventDetailData) GetAttemptsOk() (*[]DeliveryAttempt, bool)`

GetAttemptsOk returns a tuple with the Attempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttempts

`func (o *EventDetailData) SetAttempts(v []DeliveryAttempt)`

SetAttempts sets Attempts field to given value.


### GetEvent

`func (o *EventDetailData) GetEvent() Event`

GetEvent returns the Event field if non-nil, zero value otherwise.

### GetEventOk

`func (o *EventDetailData) GetEventOk() (*Event, bool)`

GetEventOk returns a tuple with the Event field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvent

`func (o *EventDetailData) SetEvent(v Event)`

SetEvent sets Event field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


