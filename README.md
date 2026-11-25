# threeKnots — Stage 1 Frontend

Premium editorial-style Christian matrimonial website frontend built with HTML5, CSS3 and vanilla JavaScript.

## Run locally
Open `index.html` directly in a browser, or use a local static server.

## Pages / hash routes
Home `#home`, Our story `#about`, How it works `#how`, Registration `#register`, Login `#login`, Forgot password `#forgot`, Browse profiles `#browse`, Profile preview `#profile?id=1`, Dashboard `#dashboard`, Edit profile `#edit-profile`, Sent interests `#sent`, Received interests `#received`, Membership `#plans`, Safety centre `#safety`, Privacy `#privacy`, Terms `#terms`, Contact `#contact`.


## Important demo limitations
- This is frontend-only. No authentication, storage, email, payment or API functionality is active.
- Sample profiles are fictional and marked illustrative.
- Profile preview contains only two photo slots, name, age and city.
- Photos use remote Unsplash URLs with fallback image handling. For production, replace with licensed/approved image assets.
- `public/` contains a mirrored frontend for Cloudflare Workers Static Assets.

## GitHub Pages subdirectory
All local script and stylesheet references use relative paths (`./styles.css`, `./app.js`). Hash-based routing avoids root-relative route assumptions.
