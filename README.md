# Minial setup for Shadow-cljs & Storybook.js

**Notice:** [Shadow-cljs][1] versions newer than `2.11.26` will not work with [Storybook.js][2].

Newer versions makes the generated JavaScript "unusable" by Storybook.

[1]: https://github.com/thheller/shadow-cljs
[2]: https://storybook.js.org/


Install depdendencies:

```
npm install
```


Run application (in development mode):

```
npx shadow-cljs watch frontend
```


Build storybook (stories):

```
npx shadow-cljs watch storybook
```


Start Storybook (opens new browser tab):

```
npx start-storybook
```
