BBC iplayer to /programmes switching bookmarklet
=================================================

Inspired by the [BBC /music - MusicBrainz bookmarklet](http://metade.org/blog/2008/07/30/bbc-musicmusicbrainz-bookmarklet/), I created this to let you switch between a [BBC iplayer](http://www.bbc.co.uk/iplayer/) page and it's corresponding [/programmes](http://www.bbc.co.uk/programmes/) page. 

### Why would you do this? 

The iplayer page has higher resolution video and is easier to discover other programmes whilst the /programmes listing includes better metadata and let's you see other episodes in the series.

### Installation

Installing is simple. Simply drag [BBC iplayer-programmes](javascript:var%20m=/http:\/\/(www.bbc.co.uk\/)?(iplayer\/episode|programmes)\/([0-9a-z]{8})/.exec(location.href);if(m[2]=='iplayer/episode'){location.href='http://www.bbc.co.uk/programmes/'+m[3];}if(m[2]=='programmes'){location.href='http://www.bbc.co.uk/iplayer/episode/'+m[3];}) link to your bookmarks bar or right click and choose *'Bookmark This Link'*

