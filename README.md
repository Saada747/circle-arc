<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>راهنمای جامع دایره و کمان (Circle & Arc)</title>
    <style>
        :root {
            --primary: #2563eb;
            --bg: #f8fafc;
            --card: #ffffff;
            --text: #1e293b;
        }
        body {
            font-family: system-ui, -apple-system, sans-serif;
            background-color: var(--bg);
            color: var(--text);
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
        header {
            text-align: center;
            margin-bottom: 40px;
        }
        .card {
            background: var(--card);
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 6px -1px rgba(0,0,0,0.1);
            margin-bottom: 25px;
        }
        h2 {
            color: var(--primary);
            margin-top: 0;
        }
        .formula {
            background: #eff6ff;
            padding: 10px;
            border-right: 4px solid var(--primary);
            font-family: monospace;
            direction: ltr;
            text-align: left;
        }
        .grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
        }
        input {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
            box-sizing: border-box;
            border: 1px solid #cbd5e1;
            border-radius: 6px;
        }
        button {
            grid-column: span 2;
            background: var(--primary);
            color: white;
            border: none;
            padding: 10px;
            border-radius: 6px;
            cursor: pointer;
            font-weight: bold;
        }
        #result {
            margin-top: 15px;
            font-weight: bold;
            color: #059669;
        }
    </style>
</head>
<body>

<div class="container">
    <header>
        <h1>اطلاعات و محاسبات دایره و کمان</h1>
        <p>مفاهیم پایه، فرمول‌ها و ابزار محاسبه آنلاین</p>
    </header>

    <div class="card">
        <h2>۱. دایره (Circle) چیست؟</h2>
        <p>مجموعه نقاطی از صفحه که فاصله‌شان از یک نقطه ثابت (مرکز)، مقدار ثابتی (شعاع) باشد.</p>
        <p><strong>محیط دایره:</strong> مسافت دور تا دور دایره.</p>
        <div class="formula">C = 2 * π * r</div>
        <p><strong>مساحت دایره:</strong> فضای داخل دایره.</p>
        <div class="formula">A =  π * r²</div>
    </div>

    <div class="card">
        <h2>۲. کمان (Arc) چیست؟</h2>
        <p>بخشی از محیط یک دایره است که بین دو نقطه قرار دارد. اندازه کمان به شعاع دایره و زاویه مرکزی بستگی دارد.</p>
        <p><strong>طول کمان (بر حسب درجه):</strong></p>
        <div class="formula">Arc Length = (θ / 360) * 2 * π * r</div>
    </div>

    <div class="card">
        <h2>۳. ماشین حساب آنلاین کمان و دایره</h2>
        <div class="grid">
            <div>
                <label>شعاع دایره (r):</label>
                <input type="number" id="radius" value="5">
            </div>
            <div>
                <label>زاویه کمان به درجه (θ):</label>
                <input type="number" id="angle" value="90">
            </div>
            <button onclick="calculate()">محاسبه مقادیر</button>
        </div>
        <div id="result"></div>
    </div>
</div>

<script>
    function calculate() {
        const r = parseFloat(document.getElementById('radius').value);
        const theta = parseFloat(document.getElementById('angle').value);
        
        if (isNaN(r) || isNaN(theta) || r <= 0 || theta <= 0) {
            document.getElementById('result').innerHTML = "لطفاً مقادیر معتبر وارد کنید.";
            return;
        }

        const pi = Math.PI;
        const circumference = 2 * pi * r;
        const area = pi * Math.pow(r, 2);
        const arcLength = (theta / 360) * circumference;

        document.getElementById('result').innerHTML = `
            🔹 محیط دایره: ${circumference.toFixed(2)}<br>
            🔹 مساحت دایره: ${area.toFixed(2)}<br>
            🔸 طول کمان: ${arcLength.toFixed(2)}
        `;
    }
</script>

</body>
</html>
