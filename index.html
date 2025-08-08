<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AnonsenSocial</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background: white;
            color: #2563eb;
            overflow-x: hidden;
        }

        /* Header */
        .header {
            background: #2563eb;
            color: white;
            padding: 15px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(37, 99, 235, 0.3);
        }

        .menu-btn {
            background: none;
            border: none;
            color: white;
            font-size: 24px;
            cursor: pointer;
            padding: 5px;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            position: absolute;
            left: 50%;
            transform: translateX(-50%);
        }

        /* Sidebar */
        .sidebar {
            position: fixed;
            left: -300px;
            top: 0;
            width: 300px;
            height: 100vh;
            background: #2563eb;
            transition: left 0.3s ease;
            z-index: 1001;
            overflow-y: auto;
        }

        .sidebar.open {
            left: 0;
        }

        .sidebar-header {
            padding: 20px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.2);
        }

        .sidebar-item {
            padding: 15px 20px;
            color: white;
            cursor: pointer;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
            transition: background 0.3s;
        }

        .sidebar-item:hover {
            background: rgba(255, 255, 255, 0.1);
        }

        .sidebar-bottom {
            position: absolute;
            bottom: 0;
            width: 100%;
        }

        /* Main Content */
        .main-content {
            margin-top: 70px;
            min-height: calc(100vh - 140px);
            padding: 20px;
        }

        .search-bar {
            width: 100%;
            max-width: 800px;
            margin: 0 auto 30px;
            position: relative;
        }

        .search-input {
            width: 100%;
            padding: 15px 20px;
            border: 2px solid #2563eb;
            border-radius: 25px;
            font-size: 16px;
            outline: none;
        }

        .search-input:focus {
            box-shadow: 0 0 10px rgba(37, 99, 235, 0.3);
        }

        /* Video Grid */
        .video-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .video-card {
            background: white;
            border: 2px solid #2563eb;
            border-radius: 10px;
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .video-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(37, 99, 235, 0.2);
        }

        .video-thumbnail {
            width: 100%;
            height: 200px;
            background: linear-gradient(135deg, #e0e7ff, #c7d2fe);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 48px;
            color: #2563eb;
        }

        .video-info {
            padding: 15px;
        }

        .video-title {
            font-weight: bold;
            margin-bottom: 5px;
            color: #2563eb;
        }

        .video-meta {
            font-size: 14px;
            color: #6b7280;
        }

        .short-indicator {
            background: #2563eb;
            color: white;
            padding: 2px 8px;
            border-radius: 12px;
            font-size: 12px;
            display: inline-block;
            margin-bottom: 5px;
        }

        /* Footer Chat */
        .footer-chat {
            background: #2563eb;
            color: white;
            padding: 15px 20px;
            position: fixed;
            bottom: 0;
            width: 100%;
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .chat-icon {
            font-size: 24px;
        }

        .chat-input {
            flex: 1;
            padding: 10px 15px;
            border: none;
            border-radius: 20px;
            outline: none;
        }

        /* Finance Page */
        .finance-content {
            display: none;
            text-align: center;
        }

        .budget-circle {
            width: 300px;
            height: 300px;
            border-radius: 50%;
            border: 10px solid #2563eb;
            margin: 30px auto;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            position: relative;
        }

        .budget-amount {
            font-size: 24px;
            font-weight: bold;
            color: #2563eb;
        }

        .budget-input {
            margin-top: 10px;
            padding: 8px;
            border: 2px solid #2563eb;
            border-radius: 5px;
            text-align: center;
        }

        .finance-sections {
            display: flex;
            justify-content: space-around;
            margin-top: 40px;
            flex-wrap: wrap;
        }

        .finance-section {
            flex: 1;
            min-width: 300px;
            margin: 10px;
        }

        .section-title {
            font-size: 20px;
            font-weight: bold;
            color: #2563eb;
            margin-bottom: 15px;
        }

        .finance-item {
            display: flex;
            gap: 10px;
            margin-bottom: 10px;
            align-items: center;
        }

        .finance-input {
            flex: 1;
            padding: 10px;
            border: 2px solid #2563eb;
            border-radius: 5px;
        }

        .add-btn {
            background: #2563eb;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
        }

        .remove-btn {
            background: #dc2626;
            color: white;
            border: none;
            padding: 5px 10px;
            border-radius: 3px;
            cursor: pointer;
        }

        /* Profile Page */
        .profile-content {
            display: none;
            max-width: 600px;
            margin: 0 auto;
        }

        .profile-section {
            background: white;
            border: 2px solid #2563eb;
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 20px;
        }

        .profile-image {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 3px solid #2563eb;
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 48px;
            background: #e0e7ff;
            color: #2563eb;
        }

        .form-group {
            margin-bottom: 15px;
        }

        .form-label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
            color: #2563eb;
        }

        .form-input {
            width: 100%;
            padding: 10px;
            border: 2px solid #2563eb;
            border-radius: 5px;
            outline: none;
        }

        .btn {
            background: #2563eb;
            color: white;
            border: none;
            padding: 12px 24px;
            border-radius: 5px;
            cursor: pointer;
            margin-right: 10px;
        }

        .btn:hover {
            background: #1d4ed8;
        }

        .btn-secondary {
            background: white;
            color: #2563eb;
            border: 2px solid #2563eb;
        }

        .btn-secondary:hover {
            background: #2563eb;
            color: white;
        }

        /* Settings Page */
        .settings-content {
            display: none;
            max-width: 600px;
            margin: 0 auto;
        }

        .setting-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px;
            border-bottom: 1px solid #e5e7eb;
        }

        .toggle {
            width: 50px;
            height: 24px;
            background: #e5e7eb;
            border-radius: 12px;
            position: relative;
            cursor: pointer;
            transition: background 0.3s;
        }

        .toggle.active {
            background: #2563eb;
        }

        .toggle::before {
            content: '';
            position: absolute;
            width: 20px;
            height: 20px;
            border-radius: 50%;
            background: white;
            top: 2px;
            left: 2px;
            transition: transform 0.3s;
        }

        .toggle.active::before {
            transform: translateX(26px);
        }

        /* Overlay */
        .overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
            z-index: 999;
            display: none;
        }

        .overlay.show {
            display: block;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .video-grid {
                grid-template-columns: 1fr;
            }
            
            .finance-sections {
                flex-direction: column;
            }
            
            .budget-circle {
                width: 250px;
                height: 250px;
            }
        }
    </style>
</head>
<body>
    <!-- Overlay -->
    <div class="overlay" id="overlay"></div>

    <!-- Header -->
    <div class="header">
        <button class="menu-btn" id="menuBtn">☰</button>
        <div class="logo" id="pageTitle">AnonsenSocial</div>
    </div>

    <!-- Sidebar -->
    <div class="sidebar" id="sidebar">
        <div class="sidebar-header">
            <div class="logo">AnonsenSocial</div>
        </div>
        <div class="sidebar-item" onclick="switchPage('social')">🏠 AnonsenSocial</div>
        <div class="sidebar-item" onclick="switchPage('finance')">💰 AnonsenFinance</div>
        <div class="sidebar-bottom">
            <div class="sidebar-item" onclick="switchPage('profile')">👤 Profil</div>
            <div class="sidebar-item" onclick="switchPage('settings')">⚙️ Einstellungen</div>
        </div>
    </div>

    <!-- Main Content -->
    <div class="main-content">
        <!-- Social Media Page -->
        <div id="socialContent">
            <div class="search-bar">
                <input type="text" class="search-input" placeholder="Suche nach Videos, Shorts und mehr..." id="searchInput">
            </div>

            <div class="video-grid" id="videoGrid">
                <!-- Videos werden hier dynamisch geladen -->
            </div>
        </div>

        <!-- Finance Page -->
        <div id="financeContent" class="finance-content">
            <div class="budget-circle">
                <div class="budget-amount">Gesamtbudget</div>
                <input type="number" class="budget-input" id="budgetInput" placeholder="€ 0" value="1000">
                <div style="margin-top: 10px; font-size: 14px;" id="budgetStatus">Im Budget</div>
            </div>

            <div class="finance-sections">
                <div class="finance-section">
                    <div class="section-title">Einnahmen</div>
                    <div id="incomeList">
                        <div class="finance-item">
                            <input type="text" class="finance-input" placeholder="Beschreibung" value="Gehalt">
                            <input type="number" class="finance-input" placeholder="Betrag" value="2500">
                            <button class="remove-btn" onclick="removeFinanceItem(this)">✕</button>
                        </div>
                    </div>
                    <button class="add-btn" onclick="addFinanceItem('income')">+ Einnahme hinzufügen</button>
                </div>

                <div class="finance-section">
                    <div class="section-title">Ausgaben</div>
                    <div id="expenseList">
                        <div class="finance-item">
                            <input type="text" class="finance-input" placeholder="Beschreibung" value="Miete">
                            <input type="number" class="finance-input" placeholder="Betrag" value="800">
                            <button class="remove-btn" onclick="removeFinanceItem(this)">✕</button>
                        </div>
                        <div class="finance-item">
                            <input type="text" class="finance-input" placeholder="Beschreibung" value="Lebensmittel">
                            <input type="number" class="finance-input" placeholder="Betrag" value="300">
                            <button class="remove-btn" onclick="removeFinanceItem(this)">✕</button>
                        </div>
                    </div>
                    <button class="add-btn" onclick="addFinanceItem('expense')">+ Ausgabe hinzufügen</button>
                </div>
            </div>
        </div>

        <!-- Profile Page -->
        <div id="profileContent" class="profile-content">
            <div class="profile-section">
                <div class="profile-image" id="profileImage">👤</div>
                <div class="form-group">
                    <label class="form-label">Profilbild</label>
                    <input type="file" class="form-input" accept="image/*" onchange="handleProfileImage(this)">
                    <button class="btn-secondary" style="margin-top: 10px;">Aus Galerie wählen</button>
                </div>
            </div>

            <div class="profile-section">
                <div class="form-group">
                    <label class="form-label">Benutzername</label>
                    <input type="text" class="form-input" id="username" placeholder="Dein Benutzername" value="Gast">
                </div>
                <div class="form-group">
                    <label class="form-label">E-Mail</label>
                    <select class="form-input" id="emailProvider">
                        <option value="gmail">Gmail</option>
                        <option value="yahoo">Yahoo</option>
                        <option value="outlook">Outlook</option>
                        <option value="custom">Individuell</option>
                    </select>
                    <input type="email" class="form-input" id="email" placeholder="deine@email.com" style="margin-top: 10px;">
                </div>
                <div class="form-group">
                    <label class="form-label">Passwort</label>
                    <input type="password" class="form-input" id="password" placeholder="Mindestens 6 Zeichen">
                </div>
                <button class="btn">Profil speichern</button>
                <button class="btn-secondary">Abbrechen</button>
            </div>
        </div>

        <!-- Settings Page -->
        <div id="settingsContent" class="settings-content">
            <div class="profile-section">
                <div class="section-title">Einstellungen</div>
                
                <div class="setting-item">
                    <span>Dunkler Modus</span>
                    <div class="toggle" onclick="toggleSetting(this)"></div>
                </div>
                
                <div class="setting-item">
                    <span>Benachrichtigungen</span>
                    <div class="toggle active" onclick="toggleSetting(this)"></div>
                </div>
                
                <div class="setting-item">
                    <span>Automatische Wiedergabe</span>
                    <div class="toggle active" onclick="toggleSetting(this)"></div>
                </div>
                
                <div class="setting-item">
                    <span>Datensparmodus</span>
                    <div class="toggle" onclick="toggleSetting(this)"></div>
                </div>
                
                <div class="setting-item">
                    <span>Standort teilen</span>
                    <div class="toggle" onclick="toggleSetting(this)"></div>
                </div>
                
                <div class="setting-item">
                    <span>Privater Modus</span>
                    <div class="toggle" onclick="toggleSetting(this)"></div>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer Chat -->
    <div class="footer-chat">
        <div class="chat-icon">💬</div>
        <input type="text" class="chat-input" placeholder="Chatte mit anderen Benutzern..." id="chatInput">
        <button class="btn" onclick="sendMessage()">Senden</button>
    </div>

    <script>
        // Sample video data
        const videos = [
            { title: "Wie man perfekte Pasta kocht", type: "normal", views: "1.2M", time: "10:45" },
            { title: "Lustiger Hund tanzt", type: "short", views: "850K", time: "0:15" },
            { title: "JavaScript Tutorial für Anfänger", type: "normal", views: "523K", time: "25:30" },
            { title: "Schnelles Workout", type: "short", views: "1.8M", time: "0:30" },
            { title: "Reise nach Japan Vlog", type: "normal", views: "340K", time: "15:20" },
            { title: "Katze vs. Gurke", type: "short", views: "2.1M", time: "0:12" },
            { title: "DIY Heimwerker Tipps", type: "normal", views: "680K", time: "18:45" },
            { title: "Dance Challenge", type: "short", views: "920K", time: "0:28" },
            { title: "Fotografie Grundlagen", type: "normal", views: "445K", time: "22:15" },
            { title: "Lustige Fails", type: "short", views: "1.5M", time: "0:45" }
        ];

        // Initialize the app
        let currentPage = 'social';
        let isLoggedIn = false;

        function loadVideos() {
            const videoGrid = document.getElementById('videoGrid');
            videoGrid.innerHTML = '';

            // Show 10 shorts and 20 normal videos as requested
            let shortCount = 0;
            let normalCount = 0;
            let displayedVideos = [];

            videos.forEach(video => {
                if (video.type === 'short' && shortCount < 10) {
                    displayedVideos.push(video);
                    shortCount++;
                } else if (video.type === 'normal' && normalCount < 20) {
                    displayedVideos.push(video);
                    normalCount++;
                }
            });

            // Shuffle the array to mix shorts and normal videos
            displayedVideos.sort(() => Math.random() - 0.5);

            displayedVideos.forEach(video => {
                const videoCard = document.createElement('div');
                videoCard.className = 'video-card';
                videoCard.innerHTML = `
                    <div class="video-thumbnail">
                        ${video.type === 'short' ? '📱' : '🎥'}
                    </div>
                    <div class="video-info">
                        ${video.type === 'short' ? '<div class="short-indicator">Ansen</div>' : ''}
                        <div class="video-title">${video.title}</div>
                        <div class="video-meta">${video.views} Aufrufe • ${video.time}</div>
                    </div>
                `;
                videoGrid.appendChild(videoCard);
            });
        }

        function switchPage(page) {
            // Hide all content
            document.getElementById('socialContent').style.display = 'none';
            document.getElementById('financeContent').style.display = 'none';
            document.getElementById('profileContent').style.display = 'none';
            document.getElementById('settingsContent').style.display = 'none';

            // Show selected content
            switch(page) {
                case 'social':
                    document.getElementById('socialContent').style.display = 'block';
                    document.getElementById('pageTitle').textContent = 'AnonsenSocial';
                    break;
                case 'finance':
                    document.getElementById('financeContent').style.display = 'block';
                    document.getElementById('pageTitle').textContent = 'AnonsenFinance';
                    calculateBudget();
                    break;
                case 'profile':
                    document.getElementById('profileContent').style.display = 'block';
                    document.getElementById('pageTitle').textContent = 'Profil';
                    break;
                case 'settings':
                    document.getElementById('settingsContent').style.display = 'block';
                    document.getElementById('pageTitle').textContent = 'Einstellungen';
                    break;
            }

            currentPage = page;
            closeSidebar();
        }

        function toggleSidebar() {
            const sidebar = document.getElementById('sidebar');
            const overlay = document.getElementById('overlay');
            
            if (sidebar.classList.contains('open')) {
                closeSidebar();
            } else {
                sidebar.classList.add('open');
                overlay.classList.add('show');
            }
        }

        function closeSidebar() {
            const sidebar = document.getElementById('sidebar');
            const overlay = document.getElementById('overlay');
            sidebar.classList.remove('open');
            overlay.classList.remove('show');
        }

        function addFinanceItem(type) {
            const list = type === 'income' ? document.getElementById('incomeList') : document.getElementById('expenseList');
            const item = document.createElement('div');
            item.className = 'finance-item';
            item.innerHTML = `
                <input type="text" class="finance-input" placeholder="Beschreibung">
                <input type="number" class="finance-input" placeholder="Betrag">
                <button class="remove-btn" onclick="removeFinanceItem(this)">✕</button>
            `;
            list.appendChild(item);
            calculateBudget();
        }

        function removeFinanceItem(btn) {
            btn.parentElement.remove();
            calculateBudget();
        }

        function calculateBudget() {
            const budget = parseFloat(document.getElementById('budgetInput').value) || 0;
            let totalIncome = 0;
            let totalExpenses = 0;

            // Calculate income
            const incomeInputs = document.querySelectorAll('#incomeList .finance-input[type="number"]');
            incomeInputs.forEach(input => {
                totalIncome += parseFloat(input.value) || 0;
            });

            // Calculate expenses
            const expenseInputs = document.querySelectorAll('#expenseList .finance-input[type="number"]');
            expenseInputs.forEach(input => {
                totalExpenses += parseFloat(input.value) || 0;
            });

            const balance = totalIncome - totalExpenses;
            const statusElement = document.getElementById('budgetStatus');
            
            if (balance < 0) {
                statusElement.textContent = `Im Minus: €${Math.abs(balance).toFixed(2)}`;
                statusElement.style.color = '#dc2626';
            } else {
                statusElement.textContent = `Übrig: €${balance.toFixed(2)}`;
                statusElement.style.color = '#059669';
            }
        }

        function toggleSetting(toggle) {
            toggle.classList.toggle('active');
        }

        function handleProfileImage(input) {
            if (input.files && input.files[0]) {
                const reader = new FileReader();
                reader.onload = function(e) {
                    const profileImage = document.getElementById('profileImage');
                    profileImage.innerHTML = `<img src="${e.target.result}" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">`;
                };
                reader.readAsDataURL(input.files[0]);
            }
        }

        function sendMessage() {
            const chatInput = document.getElementById('chatInput');
            if (chatInput.value.trim()) {
                // Here you would typically send the message to a server
                alert('Nachricht gesendet: ' + chatInput.value);
                chatInput.value = '';
            }
        }

        // Event listeners
        document.getElementById('menuBtn').addEventListener('click', toggleSidebar);
        document.getElementById('overlay').addEventListener('click', closeSidebar);
        document.getElementById('budgetInput').addEventListener('input', calculateBudget);

        document.getElementById('searchInput').addEventListener('keypress', function(e) {
            if (e.key === 'Enter') {
                // Here you would filter videos based on search
                alert('Suche nach: ' + this.value);
            }
        });

        document.getElementById('chatInput').addEventListener('keypress', function(e) {
            if (e.key === 'Enter') {
                sendMessage();
            }
        });

        // Initialize the app
        loadVideos();
        calculateBudget();
    </script>
</body>
</html>
