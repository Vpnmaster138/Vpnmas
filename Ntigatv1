<!DOCTYPE html>
<html lang="sw">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NtigaTV | VPN Master</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header, footer {
            background-color: #003366;
            color: red;
            text-align: center;
            padding: 15px;
        }
        .container {
            max-width: 600px;
            margin: 30px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        input, select, button {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .hidden {
            display: none;
        }
        .link {
            color: #4CAF50;
            text-decoration: none;
        }
        .dashboard-card {
            background: #e0f7fa;
            margin-top: 15px;
            padding: 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>

<header>
    <h1>Karibu NtigaTV</h1>
</header>

<!-- Login Section -->
<section id="login-section" class="container">
    <h2>Ingia kwenye Akaunti</h2>
    <form id="login-form">
        <label for="email">Barua Pepe:</label>
        <input type="email" id="email" required placeholder="Ingiza barua pepe yako">

        <label for="password">Neno la Siri:</label>
        <input type="password" id="password" required placeholder="Ingiza neno la siri">

        <label for="phone">Namba ya Simu:</label>
        <div style="display: flex;">
            <select required style="width: 30%; margin-right: 5px;">
                <option value="+255">+255</option>
                <option value="+254">+254</option>
                <option value="+256">+256</option>
            </select>
            <input type="tel" required placeholder="Namba ya simu" style="width: 70%;">
        </div>

        <button type="submit">Ingia</button>
        <p style="text-align:center; margin-top:10px;">
            <a href="https://youtube.com/@ntigatv" class="link" target="_blank">Ingia bila kujaza</a>
        </p>
        <p style="text-align:center;">Huna akaunti? <a href="#" class="link">Jisajili</a></p>
    </form>
</section>

<!-- VPN Master Section -->
<section id="vpn-section" class="container hidden">
    <h2>VPN MASTER</h2>
    <p><strong>Developer:</strong> MR.IT a.k.a VPN Master The Future Man</p>
    <p><strong>Kazi:</strong> Inakupa internet bure kupitia njia za siri</p>
    <p><strong>Tools:</strong> TLS, HTTP, SSL, DNS, na UDP</p>
    <p><strong>Network:</strong> Free Internet Provider</p>
    <button onclick="goToDashboard()">Nenda kwenye Dashboard</button>
    <button onclick="logout()">Toka</button>
</section>

<!-- Dashboard Section -->
<section id="dashboard-section" class="container hidden">
    <h2>Dashboard</h2>
    <div class="dashboard-card"><strong>Watumiaji:</strong> 1,234</div>
    <div class="dashboard-card"><strong>Bonus:</strong> TZS 120,000</div>
    <div class="dashboard-card"><strong>Withdrawals:</strong> TZS 75,000</div>
    <div class="dashboard-card"><strong>Referral Links:</strong> <a href="#">ntigapesa.com/ref/yourcode</a></div>
    <button onclick="goToVPN()">Rudi VPN MASTER</button>
    <button onclick="logout()">Toka</button>
</section>

<footer>
    <p>&copy; 2025 NtigaTV | VPN Master</p>
</footer>

<script>
    const loginForm = document.getElementById('login-form');
    const loginSection = document.getElementById('login-section');
    const vpnSection = document.getElementById('vpn-section');
    const dashboardSection = document.getElementById('dashboard-section');

    loginForm.addEventListener('submit', function(e) {
        e.preventDefault();
        loginSection.classList.add('hidden');
        vpnSection.classList.remove('hidden');
    });

    function goToDashboard() {
        vpnSection.classList.add('hidden');
        dashboardSection.classList.remove('hidden');
    }

    function goToVPN() {
        dashboardSection.classList.add('hidden');
        vpnSection.classList.remove('hidden');
    }

    function logout() {
        vpnSection.classList.add('hidden');
        dashboardSection.classList.add('hidden');
        loginSection.classList.remove('hidden');
    }
</script>

</body>
</html>
