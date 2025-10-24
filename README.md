<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DigiQash Agencies</title>
    <style>
        /* Basic CSS Styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
        }
        header {
            background: #5098d1;
            color: white;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: 3px solid #3D78BB;
        }
        header a {
            color: #ffffff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            margin: 0;
            list-style: none;
            overflow: hidden;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        .selector {
            margin-bottom: 20px;
        }
        .summary {
            border: 1px solid #ddd;
            padding: 10px;
            margin-top: 10px;
            background-color: white;
        }
        .button {
            background-color: #5098d1;
            color: white;
            padding: 10px 15px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        .button:hover {
            background-color: #3D78BB;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1>DigiQash Agencies</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Services</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="container">
        <div class="selector">
            <label for="country">Select Country:</label>
            <select id="country">
                <option value="">Select a Country</option>
                <option value="kenya">Kenya</option>
                <option value="cameroon">Cameroon</option>
                <option value="ghana">Ghana</option>
                <option value="uganda">Uganda</option>
                <option value="malawi">Malawi</option>
            </select>
        </div>

        <button class="button" id="registrationButton">Register Here</button>

        <div id="summaryDisplay" class="summary" style="display:none;">
            <h2>Summary for <span id="selectedCountry"></span></h2>
            <p id="countrySummary"></p>
        </div>
    </div>

    <script>
        // JavaScript to handle country selection and display summary
        const countrySelector = document.getElementById('country');
        const summaryDisplay = document.getElementById('summaryDisplay');
        const selectedCountry = document.getElementById('selectedCountry');
        const countrySummary = document.getElementById('countrySummary');
        const registrationButton = document.getElementById('registrationButton');

        // Registration Link (to be provided)
        const registrationLink = 'https://wa.me/254117410138?text=Hello%20am%20interested%20in%20Digiqashagencies';

        registrationButton.addEventListener('click', function() {
            window.location.href = registrationLink;
        });

        const countrySummaries = {
            kenya: '<div class="summary"><h2>DigiQash Agencies Summary - Kenya</h2><p>To be officially launched on <strong>1st November</strong> at 11:00 am.</p><p>Once you register your account, you can earn over Ksh 2,000 daily by completing simple tasks from your account.</p><h3>Ways to Earn:</h3><ul><li>Welcome bonus of KSH100 instantly credited upon activation.</li><li>Answering easy survey questions.</li><li>Watch TikTok videos uploaded to your dashboard.</li><li>Watch YouTube videos.</li><li>Create and share memes.</li><li>Watch Instagram Reels.</li><li>Write blogs.</li><li>Invite friends and earn up to KSH 1500 daily across 3 levels:<ul><li>Level 1 – KSH 300</li><li>Level 2 – KSH 100</li><li>Level 3 – KSH 50</li></ul></li><li>Earn extra bonuses from your Uplines through daily and weekly rewards.</li></ul><p>To join, register and activate your account with <strong>ksh 500 paid once</strong> in a lifetime.</p></div>',
            cameroon: '<div class="summary"><h2>DigiQash Agencies Summary - Cameroon</h2><p>To be officially launched on <strong>1st November</strong> at 9:00 am.</p><p>Once you register your account, you can earn over XAF 11,000 daily by completing simple tasks from your account.</p><h3>Ways to Earn:</h3><ul><li>Welcome bonus of xaf 650 instantly credited upon activation.</li><li>Answering easy survey questions.</li><li>Watch TikTok videos uploaded to your dashboard.</li><li>Watch YouTube videos.</li><li>Create and share memes.</li><li>Watch Instagram Reels.</li><li>Write blogs.</li><li>Invite friends and earn up to xaf 10,000 daily across 3 levels:<ul><li>Level 1 – XAF 1300</li><li>Level 2 – XAF 650</li><li>Level 3 – XAF 2000</li></ul></li><li>Earn extra bonuses from your Uplines through daily and weekly rewards.</li></ul><p>To join, register and activate your account with <strong>xaf 2900 paid once</strong> in a lifetime.</p></div>',
            ghana: '<div class="summary"><h2>DigiQash Agencies Summary - Ghana</h2><p>To be officially launched on <strong>1st November</strong> at 8:00 am.</p><p>Once you register your account, you can earn over ghs 250 daily by completing simple tasks from your account.</p><h3>Ways to Earn:</h3><ul><li>Welcome bonus of ghs 15 instantly credited upon activation.</li><li>Answering easy survey questions.</li><li>Watch TikTok videos uploaded to your dashboard.</li><li>Watch YouTube videos.</li><li>Create and share memes.</li><li>Watch Instagram Reels.</li><li>Write blogs.</li><li>Invite friends and earn up to GHS 200 daily across 3 levels:<ul><li>Level 1 – GHS 35</li><li>Level 2 – GHS 15</li><li>Level 3 – GHS 5</li></ul></li><li>Earn extra bonuses from your Uplines through daily and weekly rewards.</li></ul><p>To join, register and activate your account with <strong>Ghs 70 paid once</strong> in a lifetime.</p></div>',
            uganda: '<div class="summary"><h2>DigiQash Agencies Summary - Uganda</h2><p>To be officially launched on <strong>1st November</strong> at 11:00 am.</p><p>Once you register your account, you can earn over UGX 40,000 daily by completing simple tasks from your account.</p><h3>Ways to Earn:</h3><ul><li>Welcome bonus of UGX 4050 instantly credited upon activation.</li><li>Answering easy survey questions.</li><li>Watch TikTok videos uploaded to your dashboard.</li><li>Watch YouTube videos.</li><li>Create and share memes.</li><li>Watch Instagram Reels.</li><li>Write blogs.</li><li>Invite friends and earn up to UGX 30,000 daily across 3 levels:<ul><li>Level 1 – UGX 9,450</li><li>Level 2 – UGX 4,050</li><li>Level 3 – ugx 1,350</li></ul></li><li>Earn extra bonuses from your Uplines through daily and weekly rewards.</li></ul><p>To join, register and activate your account with <strong>UGX 18,500 paid once</strong> in a lifetime.</p></div>',
            malawi: '<div class="summary"><h2>DigiQash Agencies Summary - Malawi</h2><p>To be officially launched on <strong>1st November</strong> at 10:00 am.</p><p>Once you register your account, you can earn over 40,000 daily by completing simple tasks from your account.</p><h3>Ways to Earn:</h3><ul><li>Welcome bonus of 3,000 instantly credited upon activation.</li><li>Answering easy survey questions.</li><li>Watch TikTok videos uploaded to your dashboard.</li><li>Watch YouTube videos.</li><li>Create and share memes.</li><li>Watch Instagram Reels.</li><li>Write blogs.</li><li>Invite friends and earn up to MWK 30,000 daily across 3 levels:<ul><li>Level 1 – MWK 7,600</li><li>Level 2 – MWK 3,800</li></ul></li><li>Earn extra bonuses from your Uplines through daily and weekly rewards.</li></ul><p>To join, register and activate your account with <strong>MWK 15,000 paid once</strong> in a lifetime.</p></div>',
        };

        countrySelector.addEventListener('change', function() {
            const selected = countrySelector.value;
            if (selected) {
                selectedCountry.textContent = selected.charAt(0).toUpperCase() + selected.slice(1);
                countrySummary.innerHTML = countrySummaries[selected];
                summaryDisplay.style.display = 'block';
            } else {
                summaryDisplay.style.display = 'none';
            }
        });
    </script>
</body>
</html>
