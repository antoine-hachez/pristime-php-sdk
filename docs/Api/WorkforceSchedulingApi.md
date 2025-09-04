# OpenAPI\Client\WorkforceSchedulingApi

All URIs are relative to https://pristime.com, except if the operation defines another base path.

| Method | HTTP request | Description |
| ------------- | ------------- | ------------- |
| [**createScheduleJob()**](WorkforceSchedulingApi.md#createScheduleJob) | **POST** /api/v2/schedule-jobs | Create Workforce Schedule Optimization Job |
| [**getScheduleJob()**](WorkforceSchedulingApi.md#getScheduleJob) | **GET** /api/v2/schedule-jobs/{job_id} | Get Scheduling Job Status and Results |


## `createScheduleJob()`

```php
createScheduleJob($schedule_state): \OpenAPI\Client\Model\ScheduleJobResponse
```

Create Workforce Schedule Optimization Job

Initiates an asynchronous workforce scheduling optimization process. Takes workers, shifts, staffing demands, and constraints as input, then runs an optimization algorithm to find optimal shift assignments. Returns immediately with a job ID for tracking progress.

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');


// Configure API key authorization: APIKeyHeader
$config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKey('Pristime-API-Key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Pristime-API-Key', 'Bearer');


$apiInstance = new OpenAPI\Client\Api\WorkforceSchedulingApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$schedule_state = new \OpenAPI\Client\Model\ScheduleState(); // \OpenAPI\Client\Model\ScheduleState

try {
    $result = $apiInstance->createScheduleJob($schedule_state);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling WorkforceSchedulingApi->createScheduleJob: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **schedule_state** | [**\OpenAPI\Client\Model\ScheduleState**](../Model/ScheduleState.md)|  | |

### Return type

[**\OpenAPI\Client\Model\ScheduleJobResponse**](../Model/ScheduleJobResponse.md)

### Authorization

[APIKeyHeader](../../README.md#APIKeyHeader)

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `getScheduleJob()`

```php
getScheduleJob($job_id): \OpenAPI\Client\Model\ScheduleJobResponse
```

Get Scheduling Job Status and Results

Retrieves the current status and results of a workforce scheduling optimization job. Returns the job status ('running', 'completed', or 'failed') and optimization results if completed.

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');


// Configure API key authorization: APIKeyHeader
$config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKey('Pristime-API-Key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Pristime-API-Key', 'Bearer');


$apiInstance = new OpenAPI\Client\Api\WorkforceSchedulingApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$job_id = 'job_id_example'; // string

try {
    $result = $apiInstance->getScheduleJob($job_id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling WorkforceSchedulingApi->getScheduleJob: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **job_id** | **string**|  | |

### Return type

[**\OpenAPI\Client\Model\ScheduleJobResponse**](../Model/ScheduleJobResponse.md)

### Authorization

[APIKeyHeader](../../README.md#APIKeyHeader)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)
