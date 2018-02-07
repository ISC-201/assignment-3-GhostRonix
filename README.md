# Assignment-3

- [ ] If you haven't already please create a release for version **v0.0.2**. It should represent your work for *Assignment 2*.
 - [ ] Remember to add release notes which should include the new features added in our last assignment. 
- [ ] Add a `Vector4` class. It should have the same API as our `Vector2` and `Vector3` classes. The fourth component should be called **w**.
- [ ] Let's add warping. Your square, which should be rendering at the center of the screen and moving freely upon input should appear on the bottom of the screen when it reaches the upper border, through the left side of the screen when it reaches the right side border and viceversa (for both cases).
 - [ ] Once warping is done, please modify your `Player` class (if you don't have one it's a good time to create it) and add the following functions for movement:
    - [ ] `MoveForward`
    - [ ] `RotateLeft`
    - [ ] `RotateRight`
- [ ] Experiment with `GL_LINE_LOOP`, at the moment we are drawing a Square, attempt to draw a different shape to represent the `Player` (or the ship). Bear in mind that the order at which you pass these values is important, please read the documentation to learn more about this. These are the points I'm using for my default ship:
  * 0, 20
  * 12, -10
  * 6, -4
  * -6, -4
  * -12, -10
  
  ## Notes
  Remember to add your repository as a sub module to this one. Please feel free to update the README if necessary for both, the assignment repo or your game repo.
