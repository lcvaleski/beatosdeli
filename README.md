# beatosdeli

**First Git setup instructions:** 

1. In Mac terminal, navigate to the `Desktop` directory. Ask google how to do this.
2. Then type `git@github.com:lcvaleski/beatosdeli.git`
3. Then `cd beatosdeli`. You are now in the folder.
4. Open this up with Visual Studio Code, or Cursor if you already have it installed.
5. **Cursor AI will be helpful for you to learn there is no shame in AI coding as long as you are doing it thoughtfully**

**Hi Ellie,** here's the setup so far. When you `git add .`, `git commit -m ""`, and then `git push` from this repository, this is noticed by Cloudflare, which provides a service called "pages":

**Cloudflare Pages** is a platform for deploying websites directly from your Git repository (such as GitHub) to Cloudflare’s global edge network. Here’s what it’s actually doing:

    Build Automation: When you connect your GitHub repository, Cloudflare Pages automatically runs your site’s build process every time you push code. This means it installs dependencies, runs your static site generator or build scripts, and produces the final static assets (HTML, CSS, JS, images, etc.)

    Global Deployment: Once built, the static assets are instantly deployed to Cloudflare’s edge network, which spans data centers around the world. This ensures your site loads quickly for visitors no matter where they are located

    Continuous Integration: Every code change (commit) triggers a new build and deployment, so your site is always up to date with your repository’s latest state. You can preview changes before going live, and roll back if needed


    Security and Performance: Your site benefits from Cloudflare’s security features (like DDoS protection and SSL) and performance optimizations by default.


**beatosdeli.com is** now hooked up to beatosdeli.pages.dev (a site Cloudflare creates), and so when you search beatosdeli.com it shows whatever we write in our code.

It will take up to 48 hours for Cloudflare to propogate this hook up to the world. In the meantime, fool around with index.html. You can pop it into AI and ask for a change then study the change. If you go into your folder and double click on index.html, it will load locally in your browser so you can see the results.