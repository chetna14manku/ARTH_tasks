First Create ansible-vault "aws-secret.yml" and put aws credentials in it.
- accesskey:
- secretkey:

Then run "aws.yml" playbook
- It will automatically store the IP of AWS Instances in "inventory"

Then run "k8s-master.yml"
