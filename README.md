<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sayyam's Clan</title>
    <style>
        /* General Reset and Body Styling */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            background: linear-gradient(to bottom, #141E30, #243B55);
            color: #f0f0f0;
            overflow-x: hidden;
        }
        header {
            background: linear-gradient(to right, #4e54c8, #8f94fb);
            text-align: center;
            padding: 60px 20px;
            color: white;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.3);
        }
        header h1 {
            font-size: 3rem;
        }
        nav {
            position: sticky;
            top: 0;
            z-index: 1000;
            background-color: #2a2d3e;
            padding: 15px 20px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav a {
            text-decoration: none;
            color: #a8dadc;
            font-size: 1rem;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #ffba08;
        }
        section {
            padding: 50px 20px;
            margin: 20px auto;
            max-width: 1200px;
        }
        h2 {
            font-size: 2.5rem;
            color: #ffba08;
            text-align: center;
            margin-bottom: 30px;
        }
        .card-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .card {
            background: #1d3557;
            color: #f0f0f0;
            border-radius: 8px;
            padding: 20px;
            text-align: center;
            box-shadow: 0px 6px 15px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0px 8px 20px rgba(0, 0, 0, 0.3);
        }
        .card a {
            text-decoration: none;
            color: #ffba08;
            font-weight: bold;
            font-size: 1.1rem;
        }
        .card p {
            font-size: 0.9rem;
            margin-top: 10px;
        }
        footer {
            text-align: center;
            background: #1d3557;
            color: #f0f0f0;
            padding: 15px;
            margin-top: 20px;
            font-size: 0.9rem;
        }
        /* Welcome Popup Styling */
        .popup {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.8);
            display: flex;
            justify-content: center;
            align-items: center;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.5s ease, visibility 0.5s ease;
        }
        .popup.active {
            opacity: 1;
            visibility: visible;
        }
        .popup-content {
            background: #4e54c8;
            padding: 40px;
            border-radius: 10px;
            text-align: center;
            color: #fff;
            box-shadow: 0px 6px 15px rgba(0, 0, 0, 0.3);
        }
        .popup-content h1 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        .popup-content button {
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            background: #ffba08;
            color: #333;
            font-weight: bold;
            cursor: pointer;
            transition: background 0.3s;
        }
        .popup-content button:hover {
            background: #f48c06;
        }
    </style>
</head>
<body>
    <div class="popup" id="welcomePopup">
        <div class="popup-content">
            <h1>Welcome to Sayyam's Clan!</h1>
            <p>Explore the best projects and opportunities curated just for you.</p>
            <button onclick="closePopup()">Enter</button>
        </div>
    </div>
    <header>
        <h1>Sayyam's Clan</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#finance">Finance</a></li>
            <li><a href="#play">Play & Win</a></li>
            <li><a href="#investment">Investments</a></li>
            <li><a href="#shopping">Shopping Deals</a></li>
            <li><a href="#services">Additional Services</a></li>
        </ul>
    </nav>
    <section id="finance">
        <h2>💳 Financial Opportunities</h2>
        <div class="card-container">
            
            <div class="card">
                <a href="https://funngro.page.link/2ogx">Kotak 811</a>
                <p>Start your banking journey today.</p>
            </div>
            <div class="card">
                <a href="https://funngro.page.link/PAAc">AngelOne</a>
                <p>Sign up and enjoy exclusive perks.</p>
            </div>
            <div class="card">
                <a href="https://funngro.page.link/VLuo">Upstox Account</a>
                <p>Take your investments to the next level.</p>
            </div>
            <div class="card">
                <a href="https://funngro.page.link/HwKq">PayZapp</a>
                <p>Empower your cashless transactions today.</p>
            </div>
            <!-- Additional financial projects can be added here -->
        </div>
    </section>
    <section id="play">
        <h2>🏆 Play & Win</h2>
        <div class="card-container">
            <div class="card">
                <a href="https://funngro.page.link/8dUY">Paytm Ludo</a>
                <p>Enjoy gaming while exploring rewards.</p>
            </div>
            <div class="card">
                <a href="https://funngro.page.link/XskJ">MPL PRO</a>
                <p>Show your skills and participate in exciting games.</p>
            </div>
            <div class="card">
                <a href="https://funngro.page.link/fzNK">Sixer</a>
                <p>Play cricket and earn exciting rewards.</p>
            </div>
            <div class="card">
                <a href="https://funngro.page.link/rxUV">Gameplay - Myteam11</a>
                <p> Build your team and rise to the top..</p>
            </div>
            <div class="card">
                <a href="https://funngro.page.link/KhYS">Tento App promotion</a>
                <p>Game On,   Anything.</p>
            </div>
            <div class="card">
                <a href="https://funngro.page.link/JVv9">Stan</a>
                <p> Watch More.Feel More</p>
            </div>
    
            <!-- Additional gaming projects can be added here -->
        </div>
    </section>
    <section id="investment">
        <h2>💰 Investment Opportunities</h2>
        <div class="card-container">
            <div class="card">
                <a href="https://funngro.page.link/ZLRV">Jar - Buy Gold</a>
                <p>Invest in gold and grow your wealth.</p>
            </div>
            <div class="card">
                <a href="https://funngro.page.link/vxf6">Tide Account</a>
                <p>Open your account to explore benefits.</p>
            </div>
           
            <!-- Additional investment projects can be added here -->
        </div>
    </section>
    <section id="shopping">
        <h2>🛍️ Best Shopping Deals</h2>
        <div class="card-container">
            <div class="card">
                <a href="https://funngro.page.link/ex67">Myntra</a>
                <p>Shop for the best fashion deals.</p>
            </div>
            <div class="card">
                <a href="https://funngro.page.link/DeUs">AJIO</a>
                <p>Trendy fashion at amazing prices.</p>
            </div>
            <div class="card">
                <a href="https://funngro.page.link/hyq4">Flipkart</a>
                <p>Unmissable shopping offers await you.</p>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 Sayyam's Clan. All Rights Reserved.</p>
    </footer>
    <script>
        const popup = document.getElementById("welcomePopup");
        
        window.onload = function() {
            popup.classList.add("active");
        };

        function closePopup() {
            popup.classList.remove("active");
        }
    </script>
    <section id="services">
        <h2>🔧 Additional Services</h2>
        <div class="card-container">
            <div class="card">
                <a href="https://meet.google.com/coc-sdqk-tvp">Rework Meeting</a>
                <p>Join for discussions about refining and improving your projects.</p>
            </div>
            <div class="card">
                <a href="https://meet.google.com/cfw-epmg-upu">New User Meeting</a>
                <p>Get guidance on how to complete this project effectively.</p>
            </div>
            <!-- Add more services here if needed -->
        </div>
    </section>
</body>
</html>
