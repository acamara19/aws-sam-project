# aws-sam-project

```Project_Structure
├── README.md
├── __init__.py
├── aws_resources
│   ├── api_gtw
│   ├── dynamodb
│   ├── iam
│   └── s3_buckets
│       ├── scripts
│       │   ├── __init__.py
│       │   ├── app.py
│       │   └── requirement.txt
│       └── template.yaml
├── cicd
│   ├── assume-role.sh
│   ├── codepipeline.yaml
│   └── pipeline
│       ├── buildspec_build_package.yml
│       ├── buildspec_deploy.yml
│       ├── buildspec_feature.yml
│       ├── buildspec_integration_test.yml
│       └── buildspec_unit_test.yml
├── events
│   └── event.json
├── hello_world
│   ├── __init__.py
│   ├── app.py
│   └── requirements.txt
├── project_struture.md
├── samconfig.toml
├── template.yaml
└── tests
    ├── __init__.py
    ├── integration
    │   ├── __init__.py
    │   └── test_api_gateway.py
    ├── requirements.txt
    └── unit
        ├── __init__.py
        └── test_handler.py

14 directories, 26 files
```
