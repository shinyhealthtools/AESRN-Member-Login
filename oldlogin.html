<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0">
    <title>AESRN Member Login Portal</title>
    <link rel="icon" href="https://raw.githubusercontent.com/mudassiribrahim12/AESRN-website/main/favicon-32x32.png" type="image/png">
    <meta name="google-site-verification" content="6zzEO7tBZ4x_xpC3utqGKn3jJekDVz2EkfZ7rCODSqQ" />
    <link rel="apple-touch-icon" sizes="180x180" href="https://raw.githubusercontent.com/mudassiribrahim12/AESRN-website/main/apple-touch-icon.png">
    <!-- Font Awesome & Calendar -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link href="https://cdn.jsdelivr.net/npm/fullcalendar@5.11.3/main.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/fullcalendar@5.11.3/main.min.js"></script>
    <!-- REMOVED logwork widget script -->
    <style>
        * { margin:0; padding:0; box-sizing:border-box; }
        body { 
            font-family: 'Inter', 'Segoe UI', Roboto, sans-serif; 
            background: #f0f2f5;
            display: flex; 
            flex-direction: column; 
            min-height: 100vh;
            transition: background-color 0.3s ease, color 0.2s ease;
        }
        
        /* DARK THEME VARIABLES (applied to body.dark-theme) */
        body.dark-theme {
            background: #121212;
            color: #e0e0e0;
        }
        body.dark-theme .login-card,
        body.dark-theme .dashboard-header,
        body.dark-theme .profile-card,
        body.dark-theme .calendar-card,
        body.dark-theme .action-tile,
        body.dark-theme .member-card,
        body.dark-theme .dashboard-footer,
        body.dark-theme .modal-card,
        body.dark-theme .inactivity-box,
        body.dark-theme .logout-notification {
            background: #1e1e1e;
            border-color: #333;
            color: #f0f0f0;
            box-shadow: 0 10px 25px -5px rgba(0,0,0,0.5);
        }
        body.dark-theme .login-title,
        body.dark-theme .profile-info h2,
        body.dark-theme .member-card-name,
        body.dark-theme .section-title,
        body.dark-theme .tile-title,
        body.dark-theme .calendar-header span {
            color: #ffffff !important;
        }
        body.dark-theme .form-label,
        body.dark-theme .profile-info .member-title,
        body.dark-theme .member-card-title,
        body.dark-theme .footer-links a {
            color: #cccccc;
        }
        body.dark-theme .form-input {
            background: #2a2a2a;
            border-color: #444;
            color: #f0f0f0;
        }
        body.dark-theme .form-input:focus {
            border-color: #6aa9d6;
            box-shadow: 0 0 0 3px rgba(106,169,214,0.2);
        }
        body.dark-theme .tile-desc {
            color: #aaa;
            border-top-color: #333;
        }
        body.dark-theme .member-card-workplace {
            color: #bbb;
        }
        body.dark-theme .member-card-email {
            background: #2a2a2a;
            color: #bbd6f0;
            border-color: #444;
        }
        body.dark-theme .dashboard-footer {
            color: #ccc;
        }
        body.dark-theme .go-to-aesrn {
            color: #8bb9e0;
            border-top-color: #333;
        }
        body.dark-theme .normal-time {
            background: rgba(255,255,255,0.1);
            color: #e0e0e0;
        }
        body.dark-theme .normal-time i {
            color: #8bb9e0;
        }
        body.dark-theme .back-to-dashboard {
            background: #3a6d9a;
            color: white;
        }
        /* Dark theme toggle button */
        .theme-toggle {
            background: none;
            border: none;
            font-size: 1.6rem;
            cursor: pointer;
            color: #5f7d9c;
            transition: transform 0.2s, color 0.2s;
            padding: 8px;
            line-height: 1;
        }
        .theme-toggle:hover {
            transform: scale(1.15);
            color: #2A5C82;
        }
        body.dark-theme .theme-toggle {
            color: #ffdb70;
        }
        body.dark-theme .theme-toggle:hover {
            color: #ffb347;
        }
        /* Login page specific - toggle positioned outside card */
        .login-page-header {
            position: absolute;
            top: 20px;
            right: 30px;
            z-index: 100;
        }
        
        .normal-time {
            font-weight: 600;
            font-size: 0.95rem;
            background: rgba(42,92,130,0.1);
            padding: 6px 14px;
            border-radius: 40px;
            display: inline-flex;
            align-items: center;
            gap: 6px;
            color: #1e3c5c;
            transition: background 0.2s;
        }
        
/* LOGIN PAGE - Studio background with box pattern (consistent with AESRN main site) */
.login-container { 
    display:flex; 
    justify-content:center; 
    align-items:center; 
    min-height:100vh; 
    background-color: #fafafa;  /* Same as main site --bg variable */
    background-image: 
        linear-gradient(rgba(0, 0, 0, 0.02) 1px, transparent 1px),
        linear-gradient(90deg, rgba(0, 0, 0, 0.02) 1px, transparent 1px);
    background-size: 40px 40px;  /* Same 40px grid as main site */
    padding:16px; 
    transition: background 0.3s;
    position: relative;
}

/* Dark theme studio background with box pattern */
body.dark-theme .login-container { 
    background-color: #0a0a0a;  /* Same as main site dark --bg */
    background-image: 
        linear-gradient(rgba(255, 255, 255, 0.02) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255, 255, 255, 0.02) 1px, transparent 1px);
    background-size: 40px 40px;
}
/* LOGIN CARD - Compact size */
.login-card { 
    background:white; 
    border-radius:24px !important; 
    padding:24px;  
    width:100%; 
    max-width:340px;  
    box-shadow:0 30px 60px -15px rgba(0,0,0,0.2);
    transition:opacity 0.3s, transform 0.3s; 
    border: 2px solid transparent;
    background-image: linear-gradient(white, white), linear-gradient(135deg, #000000, #000000);
    background-origin: border-box;
    background-clip: padding-box, border-box;
}

        .login-logo { text-align:center; margin-bottom:16px; }
        .login-logo img { 
            width:160px;
            height:160px; 
            object-fit:contain; 
        }
        .login-title { font-size:18px; font-weight:700; color:#1e3c5c; text-align:center; margin-bottom:20px; letter-spacing:-0.3px; }
        .form-group { margin-bottom:16px; }
        .form-label { font-weight:600; font-size:13px; color:#1e2e44; margin-bottom:4px; display:block; }
        .required-asterisk { color:#E63946; margin-left:4px; font-weight:700; }
        .form-input { width:100%; padding:10px 14px; border:1px solid #d4deec; border-radius:8px; font-size:14px; font-weight:500; transition:0.2s; background:white; }
        .form-input:focus { outline:none; border-color:#2A5C82; box-shadow:0 0 0 3px rgba(42,92,130,0.15); }
        .password-wrapper { position:relative; }
        .toggle-password { position:absolute; right:12px; top:50%; transform:translateY(-50%); background:none; border:none; cursor:pointer; color:#7c8b9c; }
  /* ===== FORCE STABLE LOGIN BUTTON - NO FLICKER ===== */
.login-btn {
    width: 100%;
    background: #2A5C82 !important;
    color: white !important;
    border: none !important;
    padding: 12px !important;
    border-radius: 8px !important;
    font-weight: 700 !important;
    font-size: 15px !important;
    cursor: pointer !important;
    box-shadow: 0 8px 18px rgba(42,92,130,0.2) !important;
    
    /* Force stable rendering */
    transition: none !important;
    transform: none !important;
    animation: none !important;
    backdrop-filter: none !important;
    -webkit-backdrop-filter: none !important;
    filter: none !important;
    will-change: auto !important;
    
    /* Hardware acceleration OFF */
    -webkit-transform: none !important;
    -moz-transform: none !important;
    -ms-transform: none !important;
    -o-transform: none !important;
    
    /* Force single layer */
    position: relative;
    z-index: 1;
}

.login-btn:hover:not(:disabled) {
    background: #1e4a6e !important;
    box-shadow: 0 12px 22px rgba(42,92,130,0.3) !important;
    
    /* No transitions on hover either */
    transition: none !important;
    transform: none !important;
}

.login-btn:active:not(:disabled) {
    transform: scale(0.98) !important;  /* Only scale on click, not hover */
    transition: transform 0.1s ease !important;  /* Quick click feedback only */
}

.login-btn:disabled {
    opacity: 0.5 !important;
    cursor: not-allowed !important;
    background: #a0b8cc !important;
    box-shadow: none !important;
    pointer-events: none !important;
    transform: none !important;
}

/* Remove any pseudo-element effects that might cause flickering */
.login-btn::before,
.login-btn::after {
    display: none !important;
}

/* ===== DARK MODE MEMBER CARDS - CRISP WHITE TEXT ===== */
body.dark-theme .member-card {
    background: #1e1e1e;
    border-color: #333;
}

body.dark-theme .member-card-name {
    color: #ffffff !important;
    font-weight: 700;
    text-shadow: 0 1px 2px rgba(0,0,0,0.2);
}

body.dark-theme .member-card-title {
    color: #e0e0e0 !important;
    background: rgba(255,255,255,0.1);
}

body.dark-theme .member-card-workplace {
    color: #dddddd !important;
}

body.dark-theme .member-card-workplace i {
    color: #8bb9e0 !important;
}

body.dark-theme .member-card-email {
    color: #ffffff !important;
    background: rgba(255,255,255,0.15);
    border-color: rgba(255,255,255,0.2);
}

body.dark-theme .view-indicator {
    color: #8bb9e0 !important;
    opacity: 0.9;
}

body.dark-theme .member-card:hover .view-indicator {
    opacity: 1;
    color: #aaccff !important;
}

/* Profile card text in dark mode */
body.dark-theme .profile-info h2 {
    color: #ffffff !important;
    background: none;
    -webkit-text-fill-color: white;
}

body.dark-theme .profile-info .member-title {
    color: #e0e0e0 !important;
}

body.dark-theme .profile-info .workplace {
    color: #cccccc !important;
}

/* Login page copyright - at background bottom, with powered by at right */
.login-page-copyright {
    position: absolute;
    bottom: 20px;
    left: 0;
    right: 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 30px;
    font-size: 13px;
    color: #1a4b73 !important; /* Deep, clear blue */
    font-weight: 500;
    z-index: 10;
    pointer-events: none; /* So it doesn't interfere with clicks */
    width: 100%;
}

.powered-by {
    font-weight: 600;
    color: #1a4b73 !important;
    letter-spacing: 0.3px;
}

/* Dark theme for login copyright - bright clear blue */
body.dark-theme .login-page-copyright,
body.dark-theme .powered-by {
    color: #4d9fff !important; /* Bright, clear blue for dark mode */
    font-weight: 600;
    text-shadow: 0 1px 3px rgba(0,0,0,0.3);
    opacity: 1; /* Full opacity */
}

/* Ensure login container has relative positioning for absolute copyright */
.login-container {
    position: relative !important;
}

/* Responsive adjustment for mobile */
@media (max-width: 700px) {
    .login-page-copyright {
        flex-direction: column;
        gap: 5px;
        text-align: center;
        padding: 10px 15px;
        font-size: 12px;
    }
}

/* Section titles in dark mode */
body.dark-theme .section-title {
    color: #ffffff !important;
    background: none;
    -webkit-text-fill-color: white;
}

body.dark-theme .section-title i {
    color: #8bb9e0 !important;
}

/* Force stable parent containers */
.login-card, .login-container, .login-btn-wrapper {
    transform: none !important;
    animation: none !important;
    transition: none !important;
    backdrop-filter: none !important;
    -webkit-backdrop-filter: none !important;
}
        .error-msg { color:#c62828; background:#ffebee; padding:10px; border-radius:8px; font-size:13px; font-weight:600; margin-top:14px; display:none; text-align:center; }
        .attempts-warning { color:#b85a00; background:#fff1e0; padding:8px; border-radius:8px; font-size:12px; font-weight:600; margin-top:10px; display:none; text-align:center; }
        .go-to-aesrn { display:flex; align-items:center; justify-content:center; gap:8px; margin-top:16px; padding-top:14px; border-top:1px solid #e0e8f0; color:#2A5C82; text-decoration:none; font-weight:600; font-size:14px; }
        .go-to-aesrn i { transition:transform 0.2s; }
        .go-to-aesrn:hover i { transform:translateX(-4px); }
        
        /* LOADERS */
        .global-loader-circle { position:fixed; inset:0; background:#f0f2f5; display:flex; flex-direction:column; align-items:center; justify-content:center; z-index:20000; opacity:0; visibility:hidden; transition:0.3s; }
        .global-loader-circle.active { opacity:1; visibility:visible; }
        .circle-spinner { width:70px; height:70px; border:6px solid rgba(42,92,130,0.15); border-top:6px solid #2A5C82; border-radius:50%; animation:spin 1s linear infinite; margin-bottom:24px; }
        .circle-text { font-size:18px; font-weight:600; color:#2A5C82; }
        @keyframes spin { to { transform:rotate(360deg); } }
        
        .app-loader { position:fixed; inset:0; background:#f0f2f5; display:flex; flex-direction:column; align-items:center; justify-content:center; z-index:10000; transition:opacity 0.4s; }
        .app-loader img { width:120px; height:120px; object-fit:contain; animation:pulse 1.5s infinite; margin-bottom:20px; }
        .app-loader div { color:#2A5C82; font-weight:600; font-size:18px; }
        @keyframes pulse { 0% { opacity:0.8; transform:scale(1); } 50% { opacity:1; transform:scale(1.05); } }
        
          /* DASHBOARD TRANSITION LOADER */
        .dashboard-loader {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(8px);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            z-index: 15000;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.3s ease, visibility 0.3s ease;
        }
        body.dark-theme .dashboard-loader {
            background: rgba(18, 18, 18, 0.95);
        }
        .dashboard-loader.active {
            opacity: 1;
            visibility: visible;
        }
        .dashboard-loader .spinner {
            width: 60px;
            height: 60px;
            border: 4px solid rgba(42,92,130,0.1);
            border-top: 4px solid #2A5C82;
            border-radius: 50%;
            animation: spin 0.8s linear infinite;
            margin-bottom: 20px;
        }
        body.dark-theme .dashboard-loader .spinner {
            border: 4px solid rgba(255,255,255,0.1);
            border-top: 4px solid #6aa9d6;
        }
        .dashboard-loader .text {
            color: #2A5C82;
            font-weight: 600;
            font-size: 16px;
            letter-spacing: 0.5px;
        }
        body.dark-theme .dashboard-loader .text {
            color: #e0e0e0;
        }
        
                /* Force dark mode for all loaders */
        body.dark-theme .dashboard-loader,
        body.dark-theme #globalCircleLoader,
        body.dark-theme #pageTransitionLoader,
        body.dark-theme .global-loader-circle,
        body.dark-theme .app-loader {
            background: #121212 !important;
        }
        
        body.dark-theme .dashboard-loader .text,
        body.dark-theme .circle-text,
        body.dark-theme .app-loader div {
            color: #e0e0e0 !important;
        }
        
        body.dark-theme .dashboard-loader .spinner,
        body.dark-theme .circle-spinner {
            border-color: rgba(255,255,255,0.1) !important;
            border-top-color: #6aa9d6 !important;
        }
        
        /* DASHBOARD - NO ENTRY ANIMATIONS */
        .dashboard { 
            display:none; 
            flex:1; 
            background:#f8fafd; 
            padding:20px; 
            width:100%; 
            min-height:100vh;
            transition: background 0.3s;
        }
        body.dark-theme .dashboard { background:#121212; }
        
        .dashboard-wrapper { max-width:1600px; margin:0 auto; width:100%; }
        
        .dashboard-header { 
            display:flex; justify-content:space-between; align-items:center; 
            background:white; border-radius:28px; padding:16px 28px; margin-bottom:24px; 
            box-shadow:0 10px 30px -10px rgba(0,0,0,0.08); border:1px solid rgba(0,0,0,0.02);
            transition: box-shadow 0.2s ease, border-color 0.2s ease; /* removed translateY hover */
        }
        
        /* ===== OTHER ELEMENTS - STATIC WITH POINTER INDICATION ONLY ===== */
.dashboard-header {
    cursor: default; /* Not clickable */
}

.dashboard-header:hover {
    box-shadow: 0 10px 30px -10px rgba(0,0,0,0.08) !important;
    border-color: rgba(0,0,0,0.02) !important;
    transform: none !important;
}

.profile-card {
    cursor: default; /* Not clickable */
}

.profile-card:hover {
    box-shadow: 0 15px 35px -12px rgba(0,0,0,0.1) !important;
    border-color: rgba(0,0,0,0.02) !important;
    transform: none !important;
}

.profile-card:hover .member-pic-large {
    box-shadow: 0 10px 20px -5px rgba(42,92,130,0.3) !important;
}

.calendar-card {
    cursor: default; /* Not clickable */
}

.calendar-card:hover {
    box-shadow: 0 15px 35px -12px rgba(0,0,0,0.1) !important;
    border-color: rgba(0,0,0,0.02) !important;
    transform: none !important;
}

/* Member cards - clickable but only show border highlight on hover */
.member-card {
    cursor: pointer;
    position: relative;
    transition: box-shadow 0.2s ease, border-color 0.2s ease !important;
}

.member-card::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    height: 6px;
    background: linear-gradient(90deg, #2A5C82, #1A9AA0);
    opacity: 0;
    transition: opacity 0.2s ease;
}

.member-card:hover::before {
    opacity: 1;
}

.member-card:hover {
    box-shadow: 0 20px 35px -15px rgba(0,0,0,0.1) !important;
    border-color: rgba(42,92,130,0.2) !important;
    transform: none !important;
}

.member-card:hover .member-card-photo {
    box-shadow: 0 10px 25px -5px rgba(42,92,130,0.3) !important;
    transform: none !important;
}

.member-card-photo {
    transition: box-shadow 0.2s ease !important;
}

.member-card:hover .view-indicator {
    opacity: 1;
}

.view-indicator {
    opacity: 0.6;
    transition: opacity 0.2s ease;
}

/* Dashboard footer - static */
.dashboard-footer {
    cursor: default;
}

.dashboard-footer:hover {
    box-shadow: 0 4px 12px rgba(0,0,0,0.03) !important;
    border-color: #e2e8f0 !important;
    transform: none !important;
}

/* Logout button - keep its hover effect */
.logout-btn {
    cursor: pointer;
    transition: all 0.2s;
}

.logout-btn:hover {
    background: #b71c1c;
    box-shadow: 0 12px 24px rgba(230,57,70,0.3);
    transform: scale(1.02);
}

/* Back to dashboard button - keep its hover effect */
.back-to-dashboard {
    cursor: pointer;
}

.back-to-dashboard:hover {
    background: #1e4a6e;
    box-shadow: 0 8px 20px rgba(42,92,130,0.4);
    transform: scale(1.02);
}

/* Admin return button - keep its hover effect */
.admin-return-btn {
    cursor: pointer;
}

.admin-return-btn:hover {
    background: #1e4a6e;
    box-shadow: 0 12px 25px -5px rgba(42,92,130,0.4);
    transform: scale(1.02);
}

/* Theme toggle - keep its hover effect */
.theme-toggle {
    cursor: pointer;
}

.theme-toggle:hover {
    transform: scale(1.15);
    color: #2A5C82;
}

/* Footer links - keep their hover effect */
.footer-links a {
    cursor: pointer;
    position: relative;
    padding: 4px 0;
}

.footer-links a::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    width: 0;
    height: 2px;
    background: linear-gradient(90deg, #2A5C82, #1A9AA0);
    transition: width 0.3s ease;
}

.footer-links a:hover::after {
    width: 100%;
}

/* Remove any floating animations from non-quick action elements */
.profile-card, 
.calendar-card,
.action-tile:nth-child(1),
.action-tile:nth-child(2),
.action-tile:nth-child(3),
.action-tile:nth-child(4) {
    animation: none !important;
}

/* Keep only Quick Actions with float animation */
.action-tile {
    animation: float 7s ease-in-out infinite;
}

.action-tile:nth-child(2) { animation: float 8s ease-in-out infinite; animation-delay: 0.5s; }
.action-tile:nth-child(3) { animation: float 6.5s ease-in-out infinite; animation-delay: 1s; }
.action-tile:nth-child(4) { animation: float 7.5s ease-in-out infinite; animation-delay: 1.5s; }

@keyframes float {
    0% { transform: translateY(0px); }
    50% { transform: translateY(-5px); }
    100% { transform: translateY(0px); }
}

/* Dark theme adjustments - keep hover states minimal for non-quick actions */
body.dark-theme .dashboard-header:hover,
body.dark-theme .profile-card:hover,
body.dark-theme .calendar-card:hover,
body.dark-theme .dashboard-footer:hover {
    border-color: #3a3a3a !important;
    box-shadow: 0 4px 12px rgba(0,0,0,0.2) !important;
}

body.dark-theme .member-card:hover {
    border-color: #555 !important;
}

body.dark-theme .action-tile:hover {
    border-color: #2A5C8244 !important;
}
        
        /* REPLACED hover effects with highlight */
        .dashboard-header:hover { 
            box-shadow:0 15px 30px -8px rgba(42,92,130,0.2); 
            border-color: rgba(42,92,130,0.2);
            transform: none;
        }
        .user-welcome { display:flex; align-items:center; gap:12px; font-size:18px; font-weight:600; color:#1a2e44; }
.user-welcome span { 
    background: linear-gradient(135deg, #1e2f4a 0%, #0f2b3d 100%);
    color: white; 
    padding: 6px 22px; 
    border-radius: 40px; 
    font-size: 16px; 
    font-weight: 600; 
    box-shadow: 0 4px 12px rgba(0,20,40,0.25);
    letter-spacing: 0.3px;
    border: 1px solid rgba(255,255,255,0.08);
}
        .logout-btn { 
            background:#E63946; color:white; border:none; padding:8px 18px; border-radius:40px; 
            font-weight:600; cursor:pointer; font-size:14px; box-shadow:0 6px 14px rgba(230,57,70,0.2);
            transition: all 0.2s; white-space:nowrap;
        }
        .logout-btn:hover { background:#b71c1c; box-shadow:0 12px 24px rgba(230,57,70,0.3); transform: scale(1.02); } /* kept slight scale for button */
        
        /* Profile + Calendar row */
        .profile-calendar-row { display:flex; gap:24px; margin-bottom:32px; flex-wrap:wrap; }
        .profile-card { 
            background:white; border-radius:28px; padding:24px; flex:1 1 300px; display:flex; align-items:center; gap:24px; 
            box-shadow:0 15px 35px -12px rgba(0,0,0,0.1); border:1px solid rgba(0,0,0,0.02);
            transition: box-shadow 0.2s ease, border-color 0.2s ease; /* no translate */
        }
        
        .profile-card:hover { 
            box-shadow:0 20px 35px -10px rgba(42,92,130,0.2); 
            border-color: rgba(42,92,130,0.15);
            transform: none;
        }
        .member-pic-large { 
            width:100px; height:100px; border-radius:50%; object-fit:cover; 
            border:3px solid #2A5C82; box-shadow:0 10px 20px -5px rgba(42,92,130,0.3); 
            transition: box-shadow 0.2s ease;
        }
        .profile-card:hover .member-pic-large { box-shadow:0 15px 25px -5px rgba(42,92,130,0.4); }
        .profile-info h2 { font-size:24px; font-weight:700; color:#1e3c5c; margin-bottom:4px; letter-spacing:-0.3px; }
        .profile-info .member-title { color:#2A5C82; font-weight:600; font-size:16px; }
        .profile-info .workplace { color:#4a5f73; margin-top:8px; font-size:15px; font-weight:500; display:flex; align-items:center; gap:4px; }
        
        .calendar-card { 
            background:white; border-radius:28px; padding:20px; flex:2 1 450px; 
            box-shadow:0 15px 35px -12px rgba(0,0,0,0.1); border:1px solid rgba(0,0,0,0.02);
            transition: box-shadow 0.2s ease, border-color 0.2s ease;
            overflow: auto;
        }
        .calendar-card:hover { 
            box-shadow:0 20px 35px -10px rgba(42,92,130,0.2); 
            border-color: rgba(42,92,130,0.15);
            transform: none;
        }
        .calendar-header { display:flex; align-items:center; gap:10px; margin-bottom:16px; color:#1e3c5c; }
        .calendar-header span { font-weight:700; font-size:16px; }
        #miniCalendar { 
            height: 260px; 
            --fc-border-color: #eef2f7; 
            --fc-today-bg: rgba(42,92,130,0.05); 
            font-size:0.9rem;
        }
        /* Make calendar scrollable */
        .fc-scrollgrid-sync-table { min-height: 200px; }
        .fc-daygrid-body { min-height: 200px; }
        
        /* Action tiles */
        .section-title { font-size:20px; font-weight:700; color:#1e3c5c; margin-bottom:20px; display:flex; align-items:center; gap:8px; letter-spacing:-0.3px; }
        .action-grid { display:grid; grid-template-columns:repeat(auto-fit, minmax(220px,1fr)); gap:24px; margin-bottom:30px; }
        .action-tile { 
            background:white; border-radius:28px; padding:28px 20px; text-align:center; cursor:pointer; 
            border:1px solid rgba(0,0,0,0.02); box-shadow:0 15px 35px -12px rgba(0,0,0,0.08);
            transition: box-shadow 0.2s ease, border-color 0.2s ease; /* removed translate/scale */
            position: relative;
            padding-bottom: 20px;
        }
        
        .action-tile:hover { 
            box-shadow:0 20px 35px -10px rgba(42,92,130,0.2); 
            border-color: #2A5C8222;
            transform: none;
        }
        .action-tile:active { transform:scale(0.98); } /* keep tap feedback */
        .tile-icon { font-size:52px; margin-bottom:8px; color:#2A5C82; transition: color 0.2s; }
        .action-tile:hover .tile-icon { color: #1A9AA0; } /* subtle color change instead of scale */
        .tile-title { font-weight:700; font-size:20px; color:#1a2e44; margin-bottom:8px; }
        .tile-desc { 
            font-size: 13px; 
            color: #5f7d9c; 
            font-weight: 500; 
            margin-top: 6px; 
            border-top: 1px dashed rgba(42,92,130,0.15);
            padding-top: 8px;
            letter-spacing: 0.2px;
            line-height: 1.4;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 4px;
            flex-wrap: wrap;
        }
        .tile-desc i { 
            font-size: 14px; 
            color: #2A5C82; 
            opacity: 0.7;
        }
        
        /* MEMBER CARDS GRID */
        .members-grid-section { margin: 40px 0 30px; }
        .members-grid { 
            display: grid; 
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr)); 
            gap: 24px; 
            margin-top: 20px; 
        }
        .member-card { 
            background: white; 
            border-radius: 32px; 
            padding: 28px 20px 24px; 
            display: flex; 
            flex-direction: column; 
            align-items: center; 
            text-align: center; 
            cursor: pointer; 
            border: 1px solid rgba(0,0,0,0.02); 
            box-shadow: 0 20px 35px -15px rgba(0,0,0,0.1); 
            transition: box-shadow 0.2s ease, border-color 0.2s ease; /* no translate/scale */
            position: relative;
            overflow: hidden;
        }
        .member-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 6px;
            background: linear-gradient(90deg, #2A5C82, #1A9AA0);
            opacity: 0;
            transition: opacity 0.2s ease;
        }
        .member-card:hover::before {
            opacity: 1;
        }
        
        .member-card:hover { 
            box-shadow: 0 25px 40px -18px rgba(42,92,130,0.3); 
            border-color: rgba(42,92,130,0.2);
            transform: none;
        }
        .member-card:active { transform: scale(0.98); }
        .member-card-photo { 
            width: 100px; 
            height: 100px; 
            border-radius: 50%; 
            object-fit: cover; 
            border: 4px solid #2A5C82; 
            margin-bottom: 18px; 
            background: #f0f4fa;
            transition: box-shadow 0.2s ease;
            box-shadow: 0 10px 25px -5px rgba(42,92,130,0.3);
        }
        .member-card:hover .member-card-photo { 
            box-shadow: 0 15px 30px -5px rgba(42,92,130,0.4);
        }
        .member-card-name { 
            font-weight: 800; 
            font-size: 20px; 
            color: #1e3c5c; 
            margin-bottom: 6px; 
            letter-spacing: -0.3px;
        }
        .member-card-title { 
            color: #2A5C82; 
            font-weight: 600; 
            font-size: 15px; 
            margin-bottom: 10px; 
            background: rgba(42,92,130,0.08);
            padding: 4px 14px;
            border-radius: 40px;
        }
        .member-card-workplace { 
            color: #4a5f73; 
            font-size: 14px; 
            font-weight: 500; 
            display: flex; 
            align-items: center; 
            gap: 6px; 
            margin-bottom: 14px;
            line-height: 1.5;
            padding: 0 8px;
        }
        .member-card-workplace i {
            color: #2A5C82;
            font-size: 14px;
        }
        .member-card-email { 
            font-size: 13px; 
            font-weight: 500;
            color: #2A5C82; 
            background: rgba(42,92,130,0.06); 
            padding: 8px 16px; 
            border-radius: 40px; 
            width: 100%; 
            overflow: hidden; 
            text-overflow: ellipsis;
            border: 1px solid rgba(42,92,130,0.1);
            transition: background 0.2s ease, border-color 0.2s ease;
        }
        .member-card:hover .member-card-email {
            background: rgba(42,92,130,0.1);
            border-color: rgba(42,92,130,0.2);
        }
        .view-indicator { 
            margin-top: 14px; 
            color: #2A5C82; 
            font-size: 14px; 
            font-weight: 700; 
            opacity: 0.6; 
            transition: opacity 0.2s ease;
            display: flex;
            align-items: center;
            gap: 6px;
        }
        .member-card:hover .view-indicator { 
            opacity: 1; 
        }
        
        /* ---------- GLOBAL TWEAKS ---------- */
        body {
            background: #f8fafd;
            font-family: 'Inter', 'Segoe UI', Roboto, sans-serif;
            color: #1e2e44;
        }

        /* ---------- LOGIN CARD REFINEMENT ---------- */
        .login-card {
            box-shadow: 0 30px 60px -20px rgba(0, 30, 60, 0.3);
            border: 1px solid rgba(255,255,255,0.5);
            backdrop-filter: blur(2px);
            border-radius: 28px; /* adjusted to match new softer style */
        }

        .login-title {
            font-weight: 600;
            letter-spacing: -0.3px;
            color: #1e3c5c;
        }

        .form-input {
            border-radius: 6px;
            border: 1px solid #e0e8f2;
            transition: all 0.2s;
            background: #ffffff;
        }

        .form-input:focus {
            border-color: #2A5C82;
            box-shadow: 0 0 0 4px rgba(42,92,130,0.1);
        }

        .login-btn {
            background: linear-gradient(135deg, #2A5C82, #1e4a6e);
            border-radius: 6px;
            font-weight: 600;
            letter-spacing: 0.5px;
            box-shadow: 0 10px 20px -5px rgba(42,92,130,0.4);
        }

/* ===== STEP 1: PREMIUM CARD ENHANCEMENTS ===== */
.dashboard-header, 
.profile-card, 
.calendar-card, 
.action-tile, 
.member-card,
.dashboard-footer {
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);
    transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
}

/* Specific padding adjustments */
.dashboard-header { padding: 16px 28px; }
.profile-card { padding: 24px; }
.calendar-card { padding: 20px; }
.action-tile { padding: 28px 20px; }
.member-card { padding: 28px 20px 24px; }
.dashboard-footer { padding: 18px 32px; }

/* Hover states with stronger borders */
.dashboard-header:hover,
.profile-card:hover,
.calendar-card:hover,
.action-tile:hover,
.member-card:hover {
    border-color: #cbd5e0;  /* Darker border on hover */
    box-shadow: 0 8px 20px rgba(0,0,0,0.06);
}

/* ===== STEP 1: PREMIUM CARD ENHANCEMENTS ===== */
.dashboard-header, 
.profile-card, 
.calendar-card, 
.action-tile, 
.member-card,
.dashboard-footer {
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);
    transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
}

/* Subtle inner glow on hover */
.dashboard-header:hover, 
.profile-card:hover, 
.calendar-card:hover, 
.action-tile:hover, 
.member-card:hover {
    transform: translateY(-2px);
    box-shadow: 0 20px 30px -10px rgba(0,0,0,0.15), 0 0 0 1px rgba(42,92,130,0.2) inset;
}

/* ===== STEP 2: GRADIENT TEXT ===== */
.section-title {
    background: linear-gradient(135deg, #1e2f4a, #2A5C82);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    font-weight: 700;
}

.profile-info h2 {
    background: linear-gradient(135deg, #1a2e44, #2A5C82);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}

/* ===== STEP 3: ANIMATED ACTION ICONS ===== */
.action-tile {
    position: relative;
    overflow: hidden;
}

.action-tile::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: radial-gradient(circle at 30% 30%, rgba(42,92,130,0.1), transparent 70%);
    opacity: 0;
    transition: opacity 0.3s ease;
}

.action-tile:hover::before {
    opacity: 1;
}

.tile-icon {
    transition: transform 0.3s ease, color 0.3s ease;
}

.action-tile:hover .tile-icon {
    transform: scale(1.1) rotate(5deg);
}
/* ===== STEP 4: GLASSMORPHISM CALENDAR ===== */
.calendar-card {
    position: relative;
    overflow: hidden;
}

.calendar-card::after {
    content: '';
    position: absolute;
    top: -50%;
    right: -50%;
    width: 200%;
    height: 200%;
    background: radial-gradient(circle at 70% 30%, rgba(42,92,130,0.05), transparent 70%);
    pointer-events: none;
}

#miniCalendar {
    --fc-event-bg-color: #2A5C82;
    --fc-event-border-color: #2A5C82;
    --fc-today-bg: rgba(42,92,130,0.05);
}

/* ===== STEP 5: MEMBER CARDS WITH DEPTH ===== */
.member-card {
    position: relative;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.member-card::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 5%;
    width: 90%;
    height: 10px;
    background: rgba(0,0,0,0.1);
    filter: blur(8px);
    border-radius: 50%;
    opacity: 0;
    transition: opacity 0.3s ease;
}

.member-card:hover::after {
    opacity: 1;
}

.member-card-photo {
    transition: transform 0.3s ease, border-color 0.3s ease;
}

.member-card:hover .member-card-photo {
    transform: scale(1.05);
    border-color: #1A9AA0;
}

/* ===== STEP 6: BEAUTIFUL FOOTER ===== */
.dashboard-footer {
    background: linear-gradient(145deg, #ffffff, #f8fafc);
    border-top: 3px solid #2A5C82;
    position: relative;
}

.footer-links a {
    position: relative;
    padding: 4px 0;
}

.footer-links a::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    width: 0;
    height: 2px;
    background: linear-gradient(90deg, #2A5C82, #1A9AA0);
    transition: width 0.3s ease;
}

.footer-links a:hover::after {
    width: 100%;
}

.normal-time {
    background: linear-gradient(145deg, rgba(42,92,130,0.1), rgba(26,154,160,0.1));
    border: 1px solid rgba(42,92,130,0.2);
}

/* ===== STEP 7: SMOOTH TRANSITIONS ===== */
button, a, .action-tile, .member-card, .profile-card, .calendar-card {
    transition: all 0.2s cubic-bezier(0.4, 0, 0.2, 1) !important;
}

/* Pulse animation for logout button */
.logout-btn {
    animation: subtle-pulse 3s infinite;
}

@keyframes subtle-pulse {
    0%, 100% { box-shadow: 0 6px 14px rgba(230,57,70,0.2); }
    50% { box-shadow: 0 8px 20px rgba(230,57,70,0.3); }
}
/* ===== STEP 9: BEAUTIFUL SCROLLBAR ===== */
::-webkit-scrollbar {
    width: 8px;
    height: 8px;
}

::-webkit-scrollbar-track {
    background: #f1f5f9;
    border-radius: 10px;
}

::-webkit-scrollbar-thumb {
    background: linear-gradient(135deg, #2A5C82, #1A9AA0);
    border-radius: 10px;
}

::-webkit-scrollbar-thumb:hover {
    background: linear-gradient(135deg, #1e4a6e, #13808a);
}

body.dark-theme ::-webkit-scrollbar-track {
    background: #2a2a2a;
}

body.dark-theme ::-webkit-scrollbar-thumb {
    background: linear-gradient(135deg, #3a6d9a, #2a8a94);
}

/* ===== STEP 11: FLOATING ANIMATION ===== */
@keyframes float {
    0% { transform: translateY(0px); }
    50% { transform: translateY(-5px); }
    100% { transform: translateY(0px); }
}

.profile-card, .calendar-card {
    animation: float 6s ease-in-out infinite;
}

.calendar-card {
    animation-delay: 1s;
}

/* Different float speeds for variety */
.action-tile:nth-child(1) { animation: float 7s ease-in-out infinite; }
.action-tile:nth-child(2) { animation: float 8s ease-in-out infinite; animation-delay: 0.5s; }
.action-tile:nth-child(3) { animation: float 6.5s ease-in-out infinite; animation-delay: 1s; }
.action-tile:nth-child(4) { animation: float 7.5s ease-in-out infinite; animation-delay: 1.5s; }

/* ===== STEP 15: TYPING EFFECT ===== */
@keyframes typing {
    from { width: 0; }
    to { width: 100%; }
}

@keyframes blink {
    50% { border-color: transparent; }
}

.user-welcome span {
    position: relative;
    overflow: hidden;
    white-space: nowrap;
    border-right: 2px solid white;
    animation: typing 2s steps(20, end), blink 0.75s step-end infinite;
    max-width: fit-content;
}

/* Dark theme adjustments */
body.dark-theme .dashboard-header,
body.dark-theme .profile-card,
body.dark-theme .calendar-card,
body.dark-theme .action-tile,
body.dark-theme .member-card,
body.dark-theme .dashboard-footer {
    background: #1e1e1e;
    border: 1px solid #3a3a3a;  /* Visible dark border */
    box-shadow: 0 4px 12px rgba(0,0,0,0.2);
}

body.dark-theme .dashboard-header:hover,
body.dark-theme .profile-card:hover,
body.dark-theme .calendar-card:hover,
body.dark-theme .action-tile:hover,
body.dark-theme .member-card:hover {
    border-color: #555555;  /* Lighter border on hover in dark mode */
}
        .action-tile:hover .tile-icon {
            color: #1A9AA0;
        }

        /* Buttons */
        .logout-btn {
            background: #E63946;
            border-radius: 40px;
            padding: 8px 18px;  /* Reduced size */
            font-weight: 600;
            box-shadow: 0 8px 16px -5px rgba(230,57,70,0.3);
            transition: all 0.2s;
            white-space: nowrap;  /* Prevent wrapping */
        }

        .logout-btn:hover {
            background: #c72a38;
            box-shadow: 0 15px 25px -8px rgba(230,57,70,0.4);
            transform: scale(1.02);
        }

        /* Back to dashboard button */
        .back-to-dashboard {
            background: #2A5C82;
            color: white;
            border: none;
            padding: 10px 24px;
            border-radius: 40px;
            font-weight: 500;
            box-shadow: 0 4px 12px rgba(42,92,130,0.2);
            transition: all 0.2s ease;
            cursor: pointer;
        }
        .back-to-dashboard:hover {
            background: #1e4a6e;
            box-shadow: 0 8px 20px rgba(42,92,130,0.4);
            transform: scale(1.02);
        }

        /* Footer - copyright moved to right */
        .dashboard-footer {
            background: white;
            border-radius: 40px;
            padding: 18px 32px;
            color: #2e405b;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
        }

        .footer-links {
            display: flex;
            gap: 24px;
            align-items: center;
            flex-wrap: wrap;
        }

        .footer-copyright {
            font-weight: 500;
            color: inherit;
        }

        .footer-links a {
            color: #2A5C82;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.2s;
        }

        .footer-links a:hover {
            color: #1e4a6e;
            text-decoration: underline 2px rgba(42,92,130,0.2);
            text-underline-offset: 4px;
        }

        /* Modals */
        .modal-overlay { 
            display:none; 
            position:fixed; 
            inset:0; 
            background:rgba(0,0,0,0.2); 
            backdrop-filter:blur(4px); 
            align-items:center; 
            justify-content:center; 
            z-index:2000; 
        }
        .modal-card { 
            background:white; 
            border-radius:32px; 
            padding:32px; 
            max-width:340px; 
            text-align:center; 
            box-shadow:0 30px 50px rgba(0,0,0,0.1);
            animation: modalPop 0.2s ease-out;
        }
        @keyframes modalPop {
            0% { opacity: 0; transform: scale(0.9); }
            100% { opacity: 1; transform: scale(1); }
        }
        .inactivity-box, .logout-notification {
            border-radius: 36px;
            box-shadow: 0 40px 70px -20px rgba(0,20,40,0.4);
            border: 1px solid rgba(255,255,255,0.3);
            backdrop-filter: blur(5px);
            background: rgba(255,255,255,0.98);
        }

        .modal-btn {
            padding: 12px 28px;
            border-radius: 40px;
            border: none;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.2s;
        }

        .cancel-btn {
            background: #f0f4fa;
            color: #1e3c5c;
        }

        .confirm-btn {
            background: #E63946;
            color: white;
            box-shadow: 0 8px 16px -5px rgba(230,57,70,0.3);
        }

        /* ===== RESPONSIVE FIXES FOR MOBILE ===== */
        @media (max-width: 700px) {
            /* Make dashboard padding smaller */
            .dashboard { padding: 12px; }
            
            /* Stack header elements properly */
            .dashboard-header {
                flex-direction: column;
                align-items: flex-start;
                gap: 12px;
                padding: 16px;
            }
            
            .dashboard-header > div:last-child {
                width: 100%;
                display: flex;
                justify-content: space-between;
                align-items: center;
            }
            
            /* Smaller logout button that fits */
            .logout-btn {
                padding: 8px 14px;
                font-size: 13px;
                white-space: nowrap;
            }
            
            /* Profile card: stack vertically with photo on top */
            .profile-card {
                flex-direction: column;
                text-align: center;
                gap: 16px;
                padding: 20px;
            }
            
            .member-pic-large {
                width: 110px;
                height: 110px;
                margin: 0 auto;
                border-radius: 50% !important; /* Force circle */
            }
            
            .profile-info {
                width: 100%;
            }
            
            .profile-info h2 {
                font-size: 22px;
            }
            
            /* Calendar adjustments */
            .calendar-card {
                padding: 16px;
            }
            
            /* Action grid spacing */
            .action-grid {
                gap: 16px;
            }
            
            .action-tile {
                padding: 20px 15px;
            }
            
            .tile-icon {
                font-size: 42px;
            }
            
            /* Footer stacking */
            .dashboard-footer {
                flex-direction: column;
                align-items: flex-start;
                gap: 12px;
                padding: 16px 20px;
            }
            
            .footer-links {
                flex-direction: column;
                align-items: flex-start;
                gap: 8px;
            }
            
            .footer-links span {
                display: none; /* hide bullet on mobile */
            }
            
            .normal-time {
                align-self: flex-start;
            }
            
            /* Member grid cards */
            .members-grid {
                grid-template-columns: 1fr;
            }
        }

        /* Mini calendar cleanup */
        #miniCalendar {
            --fc-border-color: #eef2f7;
            --fc-today-bg: rgba(42,92,130,0.03);
            font-size: 0.9rem;
        }

        /* Loader refinement */
        .app-loader img {
            filter: drop-shadow(0 10px 20px rgba(42,92,130,0.15));
        }

        .circle-spinner {
            border-width: 5px;
            border-color: rgba(42,92,130,0.1);
            border-top-color: #2A5C82;
        }
        
        /* Return to Admin View button */
        .admin-return-btn {
            background: #2A5C82;
            color: white;
            border: none;
            padding: 8px 24px;
            border-radius: 40px;
            font-weight: 700;
            cursor: pointer;
            font-size: 14px;
            display: flex;
            align-items: center;
            gap: 8px;
            box-shadow: 0 8px 20px -5px rgba(42,92,130,0.3);
            transition: all 0.2s ease;
            margin-left: 16px;
        }
        .admin-return-btn:hover {
            background: #1e4a6e;
            box-shadow: 0 12px 25px -5px rgba(42,92,130,0.4);
            transform: scale(1.02);
        }
        .admin-return-btn i {
            transition: transform 0.2s ease;
        }
        .admin-return-btn:hover i {
            transform: translateX(-4px);
        }
        
        /* Form iframe container */
        .form-container { display:none; position:fixed; inset:0; background:white; z-index:5000; flex-direction:column; }
        .form-header { background:#f8fafd; padding:16px 24px; display:flex; align-items:center; gap:16px; border-bottom:1px solid #d4deec; }
        iframe { width:100%; flex:1; border:none; background:white; }
        .loading-overlay { position:absolute; inset:0; background:white; display:flex; flex-direction:column; align-items:center; justify-content:center; z-index:10; }
        
        /* logout notification */
        .logout-notification { position:fixed; top:50%; left:50%; transform:translate(-50%,-50%) scale(0.9); background:white; border-radius:32px; padding:30px; text-align:center; z-index:6000; display:none; flex-direction:column; align-items:center; gap:12px; box-shadow:0 30px 50px rgba(0,0,0,0.15); transition:0.2s; }
        .logout-notification.show { transform:translate(-50%,-50%) scale(1); }

        /* ---------- NEW RULES FOR PHONE & TICKBOX ---------- */
        /* Ensure profile container and logout button keep consistent shape on all devices */
        .profile-card {
            border-radius: 28px !important;
        }
        .logout-btn {
            border-radius: 40px !important;
            min-width: auto; /* allow auto width */
        }
        .dashboard-header .user-welcome,
        .dashboard-header > div:last-child {
            flex-shrink: 0;
        }

        /* Tickbox container */
        .terms-checkbox-wrapper {
            display: flex;
            align-items: center;
            gap: 8px;
            margin: 16px 0 12px;
            font-size: 13px;
            font-weight: 500;
            color: #2e405b;
        }
        .terms-checkbox-wrapper input[type="checkbox"] {
            width: 18px;
            height: 18px;
            accent-color: #2A5C82;
            margin: 0;
            cursor: pointer;
        }
        .terms-checkbox-wrapper label {
            cursor: pointer;
        }
        body.dark-theme .terms-checkbox-wrapper {
            color: #ccc;
        }

        /* inactivity warning styling - ensure it's prominent */
        .inactivity-box {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background: white;
            padding: 32px 24px;
            border-radius: 32px;
            text-align: center;
            z-index: 10000;
            box-shadow: 0 30px 60px rgba(0,0,0,0.3);
            min-width: 280px;
        }
        .inactivity-box .keep-btn {
            background: #2A5C82;
            color: white;
            border: none;
            padding: 12px 28px;
            border-radius: 40px;
            font-weight: 700;
            margin-top: 16px;
            cursor: pointer;
            font-size: 15px;
            transition: background 0.2s;
        }
        .inactivity-box .keep-btn:hover {
            background: #1e4a6e;
        }
        .inactivity-timer {
            font-size: 32px;
            font-weight: 800;
            color: #E63946;
            margin: 10px 0;
            font-family: monospace;
        }
    </style>
</head>
<body>
    <!-- APP LOADER -->
    <div class="app-loader" id="appLoader">
        <img src="https://raw.githubusercontent.com/mudassiribrahim12/AESRN-website/main/Networknewlogo.png" alt="AESRN logo">
        <div>Loading Portal...</div>
    </div>

    <!-- GLOBAL CIRCLE LOADER -->
    <div class="global-loader-circle" id="globalCircleLoader">
        <div class="circle-spinner"></div>
        <div class="circle-text">Loading Dashboard...</div>
    </div>

    <!-- DASHBOARD TRANSITION LOADER -->
    <div class="dashboard-loader" id="dashboardLoader">
        <div class="spinner"></div>
        <div class="text">Switching Dashboard...</div>
    </div>

    <!-- PAGE TRANSITION LOADER (for card clicks) -->
    <div class="dashboard-loader" id="pageTransitionLoader">
        <div class="spinner"></div>
        <div class="text">Loading Content...</div>
    </div>

<!-- LOGIN PAGE with theme toggle OUTSIDE card at top right -->
<div class="login-container" id="loginContainer" style="display: none;">
    <div class="login-page-header">
        <button class="theme-toggle" id="loginThemeToggle" title="Toggle dark mode"><i class="fas fa-moon"></i></button>
    </div>
    <div class="login-card" id="loginCard">
        <div class="login-logo">
            <img src="https://raw.githubusercontent.com/mudassiribrahim12/AESRN-website/main/Networknewlogo.png" alt="AESRN">
        </div>
        <div class="login-title">Member Login</div>
        <form id="loginForm">
            <div class="form-group">
                <label class="form-label">Email<span class="required-asterisk">*</span></label>
                <input type="email" id="email" class="form-input" placeholder="" required>
            </div>
            <div class="form-group">
                <label class="form-label">Password <span class="required-asterisk">*</span></label>
                <div class="password-wrapper">
                    <input type="password" id="password" class="form-input" placeholder="" required>
                    <button type="button" class="toggle-password" id="togglePassword"><i class="far fa-eye"></i></button>
                </div>
            </div>
            <!-- TICK BOX ADDED HERE -->
            <div class="terms-checkbox-wrapper">
                <input type="checkbox" id="termsCheckbox" required>
                <label for="termsCheckbox"></label>
            </div>
            <button type="submit" class="login-btn" id="loginBtn">Sign in</button>
            <div class="error-msg" id="errorMessage">Invalid email or password</div>
            <div class="attempts-warning" id="attemptsWarning">Too many attempts. Wait <span id="cooldownCounter">60</span>s</div>
            <a href="https://www.aesrn.net/#home" class="go-to-aesrn"><i class="fas fa-arrow-left"></i> Go to AESRN</a>
        </form>
    </div>
    
    <!-- COPYRIGHT AT BACKGROUND BOTTOM - WITH POWERED BY AT RIGHT -->
    <div class="login-page-copyright">
        <span>Copyright © <span id="loginYear"></span> African Emerging Scholars Research Network (AESRN)</span>
        <span class="powered-by">Powered by AESRN</span>
    </div>
</div>

    <!-- DASHBOARD -->
    <div class="dashboard" id="dashboardContainer" style="display: none;">
        <div class="dashboard-wrapper">
            <div class="dashboard-header">
                <div class="user-welcome">
                    <!-- Removed user icon and name - only "dashboard" remains -->
                    <span>Welcome Back!</span>
                    <!-- Return to Admin View button (only visible when viewing a member as founder) -->
                    <button class="admin-return-btn" id="returnToAdminView" style="display: none;">
                        <i class="fas fa-arrow-left"></i> Back to Admin View
                    </button>
                </div>
                <div style="display: flex; align-items: center; gap: 12px;">
                    <button class="theme-toggle" id="dashboardThemeToggle" title="Toggle dark mode"><i class="fas fa-moon"></i></button>
                    <button class="logout-btn" id="logoutBtn"><i class="fas fa-sign-out-alt"></i> Log out</button>
                </div>
            </div>

            <!-- PROFILE + CALENDAR row -->
            <div class="profile-calendar-row">
                <div class="profile-card">
                    <img src="" alt="member" class="member-pic-large" id="memberPhoto">
                    <div class="profile-info">
                        <h2 id="profileName"></h2>
                        <div class="member-title" id="profileRole"></div>
                        <div class="workplace" id="profileWork"><i class="fas fa-university"></i> <span></span></div>
                    </div>
                </div>
                <div class="calendar-card">
                    <div class="calendar-header"><i class="fas fa-calendar-alt" style="color:#2A5C82;"></i><span id="calendarMonthYear"></span></div>
                    <div id="miniCalendar"></div>
                </div>
            </div>

            <!-- QUICK ACTIONS (visible to all users) -->
            <div class="section-title"><i class="fas fa-clipboard-list" style="color:#2A5C82;"></i> Quick actions</div>
            <div class="action-grid">
                <div class="action-tile" id="viewAssignment">
                    <div class="tile-icon">📋</div>
                    <div class="tile-title">Assignments</div>
                    <div class="tile-desc"><i class="fas fa-pen-fancy"></i> view tasks & deadlines</div>
                </div>
                <div class="action-tile" id="makeSubmission">
                    <div class="tile-icon">📤</div>
                    <div class="tile-title">Submit work</div>
                    <div class="tile-desc"><i class="fas fa-upload"></i> send your assignment</div>
                </div>
                <div class="action-tile" id="viewCorrections">
                    <div class="tile-icon">✏️</div>
                    <div class="tile-title">Corrections</div>
                    <div class="tile-desc"><i class="fas fa-check-double"></i> review feedback & fixes</div>
                </div>
                <div class="action-tile" id="reviewMaterials">
                    <div class="tile-icon">📚</div>
                    <div class="tile-title">Resources</div>
                    <div class="tile-desc"><i class="fas fa-book-open"></i> past review materials</div>
                </div>
            </div>

            <!-- MEMBER CARDS SECTION - Only visible to founder/coordinator emails -->
            <div class="members-grid-section" id="membersSection" style="display: none;">
                <div class="section-title"><i class="fas fa-users" style="color:#2A5C82;"></i> All members · Click to View Dashboard</div>
                <div class="members-grid" id="membersGrid"></div>
            </div>

            <!-- FOOTER with copyright at right corner (year auto-updates) -->
            <div class="dashboard-footer">
                <div class="footer-links">
                    <a href="mailto:research.aesrn@yahoo.com"> For any problems encountered, please contact: <i class="fas fa-envelope"></i> research.aesrn@yahoo.com</a>
                    <span>•</span>
                    <div class="normal-time" id="liveClock"><i class="far fa-clock"></i> <span id="timeText"></span></div>
                </div>
                <div class="footer-copyright">Copyright © <span id="footerYear"></span> AESRN</div>
            </div>
        </div>
    </div>

    <!-- FORM IFRAME CONTAINER -->
    <div class="form-container" id="formContainer">
        <div class="form-header">
            <button class="back-to-dashboard" id="backToDashboardBtn"><i class="fas fa-arrow-left"></i> Dashboard</button>
            <span style="font-weight:600;">Submission Form</span>
        </div>
        <div class="loading-overlay" id="iframeLoading" style="display:flex;">
            <div class="loading-spinner"></div>
            <div>Loading Form...</div>
        </div>
        <iframe id="tallyIframe" allow="fullscreen" style="visibility:hidden;"></iframe>
    </div>

    <!-- LOGOUT NOTIFICATION -->
    <div class="logout-notification" id="logoutNotification">
        <div style="font-size:48px;">👋🏾</div>
        <div style="font-size:22px; font-weight:700;">Logged out</div>
        <div class="logout-countdown" style="font-weight:500;">Redirecting in <span id="logoutCountdown">5</span> seconds...</div>
    </div>

    <!-- INACTIVITY WARNING (1min 30sec) - now visible and requires click -->
    <div class="inactivity-box" id="inactivityWarning" style="display: none;">
        <i class="fas fa-hourglass-half" style="font-size:44px; color:#E63946;"></i>
        <h3 style="margin:12px 0 8px; font-weight:700;">Session timeout</h3>
        <div class="inactivity-timer" id="inactivityTimer">1:30</div>
        <p style="font-weight:500;">You've been inactive</p>
        <button class="keep-btn" id="keepSessionBtn">Continue session</button>
    </div>
    
    <!-- LOGOUT CONFIRMATION MODAL (with subtle pop animation) -->
    <div class="modal-overlay" id="logoutModal">
        <div class="modal-card">
            <i class="fas fa-door-open" style="font-size:48px; color:#2A5C82;"></i>
            <h3 style="margin:16px 0 8px; font-weight:700;">End session?</h3>
            <p style="color:#4f6f8f; font-weight:500;">You will be logged out</p>
            <div class="modal-buttons">
                <button class="modal-btn cancel-btn" id="cancelLogout">Stay</button>
                <button class="modal-btn confirm-btn" id="confirmLogout">Logout</button>
            </div>
        </div>
    </div>

    <script>
        (function() {
            // ----- MEMBER DATA -----
            // Using a Map to ensure unique entries by email
            const memberDetails = new Map([
                ["malikseidu4@gmail.com", { fullName:"Abdul-Malik Seidu", title:"Member", workplace:"Nurses' & Midwives' Training College, Tamale", photo:"https://raw.githubusercontent.com/mudassiribrahim12/AESRN-website/main/malik.png" }],
                ["abdulrazakiddrisu1@gmail.com", { fullName:"Iddrisu Abdul-Razak", title:"Member", workplace:"Tamale Teaching Hospital", photo:"https://raw.githubusercontent.com/mudassiribrahim12/AESRN-website/main/razak.png" }],
                ["abdul0247080685@gmail.com", { fullName:"Abdul Latif Abdul Rahman", title:"Member", workplace:"Le Mete Ghana, Tamale Urology Centre", photo:"https://raw.githubusercontent.com/mudassiribrahim12/AESRN-website/main/Latif.png" }],
                ["ednadie93@gmail.com", { fullName:"Edna Die", title:"Member", workplace:"Tamale Teaching Hospital", photo:"https://raw.githubusercontent.com/mudassiribrahim12/AESRN-website/main/Edna.png" }],
                ["issahaqalhassan26@gmail.com", { fullName:"Alhassan Issahaq", title:"Member", workplace:"Nurses' & Midwives' Training College, Tamale", photo:"https://raw.githubusercontent.com/mudassiribrahim12/AESRN-website/main/Alhassan.png" }],
                ["mohammed.mudasir@tth.gov.gh", { fullName:"Mudasir Mohammed Ibrahim", title:"Founder & Network Coordinator", workplace:"Tamale Teaching Hospital", photo:"https://raw.githubusercontent.com/mudassiribrahim12/AESRN-website/main/mudasir.png" }],
                ["mudassiribrahim30@gmail.com", { fullName:"Mudasir Mohammed Ibrahim", title:"Founder & Network Coordinator", workplace:"Tamale Teaching Hospital", photo:"https://raw.githubusercontent.com/mudassiribrahim12/AESRN-website/main/mudasir.png" }]
            ]);
            
            // Corrections links for each member
            const correctionsMap = new Map([
                ["malikseidu4@gmail.com", "https://swpgh-my.sharepoint.com/:f:/g/personal/mohammed_mudasir_tth_gov_gh/IgD9xiKlwu5uT4wIyCUtx8CEAWfmCIJEzoFXT694hE5Lswk?e=jZ7PEn"],
                ["abdulrazakiddrisu1@gmail.com", "https://swpgh-my.sharepoint.com/:f:/g/personal/mohammed_mudasir_tth_gov_gh/IgCxO2xHXwtSSbptkWKxGGBwAdC4TDWfli4Tp1z7IE_PrTw?e=bWc5nR"],
                ["abdul0247080685@gmail.com", "https://swpgh-my.sharepoint.com/:f:/g/personal/mohammed_mudasir_tth_gov_gh/IgChCoaEDswITaM13pAxNNpxAf63Gvalxk11ielEoDRlP4s?e=EFQrSN"],
                ["ednadie93@gmail.com", "https://swpgh-my.sharepoint.com/:f:/g/personal/mohammed_mudasir_tth_gov_gh/IgANkmZo8kibRoFYyc8nJBPsAd7A28Ua96HsgxFZArCpurQ?e=8CWeaS"],
                ["issahaqalhassan26@gmail.com", "https://swpgh-my.sharepoint.com/:f:/g/personal/mohammed_mudasir_tth_gov_gh/IgBP-ZvDfgz8R402lV3jNtpZAajXW_HKFwtuKAJAKuE4RZg?e=Ib5jfO"],
                ["mohammed.mudasir@tth.gov.gh", "https://swpgh-my.sharepoint.com/:f:/g/personal/mohammed_mudasir_tth_gov_gh/IgA_Wlt3rN4TToHhLhObdU30AcaZzPZJbmlpAHBVGN1fCMc?e=TD7Ls1"],
                ["mudassiribrahim30@gmail.com", "https://swpgh-my.sharepoint.com/:f:/g/personal/mohammed_mudasir_tth_gov_gh/IgA_Wlt3rN4TToHhLhObdU30AcaZzPZJbmlpAHBVGN1fCMc?e=TD7Ls1"]
            ]);
            
            const DEFAULT_CORR = "https://onedrive.live.com/";
            const CORRECT_PASSWORD = "Scholar123";

            // Founder/Coordinator emails (both)
            const FOUNDER_EMAILS = ["mohammed.mudasir@tth.gov.gh", "mudassiribrahim30@gmail.com"];

            // Session & cooldown vars
            let currentUserEmail = null, currentUserData = null;
            let originalFounderEmail = null; // Store the original founder email when viewing a member
            let isViewingMember = false; // Flag to track if we're viewing a member as founder
            let failedAttempts = 0, cooldownTimer = null, cooldownSeconds = 0;
            let isDashboard = false, warningActive = false;
            let inactivityTimer, warningTimer, countdownInterval;
            
            // Updated timeout: 1 minute = 60000 ms (changed from 90s to 60s)
            const SESSION_TIMEOUT = 60000; // 1 min exact
            const WARNING_TIME = 30000; // show warning after 30s (30s remaining)
            let iframeInitialized = false;

            // Dark mode state
            function initTheme() {
                const savedTheme = localStorage.getItem('aesrn_theme') || 'light';
                if (savedTheme === 'dark') {
                    document.body.classList.add('dark-theme');
                    updateThemeIcons('dark');
                } else {
                    updateThemeIcons('light');
                }
            }
            function toggleTheme() {
                if (document.body.classList.contains('dark-theme')) {
                    document.body.classList.remove('dark-theme');
                    localStorage.setItem('aesrn_theme', 'light');
                    updateThemeIcons('light');
                } else {
                    document.body.classList.add('dark-theme');
                    localStorage.setItem('aesrn_theme', 'dark');
                    updateThemeIcons('dark');
                }
            }
            function updateThemeIcons(mode) {
                const icons = document.querySelectorAll('.theme-toggle i');
                icons.forEach(icon => {
                    if (mode === 'dark') {
                        icon.classList.remove('fa-moon');
                        icon.classList.add('fa-sun');
                    } else {
                        icon.classList.remove('fa-sun');
                        icon.classList.add('fa-moon');
                    }
                });
            }

            // session storage functions
            function getActiveSessions() { return JSON.parse(localStorage.getItem('aesrn_active_sessions')||'{}'); }
            function saveActiveSessions(s) { localStorage.setItem('aesrn_active_sessions', JSON.stringify(s)); }
            function generateSessionId() { return 'sess_'+Date.now()+'_'+Math.random().toString(36).substring(2); }
            
            function isLoggedInElsewhere(email) {
                let sessions = getActiveSessions();
                let sess = sessions[email];
                if (!sess) return false;
                if (Date.now() > sess.expiry) { delete sessions[email]; saveActiveSessions(sessions); return false; }
                let current = sessionStorage.getItem('aesrn_sid');
                return sess.sessionId !== current;
            }

            function registerSession(email, name) {
                let sid = generateSessionId();
                let sessions = getActiveSessions();
                sessions[email] = { sessionId: sid, expiry: Date.now() + SESSION_TIMEOUT, name };
                saveActiveSessions(sessions);
                sessionStorage.setItem('aesrn_sid', sid);
                localStorage.setItem('aesrn_user_session', JSON.stringify({ email, name, sessionId: sid, expiry: Date.now()+SESSION_TIMEOUT }));
                return sid;
            }

            function removeSession(email) {
                let sessions = getActiveSessions();
                if (sessions[email]) delete sessions[email];
                saveActiveSessions(sessions);
                localStorage.removeItem('aesrn_user_session');
                sessionStorage.removeItem('aesrn_sid');
            }

            // inactivity timers (adjusted for 60s)
            function clearTimers() {
                clearTimeout(inactivityTimer); clearTimeout(warningTimer); 
                if (countdownInterval) clearInterval(countdownInterval);
                hideWarning();
            }
            function hideWarning() {
                warningActive = false;
                document.getElementById('inactivityWarning').style.display = 'none';
            }
            function resetTimers() {
                if (!isDashboard) return;
                clearTimers();
                updateSessionExpiry();
                warningTimer = setTimeout(() => { if (isDashboard && !warningActive) showWarning(); }, WARNING_TIME);
                inactivityTimer = setTimeout(() => { if (isDashboard) forceLogout(); }, SESSION_TIMEOUT);
            }
            function showWarning() {
                if (warningActive || !isDashboard) return;
                warningActive = true;
                document.getElementById('inactivityWarning').style.display = 'block';
                detachListeners(); // stop listening while warning shows
                let seconds = 30; // 30 seconds remaining
                let timerSpan = document.getElementById('inactivityTimer');
                function tick() {
                    let m = Math.floor(seconds/60), s = seconds%60;
                    timerSpan.textContent = m+':'+(s<10?'0':'')+s;
                    if (seconds<=0) { clearInterval(countdownInterval); if (isDashboard) forceLogout(); }
                    seconds--;
                }
                tick();
                countdownInterval = setInterval(tick,1000);
            }
            function continueSession() {
                if (isDashboard) { 
                    hideWarning(); 
                    resetTimers(); 
                    updateSessionExpiry(); 
                    attachListeners(); // re-attach listeners after continuing
                }
            }
            function updateSessionExpiry() {
                if (!currentUserEmail) return;
                let sessions = getActiveSessions();
                if (sessions[currentUserEmail]) {
                    sessions[currentUserEmail].expiry = Date.now() + SESSION_TIMEOUT;
                    saveActiveSessions(sessions);
                }
            }
            function attachListeners() {
                // Timer is based on time passing, not mouse events - we just reset on activity
                ['mousemove','keydown','click','scroll','touchstart'].forEach(ev => document.addEventListener(ev, resetTimers));
            }
            function detachListeners() {
                ['mousemove','keydown','click','scroll','touchstart'].forEach(ev => document.removeEventListener(ev, resetTimers));
            }
            function forceLogout() { clearTimers(); performLogout(true); }

            // cooldown after 5 failed attempts
            function startCooldown() {
                const btn = document.getElementById('loginBtn');
                const warn = document.getElementById('attemptsWarning');
                const counterSpan = document.getElementById('cooldownCounter');
                btn.disabled = true;
                warn.style.display = 'block';
                cooldownSeconds = 60;
                function tick() {
                    counterSpan.textContent = cooldownSeconds;
                    if (cooldownSeconds <= 0) {
                        clearInterval(cooldownTimer);
                        btn.disabled = false;
                        warn.style.display = 'none';
                        failedAttempts = 0;
                    }
                    cooldownSeconds--;
                }
                tick();
                cooldownTimer = setInterval(tick,1000);
            }

            // Show dashboard loader with animation
            function showDashboardLoader() {
                document.getElementById('dashboardLoader').classList.add('active');
            }
            
            function hideDashboardLoader() {
                document.getElementById('dashboardLoader').classList.remove('active');
            }

            // Show page transition loader (3 seconds)
            function showPageTransitionLoader(callback) {
                const loader = document.getElementById('pageTransitionLoader');
                loader.classList.add('active');
                
                setTimeout(() => {
                    loader.classList.remove('active');
                    if (callback) callback();
                }, 3000);
            }

            // render member cards for founder/coordinator (excluding founder themselves)
            function renderMemberCards() {
                const membersGrid = document.getElementById('membersGrid');
                membersGrid.innerHTML = '';
                
                // Convert Map to array and render each unique member, excluding founder emails
                Array.from(memberDetails.entries())
                    .filter(([email]) => !FOUNDER_EMAILS.includes(email)) // Remove founder from cards
                    .forEach(([email, data]) => {
                    const card = document.createElement('div');
                    card.className = 'member-card';
                    card.setAttribute('data-email', email);
                    
                    card.innerHTML = `
                        <img src="${data.photo}" alt="${data.fullName}" class="member-card-photo" loading="lazy" onerror="this.src='https://raw.githubusercontent.com/mudassiribrahim12/AESRN-website/main/Networknewlogo.png'">
                        <div class="member-card-name">${data.fullName}</div>
                        <div class="member-card-title">${data.title}</div>
                        <div class="member-card-workplace"><i class="fas fa-university"></i> ${data.workplace}</div>
                        <div class="member-card-email">${email}</div>
                        <div class="view-indicator"><i class="fas fa-arrow-right"></i> view dashboard</div>
                    `;
                    
                    card.addEventListener('click', () => {
                        if (warningActive) return;
                        // Show 3-second loader then switch view
                        showPageTransitionLoader(() => {
                            switchToMemberView(email);
                        });
                    });
                    
                    membersGrid.appendChild(card);
                });
            }
            
            // Switch to a member's view (for founder/coordinator) - NO SESSION CHANGE
            function switchToMemberView(email) {
                if (!memberDetails.has(email)) return;
                
                // Store the original founder email if this is the first time
                if (!isViewingMember) {
                    originalFounderEmail = currentUserEmail;
                    isViewingMember = true;
                    // Save to localStorage for persistence on reload
                    localStorage.setItem('aesrn_viewing_member', email);
                    localStorage.setItem('aesrn_original_founder', originalFounderEmail);
                }
                
                // Just update the current view data - DON'T change the session
                currentUserEmail = email;
                currentUserData = memberDetails.get(email);
                
                // Update dashboard to show this member's info
                renderDashboard();
                
                // Hide member section when viewing a member
                document.getElementById('membersSection').style.display = 'none';
                
                // Show the return to admin button
                document.getElementById('returnToAdminView').style.display = 'inline-flex';
                
                // Reset timers for new view
                resetTimers();
            }
            
            // Return to admin view (founder's original dashboard) - INSTANT
            function returnToAdminView() {
                if (originalFounderEmail && memberDetails.has(originalFounderEmail)) {
                    // Show 3-second loader for smooth transition
                    showPageTransitionLoader(() => {
                        // Restore original founder as current user
                        currentUserEmail = originalFounderEmail;
                        currentUserData = memberDetails.get(originalFounderEmail);
                        
                        // Update dashboard
                        renderDashboard();
                        
                        // Show member section again
                        document.getElementById('membersSection').style.display = 'block';
                        
                        // Hide return button
                        document.getElementById('returnToAdminView').style.display = 'none';
                        
                        // Clear viewing state
                        isViewingMember = false;
                        localStorage.removeItem('aesrn_viewing_member');
                        localStorage.removeItem('aesrn_original_founder');
                        originalFounderEmail = null;
                        
                        // Reset timers
                        resetTimers();
                    });
                }
            }

            // render dashboard with profile photo
            function renderDashboard() {
                if (!currentUserData) return;
                // Removed displayName update (user name no longer shown)
                document.getElementById('profileName').textContent = currentUserData.fullName;
                document.getElementById('profileRole').textContent = currentUserData.title;
                document.getElementById('profileWork').querySelector('span').textContent = currentUserData.workplace;
                document.getElementById('memberPhoto').src = currentUserData.photo;
                // Force image to load immediately
                document.getElementById('memberPhoto').setAttribute('loading', 'eager');
                initCalendar();
            }

            let calendar = null;
            function initCalendar() {
                let calEl = document.getElementById('miniCalendar');
                if (!calEl) return;
                if (calendar) calendar.destroy();
                
                calendar = new FullCalendar.Calendar(calEl, {
                    initialView: 'dayGridMonth',
                    height: 260,
                    headerToolbar: { start:'', center:'title', end:'' },
                    titleFormat: { year:'numeric', month:'short' },
                    fixedWeekCount: false,
                    showNonCurrentDates: false,
                    // After rendering, scroll to today's date
                    datesSet: function() {
                        setTimeout(() => {
                            const todayStr = new Date().toISOString().slice(0,10);
                            const todayCell = document.querySelector(`[data-date="${todayStr}"]`);
                            if (todayCell) {
                                todayCell.scrollIntoView({ block: 'nearest', behavior: 'smooth' });
                            }
                        }, 100);
                    }
                });
                calendar.render();
                
                // Update month/year in header
                const monthNames = ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"];
                const today = new Date();
                document.getElementById('calendarMonthYear').textContent = monthNames[today.getMonth()] + ' ' + today.getFullYear();
            }

            // Normal time update
            function updateClock() {
                const now = new Date();
                const timeStr = now.toLocaleTimeString('en-US', { hour: '2-digit', minute: '2-digit', second: '2-digit', hour12: true });
                document.getElementById('timeText').textContent = timeStr;
            }
            setInterval(updateClock, 1000);

            // Initialize iframe - restored original working URL
            function initSubmissionIframe() {
                if (iframeInitialized) return;
                const iframe = document.getElementById('tallyIframe');
                iframe.src = "https://tally.so/r/dWd6gA?transparentBackground=1";
                iframeInitialized = true;

                document.getElementById('iframeLoading').style.display = 'flex';
                iframe.style.visibility = 'hidden';

                iframe.addEventListener('load', function onLoad() {
                    document.getElementById('iframeLoading').style.display = 'none';
                    iframe.style.visibility = 'visible';
                    iframe.removeEventListener('load', onLoad);
                });
            }

            // Check if user is founder/coordinator
            function isFounder(email) {
                return FOUNDER_EMAILS.includes(email);
            }

            // login flow - now checks tickbox
            function handleLogin(e) {
                e.preventDefault();
                if (document.getElementById('loginBtn').disabled) return;

                // Check tickbox
                const termsChecked = document.getElementById('termsCheckbox').checked;
                if (!termsChecked) {
                    alert('Please tick the box to agree to the terms and conditions before signing in.');
                    return;
                }

                let email = document.getElementById('email').value;
                let pass = document.getElementById('password').value;
                document.getElementById('errorMessage').style.display = 'none';

                // Find matching email (case insensitive)
                let matchedKey = null;
                for (let key of memberDetails.keys()) {
                    if (key.toLowerCase() === email.trim().toLowerCase()) {
                        matchedKey = key;
                        break;
                    }
                }
                
                if (!matchedKey || pass !== CORRECT_PASSWORD) {
                    failedAttempts++;
                    document.getElementById('errorMessage').style.display = 'block';
                    if (failedAttempts >= 5) startCooldown();
                    return;
                }

                if (isLoggedInElsewhere(matchedKey)) {
                    alert('Already logged in from another device.');
                    return;
                }

                currentUserEmail = matchedKey;
                currentUserData = memberDetails.get(matchedKey);

                document.getElementById('loginCard').style.opacity = '0';
                document.getElementById('loginCard').style.transform = 'scale(0.9)';
                document.getElementById('globalCircleLoader').classList.add('active');

                setTimeout(() => {
                    document.getElementById('loginContainer').style.display = 'none';
                    document.getElementById('loginCard').style.opacity = '1';
                    document.getElementById('loginCard').style.transform = '';
                }, 300);

                setTimeout(() => {
                    document.getElementById('globalCircleLoader').classList.remove('active');
                    registerSession(currentUserEmail, currentUserData.fullName);
                    document.getElementById('dashboardContainer').style.display = 'block';
                    
                    // Render dashboard with current user
                    renderDashboard();
                    
                    // Show member cards if user is founder
                    if (isFounder(currentUserEmail)) {
                        document.getElementById('membersSection').style.display = 'block';
                        renderMemberCards();
                    } else {
                        document.getElementById('membersSection').style.display = 'none';
                    }
                    
                    // Check if we were viewing a member before reload
                    const savedViewingMember = localStorage.getItem('aesrn_viewing_member');
                    const savedOriginalFounder = localStorage.getItem('aesrn_original_founder');
                    
                    if (savedViewingMember && savedOriginalFounder && isFounder(currentUserEmail)) {
                        // Restore the member view state
                        originalFounderEmail = savedOriginalFounder;
                        isViewingMember = true;
                        switchToMemberView(savedViewingMember);
                    } else {
                        // Hide return button initially
                        document.getElementById('returnToAdminView').style.display = 'none';
                        isViewingMember = false;
                        originalFounderEmail = null;
                    }
                    
                    isDashboard = true;
                    resetTimers();
                    attachListeners();
                    initSubmissionIframe();
                }, 3200);
            }

            // logout
            function performLogout(redirect = true) {
                if (currentUserEmail) removeSession(currentUserEmail);
                isDashboard = false; 
                clearTimers(); 
                detachListeners();
                document.getElementById('dashboardContainer').style.display = 'none';
                document.getElementById('formContainer').style.display = 'none';
                document.getElementById('logoutModal').style.display = 'none';
                hideWarning();
                currentUserEmail = null; currentUserData = null;
                isViewingMember = false;
                originalFounderEmail = null;
                localStorage.removeItem('aesrn_viewing_member');
                localStorage.removeItem('aesrn_original_founder');

                let notif = document.getElementById('logoutNotification');
                let countSpan = document.getElementById('logoutCountdown');
                notif.style.display = 'flex';
                notif.classList.add('show');
                let sec = 5;
                countSpan.textContent = sec;
                let interval = setInterval(() => {
                    sec--;
                    countSpan.textContent = sec;
                    if (sec <= 0) {
                        clearInterval(interval);
                        notif.style.display = 'none';
                        notif.classList.remove('show');
                        document.getElementById('loginContainer').style.display = 'flex';
                        document.getElementById('loginForm').reset();
                    }
                }, 1000);
            }

            // open forms with 3-second loader
            function openSubmissionForm() {
                if (warningActive) return;
                showPageTransitionLoader(() => {
                    document.getElementById('dashboardContainer').style.display = 'none';
                    document.getElementById('formContainer').style.display = 'flex';
                    // Ensure iframe is initialized
                    initSubmissionIframe();
                });
            }
            
function closeForm() {
    // Show page transition loader when returning to dashboard
    showPageTransitionLoader(() => {
        document.getElementById('formContainer').style.display = 'none';
        document.getElementById('dashboardContainer').style.display = 'block';
    });
}

            function openAssignment() { 
                if(!warningActive) {
                    showPageTransitionLoader(() => {
                        window.location.href = 'https://swpgh-my.sharepoint.com/:f:/g/personal/mohammed_mudasir_tth_gov_gh/IgAIsMG6e8n2QouivuzCfkg8Ac6Tv18kYWZP7inlnNq07hI?e=gGnKAF';
                    });
                }
            }
            
            function openCorrections() { 
                if(!warningActive && currentUserEmail) { 
                    showPageTransitionLoader(() => {
                        let link = correctionsMap.get(currentUserEmail) || DEFAULT_CORR; 
                        window.location.href = link;
                    });
                } 
            }
            
            function openResources() { 
                if(!warningActive) {
                    showPageTransitionLoader(() => {
                        window.location.href = 'https://swpgh-my.sharepoint.com/:f:/g/personal/mohammed_mudasir_tth_gov_gh/IgDopS4nZaKiS4WhTxSeRb6FAbaOLyIXT4b1TMfT6GT26nM?e=G6Fqam';
                    });
                }
            }

            // check existing session
            function checkExistingSession() {
                let stored = JSON.parse(localStorage.getItem('aesrn_user_session')||'{}');
                if (stored.email && stored.sessionId && Date.now() < stored.expiry) {
                    let sessions = getActiveSessions();
                    if (sessions[stored.email] && sessions[stored.email].sessionId === stored.sessionId) {
                        currentUserEmail = stored.email;
                        currentUserData = memberDetails.get(stored.email);
                        return true;
                    }
                }
                return false;
            }

            // ---------- EVENT LISTENERS ----------
            document.getElementById('loginForm').addEventListener('submit', handleLogin);
            document.getElementById('togglePassword').addEventListener('click', function() {
                let pwd = document.getElementById('password');
                let icon = this.querySelector('i');
                if (pwd.type === 'password') { pwd.type = 'text'; icon.classList.replace('fa-eye','fa-eye-slash'); }
                else { pwd.type = 'password'; icon.classList.replace('fa-eye-slash','fa-eye'); }
            });

            document.getElementById('viewAssignment').addEventListener('click', openAssignment);
            document.getElementById('makeSubmission').addEventListener('click', openSubmissionForm);
            document.getElementById('viewCorrections').addEventListener('click', openCorrections);
            document.getElementById('reviewMaterials').addEventListener('click', openResources);
            document.getElementById('backToDashboardBtn').addEventListener('click', closeForm);
            document.getElementById('returnToAdminView').addEventListener('click', returnToAdminView);

            document.getElementById('logoutBtn').addEventListener('click', () => document.getElementById('logoutModal').style.display = 'flex');
            document.getElementById('cancelLogout').addEventListener('click', () => document.getElementById('logoutModal').style.display = 'none');
            document.getElementById('confirmLogout').addEventListener('click', () => { performLogout(true); document.getElementById('logoutModal').style.display = 'none'; });
            document.querySelector('.modal-overlay').addEventListener('click', (e) => { if(e.target.classList.contains('modal-overlay')) e.target.style.display = 'none'; });

            document.getElementById('keepSessionBtn').addEventListener('click', continueSession);

            // Dark theme toggles
            document.getElementById('loginThemeToggle').addEventListener('click', toggleTheme);
            document.getElementById('dashboardThemeToggle').addEventListener('click', toggleTheme);

            setInterval(() => {
                if (currentUserEmail && !isViewingMember) { // Only check session if not viewing a member
                    let s = getActiveSessions();
                    if (!s[currentUserEmail] || s[currentUserEmail].sessionId !== sessionStorage.getItem('aesrn_sid')) {
                        alert('Session ended (another login)');
                        performLogout(false);
                    }
                }
            }, 30000);

            // initial load - FIXED LOGIN CARD FLASH
            window.addEventListener('load', () => {
                initTheme();
                setTimeout(() => {
                    document.getElementById('appLoader').style.opacity = '0';
                    setTimeout(() => {
                        document.getElementById('appLoader').style.display = 'none';
                        
                        // First check if we have a valid session - HIDE login container immediately
                        if (checkExistingSession()) {
                            // Valid session found - show dashboard directly, no login card flash
                            document.getElementById('dashboardContainer').style.display = 'block';
                            
                            renderDashboard();
                            
                            // Show member cards if founder
                            if (isFounder(currentUserEmail)) {
                                document.getElementById('membersSection').style.display = 'block';
                                renderMemberCards();
                                
                                // Check if we were viewing a member before reload
                                const savedViewingMember = localStorage.getItem('aesrn_viewing_member');
                                const savedOriginalFounder = localStorage.getItem('aesrn_original_founder');
                                
                                if (savedViewingMember && savedOriginalFounder) {
                                    // Restore the member view state
                                    originalFounderEmail = savedOriginalFounder;
                                    isViewingMember = true;
                                    switchToMemberView(savedViewingMember);
                                }
                            } else {
                                document.getElementById('membersSection').style.display = 'none';
                            }
                            
                            isDashboard = true;
                            resetTimers();
                            attachListeners();
                            initSubmissionIframe();
                        } else {
                            // No valid session - show login
                            document.getElementById('loginContainer').style.display = 'flex';
                        }
                        updateClock();
                    }, 400);
                }, 1500);
            });

// Auto-update copyright year for both footer and login
document.getElementById('footerYear').textContent = new Date().getFullYear();
document.getElementById('loginYear').textContent = new Date().getFullYear();
        })();
    </script>
</body>
</html>
