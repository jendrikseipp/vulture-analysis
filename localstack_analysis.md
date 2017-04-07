# vullture report for [localstack](https://github.com/atlassian/localstack)

We used [vulture](https://github.com/jendrikseipp/vulture) to search
for unused code in your project. You can find the report below. It 
would be great if you could give us feedback about which items are 
actually used or unused. This would allow us to improve vulture and
ideally it also helps you to remove obsolete code or even find typos 
and bugs.

### Command
```
vulture localstack --exclude=localstack/.venv/
```

### Raw results
```
localstack/localstack/constants.py:91: Unused variable 'LAMBDA_MAIN_SCRIPT_NAME'
localstack/localstack/dashboard/api.py:14: Unused function 'spec'
localstack/localstack/dashboard/api.py:64: Unused function 'hello'
localstack/localstack/dashboard/api.py:69: Unused function 'send_static'
localstack/localstack/dashboard/infra.py:224: Unused attribute 'count'
localstack/localstack/dashboard/infra.py:225: Unused attribute 'bytes'
localstack/localstack/dashboard/infra.py:226: Unused attribute 'created_at'
localstack/localstack/mock/apis/dynamodbstreams_api.py:8: Unused import '__init__'
localstack/localstack/mock/apis/dynamodbstreams_api.py:28: Unused function 'post_request'
localstack/localstack/mock/apis/firehose_api.py:40: Unused function 'add_s3_destination'
localstack/localstack/mock/apis/lambda_api.py:265: Unused function 'get_function'
localstack/localstack/mock/apis/lambda_api.py:294: Unused function 'list_functions'
localstack/localstack/mock/apis/lambda_api.py:309: Unused function 'delete_function'
localstack/localstack/mock/apis/lambda_api.py:335: Unused function 'update_function_code'
localstack/localstack/mock/apis/lambda_api.py:350: Unused function 'update_function_configuration'
localstack/localstack/mock/apis/lambda_api.py:365: Unused function 'invoke_function'
localstack/localstack/mock/apis/lambda_api.py:390: Unused function 'list_event_source_mappings'
localstack/localstack/mock/generic_proxy.py:32: Unused function 'do_GET'
localstack/localstack/mock/generic_proxy.py:36: Unused function 'do_PUT'
localstack/localstack/mock/generic_proxy.py:41: Unused function 'do_POST'
localstack/localstack/mock/generic_proxy.py:46: Unused function 'do_DELETE'
localstack/localstack/mock/generic_proxy.py:50: Unused function 'do_HEAD'
localstack/localstack/mock/generic_proxy.py:54: Unused function 'do_PATCH'
localstack/localstack/mock/generic_proxy.py:104: Unused function 'log_message'
localstack/localstack/mock/infra.py:50: Unused variable 'frame'
localstack/localstack/mock/proxy/dynamodb_listener.py:23: Unused variable 'response_data'
localstack/localstack/mock/proxy/kinesis_listener.py:46: Unused attribute '_content'
localstack/localstack/utils/aws/aws_models.py:57: Unused variable 'amount'
localstack/localstack/utils/aws/aws_models.py:86: Unused function 'destroy'
localstack/localstack/utils/aws/aws_models.py:116: Unused function 'sort'
localstack/localstack/utils/aws/aws_models.py:129: Unused function 'max'
localstack/localstack/utils/aws/aws_models.py:198: Unused attribute 'indexes'
localstack/localstack/utils/aws/aws_models.py:218: Unused attribute 'trigger'
localstack/localstack/utils/aws/aws_stack.py:67: Unused function 'from_json'
localstack/localstack/utils/aws/aws_stack.py:84: Unused function 'create_environment_file'
localstack/localstack/utils/aws/aws_stack.py:187: Unused function 'base64Encode'
localstack/localstack/utils/aws/aws_stack.py:192: Unused function 'base64Decode'
localstack/localstack/utils/aws/aws_stack.py:246: Unused function 'sqs_queue_arn'
localstack/localstack/utils/aws/aws_stack.py:252: Unused function 'sns_topic_arn'
localstack/localstack/utils/aws/aws_stack.py:364: Unused function 'delete_all_elasticsearch_indices'
localstack/localstack/utils/common.py:86: Unused function 'is_killed'
localstack/localstack/utils/common.py:95: Unused variable 'SIGKILL'
localstack/localstack/utils/kinesis/kclipy_helper.py:8: Unused import 'argparse'
localstack/localstack/utils/kinesis/kclipy_helper.py:10: Unused import 'samples'
localstack/localstack/utils/kinesis/kinesis_connector.py:64: Unused function 'initialize'
localstack/localstack/utils/kinesis/kinesis_connector.py:84: Unused function 'shutdown'
localstack/localstack/utils/kinesis/kinesis_connector.py:109: Unused function 'run_processor'
localstack/localstack/utils/kinesis/kinesis_connector.py:157: Unused attribute 'severe'
localstack/localstack/utils/kinesis/kinesis_connector.py:158: Unused attribute 'fatal'
localstack/localstack/utils/kinesis/kinesis_connector.py:162: Unused variable 'cls'
localstack/setup.py:7: Unused import 'setuptools'
localstack/tests/lambdas/lambda_integration.py:12: Unused function '_deserialize_n'
localstack/tests/lambdas/lambda_integration.py:15: Unused function '_deserialize_b'
localstack/tests/test_integration.py:181: Unused attribute 'KILLED'
localstack/tests/test_kinesis_errors.py:3: Unused import 'assert_raises'
localstack/tests/test_kinesis_errors.py:4: Unused import 'ClientError'

```

#### Perhaps, since they are provided as a part of API, they are user targeted.
```
localstack/localstack/dashboard/api.py:69: Unused function 'send_static'
localstack/localstack/mock/apis/dynamodbstreams_api.py:28: Unused function 'post_request'
localstack/localstack/mock/apis/firehose_api.py:40: Unused function 'add_s3_destination'
localstack/localstack/mock/apis/lambda_api.py:335: Unused function 'update_function_code'
localstack/localstack/mock/apis/lambda_api.py:365: Unused function 'invoke_function'
localstack/localstack/mock/apis/lambda_api.py:390: Unused function 'list_event_source_mappings'
```

#### unused code or False positives
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

