# Stream Overlay Html&Css
Dynamic, customizable Lower Third and Social Media animated overlays for OBS, Streamlabs, and other broadcasting software.

## 🌟 New Feature: Web Control Panel!
You no longer need to edit code manually! We have introduced a **Real-Time Web Control Panel**.

### How to use the Control Panel:
1. Double-click the `index.html` file to open it in your browser (or visit the hosted GitHub Pages link if available).
2. Use the left sidebar to customize everything in real-time:
   - Primary Theme Color
   - Animation Duration
   - Lower Third Name & Role
   - Add/Remove Social Media Handles & Font Awesome Icons
3. Watch your changes apply instantly in the live preview.
4. When you're happy with how it looks, click the **"Copy for OBS"** button below the preview.
5. Go to OBS, add a new **Browser Source**.
6. **Important:** *Uncheck* "Local File", and **Paste** the copied URL directly into the URL field!
7. Set the Width (1920) and Height (1080) and click OK.

### Manual Configuration
If you prefer not to use the generated URLs, you can still edit the `config.js` file manually as a fallback! The HTML files will automatically read from `config.js` if no custom URL data is provided.

## Demo
Open `index.html` to view the control panel and preview the overlays!

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
