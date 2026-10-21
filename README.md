
<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>EFE VSM QR Kilit</title>
<style>
* { box-sizing: border-box; }
body {
  margin: 0;
  padding: 25px 15px;
  background: #101010;
  color: white;
  font-family: Arial, sans-serif;
  text-align: center;
}
.card {
  max-width: 360px;
  margin: auto;
  padding: 25px 18px;
  border: 2px solid #333;
  border-radius: 22px;
  background: #1c1c1c;
}
h1 { font-size: 32px; }
.green { color: #19d879; }
button {
  width: 100%;
  padding: 15px;
  border: 0;
  border-radius: 12px;
  background: #19d879;
  color: #101010;
  font-size: 17px;
  font-weight: bold;
}
.small { color: #bbb; font-size: 13px; }
</style>
</head>
<body>
<div class="card">
  <h1>🏍️ VOLTA VSM</h1>
  <h2 class="green">EFE VSM</h2>
  <p>QR KODLU KİLİT SİSTEMİ</p>
  <hr>
  <h2 id="status">🔒 KİLİTLİ</h2>
  <button onclick="kontrol()">KİLİDİ KONTROL ET</button>
  <p id="mesaj"></p>
  <p class="small">EFE VSM • SÜRÜŞE HAZIR</p>
</div>

<script>
function kontrol() {
  document.getElementById("status").textContent =
    "🔐 ELEKTRONİK BAĞLANTI GEREKLİ";
  document.getElementById("mesaj").textContent =
    "Gerçek kilit kontrolü için elektronik donanım bağlanmalıdır.";
}
</script>
</body>
</html>

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
