<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shoe Refresh - Layanan Laundry Sepatu & Aksesoris Profesional Cikarang Bekasi</title>
    <meta name="description" content="Layanan laundry sepatu profesional di Cikarang Bekasi. Cuci sepatu, tas, helm, stroller dengan teknologi modern. Pesan via WhatsApp sekarang!">
    <meta name="keywords" content="laundry sepatu, cuci sepatu, Cikarang, Bekasi, shoes clean, bag clean, helmet clean, stroller clean, sepatu bersih, perawatan sepatu">
    <meta name="author" content="Shoe Refresh">
    <meta property="og:title" content="Shoe Refresh - Layanan Laundry Sepatu Profesional">
    <meta property="og:description" content="Cuci sepatu, tas, helm, stroller dengan hasil maksimal di Cikarang Bekasi">
    <meta property="og:type" content="website">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="icon" type="image/x-icon" href="https://img.icons8.com/fluency/96/000000/sneakers.png">
    <style>
        :root {
            --dark-bg: #0a0a0a;
            --darker-bg: #050505;
            --card-bg: #121212;
            --neon-blue: #00f3ff;
            --neon-green: #00ff9d;
            --neon-pink: #ff00ff;
            --neon-yellow: #ffff00;
            --neon-white: #ffffff;
            --neon-dim: rgba(255, 255, 255, 0.7);
            --neon-dimmer: rgba(255, 255, 255, 0.5);
            --accent-blue: #0088ff;
            --whatsapp-green: #25D366;
            --shadow-neon: 0 0 10px, 0 0 20px, 0 0 40px;
            --transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        html {
            scroll-behavior: smooth;
            background-color: var(--dark-bg);
        }
        
        body {
            font-family: 'Inter', sans-serif;
            line-height: 1.6;
            color: var(--neon-dim);
            background-color: var(--dark-bg);
            max-width: 100%;
            overflow-x: hidden;
            padding-bottom: 20px;
        }
        
        .container {
            width: 100%;
            max-width: 500px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header & Navigation */
        header {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            z-index: 1000;
            background-color: rgba(10, 10, 10, 0.95);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid rgba(0, 243, 255, 0.1);
            padding: 15px 0;
        }
        
        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo h1 {
            font-size: 1.8rem;
            font-weight: 900;
            background: linear-gradient(90deg, var(--neon-blue), var(--neon-green));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 0 10px rgba(0, 243, 255, 0.3);
            margin-bottom: 3px;
            letter-spacing: -0.5px;
        }
        
        .logo p {
            font-size: 0.8rem;
            color: var(--neon-green);
            font-weight: 700;
            letter-spacing: 2px;
            text-transform: uppercase;
        }
        
        .mobile-menu-btn {
            background: none;
            border: none;
            font-size: 1.8rem;
            color: var(--neon-blue);
            cursor: pointer;
            transition: var(--transition);
        }
        
        .mobile-menu-btn:hover {
            color: var(--neon-green);
            transform: scale(1.1);
        }
        
        .mobile-menu {
            position: fixed;
            top: 70px;
            left: 0;
            width: 100%;
            background-color: rgba(18, 18, 18, 0.98);
            backdrop-filter: blur(15px);
            border-top: 1px solid rgba(0, 243, 255, 0.2);
            padding: 20px;
            display: none;
            z-index: 999;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
        }
        
        .mobile-menu.active {
            display: block;
            animation: slideDown 0.3s ease;
        }
        
        @keyframes slideDown {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .mobile-menu ul {
            list-style: none;
        }
        
        .mobile-menu ul li {
            margin-bottom: 15px;
        }
        
        .mobile-menu ul li a {
            text-decoration: none;
            color: var(--neon-dim);
            font-weight: 600;
            font-size: 1.2rem;
            display: block;
            padding: 12px 0;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
            transition: var(--transition);
        }
        
        .mobile-menu ul li a:hover {
            color: var(--neon-green);
            padding-left: 10px;
        }
        
        /* Hero Section */
        .hero {
            padding: 120px 0 40px;
            position: relative;
            overflow: hidden;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: radial-gradient(circle at 30% 30%, rgba(0, 243, 255, 0.05) 0%, transparent 70%);
            z-index: -1;
        }
        
        .hero-content h1 {
            font-size: 2.3rem;
            font-weight: 900;
            line-height: 1.2;
            margin-bottom: 20px;
            color: var(--neon-white);
            text-shadow: 0 0 15px rgba(255, 255, 255, 0.3);
        }
        
        .hero-content h1 span {
            background: linear-gradient(90deg, var(--neon-blue), var(--neon-pink));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        
        .hero-content p {
            font-size: 1.05rem;
            color: var(--neon-dim);
            margin-bottom: 30px;
            line-height: 1.7;
        }
        
        .stats {
            display: flex;
            justify-content: space-between;
            margin-bottom: 30px;
            background: rgba(0, 0, 0, 0.3);
            border-radius: 15px;
            padding: 20px;
            border: 1px solid rgba(0, 243, 255, 0.1);
        }
        
        .stat-item {
            text-align: center;
        }
        
        .stat-item h3 {
            font-size: 1.8rem;
            font-weight: 800;
            color: var(--neon-blue);
            margin-bottom: 5px;
            text-shadow: 0 0 10px rgba(0, 243, 255, 0.5);
        }
        
        .stat-item p {
            font-size: 0.8rem;
            color: var(--neon-dimmer);
        }
        
        .hero-image {
            position: relative;
            border-radius: 15px;
            overflow: hidden;
            height: 220px;
            margin-bottom: 30px;
            border: 2px solid rgba(0, 243, 255, 0.2);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
            background: linear-gradient(45deg, #0a0a0a, #1a1a2e);
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .shoe-image {
            width: 100%;
            height: 100%;
            object-fit: cover;
            opacity: 0.9;
        }
        
        /* WhatsApp Button - Flat Design */
        .whatsapp-button-container {
            width: 100%;
            margin: 40px auto 30px;
            display: flex;
            justify-content: center;
        }
        
        .whatsapp-button-flat {
            position: relative;
            background-color: var(--whatsapp-green);
            color: white;
            padding: 20px 40px;
            border-radius: 50px;
            font-weight: 800;
            font-size: 1.3rem;
            text-decoration: none;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 15px;
            box-shadow: 0 10px 25px rgba(37, 211, 102, 0.4);
            animation: pulseButton 2s infinite;
            transition: var(--transition);
            border: 2px solid rgba(255, 255, 255, 0.2);
            width: 100%;
            max-width: 400px;
        }
        
        @keyframes pulseButton {
            0% { transform: scale(1); box-shadow: 0 10px 25px rgba(37, 211, 102, 0.4); }
            50% { transform: scale(1.05); box-shadow: 0 15px 30px rgba(37, 211, 102, 0.6); }
            100% { transform: scale(1); box-shadow: 0 10px 25px rgba(37, 211, 102, 0.4); }
        }
        
        .whatsapp-button-flat:hover {
            transform: scale(1.08);
            box-shadow: 0 20px 40px rgba(37, 211, 102, 0.7);
            background-color: #128C7E;
        }
        
        .whatsapp-icon-large {
            font-size: 2.2rem;
            filter: drop-shadow(0 0 5px rgba(255, 255, 255, 0.7));
        }
        
        /* Services Highlight */
        .services-highlight {
            padding: 40px 0;
            text-align: center;
            border-top: 1px solid rgba(255, 255, 255, 0.05);
            border-bottom: 1px solid rgba(255, 255, 255, 0.05);
            margin-bottom: 30px;
        }
        
        .services-highlight-title {
            font-size: 1.3rem;
            color: var(--neon-white);
            margin-bottom: 25px;
            font-weight: 700;
            text-shadow: 0 0 10px rgba(0, 243, 255, 0.3);
        }
        
        .services-icons {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
        }
        
        .service-icon-item {
            background-color: rgba(255, 255, 255, 0.03);
            border-radius: 12px;
            padding: 20px 15px;
            display: flex;
            flex-direction: column;
            align-items: center;
            border: 1px solid rgba(255, 255, 255, 0.05);
            transition: var(--transition);
        }
        
        .service-icon-item:hover {
            background-color: rgba(0, 243, 255, 0.05);
            transform: translateY(-5px);
            border-color: rgba(0, 243, 255, 0.2);
        }
        
        .service-icon-item i {
            font-size: 2.2rem;
            color: var(--neon-blue);
            margin-bottom: 15px;
            text-shadow: 0 0 10px rgba(0, 243, 255, 0.5);
        }
        
        .service-icon-item p {
            font-weight: 600;
            color: var(--neon-white);
            font-size: 1rem;
        }
        
        /* Section Styling */
        .section {
            padding: 50px 0;
            border-bottom: 1px solid rgba(255, 255, 255, 0.05);
        }
        
        .section-title {
            margin-bottom: 35px;
            position: relative;
        }
        
        .section-title h2 {
            font-size: 1.9rem;
            font-weight: 800;
            color: var(--neon-white);
            margin-bottom: 10px;
            text-shadow: 0 0 10px rgba(255, 255, 255, 0.2);
        }
        
        .section-title h2 span {
            background: linear-gradient(90deg, var(--neon-blue), var(--neon-pink));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        
        .section-title p {
            font-size: 0.95rem;
            color: var(--neon-dimmer);
            max-width: 90%;
        }
        
        /* Value Cards */
        .value-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
        }
        
        .value-card {
            background-color: var(--card-bg);
            padding: 25px;
            border-radius: 15px;
            border: 1px solid rgba(0, 243, 255, 0.1);
            transition: var(--transition);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
        }
        
        .value-card:hover {
            transform: translateY(-5px);
            border-color: rgba(0, 243, 255, 0.3);
            box-shadow: 0 10px 25px rgba(0, 243, 255, 0.1);
        }
        
        .value-icon {
            font-size: 2.2rem;
            margin-bottom: 20px;
            color: var(--neon-blue);
            text-shadow: 0 0 10px rgba(0, 243, 255, 0.5);
        }
        
        .value-card h3 {
            font-size: 1.3rem;
            margin-bottom: 15px;
            font-weight: 700;
            color: var(--neon-white);
        }
        
        .value-card p {
            color: var(--neon-dim);
            font-size: 0.9rem;
            line-height: 1.7;
        }
        
        /* Services Section */
        .services-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
        }
        
        .service-card {
            background-color: var(--card-bg);
            border-radius: 15px;
            overflow: hidden;
            border: 1px solid rgba(255, 255, 255, 0.05);
            transition: var(--transition);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
        }
        
        .service-card:hover {
            transform: translateY(-5px);
            border-color: rgba(0, 255, 157, 0.2);
            box-shadow: 0 10px 25px rgba(0, 255, 157, 0.1);
        }
        
        .service-header {
            padding: 20px 20px 15px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.05);
        }
        
        .service-header h3 {
            font-size: 1.4rem;
            margin-bottom: 10px;
            color: var(--neon-white);
            font-weight: 700;
        }
        
        .price {
            font-size: 1.8rem;
            font-weight: 800;
            color: var(--neon-green);
            margin-bottom: 5px;
            text-shadow: 0 0 10px rgba(0, 255, 157, 0.5);
        }
        
        .service-details {
            padding: 20px;
        }
        
        .service-details ul {
            list-style: none;
        }
        
        .service-details ul li {
            padding: 8px 0;
            color: var(--neon-dim);
            border-bottom: 1px dashed rgba(255, 255, 255, 0.05);
            display: flex;
            align-items: center;
            font-size: 0.9rem;
        }
        
        .service-details ul li:last-child {
            border-bottom: none;
        }
        
        .service-details ul li i {
            color: var(--neon-green);
            margin-right: 10px;
            font-size: 0.9rem;
        }
        
        /* Process Section */
        .process-steps {
            display: grid;
            grid-template-columns: 1fr;
            gap: 25px;
            position: relative;
        }
        
        .process-step {
            display: flex;
            align-items: flex-start;
            position: relative;
        }
        
        .step-number {
            width: 45px;
            height: 45px;
            min-width: 45px;
            background: linear-gradient(135deg, var(--neon-blue), var(--accent-blue));
            color: var(--dark-bg);
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 1.2rem;
            font-weight: 800;
            margin-right: 15px;
            box-shadow: 0 0 15px rgba(0, 243, 255, 0.5);
        }
        
        .step-content h4 {
            font-size: 1.2rem;
            margin-bottom: 8px;
            color: var(--neon-white);
            font-weight: 700;
        }
        
        .step-content p {
            color: var(--neon-dim);
            font-size: 0.9rem;
            line-height: 1.7;
        }
        
        /* Testimonials */
        .testimonials-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
        }
        
        .testimonial-card {
            background-color: var(--card-bg);
            padding: 20px;
            border-radius: 15px;
            border: 1px solid rgba(255, 255, 255, 0.05);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
        }
        
        .testimonial-header {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
        }
        
        .testimonial-avatar {
            width: 50px;
            height: 50px;
            min-width: 50px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--neon-pink), var(--neon-blue));
            display: flex;
            justify-content: center;
            align-items: center;
            margin-right: 15px;
            font-size: 1.5rem;
            color: var(--dark-bg);
            font-weight: 700;
        }
        
        .testimonial-info h4 {
            font-size: 1rem;
            margin-bottom: 5px;
            color: var(--neon-white);
        }
        
        .testimonial-info p {
            font-size: 0.85rem;
            color: var(--neon-dimmer);
        }
        
        .rating {
            color: var(--neon-yellow);
            margin-bottom: 10px;
            font-size: 0.9rem;
        }
        
        .testimonial-text {
            color: var(--neon-dim);
            font-style: italic;
            line-height: 1.7;
            font-size: 0.9rem;
        }
        
        /* Services List */
        .services-list {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
            margin-top: 30px;
        }
        
        .service-item {
            background-color: rgba(0, 243, 255, 0.05);
            padding: 15px;
            border-radius: 10px;
            text-align: center;
            border: 1px solid rgba(0, 243, 255, 0.1);
            transition: var(--transition);
        }
        
        .service-item:hover {
            background-color: rgba(0, 243, 255, 0.1);
            transform: scale(1.05);
        }
        
        .service-item i {
            font-size: 1.6rem;
            color: var(--neon-blue);
            margin-bottom: 10px;
            display: block;
        }
        
        .service-item p {
            font-weight: 600;
            color: var(--neon-white);
            font-size: 0.9rem;
        }
        
        /* CTA Section */
        .cta-section {
            padding: 50px 0;
            text-align: center;
            position: relative;
        }
        
        .cta-section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: radial-gradient(circle at 70% 30%, rgba(255, 0, 255, 0.05) 0%, transparent 70%);
            z-index: -1;
        }
        
        .cta-section h2 {
            font-size: 2rem;
            margin-bottom: 20px;
            color: var(--neon-white);
            font-weight: 800;
        }
        
        .cta-section h2 span {
            background: linear-gradient(90deg, var(--neon-pink), var(--neon-yellow));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        
        .cta-section p {
            font-size: 1.05rem;
            color: var(--neon-dim);
            margin-bottom: 30px;
            max-width: 90%;
            margin-left: auto;
            margin-right: auto;
            line-height: 1.7;
        }
        
        .cta-buttons {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-top: 30px;
        }
        
        .cta-button {
            padding: 18px 25px;
            font-size: 1.1rem;
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            text-decoration: none;
            font-weight: 700;
            transition: var(--transition);
            border: 2px solid transparent;
        }
        
        .btn-whatsapp {
            background-color: var(--whatsapp-green);
            color: white;
        }
        
        .btn-whatsapp:hover {
            background-color: #128C7E;
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(37, 211, 102, 0.3);
        }
        
        .btn-location {
            background-color: transparent;
            color: var(--neon-blue);
            border-color: var(--neon-blue);
        }
        
        .btn-location:hover {
            background-color: rgba(0, 243, 255, 0.1);
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 243, 255, 0.2);
        }
        
        /* Footer */
        footer {
            background-color: var(--darker-bg);
            color: var(--neon-dim);
            padding: 50px 0 25px;
            border-top: 1px solid rgba(0, 243, 255, 0.1);
        }
        
        .footer-container {
            display: flex;
            flex-direction: column;
            gap: 35px;
        }
        
        .footer-column h3 {
            font-size: 1.3rem;
            margin-bottom: 20px;
            color: var(--neon-white);
            font-weight: 700;
            position: relative;
            padding-bottom: 8px;
        }
        
        .footer-column h3::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 50px;
            height: 3px;
            background: linear-gradient(90deg, var(--neon-blue), transparent);
        }
        
        .footer-column p, .footer-column a {
            color: var(--neon-dim);
            margin-bottom: 10px;
            display: block;
            text-decoration: none;
            transition: var(--transition);
            line-height: 1.7;
            font-size: 0.95rem;
        }
        
        .footer-column a:hover {
            color: var(--neon-green);
            padding-left: 5px;
        }
        
        .contact-item {
            display: flex;
            align-items: flex-start;
            margin-bottom: 15px;
        }
        
        .contact-item i {
            color: var(--neon-blue);
            margin-right: 10px;
            margin-top: 3px;
            font-size: 1.1rem;
        }
        
        .social-icons {
            display: flex;
            gap: 12px;
            margin-top: 20px;
        }
        
        .social-icons a {
            width: 40px;
            height: 40px;
            background-color: rgba(255, 255, 255, 0.05);
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            color: var(--neon-dim);
            font-size: 1.1rem;
            transition: var(--transition);
        }
        
        .social-icons a:hover {
            background-color: var(--neon-blue);
            color: var(--dark-bg);
            transform: translateY(-5px);
        }
        
        .copyright {
            text-align: center;
            padding-top: 25px;
            border-top: 1px solid rgba(255, 255, 255, 0.05);
            color: var(--neon-dimmer);
            font-size: 0.85rem;
            margin-top: 35px;
        }
        
        /* Floating WhatsApp */
        .floating-whatsapp {
            position: fixed;
            bottom: 25px;
            right: 25px;
            width: 60px;
            height: 60px;
            background-color: var(--whatsapp-green);
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            font-size: 1.8rem;
            z-index: 999;
            box-shadow: 0 5px 20px rgba(37, 211, 102, 0.5);
            animation: pulseFloat 3s infinite;
            text-decoration: none;
            transition: var(--transition);
        }
        
        @keyframes pulseFloat {
            0% { transform: scale(1); box-shadow: 0 5px 20px rgba(37, 211, 102, 0.5); }
            50% { transform: scale(1.1); box-shadow: 0 8px 25px rgba(37, 211, 102, 0.7); }
            100% { transform: scale(1); box-shadow: 0 5px 20px rgba(37, 211, 102, 0.5); }
        }
        
        .floating-whatsapp:hover {
            transform: scale(1.2);
            box-shadow: 0 10px 30px rgba(37, 211, 102, 0.8);
        }
        
        /* Animations */
        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        @keyframes iconFloatIn {
            0% { 
                opacity: 0; 
                transform: translateY(30px) scale(0.8); 
            }
            60% { 
                opacity: 1; 
                transform: translateY(-5px) scale(1.05); 
            }
            100% { 
                opacity: 1; 
                transform: translateY(0) scale(1); 
            }
        }
        
        .fade-in {
            animation: fadeInUp 0.8s ease forwards;
        }
        
        .icon-float-in {
            animation: iconFloatIn 0.8s ease forwards;
        }
        
        .delay-1 { animation-delay: 0.1s; }
        .delay-2 { animation-delay: 0.2s; }
        .delay-3 { animation-delay: 0.3s; }
        .delay-4 { animation-delay: 0.4s; }
        .delay-5 { animation-delay: 0.5s; }
        .delay-6 { animation-delay: 0.6s; }
        
        /* Responsive Adjustments */
        @media (max-width: 480px) {
            .container {
                padding: 0 15px;
            }
            
            .hero-content h1 {
                font-size: 2rem;
            }
            
            .stats {
                flex-direction: column;
                gap: 20px;
            }
            
            .services-list {
                grid-template-columns: 1fr;
            }
            
            .whatsapp-button-flat {
                font-size: 1.2rem;
                padding: 18px 30px;
            }
            
            .whatsapp-icon-large {
                font-size: 2rem;
            }
            
            .services-icons {
                grid-template-columns: 1fr;
            }
        }
        
        @media (min-width: 768px) {
            .container {
                max-width: 500px;
            }
        }
    </style>
</head>
<body>
    <!-- Header & Navigation -->
    <header id="header">
        <div class="container header-container">
            <div class="logo">
                <h1>Shoe Refresh</h1>
                <p>Pede Auto Fresh</p>
            </div>
            
            <button class="mobile-menu-btn" id="mobileMenuBtn">
                <i class="fas fa-bars"></i>
            </button>
        </div>
        
        <!-- Mobile Menu -->
        <div class="mobile-menu" id="mobileMenu">
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#values">Keunggulan</a></li>
                <li><a href="#services">Layanan</a></li>
                <li><a href="#process">Proses</a></li>
                <li><a href="#testimonials">Testimoni</a></li>
                <li><a href="#contact">Kontak</a></li>
                <li><a href="https://wa.me/6287720123511?text=Halo%20Shoe%20Refresh,%20saya%20ingin%20konsultasi%20tentang%20layanan%20laundry%20sepatu" target="_blank" class="btn-whatsapp cta-button" style="margin-top: 20px; display: inline-block; text-align: center;"><i class="fab fa-whatsapp"></i> Pesan Sekarang</a></li>
            </ul>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <div class="hero-content fade-in">
                <h1>Sepatu Bersih, <span>Langkah Lebih Percaya Diri</span></h1>
                <p>Layanan spesialis laundry sepatu dengan teknologi modern dan eco-friendly. Kami rawat sepatu kesayangan Anda seperti milik sendiri.</p>
                
                <div class="hero-image fade-in delay-1">
                    <img src="https://images.unsplash.com/photo-1606107557195-0e29a4b5b4aa?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Sepatu bersih setelah dicuci di Shoe Refresh" class="shoe-image">
                </div>
                
                <div class="stats fade-in delay-2">
                    <div class="stat-item">
                        <h3>500+</h3>
                        <p>Sepatu telah direfresh</p>
                    </div>
                    <div class="stat-item">
                        <h3>98%</h3>
                        <p>Kepuasan pelanggan</p>
                    </div>
                    <div class="stat-item">
                        <h3>2-3</h3>
                        <p>Hari pengerjaan</p>
                    </div>
                </div>
            </div>
            
            <!-- WhatsApp Button - Flat Design -->
            <div class="whatsapp-button-container fade-in delay-3">
                <a href="https://wa.me/6287720123511?text=Halo%20Shoe%20Refresh,%20saya%20ingin%20konsultasi%20tentang%20layanan%20laundry%20sepatu" target="_blank" class="whatsapp-button-flat">
                    <i class="fab fa-whatsapp whatsapp-icon-large"></i>
                    <span>Hubungi via WhatsApp</span>
                </a>
            </div>
            
            <!-- Services Icons Section -->
            <div class="services-highlight fade-in delay-4">
                <div class="services-highlight-title">Layanan Lengkap untuk Semua Kebutuhan</div>
                <div class="services-icons">
                    <div class="service-icon-item icon-float-in delay-1">
                        <i class="fas fa-shoe-prints"></i>
                        <p>Shoes Clean</p>
                    </div>
                    <div class="service-icon-item icon-float-in delay-2">
                        <i class="fas fa-shopping-bag"></i>
                        <p>Bag Clean</p>
                    </div>
                    <div class="service-icon-item icon-float-in delay-3">
                        <i class="fas fa-helmet-safety"></i>
                        <p>Helmet Clean</p>
                    </div>
                    <div class="service-icon-item icon-float-in delay-4">
                        <i class="fas fa-baby-carriage"></i>
                        <p>Stroller Clean</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Value Proposition Section -->
    <section class="section" id="values">
        <div class="container">
            <div class="section-title fade-in">
                <h2>Kenapa <span>Memilih Kami?</span></h2>
                <p>Kami memberikan perawatan terbaik untuk sepatu kesayangan Anda dengan teknologi terkini dan tim ahli</p>
            </div>
            
            <div class="value-grid">
                <div class="value-card fade-in delay-1">
                    <div class="value-icon">
                        <i class="fas fa-bacteria"></i>
                    </div>
                    <h3>Teknologi UV Sanitasi</h3>
                    <p>Bebas bakteri & jamur dengan sinar UV yang efektif membunuh mikroorganisme berbahaya pada sepatu.</p>
                </div>
                
                <div class="value-card fade-in delay-2">
                    <div class="value-icon">
                        <i class="fas fa-leaf"></i>
                    </div>
                    <h3>Eco-Friendly</h3>
                    <p>Menggunakan deterjen ramah lingkungan yang aman untuk kulit dan tidak merusak material sepatu.</p>
                </div>
                
                <div class="value-card fade-in delay-3">
                    <div class="value-icon">
                        <i class="fas fa-bolt"></i>
                    </div>
                    <h3>Fast Turnaround</h3>
                    <p>Siap dalam 2-3 hari dengan proses yang cepat tanpa mengorbankan kualitas hasil cleaning.</p>
                </div>
                
                <div class="value-card fade-in delay-4">
                    <div class="value-icon">
                        <i class="fas fa-user-tie"></i>
                    </div>
                    <h3>Ahli Sepatu</h3>
                    <p>Ditangani oleh spesialis bersertifikat yang memahami berbagai bahan dan jenis sepatu.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="section" id="services" style="background-color: rgba(0,0,0,0.2);">
        <div class="container">
            <div class="section-title fade-in">
                <h2>Layanan <span>Kami</span></h2>
                <p>Pilih paket yang sesuai dengan kebutuhan sepatu Anda. Semua paket sudah termasuk jemput antar gratis dalam radius 5km</p>
            </div>
            
            <div class="services-grid">
                <div class="service-card fade-in delay-1">
                    <div class="service-header">
                        <h3>Basic Clean</h3>
                        <div class="price">Rp 25.000</div>
                        <p>Untuk perawatan rutin</p>
                    </div>
                    
                    <div class="service-details">
                        <ul>
                            <li><i class="fas fa-check"></i> Cuci eksterior menyeluruh</li>
                            <li><i class="fas fa-check"></i> Penghilangan noda ringan</li>
                            <li><i class="fas fa-check"></i> Pengeringan optimal</li>
                            <li><i class="fas fa-check"></i> Aroma fresh</li>
                        </ul>
                    </div>
                </div>
                
                <div class="service-card fade-in delay-2">
                    <div class="service-header">
                        <h3>Deep Clean</h3>
                        <div class="price">Rp 45.000</div>
                        <p>Pilihan terpopuler</p>
                    </div>
                    
                    <div class="service-details">
                        <ul>
                            <li><i class="fas fa-check"></i> Semua fitur Basic Clean</li>
                            <li><i class="fas fa-check"></i> Cuci menyeluruh interior & eksterior</li>
                            <li><i class="fas fa-check"></i> Deodorisasi menyeluruh</li>
                            <li><i class="fas fa-check"></i> UV sanitasi</li>
                            <li><i class="fas fa-check"></i> Whitening untuk sol putih</li>
                        </ul>
                    </div>
                </div>
                
                <div class="service-card fade-in delay-3">
                    <div class="service-header">
                        <h3>Premium Treatment</h3>
                        <div class="price">Rp 75.000</div>
                        <p>Perawatan maksimal</p>
                    </div>
                    
                    <div class="service-details">
                        <ul>
                            <li><i class="fas fa-check"></i> Semua fitur Deep Clean</li>
                            <li><i class="fas fa-check"></i> Waterproofing treatment</li>
                            <li><i class="fas fa-check"></i> Special care untuk bahan premium</li>
                            <li><i class="fas fa-check"></i> Conditioning & polishing</li>
                            <li><i class="fas fa-check"></i> Priority service</li>
                        </ul>
                    </div>
                </div>
            </div>
            
            <!-- Additional Services -->
            <div class="section-title fade-in" style="margin-top: 50px;">
                <h2>Layanan <span>Lainnya</span></h2>
                <p>Kami juga menyediakan layanan cleaning untuk berbagai kebutuhan lainnya</p>
            </div>
            
            <div class="services-list">
                <div class="service-item icon-float-in delay-1">
                    <i class="fas fa-shoe-prints"></i>
                    <p>Shoes Clean</p>
                </div>
                <div class="service-item icon-float-in delay-2">
                    <i class="fas fa-shopping-bag"></i>
                    <p>Bag Clean</p>
                </div>
                <div class="service-item icon-float-in delay-3">
                    <i class="fas fa-helmet-safety"></i>
                    <p>Helmet Clean</p>
                </div>
                <div class="service-item icon-float-in delay-4">
                    <i class="fas fa-baby-carriage"></i>
                    <p>Stroller Clean</p>
                </div>
                <div class="service-item icon-float-in delay-5">
                    <i class="fas fa-tshirt"></i>
                    <p>Jaket & Outerwear</p>
                </div>
                <div class="service-item icon-float-in delay-6">
                    <i class="fas fa-running"></i>
                    <p>Sepatu Olahraga</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Process Section -->
    <section class="section" id="process">
        <div class="container">
            <div class="section-title fade-in">
                <h2>Proses <span>Mudah</span></h2>
                <p>Hanya dengan 4 langkah sederhana, sepatu Anda akan kembali fresh dan bersih maksimal</p>
            </div>
            
            <div class="process-steps">
                <div class="process-step fade-in delay-1">
                    <div class="step-number">1</div>
                    <div class="step-content">
                        <h4>Drop-off / Pickup</h4>
                        <p>Jemput antar gratis dalam radius 5km atau drop-off ke workshop kami</p>
                    </div>
                </div>
                
                <div class="process-step fade-in delay-2">
                    <div class="step-number">2</div>
                    <div class="step-content">
                        <h4>Diagnosis</h4>
                        <p>Pemeriksaan kondisi sepatu dan rekomendasi perawatan terbaik</p>
                    </div>
                </div>
                
                <div class="process-step fade-in delay-3">
                    <div class="step-number">3</div>
                    <div class="step-content">
                        <h4>Treatment</h4>
                        <p>Proses cleaning sesuai paket yang dipilih dengan teknologi modern</p>
                    </div>
                </div>
                
                <div class="process-step fade-in delay-4">
                    <div class="step-number">4</div>
                    <div class="step-content">
                        <h4>Ready</h4>
                        <p>Notifikasi & pengantaran kembali sepatu yang sudah bersih maksimal</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="section" id="testimonials" style="background-color: rgba(0,0,0,0.2);">
        <div class="container">
            <div class="section-title fade-in">
                <h2>Testimoni <span>Pelanggan</span></h2>
                <p>Lihat pengalaman nyata dari pelanggan yang telah mempercayakan sepatu kesayangan mereka pada kami</p>
            </div>
            
            <div class="testimonials-grid">
                <div class="testimonial-card fade-in delay-1">
                    <div class="testimonial-header">
                        <div class="testimonial-avatar">
                            R
                        </div>
                        <div class="testimonial-info">
                            <h4>Rizky Pratama</h4>
                            <p>Mahasiswa</p>
                        </div>
                    </div>
                    
                    <div class="rating">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    
                    <p class="testimonial-text">"Sepatu sneaker kesayangan saya yang sudah 2 tahun akhirnya bersih seperti baru lagi! Hasilnya melebihi ekspektasi, dan harganya terjangkau untuk kualitas premium."</p>
                </div>
                
                <div class="testimonial-card fade-in delay-2">
                    <div class="testimonial-header">
                        <div class="testimonial-avatar">
                            S
                        </div>
                        <div class="testimonial-info">
                            <h4>Sarah Wijaya</h4>
                            <p>Karyawan</p>
                        </div>
                    </div>
                    
                    <div class="rating">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                    
                    <p class="testimonial-text">"Sebagai orang yang sibuk, jemput antar gratis sangat membantu. Sepatu kerja saya yang kotor terkena lumpur kini bersih total. Recommended banget!"</p>
                </div>
                
                <div class="testimonial-card fade-in delay-3">
                    <div class="testimonial-header">
                        <div class="testimonial-avatar">
                            A
                        </div>
                        <div class="testimonial-info">
                            <h4>Andi Setiawan</h4>
                            <p>Freelancer</p>
                        </div>
                    </div>
                    
                    <div class="rating">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    
                    <p class="testimonial-text">"Sepatu kulit mahal saya dirawat dengan sangat baik. Hasilnya mengkilap dan wangi. Timnya profesional dan komunikasif. Pasti akan pakai layanan ini lagi!"</p>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="cta-section" id="contact">
        <div class="container">
            <h2 class="fade-in">Siap <span>Refresh Sepatu</span> Anda Hari Ini?</h2>
            <p class="fade-in delay-1">Pesan via WhatsApp untuk konsultasi gratis atau langsung drop-off ke lokasi kami. Jadwalkan perawatan sepatu Anda sekarang untuk spot terbatas!</p>
            
            <div class="cta-buttons">
                <a href="https://wa.me/6287720123511?text=Halo%20Shoe%20Refresh,%20saya%20ingin%20konsultasi%20tentang%20layanan%20laundry%20sepatu" target="_blank" class="cta-button btn-whatsapp fade-in delay-2">
                    <i class="fab fa-whatsapp"></i> Chat via WhatsApp
                </a>
                <a href="https://maps.app.goo.gl/KNTtiepbHge7i1tm7" target="_blank" class="cta-button btn-location fade-in delay-3">
                    <i class="fas fa-map-marker-alt"></i> Kunjungi Workshop Kami
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-container">
                <div class="footer-column">
                    <h3>Shoe Refresh</h3>
                    <p>Pede Auto Fresh. Layanan spesialis laundry sepatu dengan teknologi modern dan eco-friendly untuk semua kalangan di area Cikarang Bekasi.</p>
                    <div class="social-icons">
                        <a href="#" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
                        <a href="#" aria-label="Facebook"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" aria-label="TikTok"><i class="fab fa-tiktok"></i></a>
                        <a href="https://wa.me/6287720123511" target="_blank" aria-label="WhatsApp"><i class="fab fa-whatsapp"></i></a>
                    </div>
                </div>
                
                <div class="footer-column">
                    <h3>Kontak & Lokasi</h3>
                    <div class="contact-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <div>
                            <a href="https://maps.app.goo.gl/KNTtiepbHge7i1tm7" target="_blank">Jl. Cikarang-Cibarusah Leuweung Malang RT/RW 07/01 No:57, Sukaresmi, Cikarang Selatan, Bekasi</a>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-phone-alt"></i>
                        <div>
                            <a href="https://wa.me/6287720123511" target="_blank">0877-2012-3511</a>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-envelope"></i>
                        <div>
                            <a href="mailto:shoerefreshcikarang@gmail.com">shoerefreshcikarang@gmail.com</a>
                        </div>
                    </div>
                </div>
                
                <div class="footer-column">
                    <h3>Jam Operasional</h3>
                    <p>Rabu - Senin: 08:00 - 20:00</p>
                    <p>Selasa: TUTUP</p>
                    <p>Hari Libur Nasional: TUTUP</p>
                </div>
                
                <div class="footer-column">
                    <h3>Layanan Kami</h3>
                    <a href="#services">Shoes Clean</a>
                    <a href="#services">Bag Clean</a>
                    <a href="#services">Helmet Clean</a>
                    <a href="#services">Stroller Clean</a>
                    <a href="#services">Jaket & Outerwear</a>
                </div>
            </div>
            
            <div class="copyright">
                <p>&copy; 2023 Shoe Refresh Cikarang. All rights reserved. Designed with <i class="fas fa-heart" style="color:#ff00ff;"></i> for sneaker lovers.</p>
            </div>
        </div>
    </footer>

    <!-- Floating WhatsApp Button -->
    <a href="https://wa.me/6287720123511?text=Halo%20Shoe%20Refresh,%20saya%20ingin%20konsultasi%20tentang%20layanan%20laundry%20sepatu" target="_blank" class="floating-whatsapp">
        <i class="fab fa-whatsapp"></i>
    </a>

    <!-- JavaScript -->
    <script>
        // Mobile Menu Toggle
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const mobileMenu = document.getElementById('mobileMenu');
        
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('active');
            mobileMenuBtn.innerHTML = mobileMenu.classList.contains('active') 
                ? '<i class="fas fa-times"></i>' 
                : '<i class="fas fa-bars"></i>';
        });
        
        // Close mobile menu when clicking a link
        const mobileLinks = document.querySelectorAll('.mobile-menu a');
        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.remove('active');
                mobileMenuBtn.innerHTML = '<i class="fas fa-bars"></i>';
            });
        });
        
        // Header scroll effect
        const header = document.getElementById('header');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 100) {
                header.style.backgroundColor = 'rgba(5, 5, 5, 0.98)';
                header.style.backdropFilter = 'blur(15px)';
            } else {
                header.style.backgroundColor = 'rgba(10, 10, 10, 0.95)';
                header.style.backdropFilter = 'blur(10px)';
            }
        });
        
        // Smooth scroll for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });
        
        // Add scroll animations
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };
        
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('fade-in');
                    if (entry.target.classList.contains('service-icon-item') || 
                        entry.target.classList.contains('service-item')) {
                        entry.target.classList.add('icon-float-in');
                    }
                }
            });
        }, observerOptions);
        
        // Observe elements for animation
        document.querySelectorAll('.value-card, .service-card, .process-step, .testimonial-card, .service-item, .service-icon-item').forEach(el => {
            observer.observe(el);
        });
        
        // WhatsApp button hover effect
        const whatsappButton = document.querySelector('.whatsapp-button-flat');
        if (whatsappButton) {
            whatsappButton.addEventListener('mouseenter', () => {
                whatsappButton.style.animation = 'pulseButton 0.5s infinite';
            });
            
            whatsappButton.addEventListener('mouseleave', () => {
                whatsappButton.style.animation = 'pulseButton 2s infinite';
            });
        }
        
        // WhatsApp click tracking
        const whatsappButtons = document.querySelectorAll('a[href*="wa.me"]');
        whatsappButtons.forEach(button => {
            button.addEventListener('click', () => {
                console.log('WhatsApp button clicked - tracking conversion');
                // Here you can add analytics tracking
            });
        });
        
        // Page load completion
        window.addEventListener('load', () => {
            console.log('Shoe Refresh Landing Page loaded successfully!');
            
            // Add loaded class to body for any post-load animations
            document.body.classList.add('loaded');
            
            // Initialize all fade-in elements
            const fadeElements = document.querySelectorAll('.fade-in');
            fadeElements.forEach(el => {
                if (!el.classList.contains('fade-in-applied')) {
                    el.classList.add('fade-in-applied');
                }
            });
        });
    </script>
</body>
</html>
