# Sync Core UI Components

Welcome to the Sync Core UI Components library! This repository contains reusable UI components built for the Sync Core applications, designed to work seamlessly with React and Storybook.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Available Components](#available-components)

## Introduction

Sync Core UI Components is a collection of reusable UI components developed by Sync Core. These components are built with React and styled with Tailwind CSS, and they are intended to streamline the development process for Sync Core applications.

## Installation

To install the Sync Core UI Components library, use the following npm command:

```bash
npm install sync-core-ui-components
```

## Usage

To use a component from the Sync Core UI Components library, simply import it into your React project:

```jsx
import React from 'react';
import { ComponentName } from 'sync-core-ui-components';

const App = () => {
  return (
    <div>
      <ComponentName />
    </div>
  );
};

export default App;
```

Ensure you have Tailwind CSS set up in your project, as the components are styled using Tailwind CSS.

## Available Components

Here are some of the key components available in this library:

- **Button**: A customizable button component.
- **Modal**: A flexible modal component.
- **Dropdown**: A dropdown menu component.
- **Tooltip**: A tooltip component for providing additional information.
- **Card**: A card component for displaying content in a card layout.
- **Table**: A table component for displaying tabular data.

For a full list of components and detailed usage examples, please refer to our [Storybook documentation](https://sync-core.github.io/ui-component).

Happy coding!
