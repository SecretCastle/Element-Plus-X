<docs>
---
title: 基本使用
---

这是一个`button`按钮最基本的使用例子
</docs>

<script setup lang="ts">
function myClick() {
  console.log('myClick')
}
</script>

<template>
  <div style="display: flex;gap: 10px;">
    <Button @click="myClick">
      按钮1
    </Button>
    <Button type="primary" @click="myClick">
      按钮2
    </Button>
    <Button type="dashed">
      按钮3
    </Button>
  </div>
</template>
