---
title: "We Have a Website"
date: 2026-09-02
categories:
  - Non Scientific News
tags:
  - Website
  - update
classes: wide
---

# We Can Make Blog/News Posts

Ok so to make new blog posts is quite different but easier than making pages (not that making pages is hard tbh). You'll want to go to `_posts` in the github. Then create a new .md file. The title should follow `YYYY-MM-DD-name-of-post.md` . Then you'll want to start your mardown post with a YAML header; scary name, simple concept. It's simply a header that tells the website compilter what is that file. Start and end the header add `---`
For posts the convention to follow is 
```ruby
---
title: 'Title to show on your post'
date: yyyy-mm-dd
categories:
  - Non Scientific News/ Scientific News / Do we want more (new project/members) ?
tags:
  - I dunno which to stick with
---
```

The categories allow to quickly split the blog into scientific and non scientific which could be used for another layout of the news pages. The tags relate articles to one another for related article option at the bottom of the page. 