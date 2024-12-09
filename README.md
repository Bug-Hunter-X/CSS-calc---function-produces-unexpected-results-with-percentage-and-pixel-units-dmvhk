# CSS calc() Unexpected Results

This repository demonstrates a bug encountered when using the CSS `calc()` function with a combination of percentage and pixel units.  The expected behavior is that `calc(50% - 10px)` should calculate 50% of the parent container's width, then subtract 10 pixels. However, the actual result varies across browsers and situations, often leading to incorrect layout.

## Bug Reproduction

The `bug.css` file contains the CSS code that reproduces the issue.  The HTML structure (not included) should simply contain an element to which the CSS is applied.  Observe the rendered width of the element; it will likely not match the expected calculation.

## Solution

The `bugSolution.css` file offers potential solutions to mitigate the issue, including using alternative units or approaches to achieve the desired layout.  The solution may involve using viewport units (`vw`) or adjusting the calculation method.

## Contributing

Contributions are welcome!  If you encounter variations of this bug or have alternative solutions, please feel free to open an issue or submit a pull request.