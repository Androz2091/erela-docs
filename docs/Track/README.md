# Track  
---  
*class* **Track**   
> The Track class.  
---
- Constructor
```javascript
new Erela.Track(data, user)
```
| Parameter <img width=1000/> | Type <img width=1000/> | Description <img width=1000/> |  
| :--- | :--- | :--- |  
| data | [ITrackData](/docs/Track/ITrackData) | The data to pass. |  
| user | [User](https://discord.js.org/#/docs/main/stable/class/User) | The user who requested the track. |  
---  
| Properties <img width=1000/> |   
| :--- |   
| [track](#track) |   
| [identifier](#identifier) |   
| [isSeekable](#isseekable) |   
| [author](#author) |   
| [duration](#duration) |   
| [isStream](#isstream) |   
| [title](#title) |   
| [uri](#uri) |   
| [thumbnail](#thumbnail) |   
| [user](#user) |   
---  
## Properties:  
- ### track  
> The base 64 encoded track.  
> **Type:** *[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string)*  
- ### identifier  
> The track's identifier.  
> **Type:** *[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string)*  
- ### isSeekable  
> Whether the track is seekable.  
> **Type:** *[boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean)*  
- ### author  
> The author of the track.  
> **Type:** *[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string)*  
- ### duration  
> The track's duration.  
> **Type:** *[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/number)*  
- ### isStream  
> Whether the track is a string.  
> **Type:** *[boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean)*  
- ### title  
> The track's title.  
> **Type:** *[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string)*  
- ### uri  
> The track's URI.  
> **Type:** *[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string)*  
- ### thumbnail  
> The track's thumbnail.  
> **Type:** *[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string)*  
- ### user  
> The user who requested the track.  
> **Type:** *[User](https://discord.js.org/#/docs/main/stable/class/User)*  
