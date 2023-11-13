# import component in a component

```jsx
<template>
    <h1 class="display-1"> Salamoon Alaikoom From Header </h1>
    <Navbar/>
</template>

<script setup>
import Navbar from "./Navbar.vue"
</script>
```

![Untitled](import%20component%20in%20a%20component%20c7643353e3604cf58882d24c10be6f26/Untitled.png)

![Untitled](import%20component%20in%20a%20component%20c7643353e3604cf58882d24c10be6f26/Untitled%201.png)

![Untitled](import%20component%20in%20a%20component%20c7643353e3604cf58882d24c10be6f26/Untitled%202.png)

![Untitled](import%20component%20in%20a%20component%20c7643353e3604cf58882d24c10be6f26/Untitled%203.png)

navbar vue

```jsx
<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dropdown
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" aria-disabled="true">Disabled</a>
        </li>
      </ul>
      <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>
</template>
```