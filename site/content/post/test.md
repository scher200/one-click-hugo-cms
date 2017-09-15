---
title: TEST
date: 2017-09-15T13:01:39.246Z
description: This is a test
image: null
---
allthisiscode

\`\`\`

console.log(window);

const netlifyIdentity =  import "netlify-identity-widget";

netlifyIdentity.on('init', user => console.log("init"));

netlifyIdentity.on('login', login => console.log("logged in: " \+ user));

netlifyIdentity.init(); // initialize it

netlifyIdentity.open(); // open the modal

\`\`\`
