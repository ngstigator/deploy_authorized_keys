# deploy_authorized_keys
Ansible playbook to deploy public key to remote e.g. vagrant

## Usage
`ansible-playbook -i hosts/lamp02 deploy_authorized_keys.yml --ask-pass -u vagrant`

## Tunables
`pubkey` - specify file location of public SSH key in playbook `deploy_authorized_keys.yml`

## Reference
https://medium.com/@visualskyrim/ansible-playbook-deploy-the-public-key-to-remote-hosts-da3f3b4b5481
