<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Terms & Conditions - MarketMind</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" />
    <style>
        :root {
            --font-family: 'Poppins', sans-serif;
            --primary-color: #7B1FA2; /* Deep Purple */
            --secondary-color: #BA68C8; /* Light Purple */
            --background-light: #F4F6F9; /* Off-White Background */
            --surface-light: #FFFFFF; /* White Cards */
            --text-primary-light: #2C3E50; 
            --text-secondary-light: #808B96; 
            --border-light: #E0E0E0; /* Subtle Border */
            --success: #27AE60; 
            --danger: #C0392B; 
            --info: #00BCD4; 
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: var(--font-family);
            background-color: var(--background-light);
            color: var(--text-primary-light);
            line-height: 1.7;
            -webkit-font-smoothing: antialiased;
        }

        #app {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }

        /* *** NEW: Translator container *** */
        #google_translate_element_wrapper {
            position: relative;
            text-align: right;
            margin-bottom: 10px;
        }
        #google_translate_element {
            display: inline-block;
            background-color: var(--surface-light);
            padding: 5px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        /* Hide Google's top frame */
        .skiptranslate iframe {
            display: none !important;
        }
        body {
            top: 0 !important; /* Fix for Google Translate adding top margin */
        }
        /* *** END NEW *** */

        header {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            margin-bottom: 30px;
            box-shadow: 0 8px 20px rgba(123, 31, 162, 0.3);
        }

        header h1 {
            font-size: 2rem;
            margin-bottom: 5px;
        }

        header p {
            font-size: 1rem;
            opacity: 0.9;
        }

        .card {
            background-color: var(--surface-light);
            border-radius: 15px;
            padding: 25px;
            margin-bottom: 20px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.05);
            opacity: 0;
            transform: translateY(20px);
            animation: slideInUp 0.6s ease-out forwards;
        }

        /* Staggered animation delay for cards */
        .card:nth-child(2) { animation-delay: 0.1s; }
        .card:nth-child(3) { animation-delay: 0.2s; }
        .card:nth-child(4) { animation-delay: 0.3s; }
        .card:nth-child(5) { animation-delay: 0.4s; }
        .card:nth-child(6) { animation-delay: 0.5s; }
        .card:nth-child(7) { animation-delay: 0.6s; }
        .card:nth-child(8) { animation-delay: 0.7s; }
        .card:nth-child(9) { animation-delay: 0.8s; }
        .card:nth-child(10) { animation-delay: 0.9s; }


        @keyframes slideInUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .card h2 {
            font-size: 1.4rem;
            color: var(--primary-color);
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .card h3 {
            font-size: 1.1rem;
            color: var(--text-primary-light);
            margin-top: 15px;
            margin-bottom: 10px;
        }

        .card p {
            font-size: 0.95rem;
            margin-bottom: 15px;
        }

        .card ul {
            padding-left: 20px;
        }

        .card li {
            font-size: 0.95rem;
            margin-bottom: 10px;
        }

        .card strong {
            color: var(--text-primary-light);
            font-weight: 600;
        }

        .highlight-danger {
            color: var(--danger);
            font-weight: 700;
        }

        .highlight-success {
            color: var(--success);
            font-weight: 700;
        }

        .highlight-info {
            color: var(--info);
            font-weight: 700;
        }

        footer {
            text-align: center;
            margin-top: 30px;
            font-size: 0.9rem;
            color: var(--text-secondary-light);
        }
    </style>
</head>
<body>

    <div id="app">
        <!-- *** NEW: Google Translate Element *** -->
        <div id="google_translate_element_wrapper">
            <div id="google_translate_element"></div>
        </div>
        <!-- *** END NEW *** -->

        <header>
            <h1><i class="fas fa-file-signature"></i> MarketMind</h1>
            <p>Terms & Conditions of Service</p>
        </header>

        <main>
            <div class="card">
                <h2><i class="fas fa-gavel"></i> 1. Introduction & Acceptance</h2>
                <p>Welcome to MarketMind ("the Platform"). These Terms and Conditions ("Terms") govern your use of our web application and all associated services. By creating an account or using our services, you agree to be bound by these Terms in full. If you disagree with any part of these terms, you must not use our platform.</p>
                <p>We reserve the right to modify these Terms at any time. All changes will be posted on this page, and your continued use of the platform constitutes acceptance of those changes.</p>
            </div>

            <div class="card">
                <h2><i class="fas fa-user-shield"></i> 2. User Account & Security</h2>
                <h3>2.1. Eligibility</h3>
                <p>You must be at least 18 years of age to use our services. By creating an account, you represent and warrant that you meet this requirement.</p>
                
                <h3>2.2. Account Security</h3>
                <p>You are responsible for maintaining the confidentiality of your account information. You are fully responsible for all activities that occur under your account.</p>

                <h3>2.3. Security PIN (Critical)</h3>
                <p>To enhance the security of your funds, you are required to set a <strong>4-digit Security PIN</strong>. This PIN is mandatory for performing all withdrawal and transfer operations.</p>
                <ul>
                    <li>You are solely responsible for remembering your Security PIN.</li>
                    <li><strong>We do not store your PIN in a readable format and cannot recover it for you.</strong> If you forget your PIN, you may be required to go through a rigorous identity verification process, which is not guaranteed to succeed.</li>
                </ul>
            </div>

            <div class="card">
                <h2><i class="fas fa-money-bill-transfer"></i> 3. Financial Transactions</h2>
                <h3>3.1. Deposits</h3>
                <p>Deposits made to the platform are credited to your <strong>Main Balance</strong>. You agree to provide accurate transaction details (e.g., TXID) for all deposits. We are not responsible for funds lost due to incorrect information provided by you. Deposit approval times are subject to network confirmations and manual review.</p>

                <h3>3.2. Withdrawals</h3>
                <p>Withdrawals are processed from your <strong>Main Balance</strong>. All withdrawal requests are subject to verification and require your valid Security PIN. We reserve the right to set minimum withdrawal amounts and referral prerequisites, as specified in the "Withdraw" section of the app.</p>

                <h3>3.3. Transfers</h3>
                <p>You may transfer funds from your <strong>Main Balance</strong> to another user's <strong>Main Balance</strong>. All transfers are final and irreversible. This action also requires your Security PIN for confirmation.</p>
            </div>

            <div class="card">
                <h2><i class="fas fa-chart-line"></i> 4. Investment Plans</h2>
                <p>Investment plans are purchased using funds from your <strong>Main Balance</strong>. Each plan has a fixed duration, price, and total return amount.</p>
                <ul>
                    <li>The total return (which includes your principal amount plus profit) is credited to your <strong>Main Balance</strong> only *after* the plan's duration is complete.</li>
                    <li>You must manually click the "Claim" button to receive your funds after maturity. Funds are not credited automatically.</li>
                </ul>
            </div>

            <div class="card">
                <h2><i class="fas fa-lock"></i> 5. Savings Vault (Staking)</h2>
                <p>The Savings Vault allows you to "stake" or lock funds from your <strong>Main Balance</strong> for a fixed duration in exchange for a specified interest rate.</p>
                
                <h3>5.1. Maturity & Release</h3>
                <p>Staked funds and their accrued interest are returned to your <strong>Main Balance</strong> upon maturity. You must manually click the "Release" button to claim your matured funds.</p>

                <h3>5.2. Breaking a Stake (Penalty)</h3>
                <p>You have the option to "Break Stake" and withdraw your principal amount before the maturity date. However, if you choose this option, you will be subject to a penalty:</p>
                <ul>
                    <li>You will receive <strong>only your initial principal amount</strong> back to your Main Balance.</li>
                    <li>All interest accrued up to that point will be <strong class="highlight-danger">100% FORFEITED</strong>.</li>
                </ul>
                <p>By using the "Break Stake" feature, you explicitly agree to this penalty.</p>
            </div>

            <div class="card">
                <h2><i class="fas fa-users"></i> 6. Referral Program (MLM)</h2>
                <p>Our platform features a 3-level referral program. You can earn bonuses from users you directly invite (Level 1), users they invite (Level 2), and users invited by your Level 2 referrals (Level 3).</p>
                <ul>
                    <li>Referral bonuses are automatically credited to your <strong>Main Balance</strong>.</li>
                    <li>The creation of fake accounts, self-referrals, or any form of system abuse to gain referral bonuses is strictly prohibited.</li>
                    <li>Such fraudulent activity will result in the <strong class="highlight-danger">immediate and permanent suspension</strong> of all associated accounts and forfeiture of all funds.</li>
                </ul>
            </div>

            <div class="card">
                <h2><i class="fas fa-ban"></i> 7. Prohibited Conduct & Termination</h2>
                <p>We reserve the right to suspend or terminate your account, freeze your funds, and block your access to the platform without notice if we find, in our sole discretion, that you have:</p>
                <ul>
                    <li>Violated any of these Terms.</li>
                    <li>Engaged in fraudulent or illegal activities.</li>
                    <li>Attempted to abuse the referral, staking, or bonus systems.</li>
                    <li>Provided false or misleading information.</li>
                </ul>
            </div>

            <div class="card">
                <h2><i class="fas fa-shield-alt"></i> 8. Disclaimers & Limitation of Liability</h2>
                <p>All investments carry risk. MarketMind does not guarantee any profit or return. Past performance is not an indicator of future results. You acknowledge that you are using the platform at your own risk.</p>
                <p>We are not a licensed financial advisor. All information provided on the platform is for informational purposes only and should not be construed as financial advice.</p>
                <p>To the fullest extent permitted by law, MarketMind shall not be liable for any direct, indirect, incidental, or consequential damages resulting from the use or inability to use our services.</p>
            </div>
        </main>

        <footer>
            <p>&copy; 2025 MarketMind. All rights reserved.</p>
        </footer>
    </div>

    <!-- *** NEW: Google Translate Script *** -->
    <script type_modules="text/javascript">
        function googleTranslateElementInit() {
            new google.translate.TranslateElement({
                pageLanguage: 'en',
                layout: google.translate.TranslateElement.InlineLayout.SIMPLE
            }, 'google_translate_element');
        }
    </script>
    <script type_modules="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>
    <!-- *** END NEW *** -->

</body>
</html>

