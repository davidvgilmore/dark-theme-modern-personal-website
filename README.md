# Modern Dark Theme Personal Website

A modern, responsive personal website featuring a dark theme design, built with clean HTML5 and CSS3. The site is optimized for performance and deployed on Vercel.

## 🌟 Features

- Modern dark theme design
- Fully responsive layout
- Blog/writings section
- About page
- Social media integration
- Fast loading with system fonts
- Optimized images via CDN

## 🛠 Technologies Used

- HTML5
- CSS3
- Font Awesome icons (v6.0.0)
- System fonts for optimal performance
- Vercel for deployment

## 🚀 Deployment

The site is deployed on Vercel. Current production URL:
https://darkthememodernpersonalwebsiteclone-e43e0guim.vercel.app

### Deploy Your Own

To deploy this website to Vercel:

1. Clone the repository:
   ```bash
   git clone https://github.com/davidvgilmore/dark-theme-modern-personal-website.git
   cd dark-theme-modern-personal-website
   ```

2. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```

3. Deploy to Vercel:
   ```bash
   vercel
   ```

4. To deploy to production:
   ```bash
   vercel --prod
   ```

## 💻 Local Development

To run the website locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/davidvgilmore/dark-theme-modern-personal-website.git
   cd dark-theme-modern-personal-website
   ```

2. Start a local server:
   ```bash
   python -m http.server 8080
   ```

3. Visit http://localhost:8080 in your browser

## 📁 Project Structure

```
.
├── index.html          # Home page
├── about.html         # About page
├── styles.css         # Main stylesheet
├── vercel.json        # Vercel configuration
└── README.md          # Project documentation
```

## 🔧 Configuration

### Vercel Configuration

The `vercel.json` file contains the deployment configuration:

```json
{
    "version": 2,
    "builds": [
        {
            "src": "**/*",
            "use": "@vercel/static"
        }
    ],
    "routes": [
        {
            "src": "/(.*)",
            "dest": "/$1"
        }
    ]
}
```

## 🎨 Customization

To customize the site for your own use:

1. Update personal information in `index.html` and `about.html`
2. Modify color schemes in `styles.css`
3. Replace profile and content images
4. Update social media links in the footer

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

David Valerio Gilmore
- Twitter: [@davidvgilmore](https://twitter.com/davidvgilmore)
- LinkedIn: [davidvgilmore](https://www.linkedin.com/in/davidvgilmore)
- GitHub: [@davidvgilmore](https://github.com/davidvgilmore)
