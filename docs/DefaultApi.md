# SimpleInventoryApi.DefaultApi

All URIs are relative to *https://fdatek.2ce.de:5443/fcomputer/av_public/1.0.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**serviceordersGet**](DefaultApi.md#serviceordersGet) | **GET** /serviceorders | Get all serviceorders for customer


<a name="serviceordersGet"></a>
# **serviceordersGet**
> [ServiceOrder] serviceordersGet()

Get all serviceorders for customer

Get all serviceorders for customer

### Example
```javascript
var SimpleInventoryApi = require('simple_inventory_api');

var apiInstance = new SimpleInventoryApi.DefaultApi();

var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
apiInstance.serviceordersGet(callback);
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**[ServiceOrder]**](ServiceOrder.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

