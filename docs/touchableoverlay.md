---
id: touchableoverlay
title: TouchableOverlay
sidebar_label: TouchableOverlay
---

This component is used to represent a whole area on which user can tap to and navigate to appropriate screen describing by the **displayed title** and the **background**

## Example

```jsx
import React from 'react'
import { StyleSheet } from 'react-native'
import HeroArea from './components/TouchableOverlay'

const style = StyleSheet.create({
  contentWrapper: {
    flex: 1,
  },
})

<TouchableOverlay
    action={...}
    title={...}
    background={require('../assets/images/home/sport-2245029_1920.png')}
    style={style.contentWrapper}
/>
```

# Reference

## Props


### `action`

Handler to be called when the user taps anywhere on the component

| Type     | Required |
| -------- | -------- |
| function | Yes      |

---

### `background`

Background image use to enhance the message display to user.

| Type     | Required |
| -------- | -------- |
| string   | Yes      |

---

### `title`

Component title

| Type   | Required |
| ------ | -------- |
| string | Yes      |

---

### `style`

Help to apply some layout property to the component

| Type   | Required |
| ------ | -------- |
| string | false      |

---