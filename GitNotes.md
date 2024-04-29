# Form SSH connection between Github & Client

- Create SSH public key
```bash
ssh-keygen -t rsa -b 4096 -C "your_email"
```
- Add it in your github profile 

- Test your ssh connection from client using below command

```shell
ssh -T git@github.com
The authenticity of host 'github.com (IP ADDRESS)' can't be established.
> ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
> Are you sure you want to continue connecting (yes/no)?
> Hi USERNAME! You've successfully authenticated, but GitHub does not
> provide shell access.
```
- Push it using "git push (add ssh url of your repository"