[![Youtube-Page-Generator](https://github.com/SSanjeevi/videos/actions/workflows/main.yml/badge.svg)](https://github.com/SSanjeevi/videos/actions/workflows/main.yml)

# Videos-By-Sanjeevi
Youtube Channel Website

## How to Reuse this Template which creates a personal website hosted in Github Pages using Jekyll and Github Actions for free!

1. Fork this repo: [Fork this on github](https://github.com/SSanjeevi/videos/fork)

2. Create Secret in Github repo and add secret named: "GOOGLEAPIKEY" with value of Google console api id.
3. Update your channel name in the file workflow - [File line : 18](https://github.com/SSanjeevi/videos/blob/gh-pages/.github/workflows/main.yml)
     > python ./youtubeChannelVideosFinder.py -k ${{ secrets.GOOGLEAPIKEY }} -c 'your-channel-name-here' --output-file-path index.md

3. Enable the repo as github pages, your website is ready.


Reference:

https://github.com/dsebastien/youtubeChannelVideosFinder

https://github.com/nathancy/jekyll-embed-video
