There are two types of container classes in Bootstrap: container and container-fluid:
+ container: creates a fixed width container in the browser window. The fixed-width container is styled to appear at the center of the screen, omitting extra space on both sides.
+ container-fluid: creates a full-width fluid container

1. col-xs for extra small displays (screen width < 768px)
2. col-sm for smaller displays (screen width ≥ 768px)
3. col-md for medium displays (screen width ≥ 992px)
4. col-lg for larger displays (screen width ≥ 1200px)

When we specify the class col-xs-12, it means the element should span all 12 of the available Bootstrap columns on extra small screens. Bootstrap will automatically follow the layout specified
for the smallest screen size. Therefore, the div will span 12 columns in all types of
displays in this code.