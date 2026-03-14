# AccountBootstrapData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Account** | [**Account**](Account.md) |  | 
**ApiKey** | [**APIKeyWithSecret**](APIKeyWithSecret.md) |  | 

## Methods

### NewAccountBootstrapData

`func NewAccountBootstrapData(account Account, apiKey APIKeyWithSecret, ) *AccountBootstrapData`

NewAccountBootstrapData instantiates a new AccountBootstrapData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountBootstrapDataWithDefaults

`func NewAccountBootstrapDataWithDefaults() *AccountBootstrapData`

NewAccountBootstrapDataWithDefaults instantiates a new AccountBootstrapData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccount

`func (o *AccountBootstrapData) GetAccount() Account`

GetAccount returns the Account field if non-nil, zero value otherwise.

### GetAccountOk

`func (o *AccountBootstrapData) GetAccountOk() (*Account, bool)`

GetAccountOk returns a tuple with the Account field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccount

`func (o *AccountBootstrapData) SetAccount(v Account)`

SetAccount sets Account field to given value.


### GetApiKey

`func (o *AccountBootstrapData) GetApiKey() APIKeyWithSecret`

GetApiKey returns the ApiKey field if non-nil, zero value otherwise.

### GetApiKeyOk

`func (o *AccountBootstrapData) GetApiKeyOk() (*APIKeyWithSecret, bool)`

GetApiKeyOk returns a tuple with the ApiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiKey

`func (o *AccountBootstrapData) SetApiKey(v APIKeyWithSecret)`

SetApiKey sets ApiKey field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


