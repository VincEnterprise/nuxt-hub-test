<script setup lang="ts">
const items = [
  {
    label: 'Ingredients',
    icon: 'i-heroicons-information-circle',
    defaultOpen: true,
    content:
      'Ingredients: water, vegetables 20% (pepper 6.4% (red, green), carrot 6.1%, onion 4.3%, celery 1.8%, water chestnut 1.8%), tomato puree 14%, pineapple 11 %, sugar, modified corn starch, pineapple juice, vinegar, salt, thickener: xanthan gum, natural flavors, spices, acid: citric acid.',
  },
  // {
  //   label: 'Installation',
  //   icon: 'i-heroicons-arrow-down-tray',
  //   disabled: true,
  //   content:
  //     'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed neque elit, tristique placerat feugiat ac, facilisis vitae arcu. Proin eget egestas augue. Praesent ut sem nec arcu pellentesque aliquet. Duis dapibus diam vel metus tempus vulputate.',
  // },
  // {
  //   label: 'Theming',
  //   icon: 'i-heroicons-eye-dropper',
  //   content:
  //     'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed neque elit, tristique placerat feugiat ac, facilisis vitae arcu. Proin eget egestas augue. Praesent ut sem nec arcu pellentesque aliquet. Duis dapibus diam vel metus tempus vulputate.',
  // },
  // {
  //   label: 'Layouts',
  //   icon: 'i-heroicons-rectangle-group',
  //   content:
  //     'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed neque elit, tristique placerat feugiat ac, facilisis vitae arcu. Proin eget egestas augue. Praesent ut sem nec arcu pellentesque aliquet. Duis dapibus diam vel metus tempus vulputate.',
  // },
  // {
  //   label: 'Components',
  //   icon: 'i-heroicons-square-3-stack-3d',
  //   content:
  //     'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed neque elit, tristique placerat feugiat ac, facilisis vitae arcu. Proin eget egestas augue. Praesent ut sem nec arcu pellentesque aliquet. Duis dapibus diam vel metus tempus vulputate.',
  // },
  // {
  //   label: 'Utilities',
  //   icon: 'i-heroicons-wrench-screwdriver',
  //   content:
  //     'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed neque elit, tristique placerat feugiat ac, facilisis vitae arcu. Proin eget egestas augue. Praesent ut sem nec arcu pellentesque aliquet. Duis dapibus diam vel metus tempus vulputate.',
  // },
]
</script>

<template>
  <UAccordion
    color="gray"
    variant="soft"
    size="md"
    :items="items"
  />
</template>
