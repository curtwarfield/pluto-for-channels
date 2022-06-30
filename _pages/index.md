---
layout: page
title: Home
id: home
permalink: /
---
# Welcome! 🌱

## Introduction

[Channels](https://getchannels.com/) is a great application by **Fancy Bits, LLC** that allows you to enjoy free over-the-air HD TV.

Their [custom channel](https://getchannels.com/custom-channels/) feature allows you to use streaming sources such as [Pluto TV](https://pluto.tv/) to create your own channels.

Visit their great [community support page](https://getchannels.com/support/) to get started.

## Updating Pluto Guide Data
When setting up Pluto as a custom channel, you need to specify a `Playlist` and `EPG` for the guide data.

One of the developers of the [Channels](https://getchannels.com/) app has already created a docker image that automatically updates both of these.

You can grab the [maddox/pluto-for-channels](https://github.com/maddox/pluto-for-channels) docker image and run the container on your own system to create and update the `Playlist` and `EPG` files for Pluto TV.

But if you prefer not to run your own docker container, you can use the active `Playlist` and `EPG` files from this site.

Use these links for your Pluto TV guide data:

1. [Playlist](https://pluto.wordfun.ink/playlist.m3u)    
`https://pluto.wordfun.ink/playlist.m3u`

2. [EPG](https://pluto.wordfun.ink/epg.xml)    
`https://pluto.wordfun.ink/epg.xml`

- Paste the `Playlist` link in the **Source** URL field in the `Custom Channels` configuration box.    
- Paste the `EPG` link in the **XMLTV Guide Data** field in the `Custom Channels` configuration box.

See the **Add Source to Channels** section in the`README.md` file in the [maddox/pluto-for-channels](https://github.com/maddox/pluto-for-channels) repository for addtional detail.

> The guide data is refreshed every 3 hours.

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
