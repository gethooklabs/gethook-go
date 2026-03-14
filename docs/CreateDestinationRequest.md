# CreateDestinationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AuthConfig** | Pointer to **map[string]interface{}** |  | [optional] 
**CustomHeaders** | Pointer to **map[string]interface{}** |  | [optional] 
**Name** | **string** |  | 
**SigningSecret** | Pointer to **string** |  | [optional] 
**TimeoutSeconds** | Pointer to **int32** |  | [optional] 
**Url** | **string** |  | 

## Methods

### NewCreateDestinationRequest

`func NewCreateDestinationRequest(name string, url string, ) *CreateDestinationRequest`

NewCreateDestinationRequest instantiates a new CreateDestinationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDestinationRequestWithDefaults

`func NewCreateDestinationRequestWithDefaults() *CreateDestinationRequest`

NewCreateDestinationRequestWithDefaults instantiates a new CreateDestinationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuthConfig

`func (o *CreateDestinationRequest) GetAuthConfig() map[string]interface{}`

GetAuthConfig returns the AuthConfig field if non-nil, zero value otherwise.

### GetAuthConfigOk

`func (o *CreateDestinationRequest) GetAuthConfigOk() (*map[string]interface{}, bool)`

GetAuthConfigOk returns a tuple with the AuthConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthConfig

`func (o *CreateDestinationRequest) SetAuthConfig(v map[string]interface{})`

SetAuthConfig sets AuthConfig field to given value.

### HasAuthConfig

`func (o *CreateDestinationRequest) HasAuthConfig() bool`

HasAuthConfig returns a boolean if a field has been set.

### GetCustomHeaders

`func (o *CreateDestinationRequest) GetCustomHeaders() map[string]interface{}`

GetCustomHeaders returns the CustomHeaders field if non-nil, zero value otherwise.

### GetCustomHeadersOk

`func (o *CreateDestinationRequest) GetCustomHeadersOk() (*map[string]interface{}, bool)`

GetCustomHeadersOk returns a tuple with the CustomHeaders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomHeaders

`func (o *CreateDestinationRequest) SetCustomHeaders(v map[string]interface{})`

SetCustomHeaders sets CustomHeaders field to given value.

### HasCustomHeaders

`func (o *CreateDestinationRequest) HasCustomHeaders() bool`

HasCustomHeaders returns a boolean if a field has been set.

### GetName

`func (o *CreateDestinationRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateDestinationRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateDestinationRequest) SetName(v string)`

SetName sets Name field to given value.


### GetSigningSecret

`func (o *CreateDestinationRequest) GetSigningSecret() string`

GetSigningSecret returns the SigningSecret field if non-nil, zero value otherwise.

### GetSigningSecretOk

`func (o *CreateDestinationRequest) GetSigningSecretOk() (*string, bool)`

GetSigningSecretOk returns a tuple with the SigningSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSigningSecret

`func (o *CreateDestinationRequest) SetSigningSecret(v string)`

SetSigningSecret sets SigningSecret field to given value.

### HasSigningSecret

`func (o *CreateDestinationRequest) HasSigningSecret() bool`

HasSigningSecret returns a boolean if a field has been set.

### GetTimeoutSeconds

`func (o *CreateDestinationRequest) GetTimeoutSeconds() int32`

GetTimeoutSeconds returns the TimeoutSeconds field if non-nil, zero value otherwise.

### GetTimeoutSecondsOk

`func (o *CreateDestinationRequest) GetTimeoutSecondsOk() (*int32, bool)`

GetTimeoutSecondsOk returns a tuple with the TimeoutSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeoutSeconds

`func (o *CreateDestinationRequest) SetTimeoutSeconds(v int32)`

SetTimeoutSeconds sets TimeoutSeconds field to given value.

### HasTimeoutSeconds

`func (o *CreateDestinationRequest) HasTimeoutSeconds() bool`

HasTimeoutSeconds returns a boolean if a field has been set.

### GetUrl

`func (o *CreateDestinationRequest) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CreateDestinationRequest) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CreateDestinationRequest) SetUrl(v string)`

SetUrl sets Url field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


