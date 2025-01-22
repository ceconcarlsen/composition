# composition
## VueJs

![image](https://github.com/user-attachments/assets/caad1d2d-0d17-41cc-90c9-32d72d2363cc)

Options API vs Composition API (vue3)

style scoped for this specific file

Create vue using Vite under the hood (hot-reloading, typescript and plugins)

Nuxt.js - SSR

<script src="https://unpkg.com/vue@3/dist/vue.global.js"></script> - easy to implement

## ```$ npm create vue@latest```

![image](https://github.com/user-attachments/assets/eb85f6cb-78cc-4281-bf37-3ab9c1c58dc4)

## Folder struct

![image](https://github.com/user-attachments/assets/0bf5ec5a-388c-414e-aead-ab72936d890a)

## Option API and v-if by props (kinda ugly ngl)

![image](https://github.com/user-attachments/assets/e7127f7a-2d7c-4174-89fe-4d81d7c82a39)

- v-if
- v-else
- v-else-if
- v-for
- v-bind
- v-on (events)
  - :click

![image](https://github.com/user-attachments/assets/bf6a636e-3b9b-445d-8e45-fc23e40c1704)


## Composition API

![image](https://github.com/user-attachments/assets/9c11dadf-836b-41f8-a3dc-b8a93a852eba)

Using ref to create reactivity (just like use state)
  - it needs to use status.`value` instead of `this`.status

So Composition API relies on the ref "hook" and .value atribute to work like Option API 

## Long version
![image](https://github.com/user-attachments/assets/43e324ad-4134-423a-9812-7b39542aad0b)

## Cleaner version
![image](https://github.com/user-attachments/assets/8217807c-a90f-4b96-8a38-0ce98c33ac78)

## LifeCycle
![image](https://github.com/user-attachments/assets/162d2bfd-a795-40db-ba77-98f41dc4b2ca)

