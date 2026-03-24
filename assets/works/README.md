# Portfolio Work Images

Your images were showing as **"Image missing"** because image files are not physically present in this repo under `/assets/works/`.
Chat attachments are not automatically written into the Git repository during deployment.

## Option 1 (recommended): Commit image files
Add your provided images to `/assets/works/` with these exact filenames:

- `shop-your-gadgets.jpg`
- `wanna-make-cool-cash.jpg`
- `energy-reload.jpg`
- `ash-wednesday.jpg`
- `welcome-to-march.jpg`
- `transform-social-media-presence.jpg`
- `invest-solar-properties.jpg`
- `sprite-campaign.jpg`
- `elevate-your-brand.jpg`
- `beckys-glamour.jpg`
- `one-bite-shawarma.jpg`
- `praise-and-worship.jpg`
- `communion-service.jpg`
- `taking-immediate-action.jpg`
- `portfolio-landing-slide.jpg`
- `resume-slide.jpg`
- `home-slide.jpg`
- `take-that-bold-step.jpg`
- `welcome-to-february.jpg`
- `others-grid-showcase.jpg`

## Option 2: Use in-browser uploader
The page now includes an **"Upload Provided Works"** button in the portfolio section.
Select images from your phone/computer in order and they will replace the gallery instantly (client-side preview).

## Current behavior
- App first loads local files from `/assets/works/...`
- If local files are missing, it temporarily falls back to backup online images
- If backup also fails, it shows the "Image missing" card
