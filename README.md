# Inertial Pan

I recently made an overflowing container pannable (vertically) by mouse. Then I added the inertial pan effect for more natural feel. Now, I want to go deeper in this, because it feels like an interesting subject.

## Overview
There are two ways to pan:

- using the already existing scrollbars
- absolute positioning the content in the container

Both has their pros/cons, but absolute positioning is more advanced. I'll start with scrollbars, and later transition to absolute positioning.

### Problems to solve

- [x] Simple pan  
  The content should just track the mouse movement exactly.
- [ ] Simple inertia effect  
  The content should keep panning for some time after the mouse is released.
- [ ] Advanced inertia effect
  - [ ] Mid-pan direction check
  - [ ] Improved velocity calculation

