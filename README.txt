Place the two videos here using these exact filenames so the page picks them up automatically:

  programmleitung.mp4      — Video 1 (Programmleitung Orion)
  co-programmleitung.mp4   — Video 2 (Strategische Co-Programmleitung)

Format suggestion for web playback:
  - Container: MP4 (H.264 video + AAC audio)
  - Resolution: 1920x1080 (16:9)
  - Bitrate: 4–6 Mbps for crisp HD on a marketing page

For Vercel hosting, files in this folder are deployed as static assets.
Large files (>100MB) should be checked against Vercel's free-tier limits or hosted via Vercel Blob / a CDN.


Windows PowerShell
Copyright (C) Microsoft Corporation. Alle Rechte vorbehalten.

Installieren Sie die neueste PowerShell für neue Funktionen und Verbesserungen! https://aka.ms/PSWindows

How to upload:
To upload videos (e.g. .mp4) to GitHub using Git LFS via Windows PowerShell, first navigate 
to your project folder with cd "C:\Programming\Proposal Post Orion". 
Initialize Git LFS once using git lfs install, then configure it to track video files with git lfs track "*.mp4". 
After that, add all files (including the video) using git add . and create a commit with git commit -m "Add video with LFS". 
Before pushing, make sure your branch is up to date by running git pull origin main --rebase, and finally upload everything to GitHub using git push origin main. 
Even if your video is larger than 50 MB (e.g. ~82 MB), it will work correctly because Git LFS handles large files automatically.
