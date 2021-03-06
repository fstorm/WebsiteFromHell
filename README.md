## About this project/ Mission statement
The idea behind this project is to demonstrate, among other things, how poorly designed websites/ interfaces can lead to disabling users through, for example, poor accessibility engineering.<br>
We want to demonstrate to colleges how not design websites by having them attempt to navigate a purposely poorly build website/ form.<br>
We hope that by the end of this presentation/ demonstrations, colleges will get a better understanding for why accessibility is vital when designing front ends, and easy steps that can be taken to achieve more usable applications.<br> 

What to demonstrate (discussed til now):
- Screenreader
- Silly navigation
- Silly validation

Examples of screenreader problems that we can force:
- unclear text
- 'press here'
- unneeded alt text on img/ icon
- unclear label - input combinations
- no or unclear error messages (being read out)
- loading state not announced
- no skip to content

Examples of silly navigation problems that we can force:
- traverse form with first all labels then all input fields
- massive navigation bar without skip to content link
- elements that don't receive focus (and thus cannot be navigated to)
- elements without visible focus ()

Examples of silly validation problems that we can force:
- name must have x characters
- not aloud to use certain characters
- name must have middle name
- date of birth must be on x

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

###Thoughts
- What is the best way to do label-input combinations?
    - if you use aria-labeledby, do you need the label (i.e. set aria-hidden=true on lable)
    - will this confuse low visibility users?
- How much of this is about the demo, and how much of this is about 'the talk'/ learning about disability/ disabling
- Do we want a 'full on workable result' by the end of it, or more a 'here are bad examples here are good examples' kind of experience
- testing a11y?


Usefull document outlining problems currently faced with a11y from a business standpoint (among other things):
https://www.levelaccess.com/wp-content/uploads/2019/03/2019-State-of-Digital-Accessibility-Report-Final-a11y.pdf
