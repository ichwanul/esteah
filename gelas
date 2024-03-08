JavaScript
const varianEsTeh = [
  {
    nama: "Es Teh Original",
    deskripsi: "Teh hitam klasik yang menyegarkan. Cocok untuk menemani aktivitas Anda sehari-hari.",
    gambar: "https://id.pinterest.com/pin/755760381222607522/",
  },
  {
    nama: "Es Teh Manis",
    deskripsi: "Teh hitam dengan tambahan gula sesuai selera. Tingkat kemanisan bisa disesuaikan dengan keinginan Anda.",
    gambar: "https://www.istockphoto.com/id/foto-foto/es-teh",
  },
  // Tambahkan data untuk varian lain (Es Teh Susu, Es Teh Tarik, Es Teh Cincau)
];

const varianContainer = document.getElementById("varian-container");

varianEsTeh.forEach((varian) => {
  const cardElement = document.createElement("div");
  cardElement.classList.add("varian-card");

  const gambarElement = document.createElement("img");
  gambarElement.classList.add("gambar-es-teh");
  gambarElement.src = varian.gambar;
  gambarElement.alt = varian.nama;

  const namaElement = document.createElement("h3");
  namaElement.textContent = varian.nama;

  const deskripsiElement = document.createElement("p");
  deskripsiElement.textContent = varian.deskripsi;

  cardElement.appendChild(gambarElement);
  cardElement.appendChild(namaElement);
  cardElement.appendChild(deskripsiElement);

  varianContainer.appendChild(cardElement);
});
