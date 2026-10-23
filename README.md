# md.gvdb

``` bash
read -s -p "Enter token: " TOKEN && git clone --no-checkout --depth=1 --filter=blob:none https://malocnet:$TOKEN@github.com/malocnet/md.gvdb.git md.gvdb
cd md.gvdb
git sparse-checkout set image
git checkout
```

```bash
git config user.email "malocnet@gmail.com"
git config user.name "malocnet"
git config credential.helper /usr/local/bin/git-credential-libsecret
read -s -p "Enter token: " TOKEN && git clone https://malocnet:$TOKEN@github.com/malocnet/md.gvdb.git
```
