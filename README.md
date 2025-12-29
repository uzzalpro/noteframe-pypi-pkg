# noteframe

`noteframe` is a lightweight Python package for rendering **YouTube videos** and **web pages** directly inside **Jupyter Notebook, JupyterLab, and Google Colab**.

It helps you create rich, visual notebooks for learning, research, tutorials, and documentation.

## Use Cases

`noteframe` is especially useful for:

-  Learning notebooks
-  Research notes
-  Tutorials
-  Documentation notebooks

## Installation

Install `noteframe` from PyPI:

```bash
pip install noteframe
```

# 🚀 Quick Usage

Just import the required function and pass a YouTube URL or a website URL.

## ▶ Render a YouTube Video

```bash
from noteframe.youtube import render_youtube_video

render_youtube_video("https://www.youtube.com/example")
```

The video will be rendered inline inside your notebook.

## Render a Website

```bash
from noteframe.site import render_site

render_site("https://www.site.com/example")
```

The website will be displayed using an iframe inside the notebook.

# Requirements

## Requirements

- Python ≥ 3.9

### Supported Environments

- Jupyter Notebook
- JupyterLab
- Google Colab
