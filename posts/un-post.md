---
title: un post
---
If you refresh the CMS page, you’ll see all of the content disappear. That’s because the CMS is now looking in your GitHub repo for content, and there is none. It’s able to check your repo for content without any authentication because your repo is public, but if you try to create a post and save, you’ll get an error. Authentication requires a server for verification, which Netlify provides for users running the CMS locally under localhost.
