# Instructions for Launching Instance

1. Use the following commands to connect to your AWS Account. Get this info or create it in IAM
```
export AWS_ACCESS_KEY_ID='access_key'
export AWS_SECRET_ACCESS_KEY='secret_key'
```
2. Update the vars in the `web_server.yml` to reflect your AWS VPC
3. Add ssh pem file to your keychain
```
ssh-add -K <pem file>
```
4. Run the playbook