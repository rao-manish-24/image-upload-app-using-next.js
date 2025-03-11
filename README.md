# image-upload-app-using-next.js

A reusable, responsive multi-image upload component built with Next.js, TypeScript, Tailwind CSS, `shadcn/ui`, and `react-hook-form`. This project provides a simple, type-safe solution for uploading multiple images with progress tracking, deletion feedback, and form validation integration.

![Demo - Next.js Image Upload](/public/og-image.png)

## Features

- **Image Upload**: Upload multiple files with a configurable maximum limit (default: 5).
- **Responsive Design**: Flex-based layout that adapts to different screen sizes using Tailwind CSS.
- **Progress Tracking**: Displays upload progress as a percentage overlay on each image.
- **Deletion Feedback**: Glow-and-dim animation during image deletion to indicate the action is in progress.
- **Form Integration**: Fully compatible with `react-hook-form` for controlled form validation and error handling.
- **Type-Safe**: Written in TypeScript with proper type definitions for props and internal state.
- **Customizable**: Easily styled via Tailwind CSS classes and extensible through props.
- **API Support**: Integrates with signed URL generation and file upload/deletion APIs (server-side logic included).

## Demo

- <https://nextjs-multi-image-upload.vercel.app>
