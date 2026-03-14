# UpdateDestinationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Active** | Pointer to **bool** |  | [optional] 
**AuthConfig** | Pointer to **map[string]interface{}** |  | [optional] 
**CustomHeaders** | Pointer to **map[string]interface{}** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**TimeoutSeconds** | Pointer to **int32** |  | [optional] 
**Url** | Pointer to **string** |  | [optional] 

## Methods

### NewUpdateDestinationRequest

`func NewUpdateDestinationRequest() *UpdateDestinationRequest`

NewUpdateDestinationRequest instantiates a new UpdateDestinationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateDestinationRequestWithDefaults

`func NewUpdateDestinationRequestWithDefaults() *UpdateDestinationRequest`

NewUpdateDestinationRequestWithDefaults instantiates a new UpdateDestinationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActive

`func (o *UpdateDestinationRequest) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *UpdateDestinationRequest) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *UpdateDestinationRequest) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *UpdateDestinationRequest) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetAuthConfig

`func (o *UpdateDestinationRequest) GetAuthConfig() map[string]interface{}`

GetAuthConfig returns the AuthConfig field if non-nil, zero value otherwise.

### GetAuthConfigOk

`func (o *UpdateDestinationRequest) GetAuthConfigOk() (*map[string]interface{}, bool)`

GetAuthConfigOk returns a tuple with the AuthConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthConfig

`func (o *UpdateDestinationRequest) SetAuthConfig(v map[string]interface{})`

SetAuthConfig sets AuthConfig field to given value.

### HasAuthConfig

`func (o *UpdateDestinationRequest) HasAuthConfig() bool`

HasAuthConfig returns a boolean if a field has been set.

### GetCustomHeaders

`func (o *UpdateDestinationRequest) GetCustomHeaders() map[string]interface{}`

GetCustomHeaders returns the CustomHeaders field if non-nil, zero value otherwise.

### GetCustomHeadersOk

`func (o *UpdateDestinationRequest) GetCustomHeadersOk() (*map[string]interface{}, bool)`

GetCustomHeadersOk returns a tuple with the CustomHeaders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomHeaders

`func (o *UpdateDestinationRequest) SetCustomHeaders(v map[string]interface{})`

SetCustomHeaders sets CustomHeaders field to given value.

### HasCustomHeaders

`func (o *UpdateDestinationRequest) HasCustomHeaders() bool`

HasCustomHeaders returns a boolean if a field has been set.

### GetName

`func (o *UpdateDestinationRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateDestinationRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateDestinationRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateDestinationRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetTimeoutSeconds

`func (o *UpdateDestinationRequest) GetTimeoutSeconds() int32`

GetTimeoutSeconds returns the TimeoutSeconds field if non-nil, zero value otherwise.

### GetTimeoutSecondsOk

`func (o *UpdateDestinationRequest) GetTimeoutSecondsOk() (*int32, bool)`

GetTimeoutSecondsOk returns a tuple with the TimeoutSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeoutSeconds

`func (o *UpdateDestinationRequest) SetTimeoutSeconds(v int32)`

SetTimeoutSeconds sets TimeoutSeconds field to given value.

### HasTimeoutSeconds

`func (o *UpdateDestinationRequest) HasTimeoutSeconds() bool`

HasTimeoutSeconds returns a boolean if a field has been set.

### GetUrl

`func (o *UpdateDestinationRequest) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *UpdateDestinationRequest) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *UpdateDestinationRequest) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *UpdateDestinationRequest) HasUrl() bool`

HasUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


