# Animal Cell Culture Laboratory — Immersive 3D Tour

A static, browser-based Three.js educational tour designed for a student presentation and deployment on Vercel.

## What's included

- 3D Animal Cell Culture Suite with ten selectable equipment stations.
- Separate Instructor Chamber, Research Students Chamber, and Seminar & Discussion Hall.
- An opening welcome from **ANSHU YADAV — Research Fellow**, including browser-generated spoken narration.
- Interactive room navigation, camera orbit, zoom, keyboard movement, hotspots, and detail panels.
- Real reference photographs from institutional laboratory pages, displayed with source attribution.
- Vercel static-site configuration. No server or build step is required.

## Run locally

The project is static. Open `index.html` in a modern browser, or use a local web server (recommended so browser features behave consistently):

```bash
# Windows PowerShell / Command Prompt
py -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to Vercel

1. Extract the ZIP file.
2. Create a GitHub repository and upload the contents of this folder. `index.html` and `vercel.json` must be in the repository root.
3. Sign in to Vercel and choose **Add New → Project**.
4. Import the GitHub repository.
5. Select **Other** as the framework preset.
6. Leave Build Command and Install Command empty. Set Output Directory to `.` (or leave the default for a static project).
7. Deploy. Vercel will publish `index.html` as the site homepage.

You can also deploy with the Vercel CLI from this directory:

```bash
npm i -g vercel
vercel
```

## Controls

- Drag with mouse / finger: rotate the camera.
- Scroll / trackpad: zoom.
- W, A, S, D or arrow keys: move the camera target.
- Left-side navigation: fly to a room.
- Select a glowing hotspot: open information about that room or equipment station.
- Audio button: play the welcome using the browser's speech synthesis engine.

## Important notes for the presentation

- The facility arrangement and room plan are an **illustrative academic concept**, not an official NIT Jalandhar architectural drawing or a claim about the institute's actual room allocation.
- ANSHU YADAV is presented as the virtual tour host because that name was provided for this assignment. The audio uses browser text-to-speech; it is not a recording of a real person.
- The photographs are real reference images from the external institutional pages listed in `CREDITS.md`. They are not represented as photographs of NIT Jalandhar or as photographs of ANSHU YADAV.
- Three.js is loaded from a CDN, and the reference photographs are loaded from their original web sources. The site therefore needs an internet connection when it is viewed.
- Scientific operating details are educational summaries. Always follow the local institution's approved SOPs, risk assessment, and equipment manuals in real laboratory work.
