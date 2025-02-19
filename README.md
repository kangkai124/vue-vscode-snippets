# Vue VSCode Snippets modified by kk

## Description

These snippets were built to supercharge my workflow in the most seamless manner possible.

This repo was built particularly for real world use. It doesn't catalogue the API definitions, and it's not a kitchen sink approach. Rather, it focuses on developer ergonomics from the point of Vue of real world use. Included are the pieces I personally get sick of typing, have to keep looking up, or forget to consider while developing that I make more use of when they're at my fingertips.

_Current version: Vue2_

## Installation

_Either_

- click the extensions button (lowest square icon in the editor), and type in Vue VSCode Snippets, select the one by sdras

_or_

- go here [vscode Extensions Marketplace](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets)

```javascript
ext install Vue VSCode Snippets
```

You can enable tab completion (recommended) by opening `Code > Preferences > Settings` (on a Mac) and applying `"editor.tabCompletion": "onlySnippets"` to your personal settings

## Snippets

### Vue

| Snippet     | Purpose                                    |
| ----------- | ------------------------------------------ |
| `vbase`     | Single file component base with LESS       |
| `vbase-css` | Single file component base with CSS        |
| `vbase-pcss`| Single file component base with PostCSS    |
| `vbase-ts`  | Single file component base with Typescript |

### Template

| Snippet           | Purpose                             |
| ----------------- | ----------------------------------- |
| `vfor`            | v-for directive                     |
| `vmodel`          | Semantic v-model directive          |
| `vmodel-num`      | Semantic v-model number directive   |
| `von`             | v-on click handler with arguments   |
| `vel-props`       | Component element with props        |
| `vsrc`            | Image src binding                   |
| `vstyle`          | Inline style binding                |
| `vstyle-obj`      | Inline style binding with objects   |
| `vclass`          | Class binding                       |
| `vclass-obj`      | Class binding with objects          |
| `vclass-obj-mult` | Multiple conditional class bindings |
| `vanim`           | Transition component with JS hooks  |
| `vnuxtl`          | Nuxt Routing Link                   |
| `vroutename`      | router-link Named Routing           |
| `vroutenameparam` | router-link Named with Parameters   |
| `vroutepath`      | router-link Path Routing Link       |

### Script

| Snippet          | Purpose                                                                  |
| ---------------- | ------------------------------------------------------------------------ |
| `vdata`          | Component data as a function                                             |
| `vmethod`        | Vue method                                                               |
| `vcomputed`      | Vue computed property                                                    |
| `vwatcher`       | Vue watcher with new and old value args                                  |
| `vbeforecreate`  | beforeCreate lifecycle method                                            |
| `vcreated`       | created lifecycle method                                                 |
| `vbeforemount`   | beforeMount lifecycle method                                             |
| `vmounted`       | vmounted lifecycle method                                                |
| `vbeforeupdate`  | beforeUpdate lifecycle method                                            |
| `vupdated`       | updated lifecycle method                                                 |
| `vbeforedestroy` | beforeDestroy lifecycle method                                           |
| `vdestroyed`     | destroyed lifecycle method                                               |
| `vprops`         | Props with type and default                                              |
| `vimport`        | Import one component into another                                        |
| `vcomponents`    | Import one component into another within the export statement            |
| `vimport-export` | Import one component into another and use it within the export statement |
| `vmapstate`      | import mapState from Vuex into vue component component                   |
| `vmapgetters`    | import mapGetters from Vuex into vue component component                 |
| `vmapmutations`  | import mapMutations from Vuex into vue component component               |
| `vmapactions`    | import mapActions from Vuex into vue component component                 |
| `vfilter`        | Vue filter                                                               |
| `vmixin`         | Create a Vue Mixin                                                       |
| `vmixin-use`     | Bring a mixin into a component to use                                    |
| `vc-direct`      | Vue create a custom directive                                            |
| `vimport-lib`    | Import a library                                                         |
| `vimport-gsap`   | Import GreenSock with Timeline and Eases                                 |
| `vanimhook-js`   | Using the Transition component JS hooks in methods                       |
| `vcommit`        | Commit to Vuex store in methods for mutation                             |
| `vdispatch`      | Dispatch to Vuex store in methods for action                             |
| `vtest`          | A simple unit testing component                                          |
| `vinc`           | incrementer                                                              |
| `vdec`           | decrementer                                                              |
| `vconfig`        | vue.config.js file, example imports a sass file into every component     |

### Vuex

| Snippet         | Purpose                        |
| --------------- | ------------------------------ |
| `vstore`        | Base for Vuex store.js         |
| `vgetter`       | Vuex Getter                    |
| `vmutation`     | Vuex Mutation                  |
| `vaction`       | Vuex Action                    |
| `vmodule`       | Vuex Module                    |
| `vstore-import` | Import vuex store into main.js |
| `vstore2`       | Updated Base for Vuex store    |

### Vue Router

| Snippet              | Purpose                                       |
| -------------------- | --------------------------------------------- |
| `vrouter`            | Vue Router base                               |
| `vscrollbehavior`    | Vue Router scrollBehavior                     |
| `vbeforeeach`        | Vue Router global guards beforeEach           |
| `vbeforeresolve`     | Vue Router global guards beforeResolve        |
| `vaftereach`         | Vue Router global guards afterEach            |
| `vbeforeenter`       | Vue Router per-route guard beforeEnter        |
| `vbeforerouteenter`  | Vue Router component guards beforeRouteEnter  |
| `vbeforerouteupdate` | Vue Router component guards beforeRouteUpdate |
| `vbeforerouteleave`  | Vue Router component guards beforeRouteLeave  |

### Nuxt Config

| Snippet | Purpose                                                 |
| ------- | ------------------------------------------------------- |
| `nfont` | link to include fonts in a nuxt project, in nuxt-config |
| `ncss`  | link to css assets such as normalize                    |

### Extra (plaintext)

| Snippet     | Purpose                 |
| ----------- | ----------------------- |
| `gitignore` | .gitignore file presets |

## Contributing

This is an open source project open to anyone. Contributions are welcome [github](https://github.com/sdras/vue-vscode-snippets)
