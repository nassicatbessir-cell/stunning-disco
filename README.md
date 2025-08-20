DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>پرداخت - دفتر مهندس خدمات رایانه و سخت ابزار _ ارتا فرانگار</title>
<style>
body { font-family: Tahoma, sans-serif; background:#f4f4f4; margin:0; padding:0; color:#333; }
header { background:#1e88e5; color:white; padding:20px; text-align:center; }
.container { max-width:600px; margin:30px auto; background:white; padding:20px; border-radius:10px; box-shadow:0 4px 8px rgba(0,0,0,0.1); }
h2 { color:#1e88e5; text-align:center; }
.card-info { background:#f0f0f0; padding:15px; border-radius:8px; text-align:center; margin-bottom:20px; }
button { background:#1e88e5; color:white; padding:10px 20px; border:none; border-radius:5px; cursor:pointer; margin-top:10px; }
button:hover { background:#1565c0; }
.info { margin-top:20px; font-size:0.95em; line-height:1.5; }
.copy-msg { color:green; display:none; margin-top:10px; text-align:center; }
footer { margin-top:30px; text-align:center; font-size:0.85em; color:#666; }
</style>
</head>
<body>

<header>
  <h1>دفتر مهندس خدمات رایانه و سخت ابزار _ ارتا فرانگار</h1>
</header>

<div class="container">
  <h2>پرداخت کارت‌به‌کارت</h2>
  <div class="card-info">
    <p>شماره کارت: <span id="cardNumber">6037.9973.2942.6721</span></p>
    <p>نام صاحب کارت: بانو منیجه خاتونی‌</p>
    <p>بانک: ملت</p>
    <button onclick="copyCard()">کپی شماره کارت</button>
    <p class="copy-msg" id="copyMsg">شماره کارت کپی شد!</p>
  </div>

  <div class="info">
    <p><strong>آدرس:</strong> تهران، منطقه ۶، ولیعصر، بالاتر از طالقانی، چهارراه</p>
    <p><strong>Address:</strong> Tehran District 6, Valiasr Street Above Taleghani, Crossroad</p>
    <p><strong>تماس با پشتیبانی:</strong> 02171197</p>
    <p><strong>شناسه مالیاتی:</strong> 123456789</p>
  </div>
</div>

<footer>
  © 2025 دفتر مهندس خدمات رایانه و سخت ابزار _ ارتا فرانگار
</footer>

<script>
function copyCard() {
  const card = document.getElementById("cardNumber").innerText;
  navigator.clipboard.writeText(card).then(() => {
    document.getElementById("copyMsg").style.display = "block";
    setTimeout(() => { document.getElementById("copyMsg").style.display = "none"; }, 2000);
  });
}
</script>

</body>
<
