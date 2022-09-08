# Manim Devcontainer

A devcontainer to get started coding with manim quickly and easily.

Note, this uses manim ce (community edition).

# Getting Started

## Platform

### Github Codespaces

Remember to check whether you have access to github codespaces, either by buying it, applying to the beta program or from your company/institution.

1. Fork the repository (by clicking the fork button on the top right of your screen)
2. Click the green code button, then under codespaces click "Create codespace on main."

### Local Installation

1. Fork the repository (by clicking the fork button on the top right of your screen).
2. Clone your forked repository to your local machine.
3. Install docker desktop (if your operating system is windows, you may need to install WSL 2 for this). 
4. Install the VS Code extension: "Remote - Containers".
5. Then click on the green button on the very bottom left, which will bring up a pop up, then click "reopen in container".

## Rendering 

The command to render a scene is `manim render filename.py SceneName`.

There is a python file `example_scenes.py` which contains a few example scenes you can practice rendering. To render the SquareToCircle scene, we type in the terminal `manim render example_scenes.py SquareToCircle`.

You can now view the video by looking under the folder `media/videos/example` and then clicking on the video which will have the name of your scene.

We can also define the quality (default is 1920x1080 60FPS). We can add `-ql` for 854x480 15FPS, `-qm` for 1280x720 30FPS, `-qh` for 1920x1080 60FPS, `-qp` for 2560x1440 and `-qk` for 3840x2160 60FPS. \
For example, `manim render -ql example_scenes.py SquareToCircle` will render the scene at 854x480 15FPS. Note, lower quality videos render faster, so it is adviced to render low quality videos while coding, and higher quality videos when you need to export them. 

To get more options and help with rendering, type `manim render --help`.

## Learning Resources 

[Manim CE Tutorial Page](https://docs.manim.community/en/stable/tutorials/index.html) (the quickstart page should give you a quick idea of the basics) \
[Manim CE Example Page](https://docs.manim.community/en/stable/examples.html) (looking at the examples to get ideas and understand how they did it) \
[Manim Beginner Video](https://www.youtube.com/watch?v=KHGoFDB-raE) (a really good explanation of manim concepts)

Take your time and experiment with the concepts as you are learning them, have fun :)
