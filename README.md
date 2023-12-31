# React Lite UI Components

React Lite UI Components is a lightweight React.js library that offers simple and minimalist components with minimal or no styles. The library is designed to be easy to use and aims to provide a hassle-free development experience.

**This is still WIP, please do not use for now**

## Features

- Lightweight and minimalistic React components
- No or minimal styles to allow for easy customization
- Easy integration into existing React projects
- Straightforward API for quick implementation

## Installation

You can install React Lite UI Components using npm or yarn. Run the following command in your project directory:

```bash
npm install react-lite-ui-components
```

or

```bash
yarn add react-lite-ui-components
```

## Usage

To use React UI Lite Components, import the desired component(s) and include them in your React components.

```jsx
import React from 'react';
import { Button, Input } from 'react-lite-ui-components';

function App() {
  return (
    <div>
      <Button onClick={() => console.log('Button clicked!')}>
        Click Me
      </Button>

      <Input type="text" placeholder="Enter your name" />
    </div>
  );
}

export default App;
```

## Documentation

For detailed documentation on the available components and their props, please refer to the [React Lite UI Components documentation](https://github.com/WalTho/react-lite-ui-components/wiki).

## Contributing

Contributions to React Lite Components are welcome! If you encounter any bugs, have feature requests, or would like to contribute enhancements, please open an issue or submit a pull request on the [GitHub repository](https://github.com/WalTho/react-lite-ui-components/issues).

## License

React Lite UI Components is released under the [MIT License](https://opensource.org/licenses/MIT).
