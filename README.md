
<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>EFE VSM | QR Kilit</title>
<style>
body {
  background: #111;
  color: white;
  font-family: Arial, sans-serif;
  text-align: center;
  padding: 35px 15px;
}
.card {
  max-width: 320px;
  margin: auto;
  padding: 25px;
  background: #202020;
  border-radius: 20px;
  border: 1px solid #444;
}
h1 { color: #ff3333; }
button {
  background: #ff3333;
  color: white;
  padding: 14px 22px;
  border: none;
  border-radius: 12px;
  font-size: 17px;
}
</style>
</head>
<body>
<div class="card">
  <h1>🏍️ EFE VSM</h1>
  <p>VOLTA VSM QR KİLİT SİSTEMİ</p>
  <h2 id="status">🔒 KİLİTLİ</h2>
  <button onclick="check()">KİLİDİ KONTROL ET</button>
  <p id="message">QR kod başarıyla okutuldu.</p>
</div>
<script>
function check() {
  document.getElementById("status").textContent = "🔐 GÜVENLİK KONTROLÜ";
  document.getElementById("message").textContent =
    "Elektronik kilit bağlantısı henüz kurulmadı.";
}
</script>
</body>
</html>
