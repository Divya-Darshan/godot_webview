## godot-webview

1. Download this repository
2. Extract the [godot-webview addon](https://godotwebview.com/pages/downloads/) into the root of the project.
3. Open the project in Godot 4.5-dev4 (or newer)
4. Run the project, use WASD to move around, right mouse click to look

There are 2 scenes:

1. The main scene displays a WebView on a 3D plane, and you can fly around with the camera
2. The jinja2 scene showcases jinja2 rendering

## Mac OS: Metal

important: this project is configured to use Vulkan. On Mac OS, only the 
Metal renderer is available. Switch to the Metal renderer 
`Project -> Project Settings`.

![](metal.png)

## Keyboard events

#### Method 1

Enable "Capture keys" in the WebView properties.

#### Method 2

do it manually, checkout https://godotwebview.com/developer/getting-started/getting-started.html
