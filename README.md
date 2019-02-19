# Invoice

Website containing buildo's invocing data

## Update

Edit whatever you need, then run

```sh
aws s3 sync . s3://invoice.our.buildo.io --acl public-read --region eu-central-1 --exclude ".git/*"
```

