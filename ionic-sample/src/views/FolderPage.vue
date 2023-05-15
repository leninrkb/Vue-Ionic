<script lang="ts" setup>
import { IonPage, IonHeader, IonContent, IonFooter, IonToolbar, IonInput } from '@ionic/vue';
</script>
<template>
  <ion-page>

    <ion-header>
      <ion-toolbar>
        <ion-title>Editor de metadata</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content>
      <div class="container mx-auto p-3 font-sans">
        <h1 class="text-3xl">Editar cancion</h1>
        <div class="rounded-lg bg-gray-600 h-screen p-3">

          <div class="bg-teal-500 rounded-md w-fit">
            <button class="p-3 text-lg">
              Selecciona una cancion
            </button>
          </div><br>

          <div class="bg-slate-500 rounded-md p-3">
            <figure class="w-2/12 mx-auto">
              <figcaption>Cover</figcaption>
              <img class="rounded-md
              ring-2 ring-slate-400 ring-offset-2 ring-offset-slate-500
              aspect-square" src="https://picsum.photos/400/400" alt="imagen random">
            </figure>
            <br>

            <div class="p-1 bg-slate-400 rounded-md mx-auto w-1/2">
              <ion-input label="Titulo" :clear-input="true"></ion-input>
            </div>
          </div>
        </div>
      </div>
    </ion-content>

    <ion-footer>
      <div class="container mx-auto p-1 bg-gradient-to-br from-cyan-600 to-teal-600 font-mono">
        <div class="w-fit mx-auto">
          <h6 class="text-gray-800">created by leninrkb - 2023</h6>
        </div>
      </div>
    </ion-footer>
  </ion-page>
</template>
