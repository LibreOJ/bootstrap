# LibreOJ Bootstrap

Serve the first HTML page of [`loj.ac`](https://loj.ac), with CDNs, regional configurations and service worker, on Azure Function App, Cloudflare Workers and Aliyun OSS.

* `core`: The (shared) core code of serving the HTML page with serverless platform.
* `azure`: The Azure Function App project.
* `cloudflare`: The Cloudflare Workers project.
* `aliyun-oss`: Serve with Aliyun OSS statically files for China mainland users.
* `service-worker`: The Service Worker running in frontend.

See [Actions](https://github.com/LibreOJ/bootstrap/actions) for deployment info.
