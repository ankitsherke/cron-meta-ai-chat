# cron-meta-ai-chat

## Manual Trigger

Use the cron secret header when manually invoking the batch job:

```sh
curl -X POST https://<app>.vercel.app/api/capi-batch \
  -H "x-cron-secret: $CRON_SECRET"
```
