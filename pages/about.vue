<template>
  <section class="container">
    <div>
      <p>
        <button @click="$store.commit('increment')">{{ $store.state.counter }}</button><br>
      </p>
      <h1 class="title">
        {{ $store.state.counter }}
      </h1>
    </div>
    <nuxt-link to="/">Home</nuxt-link>
  </section>
</template>
