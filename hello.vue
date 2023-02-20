<template>
  <FDraggable>
    <template #="{ item, index }">
      <div class="sort-item">
        {{ item }}
      </div>
    </template>
  </FDraggable>
</template>
