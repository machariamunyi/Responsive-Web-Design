# Learn HTML Forms by Building a Registration Form

**_1% Completed_**

**You can use HTML forms to collect information from people who visit your webpage.**

> In this course, you'll learn HTML forms by building a signup page. You'll learn how to control what types of data people can type into your form, and some new CSS tools for styling your page.

## Step 20

With `type="password"` you can use the pattern attribute to define a regular expression that the password must match to be considered valid.

Add a pattern attribute to the password input element to require the input match: `[a-z0-5]{8,}`

The above is a regular expression which matches eight or more lowercase letters or the digits `0` to `5`. Then, remove the minlength attribute, and try it out.