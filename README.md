# fernaspiazu.github.io

## Build and Serve Locally

1. **Install dependencies** (if not already):
   ```bash
   gem install bundler jekyll
   bundle install
   ```

2. **Build the site**:
   ```bash
   bundle exec jekyll build
   ```

3. **Serve locally with live reload**:
   ```bash
   bundle exec jekyll serve --livereload
   ```
   The site will be available at [http://localhost:4000](http://localhost:4000)

## Deploy
Push your changes to the `main` branch of this repository on GitHub. GitHub Pages will automatically build and deploy your site.