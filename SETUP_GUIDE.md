# Data & AI Team Survey System - Setup Guide

## What You've Got

I've created a complete survey system with two apps:

1. **Survey App** (`survey-app.html`) - For attendees to answer on their phones
2. **Dashboard** (`dashboard.html`) - Live results display for the main screen

## How It Works

### The Flow
1. Attendees scan a QR code from your PowerPoint
2. They open the survey on their phones and answer both questions
3. Responses are stored in real-time
4. The dashboard automatically updates every 3 seconds showing all responses
5. New responses appear with a green glow effect

## Setup Instructions

### Step 1: Get Your Survey Online
You need to upload both HTML files to a web hosting service. Here are your options:

**Option A: Netlify (Recommended - Free & Easy)**
1. Go to https://app.netlify.com/drop
2. Drag and drop both HTML files
3. You'll get two URLs instantly (no account needed)

**Option B: Your Company's Web Server**
1. Ask your IT team to host these files
2. They'll give you the URLs

### Step 2: Generate QR Code
1. Take the survey app URL (the one for `survey-app.html`)
2. Go to https://www.qr-code-generator.com/
3. Paste your survey URL
4. Download the QR code image
5. Add it to your PowerPoint slide

### Step 3: On Event Day

**Before the event starts:**
1. Open the dashboard (`dashboard.html` URL) on the presentation computer
2. Put it in full-screen mode (F11)
3. Keep it running in the background

**During the event:**
1. Show the slide with the QR code
2. Tell attendees: "Scan this code and share your thoughts"
3. Switch to the dashboard when you're ready to review responses
4. Watch responses appear live!

## Questions Shown to Attendees

**Question 1:** "What drives you to continuously improve yourself and support the growth of those around you?"

**Question 2:** "What's one initiative or improvement you'd like to see our business unit implement in 2026?"

## Features

✓ Mobile-friendly design
✓ Real-time updates (every 3 seconds)
✓ Responses appear newest first
✓ Character limit (500 chars per question)
✓ Clean, modern interface
✓ Success confirmation for attendees
✓ Live response counter

## Tips for Success

- **Test it first**: Send the survey link to a colleague and submit a test response to make sure everything works
- **Announce clearly**: Give people 2-3 minutes to scan and respond
- **Show the dashboard**: Let attendees see their responses appearing live - it's engaging!
- **Keep it open**: Leave the dashboard open during breaks if you want to collect more responses

## Troubleshooting

**"Responses aren't showing up"**
- Make sure both the survey app and dashboard are using the same hosting service
- Check that attendees are submitting (they should see a green checkmark)
- Refresh the dashboard manually if needed

**"QR code isn't working"**
- Verify the URL is correct
- Make sure it starts with `https://`
- Test it with your own phone first

## Need Changes?

I can help you:
- Customize the questions
- Change colors/branding
- Add more questions
- Modify the dashboard layout
- Export responses to a file

Just let me know what you'd like to adjust!