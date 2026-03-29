This reposity includes my blog posting. 

## Makoing a public link for a Markdown file
To provide a public link for a Markdown file hosted on **GitHub Pages** (your `jskdr.github.io` site), you follow a specific conversion rule.

GitHub Pages automatically processes your repository and serves it as a website. Here is the logic for your specific file:

### The Rule
1.  **Change the Domain:** Move from `github.com/user/repo/blob/master/` to `user.github.io/`.
2.  **Keep the Path:** Keep the folder structure (e.g., `/blogs/`).
3.  **Change the Extension:** Change `.md` to **`.html`**.

---

### Your Specific Link
For the file you are currently viewing:
* **Repository Path:** `blogs/long_post_in_x.md`
* **Public Link:** **`https://jskdr.github.io/blogs/long_post_in_x.html`**

### Summary for your README.md
You can add this snippet to your `README.md` so you don't forget the format:

```markdown
### 🔗 How to Link to Blog Posts
To share a post on X (Twitter), use the GitHub Pages URL format:
- **Format:** `https://jskdr.github.io/[folder]/[filename].html`
- **Example:** [Long Post in X](https://jskdr.github.io/blogs/long_post_in_x.html)
```

> **Note:** If you try to use the `.md` extension in the link, the browser will often try to download the file or show raw text instead of rendering it as a nice webpage. Always use **`.html`** for the public-facing link.

Would you like me to check if your GitHub Pages is already correctly configured to serve these files?
