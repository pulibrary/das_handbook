### Debride
Use [debride](https://github.com/seattlerb/debride) to find potentially unused methods in your code. Pass it a directory to check. You can also optionally pass it an allowlist file, which will ignore methods you have determined to be needed.

```zsh
debride -w .debride_allowlist.txt app/models/requests
```

One thing to look out for is that it does not seem to find methods used in `.erb` files, so pay particular attention to these when checking whether a method is in fact used.
