# Editor

Write_Code™. Nothing Else.

After trying out virtually every online python interepreter, (and not liking any of them) I built my own.

![Editor Screenshot](https://github.com/msrsaditya/editor/blob/22b5fa8d68227748bad7815025d1b3079c2d6ef1/Screenshot.png)

# Why this Editor?

- It has no ads, no popups, no memberships, no sign-ins, no purchases, no telemetry etc. and hence no bloat. 
- The website UI is so minimalistic that it has no buttons at all! 
- Everything happens through keyboard shortcuts, which not only make you faster but also lets you focus more on the code, less on the details.
- It's generic as hell and doesn't force any idealogy on you. It is what you make it to be.
- It runs on "YOUR" browser, not mine. It's completely serverless and runs on WebAssembly.
- All features in it are tailored for maximum productivity - from themes to fonts to shortcuts to everything.
- It's most suited for running small code snippets for rapid testing and prototyping. It's also recommended for beginners since it basically just requires a web browser and nothing else.
- This level of minimalism both in design and by design can be found nowhere on the internet. This is basically the ArchLinux of Editors.

# Keyboard Shortcuts

- **Ctrl/Cmd+Enter**: Run code
- **Ctrl/Cmd+Left Arrow**: Expand Output
- **Ctrl/Cmd+Right Arrow**: Expand Code
- **Ctrl/Cmd+K**: Open a new instance
- **Ctrl/Cmd+S**: Export file
- **Ctrl/Cmd+O**: Import file

# Usage

To install any ([supported](https://pyodide.org/en/stable/#what-is-pyodide)) packages, simply add this line above your code:

```python
await micropip.install("<package_name>")
```
For example, to install pandas package you need to run:

```python
await micropip.install("pandas")
# write your pandas code here
```

The packages installed via micropip are stored in the in‐memory filesystem of your Pyodide session, so they remain available but not persisted across browser reloads or restarts. They are ephemeral, and you need to reinstall them every time your browser reloads. This is a feature not a bug.

## Acknowledgments

- [Pyodide](https://pyodide.org/) for bringing Python to the browser
- [CodeMirror](https://codemirror.net/) for the powerful editor component
- [Dracula Theme](https://draculatheme.com/) for the awesome dark theme
