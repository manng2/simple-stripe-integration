# Simple stripe integration

Front end: React\
Back end: NodeJS

## Installations and configurations

- Run `git clone --recurse-submodules https://github.com/manng2/simple-stripe-integration`
- Install and run `React` project
  - at the root folder, cd `webapp`
  - run `npm install`
  - create `.env.local` file with content like this
    > PORT=4200\
    > REACT_APP_STRIPE_API_KEY=pk_test_51MkdfSLiErps3Z1hbRvWimP85toa73MaV1dC3K7zafZOesdBQRVdWwOWaVKFHn5DnERwbFBepxrQCKafb8e7XB2g00M3kId3bv
  - run `npm start`
- Install and run `NodeJs` project
  - at the root folder, cd `api`
  - run `npm install`
  - create `.env` file with content like this
    > PORT=3000\
    > STRIPE_API_KEY=sk_test_51MkdfSLiErps3Z1hSnQjgpBhqHZLUo7RoYVYWpWmThh82u91JgWMwCiFBiA3TwKDPWCMCzfC7VYNuIDBpSkLXM6d006y3kbECU
  - run `npm run dev`
