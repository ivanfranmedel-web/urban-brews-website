# Urban Brews ☕

> *Where every cup tells a story*

🔗 **Live site: https://ivanfranmedel-web.github.io/urban-brews-website/**

A six-page website for Urban Brews, a made-up coffee shop in Dublin City. It was our CA2 group project in first year: four people, one shared codebase, plain HTML and CSS.

<!-- To add a screenshot: save one of your home page as screenshot.png in this repo, then delete this line's comment tags:
![Urban Brews home page](screenshot.png)
-->

## Pages

| Page | File |
| --- | --- |
| Home | `index.html` |
| Menu | `menu.html` |
| About Us | `about.html` |
| Join Us (Careers) | `careers.html` |
| Login / Sign up | `login.html` |
| Public Review | `review.html` |

## Team

| Name | Contribution |
| --- | --- |
| **Chaimae** | Home page (HTML), images |
| **Ivan** | About Us page (HTML), stylesheet |
| **Jose Lo** | Login page (HTML), Join Us page (HTML), stylesheet |
| **Oleksandr** | Server hosting |

## My part

I built the About Us page and worked on `css/style.css`, the roughly 365-line stylesheet that all six pages share. Four of us were writing pages at the same time, so the styles had to work for everyone's HTML, not just mine. The layout runs on flexbox (header, nav bar, content boxes, cards), and the site has three different forms: login/sign-up, a job application, and a customer review form.

This was also the first time I put a project on GitHub and published it as a live site.

## What's not finished

I'd rather say this up front than have you find it:

- **The forms don't do anything yet.** Login, sign-up, applications and reviews are front-end only. There's no backend, so nothing gets submitted or saved.
- **The reviews are typed straight into the HTML.** New reviews won't show up.
- **No mobile layout.** The CSS has no media queries, so the site is built for a desktop screen and looks cramped on a phone.

Next I want to fix the mobile layout, then learn enough JavaScript to make the forms validate their input.

## Built with

HTML5 and CSS3. No frameworks or libraries.

## Project structure

```
├── index.html
├── menu.html
├── about.html
├── careers.html
├── login.html
├── review.html
├── css/
│   └── style.css
└── img/
    ├── 60P9094.jpg
    ├── logo.png
    └── wallpaper-6380532_960_720.webp
```
