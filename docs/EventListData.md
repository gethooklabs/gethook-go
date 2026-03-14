# EventListData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]Event**](Event.md) |  | 
**Total** | **int32** |  | 

## Methods

### NewEventListData

`func NewEventListData(items []Event, total int32, ) *EventListData`

NewEventListData instantiates a new EventListData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEventListDataWithDefaults

`func NewEventListDataWithDefaults() *EventListData`

NewEventListDataWithDefaults instantiates a new EventListData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *EventListData) GetItems() []Event`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *EventListData) GetItemsOk() (*[]Event, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *EventListData) SetItems(v []Event)`

SetItems sets Items field to given value.


### GetTotal

`func (o *EventListData) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *EventListData) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *EventListData) SetTotal(v int32)`

SetTotal sets Total field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


