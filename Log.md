# Log

My log of changes and thoughts I have while doing the project.

Forked and cloned the fork.

Updated the README to include more details about what the project does.

From the terminal did an pnpm install to get the packages. I'm seeing next 13 again... so much confusion online between different versions... maybe I will try "updating" some of these as well, we'll see.

dependencies:

- @sanity/vision 3.46.1
- @stripe/stripe-js 2.4.0 (3.5.0 is available)
- @types/node 20.8.2 (20.14.2 is available)
- @types/react 18.2.24 (18.3.3 is available)
- @types/react-dom 18.2.8 (18.3.0 is available)
- autoprefixer 10.4.16 (10.4.19 is available)
- axios 1.7.2
- chart.js 4.4.3
- eslint 8.50.0 (9.5.0 is available)
- eslint-config-next 13.5.4 (14.2.4 is available)
- next 13.5.4 (14.2.4 is available)
- next-auth 4.24.7
- next-auth-sanity 1.5.3
- next-sanity 5.5.11 (9.3.10 is available)
- postcss 8.4.31 (8.4.38 is available)
- react 18.2.0 (18.3.1 is available)
- react-chartjs-2 5.2.0
- react-datepicker 4.25.0 (7.0.0 is available)
- react-dom 18.2.0 (18.3.1 is available)
- react-hot-toast 2.4.1
- react-icons 4.12.0 (5.2.1 is available)
- sanity 3.46.1
- stripe 13.11.0 (15.12.0 is available)
- swr 2.2.5
- tailwindcss 3.3.3 (3.4.4 is available)
- typescript 5.2.2 (5.4.5 is available)

devDependencies:

- @types/react-datepicker 4.19.6 (6.2.0 is available)

I thought before I look through the code too much more, I'll just try to run it like the README suggests and see what happens....
It errors of course.

> ./node_modules/.pnpm/@sanity+client@6.20.0/node_modules/@sanity/client/dist/index.browser.js
> Attempted import error: 'retry' is not exported from 'get-it/middleware' (imported as 'retry').

ChatGPT says it is an issue with one of those libraries...

I did an `npm install` instead and that seemed to kick it into gear. As expected now though, we are missing configuration steps... which aren't mentioned anywhere in the README sadly. I do not see any `.env.local.example` or whatever the standard is that encourages you to copy that to `.env.local` and put in your own credentials. First off is an issue with the 'sanity' configuration... we don't have anything setup on that service, no data stored etc. Hmmm... guess it isn't "out of the box" after all, and we do need to go through the 'Tutorial video?' (which also isn't referenced in the README)

Started watching the video. I noticed it had no youtube 'bookmarks/chapters' ... but there are notes in the comments with time-codes to skip around.

I'm not vibing with the content. Going to try another demo.
