# DestinationPreset

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AuthHeader** | Pointer to **string** | for api_key type | [optional] 
**AuthLabel** | Pointer to **string** | e.g. \&quot;Bot Token\&quot;, \&quot;API Key\&quot; | [optional] 
**AuthType** | Pointer to **string** | \&quot;none\&quot;, \&quot;bearer\&quot;, \&quot;api_key\&quot; | [optional] 
**Category** | Pointer to **string** |  | [optional] 
**Color** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**DocsUrl** | Pointer to **string** |  | [optional] 
**ExtraHeaders** | Pointer to **map[string]string** |  | [optional] 
**Id** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**UrlHint** | Pointer to **string** |  | [optional] 

## Methods

### NewDestinationPreset

`func NewDestinationPreset() *DestinationPreset`

NewDestinationPreset instantiates a new DestinationPreset object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDestinationPresetWithDefaults

`func NewDestinationPresetWithDefaults() *DestinationPreset`

NewDestinationPresetWithDefaults instantiates a new DestinationPreset object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuthHeader

`func (o *DestinationPreset) GetAuthHeader() string`

GetAuthHeader returns the AuthHeader field if non-nil, zero value otherwise.

### GetAuthHeaderOk

`func (o *DestinationPreset) GetAuthHeaderOk() (*string, bool)`

GetAuthHeaderOk returns a tuple with the AuthHeader field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthHeader

`func (o *DestinationPreset) SetAuthHeader(v string)`

SetAuthHeader sets AuthHeader field to given value.

### HasAuthHeader

`func (o *DestinationPreset) HasAuthHeader() bool`

HasAuthHeader returns a boolean if a field has been set.

### GetAuthLabel

`func (o *DestinationPreset) GetAuthLabel() string`

GetAuthLabel returns the AuthLabel field if non-nil, zero value otherwise.

### GetAuthLabelOk

`func (o *DestinationPreset) GetAuthLabelOk() (*string, bool)`

GetAuthLabelOk returns a tuple with the AuthLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthLabel

`func (o *DestinationPreset) SetAuthLabel(v string)`

SetAuthLabel sets AuthLabel field to given value.

### HasAuthLabel

`func (o *DestinationPreset) HasAuthLabel() bool`

HasAuthLabel returns a boolean if a field has been set.

### GetAuthType

`func (o *DestinationPreset) GetAuthType() string`

GetAuthType returns the AuthType field if non-nil, zero value otherwise.

### GetAuthTypeOk

`func (o *DestinationPreset) GetAuthTypeOk() (*string, bool)`

GetAuthTypeOk returns a tuple with the AuthType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthType

`func (o *DestinationPreset) SetAuthType(v string)`

SetAuthType sets AuthType field to given value.

### HasAuthType

`func (o *DestinationPreset) HasAuthType() bool`

HasAuthType returns a boolean if a field has been set.

### GetCategory

`func (o *DestinationPreset) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *DestinationPreset) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *DestinationPreset) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *DestinationPreset) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetColor

`func (o *DestinationPreset) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *DestinationPreset) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *DestinationPreset) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *DestinationPreset) HasColor() bool`

HasColor returns a boolean if a field has been set.

### GetDescription

`func (o *DestinationPreset) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *DestinationPreset) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *DestinationPreset) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *DestinationPreset) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDocsUrl

`func (o *DestinationPreset) GetDocsUrl() string`

GetDocsUrl returns the DocsUrl field if non-nil, zero value otherwise.

### GetDocsUrlOk

`func (o *DestinationPreset) GetDocsUrlOk() (*string, bool)`

GetDocsUrlOk returns a tuple with the DocsUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocsUrl

`func (o *DestinationPreset) SetDocsUrl(v string)`

SetDocsUrl sets DocsUrl field to given value.

### HasDocsUrl

`func (o *DestinationPreset) HasDocsUrl() bool`

HasDocsUrl returns a boolean if a field has been set.

### GetExtraHeaders

`func (o *DestinationPreset) GetExtraHeaders() map[string]string`

GetExtraHeaders returns the ExtraHeaders field if non-nil, zero value otherwise.

### GetExtraHeadersOk

`func (o *DestinationPreset) GetExtraHeadersOk() (*map[string]string, bool)`

GetExtraHeadersOk returns a tuple with the ExtraHeaders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraHeaders

`func (o *DestinationPreset) SetExtraHeaders(v map[string]string)`

SetExtraHeaders sets ExtraHeaders field to given value.

### HasExtraHeaders

`func (o *DestinationPreset) HasExtraHeaders() bool`

HasExtraHeaders returns a boolean if a field has been set.

### GetId

`func (o *DestinationPreset) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DestinationPreset) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DestinationPreset) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *DestinationPreset) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *DestinationPreset) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *DestinationPreset) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *DestinationPreset) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *DestinationPreset) HasName() bool`

HasName returns a boolean if a field has been set.

### GetUrlHint

`func (o *DestinationPreset) GetUrlHint() string`

GetUrlHint returns the UrlHint field if non-nil, zero value otherwise.

### GetUrlHintOk

`func (o *DestinationPreset) GetUrlHintOk() (*string, bool)`

GetUrlHintOk returns a tuple with the UrlHint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrlHint

`func (o *DestinationPreset) SetUrlHint(v string)`

SetUrlHint sets UrlHint field to given value.

### HasUrlHint

`func (o *DestinationPreset) HasUrlHint() bool`

HasUrlHint returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


