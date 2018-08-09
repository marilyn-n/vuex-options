# Options of Vuex Store


Vuex is a state management (pattern + library) for Vue.js applications. Vuex it serves as a centralized store for all the components in an application.

## State

Its the data in its initial/natural state

## Mutations

Mutations are used to change the state in  the Vuex store. The only way to actually change state is by committing a mutation. 

- Execute mutations with commit
```
commit('Products')
```

## Actions

- Dispatch is used for calling actions
```
store.dispatch('setMyAction') 

```
-Actions are usually asynchronous


## Getters

## Modules

## Store access from all Components

