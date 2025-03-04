# 📱 Setting up Expo App

### **1. Create a New Expo App**
```sh
npx create-expo-app@latest my-app
cd my-app
```

### **2. Start the Development Server**
```sh
npx expo start
```
This command starts Metro Bundler, which helps you run the app on an emulator or physical device.

### **3. Reset Project (If Needed)**
If you encounter errors or need a clean slate, reset the project:
```sh
npx expo run reset-project
```
---

---
## 🚀 **Developer Tools**
### **Using React/Redux/React-Native Snippets extension**
For faster coding, on VS code (ES7+ React/Redux/React-Native snippets by dsznajder). This allows auto-generating component templates with commands like on (tsx, jsx):
```sh
rnfes
``` 
```sh
import { StyleSheet, Text, View } from 'react-native'
import React from 'react'

const test = () => {
  return (
    <View>
      <Text>test</Text>
    </View>
  )
}

export default test

const styles = StyleSheet.create({})
```
