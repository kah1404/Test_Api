# TestApi.AppLeadsApi

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**apiAppLeadsByCountryIdGet**](AppLeadsApi.md#apiAppLeadsByCountryIdGet) | **GET** /api/AppLeads/{countryId} | 


<a name="apiAppLeadsByCountryIdGet"></a>
# **apiAppLeadsByCountryIdGet**
> apiAppLeadsByCountryIdGet(countryId)



### Example
```javascript
var TestApi = require('test_api');

var apiInstance = new TestApi.AppLeadsApi();

var countryId = 56; // Number | 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
};
apiInstance.apiAppLeadsByCountryIdGet(countryId, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **countryId** | **Number**|  | 

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

