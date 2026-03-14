# Route

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | **string** |  | 
**Active** | **bool** |  | 
**CreatedAt** | **string** |  | 
**DestinationId** | **string** |  | 
**EventTypePattern** | Pointer to **string** |  | [optional] 
**Id** | **string** |  | 
**RetryPolicy** | **map[string]interface{}** |  | 
**SourceId** | Pointer to **string** |  | [optional] 

## Methods

### NewRoute

`func NewRoute(accountId string, active bool, createdAt string, destinationId string, id string, retryPolicy map[string]interface{}, ) *Route`

NewRoute instantiates a new Route object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRouteWithDefaults

`func NewRouteWithDefaults() *Route`

NewRouteWithDefaults instantiates a new Route object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *Route) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *Route) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *Route) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.


### GetActive

`func (o *Route) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *Route) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *Route) SetActive(v bool)`

SetActive sets Active field to given value.


### GetCreatedAt

`func (o *Route) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Route) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Route) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetDestinationId

`func (o *Route) GetDestinationId() string`

GetDestinationId returns the DestinationId field if non-nil, zero value otherwise.

### GetDestinationIdOk

`func (o *Route) GetDestinationIdOk() (*string, bool)`

GetDestinationIdOk returns a tuple with the DestinationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationId

`func (o *Route) SetDestinationId(v string)`

SetDestinationId sets DestinationId field to given value.


### GetEventTypePattern

`func (o *Route) GetEventTypePattern() string`

GetEventTypePattern returns the EventTypePattern field if non-nil, zero value otherwise.

### GetEventTypePatternOk

`func (o *Route) GetEventTypePatternOk() (*string, bool)`

GetEventTypePatternOk returns a tuple with the EventTypePattern field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventTypePattern

`func (o *Route) SetEventTypePattern(v string)`

SetEventTypePattern sets EventTypePattern field to given value.

### HasEventTypePattern

`func (o *Route) HasEventTypePattern() bool`

HasEventTypePattern returns a boolean if a field has been set.

### GetId

`func (o *Route) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Route) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Route) SetId(v string)`

SetId sets Id field to given value.


### GetRetryPolicy

`func (o *Route) GetRetryPolicy() map[string]interface{}`

GetRetryPolicy returns the RetryPolicy field if non-nil, zero value otherwise.

### GetRetryPolicyOk

`func (o *Route) GetRetryPolicyOk() (*map[string]interface{}, bool)`

GetRetryPolicyOk returns a tuple with the RetryPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryPolicy

`func (o *Route) SetRetryPolicy(v map[string]interface{})`

SetRetryPolicy sets RetryPolicy field to given value.


### GetSourceId

`func (o *Route) GetSourceId() string`

GetSourceId returns the SourceId field if non-nil, zero value otherwise.

### GetSourceIdOk

`func (o *Route) GetSourceIdOk() (*string, bool)`

GetSourceIdOk returns a tuple with the SourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceId

`func (o *Route) SetSourceId(v string)`

SetSourceId sets SourceId field to given value.

### HasSourceId

`func (o *Route) HasSourceId() bool`

HasSourceId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


