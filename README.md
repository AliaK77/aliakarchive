# aliakarchive
blog files for aliakarchive.com

- clone / download source files via tz1and : https://github.com/tz1and/typed.art-blog-template
- change the categories (TypedArtPostType) and whitelist in src/TypedArtBlog/TypedArtUtils.tsx
- run "npm run build" to update/create build version
- upload the build dir to hosting site
- for dreamhost, use this .htaccess file

<IfModule mod_rewrite.c>
RewriteEngine On
RewriteBase /
RewriteRule ^index\.html$ - [L]
RewriteCond %{REQUEST_FILENAME} !-f
RewriteCond %{REQUEST_FILENAME} !-d
RewriteCond %{REQUEST_FILENAME} !-l
RewriteRule . /index.html [L]
</IfModule>


