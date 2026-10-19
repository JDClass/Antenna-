# Antenna Learning Modules

Interactive teaching website for antennas: live simulations, working principles, key equations and MCQ tests.

| Page | Contents |
|---|---|
| `index.html` | Home page with links to all chapters |
| `chapter1.html` | Antenna parameters |
| `chapter2.html` | Linear and planar arrays |
| `chapter3.html` | HF, UHF and microwave antennas |
| `config.js` | Settings (feedback form link) |

Everything runs in the browser. There is no server, database or build step.

## Publish on GitHub Pages

1. Create a new **public** repository on GitHub (for example `antenna-modules`).
2. Click **Add file → Upload files**, drag in all the files from this folder (including `.nojekyll`), and click **Commit changes**.
3. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/antenna-modules/`.

## Set up the feedback form

1. Create a Google Form (for example: name, register number, topic, rating, comment).
2. In the form, click **Send → link icon** and copy the link.
3. In the repository, open `config.js`, click the pencil icon, paste the link between the quotes of `feedbackFormUrl`, and commit.

Responses then collect in the Google Form (and its linked Google Sheet). Until a link is set, the feedback section says the form has not been set up yet.

## Updating content

Edit any `.html` file on GitHub (pencil icon) and commit. GitHub Pages republishes automatically within a minute or two.
