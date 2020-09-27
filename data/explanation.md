# GBvideos.csv
Videos have an entry have an entry for each day they are on trending, so can have multiple entries in the dataset. Values are taken at the end of the day.

| Field Name | Type | Description |
|:-----------|:-----|:------------|
| *video_id* | str | id for video in YouTube's system. Can be visited at `https://www.youtube.com/watch?v=__video_id__` |
| *trending_date* | str (date) | date video was in trending. (YY.DD.MM) |
| *title* | str | title of video |
| *channel_title* | str | title channel video was posted on |
| *category_id* | int | id for video's category. Details about category ids can be found in `GB_category_id.json` |
| *publish_time* | datetime | time video was posted |
| *tags* | [str] | tags assigned to  video (defined by video poster) |
| *views* | int | video views at the end of day |
| *likes* | int | likes on videos at the end of the day |
| *dislikes* | int | dislikes on videos at the end of the day |
| *comment_count* | int | number of comments on video at the end of the day |
| *thumbnail_link* | str (url) | url of video's thumbnail image |
| *comments_disabled* | bool | whether comments are disabled on the video |
| *ratings_disabled* | bool | whether likes/dislikes are disabled on the video |
| *video_error_or_removed* | bool | whether video has been removed from YouTube |
| *description* | str | description of video (defined by video poster) |
