VClipz website files

FILES
- index.html: Application homepage
- privacy.html: Privacy policy
- terms.html: Terms of service
- style.css: Shared styling

BEFORE PUBLISHING
1. Replace YOUR_EMAIL@example.com in index.html, privacy.html, and terms.html with an email address you monitor.
2. Verify the privacy policy against the actual app implementation. In particular, confirm where OAuth tokens are stored, whether logs/analytics/crash reports are sent anywhere, and whether any backend receives user data.
3. Upload all four website files to a public GitHub repository named vclipz (or adjust the URLs to match your repository).
4. In GitHub, open Settings > Pages, choose Deploy from a branch, select main and /(root), and save.
5. Wait for GitHub Pages to publish the site. Test all three pages in a private/incognito browser window.
6. Enter the live URLs in Google Cloud Console:
   Homepage: https://vclipz.github.io/vclipz/
   Privacy:   https://vclipz.github.io/vclipz/privacy.html
   Terms:     https://vclipz.github.io/vclipz/terms.html

IMPORTANT
These are starter templates, not legal advice or a guarantee of Google verification. Do not publish claims that are inaccurate. If the app sends data to a server, uses analytics, or stores tokens outside the local device, update the privacy policy accordingly. Make sure your app's actual use of YouTube API Services complies with the YouTube API Services Terms and Google API Services User Data Policy.
