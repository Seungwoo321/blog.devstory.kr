---
title: Vue-Datamaps
author: Seungwoo Lee
tags: ["vue-datamaps", "vue", "datamaps"]
date: 2019-12-15
description: It is a Vue port of the javascript-based DataMaps
---

# Vue Datamaps

[![npm](https://flat.badgen.net/npm/v/vue-datamaps)](https://npmjs.com/package/vue-datamaps)
[![npm](https://flat.badgen.net/npm/dt/vue-datamaps)](https://npmjs.com/package/vue-datamaps)

It is a Vue port of the jQuery-based [DataMaps](https://datamaps.github.io/)

## Installation
```shall
$ npm install -D vue-datamaps
```

## Usage
### Global Component
main.js
```js
import Vue from 'vue'
import VueDatamaps from 'vue-datamaps'

Vue.use(VueDatamaps)
```

### Component style
__app.vue__

```html
<template>
    <div id="app">
        <vue-datamaps></vue-datamaps>
    </div>
</template>

<script>
import { VueDatamaps } from 'vue-datamaps'

</script>

<style>

</style>
```




## Inspired
* [markmarkoh/datamaps](https://datamaps.github.io/) - original
* [btmills/react-datamaps](https://github.com/btmills/react-datamaps) - React-based datamaps library


## props

...


## License
MIT