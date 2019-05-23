# aws-networking-bastion

#### How to run it?

```
docker run --rm -it \
    -e AWS_ACCESS_KEY_ID=xxxxx \
    -e AWS_SECRET_ACCESS_KEY=xxxxx \
    -v ~/workspace/aws-training/aws-networking-bastion:/app \
    -w /app zpei/workshop:latest \
        ansible-playbook -i inventory/dev/inventory playbook-networking-bastion.yml -vvv
```
