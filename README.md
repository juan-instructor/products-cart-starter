# Shopping Cart Challenge

Each next challenge is increasingly more difficult. Try to complete them all and share your
progress in #practice. I hope you enjoy the challenge 🎯.

1. Fix Bootstrap styles! by using variables and overriding their `--bs-*` defaults

> [!NOTE]
> Make sure you know if their styles are defined in `:root {}` or in the `class`, it can vary so always have the `Dev Tools` open.

2. Make sure your end design aligns with `./design` assets.

> [!IMPORTANT]
> Make sure to use only `BootStrap` and utility styled classes.

3. In `cart.js` file there will be two functions `incrementBy` and `decrementBy`.
   Find a way to unify these two functions into one! They seem to be doing pretty similar things 🤔.

4. In `cart.js` file there will be a function `canDecreaseBy`. Let's make this function
   a bit more flexible. Can you find a way to allow a programmer to use this function in two ways:

- One: Allowing a programmer to query and decrease item quantity in one call! 💭

- Two: Allowing to query only if item can be decreased by certain quantity (this is the default behaviour).

5. Add the functionality to allow a user to remove an item from our `cart` by clicking on
   the `x` button.

6. Finally, ( well first, if you have reached this exercise, then congratulations! 🎉) can
   you allow a user to enter the number of items they want to add to cart? Remember that
   `cartController` is already an input, so let's allow users to add many items at once. 🤯
