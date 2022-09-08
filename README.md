```
# Export GOOGLE_APPLICATION_CREDENTIALS
export GOOGLE_APPLICATION_CREDENTIALS="./key/favorable-bison-352010-28675b5e7bc4.json"
```

```
# Create bucket
gsutil mb gs://bucket-tfstate-da0769f7365b269e

# Delete bucket
gcloud alpha storage rm --recursive gs://bucket-tfstate-da0769f7365b269e
```

```
terraform init
terraform plan
terraform apply
```

```
terraform fmt
```
