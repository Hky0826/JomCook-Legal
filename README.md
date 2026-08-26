# JomCook Legal & Support Portal

This repository hosts the official public legal and support pages for the **JomCook** mobile application, developed by **ywy dev**. It is configured to deploy directly as a static website on **GitHub Pages**, providing the required public URLs for the **Google Play Console** and App Store.

---

## 🌐 Public URLs

Once GitHub Pages is enabled on this repository (`Hky0826/JomCook-Legal`), the pages will be accessible at:

| Page | Path | URL |
| :--- | :--- | :--- |
| **Home Portal** | `/` | `https://hky0826.github.io/JomCook-Legal/` |
| **Privacy Policy** | `/privacy-policy/` | `https://hky0826.github.io/JomCook-Legal/privacy-policy/` |
| **Account Deletion** | `/delete-account/` | `https://hky0826.github.io/JomCook-Legal/delete-account/` |
| **AdMob App-Ads.txt** | `/app-ads.txt` | `https://hky0826.github.io/JomCook-Legal/app-ads.txt` |

---

## 📁 Repository Structure

```text
JomCook-Legal/
├── index.html                  # Landing page with navigation cards
├── app-ads.txt                 # Google AdMob authorized sellers list
├── .nojekyll                   # Ensures raw text static file serving
├── css/
│   └── style.css               # Clean, responsive, accessible CSS
├── privacy-policy/
│   └── index.html              # Comprehensive Privacy Policy
├── delete-account/
│   └── index.html              # In-App & External Account Deletion Guide
└── README.md                   # Repository documentation
```

---

## ⚙️ Enabling GitHub Pages

To activate hosting for this repository on GitHub Pages:

1. Open your repository on GitHub: [https://github.com/Hky0826/JomCook-Legal](https://github.com/Hky0826/JomCook-Legal)
2. Go to **Settings** (top navigation tab).
3. In the left sidebar under the **Code and automation** section, click **Pages**.
4. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`.
   - **Branch**: Select `main` and folder `/ (root)`.
5. Click **Save**.
6. Wait 1–2 minutes for the deployment workflow to complete. Your site will be live at `https://hky0826.github.io/JomCook-Legal/`.

---

## 📱 Google Play Console Configuration

Provide the following URLs in the Google Play Console:

1. **Privacy Policy URL**:
   - `https://hky0826.github.io/JomCook-Legal/privacy-policy/`
   - *Enter under: App content → Privacy Policy*

2. **App Account Deletion URL**:
   - `https://hky0826.github.io/JomCook-Legal/delete-account/`
   - *Enter under: App content → Data Safety → Deletion request link*

---

## 📋 App & Developer Details

- **App Name:** JomCook
- **Developer:** ywy dev
- **Support Email:** ywy.dev@gmail.com
- **AI Processing:** Google Gemini (Google LLC)
- **Backend & Cloud Storage:** Supabase
- **Subscriptions:** RevenueCat
- **Advertisements:** Google AdMob
