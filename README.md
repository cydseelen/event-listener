
https://user-images.githubusercontent.com/68465807/116428053-d9305d00-a844-11eb-9592-a8e57ecf7588.mp4

## Background & Objectives

Yesterday, we covered how to select a DOM element, read information on it and update it (text, CSS, etc.). Today, we'll see how we can react to [DOM events](https://developer.mozilla.org/en-US/docs/Web/Events) to create interactive websites.

## Specs

Launch your local webserver with:

```bash
rake webpack
```

Open the `index.html` file. You can see we are using Bootstrap. Also, there is a big button in the `<body />`.

Your goal is to implement some JavaScript in the `lib/listener.js` file. **You should react to the click on the blue button.** When clicked, we want:

- The button to be disabled. This can be done by adding the `.disabled` class.
- The button text to change from "Click me!" to "Bingo!"
- Optional: the `sound.mp3` [plays in the Browser](https://stackoverflow.com/questions/9419263/playing-audio-with-javascript)

The sound might not work on some browsers running on **Ubuntu**. To fix it, just run:

```bash
sudo apt-get install ubuntu-restricted-extras 
```

There aren't any tests for this exercise, but we check your style! So run `rake`.
