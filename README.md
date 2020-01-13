# chaws
Change aws default profile to you specify profile.

## Intall
```
curl -O https://github.com/daydayjuice/chaws/blob/master/chaws
chmod +x chaws
mv chaws /usr/local/bin/
```

## Usage
For example there is aws profile like below:
```
[default]
aws_access_key_id = DEVXXXXXXXXX
aws_secret_access_key = Dxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

[dev]
aws_access_key_id = DEVXXXXXXXXX
aws_secret_access_key = Dxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

[stg]
aws_access_key_id = STGXXXXXXXXX
aws_secret_access_key  = Sxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

[prd]
aws_access_key_id = PRDXXXXXXXXX
aws_secret_access_key  = Pxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

```
So we just need to execute below command to change default profile
```
chaws stg 
```

