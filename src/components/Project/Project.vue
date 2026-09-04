<script setup>
import projectMc from '@/assets/images/project/mc.png'
import projectDb from '@/assets/images/project/db.png'
import projectSpcm from '@/assets/images/project/spcm.png'
</script>

<template>
  <div class="row gx-5 justify-content-center">
    <div class="col-lg-11 col-xl-9 col-xxl-8">
      <!-- Project Card 1-->
      <div class="card overflow-hidden shadow rounded-4 border-0 mb-5">
        <div class="card-body p-0">
          <div class="row">
            <div class="col-md-6 p-5">
              <h2 class="fw-bolder">Machine Learning</h2>
              <p>Analisis sentimen opini publik terhadap UU TPKS menggunakan TF-IDF dan machine learning dengan akurasi terbaik 85,35% pada Random Forest dan SVM.</p>
              <div style="margin-bottom: 15px;">
                <a href="https://bit.ly/GoogleColabJurnal" class="text-gradient text-decoration-none" target="_blank">https://bit.ly/GoogleColabJurnal</a>
              </div>
              <div>
                <a href="https://bit.ly/DOIJurnalJAIC" class="text-gradient text-decoration-none" target="_blank">https://bit.ly/DOIJurnalJAIC</a>
              </div>
            
              </div>
            <div class="col-md-6" :style="{ backgroundImage: `url(${projectMc})`, backgroundSize: 'contain', backgroundRepeat: 'no-repeat', backgroundPosition: 'center center' }">
            </div>
          </div>
        </div>
      </div>

      <div class="card overflow-hidden shadow rounded-4 border-0 mb-5">
        <div class="card-body p-0">
          <div class="row">
            <div class="col-md-6 p-5">
              <h2 class="fw-bolder">Data Analytics Capstone Project</h2>
              <p>Menganalisis data penjualan Wonka Chocolate Factory untuk mengidentifikasi tren penjualan, performa produk, dan peluang peningkatan penjualan melalui data cleaning, visualization, dan data analysis.</p>
              <a href="https://bit.ly/CapstoneProjectDAReVou" class="text-gradient text-decoration-none" target="_blank">https://bit.ly/CapstoneProjectDAReVou</a>
            </div>
            <div class="col-md-6" :style="{ backgroundImage: `url(${projectDb})`, backgroundSize: 'contain', backgroundRepeat: 'no-repeat', backgroundPosition: 'center center' }">
            </div>
          </div>
        </div>
      </div>

      <!--      Project Card 2-->
      <div class="card overflow-hidden shadow rounded-4 border-0 mb-5">
        <div class="card-body p-0">
          <div class="row">
            <div class="col-md-6 p-5">
              <h2 class="fw-bolder">Analisis Faktor Risiko Penyakit Jantung</h2>
              <p>Menganalisis faktor risiko penyakit jantung menggunakan Python melalui EDA, visualisasi data, analisis korelasi Spearman, dan regresi linear untuk menemukan pola serta hubungan antar variabel.</p>
              <a href="https://bit.ly/GoogleColabAFRPJ" class="text-gradient text-decoration-none" target="_blank">https://bit.ly/GoogleColabAFRPJ</a>
            </div>
            <div class="col-md-6" :style="{ backgroundImage: `url(${projectSpcm})`, backgroundSize: 'contain', backgroundRepeat: 'no-repeat', backgroundPosition: 'center center' }">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>