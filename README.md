# Amishi's Art Gallery

## Publish
Upload `index.html`, `style.css`, `script.js`, `paintings.json`, and the `images` folder to the root of the GitHub repository `100amg.github.io`.

In GitHub, go to Settings > Pages. Under Build and deployment, choose **Deploy from a branch**, select **main** and **/(root)**, then Save. Your website will appear at https://100amg.github.io/ after GitHub finishes publishing.

## Add a painting
1. Open the `images` folder in GitHub and select **Add file > Upload files**. Upload a JPG, PNG, or WebP image. Use a short filename with no spaces (e.g. `blue-study.jpg`). Commit changes.
2. Open `paintings.json` and click the pencil icon to edit it.
3. Replace the example with your painting's information. For additional paintings, add another `{ ... }` entry separated by a comma. Keep the outer square brackets and valid JSON syntax.
4. For the `image` field, use `images/blue-study.jpg` (match the filename exactly, including capitalization).
5. Set `type` to `Original composition`, `Study after [artist]`, or `Inspired by [artist]`. For reproductions, use `credit` to name the artist and source work.
6. Commit changes and refresh the site after deployment.

Tip: keep images reasonably compressed (ideally below 2 MB each). Don't upload works or reference images you don't have rights to publish. This version is intentionally a simple static website, not a visual content-management system.
