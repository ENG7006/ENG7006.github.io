---
title: Troubleshooting Jekyll
layout: post
category: tech, how-to, jekyll, announcements
---
Thank you for bearing with me on Thursday as the technology broke. (Technology always breaks.)

There were actually two different issues in the ```_config.yml``` files, which should be very easy to fix. If you're intrepid, you can try the fix at home. If not, we'll go over them together in lab next time.

The solution is to overwrite two lines in the config file. You can copy and paste and edit them in your Jekyll site and push the changes up to GitHub, and it should work.

```yaml
### ...
description: 'Put your description here.'
baseurl: http://[your github username].github.io/
### ...
```
