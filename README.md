<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>OLa LUXE LIPS – Premium Lip Cosmetics</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  <style>
    :root {
      --bg: #fff5f7; /* Soft pink background for elegance */
      --surface: #fce4ec; /* Light pink surface for cards */
      --surface-2: #ffebf0; /* Lighter pink for hover effects */
      --brand: #e91e63; /* Vibrant pink as primary brand color */
      --brand-600: #c2185b; /* Darker pink for hover */
      --brand-700: #ad1457; /* Deep pink for depth */
      --accent: #f06292; /* Softer pink accent */
      --gold: #f3e5ab; /* Soft gold for luxury highlights */
      --ink: #4a2c40; /* Deep plum ink for text */
      --subtle: #b39ddb; /* Lavender subtle for secondary text */
      --ok: #4caf50; /* Green for success */
      --warn: #ef5350; /* Coral warn */
      --ring: 0 12px 32px rgba(233, 30, 99, 0.15); /* Shadow with pink tint */
    }
    body {
      font-family: "Poppins", system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, 'Helvetica Neue', Arial;
      color: var(--ink);
      background: var(--bg);
    }
    .btn-primary {
      background-color: var(--brand);
      border-color: var(--brand);
    }
    .btn-primary:hover {
      background-color: var(--brand-600);
      border-color: var(--brand-600);
    }
    .btn-secondary {
      background-color: var(--surface);
      color: var(--brand-700);
      border-color: rgba(233, 30, 99, 0.25);
    }
    .btn-secondary:hover {
      background-color: var(--surface-2);
    }
    .btn-outline-secondary {
      color: var(--brand-700);
      border-color: rgba(233, 30, 99, 0.3);
    }
    .btn-outline-secondary:hover {
      background-color: var(--surface-2);
    }
    .btn-danger {
      background-color: var(--warn);
    }
    .btn-danger:hover {
      background-color: #d32f2f;
    }
    .badge.bg-success {
      background-color: #e8f5e9 !important;
      border-color: #c8e6c9;
      color: var(--ok);
    }
    .badge.bg-warning {
      background-color: #ffebee !important;
      border-color: #ffcdd2;
      color: var(--warn);
    }
    .badge.bg-light {
      background-color: var(--surface-2);
      border-color: rgba(233, 30, 99, 0.25);
      color: var(--ink);
    }
    .text-muted {
      color: var(--subtle) !important;
    }
    .navbar {
      background: rgba(255, 245, 247, 0.92);
      backdrop-filter: saturate(180%) blur(16px);
    }
    .nav-link.active {
      background: var(--brand);
      color: #fff !important;
      border-color: var(--brand);
    }
    .card {
      border: 1px solid rgba(243, 229, 171, 0.15);
      box-shadow: var(--ring);
    }
    .form-control:focus {
      border-color: var(--gold);
      box-shadow: 0 0 0 0.25rem rgba(243, 229, 171, 0.2);
    }
    .table th {
      background: var(--surface);
    }
    .table-striped > tbody > tr:nth-of-type(odd) > * {
      --bs-table-bg-type: var(--surface-2);
    }
    .table td, .table th {
      border-bottom: 1px dashed rgba(243, 229, 171, 0.25);
    }
    .cart-toggle {
      position: fixed;
      right: 24px;
      bottom: 24px;
      border-radius: 50rem;
      padding: 0.75rem 1.5rem;
      box-shadow: var(--ring);
    }
    .cart-panel {
      position: fixed;
      right: 24px;
      bottom: 96px;
      width: 420px;
      max-width: 95vw;
      background: #fff;
      border: 1px solid rgba(243, 229, 171, 0.15);
      border-radius: 1.5rem;
      box-shadow: var(--ring);
      padding: 1.5rem;
      display: none;
    }
    .cart-panel.active {
      display: block;
    }
    footer {
      border-top: 1px solid rgba(243, 229, 171, 0.15);
    }
    .product img {
      border: 1px solid rgba(243, 229, 171, 0.25);
    }
    .navbar-brand img {
      height: 40px; /* Adjust based on your logo size */
    }
  </style>
</head>
<body>
  <header>
    <nav class="navbar navbar-expand-lg sticky-top">
      <div class="container">
        <a class="navbar-brand d-flex align-items-center gap-2" href="#">
          <img src="https://via.placeholder.com/150x40/FFE4E1/000000?text=OLa+LUXE+LIPS" alt="OLa LUXE LIPS Logo" />
          <small class="fw-normal text-muted">LUXURY FOR YOUR LIPS 💋 ✨</small>
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
          <ul class="navbar-nav gap-2">
            <li class="nav-item">
              <button class="nav-link active rounded-pill px-3 py-2" data-route="home">Home</button>
            </li>
            <li class="nav-item">
              <button class="nav-link rounded-pill px-3 py-2" data-route="shop">Shop</button>
            </li>
            <li class="nav-item">
              <button class="nav-link rounded-pill px-3 py-2" data-route="about">About</button>
            </li>
            <li class="nav-item">
              <button class="nav-link rounded-pill px-3 py-2" data-route="contact">Contact</button>
            </li>
            <li class="nav-item">
              <button class="nav-link rounded-pill px-3 py-2" data-route="admin">Admin</button>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>

  <main class="container py-5">
    <!-- HOME -->
    <section id="route-home" class="active">
      <div class="row">
        <div class="col-12">
          <div class="card text-center" style="background: linear-gradient(135deg, var(--brand), var(--accent)); color: #fff;">
            <div class="card-body">
              <h1 class="card-title display-4">Welcome to OLa LUXE LIPS</h1>
              <p class="card-text fs-4">Discover premium, cruelty-free lip cosmetics for ultimate glamour.</p>
              <button class="btn btn-secondary" onclick="navigate('shop')">Shop Now</button>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- SHOP -->
    <section id="route-shop" style="display: none;">
      <div class="row">
        <div class="col-12">
          <div class="card">
            <div class="card-body">
              <div class="d-flex flex-wrap gap-3 justify-content-between align-items-center">
                <div class="d-flex flex-wrap gap-3">
                  <input id="search" class="form-control" style="min-width: 280px;" placeholder="Search products…" aria-label="Search products" />
                  <select id="availabilityFilter" class="form-select" aria-label="Filter by availability">
                    <option value="all">All</option>
                    <option value="in">In stock</option>
                    <option value="out">Out of stock</option>
                  </select>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div id="catalog" class="row mt-4 g-4"></div>
    </section>

    <!-- ABOUT -->
    <section id="route-about" style="display: none;">
      <div class="row">
        <div class="col-lg-6 col-12">
          <div class="card h-100">
            <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='100%' height='100%'><rect width='100%' height='100%' fill='#fce4ec'/><text x='50%' y='50%' text-anchor='middle' font-family='Poppins' font-size='24' fill='#c2185b'>Brand Image Placeholder</text></svg>" class="card-img-top" alt="About Image" style="height: 300px; object-fit: cover;">
          </div>
        </div>
        <div class="col-lg-6 col-12">
          <div class="card h-100">
            <div class="card-body">
              <h2 class="card-title">About OLa LUXE LIPS</h2>
              <p>LUXURY FOR YOUR LIPS 💋 ✨ We offer premium, cruelty-free lip cosmetics that deliver sophistication and glamour. From velvety mattes to glossy shines, our products are crafted for the ultimate lip experience.</p>
              <p class="text-muted">This demo shop is built using HTML, CSS, and JavaScript (no backend). All data is stored locally in your browser via <strong>localStorage</strong>.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="route-contact" style="display: none;">
      <div class="row">
        <div class="col-lg-6 col-12">
          <div class="card">
            <div class="card-body">
              <h2 class="card-title">Contact Us</h2>
              <form id="contactForm" class="row g-3" onsubmit="return false">
                <div class="col-md-6">
                  <label for="ctName" class="form-label">Your Name</label>
                  <input id="ctName" class="form-control" required placeholder="Jane Doe" aria-required="true" />
                </div>
                <div class="col-md-6">
                  <label for="ctEmail" class="form-label">Your Email (for feedback)</label>
                  <input id="ctEmail" class="form-control" required type="email" placeholder="you@gmail.com" aria-required="true" />
                </div>
                <div class="col-12">
                  <label for="ctMessage" class="form-label">Message</label>
                  <textarea id="ctMessage" class="form-control" required rows="5" placeholder="Type your message…" aria-required="true"></textarea>
                </div>
                <div class="col-12 d-flex flex-wrap justify-content-between gap-3">
                  <button class="btn btn-secondary" id="mailtoBtn" type="button">Send via Email</button>
                  <button class="btn btn-primary flex-grow-1" id="storeMsgBtn" type="submit">Send & Save</button>
                </div>
                <div class="col-12">
                  <p class="text-muted">“Send via Email” opens your email client. “Send & Save” stores the message for admin review.</p>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ADMIN -->
    <section id="route-admin" style="display: none;">
      <div class="row">
        <div class="col-12">
          <div class="card">
            <div class="card-body">
              <div class="d-flex flex-wrap justify-content-between align-items-center">
                <h2 class="card-title mb-0">Admin Dashboard</h2>
                <div class="d-flex flex-wrap gap-3">
                  <input id="adminEmail" class="form-control" placeholder="Admin Email (for contact)" style="min-width: 280px" aria-label="Admin Email" />
                  <input id="adminPass" class="form-control" placeholder="Admin Password" type="password" style="min-width: 200px" aria-label="Admin Password" />
                  <button class="btn btn-primary" id="saveAdminPrefs">Save</button>
                </div>
              </div>
              <p class="text-muted mt-2">Password stored locally for access (not secure). Default: <code>admin123</code>. Set email for contact form.</p>
            </div>
          </div>
        </div>
      </div>

      <!-- Admin Sub-Nav -->
      <ul class="nav nav-tabs mt-4" style="justify-content: flex-start;">
        <li class="nav-item">
          <button class="nav-link active" data-admin-route="products">Products</button>
        </li>
        <li class="nav-item">
          <button class="nav-link" data-admin-route="orders">Orders</button>
        </li>
        <li class="nav-item">
          <button class="nav-link" data-admin-route="messages">Messages</button>
        </li>
      </ul>

      <!-- Product Form and List -->
      <div id="admin-products" class="admin-section mt-3">
        <div class="row">
          <div class="col-12">
            <div class="card">
              <div class="card-body">
                <h3 class="card-title">Add / Edit Product</h3>
                <form id="productForm" class="row g-3" onsubmit="return false">
                  <input type="hidden" id="prodId" />
                  <div class="col-md-6">
                    <label for="prodName" class="form-label">Product Name</label>
                    <input id="prodName" class="form-control" required placeholder="Velvet Matte Lipstick" aria-required="true" />
                  </div>
                  <div class="col-md-3">
                    <label for="prodPrice" class="form-label">Price (NGN)</label>
                    <input id="prodPrice" class="form-control" required type="number" min="0" step="0.01" placeholder="7500" aria-required="true" />
                  </div>
                  <div class="col-md-3">
                    <label for="prodQty" class="form-label">Quantity in Stock</label>
                    <input id="prodQty" class="form-control" required type="number" min="0" step="1" placeholder="20" aria-required="true" />
                  </div>
                  <div class="col-12">
                    <label for="prodDesc" class="form-label">Description</label>
                    <textarea id="prodDesc" class="form-control" rows="3" placeholder="Short details about this product…"></textarea>
                  </div>
                  <div class="col-md-6">
                    <label for="prodAvail" class="form-label">Availability</label>
                    <select id="prodAvail" class="form-select" aria-label="Product Availability">
                      <option value="in">In stock</option>
                      <option value="out">Out of stock</option>
                    </select>
                  </div>
                  <div class="col-md-6">
                    <label for="prodImg" class="form-label">Product Image</label>
                    <input id="prodImg" class="form-control" type="file" accept="image/*" />
                    <small class="text-muted">Upload square image (max 500KB). Stored as base64.</small>
                  </div>
                  <div class="col-12 d-flex justify-content-end gap-3">
                    <button class="btn btn-secondary" id="resetForm" type="button">Reset</button>
                    <button class="btn btn-primary" id="saveProduct" type="submit">Save Product</button>
                  </div>
                </form>
              </div>
            </div>
          </div>

          <div class="col-12 mt-4">
            <div class="card">
              <div class="card-body">
                <div class="d-flex justify-content-between align-items-center">
                  <h3 class="card-title mb-0">Products</h3>
                  <span class="text-muted" id="prodCount">0 items</span>
                </div>
                <div class="table-responsive mt-3">
                  <table id="prodTable" class="table table-striped table-hover">
                    <thead>
                      <tr>
                        <th>Item</th>
                        <th>Price</th>
                        <th>Qty</th>
                        <th>Status</th>
                        <th>Actions</th>
                      </tr>
                    </thead>
                    <tbody></tbody>
                  </table>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Orders -->
      <div id="admin-orders" class="admin-section mt-3" style="display: none;">
        <div class="row">
          <div class="col-12">
            <div class="card">
              <div class="card-body">
                <div class="d-flex justify-content-between align-items-center">
                  <h3 class="card-title mb-0">Orders</h3>
                  <span class="text-muted" id="orderCount">0 orders</span>
                </div>
                <div class="table-responsive mt-3">
                  <table id="orderTable" class="table table-striped table-hover">
                    <thead>
                      <tr>
                        <th>Order #</th>
                        <th>Customer</th>
                        <th>Email</th>
                        <th>Items</th>
                        <th>Total</th>
                        <th>Status</th>
                        <th>Actions</th>
                      </tr>
                    </thead>
                    <tbody></tbody>
                  </table>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Messages -->
      <div id="admin-messages" class="admin-section mt-3" style="display: none;">
        <div class="row">
          <div class="col-12">
            <div class="card">
              <div class="card-body">
                <div class="d-flex justify-content-between align-items-center">
                  <h3 class="card-title mb-0">Contact Messages</h3>
                  <span class="text-muted" id="msgCount">0 messages</span>
                </div>
                <div class="table-responsive mt-3">
                  <table id="msgTable" class="table table-striped table-hover">
                    <thead>
                      <tr>
                        <th>From</th>
                        <th>Email</th>
                        <th>Message</th>
                        <th>Date</th>
                        <th>Actions</th>
                      </tr>
                    </thead>
                    <tbody></tbody>
                  </table>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>

  <!-- CART -->
  <button class="btn btn-primary cart-toggle" id="cartToggle" aria-label="Open Cart">Cart (<span id="cartCount">0</span>)</button>
  <div class="cart-panel" id="cartPanel">
    <h3 class="mb-3">Your Cart</h3>
    <div id="cartItems" style="max-height: 320px; overflow: auto"></div>
    <div class="d-flex justify-content-between mt-3">
      <strong>Total:</strong>
      <strong id="cartTotal">₦0</strong>
    </div>
    <hr class="my-3" style="border-top: 1px dashed rgba(243, 229, 171, 0.25);">
    <form id="checkoutForm" class="row g-3" onsubmit="return false">
      <div class="col-12">
        <label for="ckName" class="form-label">Full Name</label>
        <input id="ckName" class="form-control" required placeholder="Jane Doe" aria-required="true" />
      </div>
      <div class="col-12">
        <label for="ckEmail" class="form-label">Email (for updates)</label>
        <input id="ckEmail" class="form-control" required type="email" placeholder="you@gmail.com" aria-required="true" />
      </div>
      <div class="col-12">
        <label for="ckAddress" class="form-label">Delivery Address</label>
        <textarea id="ckAddress" class="form-control" required rows="3" placeholder="Address details…" aria-required="true"></textarea>
      </div>
      <div class="col-12">
        <button class="btn btn-primary w-100" id="placeOrder" type="submit">Place Order</button>
      </div>
      <div class="col-12">
        <p class="text-muted">Orders sent to admin. No payment here.</p>
      </div>
    </form>
  </div>

  <footer class="container py-5 text-center text-muted">© <span id="year"></span> OLa LUXE LIPS. All rights reserved.</footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
  <script>
    // Utilities
    const $ = (sel, root = document) => root.querySelector(sel);
    const $$ = (sel, root = document) => Array.from(root.querySelectorAll(sel));
    const money = (n) => new Intl.NumberFormat('en-NG', { style: 'currency', currency: 'NGN' }).format(n || 0);
    const id = () => Math.random().toString(36).slice(2, 10);
    const today = () => new Date().toISOString();
    const LS = {
      get(key, fallback) {
        try { return JSON.parse(localStorage.getItem(key)) ?? fallback; } catch (e) { return fallback; }
      },
      set(key, val) { localStorage.setItem(key, JSON.stringify(val)); }
    };

    // Data Stores
    let products = LS.get('oll_products', []);
    let orders = LS.get('oll_orders', []);
    let messages = LS.get('oll_messages', []);
    let prefs = LS.get('oll_prefs', { adminEmail: '', adminPass: 'admin123' });
    const state = { cart: LS.get('oll_cart', []) };

    // Initial Setup
    $$('#year').forEach((n) => n.textContent = new Date().getFullYear());

    // Routing
    $$('.nav-link:not([data-admin-route])').forEach((btn) => btn.addEventListener('click', () => navigate(btn.dataset.route)));
    function navigate(route) {
      $$('.nav-link:not([data-admin-route])').forEach((b) => b.classList.toggle('active', b.dataset.route === route));
      $$('main section').forEach((s) => s.style.display = s.id === 'route-' + route ? 'block' : 'none');
      if (route === 'admin') gateAdmin();
      if (route === 'shop') renderCatalog();
    }

    // Admin Sub-Routing
    $$('[data-admin-route]').forEach((btn) => btn.addEventListener('click', () => {
      $$('[data-admin-route]').forEach((b) => b.classList.toggle('active', b.dataset.adminRoute === btn.dataset.adminRoute));
      $$('.admin-section').forEach((s) => s.style.display = s.id === 'admin-' + btn.dataset.adminRoute ? 'block' : 'none');
    }));

    function gateAdmin() {
      const pass = prompt('Enter admin password:', '') || '';
      if (pass !== prefs.adminPass) {
        alert('Incorrect password. Redirecting to Home.');
        navigate('home');
      } else {
        $('#adminEmail').value = prefs.adminEmail || '';
        $('#adminPass').value = prefs.adminPass || '';
        renderAdminTables();
      }
    }

    // Catalog & Cart Functions
    function renderCatalog() {
      const wrap = $('#catalog');
      wrap.innerHTML = '';
      const q = ($('#search').value || '').toLowerCase();
      const filter = $('#availabilityFilter').value;
      const list = products.filter((p) => {
        const matches = p.name.toLowerCase().includes(q) || (p.desc || '').toLowerCase().includes(q);
        const availOK = filter === 'all' || (filter === 'in' ? p.avail === 'in' && p.qty > 0 : p.avail === 'out' || p.qty === 0);
        return matches && availOK;
      });

      if (list.length === 0) {
        wrap.innerHTML = `<div class="col-12"><div class="card"><div class="card-body"><em>No products found. Add via Admin.</em></div></div></div>`;
        return;
      }

      list.forEach((p) => {
        const card = document.createElement('div');
        card.className = 'col-md-6 col-lg-3';
        card.innerHTML = `
          <div class="card h-100">
            <div class="card-body d-flex flex-column">
              <div class="product d-flex gap-3 align-items-start flex-grow-1">
                <img src="${p.img || placeholder()}" alt="${escapeHtml(p.name)}" class="rounded" style="width: 140px; height: 140px; object-fit: cover;" loading="lazy"/>
                <div class="meta flex-grow-1">
                  <h4 class="mb-2">${escapeHtml(p.name)}</h4>
                  <p class="mb-3 text-muted">${escapeHtml(p.desc || '')}</p>
                </div>
              </div>
              <div class="d-flex justify-content-between align-items-center mt-auto">
                <div class="d-flex gap-3 align-items-center">
                  <strong>${money(p.price)}</strong>
                  <span class="badge ${p.avail === 'in' && p.qty > 0 ? 'bg-success' : 'bg-warning'}">${p.avail === 'in' && p.qty > 0 ? 'In stock' : 'Out of stock'}</span>
                  <small class="text-muted">Qty: ${p.qty}</small>
                </div>
                <button class="btn btn-primary ${p.avail !== 'in' || p.qty <= 0 ? 'disabled' : ''}" data-id="${p.id}">Add to Cart</button>
              </div>
            </div>
          </div>`;
        $('button.btn-primary', card).addEventListener('click', () => addToCart(p.id));
        wrap.appendChild(card);
      });
    }

    function placeholder() {
      return 'data:image/svg+xml;utf8,' + encodeURIComponent(`<svg xmlns="http://www.w3.org/2000/svg" width="140" height="140"><rect width="100%" height="100%" fill="#fce4ec"/><text x="50%" y="52%" text-anchor="middle" font-family="Poppins" font-size="14" fill="#c2185b">No Image</text></svg>`);
    }

    function addToCart(pid) {
      const p = products.find((x) => x.id === pid);
      if (!p || p.avail !== 'in' || p.qty <= 0) return alert('Item unavailable.');
      const line = state.cart.find((l) => l.id === pid);
      if (line) { line.qty = Math.min(line.qty + 1, p.qty); } else { state.cart.push({ id: pid, qty: 1 }); }
      saveCart();
      renderCart();
    }

    function renderCart() {
      $('#cartCount').textContent = state.cart.reduce((a, b) => a + b.qty, 0);
      const box = $('#cartItems');
      box.innerHTML = '';
      let total = 0;
      state.cart.forEach((line) => {
        const p = products.find((x) => x.id === line.id);
        const li = document.createElement('div');
        li.className = 'd-flex justify-content-between align-items-center mb-3 gap-3';
        const sub = (p?.price || 0) * line.qty; total += sub;
        li.innerHTML = `
          <div class="d-flex gap-3 align-items-center">
            <img src="${p?.img || placeholder()}" class="rounded" style="width: 52px; height: 52px; border: 1px solid rgba(243, 229, 171, 0.2)" alt="${escapeHtml(p?.name || 'Item')}"/>
            <div>
              <div class="fw-semibold">${escapeHtml(p?.name || 'Unknown')}</div>
              <small class="text-muted">${money(p?.price)} × </small>
              <input type="number" class="form-control d-inline-block" style="width: 80px" min="1" max="${p?.qty || 1}" value="${line.qty}" aria-label="Quantity" />
            </div>
          </div>
          <div class="d-flex gap-3 align-items-center">
            <strong>${money(sub)}</strong>
            <button class="btn btn-secondary">Remove</button>
          </div>`;
        $('input', li).addEventListener('input', (e) => { line.qty = Math.max(1, Math.min(+e.target.value || 1, p?.qty || 1)); saveCart(); renderCart(); });
        $('button', li).addEventListener('click', () => { state.cart = state.cart.filter((x) => x !== line); saveCart(); renderCart(); });
        box.appendChild(li);
      });
      $('#cartTotal').textContent = money(total);
    }

    function saveCart() { LS.set('oll_cart', state.cart); }

    // Checkout
    $('#placeOrder').addEventListener('click', () => {
      if (state.cart.length === 0) return alert('Cart is empty.');
      const name = $('#ckName').value.trim();
      const email = $('#ckEmail').value.trim();
      const address = $('#ckAddress').value.trim();
      if (!name || !email || !address) return alert('Complete all fields.');
      const lines = state.cart.map((l) => {
        const p = products.find((x) => x.id === l.id);
        return { id: p.id, name: p.name, price: p.price, qty: l.qty };
      });
      const total = lines.reduce((a, b) => a + b.price * b.qty, 0);
      const order = { id: id(), created: today(), name, email, address, lines, total, status: 'Pending' };
      lines.forEach((li) => {
        const p = products.find((x) => x.id === li.id);
        if (p) { p.qty = Math.max(0, p.qty - li.qty); if (p.qty === 0) p.avail = 'out'; }
      });
      orders.unshift(order);
      LS.set('oll_orders', orders);
      LS.set('oll_products', products);
      state.cart = []; saveCart();
      renderCatalog(); renderCart(); renderAdminTables();
      alert('Order placed!');
    });

    // Cart Toggle
    $('#cartToggle').addEventListener('click', () => $('#cartPanel').classList.toggle('active'));

    // Search/Filter
    $('#search').addEventListener('input', () => { if ($('#route-shop').style.display === 'block') renderCatalog(); });
    $('#availabilityFilter').addEventListener('change', () => { if ($('#route-shop').style.display === 'block') renderCatalog(); });

    // Admin Prefs
    $('#saveAdminPrefs').addEventListener('click', () => {
      prefs.adminEmail = $('#adminEmail').value.trim();
      prefs.adminPass = $('#adminPass').value || 'admin123';
      LS.set('oll_prefs', prefs);
      alert('Preferences saved.');
    });

    // Product Form
    $('#resetForm').addEventListener('click', resetForm);
    $('#saveProduct').addEventListener('click', async () => {
      const payload = await readProductForm();
      if (!payload) return;
      if (payload.id) {
        const idx = products.findIndex((p) => p.id === payload.id);
        if (idx > -1) products[idx] = payload;
      } else {
        payload.id = id();
        products.unshift(payload);
      }
      LS.set('oll_products', products);
      resetForm(); renderCatalog(); renderAdminTables();
      alert('Product saved.');
    });

    function resetForm() {
      $('#prodId').value = '';
      $('#productForm').reset();
    }

    async function readProductForm() {
      const name = $('#prodName').value.trim();
      const price = +$('#prodPrice').value;
      const qty = +$('#prodQty').value;
      const desc = $('#prodDesc').value.trim();
      const avail = $('#prodAvail').value;
      const existingId = $('#prodId').value || null;
      if (!name || isNaN(price) || isNaN(qty)) {
        alert('Required: name, price, quantity.');
        return null;
      }
      let imgData = null;
      const file = $('#prodImg').files[0];
      if (file) { imgData = await toBase64(file); }
      if (!imgData && existingId) { imgData = (products.find((p) => p.id === existingId) || {}).img || null; }
      return { id: existingId, name, price, qty, desc, avail, img: imgData };
    }

    function toBase64(file) {
      return new Promise((resolve, reject) => {
        const fr = new FileReader();
        fr.onload = () => resolve(fr.result);
        fr.onerror = reject;
        fr.readAsDataURL(file);
      });
    }

    // Admin Tables
    function renderAdminTables() {
      $('#prodCount').textContent = products.length + ' items';
      const pbody = $('#prodTable tbody');
      pbody.innerHTML = '';
      products.forEach((p) => {
        const tr = document.createElement('tr');
        tr.innerHTML = `
          <td>
            <div class="d-flex align-items-center gap-3">
              <img src="${p.img || placeholder()}" class="rounded" style="width: 42px; height: 42px; border: 1px solid rgba(243, 229, 171, 0.2)" alt="${escapeHtml(p.name)}"/>
              <div>
                <div class="fw-semibold">${escapeHtml(p.name)}</div>
                <small class="text-muted">${escapeHtml(p.desc || '')}</small>
              </div>
            </div>
          </td>
          <td>${money(p.price)}</td>
          <td>${p.qty}</td>
          <td><span class="badge ${p.avail === 'in' && p.qty > 0 ? 'bg-success' : 'bg-warning'}">${p.avail === 'in' && p.qty > 0 ? 'In stock' : 'Out of stock'}</span></td>
          <td>
            <div class="d-flex gap-2">
              <button class="btn btn-secondary" data-act="edit">Edit</button>
              <button class="btn btn-danger" data-act="del">Delete</button>
            </div>
          </td>`;
        $('[data-act="edit"]', tr).addEventListener('click', () => editProduct(p.id));
        $('[data-act="del"]', tr).addEventListener('click', () => deleteProduct(p.id));
        pbody.appendChild(tr);
      });

      $('#orderCount').textContent = orders.length + ' orders';
      const obody = $('#orderTable tbody');
      obody.innerHTML = '';
      orders.forEach((o) => {
        const tr = document.createElement('tr');
        tr.innerHTML = `
          <td>#${o.id.slice(0, 6)}</td>
          <td>${escapeHtml(o.name)}</td>
          <td>${escapeHtml(o.email)}</td>
          <td>${o.lines.map((li) => `${escapeHtml(li.name)} × ${li.qty}`).join(', ')}</td>
          <td>${money(o.total)}</td>
          <td><span class="badge ${o.status === 'Shipped' ? 'bg-success' : 'bg-light text-dark'}">${o.status}</span></td>
          <td>
            <div class="d-flex gap-2">
              <button class="btn btn-secondary" data-act="ship">Mark Shipped</button>
              <button class="btn btn-danger" data-act="del">Delete</button>
            </div>
          </td>`;
        $('[data-act="ship"]', tr).addEventListener('click', () => { o.status = 'Shipped'; LS.set('oll_orders', orders); renderAdminTables(); });
        $('[data-act="del"]', tr).addEventListener('click', () => { orders = orders.filter((x) => x !== o); LS.set('oll_orders', orders); renderAdminTables(); });
        obody.appendChild(tr);
      });

      $('#msgCount').textContent = messages.length + ' messages';
      const mbody = $('#msgTable tbody');
      mbody.innerHTML = '';
      messages.forEach((m) => {
        const tr = document.createElement('tr');
        tr.innerHTML = `
          <td>${escapeHtml(m.name)}</td>
          <td>${escapeHtml(m.email)}</td>
          <td>${escapeHtml(m.message)}</td>
          <td><small>${new Date(m.created).toLocaleString()}</small></td>
          <td>
            <div class="d-flex gap-2">
              <a class="btn btn-secondary" href="mailto:${encodeURIComponent(m.email)}?subject=Re: OLa LUXE LIPS&body=${encodeURIComponent('\n\n--- Message: ' + m.message)}">Reply</a>
              <button class="btn btn-danger" data-act="del">Delete</button>
            </div>
          </td>`;
        $('[data-act="del"]', tr).addEventListener('click', () => { messages = messages.filter((x) => x !== m); LS.set('oll_messages', messages); renderAdminTables(); });
        mbody.appendChild(tr);
      });
    }

    function editProduct(pid) {
      const p = products.find((x) => x.id === pid); if (!p) return;
      $('#prodId').value = p.id;
      $('#prodName').value = p.name;
      $('#prodPrice').value = p.price;
      $('#prodQty').value = p.qty;
      $('#prodDesc').value = p.desc || '';
      $('#prodAvail').value = p.avail;
      alert('Product loaded.');
      window.scrollTo({ top: 0, behavior: 'smooth' });
    }

    function deleteProduct(pid) {
      if (!confirm('Delete product?')) return;
      products = products.filter((p) => p.id !== pid);
      LS.set('oll_products', products);
      renderCatalog(); renderAdminTables();
    }

    // Contact
    $('#mailtoBtn').addEventListener('click', () => {
      const name = $('#ctName').value.trim();
      const email = $('#ctEmail').value.trim();
      const msg = $('#ctMessage').value.trim();
      const to = prefs.adminEmail || 'admin@example.com';
      const subject = `Message from ${name} - OLa LUXE LIPS`;
      const body = `${msg}\n\nFrom: ${name} <${email}>`;
      window.location.href = `mailto:${encodeURIComponent(to)}?subject=${encodeURIComponent(subject)}&body=${encodeURIComponent(body)}`;
    });

    $('#contactForm').addEventListener('submit', () => {
      const name = $('#ctName').value.trim();
      const email = $('#ctEmail').value.trim();
      const message = $('#ctMessage').value.trim();
      if (!name || !email || !message) return alert('Fields required.');
      messages.unshift({ id: id(), name, email, message, created: today() });
      LS.set('oll_messages', messages);
      $('#contactForm').reset();
      renderAdminTables();
      alert('Message sent!');
    });

    // Helpers
    function escapeHtml(str) {
      return String(str || '').replace(/[&<>"']/g, (s) => ({ '&': '&amp;', '<': '&lt;', '>': '&gt;', '"': '&quot;', "'": '&#39;' }[s]));
    }

    // Initial Renders
    navigate('home');
    renderCart();
  </script>
</body>
</html>