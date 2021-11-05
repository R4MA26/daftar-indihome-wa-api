<template>
  <!-- navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
    <div class="container-fluid">
      <img :src="image" width="100" />
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link" aria-current="page" href="#">Cara Daftar IndiHome</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Tentang Kami</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <div class="d-flex justify-content-center mt-6">
    <div class="card" style="width: 1000px">
      <div class="card-body">
        <!-- content 1 -->
        <h1 class="text-center text-danger p-2">Daftar Indihome Makassar</h1>
        <h2 class="text-center font-weight-bold p-2">
          Layanan Online Pasang Baru Indihome Makassar
        </h2>

        <div class="p-3 d-grid gap-2">
          <div>
            <p style="text-align: justify">
              Silahkan pilih paket Internet Indihome sesuai dengan kebutuhan Anda. Apabila
              Anda ingin daftar Indihome atau mempunyai pertanyaan seputar layanan
              Indihome Anda bisa langsung live chat via Whatsapp ke Marketing kami. Kami
              siap membantu Anda sampai dengan terpasanganya layanan Indihome fiber di
              rumah, ruko, kost-kostan, warkop, kantor maupun tempat usaha Anda. Kami
              melayani pemasangan Indihome untuk seluruh wilayah Makassar, Gowa, Maros dan
              sekitarnya.
            </p>
            <p style="text-align: justify">
              Indihome menawarkan koneksi internet cepat dan stabil dengan teknologi fiber
              optic. Saat ini, tersedia layanan Triple Play dan Dual Play yang bisa Anda
              pilih. Triple Play terdiri dari Internet Fiber, Telepon Rumah, dan TV
              Interaktif (Usee TV). Adapun Dual Play terdiri dari Internet Fiber dan
              Telepon Rumah atau Internet Fiber dan TV Interaktif (Usee TV).
            </p>
          </div>

          <a
            class="btn btn-success"
            href="https://wa.me/628114449289?text=Saya%20tertarik%20berlangganan%20paket%20indihome..."
            >Daftar IndiHome Sekarang
          </a>
        </div>
        <div class="d-grid gap-2">
          <h2 class="text-center">PAKET INDIHOME MAKASSAR</h2>
          <h4 class="text-center text-primary">PAKET 2P INTERNET PHONE</h4>
          <div class="d-flex justify-content-center">
            <img :src="b2" alt="Responsive image" class="img-fluid" width="500" />
          </div>
          <p class="text-danger">Paket 2P Internet + Phone 300 menit</p>
          <div>
            <ul class="text-primary">
              <li>Speed 30 Mbps = Rp. 335.000,-/Bulan</li>
              <li>Speed 50 Mbps = Rp. 475.000,-/Bulan</li>
              <li>Speed 100 Mbps = Rp. 795.000,-/Bulan</li>
            </ul>
          </div>

          <p class="text-left">keterangan :</p>
          <ul>
            <li>Bebas nelpon 100 menit Lokal/interlokal (Telpon Rumah)</li>
            <li>Bebas akses disney + hotstar</li>
          </ul>
          <a
            class="btn btn-success mb-2"
            href="https://wa.me/628114449289?text=Saya%20tertarik%20berlangganan%20paket%20indihome..."
            >Daftar IndiHome Sekarang
          </a>
        </div>

        <div class="d-grid gap-2">
          <h4 class="text-center text-primary">PAKET 2P INTERNET TV</h4>
          <div class="d-flex justify-content-center">
            <img :src="internetTV" alt="Responsive image" class="img-fluid" width="500" />
          </div>
          <p class="text-danger">Paket 2P Internet + Usee TV</p>
          <ul class="text-primary">
            <li>Speed 20 Mbps = Rp. 345.000,-/Bulan</li>
            <li>Speed 30 Mbps = Rp. 420.000,-/Bulan</li>
            <li>Speed 40 Mbps = Rp. 495.000,-/Bulan</li>
            <li>Speed 50 Mbps = Rp. 560.000,-/Bulan</li>
            <li>Speed 100 Mbps = Rp. 915.000,-/Bulan</li>
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
          <a
            class="btn btn-success"
            href="https://wa.me/628114449289?text=Saya%20tertarik%20berlangganan%20paket%20indihome..."
            >Daftar IndiHome Sekarang
          </a>
        </div>

        <div class="d-grid gap-2">
          <h4 class="text-center text-primary">PAKET 3P INTERNET PHONE TV</h4>
          <div class="d-flex justify-content-center">
            <img :src="b2" alt="Responsive image" class="img-fluid" width="500" />
          </div>
          <p class="text-danger">Paket 3P Internet + Phone + Usee TV</p>
          <ul class="text-primary">
            <li>30 Mbps = Rp. 385.000,-/Bulan</li>
            <li>50 Mbps = Rp. 615.000,-/Bulan</li>
            <li>100 Mbps = Rp. 965.000,-/Bulan</li>
            <li>200 Mbps = Rp. 1.335.000,-/Bulan</li>
            <li>300 Mbps = Rp. 1.725.000,-/Bulan</li>
          </ul>
          <p class="text-left">keterangan :</p>
          <ul>
            <li>Bebas nelpon 100 menit Lokal/interlokal (Telpon Rumah)</li>
            <li>Bebas akses disney + hotstar</li>
          </ul>
          <a
            class="btn btn-success"
            href="https://wa.me/628114449289?text=Saya%20tertarik%20berlangganan%20paket%20indihome..."
            >Daftar IndiHome Sekarang
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
            <li>Speed 20 Mbps = Rp. 385.000,-/Bulan</li>
            <li>Speed 50 Mbps = Rp. 600.000,-/Bulan</li>
            <li>Speed 100 Mbps = Rp. 955.000,-/Bulan</li>
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
          <a
            class="btn btn-success"
            href="https://wa.me/628114449289?text=Saya%20tertarik%20berlangganan%20paket%20indihome..."
            >Daftar IndiHome Sekarang
          </a>
          <p class="mb-5">
            Cara Daftar Indihome Makassar cukup klik tombol Whatsapp diatas dan otomatis
            bisa melakukan chat dengan Costumer Service Kami. Anda bisa melengkapi data
            mengirimnya pula disana.
          </p>
        </div>
        <!-- footer fixed -->
        <div class="fixed-bottom d-grid gap-2 d-lg-none">
          <a
            class="btn btn-success"
            href="https://wa.me/628114449289?text=Saya%20tertarik%20berlangganan%20paket%20indihome..."
            >Daftar IndiHome Sekarang
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import image from "../img/logo.png";
import brosur from "../img/Brosur.png";
import b2 from "../img/b2.jpg";
import game from "../img/game.jpg";
import internetTV from "../img/internettv.jpg";

export default {
  data: function () {
    return {
      image: image,
      brosur: brosur,
      b2: b2,
      game: game,
      internetTV: internetTV,
    };
  },
};
</script>

<style scope>
div .mt-6 {
  margin-top: 5rem;
}
</style>
