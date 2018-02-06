# lacie2bigNAS

```
mount -o remount,rw /
```

```
vi /usr/local/twonkymedia/resources/views/view-definitions.xml
```

```
<container name='byfolder' id='music/folders' class='object.container.storageFolder' createClass='object.item.audioItem.musicTrack,object.item.audioItem.audioBook'>                                          
                                <container buildon='res' albumart='1' sortcriteria='+pv:numberOfThisDisc,+upnp:originalTrackNumber' createClass='object.item.audioItem.musicTrack,object.item.audioItem.audioBook' class='object.container.storageFolder' />
</container>
```
