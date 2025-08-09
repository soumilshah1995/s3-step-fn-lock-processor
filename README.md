# s3-step-fn-lock-processor
s3-step-fn-lock-processor

<img width="330" height="356" alt="image" src="https://github.com/user-attachments/assets/a1520b31-69f1-4524-a779-3ec4fc41779a" />


### Sample Fire Payload 
```
{
  "bucket_name": "<>",
  "concurrency_limit": 1,
  "counter_name": "active_locks.json",
  "lock_timeout_minutes": 15
}
```


## Deploy
```
npm install --save-dev serverless-step-functions

sls deploy
```

