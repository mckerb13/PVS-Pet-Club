# PVS Johns Creek Pet Club (prototype)

Static site: index.html is the whole app. No build step.

## Deploy to Vercel
1. Put this folder in a new GitHub repository.
2. In Vercel: Add New > Project > import the repository.
3. Framework Preset: Other. Leave Build Command and Output Directory empty. Deploy.

## Or deploy from the terminal
    npm i -g vercel
    cd pet-club-project
    vercel --prod

## Important
- Prototype only: no logins, and data is saved per browser. Do not enter real client information.
- vercel.json asks search engines not to list the site. Remove it once the secure backend is live.
