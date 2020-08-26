# Discussion Questions: Exploring Props and State Further

In this program, we have three components: `App`, `MasterHog`, and `BabyHog`.

###### `MasterHog`:

- Has an eye color that can change via a radio button on the DOM
- Renders three `BabyHog`s, which inherit its eye color
- Owns the non-variable data associated with each `BabyHog`. This includes their: name, eye color, and hobby. _(Obviously, `MasterHog` gets to name her babies, and they genetically inherit her eye color. Not obviously, `MasterHog` also gets to determine their hobbies)_ Look inside `src/db.js` to see data defining what the `BabyHog` offspring should "inherit."

###### `BabyHog`:

- Has an eye color received from its parent
- Has a hobby assigned by its parent
- Has a name given by its parent
- Has a variable weight, that can be changed via buttons

**Note:** While the `MasterHog` component can change its own eye color via radio buttons, its children can only inherit the eye color of their parent!


## Directions:

- While the `changeWeight` method has been implemented in `BabyHog`, it is not 'hooked up' to the component. Make sure the function is invoked so our hogs can grow and shrink when either of the button's are clicked. (Consider how `MasterHog`'s `changeEyeColor` method is 'hooked up' if you are stuck here)

