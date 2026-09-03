# LaTeX portfolio

## Compile
    pdflatex portfolio.tex     (run twice, so page numbers settle)

Or upload portfolio.tex + the images folder to Overleaf.

## Images
Drop your photos in as:

    images/solar-station/main.jpg
    images/robot-arm-6dof/main.jpg
    images/ros-manipulator/main.jpg
    images/weld-vision/main.jpg
    images/matlab-sims/main.jpg
    images/thesis/main.jpg
    images/youtube/main.jpg

Any image that is missing renders as a grey placeholder box, so the file
always compiles. Add images one at a time as you get them.

## Editing
All content is below the "CONTENT" line in portfolio.tex.

Each project is one \project{} call with six arguments, in order:
  1. title
  2. image path
  3. placeholder caption (shown when the image is missing)
  4. what it is
  5. my role
  6. tools

To add a project, copy a \project{} block and edit it.
To reorder projects, move the blocks.
To remove one, delete the block.

## Notes
- Replace every [ bracketed ] item before sending.
- Escape underscores in text as \_  (e.g. Robotics\_MEXE\_3rdYearCourse)
