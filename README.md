<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arc House | The Economic OS for the Internet</title>
    <style>
        :root {
            --bg-main: #090d16;
            --bg-sidebar: #0f1626;
            --bg-card: #141d30;
            --accent-blue: #00f2fe;
            --accent-purple: #4facfe;
            --text-main: #ffffff;
            --text-muted: #8493a8;
            --border: rgba(255, 255, 255, 0.05);
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            background-color: var(--bg-main);
            color: var(--text-main);
            margin: 0;
            padding: 0;
            display: flex;
        }
        /* Sidebar Layout */
        .sidebar {
            width: 260px;
            background-color: var(--bg-sidebar);
            height: 100vh;
            position: fixed;
            border-right: 1px solid var(--border);
            padding: 24px;
            box-sizing: border-box;
        }
        .logo-area {
            font-size: 1.3rem;
            font-weight: 700;
            letter-spacing: 1px;
            background: linear-gradient(135deg, var(--accent-blue), var(--accent-purple));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 40px;
        }
        .nav-links {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        .nav-links li {
            padding: 12px 16px;
            color: var(--text-muted);
            cursor: pointer;
            border-radius: 8px;
            margin-bottom: 8px;
            font-size: 0.95rem;
            transition: all 0.2s;
        }
        .nav-links li.active, .nav-links li:hover {
            background-color: rgba(255, 255, 255, 0.03);
            color: var(--text-main);
        }
        /* Main Content Layout */
        .main-content {
            margin-left: 260px;
            padding: 40px 60px;
            width: calc(100% - 260px);
            box-sizing: border-box;
        }
        .hero {
            max-width: 800px;
            margin-bottom: 50px;
        }
        .hero h1 {
            font-size: 2.5rem;
            font-weight: 800;
            margin: 0 0 16px 0;
            line-height: 1.2;
        }
        .hero p {
            color: var(--text-muted);
            font-size: 1.15rem;
            line-height: 1.6;
            margin: 0;
        }
        /* Dashboard Sections Grid */
        .section-title {
            font-size: 1.25rem;
            font-weight: 600;
            margin-bottom: 20px;
            color: var(--text-main);
            letter-spacing: 0.5px;
        }
        .grid-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 24px;
            margin-bottom: 40px;
        }
        .card {
            background-color: var(--bg-card);
            border: 1px solid var(--border);
            border-radius: 12px;
            padding: 24px;
            transition: transform 0.2s, border-color 0.2s;
        }
        .card:hover {
            transform: translateY(-2px);
            border-color: rgba(0, 242, 254, 0.3);
        }
        .card-tag {
            font-size: 0.75rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            color: var(--accent-blue);
            font-weight: 700;
            margin-bottom: 12px;
        }
        .card h3 {
            margin: 0 0 10px 0;
            font-size: 1.15rem;
            font-weight: 600;
        }
        .card p {
            color: var(--text-muted);
            font-size: 0.95rem;
            line-height: 1.5;
            margin: 0;
        }
        @media (max-width: 768px) {
            body { flex-direction: column; }
            .sidebar { width: 100%; height: auto; position: relative; border-right: none; border-bottom: 1px solid var(--border); }
            .main-content { margin-left: 0; width: 100%; padding: 24px; }
        }
    </style>
</head>
<body>

    <!-- Sidebar Navigation Section (community.arc.io structure) -->
    <div class="sidebar">
        <div class="logo-area">Arc House</div>
        <ul class="nav-links">
            <li class="active">Home</li>
            <li>Arc Discord</li>
            <li>Arc Docs</li>
            <li>Discussions</li>
            <li>Events</li>
            <li>Ecosystem</li>
        </ul>
    </div>

    <!-- Main Content Area -->
    <div class="main-content">
        <div class="hero">
            <h1>Building the Economic OS for the Internet</h1>
            <p>Join the global network of Architects reimagining how value moves. Arc is a stablecoin-native Layer-1 blockchain ecosystem engineered by Circle for internet-scale financial activity.</p>
        </div>

        <!-- Ecosystem Core Section -->
        <div class="section-title">Core Architecture</div>
        <div class="grid-container">
            <div class="card">
                <div class="card-tag">Circle Infrastructure</div>
                <h3>Powered by Circle</h3>
                <p>Circle, the issuer of USDC, stewards the core infrastructure of the Arc network, enabling frictionless global stablecoin liquidity integration from day one.</p>
            </div>
            <div class="card">
                <div class="card-tag">L1 Blockchain</div>
                <h3>The Economic OS</h3>
                <p>An open, EVM-compatible Layer-1 platform designed specifically for programmable value transfer, fast deterministic execution, and ultra-low fees.</p>
            </div>
        </div>

        <!-- Latest Blueprints and Applications Section -->
        <div class="section-title">Ecosystem Blueprints</div>
        <div class="grid-container">
            <div class="card">
                <div class="card-tag">Agentic Economy</div>
                <h3>AI-Driven Financial Flows</h3>
                <p>Arc is optimized to support AI agents executing automated on-chain micro-transactions safely using stablecoin-native infrastructure layers.</p>
            </div>
            <div class="card">
                <div class="card-tag">DeFi Systems</div>
                <h3>Lending & Borrowing</h3>
                <p>Unlocking instant capital efficiencies by combining native compliance standards, programmable smart contracts, and sub-second transaction finality.</p>
            </div>
        </div>
    </div>

</body>
</html>
