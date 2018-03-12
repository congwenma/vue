# Vue Constructor

Stopped at `initRender`

```js
Options = {
  _isComponent: "<Bool>", // optimize internal component instantiation since internal component options dont need special treatment
}

Attributes =  {
  _uid: uid++,
  _isVue: true, // mark as vue component


  // set by lifecycle
  $parent: parent_component,
  $root: parent_component.$root,
  $children: [],


  $refs: [],
  _watcher: null,
  _inactive: null,
  _directInactive: false,
  _isMounted: false,
  _isDestroyed: false,
  _isBeingDestroyed: false,
}

```