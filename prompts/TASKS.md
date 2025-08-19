# TASKS,md 

## INSTRUCTIONS FOR AI

1. Review all the tasks below and execute the ones that are marked 'R', for ready to execute.
1. The different states are:
  - [ ] do not execute - this task is not ready to execute.
  - [R] ready to execute.
  - [I] used by AI to indicate the task is implemented. Mark the task with the completion timestamp.
  - [X] task has been verified by human.


## PROMPT
```
Review TASKS.md and execute all tasks marked 'R' per the INSTRUCTIONS.
```

# v00.00.01
Generate app: index-auto.html
1. [X] Generate an one page HTML app to explore Voronoi diagrams. - Completed: 2025-08-17 20:09:11

# v00.00.02
Generate app: index-gpt5.html
1. [X] Generate an one page HTML app to explore Voronoi diagrams. - Completed: 2024-12-19 15:30:00
1. [X] Add a feature to support multiple color themes. - Completed: 2025-08-17 20:24:47

# v00.00.03
1. [X] - Make sure neighboring colors are different. Use up to 10 colors if needed. - Completed: 2025-08-17 20:38:37
1. [X] - Create 6 different color palettes. - Completed: 2025-08-17 20:38:37

# v00.00.04
1. [X] Whilst moving the dot, color the section black. When the mouse pointer is released to drop the dot, set it to one of the colors in the palette and apply the neighboring color algorithm. - Completed: 2025-08-17 20:50:17
1. [X] Color the Delaunay lines white. - Completed: 2025-08-17 20:52:41
1. [I] The color should change to one from the palette as soon as the mouse button is lifted. - Completed: 2025-08-18 18:46:52

# v00.00.05
1. [M] verify the algoritm for deduping colors - make sure it makes as few changes as possible

# v00.00.06
1. [I] Allow the panel on the left to be collapsible. Create a hamburger menu on the top left. - Completed: 2025-08-18 19:17:37

# v00.00.07
1. [R] Add more pallets up to 20.
1. [R] Recolor after any change in palette.
1. [R] When user clicks on a color in the palette:
      - set the color on the pallete to black
      - set the color used in the canvas to black
      - revert the color back when the mouse button is released.
1. [R] When the screen loads, set the colors to the Vivid palette
