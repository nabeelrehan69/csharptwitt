The Csharptwitt is an Implementation of Twitter Api in c#.

In this project most of the commonnly used methods are captured.

The Csharptwitt API is differentiated in two catogories:

1. PublicTwitt
> API which are not required user authentication.
2. UserTwitt
> API which are required user authentication.

<b><u>PublicTwitt</u></b>

<br><br>SEARCH API Methods<br>
<br>                search<br>
<br>                trends<br>
<br>                trends/current<br>
<br>                trends/daily<br>
<br>                trends/weekly<br>
<br><br>REST API Methods<br>
<br>Timeline Methods<br>
<br>                 statuses/public_timeline<br>
<br><br>Status Methods<br>
<br>                 statuses/show<br>
<br><br>User Methods<br>
<br>                 users/show<br>
<br>                 statuses/friends<br>
<br>                 statuses/followers<br>
<br><br>Account Methods<br>
<br>                 account/rate_limit_status<br>Example:<br>
<blockquote>To get publictimeline from twitter without authentication ( without user login ) in xml format.</blockquote>

<blockquote>Twitter.PublicTwitt pubTwitt = new Twitter.PublicTwitt();<br>
string strResult= pubTwitt.GetPublicTimeline(Twitter.OutputFormatType.xml);</blockquote>


<b><u>UserTwitt</u></b>
<br>REST API Methods<br>
<br>Timeline Methods<br>
<br>               statuses/public_timeline<br>
<br>               statuses/home_timeline<br>
<br>               statuses/friends_timeline<br>
<br>               statuses/user_timeline<br>
<br>               statuses/mentions<br>
<br>               statuses/retweeted_by_me<br>
<br>               statuses/retweeted_to_me<br>
<br>               statuses/retweets_of_me<br>
<br><br>Status Methods<br>
<br>               statuses/show<br>
<br>               statuses/update<br>
<br>               statuses/destroy<br>
<br>               statuses/retweet<br>
<br>               statuses/retweets<br>
<br><br>User Methods<br>
<br>               users/show<br>
<br>               users/search<br>
<br>               statuses/friends<br>
<br>               statuses/followers<br>
<br><br>List Methods<br>
<br>               POST lists      (create)<br>
<br>               POST lists id  (update)<br>
<br>               GET lists        (index)<br>
<br>               GET list id      (show)<br>
<br>               DELETE list id (destroy)<br>
<br>               GET list statuses<br>
<br>               GET list memberships<br>
<br>               GET list subscriptions<br>
<br><br>List Members Methods<br>
<br>               GET list members<br>
<br>               POST list members<br>
<br>               DELETE list members<br>
<br>               GET list members id<br>
<br><br>List Subscribers Methods<br>
<br>               GET list subscribers<br>
<br>               POST list subscribers<br>
<br>               DELETE list subscribers<br>
<br>               GET list subscribers id<br>
<br><br>Direct Message Methods<br>
<br>               direct_messages<br>
<br>               direct_messages/sent<br>
<br>               direct_messages/new<br>
<br>               direct_messages/destroy<br>
<br><br>Friendship Methods<br>
<br>               friendships/create<br>
<br>               friendships/destroy<br>
<br>               friendships/exists<br>
<br>               friendships/show<br>
<br><br>Social Graph Methods<br>
<br>               friends/ids<br>
<br>               followers/ids<br>
<br><br>Account Methods<br>
<br>               account/verify_credentials<br>
<br>               account/rate_limit_status<br>
<br>               account/end_session<br>
<br>               account/update_delivery_device<br>
<br><br>Favorite Methods<br>
<br>               favorites<br>
<br>               favorites/create<br>
<br>               favorites/destroy<br>
<br><br>Notification Methods<br>
<br>               notifications/follow<br>
<br>               notifications/leave<br>
<br><br>Block Methods<br>
<br>               blocks/create<br>
<br>               blocks/destroy<br>
<br>               blocks/exists<br>
<br>               blocks/blocking<br>
<br>               blocks/blocking/ids<br>
<br><br>Spam Reporting Methods<br>
<br>               report_spam<br>
<br><br>Saved Searches Methods<br>
<br>               saved_searches<br>
<br>               saved_searches/show<br>
<br>               saved_searches/create<br>
<br>               saved_searches/destroy<br>
<br>
<br>

For Example visit my blog<br>
<blockquote><a href='http://himanshu-hajariwala.blogspot.com/'><a href='http://himanshu-hajariwala.blogspot.com/'>http://himanshu-hajariwala.blogspot.com/</a></a>