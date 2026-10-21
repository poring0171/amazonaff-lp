HOW TO ADD A NEW CATEGORY
1. Duplicate _new-category-template.html and rename it, e.g. pets.html (lowercase, no spaces).
2. Open it in a text editor. Change the title, heading, text, and each Amazon link
   (replace PASTE-YOUR-AMAZON-LINK with your SiteStripe / amzn.to link).
3. Put your images in the images folder (e.g. pets-1.jpg) and update the file names.
4. In index.html, copy one <a class="cat"> block and point it to pets.html.
   Also add <a href="pets.html">Pets</a> to the nav line on every page.
5. Re-upload the whole folder to Netlify (drag and drop).

PINTEREST
- Open index.html and paste your Pinterest meta tag where marked, then upload and click Verify.
- Use the page link for each category (yoursite.netlify.app/kitchen.html) as the Pin destination.

AMAZON RULES
- Replace YOUR SITE NAME. Keep the Associates disclosure on every page.
- Use your own photos or images from Amazon SiteStripe / Product Advertising API. Don't save other images from Amazon pages.
- Don't show fixed prices.
