<html>
<meta charset='UTF-8' />
<meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5'
  name='viewport' />
<meta content='IE=edge' http-equiv='X-UA-Compatible' />

<script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script>
<script src="https://unpkg.com/typeit@8.7.0/dist/index.umd.js"></script>
<link href="https://htmlku.com/dariku/style.css" rel="stylesheet" type="text/css" />

<head>
  <title>Makasih Ayang Mila❤</title>
</head>

<body>

  <div id="bodyblur">
    <!-- Wallpaper / Background --><img
      src="https://github.com/Frz326/Data-Base/blob/main/Gambar%20WhatsApp%202024-01-25%20pukul%2015.45.09_c546195c.jpg?raw=true"
      id="wallpaper" />
  </div>

  <div class="kumpulanstiker">
    <!-- Stiker untuk Konten -->
    <img src="https://htmlku.com/0/panda/pusn.gif" id="fotoakhir1" />
    <img src="https://feeldreams.github.io/mndkat.gif" id="fotoakhir2" />
    <img src="https://i.ibb.co/xGc2wBh/cartoons.gif" id="fotoakhir3" />
    <img src="https://htmlku.com/0/panda/gemoy.gif" id="fotoakhir4" />
  </div>

  <div id='Content'>

    <div id="suratin" onClick="memulai();audio.play();">
      <!-- Surat --><img
        src="https://github.com/Frz326/Data-Base/blob/main/Gambar%20WhatsApp%202024-01-26%20pukul%2000.37.11_6b32799a.jpg?raw=true" />
    </div>
    <p id="ket">Sentuh Beruang nya!</p>

    <div><!-- Foto Akhir --><img src="https://github.com/Frz326/Data-Base/blob/main/beruang%20nangis.gif?raw=true"
        id="fotoakhir" /></div>
    <div>
      <blockquote id='bq'>
        <p id="kalimat"></p>
        <p id="kalimatc"></p>
      </blockquote>
    </div>

    <!-- Tombol Kirim Pesan -->
    <div id="Tombol">
      <a onClick="sjawab()">
        <b>💌 Balas</b>
      </a>
    </div>

  </div>

  <div class='sticky-ad' id='sticky-ad'>
    <div class='adB'><a rel="dofollow" href='https://bit.ly/htmlfeeldream'>Lihat Script HTML Lainnya di Sini!</a></div>
    <button aria-label='Close this ad' class='sticky-ad-close-button' onclick='hilangkan();' />
  </div>

  <script src="https://htmlku.com/dariku/script.js"></script>

  <!-- Ganti Kata², Foto, Lagu di bawah ya
1) Upload foto ke https://postimages.org
     buat dapetin linknya
2) Ganti Lagu Upload ke replit.com
     atau bisa juga ke mailboxdrive.com -->

  <script type="text/javascript">
    async function jawab() { await swals.fire('Kirim pesan ke WhatsApp aku, ya!'); window.location = "" + pesanwhatsapp; }

    async function pertama() {
      audio = new Audio('https://feeldreams.github.io/audio/nightchanges.mp3'); setTimeout(showDiv, 100);
    } pertama();


    async function pesan() {
      await swalst.fire({
        title: 'Heyy Mila! 😍',
        imageUrl: '' + fotoakhir1.src,
      });
      await swalst.fire({
        title: 'Makasih Ya!! 😘',
        imageUrl: '' + fotoakhir2.src,
      });
      await swalst.fire({
        title: 'Makasih buat apaa Hayoo?',
        imageUrl: '' + fotoakhir3.src,
      });
      await swalst.fire({
        title: 'Baca sampai akhir ya sayang ❤',
        imageUrl: '' + fotoakhir4.src,
      });

      katangetik = "<b>Aku cuma mau bilang:</b><br><br><i>im very lucky to have you!</i><br>Terimakasih telah bersamaku mau nerima aku apa adanya..<br><br>Dan asal kamu tau gimana beruntungnya aku semenjak deket sama kamu,  dengan kamu yang sederhana tapi kamu selalu punya cara buat aku tersenyum, bahkan dari hal kecil yang belum pernah aku dapatkan sebelumnya... <br><br>Terimakasih banyak yaa 🙂, <br>Dari kamu aku merasa dihargai..<333333";
      katangetik2 = "<i>I Love uuuu 💞🤍💝❣️</i>";

      pesanwhatsapp = "ilvyou too 💞🤍💝❣️";
      setTimeout(kpemb, 200);
    }
  </script>
</body>

</html>
