# Sign Placer

Document image mela unga signature-ah place panra app.

## Features
- Document image upload (gallery / files)
- Signature image upload (white background auto-remove -> transparent)
- Illa screen-la direct-ah sign draw pannalam
- 1 finger = move, 2 fingers = zoom + rotate; sliders + arrow buttons for exact placement
- Ink: Original / Black / Blue
- Save/share at full original resolution (PNG or JPG)

## APK epdi edukkurathu (free, GitHub use panni)

1. https://github.com la free account create pannunga (illa login).
2. **New repository** -> name: `sign-placer` -> Create.
3. Indha folder-la ulla ellaa files-um repo-la upload pannunga
   (**Add file -> Upload files**). `.github` folder-um sethu upload aaganum.
   - `.github` folder upload aagala-na: **Add file -> Create new file**,
     name-la `.github/workflows/build-apk.yml` nu type pannunga, indha folder-la ulla
     `build-apk.yml` content-ah paste pannunga.
4. **Actions** tab -> **Build APK** -> **Run workflow**.
5. 5-10 minutes-la green tick varum. Run-ah open pannunga -> keezha **Artifacts** -> `SignPlacer-APK` download.
6. Zip-ah extract pannina `app-debug.apk` kidaikkum. Phone-la install pannunga
   (Settings-la "Install unknown apps" allow pannanum).

## Web-la direct-ah use panna
`www/index.html` file-ah Netlify Drop / GitHub Pages-la host pannina, phone browser-la
open panni "Add to Home screen" pannalam.
