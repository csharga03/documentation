---
title: "Does Patchstack work with LiteSpeed?"

excerpt: ""
hidden: false
metadata: 
  image: []
  robots: "index"
createdAt: "Tue Aug 23 2022 13:49:24 GMT+0000 (Coordinated Universal Time)"
updatedAt: "Tue Aug 23 2022 13:49:24 GMT+0000 (Coordinated Universal Time)"
---
LiteSpeed has the ability to support .htaccess files as well, so Patchstack will work with LiteSpeed.  
However, make sure your .htaccess file contains the following on top of the file:

```
<IfModule LiteSpeed>
  CacheLookup public on
</IfModule>
```