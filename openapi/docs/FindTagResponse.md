# FindTagResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]TagResponse1**](TagResponse1.md) |  | 
**Links** | [**SelfLinks**](SelfLinks.md) |  | 

## Methods

### NewFindTagResponse

`func NewFindTagResponse(data []TagResponse1, links SelfLinks, ) *FindTagResponse`

NewFindTagResponse instantiates a new FindTagResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFindTagResponseWithDefaults

`func NewFindTagResponseWithDefaults() *FindTagResponse`

NewFindTagResponseWithDefaults instantiates a new FindTagResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *FindTagResponse) GetData() []TagResponse1`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *FindTagResponse) GetDataOk() (*[]TagResponse1, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *FindTagResponse) SetData(v []TagResponse1)`

SetData sets Data field to given value.


### GetLinks

`func (o *FindTagResponse) GetLinks() SelfLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *FindTagResponse) GetLinksOk() (*SelfLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *FindTagResponse) SetLinks(v SelfLinks)`

SetLinks sets Links field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


