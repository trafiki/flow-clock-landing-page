# FlowClock Website

Simple static website for FlowClock Chrome Extension.

## Pages

- `/` - Homepage with features and CTA
- `/privacy` - Privacy Policy
- `/support` - Support & FAQ

## Deploy to Vercel

1. Install Vercel CLI (optional):
   ```bash
   npm i -g vercel
   ```

2. Deploy:
   ```bash
   cd website
   vercel
   ```

   Or just drag the `website` folder into [Vercel's web interface](https://vercel.com/new).

3. After deployment, update your Chrome Web Store listing with:
   - Privacy Policy URL: `https://your-site.vercel.app/privacy`
   - Support URL: `https://your-site.vercel.app/support`
   - Homepage URL: `https://your-site.vercel.app`

## Local Development

Just open `index.html` in your browser. No build step needed.

## Update Chrome Store Link

After your extension is published, update the "Add to Chrome" button link in `index.html`:

```html
<a href="YOUR_CHROME_STORE_URL" class="cta-button" target="_blank">
```
