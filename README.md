[Untitled6.htm](https://github.com/user-attachments/files/23442098/Untitled6.htm)
<!doctype html>
<html lang="en">
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width,initial-scale=1" />
    <title>DEN OF FIRE ARMS</title>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Roboto&display=swap" rel="stylesheet">
    <style>
        :root{
            --bg1:#070707; --bg2:#202020; --accent:#ff2e2e; --muted:#bdbdbd;
            --card:#111; --glass: rgba(255,255,255,0.03);
        }
        *{box-sizing:border-box}
        body{margin:0; font-family:Roboto,Arial,sans-serif; background:linear-gradient(120deg,var(--bg1),var(--bg2)); color:#fff;}
        header.site{display:flex;align-items:center;justify-content:space-between;padding:16px 24px;border-bottom:1px solid rgba(255,255,255,0.03);position:sticky;top:0;background:linear-gradient(90deg, rgba(0,0,0,0.6), rgba(0,0,0,0.15));z-index:50}
        .brand{display:flex;gap:12px;align-items:center}
        .logo{width:56px;height:56px;background:var(--accent);display:flex;align-items:center;justify-content:center;font-weight:800;color:#111;border-radius:8px;font-family:Orbitron}
        h1{margin:0;font-size:1.05rem;font-family:Orbitron}
        nav.top{display:flex;gap:10px;align-items:center}
        nav.top a{color:var(--muted);text-decoration:none;padding:8px 12px;border-radius:8px;font-size:0.95rem}
        nav.top a.active,nav.top a:hover{background:var(--glass);color:#fff;border:1px solid rgba(255,255,255,0.03)}
        .contact{font-size:0.86rem;color:var(--muted)}
        main{padding:22px}
        .hero{display:flex;gap:18px;align-items:flex-start;margin-bottom:18px}
        .left{max-width:720px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:20px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}
        .meta{display:flex;gap:12px;align-items:center;margin-bottom:8px}
        .owner{font-weight:700;color:var(--accent);font-family:Orbitron}
        .actions{margin-top:12px;display:flex;gap:10px}
        .btn{background:var(--accent);color:#111;border:none;padding:10px 14px;border-radius:8px;cursor:pointer;font-weight:700}
        .btn.ghost{background:transparent;color:var(--muted);border:1px solid rgba(255,255,255,0.03)}
        .layout{display:grid;grid-template-columns:280px 1fr;gap:20px;align-items:start}
        .sidebar{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:14px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}
        .menu{display:flex;flex-direction:column;gap:8px}
        .menu button{background:transparent;border:0;text-align:left;padding:10px;color:var(--muted);border-radius:8px;cursor:pointer}
        .menu button.active,.menu button:hover{background:var(--glass);color:#fff}
        .section-title{font-size:0.95rem;color:var(--muted);margin-bottom:8px}
        .content-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(260px,1fr));gap:16px}
        .card{background:var(--card);padding:12px;border-radius:10px;border:1px solid rgba(255,255,255,0.03)}
        .card img.gun{width:100%;height:160px;object-fit:cover;border-radius:8px}
        .card img.pellet{width:100px;height:66px;object-fit:cover;border-radius:6px;border:1px solid rgba(255,255,255,0.04);margin-top:8px}
        .card h3{margin:10px 0 6px 0;font-size:1rem}
        .input,select{width:100%;padding:8px;margin-top:8px;border-radius:8px;border:1px solid rgba(255,255,255,0.06);background:transparent;color:#fff}
        .small{font-size:0.86rem;color:var(--muted)}
        .filters{display:flex;gap:8px;margin-bottom:12px;flex-wrap:wrap}
        .pill{background:rgba(255,255,255,0.03);padding:6px 10px;border-radius:999px;color:var(--muted);cursor:pointer}
        .pill.active{background:var(--accent);color:#111}
        table{width:100%;border-collapse:collapse}
        th,td{padding:10px;text-align:left;border-bottom:1px dashed rgba(255,255,255,0.03);font-size:0.95rem}
        footer{margin-top:18px;text-align:center;color:var(--muted);padding:16px 0}
        @media(max-width:900px){.layout{grid-template-columns:1fr}.hero{flex-direction:column}}
        .badge{background:rgba(255,255,255,0.04);padding:6px 10px;border-radius:8px;font-weight:700;color:var(--muted)}
    </style>
</head>
<body>
    <header class="site">
        <div class="brand">
            <div class="logo">DF</div>
            <div>
                <h1>DEN OF FIRE ARMS</h1>
                <div class="contact">Owner: <span class="owner">CHAUDARY HAMZA SHAFQAT GUJJAR</span></div>
            </div>
        </div>

        <nav class="top" aria-label="Main menu">
            <a href="#" data-target="home" class="active">Home</a>
            <a href="#" data-target="guns">Guns</a>
            <a href="#" data-target="bullets">Bullets</a>
            <a href="#" data-target="oils">Oils & Accessories</a>
            <a href="#" data-target="orders">Order Listings</a>
            <a href="#" data-target="faq">FAQ</a>
            <a href="#" id="loginBtn">Login</a>
        </nav>

        <div class="contact">📧 25-se-081@student.hitecuni.edu.pk | 📞 +92 332 5534567</div>
    </header>

    <main>
        <section class="hero">
            <div class="left">
                <div class="meta"><div class="badge">Premium Airguns</div><div class="small">Curated selection — local edits saved to browser</div></div>
                <h2 style="margin:6px 0 8px 0;font-family:Orbitron">DEN OF FIRE ARMS — Precision. Power. Pride.</h2>
                <p class="small">Browse guns, see pellet sizes, edit prices and delivery options, and manage demo orders. Replace local storage with a backend when ready.</p>
                <div class="actions">
                    <button class="btn" id="showGuns">Browse Guns</button>
                    <button class="btn ghost" id="showOrders">View Orders</button>
                </div>
            </div>

            <div style="width:360px">
                <div class="card" style="padding:14px">
                    <h3 style="margin:0 0 8px 0">Quick Data Editor</h3>
                    <div class="small">Edit price/delivery for demo items. Click Save to store locally.</div>
                    <input id="editSku" class="input" placeholder="SKU (e.g., gun-001)" />
                    <input id="editPrice" class="input" placeholder="Price (e.g., 1200 USD)" />
                    <select id="editDelivery" class="input">
                        <option>Standard</option>
                        <option>Express</option>
                        <option>Pickup</option>
                    </select>
                    <div style="display:flex;gap:8px;margin-top:8px">
                        <button class="btn" id="saveBtn">Save</button>
                        <button class="btn ghost" id="resetBtn">Reset Local</button>
                    </div>
                    <div style="margin-top:8px" class="small">Demo uses local browser storage. Add a server for shared persistence.</div>
                </div>
            </div>
        </section>

        <div class="layout">
            <aside class="sidebar">
                <div class="section-title">Site Menu</div>
                <div class="menu" id="sideMenu">
                    <button data-target="home" class="active">Home</button>
                    <button data-target="guns">Guns Catalog</button>
                    <button data-target="bullets">Bullets & Ammo</button>
                    <button data-target="oils">Oils & Accessories</button>
                    <button data-target="orders">Order Listings</button>
                    <button data-target="faq">FAQ</button>
                </div>

                <div style="margin-top:12px">
                    <div class="section-title">Filter by Range</div>
                    <div id="rangeFilters" class="menu" style="gap:6px">
                        <button class="pill" data-range="0-20">0–20 m (Close)</button>
                        <button class="pill" data-range="20-50">20–50 m (Short)</button>
                        <button class="pill" data-range="50-100">50–100 m (Medium)</button>
                        <button class="pill" data-range="100-200">100–200 m (Long)</button>
                        <button class="pill" data-range="200+">200+ m (Extreme)</button>
                        <button class="pill active" data-range="all">Show All</button>
                    </div>
                </div>

                <div style="margin-top:12px">
                    <div class="section-title">Quick Contact</div>
                    <div class="small">Owner: <strong>CHAUDARY HAMZA SHAFQAT GUJJAR</strong></div>
                    <div class="small">Email: 25-se-081@student.hitecuni.edu.pk</div>
                    <div class="small">Phone: +92 332 5534567</div>
                </div>
            </aside>

            <section class="main-content">
                <div id="panel-home" class="panel">
                    <div style="margin-bottom:12px">
                        <h2 style="margin:0 0 6px 0">Featured Guns</h2>
                        <div class="small">Tap a gun card to edit price and delivery locally</div>
                    </div>

                    <div class="filters" id="topFilters">
                        <div class="pill active" data-filter="all">All</div>
                        <div class="pill" data-filter="hunting">Hunting</div>
                        <div class="pill" data-filter="target">Target</div>
                        <div class="pill" data-filter="tactical">Tactical</div>
                        <div class="pill" data-filter="plinking">Plinking</div>
                    </div>

                    <div class="content-grid" id="gunsGrid"></div>
                </div>

                <div id="panel-guns" class="panel" style="display:none">
                    <h2>Guns Catalog (60)</h2>
                    <div class="small">Search, sort and edit. Add more items to gunsData in the script.</div>
                    <div style="margin:12px 0;display:flex;gap:8px;align-items:center;flex-wrap:wrap">
                        <input id="searchBox" class="input" placeholder="Search by name, SKU, or category" />
                        <select id="sortSelect" class="input" style="max-width:180px">
                            <option value="default">Sort: Featured</option>
                            <option value="price-asc">Price ascending</option>
                            <option value="price-desc">Price descending</option>
                        </select>
                    </div>
                    <div id="gunsList" class="content-grid"></div>
                </div>

                <div id="panel-bullets" class="panel" style="display:none">
                    <h2>Bullets & Ammo</h2>
                    <div class="card">
                        <h3>Ammo Types & Typical Use</h3>
                        <ul class="small">
                            <li><strong>.177 (4.5 mm)</strong> — target, plinking, short-range precision</li>
                            <li><strong>.22 (5.5 mm)</strong> — general hunting small game, better energy transfer</li>
                            <li><strong>.25 (6.35 mm)</strong> — larger small game, deeper penetration</li>
                            <li><strong>.30 (7.62 mm)</strong> — highest energy for long-range/specialized airguns</li>
                        </ul>
                    </div>
                </div>

                <div id="panel-oils" class="panel" style="display:none">
                    <h2>Oils & Accessories</h2>
                    <div class="card">
                        <h3>Maintenance Essentials</h3>
                        <ul class="small">
                            <li>Barrel cleaning kits; silicone-based oils for seals; gun-specific lubricants</li>
                            <li>Scope mounts; bipods; slings; cases and safes</li>
                            <li>Spare magazines, seals, o-rings and maintenance kits</li>
                        </ul>
                    </div>
                </div>

                <div id="panel-orders" class="panel" style="display:none">
                    <h2>Order Listings</h2>
                    <div class="card">
                        <table id="ordersTable">
                            <thead><tr><th>Order ID</th><th>SKU</th><th>Model</th><th>Price</th><th>Delivery</th><th>Status</th></tr></thead>
                            <tbody></tbody>
                        </table>
                        <div style="margin-top:10px" class="small">Demo orders stored locally. Integrate server for production.</div>
                    </div>
                </div>

                <div id="panel-faq" class="panel" style="display:none">
                    <h2>FAQ</h2>
                    <div class="card">
                        <h3>Suggested FAQ items</h3>
                        <ol class="small">
                            <li>What licenses or permits are required in my region to buy airguns?</li>
                            <li>How to choose pellet size for hunting different game?</li>
                            <li>Delivery options, shipping times and return policy</li>
                            <li>Maintenance routines and recommended oils</li>
                            <li>Warranty, repair and service information</li>
                        </ol>
                        <div class="small">Tailor legal FAQ to your jurisdiction and never provide instructions to bypass law.</div>
                    </div>
                </div>
            </section>
        </div>

        <footer>&copy; <span id="year"></span> DEN OF FIRE ARMS — Owner: <strong>CHAUDARY HAMZA SHAFQAT GUJJAR</strong></footer>
    </main>

    <!-- Login modal -->
    <div id="loginModal" aria-hidden="true" style="position:fixed;inset:0;display:none;align-items:center;justify-content:center;background:rgba(0,0,0,0.6);z-index:80">
        <div style="width:360px;background:#0f0f0f;padding:18px;border-radius:12px;border:1px solid rgba(255,255,255,0.04)">
            <h3 style="margin:0 0 8px 0">Login</h3>
            <div class="small">Demo login — replace with Firebase/Auth0/Custom server</div>
            <input id="loginEmail" class="input" placeholder="Email" />
            <input id="loginPass" type="password" class="input" placeholder="Password" />
            <div style="margin:10px 0;padding:10px;border-radius:8px;background:rgba(255,255,255,0.02);text-align:center" id="recaptchaPlaceholder">
                reCAPTCHA placeholder — add your Google site key here
            </div>
            <div style="display:flex;gap:8px;margin-top:8px">
                <button class="btn" id="doLogin">Login</button>
                <button class="btn ghost" id="closeLogin">Cancel</button>
            </div>
        </div>
    </div>

    <script>
        document.getElementById('year').textContent = new Date().getFullYear();

        const gunsData = [
            {"sku":"gun-001","name":"FX Crown MKII","category":"hunting","range":"50-100","price":"1800 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=FX+Crown+MKII","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-002","name":"FX Impact X MKII","category":"tactical","range":"100-200","price":"2200 USD","delivery":"Express","img":"https://via.placeholder.com/900x600.png?text=FX+Impact+X+MKII","pellet_size":"6.35 mm (.25)","pellet_image":"https://via.placeholder.com/300x200.png?text=.25+6.35mm"},
            {"sku":"gun-003","name":"FX Impact M3","category":"hunting","range":"50-100","price":"2100 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=FX+Impact+M3","pellet_size":"5.5 mm (.22)","pellet_image":"https://via.placeholder.com/300x200.png?text=.22+5.5mm"},
            {"sku":"gun-004","name":"Weihrauch HW100","category":"target","range":"20-50","price":"950 USD","delivery":"Pickup","img":"https://via.placeholder.com/900x600.png?text=Weihrauch+HW100","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-005","name":"Daystate Huntsman","category":"hunting","range":"100-200","price":"2500 USD","delivery":"Express","img":"https://via.placeholder.com/900x600.png?text=Daystate+Huntsman","pellet_size":"7.62 mm (.30)","pellet_image":"https://via.placeholder.com/300x200.png?text=.30+7.62mm"},
            {"sku":"gun-006","name":"Air Arms S510","category":"target","range":"20-50","price":"1250 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=Air+Arms+S510","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-007","name":"Weihrauch HW97K","category":"hunting","range":"50-100","price":"900 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=Weihrauch+HW97K","pellet_size":"5.5 mm (.22)","pellet_image":"https://via.placeholder.com/300x200.png?text=.22+5.5mm"},
            {"sku":"gun-008","name":"BSA R10","category":"target","range":"50-100","price":"1400 USD","delivery":"Express","img":"https://via.placeholder.com/900x600.png?text=BSA+R10","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-009","name":"HW50S","category":"plinking","range":"0-20","price":"420 USD","delivery":"Pickup","img":"https://via.placeholder.com/900x600.png?text=HW50S","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-010","name":"S410 Tactical","category":"tactical","range":"50-100","price":"1150 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=S410+Tactical","pellet_size":"5.5 mm (.22)","pellet_image":"https://via.placeholder.com/300x200.png?text=.22+5.5mm"},
            {"sku":"gun-011","name":"Steyr LG110","category":"target","range":"20-50","price":"2300 USD","delivery":"Express","img":"https://via.placeholder.com/900x600.png?text=Steyr+LG110","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-012","name":"FX Bobcat","category":"hunting","range":"50-100","price":"1600 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=FX+Bobcat","pellet_size":"5.5 mm (.22)","pellet_image":"https://via.placeholder.com/300x200.png?text=.22+5.5mm"},
            {"sku":"gun-013","name":"Kral Arms Puncher","category":"plinking","range":"0-20","price":"320 USD","delivery":"Pickup","img":"https://via.placeholder.com/900x600.png?text=Kral+Puncher","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-014","name":"Brocock Bantam","category":"hunting","range":"50-100","price":"1200 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=Brocock+Bantam","pellet_size":"5.5 mm (.22)","pellet_image":"https://via.placeholder.com/300x200.png?text=.22+5.5mm"},
            {"sku":"gun-015","name":"Hatsan 95","category":"plinking","range":"0-20","price":"210 USD","delivery":"Pickup","img":"https://via.placeholder.com/900x600.png?text=Hatsan+95","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-016","name":"Airforce Texan","category":"hunting","range":"100-200","price":"1700 USD","delivery":"Express","img":"https://via.placeholder.com/900x600.png?text=Airforce+Texan","pellet_size":"7.62 mm (.30)","pellet_image":"https://via.placeholder.com/300x200.png?text=.30+7.62mm"},
            {"sku":"gun-017","name":"Benjamin Marauder","category":"hunting","range":"50-100","price":"800 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=Benjamin+Marauder","pellet_size":"5.5 mm (.22)","pellet_image":"https://via.placeholder.com/300x200.png?text=.22+5.5mm"},
            {"sku":"gun-018","name":"Benjamin Discovery","category":"plinking","range":"0-20","price":"380 USD","delivery":"Pickup","img":"https://via.placeholder.com/900x600.png?text=Benjamin+Discovery","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-019","name":"FX Ranchero","category":"hunting","range":"50-100","price":"1500 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=FX+Ranchero","pellet_size":"6.35 mm (.25)","pellet_image":"https://via.placeholder.com/300x200.png?text=.25+6.35mm"},
            {"sku":"gun-020","name":"Cometa Fusion","category":"target","range":"20-50","price":"450 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=Cometa+Fusion","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-021","name":"Kral Puncher Jumbo","category":"hunting","range":"50-100","price":"950 USD","delivery":"Express","img":"https://via.placeholder.com/900x600.png?text=Kral+Puncher+Jumbo","pellet_size":"6.35 mm (.25)","pellet_image":"https://via.placeholder.com/300x200.png?text=.25+6.35mm"},
            {"sku":"gun-022","name":"Hatsan BT65","category":"hunting","range":"50-100","price":"420 USD","delivery":"Pickup","img":"https://via.placeholder.com/900x600.png?text=Hatsan+BT65","pellet_size":"5.5 mm (.22)","pellet_image":"https://via.placeholder.com/300x200.png?text=.22+5.5mm"},
            {"sku":"gun-023","name":"FX Maverick","category":"target","range":"20-50","price":"980 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=FX+Maverick","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-024","name":"Walther LGU","category":"target","range":"20-50","price":"1100 USD","delivery":"Express","img":"https://via.placeholder.com/900x600.png?text=Walther+LGU","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-025","name":"Air Arms TX200","category":"target","range":"20-50","price":"1350 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=Air+Arms+TX200","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-026","name":"FX Wildcat","category":"hunting","range":"50-100","price":"1450 USD","delivery":"Express","img":"https://via.placeholder.com/900x600.png?text=FX+Wildcat","pellet_size":"5.5 mm (.22)","pellet_image":"https://via.placeholder.com/300x200.png?text=.22+5.5mm"},
            {"sku":"gun-027","name":"Daystate Red Wolf","category":"hunting","range":"100-200","price":"2800 USD","delivery":"Express","img":"https://via.placeholder.com/900x600.png?text=Daystate+Red+Wolf","pellet_size":"6.35 mm (.25)","pellet_image":"https://via.placeholder.com/300x200.png?text=.25+6.35mm"},
            {"sku":"gun-028","name":"Weihrauch HW77","category":"target","range":"20-50","price":"760 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=Weihrauch+HW77","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-029","name":"Gamo Whisper","category":"plinking","range":"0-20","price":"260 USD","delivery":"Pickup","img":"https://via.placeholder.com/900x600.png?text=Gamo+Whisper","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-030","name":"Gamo Coyote","category":"hunting","range":"20-50","price":"300 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=Gamo+Coyote","pellet_size":"5.5 mm (.22)","pellet_image":"https://via.placeholder.com/300x200.png?text=.22+5.5mm"},
            {"sku":"gun-031","name":"Hatsan Flash","category":"plinking","range":"0-20","price":"180 USD","delivery":"Pickup","img":"https://via.placeholder.com/900x600.png?text=Hatsan+Flash","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-032","name":"Benjamin Trail NP","category":"plinking","range":"0-20","price":"240 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=Benjamin+Trail+NP","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-033","name":"Airforce Condor","category":"hunting","range":"100-200","price":"1500 USD","delivery":"Express","img":"https://via.placeholder.com/900x600.png?text=Airforce+Condor","pellet_size":"7.62 mm (.30)","pellet_image":"https://via.placeholder.com/300x200.png?text=.30+7.62mm"},
            {"sku":"gun-034","name":"Brocock Compatto","category":"target","range":"20-50","price":"820 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=Brocock+Compatto","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-035","name":"Seacraft Ranger","category":"tactical","range":"50-100","price":"980 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=Seacraft+Ranger","pellet_size":"5.5 mm (.22)","pellet_image":"https://via.placeholder.com/300x200.png?text=.22+5.5mm"},
            {"sku":"gun-036","name":"FX Streamline","category":"target","range":"20-50","price":"1300 USD","delivery":"Express","img":"https://via.placeholder.com/900x600.png?text=FX+Streamline","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-037","name":"Hatsan Striker","category":"plinking","range":"0-20","price":"340 USD","delivery":"Pickup","img":"https://via.placeholder.com/900x600.png?text=Hatsan+Striker","pellet_size":"5.5 mm (.22)","pellet_image":"https://via.placeholder.com/300x200.png?text=.22+5.5mm"},
            {"sku":"gun-038","name":"Kral Phantom","category":"hunting","range":"50-100","price":"860 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=Kral+Phantom","pellet_size":"6.35 mm (.25)","pellet_image":"https://via.placeholder.com/300x200.png?text=.25+6.35mm"},
            {"sku":"gun-039","name":"Diablo Hunter","category":"hunting","range":"50-100","price":"1250 USD","delivery":"Express","img":"https://via.placeholder.com/900x600.png?text=Diablo+Hunter","pellet_size":"5.5 mm (.22)","pellet_image":"https://via.placeholder.com/300x200.png?text=.22+5.5mm"},
            {"sku":"gun-040","name":"BSA Super Meteor","category":"plinking","range":"0-20","price":"330 USD","delivery":"Pickup","img":"https://via.placeholder.com/900x600.png?text=BSA+Super+Meteor","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-041","name":"RWS 34","category":"target","range":"20-50","price":"810 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=RWS+34","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-042","name":"Rossi RB","category":"hunting","range":"50-100","price":"720 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=Rossi+RB","pellet_size":"5.5 mm (.22)","pellet_image":"https://via.placeholder.com/300x200.png?text=.22+5.5mm"},
            {"sku":"gun-043","name":"Hawke Sniper","category":"tactical","range":"100-200","price":"1490 USD","delivery":"Express","img":"https://via.placeholder.com/900x600.png?text=Hawke+Sniper","pellet_size":"6.35 mm (.25)","pellet_image":"https://via.placeholder.com/300x200.png?text=.25+6.35mm"},
            {"sku":"gun-044","name":"Crosman Phantom","category":"plinking","range":"0-20","price":"290 USD","delivery":"Pickup","img":"https://via.placeholder.com/900x600.png?text=Crosman+Phantom","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-045","name":"FX Cyclone","category":"target","range":"20-50","price":"1020 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=FX+Cyclone","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-046","name":"Daystate Wolverine","category":"hunting","range":"100-200","price":"2600 USD","delivery":"Express","img":"https://via.placeholder.com/900x600.png?text=Daystate+Wolverine","pellet_size":"7.62 mm (.30)","pellet_image":"https://via.placeholder.com/300x200.png?text=.30+7.62mm"},
            {"sku":"gun-047","name":"Weihrauch HW30","category":"plinking","range":"0-20","price":"420 USD","delivery":"Pickup","img":"https://via.placeholder.com/900x600.png?text=Weihrauch+HW30","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-048","name":"Gletcher CLT","category":"plinking","range":"0-20","price":"160 USD","delivery":"Pickup","img":"https://via.placeholder.com/900x600.png?text=Gletcher+CLT","pellet_size":"4.5 mm BB","pellet_image":"https://via.placeholder.com/300x200.png?text=BB+4.5mm"},
            {"sku":"gun-049","name":"FX Royale","category":"hunting","range":"50-100","price":"1950 USD","delivery":"Express","img":"https://via.placeholder.com/900x600.png?text=FX+Royale","pellet_size":"6.35 mm (.25)","pellet_image":"https://via.placeholder.com/300x200.png?text=.25+6.35mm"},
            {"sku":"gun-050","name":"Custom PCP Sporter","category":"hunting","range":"50-100","price":"1350 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=Custom+PCP+Sporter","pellet_size":"5.5 mm (.22)","pellet_image":"https://via.placeholder.com/300x200.png?text=.22+5.5mm"},
            {"sku":"gun-051","name":"Legacy Defender","category":"tactical","range":"50-100","price":"980 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=Legacy+Defender","pellet_size":"5.5 mm (.22)","pellet_image":"https://via.placeholder.com/300x200.png?text=.22+5.5mm"},
            {"sku":"gun-052","name":"Hammerli AP20","category":"target","range":"20-50","price":"700 USD","delivery":"Express","img":"https://via.placeholder.com/900x600.png?text=Hammerli+AP20","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-053","name":"Seacraft Prowler","category":"hunting","range":"50-100","price":"920 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=Seacraft+Prowler","pellet_size":"6.35 mm (.25)","pellet_image":"https://via.placeholder.com/300x200.png?text=.25+6.35mm"},
            {"sku":"gun-054","name":"Crosman Optimus","category":"plinking","range":"0-20","price":"200 USD","delivery":"Pickup","img":"https://via.placeholder.com/900x600.png?text=Crosman+Optimus","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-055","name":"FX Ranger","category":"target","range":"20-50","price":"980 USD","delivery":"Express","img":"https://via.placeholder.com/900x600.png?text=FX+Ranger","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-056","name":"Urban Defender","category":"tactical","range":"20-50","price":"630 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=Urban+Defender","pellet_size":"5.5 mm (.22)","pellet_image":"https://via.placeholder.com/300x200.png?text=.22+5.5mm"},
            {"sku":"gun-057","name":"Precision Hunter X","category":"hunting","range":"100-200","price":"2100 USD","delivery":"Express","img":"https://via.placeholder.com/900x600.png?text=Precision+Hunter+X","pellet_size":"7.62 mm (.30)","pellet_image":"https://via.placeholder.com/300x200.png?text=.30+7.62mm"},
            {"sku":"gun-058","name":"Target Master 500","category":"target","range":"20-50","price":"880 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=Target+Master+500","pellet_size":"4.5 mm (.177)","pellet_image":"https://via.placeholder.com/300x200.png?text=.177+4.5mm"},
            {"sku":"gun-059","name":"HuntPro Elite","category":"hunting","range":"50-100","price":"1290 USD","delivery":"Standard","img":"https://via.placeholder.com/900x600.png?text=HuntPro+Elite","pellet_size":"5.5 mm (.22)","pellet_image":"https://via.placeholder.com/300x200.png?text=.22+5.5mm"},
            {"sku":"gun-060","name":"Compact Repeater","category":"plinking","range":"0-20","price":"280 USD","delivery":"Pickup","img":"https://via.placeholder.com/900x600.png?text=Compact+Repeater","pellet_size":"4.5 mm BB","pellet_image":"https://via.placeholder.com/300x200.png?text=BB+4.5mm"}
        ];

        const localEdits = JSON.parse(localStorage.getItem('den_local_edits') || '{}');
        const demoOrders = JSON.parse(localStorage.getItem('den_orders') || '[]');

        function applyLocalEdits(item){
            if(localEdits[item.sku]) return {...item, ...localEdits[item.sku]};
            return item;
        }

        function makeCard(item){
            const it = applyLocalEdits(item);
            const div = document.createElement('div'); div.className='card';
            div.innerHTML = `
                <img class="gun" src="${it.img}" alt="${it.name}" loading="lazy" onerror="this.style.opacity=0.6">
                <h3>${it.name}</h3>
                <div class="meta"><div class="small">SKU: ${it.sku}</div><div class="small">${it.range} m</div></div>
                <div class="small" style="margin-top:6px">Pellet: <strong>${it.pellet_size}</strong></div>
                <div style="display:flex;gap:10px;align-items:center">
                    <img class="pellet" src="${it.pellet_image}" alt="pellet ${it.pellet_size}" loading="lazy" onerror="this.style.opacity=0.6">
                    <div style="flex:1">
                        <input class="input priceInput" data-sku="${it.sku}" value="${it.price}" />
                        <select class="input deliverySelect" data-sku="${it.sku}">
                            <option ${it.delivery==='Standard'?'selected':''}>Standard</option>
                            <option ${it.delivery==='Express'?'selected':''}>Express</option>
                            <option ${it.delivery==='Pickup'?'selected':''}>Pickup</option>
                        </select>
                    </div>
                </div>
                <div style="display:flex;gap:8px;margin-top:10px">
                    <button class="btn saveLocal" data-sku="${it.sku}">Save</button>
                    <button class="btn ghost viewBtn" data-sku="${it.sku}">View</button>
                    <button class="btn ghost orderBtn" data-sku="${it.sku}">Order</button>
                </div>
            `;
            return div;
        }

        function renderGrid(list){
            const grid = document.getElementById('gunsGrid');
            grid.innerHTML=''; list.forEach(i=>grid.appendChild(makeCard(i)));
            attachCardHandlers();
        }

        function renderList(list){
            const grid = document.getElementById('gunsList');
            grid.innerHTML=''; list.forEach(i=>grid.appendChild(makeCard(i)));
            attachCardHandlers();
        }

        renderGrid(gunsData.slice(0,12));
        renderList(gunsData);

        function attachCardHandlers(){
            document.querySelectorAll('.saveLocal').forEach(btn=>{
                btn.onclick = () => {
                    const sku = btn.dataset.sku;
                    const price = document.querySelector('.priceInput[data-sku="'+sku+'"]').value;
                    const delivery = document.querySelector('.deliverySelect[data-sku="'+sku+'"]').value;
                    localEdits[sku] = {price, delivery};
                    localStorage.setItem('den_local_edits', JSON.stringify(localEdits));
                    alert('Saved locally for SKU ' + sku);
                };
            });
            document.querySelectorAll('.viewBtn').forEach(b=>{
                b.onclick = () => {
                    const sku = b.dataset.sku;
                    const item = gunsData.find(x=>x.sku===sku);
                    const edit = localEdits[sku] || {};
                    alert(item.name + '\nSKU: '+item.sku+'\nPrice: '+(edit.price||item.price)+'\nDelivery: '+(edit.delivery||item.delivery)+'\nPellet: '+item.pellet_size);
                };
            });
            document.querySelectorAll('.orderBtn').forEach(b=>{
                b.onclick = () => {
                    const sku = b.dataset.sku;
                    const item = gunsData.find(x=>x.sku===sku);
                    const edit = localEdits[sku] || {};
                    const price = edit.price||item.price;
                    const delivery = edit.delivery||item.delivery;
                    const orderId = 'ORD-'+Math.random().toString(36).slice(2,8).toUpperCase();
                    const order = {id:orderId, sku:item.sku, model:item.name, price, delivery, status:'Processing'};
                    demoOrders.push(order);
                    localStorage.setItem('den_orders', JSON.stringify(demoOrders));
                    renderOrders();
                    alert('Order placed: ' + orderId);
                };
            });
        }

        function showPanel(name){
            document.querySelectorAll('nav.top a, #sideMenu button').forEach(e=>e.classList.remove('active'));
            document.querySelectorAll('nav.top a[data-target="'+name+'"]').forEach(e=>e.classList.add('active'));
            document.querySelectorAll('#sideMenu button[data-target="'+name+'"]').forEach(e=>e.classList.add('active'));
            document.querySelectorAll('.panel').forEach(p=>p.style.display='none');
            const panel = document.getElementById('panel-'+name);
            if(panel) panel.style.display='block';
            else document.getElementById('panel-home').style.display='block';
            window.scrollTo({top:0,behavior:'smooth'});
        }

        document.querySelectorAll('nav.top a').forEach(a=>{
            a.addEventListener('click', e=>{ e.preventDefault(); showPanel(a.dataset.target); });
        });
        document.querySelectorAll('#sideMenu button').forEach(b=>{ b.addEventListener('click', ()=>showPanel(b.dataset.target)); });

        document.getElementById('showGuns').onclick = ()=> showPanel('guns');
        document.getElementById('showOrders').onclick = ()=> showPanel('orders');

        document.querySelectorAll('#rangeFilters .pill').forEach(p=>{
            p.addEventListener('click', ()=>{
                document.querySelectorAll('#rangeFilters .pill').forEach(x=>x.classList.remove('active'));
                p.classList.add('active');
                const range = p.dataset.range;
                if(range==='all') renderGrid(gunsData.slice(0,12));
                else {
                    if(range.includes('+')){
                        const a = parseInt(range);
                        const filtered = gunsData.filter(g=> {
                            const r = parseInt(g.range.split('-')[0]) || parseInt(g.range) || 0;
                            return r >= a;
                        });
                        renderGrid(filtered);
                    } else {
                        const [a,b] = range.split('-').map(Number);
                        const filtered = gunsData.filter(g=>{
                            const r = parseInt(g.range.split('-')[0]) || parseInt(g.range) || 0;
                            return r >= a && r <= b;
                        });
                        renderGrid(filtered);
                    }
                }
            });
        });

        document.querySelectorAll('#topFilters .pill').forEach(p=>{
            p.addEventListener('click', ()=>{
                document.querySelectorAll('#topFilters .pill').forEach(x=>x.classList.remove('active'));
                p.classList.add('active');
                const f = p.dataset.filter;
                if(f==='all') renderGrid(gunsData.slice(0,12));
                else renderGrid(gunsData.filter(g=>g.category===f));
            });
        });

        document.getElementById('searchBox').addEventListener('input', e=>{
            const q = e.target.value.toLowerCase();
            const out = gunsData.filter(g=> g.name.toLowerCase().includes(q) || g.sku.toLowerCase().includes(q) || g.category.toLowerCase().includes(q));
            renderList(out);
        });

        document.getElementById('sortSelect').addEventListener('change', e=>{
            let arr = [...gunsData];
            if(e.target.value==='price-asc') arr.sort((a,b)=> (parseInt(a.price)||0) - (parseInt(b.price)||0));
            if(e.target.value==='price-desc') arr.sort((a,b)=> (parseInt(b.price)||0) - (parseInt(a.price)||0));
            renderList(arr);
        });

        document.getElementById('saveBtn').addEventListener('click', ()=>{
            const sku = document.getElementById('editSku').value.trim();
            const price = document.getElementById('editPrice').value.trim();
            const delivery = document.getElementById('editDelivery').value;
            if(!sku) return alert('Enter SKU to save');
            localEdits[sku] = {price, delivery};
            localStorage.setItem('den_local_edits', JSON.stringify(localEdits));
            alert('Saved local edit for '+sku);
            renderGrid(gunsData.slice(0,12));
            renderList(gunsData);
        });

        document.getElementById('resetBtn').addEventListener('click', ()=>{
            if(confirm('Clear local demo edits?')){ localStorage.removeItem('den_local_edits'); location.reload(); }
        });

        function renderOrders(){
            const tb = document.querySelector('#ordersTable tbody');
            tb.innerHTML='';
            const orders = demoOrders.length ? demoOrders : [
                {id:'ORD-001', sku:'gun-001', model:'FX Crown MKII', price:'1800 USD', delivery:'Standard', status:'Processing'},
                {id:'ORD-002', sku:'gun-004', model:'Weihrauch HW100', price:'950 USD', delivery:'Pickup', status:'Ready'}
            ];
            orders.forEach(o=>{
                const tr = document.createElement('tr');
                tr.innerHTML = `<td>${o.id}</td><td>${o.sku}</td><td>${o.model}</td><td>${o.price}</td><td>${o.delivery}</td><td>${o.status}</td>`;
                tb.appendChild(tr);
            });
        }
        renderOrders();

        // Login modal demo
        const loginModal = document.getElementById('loginModal');
        document.getElementById('loginBtn').addEventListener('click', ()=> { loginModal.style.display='flex'; });
        document.getElementById('closeLogin').addEventListener('click', ()=> { loginModal.style.display='none'; });
        document.getElementById('doLogin').addEventListener('click', ()=>{
            const em = document.getElementById('loginEmail').value;
            if(!em) return alert('Enter email for demo login.');
            alert('Demo login successful as ' + em + '. Replace with real auth for production.');
            loginModal.style.display='none';
        });

        // reCAPTCHA placeholder notes:
        // 1) Register domain at https://www.google.com/recaptcha/admin to get site key & secret.
        // 2) Add <script src="https://www.google.com/recaptcha/api.js" async defer></script>
        // 3) Render grecaptcha in #recaptchaPlaceholder and verify token on server.
    </script>
</body>
</html>
