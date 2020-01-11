# Directives
Like Angular view has directive here some of them:
- v-for="t in 4"
- v-model="modelName"
    * v-model can have extensions
      - v-model.trim
      - v-model.number
      - v-model.lazy
- v-if // v-show
    * v-if / v-show unmount component
    * v-show set to display none
- v-bind or ':', allow to do a lot of stuff.
    * :style={....}
- v-once: update only the first time it start the dom
- v-pre: show all the code of the template, will not process anything, show the 
       variable name
- v-on or @: binding to event, like click and mouse. 
    * .stop: e.stopPropagation
    * .prevent: e.preventDefault
    * .once: the click event ca be trigger only one time
    * .native: listen native elements of the DOM
    * with Keycodes, __I can configure my own__
_ v-html: to render string that are html
- v-text: is like mustache template.
