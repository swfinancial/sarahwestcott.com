# sarahwestcott.com



## Deploying Jekyll Site to GitHub Pages

### **Step 1: Configure GitHub Pages**

1. Navigate to your repository on **GitHub**.
2. Go to **Settings** > **Pages**.
3. Under **Source**, select the `main` branch and click **Save**.
4. Your site will be available at `https://your-username.github.io/your-repo/` after a few minutes.

### **Step 2: Configure `baseurl` in `_config.yml`**

#### **If You Don't Have a Custom Domain**

Set the `baseurl` to the repository name:

```yaml
baseurl: "/your-repo" # Change to match your GitHub repo name
url: "https://your-username.github.io"
```

#### **If You Have a Custom Domain**

Set `baseurl` to an empty string:

```yaml
baseurl: "" # Leave empty if using a custom domain
url: "https://your-custom-domain.com"
```

### **Step 3: Build and Test Locally**

Before pushing changes, test the site locally:

```bash
bundle exec jekyll serve
```

If using a `baseurl`, access the site at:

```
http://localhost:4000/your-repo/
```

### **Step 4: Commit and Push Changes**

After updating `_config.yml`, commit and push:

```bash
git add .
git commit -m "Update baseurl settings"
git push origin main
```





====================
Agency Jekyll theme
====================

Agency theme based on [Agency bootstrap theme ](https://startbootstrap.com/template-overviews/agency/)

# How to use

###Portfolio 

Portfolio projects are in '/_posts'

Images are in '/img/portfolio'

###About

Images are in '/img/about/'

###Team

Team members and info are in '_config.yml'

Images are in '/img/team/'


# Demo

View this jekyll theme in action [here](https://y7kim.github.io/agency-jekyll-theme)

=========
For more details, read [documentation](http://jekyllrb.com/)
