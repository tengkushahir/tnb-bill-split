# TNB Bill Split Calculator (offline app)

Splits the TNB bill for a dual-key house: upload the TNB bill PDF, enter the neighbour's
sub-meter reading, and it works out each person's share line by line.

- Works offline once opened. The PDF is read on the phone and never uploaded anywhere.
- A personal calculator; not made by or affiliated with Tenaga Nasional Berhad.
- Nothing personal is in these files, so a public repository is fine.
- Your record is kept on the phone (browser storage). Bring in past months once with
  Import record file (pick tnb-record.json, which you keep on the phone and never upload),
  and use Export record (backup) now and then.

## Put it on GitHub Pages
1. Create a repository (or a folder in your existing one) and upload every file in this folder.
2. Settings > Pages > Deploy from a branch > main / root. Wait a minute for the link.
3. Open the link on your phone once while online.
   - iPhone (Safari): Share > Add to Home Screen.
   - Android (Chrome): menu > Install app / Add to Home screen.
4. Open it from the home-screen icon. From then on it works without internet.

To update later, replace index.html and push; the app picks it up the next time it's opened online.
