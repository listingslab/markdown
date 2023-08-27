---
order: 10
bookSlug: "get-started"
path: "/get-started/clone"
title: "Clone"
keywords: "GitHub"
icon: "tricks"
image: "/jpg/hippy.jpg"
---
Identify where you're going to clone the repository. We'll call this `<working-repo>`. Decide on the machine readable name `<your-project>`. Clone the repo and install dependencies

```bash
cd <working-dir>
git clone /listingslab-goldlabel/open-source <your-project>
cd <your-project>
cd gatsby
npm install
cd ../
npm start
```