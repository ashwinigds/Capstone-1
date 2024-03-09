Capstone-1
Title: Youtube Harvesting,warehousing[MONGO DB] and using Streamlit application to get input 

STAGE-1-->Youtube data harvesting and storing in MONGO DB
*steps*
1]To get data from yt,u need to use api of particular platform -->youtube api documentation-->guides.
2]Developers console-->create project and enable yt api key -->YouTube Data API v3.
3]Go to credentials to add api keys -->create api key
-->use generated api key to retrieve those data into our project
4]Store API key in any variable
5] Request yt to share the details of particular video[pk-id]
6]Datails going to scrap from yt:

CHANNEL:
-->Channel name
-->Channel ID
-->Subscribers count
-->started on 
-->Total views
-->country
-->yt link
-->Description
-->Playlist ID

VideoDetails:
-->Video_Id
-->Video_Name
-->Video_Description
-->Tags
-->PublishedAt
-->View_Count
-->Like_Count
-->Comment_Count
-->Duration
-->Thumbnail
-->Caption_Status

Comments:
-->Comment_Id
-->Comment_Text
-->Comment_Author
-->Comment_PublishedAt


       



