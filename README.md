# Photo Gallery for Wallpaper Engine

I appreciate the Android wallpaper rotation tool [Wallpaper Engine](https://github.com/wallpaper-tools/wallpaper-engine) but the 
photo selection for cloud photo services required manual individual photo selection.

Fortunately Wallpaper Engine provides straightforward [API for building custom wallpaper sources](https://github.com/wallpaper-tools/wallpaper-engine/wiki/API)
 so I developed this which retrieves metadata (ID and timestamp) for all your cloud photos and delivers
 a randomized photo which hasn't been displayed yet each time Wallpaper Engine requests a new wallpaper.
 After cycling through all your photos it restarts the sequence. 

Referenced code patterns from [stock photo example](https://github.com/wallpaper-tools/wallpaper-engine/tree/master/example-source-stock-photos)
and [cloud API sample code](https://developers.cloud-services.io/api/v1/quickstart/android)
