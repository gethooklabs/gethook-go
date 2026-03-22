# AggregateTotals

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | **int32** |  | 
**Delivered** | **int32** |  | 
**Failed** | **int32** |  | 

## Methods

### NewAggregateTotals

`func NewAggregateTotals(total int32, delivered int32, failed int32, ) *AggregateTotals`

NewAggregateTotals instantiates a new AggregateTotals object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAggregateTotalsWithDefaults

`func NewAggregateTotalsWithDefaults() *AggregateTotals`

NewAggregateTotalsWithDefaults instantiates a new AggregateTotals object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *AggregateTotals) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *AggregateTotals) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *AggregateTotals) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetDelivered

`func (o *AggregateTotals) GetDelivered() int32`

GetDelivered returns the Delivered field if non-nil, zero value otherwise.

### GetDeliveredOk

`func (o *AggregateTotals) GetDeliveredOk() (*int32, bool)`

GetDeliveredOk returns a tuple with the Delivered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelivered

`func (o *AggregateTotals) SetDelivered(v int32)`

SetDelivered sets Delivered field to given value.


### GetFailed

`func (o *AggregateTotals) GetFailed() int32`

GetFailed returns the Failed field if non-nil, zero value otherwise.

### GetFailedOk

`func (o *AggregateTotals) GetFailedOk() (*int32, bool)`

GetFailedOk returns a tuple with the Failed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailed

`func (o *AggregateTotals) SetFailed(v int32)`

SetFailed sets Failed field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


