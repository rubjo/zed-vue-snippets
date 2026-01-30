# Vue snippets for Zed

Based on the snippets from the [Vue 3 VS Code Snippets](https://marketplace.visualstudio.com/items?itemName=exer7um.vue-3-vscode-snippets) extension by ExEr7um.

## Snippets

### `.vue` files

| Snippet      | Purpose                                                               |
| ------------ | --------------------------------------------------------------------- |
| `vbase`      | Base for Vue 3 File with `<script setup>`, `TypeScript` and `SCSS`    |
| `vbase-sass` | Base for Vue 3 File with `<script setup>`, `TypeScript` and `SASS`    |
| `vbase-less` | Base for Vue 3 File with `<script setup>`, `TypeScript` and `LESS`    |
| `vbase-pcss` | Base for Vue 3 File with `<script setup>`, `TypeScript` and `PostCSS` |
| `vbase-css`  | Base for Vue 3 File with `<script setup>`, `TypeScript` and `CSS`     |
| `vbase-styl` | Base for Vue 3 File with `<script setup>`, `TypeScript` and `Stylus`  |
| `vbase-ns`   | Base for Vue 3 File with `<script setup>`, `TypeScript` and no style  |

### Template

| Snippet        | Purpose                                |
| -------------- | -------------------------------------- |
| `vfor`         | `v-for` statement                      |
| `vmodel`       | `v-model` directive                    |
| `von`          | `v-on` click handler                   |
| `vel-props`    | Component element with `props`         |
| `vslot-named`  | Named slot                             |
| `vimg`         | Image source binding                   |
| `vstyle`       | Inline style binding                   |
| `vstyle-obj`   | Inline style binding with objects      |
| `vclass`       | Class binding                          |
| `vclass-ter`   | Ternary class binding                  |
| `vtrans`       | Transition component                   |
| `vtrans-group` | Transition group component             |
| `vrlink`       | Router link                            |
| `vrlink-param` | Router link with param                 |
| `vsuspense`    | Suspense wrapper with fallback content |

### Script

| Snippet                     | Purpose                              |
| --------------------------- | ------------------------------------ |
| `vref`                      | Vue `ref`                            |
| `vref-typed`                | Vue `ref` with generic type argument |
| `vreactive`                 | Vue `reactive`                       |
| `vcomputed`                 | Vue `computed`                       |
| `vwatch`                    | Watcher                              |
| `vwatcheffect`              | Watch Effect                         |
| `vonmounted`                | onMounted hook                       |
| `vonbeforemount`            | onBeforeMount hook                   |
| `vonbeforeupdate`           | onBeforeUpdate hook                  |
| `vonupdated`                | onUpdated hook                       |
| `vonerrorcaptured`          | onErrorCaptured hook                 |
| `vonunmounted`              | onUnmounted hook                     |
| `vonbeforeunmount`          | onBeforeUnmount hook                 |
| `vdefineprops`              | Define props                         |
| `vdefineprops-withdefaults` | Define props with defaults           |
| `vdefineemits`              | Define emits                         |
| `vsingleemit`               | Single emit for defineEmits          |
| `vdefineslots`              | Define slots                         |
| `vsingleslot`               | Single slot for defineSlots          |
| `vdefineoptions`            | Define Options                       |
| `vdefinemodel`              | Define Model                         |
| `vdefineasynccomponent`     | Define async component               |

### `.ts / .js` files

| Snippet       | Purpose                |
| ------------- | ---------------------- |
| `vcomposable` | Generic Vue composable |

### CSS

| Snippet                          | Purpose                                      |
| -------------------------------- | -------------------------------------------- |
| `vcss-transition`                | Vue Transition styles                        |
| `vcss-transition-named`          | Vue Named Transition styles                  |
| `vcss-transition-tailwind`       | Vue Transition styles for Tailwind CSS       |
| `vcss-transition-named-tailwind` | Vue Named Transition styles for Tailwind CSS |
| `vcss-transition-group`          | Vue Transition Group styles                  |
| `vcss-transition-group-tailwind` | Vue Transition Group styles for Tailwind CSS |

### Vue Router

| Snippet              | Purpose                                         |
| -------------------- | ----------------------------------------------- |
| `vrouter`            | Vue Router base                                 |
| `vscrollbehavior`    | Vue Router `scrollBehavior`                     |
| `vbeforeeach`        | Vue Router global guards `beforeEach`           |
| `vbeforeresolve`     | Vue Router global guards `beforeResolve`        |
| `vaftereach`         | Vue Router global guards `afterEach`            |
| `vbeforeenter`       | Vue Router per-route guard `beforeEnter`        |
| `vbeforerouteenter`  | Vue Router component guards `beforeRouteEnter`  |
| `vbeforerouteupdate` | Vue Router component guards `beforeRouteUpdate` |
| `vbeforerouteleave`  | Vue Router component guards `beforeRouteLeave`  |
