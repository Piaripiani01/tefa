<template>
    <div class="container-fluid">
        <div class="row ny-5">
            <div class="col-lg-6">
            <nuxt-link to="/pengunjung/tambah">
                <div class="card bg-pengunjung rounded-5">
                    <div class="card-body">
                        <h2>pengunjung</h2>
                    </div>
                </div>
            </nuxt-link>
            </div>

            <div class="col-lg-6">
                <nuxt-link to="/buku">
                <div class="card bg-buku rounded-5">
                    <div class="card-body">
                        <h2>card buku</h2>
                    </div>
                </div>
                </nuxt-link>
            </div>
        </div>
        <h2>Statistik</h2>
        <div class="row my-5">
            <div class="col-lg-6">
                <nuxt-link to="/pengunjung/index.vue">
                <div class="card pengunjung rounded-5">
                    <div class="card-body">
                        <h2>0 Pengunjung</h2>
                    </div>
                </div>
                </nuxt-link>
            </div>

            <div class="col-lg-6">
                <nuxt-link to="/buku">
                <div class="card buku rounded-5">
                    <div class="card-body">
                        <h2>50 Buku</h2>
                    </div>
                </div>
                </nuxt-link>
            </div>
        </div>
    </div>
</template>

<style scoped>
.card {
    height: 250px;
    box-shadow: 1px 1px 10px hsl(0, 0%, 100%)
}
.card.bg-pengunjung {
    background-image: url('../assets/img/pengunjung.jpeg');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
}
.card.bg-buku {
    background: url('../assets/img/cari buku.jpg') no-repeat center center;
    background-size: cover;
}

.pengunjung {
    background-color: #89B6D6;
}
.buku {
    background-color: #89B6D6;
}

</style>
