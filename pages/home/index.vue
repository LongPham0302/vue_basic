<template>
  <div>
    <ul class="skip-links">
    <li>
      <a href="#main" ref="skipLink" class="skip-link">Skip to main content</a>
    </li>
  </ul>
  <MyComponent>
    <h1 id="main">Main content</h1>
    <template v-slot:icon>
        <h2>This is the icon</h2>
      </template>
      <template v-slot:content>
        <h2>This is the content</h2>
      </template>
  </MyComponent>
  </div>
</template>

<script>
import MyComponent from "../../components/MyComponent.vue";

export default {
  components: {
    MyComponent,
  },  
  data() {
    return {
      message: "Xin chào thế giới!",
    };
  },
};
</script>
