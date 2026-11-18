# Customer Churn Intelligence System: capstone presentation

Presentation for my Summer Internship-I capstone (course code 21INT58) at Bluemind Solutions Pvt. Ltd., Mysuru.

Abhishek Rai A. · USN 24SEAI003 · V Semester, AI&ML · Mysore University School of Engineering, University of Mysore
Mentor: Dr. Santhosh Kumar K. S.

Project code: https://github.com/Abhirai2006/telco-churn-intelligence-system

## What is in this repository

`index.html` is the whole presentation in one file. It works online and offline, and Cloudflare serves it from the root through `wrangler.jsonc`.

## Deploy on Cloudflare

`wrangler.jsonc` tells Cloudflare to serve `index.html` as a static site, so no build step is needed.

1. In GitHub Desktop: File, Add local repository, pick this folder, then Publish repository.
2. In the Cloudflare dashboard: Workers & Pages, Create application, Import a repository. Choose this repository.
3. Build command: leave empty.
4. Deploy command: `npx wrangler deploy` (the default).
5. Save and Deploy. Cloudflare gives you a `*.workers.dev` address. Every push to GitHub redeploys on its own.

To change a slide, edit `index.html`, then commit and push.

## Presenting

Open the site in Chrome and press F for full screen.

| Key | Action |
| --- | --- |
| Right arrow, Space, click on the right | Next slide |
| Left arrow, click on the left quarter | Previous slide |
| A number, then Enter | Jump to that slide |
| P | Presenter window with speaker notes |
| N | Speaker notes on the same screen |
| R | Replay the current slide's animation |
| B | Blank screen |
| ? | All keys |

On the first slide you can grab the ID card with the mouse and throw it; it swings back on its strap.
The live cutoff demo is slide 18: drag the slider, then press "Back to 0.485".

## Credits

* Data: IBM Telco Customer Churn sample dataset.
* Fonts: Inter, Bricolage Grotesque and Caveat (SIL Open Font License), Yellowtail (Apache License 2.0).
* Illustrations: unDraw, from the balazser/undraw-svg-collection repository, recoloured.
