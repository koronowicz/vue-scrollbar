# Vue Scrollbar

The Simplest Scroll Area Component with custom scrollbar for [Vue Js](http://vuejs.org/).

[DEMO](https://bosnaufal.github.io/vue-scrollbar)

## Install
You can import [vue-scrollbar.vue](./src/js/components/vue-scrollbar.vue) to your vue component file like [this](./src/js/components/app.js) and process it with your preprocessor.;


You can install it via NPM
```bash
npm install vue-scrollbar
```


## Usage
```html

<template>
  <vue-scrollbar classes="my-scrollbar">
    <div class="should-have-a-children scroll-me">
      <p>And Now</p>
      <p>You Can Put</p>
      <p>A Long Content Here</p>
    </div>
  </vue-scrollbar>
</template>

<script>

  // Don't forget to import the Scrollbar Sass
  require('../../sass/_Scrollbar.sass');

  import vueScrollbar from './vue-scrollbar.vue';

  export default {
    components: { vueScrollbar }
  };

</script>
```


## Props
##### clasess (String)
Just the ordinary class name for styling the wrapper. It's TOTALLY CUSTOMIZABLE!
```css
/*The Wrapper*/
.my-scrollbar{
  max-width: 500px;
  max-height: 450px;
}

/*The Content*/
.scroll-me{
  min-width: 750px;
}
```

## Thank You for Making this useful~

## Let's talk about some projects with me
Just Contact Me At:
- Email: [bosnaufalemail@gmail.com](mailto:bosnaufalemail@gmail.com)
- Skype Id: bosnaufal254
- twitter: [@BosNaufal](https://twitter.com/BosNaufal)

## License
[MIT](http://opensource.org/licenses/MIT)
Copyright (c) 2016 - forever Naufal Rabbani
