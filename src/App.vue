<script setup>
import "bootstrap/dist/css/bootstrap.min.css"
import "bootstrap"
import TargetsSteps from './components/TargetsSteps.vue'
import MainTargets from "./components/MainTargets.vue"
</script>

<template>
  <header>
    <div class="wrapper">
    </div>
  </header>

  <main>
    <div class="container">
      <div class="row">
        <h2 class="text-center mt-2">Your Targets</h2>
      </div>
      <div class="row">
        <div class="col-md-8">
          <targets-steps></targets-steps>
        </div>
        <div class="col-md-4">
          <main-targets></main-targets>
        </div>
      </div>
    </div>
  </main>
</template>
