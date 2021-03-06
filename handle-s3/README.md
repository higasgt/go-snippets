# handle-s3

## Getting Started
- access to aws.amazon.com and get iam api access keys (access_key, secret_access_key)

- install dependency packages
```bash
$ gom install
```

- set your s3 configuration in .env

```bash
cp .env.sample .env
vi .env
```

- run

```bash
go run app.go
```

## Feature
- upload file to s3
- other
    - As a package manager, I use gom.

### Todo
- download file from s3
- get lists of bucket or objects

## Ref
### Relevant to S3
- [Using Sessions to Configure Service Clients in the AWS SDK for Go](https://docs.aws.amazon.com/sdk-for-go/v1/developer-guide/sessions.html)
- [NoCredentialProviders: no valid providers in chain. Deprecated. ](https://github.com/aws/aws-sdk-go/issues/992)
- [s3manager/Downloader](https://docs.aws.amazon.com/sdk-for-go/api/service/s3/s3manager/#Downloader.Download)

#### public article(untrusted)
- [GoでAWSのS3からファイルをダウンロードする](https://qiita.com/unikk/items/02282a1f219bf4715c4a)