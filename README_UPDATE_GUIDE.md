# Guide to Update README with the HTML Dashboard

This guide explains how to place the provided HTML code into `README.md`.

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd X
   ```
2. **Create a working branch** (optional but recommended)
   ```bash
   git checkout -b update-readme
   ```
3. **Edit `README.md`**
   Replace the existing text or append the HTML snippet. Because GitHub does not render raw HTML in README files, wrap the snippet in a fenced code block:
   ```html
   <!DOCTYPE html>
   <html lang="pt-BR">
   <!-- truncated for brevity -->
   </html>
   ```
   Alternatively, link to an external HTML file if the snippet is large.
4. **Preview your changes**
   Ensure the code block displays correctly in your Markdown previewer.
5. **Commit the update**
   ```bash
   git add README.md
   git commit -m "Document HTML dashboard in README"
   ```
6. **Push and open a pull request**
   ```bash
   git push origin update-readme
   ```
   Then create a pull request on your Git hosting service to merge the changes.
