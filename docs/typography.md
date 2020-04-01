---
id: typography
title: Typography
sidebar_label: Typography
---

This component help to display text inside the app uniformly. As we follow the material design guide for this app, we have defined a style accordingly and use this component to apply it. When we will want to use another design system typography principle, the transition we will easy.


### Example

```jsx
import React from 'react'
import Typography from 'shared/components/Typography';
import { StyleSheet } from 'react-native'

const styles = StyleSheet.create({
    cta: {
      width: 228,
      color: "#FFFFFF",
      marginTop: 16 
    }
})

<Typography  variant="button">
    WITH OUR SHOES
</Typography>

<Typography  variant="h6">
    712
    <Typography  variant="h5">
        products
    </Typography>
</Typography>
```

# Reference

## Props

### `chilren`

The values should be one the values : 

JSX.Element | string | string[] | JSX.Element[] | React.ReactNode

| Type     | Required |
| -------- | -------- |
| function | Yes      |

---

### `style`

style to help apply some layout property to the button

| Type   | Required |
| ------ | -------- |
| string | false      |

---

### `theme`

Used to pass our theme property to a specific component. Here the Typography component

| Type   | Required |
| ------ | -------- |
| string | Yes    |

---

### `variant`

Use to apply a specific material design typography specification to a text.

**h1** | **h2** | **h3** | **h4** | **h5** | **h6** | **subtitle1** | **subtitle2** | **body1** | **body2** | **button** | **caption** | **overline**

| Type   | Required |
| ------ | -------- |
| string | Yes      |

---