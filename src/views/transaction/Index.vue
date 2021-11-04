<template>
  <!-- navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light mb-2">
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
  <div class="d-flex justify-content-center">
    <div class="card" style="width: 1000px">
      <div class="card-body">
        <!-- content 1 -->
        <h1 class="text-center text-danger p-2">Daftar Indihome Makassar</h1>
        <h2 class="text-center font-weight-bold p-2">
          Layanan Online Pasang Baru Indihome Makassar
        </h2>

        <div class="p-4 d-grid gap-2">
          <p>
            Silahkan pilih paket Internet Indihome sesuai dengan kebutuhan Anda. Apabila
            Anda ingin daftar Indihome atau mempunyai pertanyaan seputar layanan Indihome
            Anda bisa langsung live chat via Whatsapp ke Marketing kami. Kami siap
            membantu Anda sampai dengan terpasanganya layanan Indihome fiber di rumah,
            apartemen, kantor maupun tempat usaha Anda. Kami melayani pemasangan Indihome
            untuk seluruh wilayah Makassar, Gowa, Maros dan sekitarnya. Indihome
            menawarkan koneksi internet cepat dan stabil dengan teknologi fiber optic.
            Saat ini, tersedia layanan Triple Play dan Dual Play yang bisa Anda pilih.
            Triple Play terdiri dari Internet Fiber, Telepon Rumah, dan TV Interaktif
            (Usee TV). Adapun Dual Play terdiri dari Internet Fiber dan Telepon Rumah atau
            Internet Fiber dan TV Interaktif (Usee TV).
          </p>

          <a
            class="btn btn-success"
            href="https://wa.me/62292256219?text=Saya%20tertarik%20membeli%20paket%20indihome"
            >Daftar IndiHome Sekarang
          </a>
        </div>
        <div class="d-grid gap-2">
          <h2 class="text-center">PAKET INDIHOME MAKASSAR</h2>
          <h4 class="text-center text-primary">PAKET 2P INTERNET PHONE</h4>
          <div class="d-flex justify-content-center">
            <img :src="brosur" alt="Responsive image" class="img-fluid" width="500" />
          </div>
          <p class="text-danger">Paket 2P Internet + Phone 300 menit</p>
          <div>
            <ul class="text-primary">
              <li>Speed 20 Mbps = Rp. 315.000,-/Bulan</li>
              <li>Speed 30 Mbps = Rp. 420.000,-/Bulan</li>
              <li>Speed 40 Mbps = Rp. 495.000,-/Bulan</li>
              <li>Speed 50 Mbps = Rp. 560.000,-/Bulan</li>
              <li>Speed 100 Mbps = Rp. 915.000,-/Bulan</li>
            </ul>
          </div>

          <p class="text-left">keterangan :</p>
          <ul>
            <li>Gratis 300 menit nelpon lokal / interlokal.</li>
            <li>
              Pilihan benefit Study (cloud storage dan Indihome study) atau Entertainment.
            </li>
            <li>Movin’ Phone (bebas pakai selama berlangganan IndiHome).</li>
            <li>Harga berlaku untuk pelanggan baru mulai Oktober 2020.</li>
            <li>Harga di atas untuk pembayaran setiap bulan.</li>
            <li>Harga sudah termasuk biaya sewa ONT.</li>
          </ul>
          <a
            class="btn btn-success mb-2"
            href="https://wa.me/62292256219?text=Saya%20tertarik%20membeli%20paket%20indihome"
            >Daftar IndiHome Sekarang
          </a>
        </div>

        <div class="d-grid gap-2">
          <h4 class="text-center text-primary">PAKET 2P INTERNET PHONE</h4>
          <div class="d-flex justify-content-center">
            <img :src="brosur" alt="Responsive image" class="img-fluid" width="500" />
          </div>
          <p class="text-danger">Paket 2P Internet + Usee TV</p>
          <ul class="text-primary">
            <li>Speed 20 Mbps = Rp. 345.000,-/Bulan</li>
            <li>Speed 30 Mbps = Rp. 390.000,-/Bulan</li>
            <li>Speed 40 Mbps = Rp. 465.000,-/Bulan</li>
            <li>Speed 50 Mbps = Rp. 530.000,-/Bulan</li>
            <li>Speed 100 Mbps = Rp. 885.000,-/Bulan</li>
          </ul>
          <p class="text-left">keterangan :</p>
          <ul>
            <li>
              Usee TV New Basic terdiri dari 109 channels UseeTV (91 channels SD dan 18
              channels HD).
            </li>
            <li>Pilihan benefit Indihome Study / i-konser / Iflix.</li>
            <li>Harga berlaku untuk pelanggan baru mulai Oktober 2020.</li>
            <li>Harga di atas untuk pembayaran setiap bulan.</li>
            <li>
              Harga paket sudah termasuk Hybrid Box IndiHome dan ONT selama berlangganan.
            </li>
            <li>Harga belum termasuk PPN.</li>
          </ul>
          <a
            class="btn btn-success"
            href="https://wa.me/62292256219?text=Saya%20tertarik%20membeli%20paket%20indihome"
            >Daftar IndiHome Sekarang
          </a>
        </div>

        <div class="d-grid gap-2">
          <h4 class="text-center text-primary">PAKET 3P INTERNET PHONE TV</h4>
          <div class="d-flex justify-content-center">
            <img :src="brosur" alt="Responsive image" class="img-fluid" width="500" />
          </div>
          <p class="text-danger">Paket 3P Internet + Phone + Usee TV</p>
          <ul class="text-primary">
            <li>20 Mbps = Rp. 375.000,-/Bulan</li>
            <li>30 Mbps = Rp. 450.000,-/Bulan</li>
            <li>40 Mbps = Rp. 525.000,-/Bulan</li>
            <li>50 Mbps = Rp. 590.000,-/Bulan</li>
            <li>100 Mbps = Rp. 945.000,-/Bulan</li>
            <li>200 Mbps = Rp. 1.665.000,-/Bulan</li>
            <li>300 Mbps = Rp. 2.655.000,-/Bulan</li>
          </ul>
          <p class="text-left">keterangan :</p>
          <ul>
            <li>Gratis 300 menit nelpon lokal/interlokal.</li>
            <li>
              Usee TV New Basic terdiri dari 109 channels UseeTV (91 channels SD dan 18
              channels HD).
            </li>
            <li>Harga di atas untuk pembayaran setiap bulan.</li>
            <li>Harga berlaku untuk pelanggan baru mulai Oktober 2020.</li>
            <li>Harga dan benefit paket berlaku selama Anda berlangganan Indihome.</li>
            <li>Harga sudah termasuk Hybrid Box IndiHome dan ONT selama berlangganan.</li>
            <li>Harga belum termasuk PPN.</li>
          </ul>
          <a
            class="btn btn-success"
            href="https://wa.me/62292256219?text=Saya%20tertarik%20membeli%20paket%20indihome"
            >Daftar IndiHome Sekarang
          </a>
        </div>
        <div class="d-grid gap-2">
          <h4 class="text-center text-primary">PAKET INTERNET GAMER</h4>
          <div class="d-flex justify-content-center">
            <img :src="brosur" alt="Responsive image" class="img-fluid" width="500" />
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
            <li>Harga berlaku untuk pelanggan baru mulai Oktober 2020.</li>
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
            href="https://wa.me/62114449289?text=Saya%20tertarik%20membeli%20paket%20indihome"
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
            href="https://wa.me/62292256219?text=Saya%20tertarik%20membeli%20paket%20indihome"
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

export default {
  data: function () {
    return {
      image: image,
      brosur: brosur,
    };
  },
};
</script>

<style scope>
@media screen and (max-width: 550px) {
  .footer {
    display: flex;
  }
}
</style>
