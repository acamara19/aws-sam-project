aws-sam-project
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
│   ├── app_pipeline
│   └── infra_pipeline
│       ├── assume-role.sh
│       ├── codepipeline.yaml
│       └── pipeline
│           ├── buildspec_build_package.yml
│           ├── buildspec_deploy.yml
│           ├── buildspec_feature.yml
│           ├── buildspec_integration_test.yml
│           └── buildspec_unit_test.yml
├── events
│   └── event.json
├── hello_world
│   ├── __init__.py
│   ├── app.py
│   └── requirements.txt
├── project_struture.md
├── samconfig.toml
├── temp
├── template.yaml
└── tests
    ├── __init__.py
    ├── codepipeline.yaml
    ├── integration
    │   ├── __init__.py
    │   └── test_api_gateway.py
    ├── requirements.txt
    └── unit
        ├── __init__.py
        └── test_handler.py

17 directories, 27 files
