<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import IconTooling from '@/components/icons/IconTooling.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading><h4 class="heading">Criar nova lista</h4></template>
    <span class="subtitle">
      Crie suas listas personalizadas
      <a href="https://vuejs.org/" target="_blank" rel="noopener">aqui</a>
    </span>
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading><h4 class="heading">Criar nova Tier List</h4></template>
    <span class="subtitle"
      >Crie seus rankings personalizados
      <a href="https://vuejs.org/" target="_blank" rel="noopener">aqui</a>
    </span>
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <IconTooling />
    </template>
    <template #heading><h4 class="heading">Frases Personalizadas</h4></template>
    <span class="subtitle">Crie suas frases ou citações personalizadas</span>
    <a href="https://vuejs.org/" target="_blank" rel="noopener">aqui</a>
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading><h4 class="heading">Novo Certificado</h4></template>
    <span class="subtitle"
      >Crie suas listas personalizadas
      <a href="https://vuejs.org/" target="_blank" rel="noopener">aqui</a>
    </span>
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading><h4 class="heading">Novo Contrato</h4></template>
    <span class="subtitle"
      >Crie contratos personalizados
      <a href="https://vuejs.org/" target="_blank" rel="noopener">aqui</a>
    </span>
  </WelcomeItem>
</template>
<style lang="scss" scoped>
.subtitle {
  color: #181818;
}
.heading {
  color: #181818;
  font-weight: 500;
}
</style>
