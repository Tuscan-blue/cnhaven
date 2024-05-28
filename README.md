### Differences between Haven and cnhaven
- Replace the Debian sources with the mirror from Tsinghua University([Debian 软件源 | 清华大学开源镜像站](https://mirrors.tuna.tsinghua.edu.cn/help/debian/)).
- When deploying locally using Docker, the process becomes exceptionally smooth.(For users in China)

### Deployment
#### Docker
1. `git clone https://github.com/Tuscan-blue/cnhaven.git`
2. `cd cnhaven`
3. `docker compose up`

### Haven

[Haven](https://havenweb.org) is a private blog application built with Ruby on Rails. Write what you want, create accounts for people you want to share with, keep up with each other using built-in RSS.

Try out a live demo at https://havenweb.org/demo.html

The following are some motivating philosophies:

* Open-source. MIT License
* Privacy-first.  This is for sharing with friends and family, not commercial endevors.  If you want a blog for your company, you probably want to use WordPress or Ghost instead.
* Easy to use.  Built-in web interface for managing users, customizing the blog, and writing/editing posts with markdown and live-preview.
* Low-bandwidth friendly.  Images get downscaled to reduce page load times.  No javascript frameworks.  No ads or trackers.
* Customizable.  Add custom CSS or fonts.
* No spam. There is no self-signup for users so there is no place for unauthorized users to impact your life.
* Media support for images, videos, and audio.
* Private RSS feeds for your friends to follow you.
* Build-in RSS reader to follow your favorite blogs.



