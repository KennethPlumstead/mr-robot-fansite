# Mr. Robot Fan Site — Terminal-Style Theme

A dedicated fan hub exploring characters, episodes, and iconic moments from *Mr. Robot*.  
Originally built on *WordPress* with custom styling and carefully structured information architecture (IA).  
This repository preserves the project (WordPress export, custom CSS, IA notes, screenshots) so reviewers can quickly understand the scope of work.

---

## 🔗 Live Site
👉 [Visit the Live Site](https://fsocietyfanhub.wordpress.com/)

---

## 🎯 Project Highlights
- Planned and implemented **information architecture** (menus, navigation flows, content groupings)  
- Created **custom CSS** for a terminal-style aesthetic, ensuring responsive layouts and accessible contrast  
- Integrated **media content** (trailers, behind-the-scenes) while maintaining usability  
- Migrated from **local development (MAMP)** to *WordPress.com* for reliable hosting and sharing  

---

## 🧭 Repository Structure
```text
mr-robot-fansite/
├─ export/                 # WordPress export ("All Content")
│  └─ wordpress-export.xml # exported 2025-08-29
├─ custom-css/             # Additional CSS from WordPress Customizer
│  └─ additional.css
├─ content/
│  ├─ SITE_MAP.md          # navigation + page structure
│  └─ COPY_DECK.md         # optional: main page copy
├─ screenshots/            # desktop & mobile screenshots
├─ .gitignore
├─ LICENSE                 # MIT by default
└─ README.md
```

---

## 🖼️ Screenshots (Responsive)

<table>
  <tr><th align="left">Home — Desktop</th><th align="left">Home — Mobile</th></tr>
  <tr>
    <td><img src="screenshots/desktop-home.png" alt="Home — Desktop" width="400"/></td>
    <td><img src="screenshots/mobile-home.png" alt="Home — Mobile" width="200"/></td>
  </tr>
  <tr><th align="left">Characters — Desktop</th><th align="left">Characters — Mobile</th></tr>
  <tr>
    <td><img src="screenshots/desktop-characters.png" alt="Characters — Desktop" width="400"/></td>
    <td><img src="screenshots/mobile-characters.png" alt="Characters — Mobile" width="200"/></td>
  </tr>
  <tr><th align="left">Plot — Desktop</th><th align="left">Plot — Mobile</th></tr>
  <tr>
    <td><img src="screenshots/desktop-plot.png" alt="Plot — Desktop" width="400"/></td>
    <td><img src="screenshots/mobile-plot.png" alt="Plot — Mobile" width="200"/></td>
  </tr>
  <tr><th align="left">About — Desktop</th><th align="left">About — Mobile</th></tr>
  <tr>
    <td><img src="screenshots/desktop-about.png" alt="About — Desktop" width="400"/></td>
    <td><img src="screenshots/mobile-about.png" alt="About — Mobile" width="200"/></td>
  </tr>
</table>  

---

## 🛠️ How This Was Captured
- **Content export:** `Tools → Export → Export All Content` → saved in `export/wordpress-export.xml`  
- **Custom CSS:** This site was built on the free WordPress.com plan, which doesn’t allow an Additional CSS file. Styling was applied using inline <style> blocks in page content. No separate CSS file exists to export.  
- **Information architecture:** documented in `content/SITE_MAP.md`  
- **Screenshots:** desktop and mobile captures to show responsiveness and layout  

---

## 🔍 Tech & Practices
- **Platform:** WordPress (WordPress.com)  
- **Core:** HTML, CSS (custom), accessibility-first, responsive design  
- **Process:** IA planning → custom styling → content organization → deployment  
- **Tools:** WordPress Customizer, Browser DevTools, media optimization  

---

## 🚀 Future Enhancements
- Publish a lightweight **static HTML/CSS mirror** on GitHub Pages  
- Add a **React component** (e.g., character search/filter) to showcase modern JavaScript  
- Perform a **Lighthouse audit** and address performance, accessibility, and SEO opportunities  

---

## 📄 License & Disclaimer
- **License:** MIT (see [`LICENSE`](LICENSE))    
- **Disclaimer:** This is a non-commercial fan project for educational and portfolio purposes.  
  - *Mr. Robot* and related assets remain the property of their respective rights holders  

