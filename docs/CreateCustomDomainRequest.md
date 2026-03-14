# CreateCustomDomainRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Domain** | **string** |  | 
**Type** | Pointer to **string** |  | [optional] 

## Methods

### NewCreateCustomDomainRequest

`func NewCreateCustomDomainRequest(domain string, ) *CreateCustomDomainRequest`

NewCreateCustomDomainRequest instantiates a new CreateCustomDomainRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCustomDomainRequestWithDefaults

`func NewCreateCustomDomainRequestWithDefaults() *CreateCustomDomainRequest`

NewCreateCustomDomainRequestWithDefaults instantiates a new CreateCustomDomainRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomain

`func (o *CreateCustomDomainRequest) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *CreateCustomDomainRequest) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *CreateCustomDomainRequest) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetType

`func (o *CreateCustomDomainRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateCustomDomainRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateCustomDomainRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *CreateCustomDomainRequest) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


