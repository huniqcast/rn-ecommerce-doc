---
id: button
title: Button
sidebar_label: Button
---

This component is used to handle all the press action of user navigating through this application. 

### Example

```jsx
import React from 'react'
import Typography from 'shared/components/Typography';
import Button from 'shared/components/Button';
import { StyleSheet } from 'react-native'

const styles = StyleSheet.create({
    cta: {
      width: 228,
      color: "#FFFFFF",
      marginTop: 16 
    }
})

<Button variant="translucide" onPress={...} style={styles.cta}>
    <Typography  variant="button">
        WITH OUR SHOES
    </Typography>
</Button>

```

# Reference

## Props

### `onPress`

Handler to be called when the user taps the button

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

### `variant`

Use to apply a specific design theme to a button. The values should be one the values : 

translucide | primary | secondary

| Type   | Required |
| ------ | -------- |
| string | Yes      |

---