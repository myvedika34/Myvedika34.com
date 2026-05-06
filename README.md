<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>मेरी प्रोफेशनल वेबसाइट</title>
    <style>
        /* बेसिक स्टाइलिंग */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
        }
        header {
            background: #2c3e50;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
        }
        .services {
            display: flex;
            justify-content: space-around;
            text-align: center;
            margin-top: 20px;
        }
        .box {
            flex: 1;
            padding: 20px;
            margin: 10px;
            background: #f4f4f4;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        form {
            background: #fff;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ddd;
        }
        button {
            background: #2c3e50;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            width: 100%;
        }
        button:hover {
            background: #34495e;
        }
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 30px;
        }
    </style>
</head>
<body>

<header>
    <h1>वेबसाइट में आपका स्वागत है</h1>
    <p>बेहतरीन सर्विस और समाधान</p>
</header>

<div class="container">
    <section>
        <h2 style="text-align: center;">हमारी सेवाएँ</h2>
        <div class="services">
            <div class="box">
                <h3>तकनीकी सहायता</h3>
                <p>हम आपको हार्डवेयर और सॉफ्टवेयर से जुड़ी समस्याओं में मदद करते हैं।</p>
            </div>
            <div class="box">
                <h3>सुरक्षा समाधान</h3>
                <p>CCTV और अन्य सुरक्षा उपकरणों की सही जानकारी और सेटअप।</p>
            </div>
            <div class="box">
                <h3>मैनेजमेंट</h3>
                <p>डेटा और फाइनेंस को मैनेज करने के लिए आसान तरीके।</p>
            </div>
        </div>
    </section>

    <hr>

    <section>
        <h2 style="text-align: center;">संपर्क करें</h2>
        <form>
            <label>नाम:</label>
            <input type="text" placeholder="अपना नाम लिखें">
            <label>ईमेल:</label>
            <input type="email" placeholder="अपनी ईमेल आईडी लिखें">
            <label>संदेश:</label>
            <textarea rows="4" placeholder="आप क्या पूछना चाहते हैं?"></textarea>
            <button type="submit">सबमिट करें</button>
        </form>
    </section>
</div>

<footer>
    <p>&copy; 2026 मेरी वेबसाइट | राजस्थान</p>
</footer>

</body>
</html>
