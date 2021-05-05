# 🥞 BobaSwap UIkit

[![Version](https://img.shields.io/npm/v/@bobaswap-libs/uikit)](https://www.npmjs.com/package/@bobaswap-libs/uikit) [![Size](https://img.shields.io/bundlephobia/min/@bobaswap-libs/uikit)](https://www.npmjs.com/package/@bobaswap-libs/uikit)

BobaSwap UIkit is a set of React components and hooks used to build pages on BobaSwap's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @bobaswap-libs/uikit`

## Setup

### Theme

Before using bobaSwap UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@bobaswap-libs/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@bobaswap-libs/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [Storybook documentation](https://bobateaswap.github.io/bobaswap-uikit/)
