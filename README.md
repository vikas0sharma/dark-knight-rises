# Dark Knight Rises
A dark glow theme for awsome developers.

> A hero can be anyone. Even a man doing something as simple and reassuring as putting a coat around a young boy's shoulders to let him know the world hadn't ended. - Batman

**Not the theme you deserve, but the one you need right now!!**

## Screenshots

### JS
![screen](https://raw.githubusercontent.com/vikas0sharma/dark-knight-rises/master/images/js.png)

### HTML

![screen](https://raw.githubusercontent.com/vikas0sharma/dark-knight-rises/master/images/html.gif)

### CS
![screen](https://raw.githubusercontent.com/vikas0sharma/dark-knight-rises/master/images/cs.png)



## Enable Glow

### Step 1: Install Custom CSS and JS Loader
Install [this](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) excellent plugin that allows you to load custom CSS and JS from the VS Marketplace. Please carefully read the ReadMe regarding permission for that extension before continuing with this installation.

### Step 2: Get CSS
Locate the-dark-knight.css either in this extension's VS code install directory, or directly from the [github repo](https://github.com/vikas0sharma/dark-knight-rises/blob/master/dark-knight-rises.css).

### Step 3: Update CSS path in settings.json
Copy your chosen CSS file to a location on your machine, such as your user folder. 
Copy the file path and add it to your VS code *settings.json*. On Mac it might look something like the snippet below:

```javascript
{
  "vscode_custom_css.imports": [
    "file:///Users/{your username}/the-dark-knight.css"
    ],
    "vscode_custom_css.policy": true,
}
```
Windows might resemble:

```javascript
{
  "vscode_custom_css.imports": [
    "file:///C:/Users/{your username}/the-dark-knight.css"
    ],
    "vscode_custom_css.policy": true,
}
```

Important: Make sure you include the file protocol in the path i.e. file://

### Step 4: Enable CSS

Open your command palette with Ctrl + Shift + P or Shift + ⌘ + P and choose "Enable custom CSS and JS". It will prompt you to restart, and when you do the lights should be on :)

At this point, VS Code may pop up a message to say that it is corrupted, this is caused by the custom CSS & JS extension and not this theme. As their installation instructions say, you can click "Don't show again" to dismiss the popup.

*NOTE*: Every time you update VS code, you will need to repeat this step to re-enable custom CSS and JS. Similarly, when the theme updates, you will need to copy the updated css to your chosen location.

### Step: 5 Install font (Optional)

You can also download this awsome font [victor mono](https://rubjo.github.io/victor-mono/)
