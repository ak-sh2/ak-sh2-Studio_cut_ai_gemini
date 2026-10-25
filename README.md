# Studio_cut_AI

Clean, minimal browser-local web application for **background removal**, **background replacement**, and **image quality enhancement**.

## Features
- **Upload & Format Handling**: Supports `JPG`, `JPEG`, `PNG`, `WebP`, and `HEIC/HEIF` (converted in-browser via `heic2any`), drag-and-drop, mobile camera/gallery capture, and automatic EXIF orientation correction. Downscales oversized images for responsive editing while preserving full original resolution for final export.
- **Background Removal**: Runs 100% locally in the browser with edge-aware alpha feathering for hair and fine details, real-time progress bar, and adjustable edge tolerance/feather sliders.
- **Background Replacement**: Transparent cutout, 9 popular solid studio colors, custom hex color picker, and custom background image upload.
- **Enhance Quality**: One-tap Auto Enhance, manual sliders for Sharpness, Brightness, Contrast, and Denoise, plus optional **2x Upscale**.
- **Compare, Undo & Export**: Interactive Before/After split slider, multi-step Undo & Reset, and full-resolution download in **PNG (transparent)**, **JPG**, or **WebP**.
- **UI/UX**: Dark/Light mode toggle at the top, 3-step workflow (`Upload → Edit → Download`), collapsible control sections, `>=44px` touch targets, thin subtle scrollbars, and full-page scrolling with zero fixed/sticky headers.

## Deploying to GitHub Pages
1. Create a new repository on GitHub and upload the files from this folder (`index.html`, `README.md`, `.gitignore`, `.nojekyll`).
2. Open **Settings → Pages** in your GitHub repository.
3. Under **Build and deployment**, select **Deploy from a branch**, choose **`main`** and **`/ (root)`**, and click **Save**.
4. Your live app will be published at `https://<your-username>.github.io/<repository-name>/`.
