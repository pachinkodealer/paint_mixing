# Mixing Paint: Drag, Mix, Learn

An interactive guide to paint color in a single HTML file. Drag paint blobs together to watch them mix, take a two-minute tour, or dig into the numbers behind 403 Bob Ross paintings.

**Live site:** https://pachinkodealer.github.io/paint_mixing/

## What's inside

- **Paint table.** Drag two paints together and see what they make, with the ratio and hex code.
- **Two-minute tour.** A quick click-through with a mixing demo and a three-question quiz.
- **Full guide.** A two-paint mixer, the split-primary color wheel, 12 recipes, five statue painting studies, and six mixing habits.
- **Bob Ross, by the numbers.** A guessing game, shareable facts, and four charts built from real data on all 31 seasons.
- **Mix lab.** Every pair of 10 paints, mixed one to one and scored for how clean the result stays.

## Run it

It's one file, `index.html`, with no build step or dependencies. Open it in a browser, or host it on GitHub Pages by going to **Settings, then Pages** and choosing the `main` branch and the `/root` folder.

## How the mixing works

Real paint mixes subtractively, so blue plus yellow gives green instead of gray. The page approximates that with a weighted geometric mean of each paint's light reflectance, and it gives strong pigments like phthalo blue more pull. The results are good estimates, not lab measurements, so test real paint on your own surface.

## Data sources

- Painting colors: [Bob Ross Paintings](https://github.com/jwilber/Bob_Ross_Paintings) by Jared Wilber
- Painting subjects: [FiveThirtyEight's Bob Ross data](https://github.com/fivethirtyeight/data/tree/master/bob-ross)

## Credits

Built by [Ian Lee](https://clairvoyanthoughts.net) ([@pachinkodealer](https://github.com/pachinkodealer)).

The Bob Ross sections are an unofficial fan tribute and are not affiliated with or endorsed by Bob Ross Inc.
