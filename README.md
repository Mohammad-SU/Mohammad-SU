[![banner](https://github.com/Mohammad-SU/LimeDrive-Cloud-Storage-Public/blob/main/screenshots/loading-screen-banner.png)](https://github.com/Mohammad-SU/LimeDrive-Cloud-Storage-Public)

## 💻 Welcome! I'm Mohammad S.U. A Full-Stack Developer.
With extensive experience in **frontend**, **backend**, and **databases**, I've honed my skills as the creator of [LimeDrive.net](https://github.com/Mohammad-SU/LimeDrive-Cloud-Storage-Public) - a full-stack cloud storage/file hosting service that I professionally optimised for cost and performance. I aim to craft scalable solutions with exceptional user experience.

<p align="center">
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react" alt="React Badge">
  <img src="https://img.shields.io/badge/typescript-%2320232a.svg?style=for-the-badge&logo=typescript" alt="Typescript Badge">
  <img src="https://img.shields.io/badge/sass-%2320232a.svg?style=for-the-badge&logo=sass" alt="Laravel Badge">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/laravel-%2320232a.svg?style=for-the-badge&logo=laravel" alt="Laravel Badge">
  <img src="https://img.shields.io/badge/postgresql-%2320232a.svg?style=for-the-badge&logo=postgresql" alt="Laravel Badge">
  <img src="https://img.shields.io/badge/cloudflare-%2320232a.svg?style=for-the-badge&logo=cloudflare" alt="Laravel Badge">
</p>

## 💼 Experience
### Full-stack developer of cloud storage/file hosting service
### [LimeDrive.net](https://limedrive.net) &nbsp;–&nbsp; [Video Demo](https://youtu.be/3P_LIRLbSy4) &nbsp;–&nbsp; [GitHub Repo](https://github.com/Mohammad-SU/LimeDrive-Cloud-Storage-Public)

I developed this robust cloud storage service, with some areas surpassing Dropbox/Google Drive (particularly speed). I handled all complex architectural and scalability decisions, implementing them myself. Seamlessly manage and view files in LimeDrive's sleek retro UI - secure, fast, and performant. Click the image to watch the demo:

[![LimeDrive Demo](https://github.com/Mohammad-SU/LimeDrive-Cloud-Storage-Public/blob/main/screenshots/yt-video-img.png)](https://youtu.be/3P_LIRLbSy4)

### 📸 Screenshots With Captions

<details>
  
<summary>
Click to expand

> UI borders may seem low quality in the screenshots. You can zoom in for better details. For more info and to see the features in action, go to the video demo above.
</summary>
  
### File List - Clean UI
![File List (Clean UI)](https://github.com/Mohammad-SU/LimeDrive-Cloud-Storage-Public/blob/main/screenshots/file-list-clean-UI.png)

### File Viewer - Video and Controls
![File Viewer (Video and Controls)](https://github.com/Mohammad-SU/LimeDrive-Cloud-Storage-Public/blob/main/screenshots/file-viewer-video.png)

### File List - Detailed UI With Item Selection, Drag and Drop, and Upload Queue
![File List (Detailed UI With Item Selection, Drag and Drop, and Upload Queue](https://github.com/Mohammad-SU/LimeDrive-Cloud-Storage-Public/blob/main/screenshots/file-list-detailed-UI.png)

### File Viewer - PDF and Shareable Link Generation
![File Viewer (PDF and Shareable Link Generation)](https://github.com/Mohammad-SU/LimeDrive-Cloud-Storage-Public/blob/main/screenshots/file-viewer-pdf-share-modal.png)

### Settings
![Settings](https://github.com/Mohammad-SU/LimeDrive-Cloud-Storage-Public/blob/main/screenshots/settings.png)

### Login
![Login](https://github.com/Mohammad-SU/LimeDrive-Cloud-Storage-Public/blob/main/screenshots/login.png)

### Responsive Design - Usable on Varied Screen Sizes
<p align='center'>
    <img src="https://github.com/Mohammad-SU/LimeDrive-Cloud-Storage-Public/blob/main/screenshots/mobile-file-list.jpg" width="37%">
    <img src="https://github.com/Mohammad-SU/LimeDrive-Cloud-Storage-Public/blob/main/screenshots/mobile-file-viewer.jpg" width="37.09%">
</p>

</details>

### 🛠️ Tech Stack

**Frontend** &nbsp;–&nbsp; React &nbsp;•&nbsp; TypeScript &nbsp;•&nbsp; HTML &nbsp;•&nbsp; CSS/Sass &nbsp;•&nbsp; Vite  &nbsp;•&nbsp; React Router &nbsp;•&nbsp; Cloudflare Pages

**Backend** &nbsp;–&nbsp; Laravel &nbsp;•&nbsp; PHP &nbsp;•&nbsp; SQL (PostgreSQL) &nbsp;•&nbsp; Docker &nbsp;•&nbsp; Cloudflare Workers &nbsp;•&nbsp; Render

**Other** &nbsp;–&nbsp; Playwright  &nbsp;•&nbsp; Axios &nbsp;•&nbsp; REST API &nbsp;•&nbsp; Cloudflare R2 (object storage) &nbsp;•&nbsp; Neon (DB host)

### 🔍 Current Features
<details>
  
<summary>Click to expand</summary>
&nbsp;

⚡ **Cost and Performance Optimisation**
>Integrates zero-egress-fee object storage, recursive CTEs, no-cost cloud service tiers, CDN, caching, lazy loading, data deduplication, automated cleanup, throttling, and usage limits - these lead to ***zero costs*** in data storage/processing and improvements in both scalability and UX. Achieved ***2.1x faster loading speed*** than Dropbox and ***sub-10ms*** UI interactions (vs. 1270ms for Google Drive) by leveraging client-side rendering, routing, and memoisation.

🚀 **Optimised Downloads** 
>A web worker, multiple data streaming packages, piped async iterables, and presigned URLs allow ***GBs of downloads*** to ***initiate immediately*** with ***only bytes of server load***.

🔒 **Security** 
>Client/server validation, encryption, hashing, proxy, WAF, SSL, CORS, and CSRF tokens.

🧪 **Automated Tests** 
>***E2E*** tests (Playwright), ***Unit*** tests (PHPUnit), and ***CI/CD*** (GitHub Actions).

🔑 **User Accounts** 
>Registration, login, account settings, sessions, and email verification/notifications.

📁 **File Storage and Management** 
>Folders, paths, drag & drop, downloading, link-share, and upload queue with robust management of varied situations like network errors, name conflicts, and cancelling.

👁️ **File Viewer** 
>Convenient viewer in-browser, supporting videos, images, PDFs, audio, and plain text. Includes shared views, printing, and custom video controls with fullscreen and keyboard shortcuts.

🔗 **Sharing** 
>Generate secure links to share files, providing effortless access/collaboration for recipients. Includes permission management. A Cloudflare worker verifies URLs via server-generated HMAC and IP.

🎨 **UX/UI** 
>A creative mix of bulletin board system/CLI themes with modern, responsive elements. Errors are more detailed/user-friendly than DropBox and UI is noticeably faster for a seamless experience.

♿ **Accessibility** 
>ARIA, keyboard navigation, shortcuts, clear labels, and semantic HTML.

✅ **Code Quality** 
>Improved type safety and documentation through use of TypeScript, PHPDoc/type hinting, and PHPStan - leading to a high reduction in runtime errors and time spent debugging them.

⏲️ **Concurrency Control** 
>DB constraints, transactions, mutexes, and graceful exception handling allows for robust concurrent operations to avoid race conditions.

⚙️ **CI/CD Pipelines** 
>Separated development and production environments, with configurations on Render, Cloudflare, Docker, Github Actions, and Doppler - reducing the chance of downtime.

</details>

### 📞 Contact
Have a question or want to work with me? You can reach me through my [LinkedIn](https://www.linkedin.com/in/mohammad-su), or through the [contact form on my portfolio.](https://msudigital.netlify.app/#contact)
