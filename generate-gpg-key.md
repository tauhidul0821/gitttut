 GPG Kye Generate 
```bash
$ gpg --version

$ gpg --full-generate-key

press 1 for RSA and RSA (default)

RSA keys may be between 1024 and 4096 bits long.
What keysize do you want? (3072) 4096

Key is valid for? (0) 1y

Real name: WRITE_YOUR_NAME_AS_GITHUB_NAME
Email address: EMAIL_ADDRESS_AS_GITHUB_EMAIL
Comment: GitHub Key

Change (N)ame, (C)omment, (E)mail or (O)kay/(Q)uit? O

$ gpg --list-secret-keys --keyid-format LONG

copy after rsa/ copy_key

$ gpg --armor --export D154646PUYGU53568

$ git config --list

$ git config --global user.name "WRITE_YOUR_NAME_AS_GITHUB_NAME"

$ git config --list

$ git config --global user.signingkey D154646PUYGU53568

$ git config --global commit.gpgsign true

$ git config --global tag.gpgsign true

$ where gpg

$ git config --global gpg.program "C:\Program Files\Git\usr\bin\gpg.exe"

$ git config --global --list

```



















