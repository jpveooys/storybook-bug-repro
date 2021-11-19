# Storybook repro for JSX expression freeze

To reproduce:

1. Run `yarn install`
2. Run `yarn storybook`
3. Visit http://localhost:6006/?path=/docs/example-header--logged-in

The browser freezes (Firefox 94 and Chrome 96 tested).

Note that this doesn't happen in a production build. It also doesn't happen if the story is constructed using the args pattern.
