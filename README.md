# Testing Cloudflare R2 storage

## Objectives

- Using the Github Action [https://github.com/marketplace/actions/r2-upload-action](https://github.com/marketplace/actions/r2-upload-action) to upload files that are pushed to this Github repo to Cloudflare R2 Object Storage.

- To test what happens when new pushes are made to the repo and what happens when already uploaded files are modified.

## Results

### It uploads also the `.git` directory to Cloudflare

- Fix: Create a directory like `contents` in the root of the repo and put all the contents inside it and set the `source-dir` in the `deploy.yml` to `contents`

### What happens when I move files?

### What happens when I push new updates?

### What happens when I delete files?
