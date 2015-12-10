## decrypting secrets

certificates, passwords, API keys should be placed in secrets/ so that they are encrypted by git-crypt:

```
git-crypt unlock ../git-crypt-codersfield-key-file 
```

## Running ansible

Operation should be idempotent:

```
./ansible.sh
```


