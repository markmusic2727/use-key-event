# `useKeyEvent`

![CI Status](https://github.com/webmail/use-last-fm/workflows/CI/badge.svg)

⌨️ A lightweight, zero-dependency React hook for detecting dynamic keyboard events.

## Installation

```bash
yarn add use-key-event
# or
npm i use-key-event
```

## Usage

**Example:**

```tsx
import useKeyEvent from "use-key-event";

const Home = () => {
  useKeyEvent("Enter", handleEvent);

  const handleEvent = () => {
    console.log("The enter key has been pressed.");
  };

  return (
    <p>
      Press the enter key and check your console!
    </p>
  );
};
```
## Contributing

PR's, issues, and contributions are welcome!

Created and maintained with ❤️ by [**@FilippoFonseca**](https://www.twitter.com/FilippoFonseca).

