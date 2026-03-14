# CreateSourceRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AuthMode** | Pointer to **string** |  | [optional] 
**Name** | **string** |  | 
**VerificationConfig** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewCreateSourceRequest

`func NewCreateSourceRequest(name string, ) *CreateSourceRequest`

NewCreateSourceRequest instantiates a new CreateSourceRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateSourceRequestWithDefaults

`func NewCreateSourceRequestWithDefaults() *CreateSourceRequest`

NewCreateSourceRequestWithDefaults instantiates a new CreateSourceRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuthMode

`func (o *CreateSourceRequest) GetAuthMode() string`

GetAuthMode returns the AuthMode field if non-nil, zero value otherwise.

### GetAuthModeOk

`func (o *CreateSourceRequest) GetAuthModeOk() (*string, bool)`

GetAuthModeOk returns a tuple with the AuthMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthMode

`func (o *CreateSourceRequest) SetAuthMode(v string)`

SetAuthMode sets AuthMode field to given value.

### HasAuthMode

`func (o *CreateSourceRequest) HasAuthMode() bool`

HasAuthMode returns a boolean if a field has been set.

### GetName

`func (o *CreateSourceRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateSourceRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateSourceRequest) SetName(v string)`

SetName sets Name field to given value.


### GetVerificationConfig

`func (o *CreateSourceRequest) GetVerificationConfig() map[string]interface{}`

GetVerificationConfig returns the VerificationConfig field if non-nil, zero value otherwise.

### GetVerificationConfigOk

`func (o *CreateSourceRequest) GetVerificationConfigOk() (*map[string]interface{}, bool)`

GetVerificationConfigOk returns a tuple with the VerificationConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerificationConfig

`func (o *CreateSourceRequest) SetVerificationConfig(v map[string]interface{})`

SetVerificationConfig sets VerificationConfig field to given value.

### HasVerificationConfig

`func (o *CreateSourceRequest) HasVerificationConfig() bool`

HasVerificationConfig returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


