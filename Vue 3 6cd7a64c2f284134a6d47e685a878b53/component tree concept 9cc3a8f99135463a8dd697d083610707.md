# component tree concept

![Untitled](component%20tree%20concept%209cc3a8f99135463a8dd697d083610707/Untitled.png)

![Untitled](component%20tree%20concept%209cc3a8f99135463a8dd697d083610707/Untitled%201.png)

![Untitled](component%20tree%20concept%209cc3a8f99135463a8dd697d083610707/Untitled%202.png)

![Untitled](component%20tree%20concept%209cc3a8f99135463a8dd697d083610707/Untitled%203.png)

[<script setup> | Vue.js](https://vuejs.org/api/sfc-script-setup.html#using-components)

basic component import

```
<template>
  <Header/>
</template>

<script setup>
import Header from "@/components/Header.vue"
</script>
```

![Untitled](component%20tree%20concept%209cc3a8f99135463a8dd697d083610707/Untitled%204.png)

multiple component import

```jsx
<template>
  <Header/>
  <Hero/>
  <Footer/>
</template>

<script setup>
import Header from "@/components/Header.vue"
import Hero from "@/components/Hero.vue"
import Footer from "@/components/Footer.vue"
</script>
```

![Untitled](component%20tree%20concept%209cc3a8f99135463a8dd697d083610707/Untitled%205.png)

![Untitled](component%20tree%20concept%209cc3a8f99135463a8dd697d083610707/Untitled%206.png)