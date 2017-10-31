#To add a custom plugin
Log into server via ssh

```
ssh web@domain.com
```

navigate to the current release
```
cd /srv/www/moordesign.me/releases
```
find most recent release
```
ls -li
```
change directory to plugins
```
cd <release number>/web/app/plugins/
```
open up a new tab in the terminal and add plugin folder via scp
```
scp -ra /path/to/local/storage user@remote.host:/srv/www/moordesign.me/releases
/<release number>/web/app/plugins/
```

Example
```
scp -r /Volumes/GoogleDrive/My\ Drive/Clients/robogallerykey web@moordesign.me:/srv/www/moordesign.me/releases/20171031184431/web/app/plugins
```