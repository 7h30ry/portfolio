# Paul Ige Portfolio

Static site: `index.html`, `images/`, `CV_Paul_Ige.pdf`. No build step.

## Deploy to Vercel
    npm i -g vercel && cd portfolio && vercel --prod

Or push this folder to a GitHub repo and import it at vercel.com/new (Framework preset: Other).

## Adding a photo to an award
Drop the image in `images/`, then in `index.html` find the award in the `awards` array and set
`img:"images/your-file.jpg", credit:"Photo: Source"`.
