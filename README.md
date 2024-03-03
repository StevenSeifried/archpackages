# archpackages
- `sudo pacman-key --keyserver hkps://keys.openpgp.org/ --recv-keys 1E62AEECBE23308A397A8B14EC628F268A54E773`
- `sudo nano /etc/pacman.conf`
Add the following lines to the end:

```
[archpackages]
SigLevel = Optional TrustAll
Server = https://stevenseifried.github.io/archpackages/x86_64/
```
