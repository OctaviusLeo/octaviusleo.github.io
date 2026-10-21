# Symaedchit Octavius Leo Portfolio

Personal portfolio website showcasing resumes, transcript, and featured projects. Hosted on GitHub Pages with a custom domain.

## Structure
* **index.html**: Main landing page featuring:
  * Hero section with contact links (Email, LinkedIn, Handshake, GitHub, LeetCode)
  * Two track-specific 2026 resume cards (Robotics/Simulation/Test and AI/ML)
  * Transcript card
  * Featured Projects section: six portfolio projects grouped Robotics/Simulation/Test and AI/ML, plus the ECE-480 senior design
  * About section
* **resume-ai.html / resume-robotics.html**: PDF embed viewer + download button for each 2026 resume
* **transcript.html**: PDF embed viewer + download button
* **styles.css**: Shared layout/theme/styles
* **assets/**: Project thumbnails and demos (GIFs/figures copied from each project repo, GIFs downscaled to 400 px wide), favicon, OG image for social sharing
* **Resume/**: The two 2026 resume PDFs
* **Transcript/**: OfficialTranscript.pdf
* **CNAME**: Custom domain mapping for GitHub Pages

## Run locally
Open `index.html` in a browser or serve the folder (`python -m http.server 8000`). 
Relative links assume the repo root as the web root.

## Deploy
Push to the `main` branch of this repo. GitHub Pages (and the CNAME) serve the static files as-is. 