<template>
  <!-- Hero -->
  <div class="hero-container">
    <div class="hero"></div>
    <div class="hero-stuff p-5">
      <h1 class="text-white font-weight-bold p-2">Daftar Indihome Makassar</h1>
      <h2 class="text-white font-weight-bold p-2">
        Layanan Online Pasang Baru Indihome Makassar
      </h2>
      <a class="btn-1"
        href="https://wa.me/628114449289?text=Saya%20tertarik%20berlangganan%20paket%20indihome...">Daftar IndiHome</a>
    </div>
  </div>
  <!-- About -->
  <About />

  <!-- navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
    <div class="container-fluid">
      <img :src="image" width="100" />
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" aria-current="page" href="#cara-daftar">Cara Daftar IndiHome</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <div class="d-flex justify-content-center mt-2">
    <div class="card" style="width: 1000px">
      <div class="card-body">
        <!-- content 1 -->
        <div class="d-grid gap-2">
          <h2 class="text-center">PAKET INDIHOME MAKASSAR</h2>
          <h4 class="text-center text-primary">PAKET 2P INTERNET PHONE</h4>
          <div class="d-flex justify-content-center">
            <img :src="b2" alt="Responsive image" class="img-fluid" width="500" />
          </div>
          <p class="text-danger">Paket 2P Internet + Phone 300 menit</p>
          <div>
            <ul class="text-primary">
              <li>Speed 30 Mbps = Rp. 315.000,-/Bulan</li>
              <li>Speed 50 Mbps = Rp. 445.000,-/Bulan</li>
              <li>Speed 100 Mbps = Rp. 795.000,-/Bulan</li>
            </ul>
          </div>

          <p class="text-left">keterangan :</p>
          <ul>
            <li>Bebas nelpon 100 menit Lokal/interlokal (Telpon Rumah)</li>
            <li>Bebas akses disney + hotstar</li>
          </ul>
          <a class="btn-1 btn-success mb-2"
            href="https://wa.me/628114449289?text=Saya%20tertarik%20berlangganan%20paket%20indihome...">Daftar IndiHome
            Sekarang
          </a>
        </div>

        <div class="d-grid gap-2">
          <h4 class="text-center text-primary">PAKET 2P INTERNET TV</h4>
          <div class="d-flex justify-content-center">
            <img :src="internetTV" alt="Responsive image" class="img-fluid" width="500" />
          </div>
          <p class="text-danger">Paket 2P Internet + Usee TV</p>
          <ul class="text-primary">
            <li>Speed 30 Mbps = Rp. 370.000,-/Bulan</li>
            <li>Speed 50 Mbps = Rp. 595.000,-/Bulan</li>
            <li>Speed 100 Mbps = Rp. 945.000,-/Bulan</li>
          </ul>
          <p class="text-left">keterangan :</p>
          <ul>
            <li>
              Usee TV New Basic terdiri dari 109 channels UseeTV (91 channels SD dan 18
              channels HD).
            </li>
            <li>Pilihan benefit Indihome Study / i-konser / Iflix.</li>
            <li>Harga berlaku untuk pelanggan baru mulai Oktober 2021.</li>
            <li>Harga di atas untuk pembayaran setiap bulan.</li>
            <li>
              Harga paket sudah termasuk Hybrid Box IndiHome dan ONT selama berlangganan.
            </li>
            <li>Harga belum termasuk PPN.</li>
          </ul>
          <a class="btn-1 btn-success"
            href="https://wa.me/628114449289?text=Saya%20tertarik%20berlangganan%20paket%20indihome...">Daftar IndiHome
            Sekarang
          </a>
        </div>

        <div class="d-grid gap-2">
          <h4 class="text-center text-primary">PAKET 3P INTERNET PHONE TV</h4>
          <div class="d-flex justify-content-center">
            <img :src='paket3p' alt="Responsive image" class="img-fluid" width="500" />
          </div>
          <p class="text-danger">Paket 3P Internet + Phone + Usee TV</p>
          <ul class="text-primary">
            <li>50 Mbps = Rp. 615.000,-/Bulan</li>
            <li>100 Mbps = Rp. 965.000,-/Bulan</li>
          </ul>
          <p class="text-left">keterangan :</p>
          <ul>
            <li>Bebas nelpon 100 menit Lokal/interlokal (Telpon Rumah)</li>
            <li>Bebas akses disney + hotstar</li>
            <li>Bebas akses Netflix</li>

          </ul>
          <a class="btn-1 btn-success"
            href="https://wa.me/628114449289?text=Saya%20tertarik%20berlangganan%20paket%20indihome...">Daftar IndiHome
            Sekarang
          </a>
        </div>
        <div class="d-grid gap-2">
          <h4 class="text-center text-primary">PAKET INTERNET GAMER</h4>
          <div class="d-flex justify-content-center">
            <img :src="game" alt="Responsive image" class="img-fluid" width="500" />
          </div>
          <p class="text-danger">
            Paket Internet Gamer (Internet + Phone + TV + Layanan Games)
          </p>
          <ul class="text-primary">
            <li>Speed 30 Mbps = Rp. 375.000,-/Bulan</li>
            <li>Speed 50 Mbps = Rp. 545.000,-/Bulan</li>
            <li>Speed 100 Mbps = Rp. 895.000,-/Bulan</li>
          </ul>
          <p class="text-left">keterangan :</p>
          <ul>
            <li>Gratis 300 menit nelpon lokal/interlokal.</li>
            <li>
              Usee TV New Basic terdiri dari 109 channels UseeTV (91 channels SD dan 18
              channels HD).
            </li>
            <li>Gratis layanan games yang bekerja sama dengan Indihome.</li>
            <li>Harga di atas untuk pembayaran setiap bulan.</li>
            <li>Harga berlaku untuk pelanggan baru mulai Oktober 2021.</li>
            <li>Harga sudah termasuk Hybrid Box IndiHome dan ONT selama berlangganan.</li>
            <li>Harga belum termasuk PPN.</li>
          </ul>
          <p>
            IndiHome Paket Gamer merupakan layanan untuk Anda para pecinta game online.
            Dapatkan berbagai benefit seperti exclusive item, in game currency, double
            experience/drop rate dan masih banyak lagi yang diberikan oleh game publisher.
          </p>
          <a class="btn-1 btn-success"
            href="https://wa.me/628114449289?text=Saya%20tertarik%20berlangganan%20paket%20indihome...">Daftar IndiHome
            Sekarang
          </a>
          <div id="cara-daftar">
            <h4 class="mt-6">Cara Daftar IndiHome:</h4>
            <p class="mb-5">
              Cara Daftar Indihome Makassar cukup klik tombol Daftar Indihome
              Sekarang(Whatsapp) dan otomatis bisa melakukan chat dengan Costumer Service
              Kami. Anda bisa melengkapi data dan mengirimnya pula disana.
            </p>
          </div>

          <h4>
            Syarat dan ketentuan berlangganan paket indihome (Dengan akses disney +
            hotstar)
          </h4>
          <ol>
            <li>
              Paket indihome(Dengan akses disney + hotstar) ini tersedia untuk pelanggan
              baru indihome dan pelanggan lama inidihome yg ingin melakukan upgrade ke
              paket baru ini. Masa berlangganan minimal 12 bulan.
            </li>
            <li>
              Untuk pilihan paket 3p (Internet + TV + Telpon). Bonus Add-On Minipack
              indimovie 2, CATCHPLAY, iflix, MOLA dan vidio hanya berlaku untuk pelanggan
              yang berlangganan dengan kecepatan minimal 50mbps.
            </li>
            <li>
              Untuk menonton berbagai tayangan di disney + hotstar. Anda dapat mengunduh
              aplikan disney + hotstar di play store (Android) atau App Store (ios), lalu
              masuk menggunakan nomor seluler yang terdaftar di layanan indihome melalui
              aplikasi. Anda juga dapat mengunjungi situs web disney + hotstar di
              http://www.hotstar.com melelui browser Anda Anda wajib menerima ketentuan
              penggunaan dan kebijakan privasi disney + hotstar sebagai syarat untuk
              mengakses disney + hotstar.
            </li>
            <li>
              Pelanggan bisa mendapolkan bonus 53 channel Minlpack Upgrade Essential
              selarno 3 bulan dan bonus coshback soldo UnkAja apso.000 untuk blaya
              pernasangan baru berlaku unluk pelanggan yang berlangganan Paket 3P
              (Internet • TV • Telepon) melalui indihome.co.ld. aplikasl myIncliHome
              aplikosi. Tokopedia. Shopee. Bukalapok. Kios mylndiHome Klosk. alau Sobat
              IndiHome App. sebagaimana berlaku
            </li>
            <li>Harga belum termasuk PPN 1O%</li>
            <li>Syarat dan ketentuan rinci berlaku.</li>
          </ol>
        </div>
        <!-- footer fixed -->
        <div class="fixed-bottom d-grid gap-2 d-lg-none d-md-none">
          <a class="btn-1 btn-success"
            href="https://wa.me/628114449289?text=Saya%20tertarik%20berlangganan%20paket%20indihome...">Daftar IndiHome
            Sekarang
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <Footer class="mt-4" />
</template>

<script>
import image from "../img/logo.png";
import brosur from "../img/Brosur.png";
import b2 from "../img/paket2p.jpg";
import paket3p from "../img/paket3p.jpg";
import game from "../img/gamer.jpg";
import internetTV from "../img/inettv.jpg";

import Footer from "../components/footer.vue";
import About from "../components/about.vue";

export default {
  components: {
    Footer,
    About,
  },
  data: function () {
    return {
      image: image,
      brosur: brosur,
      b2: b2,
      game: game,
      internetTV: internetTV,
      paket3p: paket3p,
    };
  },
};
</script>

<style scope>
div .mt-6 {
  margin-top: 5rem;
}

/* hero */

.hero-container {
  height: 100vh;
  width: 100%;
  overflow: hidden;
  position: relative;
  margin-bottom: 20px;
}

.hero {
  background: url("../img/hero.jpg") no-repeat center center;
  background-size: cover;
  height: 100%;
  width: 100%;
  padding: 40px;
  transition: transform 2s;
  filter: brightness(50%);
}

.hero:hover {
  transform: scale(1.15);
}

.hero-stuff {
  margin-top: 200px !important;
  position: absolute;
  top: 40px;
  left: 40px;
}

h1 {
  font-size: 55px;
  font-weight: 700;
  font-family: sans-serif;
  color: #fff;
}

a.btn-1 {
  text-decoration: none;
  cursor: pointer;
  background-image: linear-gradient(to right, #ff512f 0%, #f09819 51%, #ff512f 100%);
}

a.btn-1 {
  display: inline-block;
  font-family: sans-serif;
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 1.5px;
  padding: 11px 30px;

  margin: 10px;
  text-align: center;
  text-transform: uppercase;
  transition: 0.5s;
  background-size: 200% auto;
  color: white;
  box-shadow: 0 0 20px #eee;
  border-radius: 10px;
}

a.btn-1:hover {
  background-position: right center; /* change the direction of the change here */
  color: #fff;
  text-decoration: none;
}

p {
  font-family: sans-serif;
}

/* Responsive */

@media screen and (max-width: 600px) {
  .hero-stuff {
    margin-top: 100px !important;
    display: flex;
    flex-direction: column;
    width: 80%;
    margin-top: 1.2rem;
    padding: 5px !important;
    /* background-color: olive; */
  }

  .hero-stuff h1 {
    /* text-align: center; */
    font-size: 2.9rem;
  }

  .hero-stuff h1,
  h2 {
    text-align: center;
  }
}

@media screen and (max-width: 770px) {
  .hero-stuff {
    margin-top: 100px !important;
  }
}
</style>
