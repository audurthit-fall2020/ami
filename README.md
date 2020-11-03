# AMI
- Builds AMI with Node.js and codedepoly agent installed
# Packer Validate:
- `packer validate ubuntu18.ami.json`
# Packer Build:
- Export Access key and Secret Key  
 `export AWS_ACCESS_KEY_ID="$aws_access_key"`  
 `export AWS_SECRET_ACCESS_KEY="$aws_secret_key"`  
 `export AWS_DEFAULT_REGION="us-east-1"`  
- Run Packer Build  
 `packer build ubuntu18.ami.json`
