<template>
  <div>
    <main class="overflow-x-hidden scroll-smooth">
      <header>
        <nav
          class="fixed top-0 px-10 py-3 bg-white w-full flex justify-between items-center z-50 transition-all .5s ease"
        >
          <div class="text-black">
            <h1 class="text-2xl font-semibold font-serif">Tutorgo</h1>
          </div>
          <ul class="md:flex hidden gap-3 font-serif">
            <li>
              <a href="#">Beranda</a>
            </li>
            <li>
              <a href="#about">Tentang</a>
            </li>
            <li>
              <a href="#tutorial">Tutorial</a>
            </li>
          </ul>
        </nav>
      </header>
      <section
        id="jumbotron"
        class="min-h-screen flex justify-center items-center bg-[url(/img/gorengan.jpg)] md:bg-fixed bg-cover bg-center"
      >
        <div class="text-center p-10">
          <h1 class="text-6xl font-bold text-white gorengan">GORENGAN</h1>
          <p class="mt-6 text-gray-200 gorengan">
            Gorengan? Makanan ringan, murah, mengenyangkan?
          </p>
          <div class="mt-6">
            <a
              href="#about"
              class="px-4 py-3 bg-red-500 text-white border border-red-500 hover:bg-opacity-75 transition-all ease .4s"
              >Selengkapnya</a
            >
          </div>
        </div>
      </section>
      <section
        id="about"
        class="min-h-screen flex justify-center items-center flex-wrap"
      >
        <div class="md:p-10 md:px-14 py-10 px-4 md:w-1/2 w-full">
          <h2 class="text-3xl font-semibold mb-4 font-serif">
            Apa itu Gorengan?
          </h2>
          <p class="text-gray-700">
            Gorengan adalah istilah yang mencakup berbagai jenis makanan yang
            dicelup adonan tepung dan kemudian digoreng rendam dalam minyak
            goreng panas yang banyak.<br />Di Indonesia gorengan adalah makanan
            ringan yang populer. Penjual gorengan dapat ditemukan di tepi jalan
            atau berkeliling dengan pikulan atau gerobak. Bahan-bahan yang
            dilapis adonan tepung dan digoreng antara lain: pisang, tempe, tahu,
            oncom, ubi, singkong, cireng (Bahasa Sunda: Aci digoreng), yaitu
            tepung singkong digoreng, sukun, dan bakwan (di Jawa Barat disebut
            "bala-bala", "yéyé") yaitu adonan tepung yang dicampur cacahan kubis
            dan wortel. Salah satu jenis gorengan yang populer adalah Tahu
            Sumedang. Perkedel jagung dan perkedel kentang juga masuk dalam
            kategori gorengan. Gorengan biasanya dimakan dengan cabe rawit. Di
            Malaysia gorengan juga lazim ditemui, antara lain pisang goreng dan
            ubi goreng.
          </p>
          <div class="mt-7">
            <a href="#tutorial" class="px-4 py-3 bg-black text-white hover:border hover:border-black hover:text-black hover:bg-transparent transition-all ease"
              >Lihat Tutorial</a
            >
          </div>
        </div>
        <div class="md:p-10 md:px-14 py-10 px-4 md:w-1/2 w-full">
          <img
            class="w-full object-cover"
            style="border-top: 2px dashed black; border-left: 2px dashed black"
            src="./img/gorengan.jpg"
          />
        </div>
      </section>
      <section id="tutorial" class="min-h-screen">
        <div class="text-center flex flex-col items-center gap-2">
          <h1 class="text-4xl font-semibold font-serif">
            Cara Membuat Gorengan
          </h1>
          <span class="h-2 w-24" style="border-top: 2px solid black"></span>
        </div>
        <div class="mt-10 flex flex-wrap items-center">
          <div class="md:p-10 md:px-14 py-10 px-4 relative md:w-1/2 w-full">
            <img
              src="./img/tutor1.jpg"
              style="
                border-top: 2px dashed black;
                border-right: 2px dashed black;
              "
              class="w-full object-cover"
            />
            <img
              src="./img/tutor2.jpg"
              style="border: 2px dashed black"
              class="w-32 absolute md:-bottom-10 md:-right-10 -bottom-10 right-14"
            />
          </div>
          <div
            class="md:p-10 md:px-14 py-10 px-4 relative md:w-1/2 w-full md:-mt-8"
          >
            <div class="flex flex-col gap-2">
              <h4 class="text-2xl font-semibold font-serif">Step 1</h4>
              <span class="h-2 w-12" style="border-top: 1px solid black"></span>
            </div>
            <p class="text-gray-700 mt-3">
              <span class="font-semibold">Siapkan bahan.</span>
              Bahan yang diperlukan tidaklah harus sama dengan apa yang saya
              lakukan disini, semua bisa di improve sesuai selera. Disini saya
              akan membuat gorengan pisan dengan bahan yang diperlukannya, yaitu
              tepung siap saji, air secukupnya, dan pisang kepok.
            </p>
          </div>
        </div>
        <div class="flex mt-10 flex-wrap">
          <div class="md:p-10 md:px-14 py-10 px-4 relative md:w-1/2 w-full">
            <div class="flex flex-col gap-2">
              <h4 class="text-2xl font-semibold font-serif">Step 2</h4>
              <span class="h-2 w-12" style="border-top: 1px solid black"></span>
            </div>
            <p class="text-gray-700 mt-3">
              <span class="font-semibold">Campurkan bahan dan masak.</span>
              Setelah bahan disiapkan, selanjutnya adalah mencampurkan air
              secukupnya dengan tepung siap saji. Jika sudah dicampurkan dan
              mendapatkan adonan yang diinginkan, selanjutnya kita bisa
              mencemplungkan pisang ke dalam adonan yang sudah dibuat
              sebelumnya, setelah melakukan itu semua maka kita bisa menggoreng
              pisang tersebut ke dalam wajan dengan minyak panas. Tunggu hingga
              warna kecoklatan dan pisang siap di santap.
            </p>
          </div>
          <div class="md:p-10 md:px-14 py-10 px-4 relative md:w-1/2 w-full">
            <img
              src="./img/tutor3.jpg"
              style="
                border-top: 2px dashed black;
                border-left: 2px dashed black;
              "
              class="w-full object-cover md:-mt-20 md:-ml-4"
            />
          </div>
        </div>
        <div class="mt-10">
          <div class="md:p-10 md:px-14 py-10 px-4 relative w-full">
            <div class="flex flex-col gap-2 text-center items-center">
              <h4 class="text-2xl font-semibold font-serif">Step 3</h4>
              <span class="h-2 w-12" style="border-top: 1px solid black"></span>
            </div>
            <p class="text-gray-700 mt-3 text-center">
              <span class="font-semibold">Hidangkan gorengan.</span>
              Gorengan sudah selesai dimasak, dan siap untuk dihidangkan.
            </p>
          </div>
        </div>
        <section
          class="min-h-screen flex justify-center items-center bg-slate-50 max-md:p-4"
        >
          <div class="flex flex-col gap-3 text-center">
            <h2 class="text-4xl font-bold font-serif">
              Pesan dan Hubungi Kami
            </h2>
            <p class="text-gray-700">
              Ingin makan gorengan enak dengan cara simpel dan tanpa memasaknya
              sendiri?
            </p>
            <div class="mt-6">
              <a
                href="#"
                class="px-5 py-3 rounded-full bg-[#3CC050] hover:text-[#3cc050] hover:border hover:border-[#3CC050] text-slate-100 transition-all ease hover:bg-transparent"
                >Kirimkan Pesan</a
              >
            </div>
          </div>
        </section>
        <div class="h-24 bg-slate-800 flex items-center justify-center">
          <p class="text-white">Created with 🤍 by figo arbiansyah</p>
        </div>
      </section>
    </main>
  </div>
</template>
