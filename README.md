# Image Segmentation AI app :wink:
This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).
The project makes use of image segmentation using Hugging Face’s Inference API for processing images using Facebook’s DETR Model. The small webpage will be able to identify different objects in images and enable the user to view them separately

## Prerequisites
You're going to need an API Key for using Hugging Face’s Inference API. Go ahead and create an account on Hugging Face in order to get access tokens.

## Getting Started
First install the dependencis:

```bash
npm i
#or
yarn i
```

Second, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Usage
This s how the app works:
1. User will upload an image from the frontend.
2. Pass this image through the DETR model using Hugging Face's API.
3. Show the user a list of objects that were identified within the image.
4. The user can select any of the identified objects to see exactly where it was found.

