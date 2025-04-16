# youtube-selenium-cookie

```python
from youtube-selenium-cookie import Youtube

upload_info = {
    "title": "rema calm down",
    "description": "Another banger",
    "video": "C:/Users/HP/Desktop/youtube automation video/channels/4th.mp4",
    "thumbnail": "",
    "category": "Music",
    "privacy": "Public",
    "tags": ["rema", "banger", "loudness", "music", "holiday"],
    "kids": False
}

Youtube("./cookies.json", upload_info, True).upload()
```

This packages solely works on cookies. You can grab your cookies by installing edit-the-cookies chrome extension.

The only method available now is upload which uploads to your channel whose cookie you provided.

the video and thumbnail path must be absolute

feel free to make PRs. In case something breaks.

@Dataslid softwares

cmlzhk