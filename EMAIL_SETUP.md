# Contact Form Email Setup Instructions

Your contact form is now **ready** to send real emails to `rivithranjuna60@gmail.com`! 

## Current Status:
- ✅ Form validation working
- ✅ UI feedback working
- ✅ EmailJS integration code ready
- ❌ **Need to setup EmailJS account** (5 minutes)

## Setup Steps (Follow in Order):

### Step 1: Create EmailJS Account
1. **Go to [EmailJS.com](https://www.emailjs.com/)**
2. **Sign up for FREE** using any email
3. **Verify your email** when they send confirmation

### Step 2: Add Email Service
1. **Go to "Email Services"** in EmailJS dashboard
2. **Click "Add New Service"**
3. **Select "Gmail"** (or your email provider)
4. **Click "Connect Account"** and login with `rivithranjuna60@gmail.com`
5. **Copy the SERVICE_ID** (looks like: `service_abc123`)

### Step 3: Create Email Template
1. **Go to "Email Templates"** in dashboard
2. **Click "Create New Template"**
3. **Use this template content:**

```
Subject: New Portfolio Contact: {{subject}}

Hi Rivith,

You received a new message through your portfolio website:

From: {{from_name}}
Email: {{from_email}}
Subject: {{subject}}

Message:
{{message}}

---
Sent from your portfolio contact form
```

4. **Save template and copy TEMPLATE_ID** (looks like: `template_xyz456`)

### Step 4: Get Public Key
1. **Go to "Account" → "General"** in EmailJS
2. **Copy your PUBLIC_KEY** (looks like: `pk_abc123def456`)

### Step 5: Update Your Code
**Open `script.js` and replace these 3 values:**

```javascript
// Line ~265: Replace YOUR_PUBLIC_KEY_HERE
emailjs.init("pk_abc123def456");  // Your actual public key

// Line ~268: Replace YOUR_SERVICE_ID and YOUR_TEMPLATE_ID  
emailjs.send("service_abc123", "template_xyz456", {
```

### Step 6: Test the Form
1. **Open your website**
2. **Fill out the contact form**
3. **Click "Send Message"**
4. **Check rivithranjuna60@gmail.com inbox** (may take 1-2 minutes)

## What Happens After Setup:
- ✅ **Real emails sent to rivithranjuna60@gmail.com**
- ✅ **Includes sender's name, email, subject, message**
- ✅ **You can reply directly to their email**
- ✅ **Free up to 200 emails/month**

## Troubleshooting:
- **"EmailJS is not defined"**: Refresh page, check internet
- **"Service not found"**: Double-check SERVICE_ID
- **"Template not found"**: Double-check TEMPLATE_ID
- **No email received**: Check spam folder, verify gmail connection

---
**After setup:** Every contact form submission will send an email to your Gmail!
