# APIKeyWithSecret

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**AccountId** | **string** |  | 
**UserId** | Pointer to **string** |  | [optional] 
**Name** | **string** |  | 
**Role** | **string** |  | 
**KeyPrefix** | **string** |  | 
**CreatedAt** | **string** |  | 
**RevokedAt** | Pointer to **string** |  | [optional] 
**Key** | **string** | Full plaintext key — returned once at creation time only. | 

## Methods

### NewAPIKeyWithSecret

`func NewAPIKeyWithSecret(id string, accountId string, name string, role string, keyPrefix string, createdAt string, key string, ) *APIKeyWithSecret`

NewAPIKeyWithSecret instantiates a new APIKeyWithSecret object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAPIKeyWithSecretWithDefaults

`func NewAPIKeyWithSecretWithDefaults() *APIKeyWithSecret`

NewAPIKeyWithSecretWithDefaults instantiates a new APIKeyWithSecret object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *APIKeyWithSecret) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *APIKeyWithSecret) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *APIKeyWithSecret) SetId(v string)`

SetId sets Id field to given value.


### GetAccountId

`func (o *APIKeyWithSecret) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *APIKeyWithSecret) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *APIKeyWithSecret) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.


### GetUserId

`func (o *APIKeyWithSecret) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *APIKeyWithSecret) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *APIKeyWithSecret) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *APIKeyWithSecret) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetName

`func (o *APIKeyWithSecret) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *APIKeyWithSecret) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *APIKeyWithSecret) SetName(v string)`

SetName sets Name field to given value.


### GetRole

`func (o *APIKeyWithSecret) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *APIKeyWithSecret) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *APIKeyWithSecret) SetRole(v string)`

SetRole sets Role field to given value.


### GetKeyPrefix

`func (o *APIKeyWithSecret) GetKeyPrefix() string`

GetKeyPrefix returns the KeyPrefix field if non-nil, zero value otherwise.

### GetKeyPrefixOk

`func (o *APIKeyWithSecret) GetKeyPrefixOk() (*string, bool)`

GetKeyPrefixOk returns a tuple with the KeyPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyPrefix

`func (o *APIKeyWithSecret) SetKeyPrefix(v string)`

SetKeyPrefix sets KeyPrefix field to given value.


### GetCreatedAt

`func (o *APIKeyWithSecret) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *APIKeyWithSecret) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *APIKeyWithSecret) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetRevokedAt

`func (o *APIKeyWithSecret) GetRevokedAt() string`

GetRevokedAt returns the RevokedAt field if non-nil, zero value otherwise.

### GetRevokedAtOk

`func (o *APIKeyWithSecret) GetRevokedAtOk() (*string, bool)`

GetRevokedAtOk returns a tuple with the RevokedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevokedAt

`func (o *APIKeyWithSecret) SetRevokedAt(v string)`

SetRevokedAt sets RevokedAt field to given value.

### HasRevokedAt

`func (o *APIKeyWithSecret) HasRevokedAt() bool`

HasRevokedAt returns a boolean if a field has been set.

### GetKey

`func (o *APIKeyWithSecret) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *APIKeyWithSecret) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *APIKeyWithSecret) SetKey(v string)`

SetKey sets Key field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


