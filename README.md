# Image search app

simple image search app with react js  
used create-react-app base setting  
(didn't consider any transfiling and bundling)

### [Demo App](https://search-image-mindflip.netlify.app/)

## What I learned

I learned some react systems and axios http client with this project

### React component

Components are separated as function module  
Simply separated 3 components (SearchBar, ImageList, ImageCard)  
Used callback function to pass data from child to parent component

### binding

If eventhandler has a `this` keyword, this point the `DOM` where handler attached  
To point `this` to the instance, arrow function is needed

### ref

Keyword `ref` is used for controling sepcific DOM  
Get a image height using ref to adjust image size

### axios

Used to request images from unsplash  
Can be modulized by axios.create function
