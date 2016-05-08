# Cryptoparty.dk Ansible playbooks

Provision command:

    ansible-playbook --ask-vault-pass -i cryptoparty.dk, provision.yml


Deploy command:

    ansible-playbook --ask-vault-pass -i cryptoparty.dk, deploy.yml

## Checks

We should ensure that these pages give the highest possible character (of
course in the boundaries of sanity).

### Performance
- https://gtmetrix.com/reports/cryptoparty.dk/NOsfIdfp
- https://developers.google.com/speed/pagespeed/insights/?url=http://cryptoparty.dk/

### Crypto:
- https://discovery.cryptosense.com/analyze/cryptoparty.dk
- https://securityheaders.io/?q=https://cryptoparty.dk
- https://www.ssllabs.com/ssltest/analyze.html?d=cryptoparty.dk
