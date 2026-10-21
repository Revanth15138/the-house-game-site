THE HOUSE — Website Starter
===========================

This is a static website for the Android horror game THE HOUSE.
Android package ID: com.revanth.thehouse
Status: In development; no APK is included.

FILES
-----
index.html           Website content
style.css            Responsive styling
script.js            Mobile menu and current year
assets/              Local SVG artwork and favicon

PREVIEW ON ANDROID
------------------
1. Extract the ZIP in your phone's Files app.
2. Open index.html with a browser, or use an HTML editor that supports preview.
3. Keep index.html, style.css, script.js, and the assets folder together.

PUBLISH FREE WITH GITHUB PAGES
------------------------------
1. Sign in or create an account at https://github.com/
2. Create a new public repository, for example: the-house-game-site
3. Upload all files and the assets folder. Upload index.html to the repository root.
4. Open the repository's Settings > Pages.
5. Under Build and deployment, choose "Deploy from a branch".
6. Choose branch "main" and folder "/ (root)", then Save.
7. Wait for the Pages deployment to finish. The public address appears in Settings > Pages.
   It commonly looks like https://YOUR-USERNAME.github.io/the-house-game-site/
8. Open the address on your phone and test the menu and sections.

ADDING THE APK LATER
--------------------
1. Build and test a real Android APK first.
2. Upload the APK to a trusted release/download host, such as a GitHub Release.
3. Edit index.html and replace the disabled "APK NOT AVAILABLE YET" span inside #download
   with a link, for example:
   <a class="button button-primary" href="YOUR-REAL-APK-URL">DOWNLOAD APK</a>
4. Only use a real, tested APK URL. Do not claim the APK is available before it is uploaded.

NOTES
-----
- This website does not create or compile the Android game.
- Package ID is displayed as project information; it does not verify an app build.
- No analytics, trackers, login, or paid services are included.
- The visuals are original, simple SVG illustrations included locally in the assets folder.
