<template>
  <div id="app" style="text-align: center; padding-top: 40px; font-family: sans-serif; color: green;">
    <h1>Как работают слоты  в вью</h1>


    <BaseAlert>
      Это первое уведомление, здесь просто текст. 
    </BaseAlert>

    
    <BaseAlert>
      <b>Внимание!</b> Это очень важное жирное сообщение. 
    </BaseAlert>

    
    <BaseAlert>
      Что-то пошло не так. Возможно есть ошибка <a href="#">здесь</a>.
    </BaseAlert>
  </div>
</template>

<script setup>
import BaseAlert from './components/BaseAlert.vue'
</script>