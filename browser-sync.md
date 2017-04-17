Static sites

If you’re only using .html files, you’ll need to use the server mode. Browsersync will start a mini-server and provide a URL to view your site.

browser-sync start --server --files "css/*.css"
Dynamic sites

If you’re already running a local server with PHP or similar, you’ll need to use the proxy mode. Browsersync will wrap your vhost with a proxy URL to view your site.

browser-sync start --proxy "myproject.dev" --files "css/*.css"