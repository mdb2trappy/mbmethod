# Larp Wallet

A parody wallet with editable fake balances. Not a bank and not connected to any real account. Plain HTML/CSS/JS, no build step.

## Put it on GitHub Pages
1. Create a new repository on github.com (public).
2. Upload `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png` and `apple-touch-icon.png` (drag them into **Add file > Upload files**) and commit.
3. Open **Settings > Pages**. Under Source choose **Deploy from a branch**, pick `main` and `/ (root)`, then Save.
4. After a minute your app is live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

## Add it to your home screen
- iPhone: open the link in Safari, tap Share, then Add to Home Screen.
- Android: open it in Chrome, tap the menu, then Install app or Add to Home screen.

## Hold to edit
Nothing in the app can be edited with a normal tap. Press and hold for 3 seconds:
- the account card on the home screen: edit balance, names, account details, footer, add or delete accounts, and the Customise screen
- "Edit widgets": show or hide home tiles
- an account row on the Accounts tab: edit that account
- the balance on an account page: add a transaction
- a transaction row: edit or delete it
- the "Contacts" title: add a contact. Hold a contact to edit or delete it
- the card on the Cards tab: change the last 4 digits
- the points number on the Rewards tab: change the points

## Edit everything
- In the app: tap the ••• on the card for balance, account names, your name, footer and extra accounts. Tap "Customise app" there for the app name, greeting, search suggestions, tile and menu labels and colours.
- iPhone uses the app name when you tap Add to Home Screen, so set the name first. Android uses `"name"` and `"short_name"` in `manifest.webmanifest`; edit them there, then reinstall.
- To change the defaults for everyone who opens your link, edit the `DEF` line near the top of the script in `index.html`.
- Your values are saved in the browser on each device, so clearing browser data resets them.
