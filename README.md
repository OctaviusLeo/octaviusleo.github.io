# Symaedchit Octavius Leo — Portfolio

Personal portfolio website showcasing resumes, transcript, and featured projects. Hosted on GitHub Pages with a custom domain.

## Structure
- **index.html**: Main landing page featuring:
  - Hero section with contact links (Email, LinkedIn, Handshake, GitHub, LeetCode)
  - Two lane-specific resume cards (AI/Software and Robotics/Embedded)
  - Transcript card
  - Featured Projects section (EMG game, Robotics demo, RAG-lite)
  - About section
- **resume-ai.html / resume-robotics.html**: Pages with Microsoft Office Online viewer (iframe) + download buttons for DOCX files
- **transcript.html**: PDF embed viewer + download button
- **styles.css**: Shared layout/theme/styles
- **assets/**: Images (project demos), favicon, OG image for social sharing
- **Resume/**: Source DOCX files for both resumes
- **Transcript/**: OfficialTranscript.pdf
- **CNAME**: Custom domain mapping for GitHub Pages

## Run locally
Open `index.html` in a browser or serve the folder (`python -m http.server 8000`). Relative links assume the repo root as the web root.

## Deploy
Push to the `main` branch of this repo; GitHub Pages (and the CNAME) serve the static files as-is. 