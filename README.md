# vue-title
=
a Vue(2.x) plugin with a custom directive v-title

npm install 'bs-vue-title'

## install
---
import Vue from 'vue'
import VueTitle from 'bs-vue-title'

Vue.use(VueTitle)

## usage
---
<div v-title >hello world</div>

<div v-title="'hi bsrli'" >hello world</div>

<div v-title.ellip >there is a long text which overflow from the element.</div>
