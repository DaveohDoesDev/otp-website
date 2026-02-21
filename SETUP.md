# Over The Top Party Rentals - Website Setup

## Contact Form Setup (Web3Forms)

Your contact form is connected to **Web3Forms** - a free email service that will send form submissions directly to your email.

### Quick Setup (5 minutes):

1. **Get your free access key:**
   - Go to https://web3forms.com/
   - Enter your email address (where you want to receive inquiries)
   - Click "Create Access Key"
   - They'll send you an access key via email

2. **Add the key to your website:**
   - Open `index.html`
   - Find line 293 (or search for `YOUR_ACCESS_KEY_HERE`)
   - Replace `YOUR_ACCESS_KEY_HERE` with your actual access key

   ```html
   <!-- Before: -->
   <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE">

   <!-- After: -->
   <input type="hidden" name="access_key" value="abc123-your-actual-key-456def">
   ```

3. **Test it out:**
   - Save the file
   - Refresh your browser
   - Fill out the contact form and submit
   - You should receive an email with the form details!

### What you get (FREE):

- ✅ 250 form submissions per month
- ✅ Email notifications for each submission
- ✅ Spam protection
- ✅ File attachments (if needed)
- ✅ No Web3Forms branding

### Need More?

If you get more than 250 inquiries per month (that's awesome!), you can upgrade to their paid plan or switch to another service.

---

## Updating Contact Information

Don't forget to update your actual contact details in the website:

- **Phone number** - Currently set to `(540) 123-4567`
- **Email** - Currently set to `info@otprentals.com`

Find and replace these in `index.html` with your real contact information!

---

## Questions?

The website is ready to go - just add your Web3Forms key and update your contact info!
