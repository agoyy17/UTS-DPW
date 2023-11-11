<template>
    <div>
      <div class="container">
            <div class="row">
                <div class="mr40 mt20">
                    <router-link to="/list-product">
                        <img src="../../assets/icons/back.svg">
                    </router-link>
                </div>
                <div>
                    <h1 class="m0">Detail Product</h1>
                    <p class="mt5 mb20 tc-green">Your product details</p>
                </div>
            </div>
            <hr class="uline-grey">
            <div class="mt10">
                <div class="image-description-container">
            <img src="../../assets/images/iphone15.png" alt="Large Image" width="280" height="380">
            <div class="description">
                <p style="color: gray;">j4f7ewf36</p>
                <p><strong style="font-size: 20px;">iPhone 15 128GB</strong></p>
                <p><strong style="font-size: 35px;">Rp 15.000.000</strong></p>
                <p><strong>Product Description :</strong></p>
                <p style="color: gray;">Keunggulan iPhone 15 128GB :</p>
                <p style="color: gray;">• Kemampuan pengisian daya nirkabel MagSafe dan dukungan untuk aksesori MagSafe, seperti dompet dan case.</p>
                <p style="color: gray;">• Dibangun dengan ketahanan tinggi terhadap air dan debu, sehingga dapat menyertai Anda di berbagai lingkungan.</p>
                <p style="color: gray;">• Keamanan yang ditingkatkan melalui Face IDyang memastikan hanya Anda yang dapat mengakses perangkat.</p>
                <p style="color: gray;">• Pengalaman audio yang ditingkatkan dengan dukungan untuk Dolby Atmos dan pengaturan suara adaptif.</p>
                <p><strong>Product Category: <span style="color: gray;">Electronic</span></strong></p>
                <p><strong>Unit: <span style="color: gray;">20</span></strong></p>
                <p><strong>Min Purchases: <span style="color: gray;">1 Unit</span></strong></p>
                <p><strong>Max Purchases: <span style="color: gray;">9 Unit</span></strong></p>
            </div>
            </div>
<div class="flex-container">
  <div>
    <p>Status<hr class="gray-line"></p>
    <label class="label-green">Publish</label>
  </div>
  <div class="right-content">
    <p>Product Status<hr class="gray-line"></p>
    <label class="label-green">Available</label>
  </div>
</div>

            </div>
        </div>
    </div>
  </template>
  
  <style>
.image-description-container {
  display: flex;
  margin-bottom: 10px;
  align-items: center; /* Untuk vertikal tengahkan gambar dan deskripsi */
}

.description {
    margin-left: 70px;
    padding-bottom: 0px;
  /* Jarak antara gambar dan deskripsi */
  /* Tambahan gaya CSS sesuai kebutuhan Anda */
}
.flex-container {
  display: flex;
  align-items: center;
  justify-content: space;
  margin-bottom: 40px; /* Memberi jarak antara dua blok konten yang berdampingan */
}
.right-content {
  margin-left: 20px; /* Menggeser elemen ke sisi kanan */
}
.gray-line {
  background-color: gray; /* Warna latar belakang diubah menjadi abu-abu */
  height: 1px; /* Ketebalan garis */
  border: none; /* Tidak ada border */
  width: 89px;
  margin: 0; /* Margin 0 untuk menghilangkan spasi */
}
</style>