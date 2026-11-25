# holiday-pickup

Private Holiday Meal Lookup web app for Lazy Acres Mission Hills (Store 27).
Pickup date: 11/25/2026. Source: TDAY26_Manifest_MI27_20261125.pdf (216 customers).

## What it is
`index.html` is the whole app in one file. All 216 customers are embedded in it.
Type a last name, or first and last name in any order, and it shows the BOX number,
pickup time, order number, and an UNPAID flag when the manifest shows unpaid.
It also finds an exact order number or box number. No internet is needed once the
file is open, and nothing is sent anywhere.

## How the team uses it
1. Open this private repo while signed in to GitHub.
2. Open `index.html`, then download it (download icon at the top right of the file view).
3. Open the downloaded file in a real browser: Chrome or Edge on a computer,
   Chrome on Android. On a computer, double clicking the downloaded file works.
4. Do NOT open it from a Messages, Mail, or Files preview. Previews block the
   search code and typing does nothing.

## Privacy
This repo is private and contains customer names, order numbers, and pickup
times. Keep it private. Do not enable GitHub Pages on a plan without access
control, do not make the repo public, and do not post raw file links outside
the team. Only repo collaborators can see this data.

## Updating
If a new manifest arrives, regenerate `index.html` from the new manifest and
push the replacement file. The current build was verified against the manifest:
216 rows, 9 unpaid, multi-entry customers (Garcia, Jamie: Box 7 and Box SF;
Smith, Rebecca: two SF entries) shown together.
