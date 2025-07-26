# Truth or Dare - Website

This is the official website for the Truth or Dare iOS app, containing the privacy policy and support center.

## 🚀 Quick Setup

This is a static website that can be hosted for free on GitHub Pages.

### Steps to Deploy:

1. **Create a new GitHub repository** (e.g., `truth-or-dare-website`)

2. **Upload these files** to the repository:
   - `index.html`
   - `README.md`

3. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)

4. **Get your website URL**:
   - Your site will be available at: `https://yourusername.github.io/truth-or-dare-website`

## 📱 App Store Integration

Use this website URL in your App Store Connect submission:

- **Privacy Policy URL**: `https://yourusername.github.io/truth-or-dare-website`
- **Support URL**: `https://yourusername.github.io/truth-or-dare-website`

## 🎨 Features

### Privacy Policy Page
- Complete privacy policy based on your app's PRIVACY_POLICY.md
- Mobile-responsive design
- Professional styling
- All third-party services documented

### Support Center
- Contact form for user issues
- Categorized support requests
- Device information collection
- Professional user experience

## 🔧 Customization

### To integrate with a form service:

1. **Formspree** (Recommended - Free tier available):
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

2. **Netlify Forms** (If hosting on Netlify):
   ```html
   <form name="support" netlify>
   ```

3. **EmailJS** (Client-side email sending):
   - Sign up at emailjs.com
   - Add their JavaScript SDK
   - Configure email templates

### To update contact information:
- Replace placeholder email addresses
- Update company information
- Customize the app icon emoji (🎲)

## 🎯 SEO & Performance

The website is optimized for:
- Mobile responsiveness
- Fast loading times
- Clean HTML structure
- Accessible design
- Search engine friendly

## 📄 File Structure

```
truth-or-dare-website/
├── index.html          # Main website file
└── README.md           # This documentation
```

## 🔗 Example URLs

After deployment, your URLs will be:
- **Privacy Policy**: `https://yourusername.github.io/truth-or-dare-website/#privacy`
- **Support**: `https://yourusername.github.io/truth-or-dare-website/#support`

## 📞 Support Integration

The support form collects:
- User name and email
- Issue category
- Device information
- Detailed description

This helps you provide better support for your app users.

---

**Ready to deploy?** Just upload to GitHub and enable Pages! 🚀