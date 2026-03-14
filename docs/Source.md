# Source

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | **string** |  | 
**AuthMode** | **string** |  | 
**CreatedAt** | **string** |  | 
**CustomDomainId** | Pointer to **string** |  | [optional] 
**Id** | **string** |  | 
**IngestUrl** | **string** |  | 
**Name** | **string** |  | 
**PathToken** | **string** |  | 
**Status** | **string** |  | 
**VerificationConfig** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewSource

`func NewSource(accountId string, authMode string, createdAt string, id string, ingestUrl string, name string, pathToken string, status string, ) *Source`

NewSource instantiates a new Source object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSourceWithDefaults

`func NewSourceWithDefaults() *Source`

NewSourceWithDefaults instantiates a new Source object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *Source) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *Source) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *Source) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.


### GetAuthMode

`func (o *Source) GetAuthMode() string`

GetAuthMode returns the AuthMode field if non-nil, zero value otherwise.

### GetAuthModeOk

`func (o *Source) GetAuthModeOk() (*string, bool)`

GetAuthModeOk returns a tuple with the AuthMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthMode

`func (o *Source) SetAuthMode(v string)`

SetAuthMode sets AuthMode field to given value.


### GetCreatedAt

`func (o *Source) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Source) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Source) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCustomDomainId

`func (o *Source) GetCustomDomainId() string`

GetCustomDomainId returns the CustomDomainId field if non-nil, zero value otherwise.

### GetCustomDomainIdOk

`func (o *Source) GetCustomDomainIdOk() (*string, bool)`

GetCustomDomainIdOk returns a tuple with the CustomDomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomDomainId

`func (o *Source) SetCustomDomainId(v string)`

SetCustomDomainId sets CustomDomainId field to given value.

### HasCustomDomainId

`func (o *Source) HasCustomDomainId() bool`

HasCustomDomainId returns a boolean if a field has been set.

### GetId

`func (o *Source) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Source) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Source) SetId(v string)`

SetId sets Id field to given value.


### GetIngestUrl

`func (o *Source) GetIngestUrl() string`

GetIngestUrl returns the IngestUrl field if non-nil, zero value otherwise.

### GetIngestUrlOk

`func (o *Source) GetIngestUrlOk() (*string, bool)`

GetIngestUrlOk returns a tuple with the IngestUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIngestUrl

`func (o *Source) SetIngestUrl(v string)`

SetIngestUrl sets IngestUrl field to given value.


### GetName

`func (o *Source) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Source) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Source) SetName(v string)`

SetName sets Name field to given value.


### GetPathToken

`func (o *Source) GetPathToken() string`

GetPathToken returns the PathToken field if non-nil, zero value otherwise.

### GetPathTokenOk

`func (o *Source) GetPathTokenOk() (*string, bool)`

GetPathTokenOk returns a tuple with the PathToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPathToken

`func (o *Source) SetPathToken(v string)`

SetPathToken sets PathToken field to given value.


### GetStatus

`func (o *Source) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Source) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Source) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetVerificationConfig

`func (o *Source) GetVerificationConfig() map[string]interface{}`

GetVerificationConfig returns the VerificationConfig field if non-nil, zero value otherwise.

### GetVerificationConfigOk

`func (o *Source) GetVerificationConfigOk() (*map[string]interface{}, bool)`

GetVerificationConfigOk returns a tuple with the VerificationConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerificationConfig

`func (o *Source) SetVerificationConfig(v map[string]interface{})`

SetVerificationConfig sets VerificationConfig field to given value.

### HasVerificationConfig

`func (o *Source) HasVerificationConfig() bool`

HasVerificationConfig returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


