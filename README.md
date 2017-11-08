# Nuxt.js Firebase Auth - SSR Version
This is an example of using Nuxt.js in SSR mode with Firebase Authentication

[Live Demo](https://nuxt-ssr-firebase-auth.now.sh)

## Files of Importance
- `/plugins/auth-cookie.js`
- `/plugins/firebase-client-init.js`
- `/services/firebase-admin-init.js`
- `/middleware/auth-check.js`
- `/store/index.js`

## Notes
For the Sign-In to work, you will need to add your production site url to the Firebase's Authorized Domains in the Authorization settings of the Firebase Console.

## Credits
I got a lot of help understanding what needed to happen by looking at this  so special thanks to the contributers of that project!
<a href="https://github.com/firebase/functions-samples/tree/master/template-handlebars" target="_blank">Firebase Function - Handlebars Example</a>
