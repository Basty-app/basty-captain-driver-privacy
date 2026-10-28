# Basty Captain website pages

These files are for the public GitHub repository `Basty-app/basty-captain-driver-privacy`. In that repository, use this layout:

```text
README.md
index.html
contact/
  index.html
```

`index.html` is the Privacy Policy. `contact/index.html` is the Contact Us page. The pages link to each other using relative paths.

## Check with the client before publishing

The client supplied **Basty** as the company name and **Basty@info.ly** as the privacy contact and deletion-request email. The client also confirmed that driver location is used for map/routing and that Basty does not store live location or location history on its server. Confirm that the descriptions of other server storage, record retention, and any other backend services match the client's actual practices. Update both the English and Arabic text and the “Last updated” date if you change the policy. Do not publish inaccurate statements.

The app's current Terms text says “Basty Tech Co.” while this policy says “Basty.” Confirm the intended legal name and make the two documents consistent before submitting the store listing.

## Move the Contact Us page into a folder on GitHub

1. Upload the local `contact/index.html` file to the GitHub repository, preserving the `contact` folder. In GitHub's web editor, you can also create a file named `contact/index.html` and paste the contents of the local file.
2. Replace the repository's root `index.html` with the updated local `index.html` so its Contact Us links point to `contact/`.
3. Delete the old root `contact.html` after the new page is live.
4. Keep GitHub Pages set to **Deploy from a branch → main → /(root)**.

The public URLs are:

- Privacy Policy: `https://basty-app.github.io/basty-captain-driver-privacy/`
- Contact Us: `https://basty-app.github.io/basty-captain-driver-privacy/contact/`

Open both URLs after deployment and test the links between them. Use the Privacy Policy URL in the Play Console **Privacy policy** field.

The page is plain HTML and CSS. It has no build step, external fonts, scripts, cookies, or analytics code.

## Keep it current

Review this policy when the app adds new data collection, integrations, or permission use. Keep the Play Console Data safety form consistent with the published policy and the app's actual behavior.
