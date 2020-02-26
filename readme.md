This is a complete Hugo theme for a blog.
## How to install
Go to [link here](https://gohugo.io/getting-started/installing/)  to learn how to install a theme in your hugo website. But a general tip is by following command below, simply change directory to themes like mywebsite/themes/
```bash
cd themes #asuming you're in hugo site directory.
```
then clone theme repo here in themes directory by following command
```bash
git clone https://github.com/minaminfo/Gaunt-theme-for-hugo.git Gaunt
```
**Don't have git installed or don't understand it?**
Simply go to **Clone or download**(preivew below) button above and download it as a ZIP file. Then extract(unzip) it into `themes directory `.
[![Screenshot-2020-02-26-minaminfo-Gaunt-theme-for-hugo.png](https://i.postimg.cc/brTGDBnG/Screenshot-2020-02-26-minaminfo-Gaunt-theme-for-hugo.png)](https://postimg.cc/bSZY4L38)

###Let's activate this theme
Go to [link here](https://gohugo.io/getting-started/installing/)  to learn how to install a theme in your hugo website.  Or in simple words edit `config.toml` file in your site directory and set theme like `theme = Gaunt`.
Make sure theme directory/folder name  is Gaunt --- same as you're giving in `config.toml`.

---

##About this Theme

- It's **fast** as no external dependency. Whole of the CSS is minimized and jank-free. CSS is less than 10KB in size and no external JavaScript.
- Full **Accessibility** support
- **PWA** enabled
- Option to show/hide sidebar

###Technical details

The tailwindcss starter theme https://github.com/minaminfo/hugo-theme-tailwindcss-starter which is fork of dirkolbrich [starter theme](https://github.com/dirkolbrich/hugo-theme-tailwindcss-starter)  is the base of this theme. Learn more [tailwind css](tailwindcss.com) 