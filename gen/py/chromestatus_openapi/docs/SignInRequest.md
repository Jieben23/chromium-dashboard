# SignInRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**credential** | **str** | The credential generated by Sign-In With Google. | 

## Example

```python
from chromestatus_openapi.models.sign_in_request import SignInRequest

# TODO update the JSON string below
json = "{}"
# create an instance of SignInRequest from a JSON string
sign_in_request_instance = SignInRequest.from_json(json)
# print the JSON string representation of the object
print(SignInRequest.to_json())

# convert the object into a dict
sign_in_request_dict = sign_in_request_instance.to_dict()
# create an instance of SignInRequest from a dict
sign_in_request_from_dict = SignInRequest.from_dict(sign_in_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

