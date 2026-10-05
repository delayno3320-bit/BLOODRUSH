BLOODRUSH – website package
===========================

What is in this folder
  index.html   the whole game (one file – nothing else is needed to run it)
  pack.zip     YOUR sounds, models, settings and key binds  (you add this, see step 2)
  .nojekyll    (leave it, GitHub Pages likes it)

How it works
  Put this folder on a website. When the page opens it looks for "pack.zip" next to index.html,
  downloads it once, saves it in the browser, and loads your files into the game by itself.
  When you replace pack.zip on the site, every computer picks up the new one next time the page opens.
  (Libraries are built into index.html, so the page does not need any other site to run.)


STEP 1 – put it online (GitHub Pages, free)
  1. Make a free account at github.com, then press New repository. Name it "bloodrush", Public, Create.
  2. Press "uploading an existing file", drag in everything from this folder
     (index.html, .nojekyll, README.txt and pack.zip), press Commit changes.
  3. Settings > Pages > Source: "Deploy from a branch" > Branch: main, folder: / (root) > Save.
  4. After about a minute your game is at   https://YOURNAME.github.io/bloodrush/
     Bookmark that on the school computer.

  Other option: Netlify – go to app.netlify.com/drop and drag this whole folder onto the page.
  Use it if your pack.zip is bigger than 25 MB (GitHub's website refuses bigger files).


STEP 2 – make pack.zip from your files (do this at home)
  1. Open the game (index.html), Options > MY FILES.
  2. Load your models and sounds (or press "Load a folder"), set your sliders and key binds.
  3. Press "Download my pack (.zip)".  You get bloodrush-pack.zip.
  4. Upload that file to the website next to index.html.
     Both names work: pack.zip or bloodrush-pack.zip.


UPDATING LATER
  * New sounds / models / settings:  make a new pack (step 2) and upload it over the old one.
    On GitHub: your repository > Add file > Upload files > drop it (same name = replaced) > Commit.
    On Netlify: Deploys > drag the folder again (the address stays the same).
  * New version of the game:  upload the new index.html the same way.
  Give it a minute, then reload the page. The menu (Options > MY FILES) says when the pack was loaded.


ON THE SCHOOL COMPUTER
  * First visit downloads your pack (a few seconds). After that it is saved in the browser.
    If the school wipes browser data when you sign out, it just downloads again next time.
  * Click on the game once so sound and the mouse lock can start.
  * If the page does not open at all, the school's filter may be blocking that website – I could not test your
    school network, so that is something to check on the school computer itself.
