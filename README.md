# Editor

Write_Code™. Nothing Else.

After trying out virtually every online python interepreter (and not liking any of them) I built my own.

![Editor Screenshot](https://via.placeholder.com/800x450)

# Why this Editor?

- It has no ads, no popups, no memberships, no sign-ins, no purchases, no telemetry etc. and hence no bloat. 
- The website UI is so minimalistic that it has no buttons at all! 
- Everything happens through shortcuts, which not only make you faster but also lets you focus more on the code, less on the details.
- It's generic as hell and doesn't force any idealogy on you. It is what you make it to be.
- It runs on "YOUR" browser, not mine. It's completely serverless and runs on WebAssembly.
- All features in it are tailored for maximum productivity - from themes to fonts to shortcuts to everything.
- It's most suited for running small code snippets for rapid testing and prototyping. It's also recommended for beginners since it basically just requires a web browser and nothing else.
- This level of minimalism both in design and by design can be found nowhere. This is the ArchLinux of Editors.

# Keyboard Shortcuts

- **Ctrl/Cmd+Enter**: Run code
- **Ctrl/Cmd+Left Arrow**: Expand Output
- **Ctrl/Cmd+Right Arrow**: Expand Code
- **Ctrl/Cmd+K**: Open a new instance
- **Ctrl/Cmd+S**: Export file
- **Ctrl/Cmd+O**: Import file

# Usage

To install any (supported) libraries:

```python
await pyodide_js.loadPackage("<library_name>")
```

## Acknowledgments

- [Pyodide](https://pyodide.org/) for bringing Python to the browser
- [CodeMirror](https://codemirror.net/) for the powerful editor component
- [Dracula Theme](https://draculatheme.com/) for the awesome dark theme
