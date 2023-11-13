# First Vue 3 Component

![Untitled](First%20Vue%203%20Component%20f5b951f6fe624c679e628270ce10e49a/Untitled.png)

1st Portion of a view component

```jsx
<template>
  <h1> Salamoon Alaikoom </h1>
</template>
```

![Untitled](First%20Vue%203%20Component%20f5b951f6fe624c679e628270ce10e49a/Untitled%201.png)

![Untitled](First%20Vue%203%20Component%20f5b951f6fe624c679e628270ce10e49a/Untitled%202.png)

2nd Portion of a view component is script with setup script setup

```jsx
<script setup>

</script>
```

![Untitled](First%20Vue%203%20Component%20f5b951f6fe624c679e628270ce10e49a/Untitled%203.png)

![Untitled](First%20Vue%203%20Component%20f5b951f6fe624c679e628270ce10e49a/Untitled%204.png)

![Untitled](First%20Vue%203%20Component%20f5b951f6fe624c679e628270ce10e49a/Untitled%205.png)

```jsx
<template>
  <h1> {{ salam }} </h1>
</template>

<script setup>
let salam = "Salamoon Alaikoom"

</script>
```

![Untitled](First%20Vue%203%20Component%20f5b951f6fe624c679e628270ce10e49a/Untitled%206.png)

![Untitled](First%20Vue%203%20Component%20f5b951f6fe624c679e628270ce10e49a/Untitled%207.png)

this kind of syntax style called sfc

[SFC Syntax Specification | Vue.js](https://vuejs.org/api/sfc-spec.html)

![Untitled](First%20Vue%203%20Component%20f5b951f6fe624c679e628270ce10e49a/Untitled%208.png)

![Untitled](First%20Vue%203%20Component%20f5b951f6fe624c679e628270ce10e49a/Untitled%209.png)

```jsx
<template>
  <h1> {{ salam }} {{ num1 + num2 }} </h1>
</template>

<script setup>
let salam = "Salamoon Alaikoom"
let num1 = 1
let num2 = 2

</script>
```

add two number and show it with string

![Untitled](First%20Vue%203%20Component%20f5b951f6fe624c679e628270ce10e49a/Untitled%2010.png)

![Untitled](First%20Vue%203%20Component%20f5b951f6fe624c679e628270ce10e49a/Untitled%2011.png)

style with scoped is useful when is need to use specifically for specific vue component 

[SFC CSS Features | Vue.js](https://vuejs.org/api/sfc-css-features.html)

```jsx
<style scoped>

</style>
```

```jsx
<template>
  <h1 id="salam"> {{ salam }} {{ num1 + num2 }} </h1>
</template>

<script setup>
let salam = "Salamoon Alaikoom"
let num1 = 1
let num2 = 2

</script>

<style scoped>
#salam {
  color:blue;
}

</style>
```

![Untitled](First%20Vue%203%20Component%20f5b951f6fe624c679e628270ce10e49a/Untitled%2012.png)

so overall summary is a basic vue js 3 component has 3 basic parts template script and style with sfc syntax

global scope for css has many option from main js file connect main.css main.css import base.css or other option is like this with sfc syntax

```jsx

<style>
#salam {
  color:blue;
}

</style>
```

- if we choose like this for a component where is no need for js or css just html then we write like this no problem

```jsx

<template>
  <h1>  salam </h1>
</template>
```

same for this if we don’t need css

```jsx
<template>
  <h1> {{ salam }} {{ num1 + num2 }} </h1>
</template>

<script setup>
let salam = "Salamoon Alaikoom"
let num1 = 1
let num2 = 2

</script>
```