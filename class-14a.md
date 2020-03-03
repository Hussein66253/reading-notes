# Transforms
## What are the transform property in CSS?
- The transform CSS property lets us **rotate**, **scale**, **skew**, or **translate** an element. It modifies the *coordinate space* of the CSS visual formatting model.
- There are many transform functions that are available:
   1. **scale():** Affects the size of the element, it also applies to the *font-size, padding, height, and width* of an element, too. It’s also a a shorthand function for the **scale X** and **scale Y** functions.  
  2. **skewX()** and **skewY():** Tilts an element to the *left* or *right*, like **turning a rectangle into a parallelogram**,*skew()* is a shorthand that combines **skewX()** and **skewY** by accepting both values.
  3. **translate():** Moves an element *sideways* or *up* and *down*.
  4. **rotate():** *Rotates* the element **clockwise** from its *current position*.
  5. **matrix():** A function that is probably not intended to be written by hand, but **combines** all transforms into one.
  6. **perspective():** Doesn’t affect the element itself, but affects the *transforms* of *descendent elements' 3D* transforms, allowing them all to have a *consistent depth perspective*.
  # Transitions
  - A transition occurs when a CSS property changes from one value to another value over a period of time. The transition property is a shorthand of *four CSS properties*, **transition-property** , **transition-duration**, **transition-timing-function** , **transition-delay**.
  ### What is the difference between transform and transition in CSS?
- **Transitions** allows property changes in CSS values to occur *smoothly over a specified duration* , **transforms** allows elements styled with CSS to be transformed in *two-dimensional or three-dimensional space*.
