# Next Subfolder Struggles
Hey all! I love Next.js + Now, but have identified a bug. This repo is an attempt to reproduce it.

I am currently running `now dev` on Windows 10. To install:

1. `git clone` this repo
2. `yarn install` (or use npm, if you so choose)
3. `now dev`

I would expect all of the following pages to work, but only some do:
```
✅ http://localhost:3000/
✅ http://localhost:3000/a
❌ http://localhost:3000/b
❌ http://localhost:3000/a/c
```

However, in the production Now environment, everything works great!
https://next-subfolder-struggles.pulljosh.now.sh/