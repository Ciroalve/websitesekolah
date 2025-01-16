<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <h5 style="background-color: black;" class="text-white text-center rounded-3 p-2 m-3">
          VISI & MISI - TUJUAN
        </h5>
      </div>
      <div class="col-lg-12">
        <p style="background-color: whitesmoke;" class="rounded-3 p-1 m-3 text-secondary">
          <NuxtLink to="/profil" class="text-decoration-none">Profil</NuxtLink> / Visi & Misi
        </p>
      </div>
      <div class="visi-misi subcontent">
        <div style="margin-top: 30px;">
          <h4 style="text-align: center"><strong>Visi & Misi SMK Negeri 4 Tasikmalaya</strong></h4>
        </div>
        <div style="margin-top: 40px;">
          <h5 class="text-center"><strong>Visi:</strong></h5>
          <blockquote style="text-align: center;">
            <strong>TERWUJUDNYA LULUSAN YANG CERDAS, AKTIF, KOMPETITIF, ADAPTIF, DAN PRODUKTIF BERLANDASKAN IMAN DAN TAKWA</strong>
            <footer><strong>(CAKAP BERIMTAK)</strong></footer>
          </blockquote>
        </div>
        <div style="margin-top: 40px;">
          <h5 class="text-center"><strong>Misi:</strong></h5>
        </div>
        <ol style="text-align: justify; line-height: 200%;" start="1">
          <li>Menyiapkan Sumber Daya Manusia yang cerdas dan kompeten baik hardskill maupun softskill.</li>
          <li>Meningkatkan dan mengembangkan aktifitas serta kreatifitas seluruh warga sekolah dalam berbagai kegiatan positif.</li>
          <li>Mewujudkan manajemen pengelolaan yang efektif, efisien, transparan, akuntabel dan layanan prima.</li>
          <li>Menumbuhkan dan mengembangkan potensi dan kemampuan Sumber Daya Manusia yang berdaya saing tinggi melalui berbagai kegiatan akademik maupun non akademik.</li>
          <li>Menyelenggarakan berbagai program kegiatan dalam upaya meningkatkan Sumber Daya Manusia yang mampu menyesuaikan dengan perkembangan.</li>
          <li>Mengembangkan sarana prasarana dan lingkungan sekolah yang menyenangkan sebagai wadah menumbuhkembangkan daya kreasi dan inovasi untuk menghasilkan produk teknologi tepat guna.</li>
          <li>Membangun jiwa wirausaha yang handal melalui pembelajaran Teaching Factory (TEFA) dan Kelas Industri.</li>
          <li>Menjalin dan mengembangkan kemitraan dengan Industri dan Dunia Kerja (IDUKA) serta lembaga lainnya yang relevan.</li>
          <li>Menanamkan dan membudayakan sikap dan perilaku yang baik pada aktivitas di sekolah maupun dalam kehidupan sehari-hari.</li>
        </ol>
        <hr title="TUJUAN SMK" />
        <div style="margin-top: 30px;">
          <h4 style="text-align: center"><strong>Tujuan SMK Negeri 4 Tasikmalaya</strong></h4>
        </div>
        <ol style="text-align: justify; line-height: 200%;" start="1">
          <li>Sekolah meraih prestasi pencapaian nilai rata-rata UN dan indeks integritas di atas rata-rata Nasional pada tahun 2026.</li>
          <li>Sekolah Menghasilkan Tamatan yang siap bekerja Minimal 50% Tamatan bekerja pada tahun tamat.</li>
          <li>Terciptanya aktivitas dan kreatifitas yang positif oleh seluruh warga sekolah.</li>
          <li>Sekolah meraih prestasi akademik dan non akademik minimal di tingkat provinsi Jawa Barat dan Nasional.</li>
          <li>Sekolah memiliki tenaga pendidik dan kependidikan yang berkualifikasi minimal S1 dan linier dengan tugasnya, bersertifikat pendidik dan telah mengikuti diklat implementasi kurikulum merdeka pada tahun 2024.</li>
          <li>Sekolah mencapai kriteria sekolah berwawasan lingkungan (adiwiyata) pada tahun 2026.</li>
          <li>Sekolah terakreditasi dengan Nilai A pada tahun 2024.</li>
          <li>Sekolah memiliki Lembaga Sertifikasi Profesi (LSP) yang terlisensi, Tempat Uji Kompetensi (TUK) yang terverifikasi dan Bursa Kerja Khusus (BKK) yang terakreditasi pada tahun 2025.</li>
          <li>Sekolah memiliki Perpustakaan yang terakreditasi A pada tahun 2026.</li>
          <li>Sekolah menjadi Badan Layanan Umum Daerah (BLUD) pada tahun 2025.</li>
          <li>Sekolah mengimplementasikan Kurikulum Merdeka untuk seluruh tingkat pada tahun 2024.</li>
          <li>Sekolah memiliki Dokumen Kurikulum Merdeka untuk seluruh tingkat pada tahun 2024.</li>
          <li>Sekolah menerapkan Kurikulum Merdeka dengan Pembelajaran Berdiferensiasi dan Pembelajaran Sosial-Emosional untuk seluruh tingkat pada tahun 2024.</li>
          <li>Sekolah memiliki sarana prasarana sesuai dengan standar pelayanan minimal pendidikan dan standar IDUKA pada tahun 2026.</li>
          <li>Sekolah memiliki Teaching Factory di semua program keahlian yang sesuai dengan standar industri dan representatif pada tahun 2024.</li>
          <li>Sekolah melaksanakan program menumbuh kembangkan Budi Pekerti dan akhlak mulia melalui pendidikan karakter pada kegiatan intra, ekstra kurikuler dan non kurikuler.</li>
        </ol>
      </div>
    </div>
  </div>
</template>

  <style scoped>
.container-fluid {
    margin: 0 auto;
    padding: 20px;
}

h5, h4, h3 {
    font-family: 'Arial', sans-serif;
    font-weight: bold;
}

.text-center {
    text-align: center;
}

.text-secondary {
    color: #6c757d;
}

.text-white {
    color: #fff;
}
h5 {
    background-color: black;
    color: white;
    text-align: center;
    border-radius: 15px;
    padding: 10px;
    margin-bottom: 15px;
}
p {
    background-color: whitesmoke;
    border-radius: 10px;
    padding: 10px;
    margin-bottom: 20px;
}

.text-decoration-none {
    text-decoration: none;
}

hr[title="TUJUAN SMK"] {
    border: 0;
    border-top: 2px dashed #000;
    margin: 20px 0;
}
.visimisi {
    padding: 20px;
    background-color: #f8f9fa;
    border-radius: 10px;
    margin-top: 30px;
}
h4 {
    font-size: 24px;
}

h5 {
    font-size: 20px;
    margin-top: 20px;
}

blockquote {
    margin: 20px;
    padding: 10px;
    font-style: italic;
    border-left: 4px solid #ddd;
}

footer {
    font-weight: normal;
    font-size: 18px;
}
ol {
    list-style-type: decimal;
    padding-left: 40px;
    margin-top: 20px;
    font-size: 16px;
    line-height: 1.8;
}

ol li {
    text-align: justify;
}

ol li:last-child {
    margin-bottom: 20px;
}
ol + hr {
    border: 2px solid #ddd;
}

ol + hr + ol {
    margin-top: 20px;
}
@media (max-width: 768px) {
    h5 {
        font-size: 16px;
    }
    h4 {
        font-size: 20px;
    }
    ol li {
        font-size: 14px;
    }
}

</style>
