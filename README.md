# SoundCast Stitching SDK
is an API call to stich Audio content with and AD

## Request Ad + Stiching content
Just call the following URL 
```
https://stitch.api.soundcast.fm/v1/ausha?podcastUrl=${URL_CONTENT}&soundcastId=${SOUNDCAST_ID}&pageTitle=${PAGE_TITLE}&pageDescription=${PAGE_DESCRIPTION}&keywords=${KEYWORDS}&pageUrl=${PAGE_URL}&tags=${TAGS}
```
### Parameters

Required:
- ${URL_CONTENT} : URL of the content to be stiched
- ${SOUNDCAST_ID} : TAG ID 
- ${PAGE_URL} :  URL from where the content is played

Optional:
- ${PAGE_TITLE}
- ${TAGS}
- ${KEYWORDS}

## Testing

Add **&test=true** to your request


## Any questions

Please contact our support team
