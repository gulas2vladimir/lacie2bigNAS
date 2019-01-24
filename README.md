# lacie2bigNAS - Sorting media by track name
```
mount -o remount,rw /
```

```
vi /usr/local/twonkymedia/resources/views/view-definitions.xml
```

```
<container name='byfolder'...
add after albumart='1'
sortcriteria='+pv:numberOfThisDisc,+upnp:originalTrackNumber,+dc:title'
```
restart service via WEBUI
