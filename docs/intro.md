---
sidebar_position: 1

id: intro
title: Introduction
# slug: /
---

# Uncover UI for React Native

Welcome to the documentation for **@uncover-ui/react-native** — your go-to UI component library for React Native and Expo!

## About the Library

- **Name:** `@uncover-ui/react-native`  
- **Expo Version:** `@uncover-ui/expo`  
- **Version:** 1.2.76  
- **License:** MIT  
- **Author:** Uncover the Future  
- **Repository:** [GitHub Repository](https://github.com/uncoverthefuture-org/uncover-ui/tree/master/packages/react-native)

This library offers a seamless way to integrate prebuilt UI components, designed for performance and scalability.

---

## Getting Started

### Installation

For React Native CLI:

```bash
npm install @uncover-ui/react-native
# or
yarn add @uncover-ui/react-native

```

### For Expo Projects

Run the following command to add the Expo version:

```bash
npm install @uncover-ui/expo
# or
yarn add @uncover-ui/expo

```

## Basic Usage

Here’s an example of how to use one of the components from the library:

```tsx
import React from 'react';
import { PrimaryButon } from '@uncover-ui/react-native';

export default function App() {
  return (
    <PrimaryButon text="Click Me" onPress={() => alert('Button Pressed!')} />
  );
}
```