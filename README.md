# SoundCast Stitching API

Stich API is a service to concatenate an ad to an audio file. In the background, the API will call our adServer to request an ad for a given Tag.

## Request

### URL

```
https://stitch.api.soundcast.fm/v1/podcast
```

### Query parameters

| Parameters      | Required | Description                                                                 |
|:--------------- |:-------- |:--------------------------------------------------------------------------- |
| soundcastId     | true     | SoundCast tag ID                                                            |
| podcastUrl      | true     | Url to the podcast audio file                                               |
| pageUrl         | false    | Url of the podcast's a page                                                 |
| pageDescription | false    | Description of the podcast                                                  |
| pageTitle       | false    | Title of the podcast                                                        |
| keywords        | false    | Words to classify the podcast separated by a , (ex: tech, lifestyle, etc..) |
| ip              | false    | IP of the listener, will be use for targeting and analytics purpose         |
| userAgent       | false    | User Agent of the listener, will be use for targeting and analytics purpose |
| consent         | false    | GDPR consent string of the listener                                         |
| idfa            | false    | IDFA of the listener device                                                 |
| test            | false    | indicates a test call                                                       |

When not pass throught the query params, the following parameters will be set by the request Headers

| Parameters      | Description                                                                 |
|:--------------- |:--------------------------------------------------------------------------- |
| ip              | IP of the listener, will be use for targeting and analytics purpose         |
| userAgent       | User Agent of the listener, will be use for targeting and analytics purpose |


## Testing

Add **&test=true** to your request


## Any questions

Please contact our support team
