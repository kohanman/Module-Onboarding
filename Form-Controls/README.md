# Form Controls

## Learning Objectives

<!--{{<objectives>}}>-->

- [x] Interpret requirements and check against a list of criteria
- [x] Write a valid form
- [x] Test with Devtools
- [x] Refactor using Devtools
<!--{{<objectives>}}>-->

## Task

We are selling t-shirts. Write a form to collect the following data:

Our customers already have accounts, so we know their addresses and charging details already. We don't need to collect that data. We want to confirm they are the right person, then get them to choose a colour and size.

Writing that out as a series of questions to ask yourself:

1. What is the customer's name? I must collect this data, and validate it. But what is a valid name? I must decide something.
2. What is the customer's email? I must make sure the email is valid. Email addresses have a consistent pattern.
3. What colour should this t-shirt be? I must give 3 options. How will I make sure they don't pick other colours?
4. What size does the customer want? I must give the following 6 options: XS, S, M, L, XL, XXL

All fields are required.
Do not write a form action for this project.

## Developers must test their work.

Let's write out our testable criteria. Check each one off as you complete it.

- [x] I have used HTML only.
- [x] I have not used any CSS or JavaScript.

### HTML

- [x] My form is semantic html.
- [x] All inputs have associated labels.
- [x] My Lighthouse Accessibility score is 100.
- [x] I require a valid name. I have defined a valid name as a text string of two characters or more.
- [x] I require a valid email.
- [x] I require one colour from a defined set of 3 colours.
- [x] I require one size from a defined set of 6 sizes.

## Resources

- [MDN: Form controls](https://developer.mozilla.org/en-US/docs/Learn/Forms)
- [MDN: Form validation](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation)
- [Lighthouse](https://developers.google.com/web/tools/lighthouse)
- [Lighthouse Guide](https://programming.codeyourfuture.io/guides/testing/lighthouse)
