# Rolling Acres Studio - Development Notes

## Site URL
https://rollingacresstudio.com

## Open Issues

### Contact Form Network Error
**Status:** Not working
**Page:** contact.html
**Error:** "A network error occurred. Please try again or email rollingacresstudio@gmail.com"

**Problem:** The contact form submission fails. GitHub Pages is static hosting and cannot process form submissions directly.

**Possible Solutions:**
1. **Formspree** (free tier available) - Add `action="https://formspree.io/f/YOUR_ID"` to the form
2. **Netlify Forms** - Would require moving hosting to Netlify
3. **Google Forms** - Embed or redirect to a Google Form
4. **EmailJS** - Client-side email sending service

**To investigate:**
- Check what the current form action/JavaScript is doing in contact.html
- Choose a form backend service and integrate it
