# Koch Snowflake in HTML & JavaScript

The `index.html` web page renders a [Koch snowflake](https://en.wikipedia.org/wiki/Koch_snowflake) using a `<canvas>` element and a sprinkle of JavaScript. Wikipedia describes the Kotch snowflake thusly:

> The Koch snowflake is a fractal curve and one of the earliest fractals to have been described. ... The Koch snowflake can be built up iteratively, in a sequence of stages. The first stage is an equilateral triangle, and each successive stage is formed by adding outward bends to each side of the previous stage, making smaller equilateral triangles.

![A Koch snowflake with 5 iterations.](https://raw.githubusercontent.com/YellowYak/LineFractal/refs/heads/main/KochSnowflake.png)

You can zoom using the **Zoom Level** slider or mouse scroll wheel.

Use the **Iterations** slider to specify how many "iterations" to step through when generating the fractal: `0` iterations draws a single line segment; `1` iteration adds an equilateral triangle to the middle of the single line segment, creating four line segments; `2` iterations adds equilateral triangles to each of the four line segments, creating a total of 16 line segments; and so on. The screenshot above shows the fractal with five iterations.

The **Starting Config** drop-down allows you to specify the starting shape to "fracalize": the traditional equilateral triangle or a line.

The **Reset View** button returns the **Zoom Level** to 100% and recenters the fractal.

### [Live Demo](https://yellowyak.github.io/LineFractal/)

![A Koch snowflake from a line with 5 iterations.](https://raw.githubusercontent.com/YellowYak/LineFractal/refs/heads/main/KochSnowflakeLine.png)