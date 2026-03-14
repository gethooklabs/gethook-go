# StatsData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ByStatus** | [**[]StatsStatusItem**](StatsStatusItem.md) |  | 
**Daily** | [**[]StatsDailyItem**](StatsDailyItem.md) |  | 

## Methods

### NewStatsData

`func NewStatsData(byStatus []StatsStatusItem, daily []StatsDailyItem, ) *StatsData`

NewStatsData instantiates a new StatsData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsDataWithDefaults

`func NewStatsDataWithDefaults() *StatsData`

NewStatsDataWithDefaults instantiates a new StatsData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetByStatus

`func (o *StatsData) GetByStatus() []StatsStatusItem`

GetByStatus returns the ByStatus field if non-nil, zero value otherwise.

### GetByStatusOk

`func (o *StatsData) GetByStatusOk() (*[]StatsStatusItem, bool)`

GetByStatusOk returns a tuple with the ByStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByStatus

`func (o *StatsData) SetByStatus(v []StatsStatusItem)`

SetByStatus sets ByStatus field to given value.


### GetDaily

`func (o *StatsData) GetDaily() []StatsDailyItem`

GetDaily returns the Daily field if non-nil, zero value otherwise.

### GetDailyOk

`func (o *StatsData) GetDailyOk() (*[]StatsDailyItem, bool)`

GetDailyOk returns a tuple with the Daily field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDaily

`func (o *StatsData) SetDaily(v []StatsDailyItem)`

SetDaily sets Daily field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


