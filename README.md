THE BETTER ONE COMPANY Ltd - Digital Flyer

A modern, interactive digital flyer for "THE BETTER ONE COMPANY Ltd" featuring synchronized typing animation and fast image gallery rotation.

🚀 Live Demo

You can view the live flyer by opening the index.html file in any modern web browser.

✨ Features

1. Typing Animation

· 18 professional messages in English and Kinyarwanda
· Normal typing speed (35ms per character)
· Continuous loop with smooth transitions
· ~1 minute total duration for all messages

2. Fast Image Gallery

· 28 product images organized into 4 categories
· Fast rotation: 2 seconds per image
· Automatic category switching
· Total time: 56 seconds for all images
· Synchronized completion with typing animation

3. Interactive Controls

· Pause/Resume gallery rotation
· Speed adjustment (Faster/Slower buttons)
· Restart presentation functionality
· Image counter (0/28 to 28/28)

4. Background Music

· Royalty-free Chill Hop Instrumental music
· Volume control (50% default)
· Auto-play after user interaction
· Toggle on/off functionality

5. Visual Design

· Modern gradient background with blue theme
· Glass-morphism card effects
· Responsive layout for all devices
· Smooth animations and transitions
· Professional color scheme

🏗️ Structure

```
index.html              # Main flyer file
/images/                # Product images (28 files)
/audio/                 # Background music file
```

📱 Categories

The 28 images are organized into 4 categories:

1. Hardware Products (Images 1-7)
2. Plumbing Materials (Images 8-14)
3. Construction Tools (Images 15-21)
4. Complete Solutions (Images 22-28)

🎮 How to Use

Basic Usage

1. Open index.html in a web browser
2. Click anywhere to start background music
3. The presentation starts automatically

Controls

· Pause/Resume: Stop or continue image rotation
· Faster: Increase image rotation speed
· Slower: Decrease image rotation speed
· Restart: Reset the entire presentation
· Music Toggle: Turn background music on/off

Contact Actions

· 📞 Call Now: Direct phone call to 0781264120
· 💬 WhatsApp: Open WhatsApp chat
· 🌐 Visit Website: Open company website

⚙️ Technical Details

Timing Configuration

· Typing Speed: 35ms per character (fixed)
· Image Rotation: 2000ms per image (adjustable)
· Total Typing Time: ~70 seconds
· Total Image Time: 56 seconds (at 2s/image)
· Synchronization: Both complete around 1 minute

Responsive Design

· Desktop: Full gallery layout with side-by-side panels
· Tablet: Adjusted layout for medium screens
· Mobile: Optimized for small screens with stacked layout

Browser Compatibility

· Chrome (recommended)
· Firefox
· Safari
· Edge
· Opera

🎨 Design Features

Color Scheme

· Primary: #0066cc (Blue)
· Accent: #00ffd0 (Cyan)
· Light: #eaf3ff (Light Blue)
· Dark: #062f6d (Dark Blue)

Animations

· Typing cursor with blink and pulse effects
· Image transitions with scale animations
· Gradient shifts on gallery cards
· Hover effects on interactive elements

Visual Effects

· Glass-morphism with backdrop filters
· Box shadows for depth
· Gradient borders
· Smooth transitions

🔧 Customization

Changing Images

Replace the image URLs in the allImages array in the JavaScript section:

```javascript
const allImages = [
  "/image/IMG-20260117-WA0005.jpg",
  // ... add your image paths here
];
```

Modifying Messages

Edit the messages array in the JavaScript section:

```javascript
const messages = [
  "Your message here",
  // ... add your messages here
];
```

Adjusting Speeds

· Typing Speed: Change typingSpeed variable (in milliseconds)
· Image Speed: Change imageSpeed variable (in milliseconds)

Changing Categories

Modify the categories array:

```javascript
const categories = [
  { 
    name: "Your Category Name", 
    images: allImages.slice(startIndex, endIndex) 
  },
  // ... more categories
];
```

📞 Contact Information

Displayed prominently in the flyer:

· 📍 Address: GIKONDO MEREZE 1
· 📞 Phone: 0781264120 / 0788704173
· ✉ Email: thebetteronecompanyltd@gmail.com
· 🌐 Website: thebetteronecompanyltd.netlify.app

🎯 Purpose

This digital flyer is designed to:

1. Showcase company products through images
2. Present company information through animated text
3. Provide easy contact methods
4. Create an engaging 1-minute presentation
5. Work across all devices and browsers

📋 Requirements

· Modern web browser with JavaScript enabled
· Internet connection for loading external resources
· Audio support for background music

🔒 Privacy

· No user data collection
· No cookies or tracking
· All resources loaded locally
· Contact actions open external apps/sites

📄 License

This digital flyer is created for THE BETTER ONE COMPANY Ltd. All images and content are property of THE BETTER ONE COMPANY Ltd.

🐛 Troubleshooting

Images Not Loading

· Check image file paths in the allImages array
· Ensure images are in the correct directory
· Check browser console for errors

Music Not Playing

· Browser may require user interaction first
· Check if browser blocks auto-play
· Verify audio file path

Animation Issues

· Ensure JavaScript is enabled
· Try a different browser
· Clear browser cache

Responsive Issues

· Check viewport meta tag
· Test on different screen sizes
· Ensure CSS media queries are correct

🤝 Support

For issues or questions regarding this digital flyer, contact THE BETTER ONE COMPANY Ltd:

· Phone: 0781264120
· WhatsApp: +250781264120
· Email: thebetteronecompanyltd@gmail.com

---

THE BETTER ONE COMPANY Ltd - Quality • Reliability • Professional Service
