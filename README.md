# Better Upload Skills

Welcome to my repository of custom skills designed for working with **Better Upload** — a library for direct file uploads to S3-compatible storage in React/Next.js applications.

## Installation

This repository uses [skills.sh](https://skills.sh). To install these skills, run the following command in your terminal:

```bash
npx skills add https://github.com/IvanTsxx/better-upload-skills
```

## Available Skills

### Better Upload (`better-upload`)

Use this skill when working with Better Upload, adding file uploads to a React or Next.js app using pre-signed S3 URLs, configuring upload routes or callbacks (onBeforeUpload, onAfterSignedUrl, RejectUpload), setting up S3 clients (AWS S3, Cloudflare R2, MinIO, Backblaze, DigitalOcean Spaces, Tigris, Wasabi), using useUploadFiles or useUploadFile hooks, implementing multipart uploads, managing upload progress or abort, using uploadFile/uploadFiles imperatively, integrating with TanStack Query or React Hook Form, working with S3 helpers (deleteObject, presignGetObject, moveObject), or using UploadDropzone/UploadButton components.

**Key Features:**

- **Architecture**: Direct browser-to-S3 uploads using pre-signed URLs (no server proxy).
- **S3 Clients**: Supports AWS S3, Cloudflare R2, MinIO, Backblaze, DigitalOcean Spaces, Tigris, and Wasabi.
- **React Hooks**: `useUploadFiles`, `useUploadFile`, and imperative `uploadFile`/`uploadFiles` functions.
- **Integrations**: TanStack Query, React Hook Form, pre-built shadcn components.
- **Server Helpers**: `deleteObject`, `presignGetObject`, `moveObject`, `copyObject`, and more.

You can find the full skill definition in [skills/better-upload/SKILL.md](./skills/better-upload/SKILL.md).
