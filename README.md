# Nuxt Ant Tailwind

> Nuxt Ant Tailwind is an experimental Nuxt project that uses Ant Design components for structure and Tailwindcss for style.

## How to overwrite Ant Design Vue component styles

Navigate to an Ant Design Component's CSS file by navigating this path.
`node_modules/ant-design-vue/lib/[component]/style/index.css`

For instance, to get to the Button Component's CSS file, navigate to.
`node_modules/ant-design-vue/lib/button/style/index.css`

Copy the contents of the `index.css` file to a new file in the `assets/css/components` directory.
In this file you can use Tailwind's `@apply` syntax to overwrite specific Ant Design Vue Component styles.

```
.ant-btn {
  @apply bg-blue-600;
}
```


Once you are finished with that, `@import` your new file into the `tailwind.css` file located in the `assets/css` directory.
```
@import './components/button.css';
```