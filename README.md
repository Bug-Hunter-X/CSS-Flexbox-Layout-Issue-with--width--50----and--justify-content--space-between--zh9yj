This repository demonstrates an uncommon layout issue that can occur when using CSS flexbox. The problem arises when a fixed width is applied to flex items in a container using `justify-content: space-between`. In some cases, this can lead to unexpected overlapping or inaccurate spacing of elements if the total width exceeds the container's width.

The `bug.css` file contains the problematic CSS code, while `bugSolution.css` offers a solution to ensure consistent and expected layout behavior across different browsers.