1. Create a workspace using this repo
2. Open a terminal and run `podman run -it --rm -p 4566:4566 localstack/localstack:latest`
3. Open another terminal and run
```
pip install awscli-local
awslocal s3 mb s3://mysamplebucket
```
