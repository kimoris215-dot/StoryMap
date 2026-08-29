<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>StoryMap — Workspace Pribadi Penulis</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root {
      --purple-900: #3b0764;
      --purple-800: #5b21b6;
      --purple-700: #6d28d9;
      --purple-600: #7c3aed;
      --purple-500: #8b5cf6;
      --purple-400: #a78bfa;
      --purple-300: #c4b5fd;
      --purple-200: #ddd6fe;
      --purple-100: #ede9fe;
      --purple-50: #f5f3ff;
      --green-500: #22c55e;
      --green-400: #4ade80;
      --gray-900: #111827;
      --gray-700: #374151;
      --gray-600: #4b5563;
      --gray-500: #6b7280;
      --gray-400: #9ca3af;
      --gray-200: #e5e7eb;
      --gray-100: #f3f4f6;
      --white: #ffffff;
      --shadow: 0 4px 20px rgba(109, 40, 217, 0.08);
      --radius: 16px;
      --radius-sm: 12px;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
      background: #f8f7fc;
      color: var(--gray-900);
      display: flex;
      min-height: 100vh;
      overflow-x: hidden;
    }

    /* ========== SIDEBAR ========== */
    .sidebar {
      width: 260px;
      background: linear-gradient(180deg, #2e1065 0%, #4c1d95 100%);
      color: white;
      display: flex;
      flex-direction: column;
      padding: 24px 16px;
      position: fixed;
      top: 0;
      left: 0;
      height: 100vh;
      z-index: 100;
      transition: transform 0.3s ease;
    }

    .logo {
      display: flex;
      align-items: center;
      gap: 10px;
      padding: 0 8px 28px;
    }

    .logo-icon {
      width: 42px;
      height: 42px;
      background: white;
      border-radius: 12px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 22px;
      font-weight: 800;
      color: var(--purple-700);
      box-shadow: 0 4px 12px rgba(0,0,0,0.15);
    }

    .logo-text h1 {
      font-size: 18px;
      font-weight: 800;
      letter-spacing: -0.3px;
    }

    .logo-text p {
      font-size: 11px;
      opacity: 0.7;
      margin-top: 2px;
    }

    .nav-menu {
      flex: 1;
      display: flex;
      flex-direction: column;
      gap: 4px;
    }

    .nav-item {
      display: flex;
      align-items: center;
      gap: 12px;
      padding: 12px 14px;
      border-radius: 12px;
      color: rgba(255,255,255,0.75);
      text-decoration: none;
      font-size: 14px;
      font-weight: 500;
      transition: all 0.2s;
      cursor: pointer;
    }

    .nav-item:hover {
      background: rgba(255,255,255,0.1);
      color: white;
    }

    .nav-item.active {
      background: #a3e635;
      color: #1a2e05;
      font-weight: 600;
    }

    .nav-item .icon {
      width: 22px;
      text-align: center;
      font-size: 18px;
    }

    .user-card {
      background: rgba(255,255,255,0.08);
      border-radius: 14px;
      padding: 14px;
      margin-top: 16px;
      display: flex;
      align-items: center;
      gap: 12px;
    }

    .user-avatar {
      width: 40px;
      height: 40px;
      border-radius: 50%;
      background: linear-gradient(135deg, #c4b5fd, #8b5cf6);
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: 700;
      font-size: 16px;
      color: white;
      overflow: hidden;
    }

    .user-info h4 {
      font-size: 14px;
      font-weight: 600;
    }

    .user-info p {
      font-size: 11px;
      opacity: 0.65;
    }

    .mascot-sidebar {
      margin-top: 16px;
      text-align: center;
      padding: 12px;
    }

    .mascot-sidebar img,
    .mascot-emoji {
      font-size: 64px;
      line-height: 1;
      filter: drop-shadow(0 4px 8px rgba(0,0,0,0.2));
    }

    .mascot-bubble {
      background: white;
      color: var(--purple-800);
      font-size: 12px;
      padding: 8px 12px;
      border-radius: 12px;
      margin-top: 8px;
      font-weight: 500;
      position: relative;
    }

    /* ========== MAIN CONTENT ========== */
    .main {
      margin-left: 260px;
      flex: 1;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    /* Header */
    .header {
      background: white;
      padding: 16px 32px;
      display: flex;
      align-items: center;
      gap: 20px;
      border-bottom: 1px solid var(--gray-200);
      position: sticky;
      top: 0;
      z-index: 50;
    }

    .search-box {
      flex: 1;
      max-width: 480px;
      position: relative;
    }

    .search-box input {
      width: 100%;
      padding: 12px 16px 12px 44px;
      border: 1.5px solid var(--gray-200);
      border-radius: 50px;
      font-size: 14px;
      background: var(--gray-100);
      outline: none;
      transition: all 0.2s;
    }

    .search-box input:focus {
      border-color: var(--purple-400);
      background: white;
      box-shadow: 0 0 0 3px rgba(139, 92, 246, 0.15);
    }

    .search-box .search-icon {
      position: absolute;
      left: 16px;
      top: 50%;
      transform: translateY(-50%);
      color: var(--gray-400);
      font-size: 16px;
    }

    .header-actions {
      display: flex;
      align-items: center;
      gap: 12px;
      margin-left: auto;
    }

    .icon-btn {
      width: 40px;
      height: 40px;
      border-radius: 50%;
      border: none;
      background: var(--gray-100);
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      font-size: 18px;
      transition: all 0.2s;
      position: relative;
    }

    .icon-btn:hover {
      background: var(--purple-100);
    }

    .icon-btn .badge {
      position: absolute;
      top: 6px;
      right: 6px;
      width: 8px;
      height: 8px;
      background: #ef4444;
      border-radius: 50%;
    }

    .profile-btn {
      width: 40px;
      height: 40px;
      border-radius: 50%;
      background: linear-gradient(135deg, #a78bfa, #7c3aed);
      border: 2px solid white;
      box-shadow: 0 2px 8px rgba(124, 58, 237, 0.3);
      cursor: pointer;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-weight: 700;
      font-size: 14px;
    }

    /* Content Area */
    .content {
      padding: 28px 32px 40px;
      flex: 1;
    }

    /* Welcome Banner */
    .welcome-banner {
      background: linear-gradient(135deg, #ede9fe 0%, #f3e8ff 50%, #fae8ff 100%);
      border-radius: 20px;
      padding: 28px 32px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 28px;
      position: relative;
      overflow: hidden;
    }

    .welcome-text h2 {
      font-size: 26px;
      font-weight: 800;
      color: var(--purple-900);
      margin-bottom: 8px;
    }

    .welcome-text p {
      font-size: 15px;
      color: var(--purple-800);
      opacity: 0.85;
      margin-bottom: 16px;
    }

    .quote-box {
      background: white;
      border-radius: 12px;
      padding: 12px 16px;
      font-size: 13px;
      color: var(--purple-800);
      max-width: 360px;
      box-shadow: 0 2px 10px rgba(109, 40, 217, 0.08);
      display: flex;
      align-items: flex-start;
      gap: 8px;
    }

    .quote-box span {
      font-size: 16px;
    }

    .mascot-welcome {
      font-size: 120px;
      line-height: 1;
      filter: drop-shadow(0 8px 16px rgba(109, 40, 217, 0.2));
      position: relative;
      z-index: 2;
    }

    .mascot-desk {
      position: absolute;
      right: 40px;
      bottom: 10px;
      font-size: 28px;
      opacity: 0.6;
    }

    /* Section Titles */
    .section-header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 16px;
    }

    .section-header h3 {
      font-size: 17px;
      font-weight: 700;
      color: var(--gray-900);
    }

    .section-header a {
      font-size: 13px;
      color: var(--purple-600);
      text-decoration: none;
      font-weight: 500;
    }

    .section-header a:hover {
      text-decoration: underline;
    }

    /* Grid Layout */
    .grid-2 {
      display: grid;
      grid-template-columns: 1.4fr 1fr;
      gap: 24px;
      margin-bottom: 28px;
    }

    .grid-3 {
      display: grid;
      grid-template-columns: 1.2fr 1fr;
      gap: 24px;
    }

    /* Cards */
    .card {
      background: white;
      border-radius: var(--radius);
      padding: 22px;
      box-shadow: var(--shadow);
      border: 1px solid rgba(139, 92, 246, 0.06);
    }

    /* Active Novel */
    .active-novel {
      display: flex;
      gap: 20px;
    }

    .novel-cover {
      width: 110px;
      height: 150px;
      border-radius: 12px;
      background: linear-gradient(160deg, #1e1b4b, #4c1d95);
      display: flex;
      align-items: flex-end;
      justify-content: center;
      padding: 12px;
      color: white;
      font-weight: 800;
      font-size: 14px;
      text-align: center;
      letter-spacing: 1px;
      box-shadow: 0 8px 20px rgba(76, 29, 149, 0.3);
      position: relative;
      overflow: hidden;
      flex-shrink: 0;
    }

    .novel-cover::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: url("data:image/svg+xml,%3Csvg width='100' height='100' viewBox='0 0 100 100' xmlns='http://www.w3.org/2000/svg'%3E%3Ccircle cx='50' cy='30' r='20' fill='%23ffffff10'/%3E%3C/svg%3E");
      opacity: 0.4;
    }

    .novel-info {
      flex: 1;
      display: flex;
      flex-direction: column;
    }

    .novel-info h4 {
      font-size: 20px;
      font-weight: 700;
      margin-bottom: 4px;
    }

    .novel-genre {
      font-size: 13px;
      color: var(--gray-500);
      margin-bottom: 12px;
    }

    .novel-stats {
      display: flex;
      flex-direction: column;
      gap: 6px;
      margin-bottom: 14px;
    }

    .stat-row {
      display: flex;
      align-items: center;
      gap: 8px;
      font-size: 13px;
      color: var(--gray-600);
    }

    .progress-bar {
      height: 8px;
      background: var(--gray-200);
      border-radius: 50px;
      overflow: hidden;
      margin-top: 4px;
    }

    .progress-fill {
      height: 100%;
      background: linear-gradient(90deg, var(--purple-600), var(--purple-400));
      border-radius: 50px;
      transition: width 0.5s ease;
    }

    .progress-text {
      font-size: 12px;
      color: var(--purple-600);
      font-weight: 600;
      margin-top: 4px;
    }

    .target-box {
      background: var(--purple-50);
      border-radius: 12px;
      padding: 14px 16px;
      margin-top: auto;
    }

    .target-box p {
      font-size: 12px;
      color: var(--purple-700);
      margin-bottom: 4px;
    }

    .target-box strong {
      font-size: 14px;
      color: var(--purple-900);
    }

    .btn-primary {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      background: var(--purple-600);
      color: white;
      border: none;
      padding: 11px 20px;
      border-radius: 12px;
      font-size: 14px;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.2s;
      margin-top: 14px;
    }

    .btn-primary:hover {
      background: var(--purple-700);
      transform: translateY(-1px);
      box-shadow: 0 4px 12px rgba(124, 58, 237, 0.35);
    }

    /* Quick Access */
    .quick-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 12px;
    }

    .quick-item {
      background: var(--gray-50);
      border: 1px solid var(--gray-200);
      border-radius: 14px;
      padding: 16px;
      display: flex;
      flex-direction: column;
      gap: 8px;
      cursor: pointer;
      transition: all 0.2s;
      text-decoration: none;
      color: inherit;
    }

    .quick-item:hover {
      border-color: var(--purple-300);
      background: var(--purple-50);
      transform: translateY(-2px);
    }

    .quick-icon {
      width: 36px;
      height: 36px;
      border-radius: 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 18px;
    }

    .quick-item h5 {
      font-size: 13px;
      font-weight: 600;
    }

    .quick-item p {
      font-size: 11px;
      color: var(--gray-500);
    }

    /* Novel List */
    .novel-list {
      display: flex;
      flex-direction: column;
      gap: 14px;
    }

    .novel-row {
      display: flex;
      align-items: center;
      gap: 14px;
      padding: 10px;
      border-radius: 12px;
      transition: background 0.2s;
      cursor: pointer;
    }

    .novel-row:hover {
      background: var(--purple-50);
    }

    .novel-row-cover {
      width: 48px;
      height: 64px;
      border-radius: 8px;
      background: linear-gradient(160deg, #312e81, #5b21b6);
      flex-shrink: 0;
      display: flex;
      align-items: flex-end;
      justify-content: center;
      padding: 4px;
      color: white;
      font-size: 8px;
      font-weight: 700;
      text-align: center;
    }

    .novel-row-info {
      flex: 1;
    }

    .novel-row-info h5 {
      font-size: 14px;
      font-weight: 600;
      margin-bottom: 2px;
    }

    .novel-row-info p {
      font-size: 12px;
      color: var(--gray-500);
    }

    .novel-row-progress {
      width: 100px;
    }

    .mini-progress {
      height: 6px;
      background: var(--gray-200);
      border-radius: 50px;
      overflow: hidden;
    }

    .mini-progress-fill {
      height: 100%;
      border-radius: 50px;
    }

    .mini-progress-fill.purple { background: var(--purple-500); }
    .mini-progress-fill.green { background: var(--green-500); }

    .btn-add {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
      width: 100%;
      padding: 12px;
      border: 2px dashed var(--purple-300);
      border-radius: 12px;
      background: var(--purple-50);
      color: var(--purple-700);
      font-weight: 600;
      font-size: 14px;
      cursor: pointer;
      margin-top: 12px;
      transition: all 0.2s;
    }

    .btn-add:hover {
      background: var(--purple-100);
      border-color: var(--purple-500);
    }

    /* Idea Vault */
    .idea-list {
      display: flex;
      flex-direction: column;
      gap: 12px;
    }

    .idea-item {
      display: flex;
      align-items: flex-start;
      gap: 12px;
      padding: 10px 0;
      border-bottom: 1px solid var(--gray-100);
    }

    .idea-item:last-child {
      border-bottom: none;
    }

    .idea-icon {
      width: 32px;
      height: 32px;
      border-radius: 8px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 14px;
      flex-shrink: 0;
    }

    .idea-content h5 {
      font-size: 13px;
      font-weight: 600;
      margin-bottom: 2px;
    }

    .idea-content p {
      font-size: 12px;
      color: var(--gray-500);
    }

    .idea-time {
      font-size: 11px;
      color: var(--gray-400);
      margin-left: auto;
      white-space: nowrap;
    }

    .btn-add-green {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
      width: 100%;
      padding: 12px;
      border: none;
      border-radius: 12px;
      background: #a3e635;
      color: #1a2e05;
      font-weight: 600;
      font-size: 14px;
      cursor: pointer;
      margin-top: 12px;
      transition: all 0.2s;
    }

    .btn-add-green:hover {
      background: #84cc16;
      transform: translateY(-1px);
    }

    /* Mobile Nav */
    .mobile-nav {
      display: none;
      position: fixed;
      bottom: 0;
      left: 0;
      right: 0;
      background: white;
      border-top: 1px solid var(--gray-200);
      padding: 8px 12px 12px;
      z-index: 100;
      justify-content: space-around;
    }

    .mobile-nav-item {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 4px;
      font-size: 11px;
      color: var(--gray-500);
      text-decoration: none;
      padding: 6px 12px;
      border-radius: 10px;
    }

    .mobile-nav-item.active {
      color: var(--purple-700);
      background: var(--purple-50);
    }

    .mobile-nav-item .icon {
      font-size: 20px;
    }

    /* Menu Toggle */
    .menu-toggle {
      display: none;
      width: 40px;
      height: 40px;
      border: none;
      background: var(--gray-100);
      border-radius: 10px;
      font-size: 20px;
      cursor: pointer;
    }

    /* Overlay */
    .sidebar-overlay {
      display: none;
      position: fixed;
      inset: 0;
      background: rgba(0,0,0,0.4);
      z-index: 90;
    }

    /* ========== RESPONSIVE ========== */
    @media (max-width: 1100px) {
      .grid-2, .grid-3 {
        grid-template-columns: 1fr;
      }
    }

    @media (max-width: 900px) {
      .sidebar {
        transform: translateX(-100%);
      }

      .sidebar.open {
        transform: translateX(0);
      }

      .sidebar-overlay.open {
        display: block;
      }

      .main {
        margin-left: 0;
      }

      .menu-toggle {
        display: flex;
        align-items: center;
        justify-content: center;
      }

      .mobile-nav {
        display: flex;
      }

      .content {
        padding: 20px 16px 90px;
      }

      .header {
        padding: 12px 16px;
      }

      .welcome-banner {
        flex-direction: column;
        text-align: center;
        padding: 24px 20px;
      }

      .mascot-welcome {
        font-size: 90px;
        margin-top: 12px;
      }

      .quote-box {
        max-width: 100%;
        text-align: left;
      }

      .active-novel {
        flex-direction: column;
        align-items: center;
        text-align: center;
      }

      .novel-stats {
        align-items: center;
      }
    }

    /* Simple page switching */
    .page {
      display: none;
    }

    .page.active {
      display: block;
    }

    /* Placeholder pages */
    .placeholder-page {
      text-align: center;
      padding: 60px 20px;
    }

    .placeholder-page .big-icon {
      font-size: 64px;
      margin-bottom: 16px;
    }

    .placeholder-page h2 {
      font-size: 24px;
      margin-bottom: 8px;
      color: var(--purple-800);
    }

    .placeholder-page p {
      color: var(--gray-500);
      max-width: 400px;
      margin: 0 auto 24px;
    }
  </style>
</head>
<body>

  <!-- Sidebar Overlay (mobile) -->
  <div class="sidebar-overlay" id="overlay" onclick="closeSidebar()"></div>

  <!-- ========== SIDEBAR ========== -->
  <aside class="sidebar" id="sidebar">
    <div class="logo">
      <div class="logo-icon">📖</div>
      <div class="logo-text">
        <h1>StoryMap</h1>
        <p>Workspace Pribadi</p>
      </div>
    </div>

    <nav class="nav-menu">
      <a class="nav-item active" data-page="beranda" onclick="switchPage('beranda', this)">
        <span class="icon">🏠</span> Beranda
      </a>
      <a class="nav-item" data-page="novelku" onclick="switchPage('novelku', this)">
        <span class="icon">📚</span> Novelku
      </a>
      <a class="nav-item" data-page="chapter" onclick="switchPage('chapter', this)">
        <span class="icon">📑</span> Chapter Manager
      </a>
      <a class="nav-item" data-page="planner" onclick="switchPage('planner', this)">
        <span class="icon">🗺️</span> Story Planner
      </a>
      <a class="nav-item" data-page="character" onclick="switchPage('character', this)">
        <span class="icon">👤</span> Character Database
      </a>
      <a class="nav-item" data-page="catatan" onclick="switchPage('catatan', this)">
        <span class="icon">💬</span> Catatan Konsultasi
      </a>
      <a class="nav-item" data-page="ide" onclick="switchPage('ide', this)">
        <span class="icon">💡</span> Idea Vault
      </a>
      <a class="nav-item" data-page="progress" onclick="switchPage('progress', this)">
        <span class="icon">📊</span> Writing Progress
      </a>
      <a class="nav-item" data-page="pengaturan" onclick="switchPage('pengaturan', this)">
        <span class="icon">⚙️</span> Pengaturan
      </a>
    </nav>

    <div class="user-card">
      <div class="user-avatar">N</div>
      <div class="user-info">
        <h4>Nazari</h4>
        <p>Penulis • Dreamer</p>
      </div>
    </div>

    <div class="mascot-sidebar">
      <div class="mascot-emoji">👾</div>
      <div class="mascot-bubble">Terus menulis, ceritamu luar biasa! 💜</div>
    </div>
  </aside>

  <!-- ========== MAIN ========== -->
  <div class="main">
    <!-- Header -->
    <header class="header">
      <button class="menu-toggle" onclick="toggleSidebar()">☰</button>
      <div class="search-box">
        <span class="search-icon">🔍</span>
        <input type="text" placeholder="Cari di StoryMap..." />
      </div>
      <div class="header-actions">
        <button class="icon-btn">🔔<span class="badge"></span></button>
        <button class="icon-btn">✉️</button>
        <div class="profile-btn">N</div>
      </div>
    </header>

    <!-- Content -->
    <div class="content">

      <!-- ===== PAGE: BERANDA ===== -->
      <div class="page active" id="page-beranda">
        <!-- Welcome Banner -->
        <div class="welcome-banner">
          <div class="welcome-text">
            <h2>Halo, Nazari! 👋</h2>
            <p>Mari kembangkan ceritamu hari ini.</p>
            <div class="quote-box">
              <span>💜</span>
              <div>"Setiap kata yang kamu tulis adalah langkah menuju novelnya yang luar biasa."</div>
            </div>
          </div>
          <div class="mascot-welcome">👾</div>
        </div>

        <!-- Active Novel + Quick Access -->
        <div class="grid-2">
          <!-- Active Novel -->
          <div class="card">
            <div class="section-header">
              <h3>Novel Aktif</h3>
              <a href="#" onclick="switchPage('novelku')">Lihat Semua Novel</a>
            </div>
            <div class="active-novel">
              <div class="novel-cover">MADONA</div>
              <div class="novel-info">
                <h4>Madona</h4>
                <p class="novel-genre">Romance • Thriller</p>
                <div class="novel-stats">
                  <div class="stat-row">📑 12 / 30 Chapter</div>
                  <div class="stat-row">✍️ 42.500 / 80.000 kata</div>
                </div>
                <div class="progress-bar">
                  <div class="progress-fill" style="width: 40%"></div>
                </div>
                <div class="progress-text">40%</div>

                <div class="target-box">
                  <p>Target Berikutnya</p>
                  <strong>Selesaikan Chapter 13</strong>
                  <p style="margin-top:6px;font-size:12px;opacity:0.8">Konflik utama dan motif karakter diperjelas.</p>
                </div>
                <button class="btn-primary" onclick="switchPage('editor')">Lanjut Menulis →</button>
              </div>
            </div>
          </div>

          <!-- Quick Access -->
          <div class="card">
            <div class="section-header">
              <h3>Quick Access</h3>
            </div>
            <div class="quick-grid">
              <a class="quick-item" onclick="switchPage('editor')">
                <div class="quick-icon" style="background:#ede9fe;">✏️</div>
                <h5>Tulis Novel</h5>
                <p>Mulai menulis chapter baru</p>
              </a>
              <a class="quick-item" onclick="switchPage('planner')">
                <div class="quick-icon" style="background:#dcfce7;">🗺️</div>
                <h5>Story Planner</h5>
                <p>Atur alur, konflik, dan plot</p>
              </a>
              <a class="quick-item" onclick="switchPage('character')">
                <div class="quick-icon" style="background:#e0e7ff;">👤</div>
                <h5>Character Database</h5>
                <p>Kelola karakter & hubungan</p>
              </a>
              <a class="quick-item" onclick="switchPage('chapter')">
                <div class="quick-icon" style="background:#fef3c7;">📑</div>
                <h5>Chapter Manager</h5>
                <p>Kelola semua chapter novel</p>
              </a>
              <a class="quick-item" onclick="switchPage('catatan')">
                <div class="quick-icon" style="background:#fce7f3;">💬</div>
                <h5>Catatan Konsultasi</h5>
                <p>Lihat masukan dan revisi</p>
              </a>
              <a class="quick-item" onclick="switchPage('ide')">
                <div class="quick-icon" style="background:#fef9c3;">💡</div>
                <h5>Idea Vault</h5>
                <p>Simpan semua ide cemerlang</p>
              </a>
            </div>
          </div>
        </div>

        <!-- Daftar Novel + Idea Vault -->
        <div class="grid-3">
          <!-- Daftar Novel -->
          <div class="card">
            <div class="section-header">
              <h3>Daftar Novelku</h3>
              <a href="#" onclick="switchPage('novelku')">Lihat Semua</a>
            </div>
            <div class="novel-list">
              <div class="novel-row">
                <div class="novel-row-cover">MADONA</div>
                <div class="novel-row-info">
                  <h5>Madona</h5>
                  <p>Romance • Thriller</p>
                </div>
                <div class="novel-row-progress">
                  <div class="mini-progress">
                    <div class="mini-progress-fill purple" style="width:40%"></div>
                  </div>
                  <div style="font-size:11px;color:#6b7280;margin-top:4px;text-align:right">12/30 • 40%</div>
                </div>
              </div>
              <div class="novel-row">
                <div class="novel-row-cover" style="background:linear-gradient(160deg,#0f172a,#1e3a5f)">THE LAST</div>
                <div class="novel-row-info">
                  <h5>The Last Winter</h5>
                  <p>Drama • Romantis</p>
                </div>
                <div class="novel-row-progress">
                  <div class="mini-progress">
                    <div class="mini-progress-fill green" style="width:32%"></div>
                  </div>
                  <div style="font-size:11px;color:#6b7280;margin-top:4px;text-align:right">8/25 • 32%</div>
                </div>
              </div>
              <div class="novel-row">
                <div class="novel-row-cover" style="background:linear-gradient(160deg,#1c1917,#44403c)">BENEATH</div>
                <div class="novel-row-info">
                  <h5>Beneath The Lies</h5>
                  <p>Mystery • Thriller</p>
                </div>
                <div class="novel-row-progress">
                  <div class="mini-progress">
                    <div class="mini-progress-fill green" style="width:25%"></div>
                  </div>
                  <div style="font-size:11px;color:#6b7280;margin-top:4px;text-align:right">5/20 • 25%</div>
                </div>
              </div>
            </div>
            <button class="btn-add">+ Tambah Novel Baru</button>
          </div>

          <!-- Idea Vault Terbaru -->
          <div class="card">
            <div class="section-header">
              <h3>Idea Vault Terbaru</h3>
              <a href="#" onclick="switchPage('ide')">Lihat Semua</a>
            </div>
            <div class="idea-list">
              <div class="idea-item">
                <div class="idea-icon" style="background:#fef3c7;">☀️</div>
                <div class="idea-content">
                  <h5>Plot Twist</h5>
                  <p>Ide plot twist untuk bagian tengah cerita...</p>
                </div>
                <div class="idea-time">2 jam lalu</div>
              </div>
              <div class="idea-item">
                <div class="idea-icon" style="background:#dbeafe;">💬</div>
                <div class="idea-content">
                  <h5>Dialog</h5>
                  <p>Dialog emosional antara Junghwan & Madona</p>
                </div>
                <div class="idea-time">Kemarin</div>
              </div>
              <div class="idea-item">
                <div class="idea-icon" style="background:#fce7f3;">🎬</div>
                <div class="idea-content">
                  <h5>Scene</h5>
                  <p>Adegan hujan di atap gedung tua</p>
                </div>
                <div class="idea-time">2 hari lalu</div>
              </div>
              <div class="idea-item">
                <div class="idea-icon" style="background:#ede9fe;">👤</div>
                <div class="idea-content">
                  <h5>Karakter</h5>
                  <p>Ide karakter sampingan yang menarik</p>
                </div>
                <div class="idea-time">3 hari lalu</div>
              </div>
            </div>
            <button class="btn-add-green">+ Tambah Ide Baru</button>
          </div>
        </div>
      </div>

      <!-- ===== OTHER PAGES (placeholder) ===== -->
      <div class="page" id="page-novelku">
        <div class="placeholder-page">
          <div class="big-icon">📚</div>
          <h2>Novelku</h2>
          <p>Kumpulan semua novelmu. Pilih novel untuk masuk workspace.</p>
          <button class="btn-primary" onclick="switchPage('beranda')">← Kembali ke Beranda</button>
        </div>
      </div>

      <div class="page" id="page-chapter">
        <div class="placeholder-page">
          <div class="big-icon">📑</div>
          <h2>Chapter Manager</h2>
          <p>Kelola, urutkan, dan atur status chapter novelmu.</p>
          <button class="btn-primary" onclick="switchPage('beranda')">← Kembali ke Beranda</button>
        </div>
      </div>

      <div class="page" id="page-planner">
        <div class="placeholder-page">
          <div class="big-icon">🗺️</div>
          <h2>Story Planner</h2>
          <p>Rancang alur cerita dengan struktur yang jelas (Plot, Timeline, Conflict, Scene).</p>
          <button class="btn-primary" onclick="switchPage('beranda')">← Kembali ke Beranda</button>
        </div>
      </div>

      <div class="page" id="page-character">
        <div class="placeholder-page">
          <div class="big-icon">👤</div>
          <h2>Character Database</h2>
          <p>Database karakter lengkap dengan detail, hubungan, dan arc.</p>
          <button class="btn-primary" onclick="switchPage('beranda')">← Kembali ke Beranda</button>
        </div>
      </div>

      <div class="page" id="page-catatan">
        <div class="placeholder-page">
          <div class="big-icon">💬</div>
          <h2>Catatan Konsultasi</h2>
          <p>Simpan semua masukan dari konsultasi dan revisi.</p>
          <button class="btn-primary" onclick="switchPage('beranda')">← Kembali ke Beranda</button>
        </div>
      </div>

      <div class="page" id="page-ide">
        <div class="placeholder-page">
          <div class="big-icon">💡</div>
          <h2>Idea Vault</h2>
          <p>Simpan semua ide cerita, dialog, scene, dan lainnya.</p>
          <button class="btn-primary" onclick="switchPage('beranda')">← Kembali ke Beranda</button>
        </div>
      </div>

      <div class="page" id="page-progress">
        <div class="placeholder-page">
          <div class="big-icon">📊</div>
          <h2>Writing Progress</h2>
          <p>Pantau progres menulis dan statistikmu (streak, total kata, dll).</p>
          <button class="btn-primary" onclick="switchPage('beranda')">← Kembali ke Beranda</button>
        </div>
      </div>

      <div class="page" id="page-pengaturan">
        <div class="placeholder-page">
          <div class="big-icon">⚙️</div>
          <h2>Pengaturan</h2>
          <p>Atur preferensi workspace, tema, dan profil penulis.</p>
          <button class="btn-primary" onclick="switchPage('beranda')">← Kembali ke Beranda</button>
        </div>
      </div>

      <div class="page" id="page-editor">
        <div class="placeholder-page">
          <div class="big-icon">✏️</div>
          <h2>Editor / Menulis</h2>
          <p>Fokus menulis tanpa gangguan. Mode distraction-free segera hadir.</p>
          <button class="btn-primary" onclick="switchPage('beranda')">← Kembali ke Beranda</button>
        </div>
      </div>

    </div>
  </div>

  <!-- Mobile Bottom Nav -->
  <nav class="mobile-nav">
    <a class="mobile-nav-item active" onclick="switchPage('beranda')">
      <span class="icon">🏠</span>
      <span>Home</span>
    </a>
    <a class="mobile-nav-item" onclick="switchPage('novelku')">
      <span class="icon">📚</span>
      <span>Novel</span>
    </a>
    <a class="mobile-nav-item" onclick="switchPage('editor')">
      <span class="icon">✏️</span>
      <span>Write</span>
    </a>
    <a class="mobile-nav-item" onclick="switchPage('ide')">
      <span class="icon">💡</span>
      <span>Ideas</span>
    </a>
    <a class="mobile-nav-item" onclick="switchPage('progress')">
      <span class="icon">📊</span>
      <span>More</span>
    </a>
  </nav>

  <script>
    function switchPage(pageId, el) {
      // Hide all pages
      document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
      // Show target
      const target = document.getElementById('page-' + pageId);
      if (target) target.classList.add('active');

      // Update sidebar active
      document.querySelectorAll('.nav-item').forEach(item => item.classList.remove('active'));
      if (el) {
        el.classList.add('active');
      } else {
        const match = document.querySelector(`.nav-item[data-page="${pageId}"]`);
        if (match) match.classList.add('active');
      }

      // Update mobile nav
      document.querySelectorAll('.mobile-nav-item').forEach(item => item.classList.remove('active'));
      
      // Close sidebar on mobile
      closeSidebar();
      
      // Scroll to top
      window.scrollTo({ top: 0, behavior: 'smooth' });
    }

    function toggleSidebar() {
      document.getElementById('sidebar').classList.toggle('open');
      document.getElementById('overlay').classList.toggle('open');
    }

    function closeSidebar() {
      document.getElementById('sidebar').classList.remove('open');
      document.getElementById('overlay').classList.remove('open');
    }
  </script>
</body>
</html>
