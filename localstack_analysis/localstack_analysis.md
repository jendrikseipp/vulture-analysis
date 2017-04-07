This report has been obtained by running vulture over [localstack](https://github.com/atlassian/localstack).
vulture finds out dead (unused) python code and helps you in trimming down 
your codebase. Please have a look at [vulture](https://github.com/jendrikseipp/vulture) for more information on the same.

#### Perhaps, since they are provided as a part of API, they are user targeted.
```
localstack/localstack/dashboard/api.py:69: Unused function 'send_static'
localstack/localstack/mock/apis/dynamodbstreams_api.py:28: Unused function 'post_request'
localstack/localstack/mock/apis/firehose_api.py:40: Unused function 'add_s3_destination'
localstack/localstack/mock/apis/lambda_api.py:335: Unused function 'update_function_code'
localstack/localstack/mock/apis/lambda_api.py:365: Unused function 'invoke_function'
localstack/localstack/mock/apis/lambda_api.py:390: Unused function 'list_event_source_mappings'
```
#### vulture sometimes reports False positives, so please have a look, before removing the code.
```
localstack/localstack/mock/generic_proxy.py:32: Unused function 'do_GET'
localstack/localstack/mock/generic_proxy.py:36: Unused function 'do_PUT'
localstack/localstack/mock/generic_proxy.py:41: Unused function 'do_POST'
localstack/localstack/mock/generic_proxy.py:46: Unused function 'do_DELETE'
localstack/localstack/mock/generic_proxy.py:50: Unused function 'do_HEAD'
localstack/localstack/mock/generic_proxy.py:54: Unused function 'do_PATCH'
localstack/localstack/utils/aws/aws_models.py:86: Unused function 'destroy'
localstack/localstack/utils/aws/aws_stack.py:84: Unused function 'create_environment_file'
localstack/localstack/utils/aws/aws_stack.py:187: Unused function 'base64Encode'
localstack/localstack/utils/aws/aws_stack.py:192: Unused function 'base64Decode'
localstack/localstack/utils/aws/aws_stack.py:246: Unused function 'sqs_queue_arn'
localstack/localstack/utils/aws/aws_stack.py:364: Unused function 'delete_all_elasticsearch_indices'
localstack/localstack/utils/common.py:86: Unused function 'is_killed'
localstack/localstack/utils/kinesis/kinesis_connector.py:109: Unused function 'run_processor'
```
#### git grep also confirms to this result:
```
localstack/localstack/constants.py:91: Unused variable 'LAMBDA_MAIN_SCRIPT_NAME'
```

#### This might be intentional perhaps to replicate some environment.
```
localstack/tests/test_integration.py:181: Unused attribute 'KILLED'
```

