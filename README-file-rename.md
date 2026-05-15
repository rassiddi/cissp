# CISSP Made Easy Portal — File Setup Instructions

## Step 1: Rename your domain HTML files

Upload these files to your GitHub repository with EXACTLY these new names:

| Original file                      | Rename to                    |
|------------------------------------|------------------------------|
| cissp-domain1-enriched.html        | d1-x7k2p9m4qn.html           |
| cissp-domain2-enriched.html        | d2-w5n8r3t6bj.html           |
| cissp-domain3-enriched.html        | d3-q4z1v7s0cx.html           |
| cissp-domain4-enriched.html        | d4-y9m6h2e5lf.html           |
| cissp-domain5-enriched.html        | d5-a8k3u1w7gd.html           |
| cissp-domain6-enriched.html        | d6-p2b9c5n0zr.html           |
| cissp-domain7-enriched.html        | d7-f4q8j1m6ys.html           |
| cissp-domain8-enriched.html        | d8-v6t3h0e2kw.html           |
| portal.html                        | portal.html (keep same name) |

## Step 2: Upload ALL files to ONE GitHub repo folder

All 9 files go in the SAME directory. Example:
- https://rashidsiddiqui.github.io/cissp/portal.html        ← share THIS URL only
- https://rashidsiddiqui.github.io/cissp/d1-x7k2p9m4qn.html ← never share directly
- https://rashidsiddiqui.github.io/cissp/d2-w5n8r3t6bj.html ← never share directly
- (etc.)

## Step 3: Enable GitHub Pages (if not already done)
Settings → Pages → Source: main branch → / (root) or /docs → Save

## Step 4: Change the access code (IMPORTANT)
Open portal.html and find this line near the top of the script:
    var ACCESS_CODE = 'CISSPmadeEasy2025';
Change it to your own chosen password before uploading.

## Step 5: Share ONLY the portal URL with students
    https://rashidsiddiqui.github.io/cissp/portal.html
Give them the access code you set in Step 4.

## Security notes
- Domain file names contain random 10-character tokens — virtually impossible to guess
- Password is checked in-browser with sessionStorage — persists for the browser session
- When student closes the browser tab, they must re-enter the code next visit
- For Udemy: paste the portal URL + access code in your course resources section
