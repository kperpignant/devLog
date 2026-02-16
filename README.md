# devLog

## Local development

1. Install dependencies: `npm install`
2. Start the server: `npm start`
3. Open http://localhost:3000 in your browser.

## Making posts

1. **Create a Markdown file** in the `posts/` folder. Use a slug for the filename (e.g. `posts/my-first-post.md`).
2. **Add an entry to `posts.json`** with the post metadata:

   ```json
   { "title": "My First Post", "date": "2025-02-16", "file": "my-first-post" }
   ```

   - `title`: Display title on the index and post page
   - `date`: Publication date (YYYY-MM-DD)
   - `file`: The slug—must match the filename without `.md`

3. The post will appear on the homepage and at `post.html#my-first-post`.

Order in `posts.json` determines listing order (newest first by default).

## Deploying to GitHub Pages

Pushes to `main` automatically deploy to `https://kperpignant.github.io/devlog/`.

**One-time setup:** Add a `PAGES_DEPLOY_TOKEN` secret to this repo:

1. Create a [Personal Access Token](https://github.com/settings/tokens) with `repo` scope.
2. In this repo: **Settings → Secrets and variables → Actions** → **New repository secret**.
3. Name: `PAGES_DEPLOY_TOKEN`, Value: your token.

The workflow copies the blog into the `devlog/` folder of `kperpignant.github.io`.