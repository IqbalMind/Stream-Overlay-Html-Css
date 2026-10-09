# Stream Overlay Html&Css
Dynamic, customizable Lower Third and Social Media animated overlays for OBS, Streamlabs, and other broadcasting software.

This project supports **TWO ways** to customize your overlay. You can choose whichever method works best for you!

---

## Option 1: Real-Time Web Control Panel (Recommended)
You do not need to touch any code with this method. It is highly recommended if you are hosting this project on GitHub Pages or just want a visual editor.

1. Double-click the `index.html` file to open it in your browser (or visit the hosted web link).
2. Use the left sidebar to customize everything in real-time:
   - Primary Theme Color & Animation Duration
   - Lower Third Name & Role
   - Add/Remove Social Media Handles & Font Awesome Icons
3. Watch your changes apply instantly in the live preview.
4. When you're happy with how it looks, click the **"Copy for OBS"** button below the preview.
5. Go to OBS, add a new **Browser Source**.
6. **Important:** *Uncheck* "Local File", and **Paste** the copied URL directly into the URL field!
7. Set the Width (1920) and Height (1080) and click OK.

---

## Option 2: Manual Configuration (Local File)
If you prefer to keep everything strictly offline and load it directly from your computer, you can use the manual configuration method.

1. Open the `config.js` file in any text editor (like Notepad, VS Code, or TextEdit).
2. Edit the `lowerThird` section to change your name and role.
3. Edit the `socialMedia` section to update your handles. You can add more networks or remove ones you don't need. 
4. Save `config.js`.
5. Open OBS and add a new **Browser Source**.
6. **Check** "Local File" and click **Browse** to select either `lowerthird.html` or `social-media.html`.
7. Ensure you check **"Refresh browser when scene becomes active"** so animations play reliably.

## Demo
Open `index.html` to view the control panel and preview the overlays!

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
