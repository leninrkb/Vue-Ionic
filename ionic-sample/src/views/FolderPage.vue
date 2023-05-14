<script lang="ts" setup>
import { IonPage, IonHeader, IonContent, IonFooter, IonToolbar } from '@ionic/vue';
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
            <div class="shadow-md rounded-md w-fit">
              <button class="p-3 text-lg">
                Selecciona una cancion
              </button>
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
