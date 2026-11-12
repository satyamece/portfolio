# Satyam Patel — Networking Portfolio

A three-page static portfolio with an interactive Three.js enterprise network visualization.

## Pages
- `index.html` — home
- `about.html` — about, skills, training and IoT internship
- `lab.html` — networking project and interactive 3D topology

## Deploy to GitHub Pages
1. Create a **public** repository named `satyamece.github.io` in the GitHub account `satyamece`.
2. Upload **all files and the `assets` folder** from this project to the repository root. Do not upload only the ZIP.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. Your site should become available at `https://satyamece.github.io/` after GitHub finishes publishing.

You can also deploy under a different repository name; the site will then be under `https://satyamece.github.io/REPOSITORY-NAME/`.

## Run locally
Use a local HTTP server, for example `python -m http.server 8000`, then open `http://localhost:8000/`. The Three.js module imports require an internet connection to the CDN.

## Important notes
- The interactive 3D topology is a **representative visualization** of the provided Packet Tracer screenshot. It is **not** a network simulator and does not reproduce all 44 devices or every port-level connection.
- The 44-device and 11-VLAN figures are project metrics from the provided resume.
- The resume button opens the supplied Google Drive URL. Ensure sharing is set to **Anyone with the link → Viewer**.
- **Privacy:** The public Google Drive resume may show your phone number because it is printed in the PDF. Replace it with a redacted resume if you want the number fully private.
- No phone number is displayed in the site pages. Academic scores are omitted.
- `assets/topology-reference.png` contains a screenshot of your project. You may replace it with a cleaner export from Packet Tracer later.
- CCNA is described as **training**, not a Cisco-issued certification.
