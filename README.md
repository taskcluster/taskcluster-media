# Taskcluster Media

## Assets

This repository contains permalinkable Taskcluster assets (all also available
via http if necessary):

 * https://media.taskcluster.net/logo/logo.png -- large logo (size may change)
 * https://media.taskcluster.net/logo/logo-96x120.png -- 96x12 logo
 * https://media.taskcluster.net/favicons/faviconLogo.png -- a plain favicon (left-justified)
 * https://media.taskcluster.net/favicons/faviconLogoCompleted.png -- plain favicon with a "completed" indication
 * https://media.taskcluster.net/favicons/faviconLogoFailed.png -- plain favicon with a "failed" indication
 * https://media.taskcluster.net/favicons/faviconLogoRunning.png -- plain favicon with a "running" indication

These assets are uploaded to an S3 bucket and served by Cloudfront.

### Updating

Use `sync.sh` to (manually) update the media data.

## Sources

The repository also contains soure material for these assets, under `source/`.
