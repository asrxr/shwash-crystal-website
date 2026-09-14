SHWASH CRYSTAL LIGHTING - WEBSITE
=================================

WHAT IS IN HERE
  index.html      the whole website
  images/         all photographs, WebP format

HOW TO PUT IT ONLINE (free, about five minutes)
  1. Go to app.netlify.com and make an account.
  2. Choose "Add new site", then "Deploy manually".
  3. Drag this entire folder onto the drop zone.
  4. Netlify gives you a live address straight away. You can point a
     custom domain such as shwashcrystal.com at it from Site settings.

HOW TO PREVIEW IT ON YOUR OWN COMPUTER
  Double click index.html. It opens in your browser. Keep index.html and
  the images folder together or the photographs will not load.

HOW TO CHANGE THINGS
  All the text lives in one place near the bottom of index.html, inside a
  block that starts with "var T = {". English sits under "en:" and Bangla
  under "bn:". Edit the words between the quote marks and save.

  Product details live just below that, in "var P = [". Each fixture has a
  code, a name, a description and a list of specifications, in both
  languages.

  To swap a photograph, replace the file in images/ keeping the same
  filename.

THE PHONE NUMBER
  The landline reads 02-9354734, taken from a business card that was partly
  smudged. Please check it before sharing the site widely.

STILL TO FILL IN (search index.html for "[confirm")
  The new chandelier (SCL-C1 to C5) and wall light (SCL-W1 to W6) entries
  in "var P = [" have their wattage, size and price written as
  "[confirm with showroom]" in English and "[শোরুমে জিজ্ঞাসা করুন]" in
  Bangla, because that detail was not available when they were written.
  Search the file for "confirm" to find every spot and replace it with the
  real number once you have it.

  The price line just under the collection filters (search for "cprice")
  lists a starting price per category, currently all "৳[confirm]". Same
  idea, replace with real numbers when ready.

  Installation terms (search for "i7a") currently just say "Ask in the
  showroom or on WhatsApp" because the exact policy was not settled yet.

IF YOU GET A CUSTOM DOMAIN
  Near the top of index.html, in the <head>, there are a few lines
  starting "og:image" and "twitter:image" pointing at "images/hero.webp".
  Once the site has a permanent web address (e.g. shwashcrystal.com),
  change that to the full address, like
  "https://shwashcrystal.com/images/hero.webp", so link previews on
  WhatsApp and Facebook can find the picture.
