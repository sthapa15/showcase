RUKI — PORTFOLIO SITE
=====================

FOLDER STRUCTURE
  portfolio-site/
    index.html                 <- your website (open this in the browser)
    images/
      splash.jpg               <- your hero splash photo (add this)
      social/                  <- Social Media pieces
      flyers/                  <- Flyer pieces
      newsletters/             <- Newsletter pieces

HOW TO WORK ON IT
  1. Open this whole folder in VS Code: File > Open Folder > portfolio-site
  2. Drop your images into the matching images/ subfolders.
     Use lowercase names with dashes, no spaces (e.g. summer-campaign.jpg)
  3. In index.html, point each piece at its image, e.g.
        data-img="images/social/summer-campaign.jpg"
     For the splash photo, replace the <div class="splash-img"> block with:
        <img src="images/splash.jpg" class="splash-img" alt="Ruki">
  4. Preview live: install the "Live Server" extension in VS Code,
     then right-click index.html > "Open with Live Server".

HOSTING (free, static)
  - Netlify: go to app.netlify.com/drop and drag this folder in. Instant live link.
  - GitHub Pages: push this folder to a repo, enable Pages in Settings.
  Either way index.html is served automatically as the homepage,
  so keep that filename exactly.
