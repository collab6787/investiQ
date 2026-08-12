INVESTIQ — Frontend Prototype

Files added:
- C:\MLSA\Project\frontend\investiq.html  (open in browser to preview)
- C:\MLSA\Project\frontend\src\investiq.css
- C:\MLSA\Project\frontend\src\investiq.js

Overview:
This is a production-style, information-dense investigation dashboard prototype inspired by the supplied visual reference. It's implemented as static files that require no build step and use CDN libraries (Chart.js, vis-network) for charts and network visualization.

How to view:
1. Open C:\\MLSA\\Project\\frontend\\investiq.html in a modern browser.

Notes & next steps:
- This prototype uses demo/fake data and local JavaScript. For a real product, scaffold a React (Vite) app and implement backend services, secure data stores, and an integration to Microsoft Copilot.
- The Copilot interactions in this demo are placeholder UI flows; to enable real Copilot assistance, integrate Microsoft Copilot APIs/tools per your organization.
- If you want, next actions can include:
  - Convert this prototype into a React+Vite project and split UI into components.
  - Add sample evidence generation using Copilot (per hackathon constraints).
  - Implement export/print reporting for Executive Brief.

Design notes:
- Colors and layout aim for a SOC/SIEM aesthetic (dark navy background, cyan highlights, amber warnings).
- Components: Timeline, Evidence Board, Evidence Fusion, Relationship Graph, Attack Path, Message Threats, Copilot panel, AI Case Brief, Replay controls.

Contact:
This prototype was generated using Copilot CLI runtime in VS Code as requested.
