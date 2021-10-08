# Wave a flag

Files can always be changed in a secret way. Can you find the flag?

```bash
curl -O https://mercury.picoctf.net/static/f95b1ee9f29d631d99073e34703a2826/warm
strings cat.jpg| grep license | cut -c 29-72 | base64 -d
```

```text
picoCTF{the_m3tadata_1s_modified}
```
