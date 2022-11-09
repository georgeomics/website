---
##  Managing a custom domain for your GitHub Pages site
---
UPDATED 06/07/2020

FROM: https://help.github.com/en/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site

(NOTE: It's better to read the article starting with the "Configuring an apex domain" part of the tutorial)

Basically, you will need to setup your apex domain (e.g. georgeomics) and subdomain (e.g. www) in <https://domains.google.com/m/registrar/georgeomics.com/dns>

"To set up an apex domain, such as example.com, you must configure a CNAME file in your GitHub Pages repository and an ALIAS, ANAME, or A record with your DNS provider.

If you are using an apex domain as your custom domain, we recommend also setting up a www subdomain. If you configure the correct records for each domain type through your DNS provider, GitHub Pages will automatically create redirects between the domains. For example, if you configure www.example.com as your custom domain for your site, and you have ALIAS and CNAME records set up for the apex and www domains, then example.com will redirect to www.example.com."
