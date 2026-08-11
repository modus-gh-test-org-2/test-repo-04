# Cache lookups in the resolver hot path

The worker now drains in-flight work and closes connections on SIGTERM instead of exiting immediately.

Change #3 of 4 on branch `pr/20260811-130136-3-cache-lookups-in-the-resolver-hot-path`.
