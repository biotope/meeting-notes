# Agenda

1. Integrate quality gate in boilerplate.
2. Make standard config of quality gate more "friendly" especially css defaults are too strict in my opinion and not every rule which generates an error atm helps to improve code quality.
3. Discuss next steps for "preview" with storybook.
4. Discuss current state of "build"

## Quality Gate 
- we are looking for a more "friendly" stylelint:
 - https://github.com/stylelint/stylelint-config-standard
 - https://github.com/primer/stylelint-config-primer
 - https://www.npmjs.com/package/stylelint-config-airbnb

## Biotope Preview
- will use storybook and adjust it for biotope.
- will add it also to the biotope cli to generate story files for components

## Action Items
- Integrate QG into boilerplate
- Look into less strict standards in QG
- remove "next" branch from "biotope/boilerplate" and update master package.json version of "build"
- @biotope/preview and @biotope/build will be worked on and reported back on the next core meeting
