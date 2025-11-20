# IMPORTANT: Download GSAP Bonus Plugins

Your build is failing because ScrollSmoother and SplitText plugins need to be downloaded manually.

## Quick Fix:

1. **Download ScrollSmoother:**
   - Go to: https://greensock.com/docs/v3/Plugins/ScrollSmoother
   - Click "Download" or "Get Plugin"
   - Save the file as `ScrollSmoother.js` in `src/lib/gsap-plugins/`

2. **Download SplitText:**
   - Go to: https://greensock.com/docs/v3/Plugins/SplitText
   - Click "Download" or "Get Plugin"  
   - Save the file as `SplitText.js` in `src/lib/gsap-plugins/`

3. **Verify the files exist:**
   ```
   src/lib/gsap-plugins/ScrollSmoother.js
   src/lib/gsap-plugins/SplitText.js
   ```

4. **Rebuild:**
   ```bash
   npm run build
   ```

## Why?

Even though GSAP is now free (as of April 30, 2025), ScrollSmoother and SplitText are bonus plugins that aren't included in the npm package structure. They need to be downloaded separately from the GSAP website and added to your project.

The imports have already been updated to use these local files.

