STEPHEN’S WHEEL: put it on your phone (no App Store)

You need two steps: (1) put this folder on a free web address, (2) add that address to your home screen.
Apps like this need to be served from a real https address, so you can’t just open the files from your phone.

STEP 1: PUT IT ONLINE (pick one)

Option A, Netlify Drop (easiest, best from a computer)
  1. Go to app.netlify.com/drop
  2. Unzip this download, then drag the whole "stephens-wheel" folder onto the page.
  3. Netlify gives you an address like something.netlify.app. That is your app.

Option B, GitHub Pages (works from a phone)
  1. Make a free account at github.com and create a new public repository.
  2. Choose "Upload files" and upload everything from this folder (index.html, sw.js, manifest.webmanifest, and the .png files).
  3. In the repository, open Settings, then Pages. Set the source to the main branch, root folder, and save.
  4. After a minute your app is at yourname.github.io/reponame

STEP 2: ADD IT TO YOUR HOME SCREEN

  iPhone:  open your address in Safari, tap Share, then Add to Home Screen.
  Android: open it in Chrome, tap the three-dot menu, then Install app (or Add to Home screen).

It then opens full screen with its own icon and works offline after the first load.

GOOD TO KNOW
  - Your stats are saved on the phone itself. They do not come over from the Claude version.
  - Use the app from the home screen icon each time. The Safari tab and the icon keep separate saved stats on iPhone.
  - To push an update later, replace the files, and change the version name at the top of sw.js (for example stephens-wheel-v3 to v4).

