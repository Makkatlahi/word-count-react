# Word Count React

A simple React app that counts words and characters in your text, and shows how many characters you have left for Facebook and Instagram posts.

## Features

- Live word and character count as you type
- Shows remaining characters for Facebook and Instagram posts
- Input validation with warnings for disallowed characters

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/YOUR-USERNAME/word-count-react.git
   cd word-count-react
   ```

2. Install dependencies:
   ```sh
   npm install
   # or
   yarn install
   ```

### Running the App

Start the development server:

```sh
npm run dev
# or
yarn dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the app.

## Project Structure

```
src/
  components/
    Container.jsx
    Stats.jsx
    Textarea.jsx
    Warning.jsx
  lib/
    constants.js
  App.jsx
  main.jsx
```

## Customization

- Update character limits in `src/lib/constants.js` as needed.
- Modify validation logic in `Textarea.jsx` to change input restrictions.

## License

MIT
