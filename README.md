## 🌈 Add the Widget to your Site

1. Install the widget by referencing it in your `config/_defaults/config.yaml`:
   ```yaml
   module:
     imports:
       - path: github.com/cdalas2/wowchemy-widget-about-avatar-caption
   ```
   
2. Create an instance of your widget in `content/home/`, for example let's create `content/home/github.about-avatar-caption.md`
   ```markdown
---
# An instance of the About Avatar Caption widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: github.cdalas2.about-avatar-caption

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 1
  
author: admin
---
  ```

3. Create an instance of an author profile in `content/authors/`, for example let's create `content/authors/admin/_index.md`
  ```markdown
---
# Display name
title: About Me
# Is this the primary user of the site?
superuser: true

# Role/position/tagline
#role: Professor of widget creations

# Organizations/Affiliations to show in About widget
#organizations:
# - name: Wowchemy
#    url: https://www.wowchemy.com

# Short bio (displayed in user profile at end of posts)
bio: My interests include creating super cool easy to use widgets for the greater good!

# Social/Academic Networking
# For available icons, see: https://wowchemy.com/docs/getting-started/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "/#contact" for contact widget.
social:
  - icon: envelope
    icon_pack: fas
    link: 
  - icon: google-scholar
    icon_pack: ai
    link: 
  - icon: github
    icon_pack: fab
    link: 
  - icon: linkedin
    icon_pack: fab
    link: 
  - icon: cv
    icon_pack: ai
    link: 

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ''

# Highlight the author in author lists? (true/false)
highlight_name: true
---

My sole purpose is to create, create, and create WIDGETS! I strive for ultimate perfection in widgetry. I will not settle for subpar! I will not settle for the template version of about!
```
