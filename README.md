# roster-f21

## TODO LIST
- [ ] Create Instructor Admin
- [ ] Verify if we need to use [netlify identity widget](https://github.com/netlify/netlify-identity-widget)
- [ ] find a default avatar image
- [ ] find a set of default cool fonts
- [ ] add fonts to admin panel
- [ ] decide to pull default colors from cms, or to declare them in the template
  - lilyx-note: If declared in the cms, there will be less code in the template, if declared in the template, we will need to use a conditional to set up a default color. 
## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out the [documentation](https://nuxtjs.org).

---
## CMS Prep Notes
- Student Panel:
  - Name
  - Tagline
  - Socials
    - Email
    - GH
    - Codepen
    - Instagram
    - Facebook
    - Twitter
    - LinkedIn
    - Youtube
  - Color Theme
    - Dominant Color
    - Secondary Color
  - Typography
    - Title Text
    - Body Text
  - Avatar
- Instructor Panel
  - Trophies
    - Main Trophy
      - MVP(Most Valuable Programmer) (icon + text)
      - Coach of the Year (icon + text)
      - Special Teams (icon + text)
    - +1
  - Badges
    - Perfect Attendance
    - Code Warrior
    - Early Riser
  