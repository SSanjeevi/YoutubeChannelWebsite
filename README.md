[![Youtube-Page-Generator](https://github.com/SSanjeevi/YoutubeChannelWebsite/actions/workflows/main.yml/badge.svg)](https://github.com/SSanjeevi/YoutubeChannelWebsite/actions/workflows/main.yml)

# Videos-By-Sanjeevi
Youtube Channel Website

## YouTube Channel Website Features:
1. Free Hosting using GitHub Pages and open-source code base in GitHub.
2. It can update all the videos, title, and description available inside the channel into the website everyday automatically using the GitHub Actions feature.
2. No need to manually do any step after posting any new video in YouTube, it will be updated in website on next day.

## How to Reuse this Template which creates a personal website hosted in Github Pages using Jekyll and Github Actions for free!

1. Fork this repo: [Fork this on github](https://github.com/SSanjeevi/YoutubeChannelWebsite/fork)

2. Create Secret in Github repo and add secret named: "GOOGLEAPIKEY" with value of Google console api id.
3. Update your channel name in the file workflow - [File line : 18](https://github.com/SSanjeevi/YoutubeChannelWebsite/blob/gh-pages/.github/workflows/main.yml)
     > python ./youtubeChannelVideosFinder.py -k ${{ secrets.GOOGLEAPIKEY }} -c 'your-channel-name-here' --output-file-path index.md

3. Enable the repo as github pages, your website is ready.


## Samples created by this tool:
https://github.com/LKG-in-IT/YoutubeChannelWebsite

## Demo 1:
https://lkg-in-it.github.io/YoutubeChannelWebsite/

## Demo 2:
https://tv.lkgforit.com/

## Demo 3
https://tnpscquickies.github.io/YoutubeChannelWebsite/

## Detailed Article:
https://lkgforit.com/personal-youtube-channel-videos-website-hosted-in-github-pages-for-free-which-populates-content-by-itself


Reference:

https://github.com/dsebastien/youtubeChannelVideosFinder

https://github.com/nathancy/jekyll-embed-video
