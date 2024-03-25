<template>
  <div class="container-fluid">
    <div class="row my-5">
      <div class="col-lg-6">
        <nuxt-link to="../Pengunjung/tambah">
          <div class="card bg-Pengunjung rounded-5">
            <div class="card-body">
              <h2>Pengunjung</h2>
            </div>
          </div>
        </nuxt-link>
      </div>

      <div class="col-lg-6">
        <nuxt-link to="../Buku">
          <div class="card bg-Buku rounded-5">
            <div class="card-body">
              <h2>Cari Buku</h2>
            </div>
          </div>
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<style scoped>
.card {
    height : 250px;
    box-shadow: 1px 1px 10px #424242;
}
.card.bg-Pengunjung {
    background-image: url('../assets/img/bg-home-kunjungan.jpeg');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
}
.card.bg-Buku {
    background: url('../assets/img/bg-home-cari-buku.jpg') no-repeat center center;
    background-size: cover;
}
</style>