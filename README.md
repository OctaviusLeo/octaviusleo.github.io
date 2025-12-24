# Symaedchit Octavius Leo — Portfolio

Static site for my resumes and transcript, hosted on GitHub Pages with a custom domain.

## Structure
- index.html: landing page with two resume cards and a transcript card
- resume-ai.html / resume-robotics.html: DOCX viewers + download buttons
- transcript.html: PDF embed + forced download button
- styles.css: shared layout/theme
- assets/: images, favicon, OG image
- Resume/: source DOCX files for both resumes
- Transcript/: OfficialTranscript.pdf
- CNAME: custom domain mapping

## Run locally
Open index.html in a browser or serve the folder (`python -m http.server 8000`). Relative links assume the repo root as the web root.

## Deploy
Push to the `main` branch of this repo; GitHub Pages (and the CNAME) serve the static files as-is. 