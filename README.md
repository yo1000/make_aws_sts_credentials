# make_aws_sts_credentials

## Requirements
- Python 3.x
- AWS CLI
- Boto3

## How to Use
1. Install Python (https://www.python.org/downloads/)
2. Install AWS CLI
    - Linux (https://docs.aws.amazon.com/ja_jp/cli/latest/userguide/install-linux.html)
    - Windows (https://docs.aws.amazon.com/ja_jp/cli/latest/userguide/install-windows.html#awscli-install-windows-pip)
    - macOS (https://docs.aws.amazon.com/ja_jp/cli/latest/userguide/install-macos.html#awscli-install-osx-pip)
3. Install Boto3
4. Configure AWS Credentials
5. Run script

### Install Boto3
```
$ pip install boto3
```

### Configure AWS Credentials
```
$ aws configure
AWS Access Key ID [None]: ABCDEFGHIJKLMNOPQRST
AWS Secret Access Key [None]: abcdefghijABCDEFGHIJ1234567890abcdefghij
Default region name [ap-northeast-1]:
Default output format [None]:
```

### Run script
```
$ python make_aws_sts_credentials.py --profile default --account 123456789012 --username iam-username
Token code: 123456
```
