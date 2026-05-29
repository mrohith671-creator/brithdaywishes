## 🎉 Birthday Wishes Interactive Landing Page

A beautiful, interactive birthday wishes website with multiple pages and surprise elements!

### 📋 Features

1. **Landing Page** - Beautiful animated birthday greeting with floating balloons
2. **Password Page** - Secure access using date of birth (DOB)
3. **Party Intro Page** - Confetti animation with "Wishing You 24 Birthday!" message
4. **Surprise Page** - Yes/No buttons to reveal the surprise (No shows sad emoji and encourages to continue)
5. **Letter Page** - A heartfelt personalized greeting message

### 🔧 How to Use

1. **Open the website:**
   - Simply open `index.html` in your web browser

2. **Set the Password:**
   - Edit `script.js` and find this line:
     ```javascript
     const correctPassword = '15-05-2002'; // Change this to the actual DOB
     ```
   - Replace `15-05-2002` with the birthday in DD-MM-YYYY format

3. **Customize the Letter:**
   - Edit the letter content in `index.html` (around line 145)
   - Replace the greeting message with your personal message

### 🎨 Page Flow

```
Landing Page (Click "Let's Begin")
     ↓
Password Page (Enter DOB in DD-MM-YYYY format)
     ↓
Party Page (Confetti animation - Click "Continue")
     ↓
Surprise Page (Choose "Yes" or "No")
     ↓
Letter Page (Personalized greeting message)
```

### ⚙️ Customization

#### Change the Birthday
In `script.js`, update:
```javascript
const correctPassword = 'DD-MM-YYYY'; // Your birthday
```

#### Personalize the Letter
In `index.html`, update the letter content with your message. The template includes:
- Personal greeting
- Birthday wishes
- Memorable moments
- Future wishes and aspirations
- Personal signature

#### Update Colors
Edit the gradient colors in `styles.css`:
- Landing page: `linear-gradient(135deg, #667eea 0%, #764ba2 100%)`
- Party page: `linear-gradient(135deg, #f093fb 0%, #f5576c 100%)`
- Surprise page: Similar gradients available

### 📱 Responsive Design

The website is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones

### 🎬 Animations

- Bouncing title on landing page
- Floating balloons
- Confetti animation on party page
- Smooth page transitions
- Button hover effects
- Wiggling sad emoji

### 🛠️ Files

- `index.html` - Main HTML structure with all 5 pages
- `styles.css` - Beautiful styling and animations
- `script.js` - Interactive functionality
- `README.md` - This file

### 💡 Tips

1. Test the password with: `15-05-2002` (default)
2. The "No" button on the surprise page won't exit - it shows a sad emoji and encourages opening the letter
3. The letter page is scrollable for longer messages
4. All animations are smooth and responsive

### 🎁 Make It Yours

Feel free to:
- Change colors and fonts
- Add more animations
- Include photos or images
- Add sound effects
- Customize the message

Enjoy creating an unforgettable birthday experience! 🎉

---

**Made with ❤️ for birthdays**
