# image-compression-before-upload

A native image resizing & compression tool for React Native (iOS & Android).

## Features

- Compress images before upload
- Resize images to desired dimensions
- Supports JPEG and PNG formats
- Works on both iOS and Android

[Here's the Complete Guide to Build a Fast Image Compression Tool in React Native.](https://www.sevensquaretech.com/build-react-native-image-compression-tool-with-github-code/)

## Installation

npm install image-compression-before-upload

or

yarn add image-compression-before-upload

## Peer Dependencies

- react >=16.8
- react-native >=0.59

## Usage

```js
import ImageCompressor from "image-compression-before-upload";

const compressImage = async () => {
  const result = await ImageCompressor.compress({
    uri: imageUri,
    quality: 0.7,
    maxWidth: 800,
    maxHeight: 800,
  });
  console.log(result);
};
```

## Options

- uri: Image file URI
- quality: Compression quality (0 to 1)
- maxWidth: Maximum width
- maxHeight: Maximum height

## Platform Support

- ✅ Android
- ✅ iOS
