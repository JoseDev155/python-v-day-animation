# Valentine's Day Animation

## Development Environment

- **Operating System**: Windows 11
- **Python version**: 3.13.1
- **Manim**: Manim Community v0.19.0
- Visual Studio Code
- Chocolatey
- MiKTeX

## Virtual Environment

Create a `venv`:

```bash
python -m venv <venv-name>
```

Activate `venv`:

```bash
./<venv-name>/Scripts/./Activate.ps1
```

Deactivate `venv`:

```bash
deactivate
```

## Required Installations

### Download Links

**MiKTeX** 
- Download [MiKTeX](https://miktex.org/download)

**Chocolatey**
- Download [Chocolatey](https://chocolatey.org/install)

### Python packages

Install `numpy`:

```bash
pip install numpy
```

### Manim

Install `manim`:

```bash
choco install manim
```

### LaTeX

```bash
choco install manim-latex
```

## Program Usage
Explain how to run the program, including command-line instructions, execution examples, and any relevant parameters.

### Run the script

**First command-line instruction**

```bash
manim -pql hearth.py Hearth
```

Deatils:

- `p (preview)`:  Preview the Scene's animation and render the video
- `ql (quality low)`: Quality low to 480p15
- `hearth.py`: Python file with the Scene
- `Hearth`: Scene (class)

**Second command**

```bash
manim -pqh hearth.py Hearth
```

Deatils:

- `qh (quality high)`: Quality high to 1080p60

Here’s the translation of the text into English for your README:

**IMPORTANT**

Regardless of which command is executed, a dialog box may appear saying "preview.sty file not found," and we will be given the option to choose between **Install** or **Cancel**.

It is recommended to choose **Install**.

### Output

A `media` directory will be created with the texts, images, and the resulting video from the animation according to the parameters we have selected (`-pql` or `-pqh`)

## Tools and Technologies Used

### Chocolatey

Chocolatey is a package manager for Windows.

### MiKTeX

MiKTeX is a LaTeX distribution for Windows.


# Python Code by "Pildoras de programación"

This youtube channel contains a Python code originally created by [Pildoras de programación](https://www.youtube.com/@pildorasdeprogramacion). You can find more details or check out the original video at the following link:

- [Hearth with Python and Manim](https://www.youtube.com/shorts/3j1TcJ6cLJ0)
