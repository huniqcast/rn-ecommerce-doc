---
id: heroarea
title: HeroArea
sidebar_label: HeroArea
---

This component is used to represent to hero area of this application. you can define your own background image, your own description and the call to action.

## Example

```jsx
import React from 'react'
import { StyleSheet } from 'react-native'
import HeroArea from './components/HeroArea'

const style = StyleSheet.create({
  contentWrapper: {
    flex: 1,
  },
})

<HeroArea
    description="BE FIT AND READY TO GO"
    action={...}
    background={require('../assets/images/home/fashionable-girl-leather-434375.png')}
    ctaTitle={...}
    style={style.contentWrapper}
/>
```

# Reference

## Props


### `action`

Handler to be called when the user taps the call to action

| Type     | Required |
| -------- | -------- |
| function | Yes      |

---

### `background`

Background image use to enhance the hero area.

| Type     | Required |
| -------- | -------- |
| string   | Yes      |

---

### `ctaTitle`

Title of the call to action button

| Type   | Required |
| ------ | -------- |
| string | Yes      |

---

### `description`

Describe the message display in the hero area

| Type     | Required |
| -------- | -------- |
| string   | Yes      |

---

### `style`

Help to apply some layout property to the component

| Type   | Required |
| ------ | -------- |
| string | false      |

---