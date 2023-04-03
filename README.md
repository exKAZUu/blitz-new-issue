# blitz-new-issue

This repository provides reproduction steps for https://github.com/blitz-js/blitz/issues/4112.

## Steps

1. `blitz new blitz-new-issue`
2. Select the following items
   ```
   ✔ Pick a new project's language › TypeScript
   ✔ Pick your new app template › Full - includes DB and auth (Recommended)
   ✔ Install dependencies? › yarn
   ✔ Pick a form library (you can switch to something else later if you want) › React Final Form (recommended)
   ```
3. `cd blitz-new-issue`
4. `yarn blitz dev`
5. The following error is shown

![image](https://user-images.githubusercontent.com/436237/229410415-ceeda102-3890-48fc-acfd-fb732b2b00d4.png)
