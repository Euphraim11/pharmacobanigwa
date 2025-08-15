Pharmaco Banigwa - Netlify CMS build

This package is Netlify CMS-ready and includes:
- index.html (home)
- about.html, contact.html
- blog/ (html posts)
- data/notification.json (editable via Netlify CMS files collection)
- admin/config.yml (Netlify CMS config)
- admin/index.html (Netlify CMS app loader)
- assets/styles.css

Deployment (Netlify):
1. Push this folder to GitHub and connect the repository to Netlify OR drag & drop the folder into Netlify to deploy the static site.
2. In Netlify, enable Identity (Netlify Identity > Enable) and then enable Git Gateway.
3. Visit https://your-site.netlify.app/admin to sign up and start creating posts.

Notes:
- The notification is editable under Settings -> Notification in the /admin panel.
- For Git Gateway to persist edits, the site must be connected to a Git provider (GitHub) and Git Gateway enabled.
