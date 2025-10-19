\# Project overview

Arthurits static site for Windows utility apps (Heat strain and Center windows). This repository hosts the public website and the ad banner used both on the site and inside proprietary WinUI apps via WebView2.



| Application | Icon | Microsoft Store |

|---|---:|---|

| \*\*Heat strain\*\* | !\[Heat strain app image](./assets/images/heat-strain.svg) | \[<img src="https://get.microsoft.com/images/en-us%20dark.svg" width="140" alt="Get it from Microsoft Store">](https://apps.microsoft.com/detail/9NFZHJH28BHD?referrer=appbadge\&mode=direct) |

| \*\*Center windows\*\* | !\[Center windows app image](./assets/images/center-windows.svg) | \[<img src="https://get.microsoft.com/images/en-us%20dark.svg" width="140" alt="Get it from Microsoft Store">](https://apps.microsoft.com/detail/9P3RF1QPJ3QC?referrer=appbadge\&mode=direct) |



\- \[Live site](https://arthurits.github.io)

\- \[Repository path](https://github.com/arthurits/arthurits.github.io)



\## Description

Minimal static site showcasing two Windows utilities (Heat strain and Center windows) and a standalone ad banner designed for:

\- Hosting on GitHub Pages as the public website.

\- Embedding inside a WinUI application using WebView2 (views/banner.html).



Built with plain HTML and CSS. The project centralizes styles in `assets/css/styles.css` and includes visible `<noscript>` fallbacks so crawlers and users without JavaScript see meaningful content.



\## Local setup and testing

1\. Clone the repository:

\- git clone https://github.com/arthurits/arthurits.github.io.git

2\. Serve the files locally:

\- Python 3: `python -m http.server 8000`

\- Node: `npx serve .`

3\. Open in a browser:

\- Main page: `http://localhost:8000/index.html`

\- Banner page: `http://localhost:8000/views/banner.html`

4\. Important checks:

\- Disable JavaScript and confirm the `<noscript>` fallback is visible.

\- View source to ensure static content is present for crawlers.



\## Deploy to GitHub Pages

1\. Push changes to the branch you use for Pages (commonly `main`).  

2\. In GitHub: \*\*Settings → Pages\*\* → select branch and folder (root).  

3\. Wait a few minutes and check the published URL shown in Pages settings.  

4\. Purge CDN/cache if you use caching to ensure verifiers and WebView2 see the latest files.



\## Contributing

\- Fork → branch → changes → pull request with a clear description.  

\- Keep style changes in `assets/css/styles.css` and reuse existing classes.



\## License

Copyright Arthurits Ltd. No part of this repository might be used whithout the explicit permission from the Arthurits Ltd.



