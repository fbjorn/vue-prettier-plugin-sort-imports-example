# vue-prettier-plugin-sort-imports-example

This repo is an example of this issue: https://github.com/trivago/prettier-plugin-sort-imports/issues/49

Steps to reproduce:

```shell
yarn install
```

```
> npx prettier test.ts

import Vue from 'vue';

import dayjs from 'dayjs';
import exampleLib from 'example-lib';

import TheNavBar from '@/components/TheNavBar';



> npx prettier Test.vue

<template>
    <div></div>
</template>

<script lang="ts">
import Vue from 'vue';
import dayjs from 'dayjs';
import exampleLib from 'example-lib';
import TheNavBar from '@/components/TheNavBar';
</script>
```
