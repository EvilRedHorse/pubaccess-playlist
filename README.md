# pubaccess-playlist
Build your video playlist and share it

## Public Portals Dapp URL
https://scp.techandsupply.ca/IABMg3cQqy7njNJbqpVWaKQJuRAeQ4a-3n4w-MGfF9M9PA

## Demo Video
change -> https://siasky.net/AABSR21FcA-YmenaD-NvOb727LrVDAsEw_Bz1r4HxglcIQ

## Build the HTML
In order to build the html you can use the npm package `inliner`.
Just run the following commands and you will end up with a `dist.html` that
contains everything which you can then upload to Public Portals.

```
npm install -g inliner
cat index.html | inliner > dist.html
```
