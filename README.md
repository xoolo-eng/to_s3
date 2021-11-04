# to_s3

```
export FLASK_APP='backend'
export REGION='eu-central-1'
export ACCESS_KEY='...'
export SECRET_KEY='...'
export BUCKET_NAME='...'
```
`gunicorn --bind 127.0.0.1:5000 wsgi:app`