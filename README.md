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
<!-- ======================================================= -->
<!-- ARC LAYER 1 FEATURES & SOCIALS (ADD TO THE BOTTOM)     -->
<!-- ======================================================= -->

<!-- Arc L1 Features Section -->
<section id="arc-l1-features" style="padding: 60px 20px; background-color: #111928; color: #ffffff; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;">
    <div style="max-width: 1200px; margin: 0 auto; text-align: center;">
        <h2 style="font-size: 2.5rem; color: #3b82f6; margin-bottom: 20px; font-weight: bold;">Gas Revolution with Arc Layer 1</h2>
        <p style="font-size: 1.1rem; color: #9ca3af; max-width: 800px; margin: 0 auto 50px auto; line-height: 1.8;">
            Arc is an independent, EVM-compatible Layer 1 blockchain developed by Circle to act as the "financial operating system of the internet." Its core breakthrough is stabilizing transaction economics using the world's most trusted digital dollar.
        </p>
        
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 30px; text-align: left;">
            <!-- Feature 1 -->
            <div style="background: #1f2937; padding: 30px; border-radius: 12px; border: 1px solid #374151; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);">
                <div style="font-size: 2rem; margin-bottom: 15px;">💵</div>
                <h3 style="font-size: 1.4rem; color: #ffffff; margin-bottom: 10px;">Native USDC Gas Fees</h3>
                <p style="color: #9ca3af; font-size: 0.95rem; line-height: 1.6;">
                    Eliminate the friction of holding volatile ecosystem tokens like ETH just to pay for transactions. On Arc Layer 1, all gas fees are paid directly and natively in **USDC**.
                </p>
            </div>

            <!-- Feature 2 -->
            <div style="background: #1f2937; padding: 30px; border-radius: 12px; border: 1px solid #374151; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);">
                <div style="font-size: 2rem; margin-bottom: 15px;">📈</div>
                <h3 style="font-size: 1.4rem; color: #ffffff; margin-bottom: 10px;">Predictable Cost Models</h3>
                <p style="color: #9ca3af; font-size: 0.95rem; line-height: 1.6;">
                    Built on stablecoin architecture, developers and enterprises can forecast operational overhead in exact fiat metrics, avoiding network spikes and fee volatility.
                </p>
            </div>

            <!-- Feature 3 -->
            <div style="background: #1f2937; padding: 30px; border-radius: 12px; border: 1px solid #374151; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);">
                <div style="font-size: 2rem; margin-bottom: 15px;">⚡</div>
                <h3 style="font-size: 1.4rem; color: #ffffff; margin-bottom: 10px;">Advanced Smoothing (EWMA)</h3>
                <p style="color: #9ca3af; font-size: 0.95rem; line-height: 1.6;">
                    Arc adapts the core logic of Ethereum's EIP-1559 base fee algorithm, utilizing an Exponentially Weighted Moving Average to isolate and smooth out brief market congestion spikes.
                </p>
            </div>
        </div>
    </div>
</section>

<!-- Social Connect Section -->
<section id="arc-socials" style="padding: 50px 20px; background-color: #0b0f19; text-align: center; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;">
    <h3 style="color: #ffffff; font-size: 1.8rem; margin-bottom: 10px;">Join the Architects Community</h3>
    <p style="color: #6b7280; font-size: 1rem; margin-bottom: 25px;">Stay updated with the official ecosystem channels for Arc and Circle.</p>
    
    <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
        <!-- Twitter (X) Button -->
        <a href="https://x.com" target="_blank" style="display: inline-flex; align-items: center; gap: 10px; background-color: #ffffff; color: #000000; padding: 12px 24px; border-radius: 30px; font-weight: bold; text-decoration: none; transition: transform 0.2s; box-shadow: 0 4px 6px rgba(255,255,255,0.1);">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="currentColor">
                <path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/>
            </svg>
            Follow Arc on X
        </a>

        <!-- Discord Button -->
        <a href="https://arc.network" target="_blank" style="display: inline-flex; align-items: center; gap: 10px; background-color: #5865F2; color: #ffffff; padding: 12px 24px; border-radius: 30px; font-weight: bold; text-decoration: none; transition: transform 0.2s; box-shadow: 0 4px 6px rgba(88,101,242,0.2);">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="currentColor">
                <path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057a.082.082 0 0 0 .031.057 19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028c.462-.63.874-1.295 1.226-1.994.021-.041.001-.09-.041-.106a13.094 13.094 0 0 1-1.873-.894.077.077 0 0 1-.008-.128c.126-.093.252-.19.372-.287a.075.075 0 0 1 .077-.011c3.92 1.793 8.18 1.793 12.061 0a.073.073 0 0 1 .078.009c.12.099.246.195.373.289a.077.077 0 0 1-.006.127 12.298 12.298 0 0 1-1.873.894.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03zM8.02 15.33c-1.183 0-2.157-1.085-2.157-2.419 0-1.333.956-2.419 2.156-2.419 1.21 0 2.176 1.096 2.157 2.42 0 1.333-.956 2.418-2.156 2.418zm7.975 0c-1.183 0-2.157-1.085-2.157-2.419 0-1.333.955-2.419 2.156-2.419 1.21 0 2.176 1.096 2.157 2.42 0 1.333-.946 2.418-2.156 2.418z"/>
            </svg>
            Join Arc Discord
        </a>
    </div>
</section>
<!-- ======================================================= -->
<!-- ARC LAYER 1 FEATURES, ECOSYSTEM FOOTER & FLOATING HUB   -->
<!-- ======================================================= -->

<!-- Main CSS Animations -->
<style>
    .arc-card {
        background: #1f2937;
        padding: 30px;
        border-radius: 12px;
        border: 1px solid #374151;
        box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
        transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
    }
    .arc-card:hover {
        transform: translateY(-8px);
        border-color: #3b82f6;
        box-shadow: 0 12px 20px -5px rgba(59, 130, 246, 0.3);
    }
    .footer-link {
        color: #9ca3af;
        text-decoration: none;
        position: relative;
        transition: color 0.25s ease;
        padding-bottom: 2px;
    }
    .footer-link:hover {
        color: #ffffff;
    }
    .footer-link::after {
        content: '';
        position: absolute;
        width: 100%;
        transform: scaleX(0);
        height: 2px;
        bottom: 0;
        left: 0;
        background-color: #3b82f6;
        transform-origin: bottom right;
        transition: transform 0.25s ease-out;
    }
    .footer-link:hover::after {
        transform: scaleX(1);
        transform-origin: bottom left;
    }
    .floating-support {
        position: fixed;
        bottom: 30px;
        right: 30px;
        background: linear-gradient(135deg, #3b82f6 0%, #1d4ed8 100%);
        color: white;
        padding: 14px 24px;
        border-radius: 50px;
        box-shadow: 0 10px 25px -5px rgba(59, 130, 246, 0.5);
        text-decoration: none;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
        font-weight: bold;
        font-size: 0.95rem;
        display: flex;
        align-items: center;
        gap: 10px;
        z-index: 9999;
        transition: all 0.3s ease;
    }
    .floating-support:hover {
        transform: scale(1.05) translateY(-3px);
        box-shadow: 0 15px 30px -5px rgba(59, 130, 246, 0.7);
    }
</style>

<!-- Arc L1 Features Section -->
<section id="arc-l1-features" style="padding: 80px 20px; background-color: #111928; color: #ffffff; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;">
    <div style="max-width: 1200px; margin: 0 auto; text-align: center;">
        <h2 style="font-size: 2.5rem; color: #3b82f6; margin-bottom: 20px; font-weight: bold;">Gas Revolution with Arc Layer 1</h2>
        <p style="font-size: 1.1rem; color: #9ca3af; max-width: 800px; margin: 0 auto 50px auto; line-height: 1.8;">
            Arc is an independent, EVM-compatible Layer 1 blockchain developed by Circle to act as the "financial operating system of the internet." Its core breakthrough is stabilizing transaction economics using the world's most trusted digital dollar.
        </p>
        
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 30px; text-align: left;">
            <!-- Feature 1 -->
            <div class="arc-card">
                <div style="font-size: 2rem; margin-bottom: 15px;">💵</div>
                <h3 style="font-size: 1.4rem; color: #ffffff; margin-bottom: 10px;">Native USDC Gas Fees</h3>
                <p style="color: #9ca3af; font-size: 0.95rem; line-height: 1.6;">
                    Eliminate the friction of holding volatile ecosystem tokens like ETH just to pay for transactions. On Arc Layer 1, all gas fees are paid directly and natively in **USDC**.
                </p>
            </div>

            <!-- Feature 2 -->
            <div class="arc-card">
                <div style="font-size: 2rem; margin-bottom: 15px;">📈</div>
                <h3 style="font-size: 1.4rem; color: #ffffff; margin-bottom: 10px;">Predictable Cost Models</h3>
                <p style="color: #9ca3af; font-size: 0.95rem; line-height: 1.6;">
                    Built on stablecoin architecture, developers and enterprises can forecast operational overhead in exact fiat metrics, avoiding network spikes and fee volatility.
                </p>
            </div>

            <!-- Feature 3 -->
            <div class="arc-card">
                <div style="font-size: 2rem; margin-bottom: 15px;">⚡</div>
                <h3 style="font-size: 1.4rem; color: #ffffff; margin-bottom: 10px;">Advanced Smoothing (EWMA)</h3>
                <p style="color: #9ca3af; font-size: 0.95rem; line-height: 1.6;">
                    Arc adapts the core logic of Ethereum's EIP-1559 base fee algorithm, utilizing an Exponentially Weighted Moving Average to isolate and smooth out brief market congestion spikes.
                </p>
            </div>
        </div>
    </div>
</section>

<!-- Official Hub Footer -->
<footer style="background-color: #0b0f19; color: #ffffff; padding: 60px 20px 30px 20px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif; border-top: 1px solid #1f2937; text-align: left;">
    <div style="max-width: 1200px; margin: 0 auto; display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 40px; margin-bottom: 40px;">
        
        <!-- Column 1: Ecosystem Socials -->
        <div>
            <h4 style="color: #3b82f6; font-size: 1.1rem; margin-bottom: 20px; font-weight: bold; text-transform: uppercase; letter-spacing: 0.05em;">Community</h4>
            <ul style="list-style: none; padding: 0; margin: 0;">
                <li style="margin-bottom: 12px;"><a href="https://x.com" target="_blank" class="footer-link">X / Twitter</a></li>
                <li style="margin-bottom: 12px;"><a href="https://discord.gg" target="_blank" class="footer-link">Discord</a></li>
                <li style="margin-bottom: 12px;"><a href="https://youtube.com" target="_blank" class="footer-link">YouTube</a></li>
            </ul>
        </div>

        <!-- Column 2: Core Websites -->
        <div>
            <h4 style="color: #3b82f6; font-size: 1.1rem; margin-bottom: 20px; font-weight: bold; text-transform: uppercase; letter-spacing: 0.05em;">Websites</h4>
            <ul style="list-style: none; padding: 0; margin: 0;">
                <li style="margin-bottom: 12px;"><a href="https://arc.network" target="_blank" class="footer-link">Arc Network</a></li>
                <li style="margin-bottom: 12px;"><a href="https://circle.com" target="_blank" class="footer-link">Circle Official</a></li>
                <li style="margin-bottom: 12px;"><a href="https://usdc.com" target="_blank" class="footer-link">USDC Official</a></li>
            </ul>
        </div>

        <!-- Column 3: Resources & Tools -->
        <div>
            <h4 style="color: #3b82f6; font-size: 1.1rem; margin-bottom: 20px; font-weight: bold; text-transform: uppercase; letter-spacing: 0.05em;">Developers</h4>
            <ul style="list-style: none; padding: 0; margin: 0;">
                <li style="margin-bottom: 12px;"><a href="https://circle.com" target="_blank" class="footer-link">Circle Faucet</a></li>
            </ul>
        </div>

        <!-- Column 4: Support -->
        <div>
            <h4 style="color: #3b82f6; font-size: 1.1rem; margin-bottom: 20px; font-weight: bold; text-transform: uppercase; letter-spacing: 0.05em;">Support</h4>
            <ul style="list-style: none; padding: 0; margin: 0;">
                <li style="margin-bottom: 12px;"><a href="https://circle.com" target="_blank" class="footer-link">Help Center</a></li>
                <li style="margin-bottom: 12px;"><a href="https://circle.coms/submit-ticket" target="_blank" class="footer-link">Submit a Ticket</a></li>
            </ul>
        </div>

    </div>

    <!-- Bottom Copyright Note -->
    <div style="max-width: 1200px; margin: 0 auto; border-top: 1px solid #1f2937; padding-top: 20px; text-align: center; color: #4b5563; font-size: 0.85rem;">
        <p>This is an informational website hub for Arc and Circle ecosystems. All rights reserved to their respective owners.</p>
    </div>
</footer>

<!-- Interactive Floating Support Button -->
<a href="https://circle.coms/submit-ticket" target="_blank" class="floating-support">
    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round">
        <path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"></path>
    </svg>
    Support Ticket
</a>
<!-- ======================================================= -->
<!--   ARC & CIRCLE ULTIMATE HUB UPGRADE (ADD TO THE BOTTOM)  -->
<!-- ======================================================= -->

<!-- Styles for Sticky Navbar, Animations, Calculator & Status -->
<style>
    /* Reset & CSS Variables for this block */
    :root {
        --arc-blue: #3b82f6;
        --arc-dark-bg: #0b0f19;
        --arc-card-bg: #1f2937;
        --arc-green: #10b981;
    }

    /* Scroll Reveal Base Animations */
    .reveal-on-scroll {
        opacity: 0;
        transform: translateY(30px);
        transition: opacity 0.8s ease-out, transform 0.8s ease-out;
    }
    .reveal-on-scroll.active {
        opacity: 1;
        transform: translateY(0);
    }

    /* Sticky Navbar */
    .arc-navbar {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        background-color: rgba(11, 15, 25, 0.9);
        backdrop-filter: blur(12px);
        -webkit-backdrop-filter: blur(12px);
        border-bottom: 1px solid #1f2937;
        z-index: 10000;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
        box-sizing: border-box;
    }
    .nav-container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 15px 20px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .nav-logo {
        color: #ffffff;
        font-size: 1.4rem;
        font-weight: 800;
        text-decoration: none;
        display: flex;
        align-items: center;
        gap: 8px;
    }
    .nav-logo span {
        color: var(--arc-blue);
    }
    .nav-menu {
        display: flex;
        gap: 25px;
        list-style: none;
        margin: 0;
        padding: 0;
    }
    .nav-link {
        color: #9ca3af;
        text-decoration: none;
        font-size: 0.95rem;
        font-weight: 500;
        transition: color 0.25s ease;
    }
    .nav-link:hover {
        color: #ffffff;
    }
    .nav-cta {
        background-color: var(--arc-blue);
        color: #ffffff;
        padding: 8px 18px;
        border-radius: 20px;
        font-weight: 600;
        transition: background-color 0.25s ease;
    }
    .nav-cta:hover {
        background-color: #2563eb;
    }

    /* Live Network Status Indicator */
    .status-badge {
        display: inline-flex;
        align-items: center;
        gap: 8px;
        background-color: rgba(16, 185, 129, 0.1);
        border: 1px solid rgba(16, 185, 129, 0.2);
        color: var(--arc-green);
        padding: 6px 14px;
        border-radius: 20px;
        font-size: 0.85rem;
        font-weight: 600;
        margin-bottom: 20px;
    }
    .ping-dot {
        width: 8px;
        height: 8px;
        background-color: var(--arc-green);
        border-radius: 50%;
        position: relative;
    }
    .ping-dot::after {
        content: '';
        position: absolute;
        width: 100%;
        height: 100%;
        background-color: var(--arc-green);
        border-radius: 50%;
        animation: ping 1.5s cubic-bezier(0, 0, 0.2, 1) infinite;
        top: 0;
        left: 0;
    }
    @keyframes ping {
        75%, 100% {
            transform: scale(2.5);
            opacity: 0;
        }
    }

    /* Gas Calculator Section */
    .calc-container {
        background: var(--arc-card-bg);
        border: 1px solid #374151;
        border-radius: 16px;
        padding: 40px;
        max-width: 600px;
        margin: 0 auto;
        box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        text-align: left;
    }
    .calc-group {
        margin-bottom: 25px;
    }
    .calc-label {
        display: block;
        color: #9ca3af;
        font-size: 0.9rem;
        margin-bottom: 8px;
        font-weight: 500;
    }
    .calc-input {
        width: 100%;
        background: #111928;
        border: 1px solid #4b5563;
        border-radius: 8px;
        padding: 12px;
        color: #ffffff;
        font-size: 1rem;
        box-sizing: border-box;
        outline: none;
        transition: border-color 0.25s ease;
    }
    .calc-input:focus {
        border-color: var(--arc-blue);
    }
    .result-box {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 20px;
        margin-top: 30px;
        padding-top: 25px;
        border-top: 1px solid #374151;
    }
    .res-card {
        padding: 15px;
        border-radius: 8px;
        text-align: center;
    }
    .res-eth { background-color: rgba(239, 68, 68, 0.1); border: 1px solid rgba(239, 68, 68, 0.2); }
    .res-arc { background-color: rgba(59, 130, 246, 0.1); border: 1px solid rgba(59, 130, 246, 0.2); }

    /* Fix body margin to avoid navbar overlap */
    body {
        margin-top: 70px !important;
    }

    /* Mobile Menu Toggle */
    .menu-toggle {
        display: none;
        flex-direction: column;
        gap: 5px;
        cursor: pointer;
    }
    .menu-toggle span {
        width: 25px;
        height: 3px;
        background-color: white;
        border-radius: 2px;
    }

    @media (max-width: 768px) {
        .nav-menu {
            display: none;
            flex-direction: column;
            position: absolute;
            top: 65px;
            left: 0;
            width: 100%;
            background-color: var(--arc-dark-bg);
            padding: 20px;
            box-sizing: border-box;
            border-bottom: 1px solid #1f2937;
            gap: 15px;
        }
        .nav-menu.mobile-open {
            display: flex;
        }
        .menu-toggle {
            display: flex;
        }
        .result-box {
            grid-template-columns: 1fr;
        }
    }
</style>

<!-- 1. STICKY NAVBAR COMPONENT -->
<nav class="arc-navbar">
    <div class="nav-container">
        <a href="https://arc.network" target="_blank" class="nav-logo">
            Arc<span>Circle</span>
        </a>
        <div class="menu-toggle" id="mobile-toggle">
            <span></span>
            <span></span>
            <span></span>
        </div>
        <ul class="nav-menu" id="nav-links">
            <li><a href="#arc-l1-features" class="nav-link">L1 Features</a></li>
            <li><a href="#gas-calculator" class="nav-link">Gas Saver</a></li>
            <li><a href="https://circle.com" target="_blank" class="nav-link">Circle Faucet</a></li>
            <li><a href="https://circle.com" target="_blank" class="nav-link">Help Center</a></li>
            <li><a href="https://usdc.com" target="_blank" class="nav-cta">Explore USDC</a></li>
        </ul>
    </div>
</nav>

<!-- 2. NETWORK STATUS & LIVE GAS CALCULATOR SECTION -->
<section id="gas-calculator" style="padding: 80px 20px; background-color: #0b0f19; color: #ffffff; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif; text-align: center;">
    <div style="max-width: 1200px; margin: 0 auto;" class="reveal-on-scroll">
        
        <!-- Live Network Status Indicator -->
        <div class="status-badge">
            <span class="ping-dot"></span>
            Arc L1 Mainnet & Circle Services: Fully Operational
        </div>

        <h2 style="font-size: 2.5rem; color: #ffffff; margin-bottom: 15px; font-weight: bold;">Arc Interactive Gas Calculator</h2>
        <p style="color: #9ca3af; max-width: 600px; margin: 0 auto 45px auto; font-size: 1.05rem; line-height: 1.6;">
            See the raw financial difference. Arc Layer 1 completely eliminates unpredictable spikes by using flat, native USDC fee architectures.
        </p>

        <!-- Calculator UI Container -->
        <div class="calc-container">
            <div class="calc-group">
                <label class="calc-label" for="tx-count">Estimated Monthly Transactions</label>
                <input type="number" id="tx-count" class="calc-input" value="1000" min="1">
            </div>

            <div class="calc-group">
                <label class="calc-label" for="tx-type">Transaction Type Complexity</label>
                <select id="tx-type" class="calc-input">
                    <option value="1">Standard Wallet Transfer (Simple Send)</option>
                    <option value="3">Smart Contract Interaction (DeFi Swap)</option>
                    <option value="5">Complex Enterprise Batch / NFT Mint</option>
                </select>
            </div>

            <div class="result-box">
                <div class="res-card res-eth">
                    <div style="color: #ef4444; font-size: 0.85rem; font-weight: bold; text-transform: uppercase;">Standard EVM Network</div>
                    <div id="eth-gas" style="font-size: 1.8rem; font-weight: bold; margin: 10px 0; color: #ffffff;">$2,500.00</div>
                    <div style="color: #9ca3af; font-size: 0.8rem;">Volatile Fees (Paid in ETH)</div>
                </div>
                <div class="res-card res-arc">
                    <div style="color: #3b82f6; font-size: 0.85rem; font-weight: bold; text-transform: uppercase;">Arc Layer 1 Ecosystem</div>
                    <div id="arc-gas" style="font-size: 1.8rem; font-weight: bold; margin: 10px 0; color: #3b82f6;">$10.00</div>
                    <div style="color: #9ca3af; font-size: 0.8rem;">Stable Pricing (Paid in USDC)</div>
                </div>
            </div>
            
            <div style="margin-top: 20px; text-align: center; color: #10b981; font-weight: 600; font-size: 0.95rem;" id="savings-text">
                🎉 Total Estimated Savings: $2,490.00 per month
            </div>
        </div>

    </div>
</section>

<!-- 3. SCROLL REVEAL & INTERACTIVE CALCULATOR JAVASCRIPT ENGINE -->
<script>
    // 1. Live Calculator Logic
    const txInput = document.getElementById('tx-count');
    const typeInput = document.getElementById('tx-type');
    const ethGasOutput = document.getElementById('eth-gas');
    const arcGasOutput = document.getElementById('arc-gas');
    const savingsOutput = document.getElementById('savings-text');

    function calculateGasSavings() {
        const txCount = parseFloat(txInput.value) || 0;
        const complexity = parseFloat(typeInput.value);

        // Simulated benchmark variables
        const ethAverageBaseFee = 2.50; // Average cost baseline in USD equivalent
        const arcFlatBaseFee = 0.01;    // Arc ultra-low predictable baseline in USDC

        const totalEthCost = txCount * complexity * ethAverageBaseFee;
        const totalArcCost = txCount * complexity * arcFlatBaseFee;
        const totalSavings = totalEthCost - totalArcCost;

        // Render values
        ethGasOutput.innerText = '$' + totalEthCost.toLocaleString('en-US', { minimumFractionDigits: 2, maximumFractionDigits: 2 });
        arcGasOutput.innerText = '$' + totalArcCost.toLocaleString('en-US', { minimumFractionDigits: 2, maximumFractionDigits: 2 });
        savingsOutput.innerText = `🎉 Total Estimated Savings: $${totalSavings.toLocaleString('en-US', { minimumFractionDigits: 2, maximumFractionDigits: 2 })} per month`;
    }

    txInput.addEventListener('input', calculateGasSavings);
    typeInput.addEventListener('change', calculateGasSavings);
    
    // Initial run on mount
    calculateGasSavings();

    // 2. Mobile Navbar Menu Toggle 
    const mobileToggle = document.getElementById('mobile-toggle');
    const navLinks = document.getElementById('nav-links');

    mobileToggle.addEventListener('click', () => {
        navLinks.classList.toggle('mobile-open');
    });

    // Close menu when clicking any link
    document.querySelectorAll('.nav-link, .nav-cta').forEach(link => {
        link.addEventListener('click', () => {
            navLinks.classList.remove('mobile-open');
        });
    });

    // 3. Scroll Reveal Animation Logic
    const revealElements = document.querySelectorAll('.reveal-on-scroll');
    
    // Also include previous arc layout cards if present
    const externalCards = document.querySelectorAll('.arc-card');
    externalCards.forEach(card => card.classList.add('reveal-on-scroll'));

    const allRevealables = document.querySelectorAll('.reveal-on-scroll');

    function checkReveal() {
        const triggerBottom = window.innerHeight * 0.85;
        allRevealables.forEach(el => {
            const elTop = el.getBoundingClientRect().top;
            if (elTop < triggerBottom) {
                el.classList.add('active');
            }
        });
    }

    window.addEventListener('scroll', checkReveal);
    // Initial trigger check
    checkReveal();
</script>
<!-- ======================================================= -->
<!--      ARC PRELOADER & GRAPHICAL COMPARISON UPGRADE        -->
<!-- ======================================================= -->

<!-- Styling for Preloader & Graphic Chart Component -->
<style>
    /* 1. Preloader Screen Styles */
    #arc-preloader {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: #0b0f19;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        z-index: 999999;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
        transition: opacity 0.6s cubic-bezier(0.4, 0, 0.2, 1), visibility 0.6s;
    }
    .loader-logo {
        font-size: 2.2rem;
        font-weight: 800;
        color: #ffffff;
        margin-bottom: 20px;
        letter-spacing: 1px;
    }
    .loader-logo span {
        color: #3b82f6;
    }
    .loader-bar-bg {
        width: 200px;
        height: 4px;
        background-color: #1f2937;
        border-radius: 10px;
        overflow: hidden;
        position: relative;
    }
    .loader-bar-fill {
        width: 0%;
        height: 100%;
        background: linear-gradient(90deg, #3b82f6, #10b981);
        border-radius: 10px;
        animation: loadProgress 1.8s cubic-bezier(0.4, 0, 0.2, 1) forwards;
    }
    @keyframes loadProgress {
        0% { width: 0%; }
        50% { width: 70%; }
        100% { width: 100%; }
    }

    /* 2. Visual Comparison Chart Styles */
    .chart-box {
        background: #1f2937;
        border: 1px solid #374151;
        border-radius: 16px;
        padding: 40px;
        max-width: 800px;
        margin: 50px auto 0 auto;
        box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        text-align: left;
    }
    .chart-wrapper {
        display: flex;
        flex-direction: column;
        gap: 25px;
        margin-top: 35px;
    }
    .chart-row {
        display: grid;
        grid-template-columns: 140px 1fr;
        align-items: center;
        gap: 15px;
    }
    .network-label {
        font-weight: 600;
        font-size: 0.95rem;
        color: #e5e7eb;
    }
    .bar-container {
        width: 100%;
        background-color: #111928;
        border-radius: 8px;
        height: 35px;
        position: relative;
        overflow: hidden;
    }
    .bar-fill {
        height: 100%;
        border-radius: 8px;
        display: flex;
        align-items: center;
        padding-left: 15px;
        font-weight: bold;
        font-size: 0.85rem;
        color: #ffffff;
        box-sizing: border-box;
        width: 0%;
        transition: width 1.5s cubic-bezier(0.4, 0, 0.2, 1);
    }
    .bar-eth {
        background: linear-gradient(90deg, #ef4444 0%, #b91c1c 100%);
    }
    .bar-arc {
        background: linear-gradient(90deg, #10b981 0%, #047857 100%);
    }
    
    /* Animation trigger via scroll reveal */
    .reveal-on-scroll.active .bar-eth-trigger { width: 95%; }
    .reveal-on-scroll.active .bar-arc-trigger { width: 3%; }

    @media (max-width: 600px) {
        .chart-row {
            grid-template-columns: 1fr;
            gap: 5px;
        }
        .chart-box {
            padding: 20px;
        }
    }
</style>

<!-- SECTION 1: ECOSYSTEM PRELOADER SCREEN -->
<div id="arc-preloader">
    <div class="loader-logo">Arc<span>Circle</span> Hub</div>
    <div class="loader-bar-bg">
        <div class="loader-bar-fill"></div>
    </div>
    <p style="color: #4b5563; font-size: 0.85rem; margin-top: 15px; letter-spacing: 0.05em; font-weight: 500;">INITIALIZING SECURE L1 CONNECTION...</p>
</div>

<!-- SECTION 2: GRAPHICAL COMPARISON COMPONENT (APPENDED INSIDE CALCULATOR AREA) -->
<script>
    // Dynamically inject the Comparison Chart into the existing calculator container for layout perfection
    document.addEventListener("DOMContentLoaded", function() {
        const targetSection = document.getElementById('gas-calculator');
        if (targetSection) {
            const chartHTML = `
                <div class="chart-box reveal-on-scroll" style="margin-top: 60px;">
                    <div style="display: flex; justify-content: space-between; align-items: center; border-bottom: 1px solid #374151; padding-bottom: 15px; flex-wrap: wrap; gap: 10px;">
                        <h3 style="margin: 0; font-size: 1.3rem; color: #ffffff;">Network Fee Architecture Breakdown</h3>
                        <span style="background-color: rgba(59, 130, 246, 0.1); border: 1px solid rgba(59, 130, 246, 0.2); color: #3b82f6; font-size: 0.75rem; font-weight: bold; padding: 4px 10px; border-radius: 12px; text-transform: uppercase;">Visual Index</span>
                    </div>
                    
                    <p style="color: #9ca3af; font-size: 0.9rem; margin-top: 15px; line-height: 1.5;">
                        Traditional networks exponentialize costs based on volatile block congestion. Arc locks baseline parameters directly to stable, ultra-low USDC micro-values.
                    </p>

                    <div class="chart-wrapper">
                        <!-- Ethereum Row -->
                        <div class="chart-row">
                            <div class="network-label">Legacy EVM L1</div>
                            <div class="bar-container">
                                <div class="bar-fill bar-eth bar-eth-trigger">HIGH VOLATILITY ($1.50 - $45.00+)</div>
                            </div>
                        </div>

                        <!-- Arc Row -->
                        <div class="chart-row">
                            <div class="network-label" style="color: #10b981; font-weight: bold;">Arc Layer 1</div>
                            <div class="bar-container">
                                <div class="bar-fill bar-arc bar-arc-trigger">FLAT RATE ($0.01 USDC)</div>
                            </div>
                        </div>
                    </div>
                    
                    <div style="margin-top: 25px; font-size: 0.8rem; color: #6b7280; display: flex; justify-content: space-between;">
                        <span>* Baseline simulations assuming 35 Gwei standard EVM gas spikes.</span>
                        <span style="color: #10b981; font-weight: 500;">99.1% More Cost-Effective</span>
                    </div>
                </div>
            `;
            // Insert chart inside the section before the main element finishes
            targetSection.querySelector('.reveal-on-scroll').insertAdjacentHTML('beforeend', chartHTML);
        }
    });

    // Preloader Execution Engine
    window.addEventListener('load', function() {
        const preloader = document.getElementById('arc-preloader');
        // Smoothly fade out the loader view after 2.0s to let animation finish beautifully
        setTimeout(() => {
            preloader.style.opacity = '0';
            preloader.style.visibility = 'hidden';
            
            // Re-trigger scroll reveal evaluation check once layout settles
            if (typeof checkReveal === "function") {
                checkReveal();
            }
        }, 2000);
    });
</script>
<!-- بخش معرفی دانشمند هسته‌ای - اضافه شده به سایت -->
<div style="direction: rtl; font-family: 'Segoe UI', Tahoma, sans-serif; max-width: 450px; margin: 40px auto; border: 1px solid #2c2d30; border-radius: 16px; overflow: hidden; background-color: #111214; box-shadow: 0 8px 24px rgba(0,0,0,0.5); text-align: center;">
    <!-- تصویر حمید الله حسن -->
    <img src="hamidullah.jpg" alt="حمید الله حسن" style="width: 100%; height: auto; display: block; filter: brightness(0.95);">
    
    <!-- توضیحات متنی -->
    <div style="padding: 24px;">
        <h3 style="margin: 0 0 8px 0; color: #ffffff; font-size: 22px; font-weight: 600;">حمید الله حسن</h3>
        <p style="margin: 0; color: #9ca3af; font-size: 15px; line-height: 1.7; font-weight: 400;">
            یکی از دانشمندان هسته هرات مقیم غیبتان
        </p>
    </div>
</div>

