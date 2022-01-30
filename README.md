# GrabTunes
Get iTunes music data with this Javascript API

### Getting an album cover

To get any song cover, use this command : (remplace term by your own search term)

https://developers.vincelinise.me/grabtunes/cover?term=***term***

```jsx
> https://developers.vincelinise.me/grabtunes/cover?term=My%20House%20Flo%20Rida
>> https://is1-ssl.mzstatic.com/image/thumb/Music125/v4/03/96/fd/0396fde4-8025-752e-36de-583b7d98e4f4/source/600x600bb.jpg
```

### Getting any data from music

To get any data from this list, use this : (replace term and data by your own)

https://developers.vincelinise.me/grabtunes/data?term=**term**&data=***data***

```jsx
> https://developers.vincelinise.me/grabtunes/data?term=my%20house%20flo%20rida&data=artistName
>> Flo Rida
```

**Available "data" tag list**

| Tag | Usage | Result (for "Flo Rida My House") |
| --- | --- | --- |
| kind | Get what kind of media you searched | song |
| artistName | Get song's artist name | Flo Rida |
| collectionName | Get song's collection name | My House |
| trackName | Get song's title | My House |
| artistViewUrl | Link to Apple Music's artist page | https://music.apple.com/us/artist/flo-rida/255303209?uo=4 |
| collectionViewUrl | Link to the collection on Apple Music | https://music.apple.com/us/album/my-house/971238498?i=971238507&uo=4 |
| trackViewURL | Link to the song on Apple Music | https://music.apple.com/us/album/my-house/971238498?i=971238507&uo=4 |
| previewURL | Link to song preview (.m4a) | https://audio-ssl.itunes.apple.com/itunes-assets/AudioPreview125/v4/ca/68/3b/ca683b58-82c3-068a-9765-cbdeda8233ae/mzaf_5849329439148890827.plus.aac.p.m4a |
| primaryGenreName | Get song's genre | Hip-Hop/Rap |
| trackTimeMillis | Get all milliseconds in track | 192191 |
| trackExplicitness | Get if song is explicit or not | notExplicit |
| releaseDate | Get song's release date | 2015-04-07T07:00:00Z |
