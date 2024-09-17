<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Buku Tamu</title>
  <link rel="stylesheet" href="Tgs1.css">
</head>
<body>
  <header>
    <h1>Buku Tamu</h1>
  </header>

  <main class="container">
    <!-- Formulir Isi Buku Tamu -->
    <section class="form-section">
      <h2>Isi Buku Tamu</h2>
      <form action="#" method="POST">
        <label for="name">Nama:</label>
        <input type="text" id="name" name="name" placeholder="Nama Anda" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Email Anda" required>

        <label for="message">Pesan:</label>
        <textarea id="message" name="message" placeholder="Tulis pesan Anda di sini" required></textarea>

        <button type="submit">Kirim</button>
      </form>
    </section>

    <!-- Daftar Buku Tamu -->
    <section class="guest-list">
      <h2>Daftar Buku Tamu</h2>
      <ul>
        <li><strong>John Doe</strong> (john@example.com): Pesan singkat dari John.</li>
        <li><strong>Jane Doe</strong> (jane@example.com): Pesan singkat dari Jane.</li>
        <li><strong>Alex Smith</strong> (alex@example.com): Pesan singkat dari Alex.</li>
      </ul>
    </section>
  </main>
</body>
</html>


* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background-color: #f4f4f4;
  color: #333;
  padding: 20px;
}

h1, h2 {
  text-align: center;
  margin-bottom: 20px;
}

.container {
  display: flex;
  justify-content: space-between;
  gap: 20px;
  max-width: 1000px;
  margin: 0 auto;
}

.form-section, .guest-list {
  flex: 1;
  background-color: white;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}
form {
  display: flex;
  flex-direction: column;
  gap: 15px;
}

label {
  font-weight: bold;
}

input[type="text"], input[type="email"], textarea {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
  font-size: 16px;
  width: 100%;
}

textarea {
  height: 100px;
  resize: vertical;
}

button {
  padding: 10px;
  background-color: #28a745;
  color: white;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  font-size: 16px;
}

button:hover {
  background-color: #218838;
}
.guest-list ul {
  list-style-type: none;
  padding: 0;
}

.guest-list li {
  background-color: #f9f9f9;
  border: 1px solid #ddd;
  padding: 10px;
  margin-bottom: 10px;
  border-radius: 4px;
}

@media (max-width: 768px) {
  .container {
    flex-direction: column;
  }

  .form-section, .guest-list {
    width: 100%;
  }
}

/* Menambahkan background gradien */
body {
  background: linear-gradient(to right, #74ebd5, #acb6e5);
}

/* Mengimpor font dari Google Fonts */
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

body {
  font-family: 'Roboto', sans-serif;
}

