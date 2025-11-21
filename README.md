# Siphiwe-Trinity-Ndlovu-Nyadongo2
# Simple Static Blog (index.html)

This is a single-file static blog (index.html) that:
- Lets you create, edit, view, delete posts.
- Stores posts in browser localStorage.
- Supports Markdown content (rendered & sanitized using marked + DOMPurify in a new window).
- Export/import posts as JSON.
- Light/dark theme with persistence.

How to use locally
1. Save `index.html` into a folder.
2. Open `index.html` in your browser (double-click or drag into the browser).
3. Click "New Post" to add content. Use Markdown in the Content field.
4. Use "Export" to download your posts as JSON and "Import" to restore or transfer.

Quick deploy options (right now)
- GitHub Pages (free)
  1. Create a new GitHub repository (public is fine).
  2. Add `index.html` to the repository root and push.
  3. In repo Settings → Pages, set Source to the main branch root (/) and save. The site will be published at `https://<your-username>.github.io/<repo>/` within a minute or two.

- Netlify (drag & drop)
  1. Go to https://app.netlify.com/drop
  2. Drag the folder (containing `index.html`) onto the page.
  3. Netlify will publish a URL immediately.

- Vercel (static)
  1. Install Vercel CLI or connect your GitHub repo in https://vercel.com.
  2. Deploy the repo; Vercel will detect a static site and publish it.

Notes and limitations
- This is client-side only. Images or large content in localStorage are not ideal for backups; use Export to keep a copy.
- If you want a real, shareable, server-backed blog (with SEO-friendly pages, images, and server-side storage), I can:
  - Convert this to a static site generator (Eleventy/Next.js) with markdown files,
  - Add a GitHub Action to build & deploy,
  - Or set up a simple backend (Firebase, Supabase) for persistent storage.

If you want, I can:
- Create a GitHub repository and push these files for you (I’ll need repo name and whether it's public/private).
- Add a small GitHub Action workflow that deploys to GitHub Pages automatically on push.
- Add live Markdown preview in the editor (so you see formatted content while writing).
Tell me which of those you want and I’ll generate the required files or instructions next.
