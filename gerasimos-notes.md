# Notes

```ini
; ~/.pypirc
[distutils]
index-servers = nexus

[nexus]
repository = https://your-nexus-server/repository/pypi-hosted/
username = your-username
password = your-password
```

```shell
pip install flit
flit publish --repository nexus
```