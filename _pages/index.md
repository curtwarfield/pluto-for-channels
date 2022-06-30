---
layout: page
title: Home
id: home
permalink: /
---
# Welcome! 🌱

[Channels](https://getchannels.com/) is a great application by **Fancy Bits, LLC** that allows you to enjoy free over-the-air HD TV.

Their [custom channel](https://getchannels.com/custom-channels/) feature allows you to use streaming sources such as [Pluto TV](https://pluto.tv/) to create your own channels.

Visit their great [community support page](https://getchannels.com/support/) to get started.

If you don't want to run your own docker container to update the guide data for Pluto TV, I've got you covered.

This site runs the [maddox/pluto-for-channels](https://github.com/maddox/pluto-for-channels) docker container for guide data updates.

Use these links to keep your Pluto guide data updated:

[Playlist](https://pluto.wordfun.ink/playlist.m3u)    
`https://pluto.wordfun.ink/playlist.m3u`

[EPG](https://pluto.wordfun.ink/epg.xml)    
`https://pluto.wordfun.ink/epg.xml`

1. Paste the `Playlist` link in the **Source** URL field in the `Custom Channels` configuration box.    
2. Paste the `EPG` link in the **XMLTV Guide Data** field in the `Custom Channels` configuration box.

> The guide data is refreshed every 3 hours.

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
