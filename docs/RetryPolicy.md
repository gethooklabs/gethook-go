# RetryPolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MaxAttempts** | Pointer to **int32** |  | [optional] 
**Backoff** | Pointer to **string** |  | [optional] 

## Methods

### NewRetryPolicy

`func NewRetryPolicy() *RetryPolicy`

NewRetryPolicy instantiates a new RetryPolicy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRetryPolicyWithDefaults

`func NewRetryPolicyWithDefaults() *RetryPolicy`

NewRetryPolicyWithDefaults instantiates a new RetryPolicy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMaxAttempts

`func (o *RetryPolicy) GetMaxAttempts() int32`

GetMaxAttempts returns the MaxAttempts field if non-nil, zero value otherwise.

### GetMaxAttemptsOk

`func (o *RetryPolicy) GetMaxAttemptsOk() (*int32, bool)`

GetMaxAttemptsOk returns a tuple with the MaxAttempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxAttempts

`func (o *RetryPolicy) SetMaxAttempts(v int32)`

SetMaxAttempts sets MaxAttempts field to given value.

### HasMaxAttempts

`func (o *RetryPolicy) HasMaxAttempts() bool`

HasMaxAttempts returns a boolean if a field has been set.

### GetBackoff

`func (o *RetryPolicy) GetBackoff() string`

GetBackoff returns the Backoff field if non-nil, zero value otherwise.

### GetBackoffOk

`func (o *RetryPolicy) GetBackoffOk() (*string, bool)`

GetBackoffOk returns a tuple with the Backoff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackoff

`func (o *RetryPolicy) SetBackoff(v string)`

SetBackoff sets Backoff field to given value.

### HasBackoff

`func (o *RetryPolicy) HasBackoff() bool`

HasBackoff returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


