<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Quick Lock Auto</title>

<style>
body {
    margin: 0;
    overflow-x: hidden; /* ✅ FIX 1 */
    font-family: Arial, sans-serif;
    background: linear-gradient(#000000, #0b1a2f);
    color: white;
    text-align: center;
}

.container {
    padding: 20px;
    max-width: 100%; /* ✅ FIX 2 */
    box-sizing: border-box; /* ✅ FIX 2 */
}

h1 {
    font-size: 32px;
    margin-top: 40px;
}

.tagline {
    color: #aaa;
    letter-spacing: 2px;
    margin-bottom: 20px;
}

.phone {
    font-size: 36px;
    font-weight: bold;
    margin: 20px 0;
}

.btn {
    display: block;
    width: 90%;
    max-width: 350px;
    margin: 10px auto;
    padding: 16px;
    border-radius: 14px;
    font-size: 18px;
    text-decoration: none;
    font-weight: bold;
}

.call {
    background: #e5e5e5;
    color: black;
}

.text {
    border: 2px solid white;
    color: white;
}

.available {
    color: #00ff66;
    margin: 15px 0;
    font-weight: bold;
}

.services {
    margin-top: 30px;
}

.service-box {
    background: rgba(255,255,255,0.05);
    padding: 18px;
    border-radius: 14px;
    margin: 12px auto;
    width: 90%;
    max-width: 350px;
    text-align: left;
}

.footer {
    margin-top: 40px;
    color: #888;
    font-size: 14px;
}

/* Bottom Bar */
.bottom-bar {
    position: fixed;
    bottom: 0;
    width: 100%;
    background: #e5e5e5;
    color: black;
    padding: 12px;
    font-weight: bold;
}
</style>
</head>

<body>

<div class="container">
    <h1>Quick Lock Auto 🔒</h1>
    <div class="tagline">FAST • RELIABLE • 24/7</div>

    <h3>Locked Out? Flat Tire? Dead Battery? We Come To You Fast 🚗💨</h3>

    <div class="phone">754-248-6383</div>

    <a href="tel:7542486383" class="btn call">📞 CALL NOW</a>
    <a href="sms:7542486383" class="btn text">💬 TEXT NOW</a>

    <div class="available">✔ Available 24/7 • Fast Response Time</div>

    <div class="services">
        <h2>Our Services</h2>

        <div class="service-box">🚗 Car Lockouts</div>
        <div class="service-box">🔧 Flat Tire Change</div>
        <div class="service-box">🔋 Jump Starts</div>

        <div class="service-box">🔑 Car Key Replacement</div>
        <div class="service-box">📡 Key Programming</div>

        <div class="service-box">🛞 Tire Inflation</div>
        <div class="service-box">🛠️ Roadside Assistance</div>
    </div>

    <div class="footer">
        Serving Broward County • Fort Lauderdale • Nearby Areas
    </div>
</div>

<div class="bottom-bar">
    📞 Call Now - 754-248-6383
</div>

</body>
</html>
