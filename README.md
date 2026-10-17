# Oceans Whispering: pin images

Public pin images for Oceans Whispering's Pinterest bulk uploads. Images only: no drafts or notes live here (those stay in the private `oceanswhispering` repo).

## How to add pin images

1. Open the folder for the post (for example `what-to-wear-in-sicily`).
2. Click **Add file → Upload files**, drag in the images, and click **Commit changes**.
3. Name each file `<number>-<short-description>.png` (or `.jpg`), for example `1-taormina-dinner.png` or `2-4-look-grid.png`. The number is the pin order; the description helps Claude match the caption.
4. Best size: 1000 x 1500 px (2:3). PNG or JPG.

A new post gets a new folder named after its blog slug (the end of its URL, `oceanswhispering.com/blog/<slug>`). To make one on GitHub: **Add file → Create new file**, type `<slug>/README.md`, add any text, and commit. Or just ask Claude.

## What happens next

Claude reads the folder, writes each pin's title, description, tags, board, and publish date, and builds the CSV for Pinterest's **Import content → Upload CSV**. Pinterest copies each image to its own servers on import, so images can be cleared out after a batch is scheduled.
