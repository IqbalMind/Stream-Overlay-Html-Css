# Stream Overlay Html&Css
Contains Lower Third and Social Media animated overlays. 
I've created what you need for a stream overlay without After Effects, media, or video files. These overlays are built purely with HTML and CSS for lightweight use in OBS, Streamlabs, or any other broadcasting software that supports browser sources.

## Features
- **Lightweight**: Pure HTML/CSS and minimal JavaScript.
- **Dynamic Configuration**: Easily change text, names, roles, and social media handles via `config.js` without touching HTML code.
- **Easy Customization**: Colors and dimensions are controlled via CSS Variables in `src/css/style.css`.
- **Modern Flexbox Layout**: Elements align perfectly regardless of font length.

## 🛠️ Configuration & Setup
Before adding to OBS, customize your details!
1. Open the `config.js` file in any text editor (like Notepad, VS Code, or TextEdit).
2. Edit the `lowerThird` section to change your **name** and **role**.
3. Edit the `socialMedia` section to update your handles. You can add more networks or remove ones you don't need. 
   *(Icons use Font Awesome classes, e.g., `"fab fa-twitch"`, `"fab fa-youtube"`)*.
4. Save `config.js`.

> **Pro-Tip**: You can customize the overlay colors by editing the `:root` section at the top of `src/css/style.css`.

## 📺 How To Use in OBS
1. Download this repository and extract it anywhere on your computer.
2. Open OBS Studio (or Streamlabs).
3. Under **Sources**, click the `+` button and add a new **Browser** source.
4. Check **Local File** and click **Browse** to select the `.html` file you want to use (`lowerthird.html` or `social-media.html`).
5. Set Width = `1920` (or `1280`) and Height = `1080` (or `720`).
6. *(Optional)* Set FPS to `60` if your stream runs at 60 FPS.
7. Scroll down and **Check** the box that says: `"Refresh browser when scene becomes active"`. (This makes the entrance animations play every time you switch to the scene).
8. Click OK.

*Note: You can hide/show the source in OBS to trigger the animation to play again!*

## Demo / Preview
Double-click `index.html` to open a preview control panel right in your browser!

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
