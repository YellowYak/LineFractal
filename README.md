# Koch Snowflake in HTML & JavaScript

The `index.html` web page renders a simplified version of a [Koch snowflake](https://en.wikipedia.org/wiki/Koch_snowflake) using a `<canvas>` element and a sprinkle of JavaScript.

![A Koch snowflake with 5 iterations.](https://raw.githubusercontent.com/YellowYak/LineFractal/refs/heads/main/KochSnowflake.png)

You can zoom using the **Zoom** slider or mouse scroll wheel. Use the **Iters** slider to specify how many "iterations" to step through when generating the fractal: `0` iterations draws a single line segment; `1` iteration adds an equilateral triangle to the middle of the single line segment, creating four line segments; `2` iterations adds equilateral triangles to each of the four line segments, creating a total of 16 line segments; and so on. The screenshot above shows the fractal with five iterations.

### [Live Demo](https://yellowyak.github.io/LineFractal/)