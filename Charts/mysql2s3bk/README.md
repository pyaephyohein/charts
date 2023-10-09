  ### Example values
  
  ```yaml
  
  envFrom:
  - secretRef:
      name: <release-name>-mysql2s3-secret #update secret name
  configs:
    suspend:
      enabled: true
    secret_env:
      MYSQL_USER: mysql
      MYSQL_PASSWORD: mysql-password
      MYSQL_PORT: "3306" ## add quotes 
      MYSQL_HOST: localhost
      BUCKET_NAME: s3bucket
      AWS_ACCESS_KEY_ID: awsacessid
      AWS_SECRET_ACCESS_KEY: awsaccesskey
      AWS_DEFAULT_REGION: ap-southeast-1
```
