### gudrunsara.github.io

# Coding standards 

## Comments 
**HTML Comments**  
Comments within HTML start with a capital letter and end with a semicolon.  
```
<!-- This is a comment: -->
```

**JavaScript Comments**  
Comments within JavaScript start with a capital letter and end with a dot.
```
// This is a comment.
```  

**Component Description Comments**  
Comments that describe the components functionality start with a slash and a star, and have the following structure.
```
/*
  Component: 
  Description:
  Props:
*/
```  

## Component structure
Each component is structured in the following way.
```
<template>
  <div>
  </div>
</template>

<script>
export default {
  name: "", 
  data() {

  },
  computed: {},
  created: {}, // To access reactive data and events, templates and Virtual DOM have not yet been mounted or rendered.
  mounted() {} // To access the reactive component, templates, and rendered DOM (via. this.$el).
  methods: {}
  Components: {}
  Props: {}
};
</script>

<style scoped>

</style>
``` 

## Name standards

**Component names**  
Component names must be multi-word names in Pascal case.
```
NavBar.vue
```  

**CSS class names**  
CSS class names are written in all lowercase letters with a dash between words.
```
css-class-name
```  

**Methods/functions names**  
Javascript function names are written in Camel case.
```
functionName()
```  

# What is it? 

# Installation & Set Up

# Build & Run

# Color codes 

# Forking the repo 

# Illustrations



