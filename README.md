# noteframe

A lightweight Python package for rendering YouTube videos and web pages
inside Jupyter Notebook, JupyterLab, and Google Colab.

Installation
```bash
pip install noteframe
```
Usage

Render a YouTube video

from noteframe.youtube import render_youtube_video
render_youtube_video("https://www.youtube.com/example")

Render a website

from noteframe.site import render_site
render_site("https://www.example.com")

Requirements

Python 3.9+

Supported Environments

Jupyter Notebook  
JupyterLab  
Google Colab
