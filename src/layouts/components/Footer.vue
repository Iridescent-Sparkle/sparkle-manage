<template>
  <div class="d-flex align-center justify-space-between h-100">
    <!-- 👉 Footer: left content -->
    <span class="d-flex align-center">
      &copy;
      {{ new Date().getFullYear() }}
      Made With
      <VIcon
        icon="bx-heart"
        color="error"
        size="1.25rem"
        class="mx-1"
      />
      By <a
        href="https://themeselection.com"
        target="_blank"
        rel="noopener noreferrer"
        class="text-primary ms-1"
      >ThemeSelection</a>
    </span>
    <!-- 👉 Footer: right content -->
    <span class="d-md-flex text-primary d-none gap-x-4">
      <a
        href="https://themeselection.com/license/"
        target="noopener noreferrer"
      >License</a>
      <a
        href="https://themeselection.com/"
        target="noopener noreferrer"
      >More Themes</a>
      <a
        href="https://demos.themeselection.com/sneat-vuetify-vuejs-admin-template/documentation/"
        target="noopener noreferrer"
      >Documentation</a>
    </span>
  </div>
</template>
