# APIKey

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | **string** |  | 
**CreatedAt** | **string** |  | 
**Id** | **string** |  | 
**KeyPrefix** | **string** |  | 
**Name** | **string** |  | 
**RevokedAt** | Pointer to **string** |  | [optional] 

## Methods

### NewAPIKey

`func NewAPIKey(accountId string, createdAt string, id string, keyPrefix string, name string, ) *APIKey`

NewAPIKey instantiates a new APIKey object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAPIKeyWithDefaults

`func NewAPIKeyWithDefaults() *APIKey`

NewAPIKeyWithDefaults instantiates a new APIKey object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *APIKey) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *APIKey) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *APIKey) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.


### GetCreatedAt

`func (o *APIKey) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *APIKey) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *APIKey) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetId

`func (o *APIKey) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *APIKey) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *APIKey) SetId(v string)`

SetId sets Id field to given value.


### GetKeyPrefix

`func (o *APIKey) GetKeyPrefix() string`

GetKeyPrefix returns the KeyPrefix field if non-nil, zero value otherwise.

### GetKeyPrefixOk

`func (o *APIKey) GetKeyPrefixOk() (*string, bool)`

GetKeyPrefixOk returns a tuple with the KeyPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyPrefix

`func (o *APIKey) SetKeyPrefix(v string)`

SetKeyPrefix sets KeyPrefix field to given value.


### GetName

`func (o *APIKey) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *APIKey) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *APIKey) SetName(v string)`

SetName sets Name field to given value.


### GetRevokedAt

`func (o *APIKey) GetRevokedAt() string`

GetRevokedAt returns the RevokedAt field if non-nil, zero value otherwise.

### GetRevokedAtOk

`func (o *APIKey) GetRevokedAtOk() (*string, bool)`

GetRevokedAtOk returns a tuple with the RevokedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevokedAt

`func (o *APIKey) SetRevokedAt(v string)`

SetRevokedAt sets RevokedAt field to given value.

### HasRevokedAt

`func (o *APIKey) HasRevokedAt() bool`

HasRevokedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


