# AR Mini-Golf Course Creator 🏌️‍♂️

An interactive web-based tool for high school students to design mini-golf courses and view them in augmented reality!

## 🎯 Workshop Overview

**Duration:** 30 minutes  
**Groups:** 4 groups of 15 students  
**Activity:** Design one mini-golf hole per group with obstacles

## 🚀 Quick Start - Deploy to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the **"+"** button (top right) → **"New repository"**
3. Name it: `ar-minigolf-workshop`
4. Make it **Public**
5. Check **"Add a README file"**
6. Click **"Create repository"**

### Step 2: Upload the File

1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop the `ar-minigolf-creator.html` file
3. Rename it to `index.html` (important!)
4. Click **"Commit changes"**

### Step 3: Enable GitHub Pages

1. Go to repository **Settings** (top menu)
2. Scroll down to **"Pages"** (left sidebar)
3. Under **"Source"**, select **"main"** branch
4. Click **"Save"**
5. Wait 1-2 minutes, then refresh the page
6. You'll see: "Your site is published at https://YOUR-USERNAME.github.io/ar-minigolf-workshop/"

### Step 4: Test It!

Open the URL on your phone and computer to test before the workshop!

---

## 📱 Workshop Day Setup

### Before Students Arrive:

1. **Test the website** on your phone and laptop
2. **Project the website** on the classroom screen
3. **Create 4 QR codes** (one for each group):
   - Use [QR Code Generator](https://www.qr-code-generator.com/)
   - All use the same URL: `https://YOUR-USERNAME.github.io/ar-minigolf-workshop/`
   - Print them large or display on tablets

4. **Prepare one device** per group (or have students use their phones)

### Workshop Timeline (30 minutes):

**Minutes 0-5: Introduction**
- Show the projected website
- Explain: "You'll design one hole of a mini-golf course"
- Demo: Place one object and rotate it
- Show AR mode (if you have AR device ready)

**Minutes 5-8: Group Assignment**
- Divide into 4 groups
- Each group scans QR code or navigates to URL
- Click their group number (Group 1, 2, 3, or 4)

**Minutes 8-23: Design Time**
- Groups collaborate to design their hole
- Encourage them to:
  - Make it challenging but fair
  - Use 5-8 obstacles
  - Think about ball path
  - Test difficulty mentally

**Walking around tips:**
- Ask: "How would the ball move through this?"
- Encourage: "Try rotating that obstacle!"
- Challenge: "Can you make it more interesting?"

**Minutes 23-28: Gallery Walk**
- Each group views others' courses
- Switch between group numbers to see all designs
- Optional: Vote on favorites (hardest, most creative, etc.)

**Minutes 28-30: AR Demo & Wrap-up**
- If available, show AR mode on one device
- Discuss: What did you learn about game design?
- Mention careers: Game designer, AR developer, level designer

---

## 🎮 How to Use the Tool

### For Students:

1. **Select Your Group** - Click Group 1, 2, 3, or 4 button at top
2. **Choose an Obstacle** - Click one of the colorful buttons:
   - 📐 Straight Ramp
   - 🌙 Curved Ramp
   - 🚇 Tunnel
   - 🧱 Wall
   - 🌀 Windmill (spins automatically!)
   - ⚙️ Moving Obstacle (moves side to side!)
   - 🎪 Jump
   - 💧 Water Hazard

3. **Place It** - Click on the green surface where you want it
4. **Select to Edit** - Click on the object you placed
5. **Adjust It**:
   - **Size slider** - Make it bigger or smaller
   - **Rotation slider** - Turn it around
   - **Height slider** - Raise it up

6. **View in AR** - Click "👓 View in AR" to see it in real space (needs AR-capable phone)

### Controls at Bottom:
- ❌ **Delete Selected** - Remove the object you clicked on
- 🗑️ **Clear Course** - Start over (deletes everything)

---

## 🎓 Learning Objectives

Students will learn about:
- **Spatial reasoning** - Visualizing 3D objects in space
- **Game design principles** - Challenge, balance, player experience
- **Iteration** - Testing and improving designs
- **Collaboration** - Working together to make decisions
- **AR technology** - How augmented reality works

---

## 💡 Discussion Questions

After the activity:

1. **"What made your hole challenging?"**
2. **"If you could test it with a real ball, what would you change?"**
3. **"Which group's hole would you want to play? Why?"**
4. **"How is designing a game level different from playing it?"**
5. **"Where else could AR be useful?"** (Architecture, medicine, education, shopping)

---

## 🔧 Technical Details

### What's Included:
- ✅ Works on desktop and mobile browsers
- ✅ No accounts or downloads required
- ✅ 4 separate workspaces (one per group)
- ✅ 8 different obstacle types
- ✅ Resize and rotation controls
- ✅ AR viewing capability (on compatible devices)
- ✅ Animated objects (windmill spins, obstacle moves)

### AR Requirements:
- **iOS**: iPhone 6S or newer (iOS 11+)
- **Android**: ARCore-compatible device
- **Browser**: Safari (iOS) or Chrome (Android)

### Browser Compatibility:
- Chrome, Firefox, Safari, Edge (latest versions)
- Mobile browsers supported

---

## 🐛 Troubleshooting

**"The website won't load"**
- Check your internet connection
- Try a different browser
- Clear browser cache

**"I can't place objects"**
- Make sure you clicked an obstacle button first (it should turn green)
- Click on the green surface (not the borders)

**"AR mode shows a black screen"**
- AR requires camera permissions - allow when prompted
- Only works on AR-capable devices
- Try Safari on iOS or Chrome on Android

**"Objects disappeared"**
- Make sure you're on the right group number
- Each group has separate objects

**"I placed an object in the wrong spot"**
- Click on it to select (it will glow yellow)
- Click "Delete Selected" 
- Place a new one

---

## 🎨 Customization Ideas

Want to modify for your workshop? Here are ideas:

### Easy Modifications:
- Change colors in the HTML file (search for color codes like `#2E7D32`)
- Add more groups (duplicate group button code)
- Change surface size (edit `width` and `height` in line 216)

### Advanced Modifications:
- Add new obstacle types (follow the pattern in `assetTemplates`)
- Add scoring system
- Add ball physics simulation
- Create multi-hole courses

---

## 📚 Additional Resources

**For Students:**
- [A-Frame School](https://aframe.io/aframe-school/) - Learn 3D web development
- [Three.js Journey](https://threejs-journey.com/) - 3D graphics course
- [CS First by Google](https://csfirst.withgoogle.com/) - Free coding courses

**For Instructors:**
- [A-Frame Documentation](https://aframe.io/docs/)
- [WebXR Device API](https://www.w3.org/TR/webxr/)
- [Game Design Principles](https://www.gamedeveloper.com/design/the-13-basic-principles-of-gameplay-design)

---

## 📝 License

This project is free to use for educational purposes. Feel free to modify and share!

---

## ❓ Questions?

If you have issues during setup, common solutions:
1. Make sure the file is named `index.html` (not `ar-minigolf-creator.html`)
2. Wait 2-3 minutes after enabling GitHub Pages
3. Try accessing in an incognito/private browser window
4. Check that your repository is set to "Public"

**Have a great workshop! The students are going to love this! 🎉**
