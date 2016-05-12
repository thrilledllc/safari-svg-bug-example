# safari-svg-bug-example

Test case url: [https://thrilledllc.github.io/safari-svg-bug-example/](https://thrilledllc.github.io/safari-svg-bug-example/)

Two issues occur with this reduced test case:

1! At small window sizes, a blue background sometimes appears. This is not defined anywhere in the markup nor in the user styles. Resizing the window makes the issue disappear.

Two examples:

![](screenshots/screenshot1.png)

![](screenshots/screenshot2.png)

2! SVG does not resize correctly while repeatedly resizing the window. 

Example, start with:

![](screenshots/screenshot3.png)

Resize to 

![](screenshots/screenshot4.png)

Reload the window to get the SVG element scaled correctly:

![](screenshots/screenshot5.png)
