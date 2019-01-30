<!-- TITLE: Local Development -->
<!-- SUBTITLE: A quick summary of Local Development -->

These notes are about local development with wiki.js.  Here's what I did:
1. clone the wiki-v1 repo
2. npm install  - this took ages
3. cp config.sample.yml config.yml
4. In the config, change `public: true` and `auth.defaultReadAccess: true`
5. Copy the Git repo credentials down from app1
6. edit the package.json line "dev" as follows, to set two environment variables when it runs:
   
```text
"dev": "WIKI_ADMIN_EMAIL=support@opentrack.run WIKI_JS_HEROKU=1 node tools/fuse -d"
```


