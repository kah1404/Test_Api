# TestApi.CompanyApi

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**apiCompaniesGet**](CompanyApi.md#apiCompaniesGet) | **GET** /api/companies | 


<a name="apiCompaniesGet"></a>
# **apiCompaniesGet**
> apiCompaniesGet()



### Example
```javascript
var TestApi = require('test_api');

var apiInstance = new TestApi.CompanyApi();

var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
};
apiInstance.apiCompaniesGet(callback);
```

### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

