# sarahwestcott.com


### Build and Test Locally

Before pushing changes, test the site locally:

```bash
bundle exec jekyll serve
```

If using a `baseurl`, access the site at:

```
http://localhost:4000/your-repo/
```



## Deploying Jekyll Site to GitHub Pages

### Configure GitHub Pages

1. Navigate to your repository on **GitHub**.
2. Go to **Settings** > **Pages**.
3. Under **Source**, select the `main` branch and click **Save**.
4. Your site will be available at `https://swfinancial.github.io/sarahwestcott.com/` after a few minutes.

### Configure `baseurl` in `_config.yml`

#### We Have a Custom Domain

Set `baseurl` to an empty string:

```yaml
baseurl: "" # Leave empty if using a custom domain
url: "https://sarah-westcott.com "
```

**be sure** to click "Enforce HTTPS" as this will add an appropirate certificate.





### Commit and Push Changes

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
