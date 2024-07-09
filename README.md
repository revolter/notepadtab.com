# Notepad Tab

A simple, secure and private note taking tool.

The idea of encoding and persisting the content in the URL was inspired by
https://mermaid.live.

## Installation

1. Install `Ruby` by following the instructions from
   https://www.ruby-lang.org/en/documentation/installation/.
2. Install the `Ruby` dependencies by running
   ```sh
   bundle install
   ```
3. Install `Node.js` by following the instructions from
   https://docs.npmjs.com/downloading-and-installing-node-js-and-npm.
4. Install the `Node.js` dependencies by running
   ```sh
   npm install
   ```

## Configuration

### Favicon

- Check if RealFaviconGenerator
  [got updated](https://realfavicongenerator.net/change_log) by running
  ```sh
  npm run check-favicon-update
  ```
- If you update [the source SVG](sources/favicon/favicon.svg), or if
  RealFaviconGenerator gets updated, generate the favicon assets by running
  ```sh
  npm run generate-favicon
  ```

## Usage

```sh
npm run serve
```

## License

[GPL](LICENSE.md)
