## ACME TLS 

We use the Automated Certificate Management Environment (ACME) [defined here](https://github.com/pulibrary/ops-catchall/blob/main/projects/incommon/incommon_certbot_ubuntu.md) and included in the [EzProxy Role](https://github.com/pulibrary/princeton_ansible/tree/main/roles/ezproxy). 

The process runs as a cron job that can be confirmed by running the following command:

```bash
sudo certbot renew --dry-run --standalone --non-interactive --agree-tos --email netid@princeton.edu --server https://acme.sectigo.com/v2/InCommonRSAOV --eab-kid XXXxxNNxNNWxXxxXNXxXx --eab-hmac-key _XNXXxxNXNNXxXNXXNXXXxxxXNNxXxxXXXxxXXXNX_XXxXxNxNNNX_XXxxNXXxXNxxXXXXxXxxXXXxXxNzXXxX 
```

The TLS files will be saved at 

`/etc/letsencrypt/live/ezproxy`


## Ezproxy Cert Renewal

EzProxy software public UI is managed at the following [URI](https://login.ezproxy.princeton.edu/ssl) Your netid will need to be among those allowed to manage the EzProxy application. The file to modify is can be found at the [EzProxy Conf Repo](https://github.com/PrincetonUniversityLibrary/ezproxy_conf/blob/main/shibuser.txt.tmp)

You will need to [Import the](https://login.ezproxy.princeton.edu/ssl-import)

the `/etc/letsencrypt/live/ezproxy/certN.pem` for the certificate, `/etc/letsencrypt/live/ezproxy/keyN.pem` for the key and select **Import Certificate** then select `/etc/letsencrypt/live/ezproxy/chainN.pem` on the next page and type **ACTIVE** to make the selected keys the now active keys for the Application.