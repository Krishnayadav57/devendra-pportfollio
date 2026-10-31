# Devendra Kumar Yadav – Portfolio Website

A single-page, fully animated portfolio website for **Devendra Kumar Yadav**, Civil Engineer and CEO of **JMC Construction and Engineering Pvt. Ltd.**, Siraha, Nepal.

Built with plain HTML, CSS and JavaScript in one file (`index.html`). No build tools or frameworks needed.

## Features

- Animated loading screen and moving network background on the home screen
- Typing effect, scroll-reveal animations, animated counters and skill bars
- Sections: Home, About, Company (JMC), Services, Skills, Experience timeline, Education, Projects (filterable), Gallery, Contact
- **Download CV** buttons
- Floating **WhatsApp** and **Facebook** buttons
- Contact form that sends by email or WhatsApp, plus an embedded Google Map
- Dark / light theme toggle (remembered between visits)
- Mobile-friendly layout with slide-out menu
- Scroll progress bar and back-to-top button

## Folder structure

Keep these files together in the same folder:

```
portfolio/
├── index.html
├── README.md
├── photo-suit.jpg                      (suit photo – hero, About, Gallery)
├── photo-jacket.jpg                    (blue jacket photo – About, Gallery)
└── Devendra_Kumar_Yadav_CV_v4.pdf      (CV used by the Download CV buttons)
```

If a photo is missing, the site shows a placeholder icon instead.

## How to run

1. Put all the files above in one folder.
2. Double-click `index.html` to open it in a browser.

An internet connection is needed for the Google Fonts, Font Awesome icons and the map.

## Customisation

### Settings (top of the `<script>` section in `index.html`)

```js
const FACEBOOK_URL = "https://www.facebook.com/";  // put the real Facebook profile/page link
const WHATSAPP_NUMBER = "9779813019707";           // country code + number, no + or spaces
const EMAIL = "dy48495@gmail.com";
```

### Content to review

- **Services and Projects:** based on the CV. Edit the text in the `#services` and `#projects` sections to match the company's actual work.
- **Skill percentages:** estimates. Change the `data-w` values on the `.bar-fill` elements and the matching percentage text.
- **Stats:** change `data-to` on the `.count` elements.
- **Project images:** the project cards use icons and colour gradients. To use real photos, replace the `.bg` content of a `.proj` card with an `<img>`.
- **Colours:** edit the CSS variables under `:root` (`--accent` is the gold colour).

### Privacy note

The website does not show the citizenship number, parents' names or date of birth. The downloadable CV PDF does contain them, so consider using a public version of the CV without those details.

## Hosting (free options)

- **Netlify Drop:** drag the folder to <https://app.netlify.com/drop>
- **GitHub Pages:** upload the files to a repository and enable Pages in Settings
- **Vercel:** import the folder as a static site

## Contact

- Email: dy48495@gmail.com
- Phone / WhatsApp: +977-9813019707
- Address: Aurahi-04, Siraha, Nepal
