---
layout: page
title: Setup
---
---
> Head over to Netlify and signup for a free account: <a href="https://app.netlify.com/signup" target="_blank">https://app.netlify.com/signup</a>

> In your Netlify panel, create a new site from a Git repo:  

<img src="https://s3.amazonaws.com/lanyon-netlify/install-01.png"/>

> Choose GitHub (GitLab is useful if you want to have your website source entirely private):  

<img src="https://s3.amazonaws.com/lanyon-netlify/install-02.png"/>

> Netlify will scan the `Gemfile` and `_config.yaml` and detect the correct build parameters:  

<img src="https://s3.amazonaws.com/lanyon-netlify/install-03.png"/>

> Your site's deployment will commence using Netlify's infrastructure. It should take less than a minute. In the meantime, you can change your desired site name:  

<img src="https://s3.amazonaws.com/lanyon-netlify/install-04.png"/>

<img src="https://s3.amazonaws.com/lanyon-netlify/install-05.png"/>

<img src="https://s3.amazonaws.com/lanyon-netlify/install-06.png"/>

> After you've configured your site URL your deployment shoud be complete by now. You'll see your associated URL in green and your deployment log now accessible:  

<img src="https://s3.amazonaws.com/lanyon-netlify/install-07.png"/>

<img src="https://s3.amazonaws.com/lanyon-netlify/install-08.png"/>

---

Netlify supports using a custom domain name via CNAME flattening; see the documentation for that here: <a href="https://www.netlify.com/docs/custom-domains/#manual" target="_blank">https://www.netlify.com/docs/custom-domains/#manual</a>  

**TL;DR**   

- create a root CNAME that matches `yourdomain.com` to `yourdomain.netlify.com`  
- create a www CNAME that matches `www.yourdomain.com` to `yourdomain.netlify.com`  

---

**Credits**  

If you love the JAMstack you'll love Netlify, so check them out: <a href="https://www.netlify.com" target="_blank">https://www.netlify.com</a>  

Mark Otto created the original Lanyon theme, so follow him: <a href="https://github.com/mdo" target="_blank">https://github.com/mdo</a>