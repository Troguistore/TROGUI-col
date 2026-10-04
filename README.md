<!DOCTYPE html>
<html lang="es-CO">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#121417">
  <meta name="description" content="Hidrolavadora inalámbrica 48V portátil. Incluye doble batería, boquilla 6 en 1 y pago contra entrega según cobertura.">

  <title>Hidrolavadora Inalámbrica 48V | Pago contra entrega</title>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@600;700;800&family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <style>
    :root {
      --orange: #f15a24;
      --orange-dark: #d94716;
      --orange-light: #fff1ea;
      --ink: #121417;
      --ink-2: #24282e;
      --muted: #667085;
      --line: #e8eaed;
      --paper: #f6f7f8;
      --white: #ffffff;
      --whatsapp: #1fa855;
      --success: #168445;
      --radius: 18px;
      --shadow: 0 18px 50px rgba(18, 20, 23, 0.12);
      --shadow-soft: 0 10px 30px rgba(18, 20, 23, 0.08);
    }

    * {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      color: var(--ink);
      font-family: "Inter", Arial, sans-serif;
      background: var(--white);
      overflow-x: hidden;
    }

    body.modal-open {
      overflow: hidden;
    }

    img,
    video {
      display: block;
      max-width: 100%;
    }

    button,
    input,
    select,
    textarea {
      font: inherit;
    }

    button {
      cursor: pointer;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    .container {
      width: min(1160px, calc(100% - 32px));
      margin: 0 auto;
    }

    .topbar {
      padding: 10px 16px;
      color: #ffffff;
      font-size: 12px;
      font-weight: 700;
      text-align: center;
      background: var(--ink);
    }

    .topbar-inner {
      display: flex;
      justify-content: center;
      gap: 18px;
      flex-wrap: wrap;
    }

    .topbar-item {
      display: inline-flex;
      align-items: center;
      gap: 6px;
    }

    .topbar-dot {
      width: 6px;
      height: 6px;
      background: var(--orange);
      border-radius: 50%;
    }

    .site-header {
      position: sticky;
      top: 0;
      z-index: 40;
      background: rgba(255, 255, 255, 0.93);
      border-bottom: 1px solid transparent;
      backdrop-filter: blur(12px);
      transition: 0.2s ease;
    }

    .site-header.scrolled {
      border-color: var(--line);
      box-shadow: 0 5px 22px rgba(18, 20, 23, 0.05);
    }

    .header-inner {
      min-height: 70px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 16px;
    }

    .brand {
      display: inline-flex;
      align-items: center;
      gap: 10px;
      font-weight: 800;
      letter-spacing: -0.04em;
    }

    .brand-mark {
      width: 34px;
      height: 34px;
      display: grid;
      place-items: center;
      color: #ffffff;
      font-family: "Barlow Condensed", sans-serif;
      font-size: 24px;
      font-style: italic;
      font-weight: 800;
      background: var(--orange);
      border-radius: 9px;
    }

    .brand small {
      display: block;
      margin-bottom: 1px;
      color: var(--muted);
      font-size: 9px;
      font-weight: 700;
      letter-spacing: 0.1em;
      text-transform: uppercase;
    }

    .brand-name {
      font-size: 17px;
    }

    .header-action {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      min-height: 42px;
      padding: 0 15px;
      color: var(--ink);
      font-size: 13px;
      font-weight: 800;
      white-space: nowrap;
      background: transparent;
      border: 1px solid var(--line);
      border-radius: 10px;
      transition: 0.2s ease;
    }

    .header-action:hover {
      color: var(--orange);
      border-color: var(--orange);
    }

    .hero {
      position: relative;
      overflow: hidden;
      padding: 36px 0 56px;
      background:
        radial-gradient(circle at 78% 10%, rgba(241, 90, 36, 0.17), transparent 28%),
        linear-gradient(135deg, #f8f9fa 0%, #ffffff 56%, #f4f5f7 100%);
    }

    .hero-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      align-items: center;
      gap: 44px;
    }

    .eyebrow {
      display: inline-flex;
      align-items: center;
      gap: 7px;
      padding: 8px 11px;
      color: var(--orange-dark);
      font-size: 11px;
      font-weight: 800;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      background: var(--orange-light);
      border: 1px solid #ffd8c9;
      border-radius: 999px;
    }

    .eyebrow span {
      width: 7px;
      height: 7px;
      background: var(--orange);
      border-radius: 50%;
    }

    h1,
    h2,
    h3,
    p {
      margin-top: 0;
    }

    h1 {
      max-width: 650px;
      margin: 16px 0 14px;
      font-family: "Barlow Condensed", Impact, sans-serif;
      font-size: clamp(46px, 6vw, 76px);
      font-style: italic;
      font-weight: 800;
      line-height: 0.88;
      letter-spacing: -0.035em;
      text-transform: uppercase;
    }

    h1 em {
      color: var(--orange);
      font-style: normal;
    }

    .hero-copy {
      max-width: 580px;
      margin-bottom: 18px;
      color: #48515f;
      font-size: clamp(15px, 2vw, 18px);
      line-height: 1.6;
    }

    .rating {
      display: flex;
      align-items: center;
      gap: 9px;
      margin-bottom: 19px;
      color: #4d5664;
      font-size: 13px;
      font-weight: 600;
    }

    .stars {
      color: #f7a600;
      font-size: 17px;
      letter-spacing: 1px;
    }

    .hero-price {
      display: flex;
      align-items: flex-end;
      flex-wrap: wrap;
      gap: 12px;
      margin-bottom: 18px;
    }

    .old-price {
      color: var(--muted);
      font-size: 15px;
      font-weight: 600;
    }

    .old-price s {
      color: #9aa2ae;
    }

    .price-big {
      color: var(--orange);
      font-family: "Barlow Condensed", sans-serif;
      font-size: clamp(48px, 6vw, 68px);
      font-weight: 800;
      line-height: 0.8;
      letter-spacing: -0.04em;
    }

    .price-tag {
      margin-bottom: 2px;
      padding: 7px 10px;
      color: var(--success);
      font-size: 11px;
      font-weight: 800;
      background: #eaf8ef;
      border-radius: 8px;
    }

    .hero-actions {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }

    .btn {
      min-height: 54px;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 9px;
      padding: 12px 20px;
      font-size: 15px;
      font-weight: 800;
      border: 0;
      border-radius: 12px;
      transition: transform 0.2s ease, box-shadow 0.2s ease, background 0.2s ease;
    }

    .btn:hover {
      transform: translateY(-2px);
    }

    .btn-primary {
      color: #ffffff;
      background: var(--orange);
      box-shadow: 0 12px 24px rgba(241, 90, 36, 0.25);
    }

    .btn-primary:hover {
      background: var(--orange-dark);
      box-shadow: 0 15px 28px rgba(241, 90, 36, 0.32);
    }

    .btn-secondary {
      color: var(--ink);
      background: #ffffff;
      border: 1px solid var(--line);
    }

    .btn-secondary:hover {
      color: var(--whatsapp);
      border-color: var(--whatsapp);
    }

    .hero-trust {
      display: flex;
      flex-wrap: wrap;
      gap: 12px 20px;
      margin-top: 20px;
      color: #596271;
      font-size: 12px;
      font-weight: 700;
    }

    .hero-trust span {
      display: inline-flex;
      align-items: center;
      gap: 6px;
    }

    .check {
      width: 17px;
      height: 17px;
      display: inline-grid;
      place-items: center;
      color: #ffffff;
      font-size: 11px;
      background: var(--success);
      border-radius: 50%;
    }

    .product-showcase {
      position: relative;
      isolation: isolate;
    }

    .product-image-wrap {
      position: relative;
      overflow: hidden;
      min-height: 510px;
      background:
        linear-gradient(145deg, rgba(15, 18, 23, 0.05), transparent),
        #dfe2e5;
      border: 1px solid rgba(18, 20, 23, 0.08);
      border-radius: 26px;
      box-shadow: var(--shadow);
    }

    .product-image-wrap::after {
      position: absolute;
      inset: auto 0 0;
      height: 43%;
      content: "";
      background: linear-gradient(to top, rgba(7, 9, 12, 0.55), transparent);
      pointer-events: none;
    }

    .product-image-wrap img {
      width: 100%;
      height: 100%;
      min-height: 510px;
      object-fit: cover;
      object-position: center;
    }

    .product-caption {
      position: absolute;
      right: 18px;
      bottom: 18px;
      left: 18px;
      z-index: 2;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 14px;
      padding: 14px 15px;
      color: #ffffff;
      background: rgba(10, 12, 15, 0.71);
      border: 1px solid rgba(255, 255, 255, 0.16);
      border-radius: 13px;
      backdrop-filter: blur(10px);
    }

    .product-caption strong {
      display: block;
      margin-bottom: 3px;
      font-size: 13px;
    }

    .product-caption span {
      color: #d6dbe0;
      font-size: 11px;
    }

    .product-caption-badge {
      flex: 0 0 auto;
      padding: 7px 9px;
      color: #ffffff;
      font-size: 10px;
      font-weight: 800;
      letter-spacing: 0.05em;
      background: var(--orange);
      border-radius: 7px;
    }

    .float-card {
      position: absolute;
      z-index: 3;
      display: flex;
      align-items: center;
      gap: 9px;
      padding: 12px 14px;
      color: var(--ink);
      font-size: 12px;
      font-weight: 800;
      background: #ffffff;
      border: 1px solid var(--line);
      border-radius: 13px;
      box-shadow: var(--shadow-soft);
    }

    .float-card strong {
      display: block;
      font-size: 13px;
    }

    .float-card small {
      display: block;
      margin-top: 2px;
      color: var(--muted);
      font-size: 10px;
      font-weight: 600;
    }

    .float-card.one {
      top: 22px;
      left: -20px;
    }

    .float-card.two {
      right: -14px;
      bottom: 82px;
    }

    .icon-box {
      width: 34px;
      height: 34px;
      display: grid;
      flex: 0 0 auto;
      place-items: center;
      color: var(--orange);
      font-size: 19px;
      background: var(--orange-light);
      border-radius: 9px;
    }

    .quick-benefits {
      padding: 23px 0;
      background: var(--ink);
    }

    .quick-benefits-grid {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 0;
    }

    .quick-benefit {
      min-height: 74px;
      display: flex;
      align-items: center;
      gap: 12px;
      padding: 6px 24px;
      color: #ffffff;
      border-right: 1px solid rgba(255, 255, 255, 0.12);
    }

    .quick-benefit:last-child {
      border-right: 0;
    }

    .quick-icon {
      width: 39px;
      height: 39px;
      display: grid;
      flex: 0 0 auto;
      place-items: center;
      color: var(--orange);
      font-size: 21px;
      background: rgba(241, 90, 36, 0.14);
      border-radius: 10px;
    }

    .quick-benefit strong {
      display: block;
      margin-bottom: 3px;
      font-size: 13px;
    }

    .quick-benefit span {
      display: block;
      color: #b7bec8;
      font-size: 11px;
      line-height: 1.35;
    }

    .section {
      padding: 78px 0;
    }

    .section-soft {
      background: var(--paper);
    }

    .section-heading {
      max-width: 740px;
      margin: 0 auto 38px;
      text-align: center;
    }

    .section-kicker {
      margin-bottom: 9px;
      color: var(--orange);
      font-size: 11px;
      font-weight: 800;
      letter-spacing: 0.11em;
      text-transform: uppercase;
    }

    .section-heading h2 {
      margin-bottom: 12px;
      font-family: "Barlow Condensed", Impact, sans-serif;
      font-size: clamp(36px, 5vw, 54px);
      font-style: italic;
      font-weight: 800;
      line-height: 0.95;
      letter-spacing: -0.02em;
      text-transform: uppercase;
    }

    .section-heading p {
      margin: 0;
      color: var(--muted);
      font-size: 15px;
      line-height: 1.65;
    }

    .problems-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 18px;
    }

    .problem-card {
      display: grid;
      grid-template-columns: 42px 1fr;
      gap: 14px;
      padding: 22px;
      background: #ffffff;
      border: 1px solid var(--line);
      border-radius: 16px;
      box-shadow: 0 6px 18px rgba(18, 20, 23, 0.035);
    }

    .problem-number {
      width: 35px;
      height: 35px;
      display: grid;
      place-items: center;
      color: var(--orange);
      font-family: "Barlow Condensed", sans-serif;
      font-size: 19px;
      font-weight: 800;
      background: var(--orange-light);
      border-radius: 9px;
    }

    .problem-card h3 {
      margin-bottom: 7px;
      font-size: 16px;
      line-height: 1.25;
    }

    .problem-card p {
      margin: 0;
      color: var(--muted);
      font-size: 13px;
      line-height: 1.55;
    }

    .solution-line {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      margin-top: 11px;
      color: var(--success);
      font-size: 12px;
      font-weight: 800;
    }

    .features-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 18px;
    }

    .feature-card {
      padding: 25px 22px;
      background: #ffffff;
      border: 1px solid var(--line);
      border-radius: var(--radius);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    .feature-card:hover {
      transform: translateY(-5px);
      box-shadow: var(--shadow-soft);
    }

    .feature-icon {
      width: 49px;
      height: 49px;
      display: grid;
      place-items: center;
      margin-bottom: 18px;
      color: var(--orange);
      font-size: 25px;
      background: var(--orange-light);
      border-radius: 13px;
    }

    .feature-card h3 {
      margin-bottom: 9px;
      font-size: 17px;
    }

    .feature-card p {
      margin-bottom: 0;
      color: var(--muted);
      font-size: 13px;
      line-height: 1.65;
    }

    .kit-grid {
      display: grid;
      grid-template-columns: 1.05fr 0.95fr;
      gap: 45px;
      align-items: center;
    }

    .kit-image {
      position: relative;
      overflow: hidden;
      min-height: 440px;
      background: #e3e5e7;
      border-radius: 22px;
      box-shadow: var(--shadow-soft);
    }

    .kit-image img {
      width: 100%;
      height: 100%;
      min-height: 440px;
      object-fit: cover;
      object-position: center;
    }

    .kit-copy h2 {
      margin-bottom: 15px;
      font-family: "Barlow Condensed", Impact, sans-serif;
      font-size: clamp(38px, 4.5vw, 56px);
      font-style: italic;
      font-weight: 800;
      line-height: 0.93;
      text-transform: uppercase;
    }

    .kit-copy > p {
      max-width: 510px;
      color: var(--muted);
      font-size: 15px;
      line-height: 1.65;
    }

    .kit-list {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 10px;
      margin: 24px 0;
      padding: 0;
      list-style: none;
    }

    .kit-list li {
      display: flex;
      align-items: flex-start;
      gap: 9px;
      padding: 12px;
      color: #36404e;
      font-size: 13px;
      font-weight: 700;
      background: var(--paper);
      border-radius: 10px;
    }

    .kit-list i {
      width: 18px;
      height: 18px;
      display: inline-grid;
      flex: 0 0 auto;
      place-items: center;
      color: #ffffff;
      font-size: 11px;
      font-style: normal;
      background: var(--success);
      border-radius: 50%;
    }

    .video-card {
      position: relative;
      overflow: hidden;
      max-width: 820px;
      margin: 0 auto;
      background: #121417;
      border-radius: 22px;
      box-shadow: var(--shadow);
    }

    .video-card video {
      width: 100%;
      max-height: 520px;
      object-fit: cover;
      background: #20242a;
    }

    .video-placeholder {
      min-height: 400px;
      display: grid;
      place-items: center;
      padding: 30px;
      color: #ffffff;
      text-align: center;
      background:
        linear-gradient(0deg, rgba(0, 0, 0, 0.52), rgba(0, 0, 0, 0.06)),
        url("IMG_2881.jpg") center / cover no-repeat;
    }

    .play-circle {
      width: 72px;
      height: 72px;
      display: grid;
      place-items: center;
      margin: 0 auto 16px;
      color: #ffffff;
      font-size: 24px;
      background: var(--orange);
      border: 7px solid rgba(255, 255, 255, 0.2);
      border-radius: 50%;
      box-shadow: 0 12px 25px rgba(0, 0, 0, 0.25);
    }

    .video-placeholder strong {
      display: block;
      margin-bottom: 7px;
      font-size: 20px;
    }

    .video-placeholder span {
      color: #e0e4e8;
      font-size: 13px;
    }

    .cta-band {
      position: relative;
      overflow: hidden;
      padding: 64px 0;
      color: #ffffff;
      background:
        radial-gradient(circle at 90% 25%, rgba(241, 90, 36, 0.65), transparent 30%),
        #16191e;
    }

    .cta-inner {
      display: grid;
      grid-template-columns: 1fr auto;
      gap: 28px;
      align-items: center;
    }

    .cta-band h2 {
      max-width: 670px;
      margin-bottom: 10px;
      font-family: "Barlow Condensed", Impact, sans-serif;
      font-size: clamp(40px, 5vw, 62px);
      font-style: italic;
      font-weight: 800;
      line-height: 0.9;
      text-transform: uppercase;
    }

    .cta-band p {
      max-width: 640px;
      margin: 0;
      color: #c9cfd7;
      font-size: 15px;
      line-height: 1.6;
    }

    .cta-price {
      margin-bottom: 15px;
      color: #ffffff;
      font-family: "Barlow Condensed", sans-serif;
      font-size: 53px;
      font-weight: 800;
      letter-spacing: -0.04em;
      text-align: center;
    }

    .cta-price span {
      display: block;
      margin-bottom: 5px;
      color: #cfd4db;
      font-family: "Inter", sans-serif;
      font-size: 12px;
      font-weight: 700;
      letter-spacing: 0;
    }

    .faq-list {
      max-width: 820px;
      margin: 0 auto;
    }

    .faq-item {
      overflow: hidden;
      margin-bottom: 11px;
      background: #ffffff;
      border: 1px solid var(--line);
      border-radius: 13px;
    }

    .faq-question {
      width: 100%;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 18px;
      padding: 18px 19px;
      color: var(--ink);
      font-size: 15px;
      font-weight: 800;
      text-align: left;
      background: #ffffff;
      border: 0;
    }

    .faq-question span:last-child {
      color: var(--orange);
      font-size: 25px;
      font-weight: 400;
      transition: transform 0.2s ease;
    }

    .faq-answer {
      max-height: 0;
      overflow: hidden;
      padding: 0 19px;
      color: var(--muted);
      font-size: 14px;
      line-height: 1.65;
      transition: max-height 0.25s ease, padding 0.25s ease;
    }

    .faq-item.active .faq-answer {
      max-height: 230px;
      padding: 0 19px 18px;
    }

    .faq-item.active .faq-question span:last-child {
      transform: rotate(45deg);
    }

    .footer {
      padding: 34px 0 106px;
      color: #a6aeb9;
      background: #101215;
    }

    .footer-inner {
      display: flex;
      justify-content: space-between;
      gap: 20px;
      align-items: center;
      flex-wrap: wrap;
    }

    .footer strong {
      color: #ffffff;
      font-size: 14px;
    }

    .footer p {
      max-width: 650px;
      margin: 7px 0 0;
      font-size: 11px;
      line-height: 1.55;
    }

    .footer-copy {
      color: #7f8996;
      font-size: 11px;
    }

    .whatsapp-float {
      position: fixed;
      right: 20px;
      bottom: 22px;
      z-index: 30;
      min-height: 51px;
      display: inline-flex;
      align-items: center;
      gap: 9px;
      padding: 0 16px;
      color: #ffffff;
      font-size: 13px;
      font-weight: 800;
      background: var(--whatsapp);
      border-radius: 999px;
      box-shadow: 0 12px 28px rgba(31, 168, 85, 0.32);
      transition: transform 0.2s ease;
    }

    .whatsapp-float:hover {
      transform: translateY(-3px);
    }

    .wa-icon {
      width: 22px;
      height: 22px;
      display: grid;
      place-items: center;
      color: var(--whatsapp);
      font-size: 12px;
      background: #ffffff;
      border-radius: 50%;
    }

    .mobile-buy-bar {
      position: fixed;
      right: 0;
      bottom: 0;
      left: 0;
      z-index: 35;
      display: none;
      align-items: center;
      justify-content: space-between;
      gap: 10px;
      padding: 10px 16px calc(10px + env(safe-area-inset-bottom));
      background: rgba(255, 255, 255, 0.97);
      border-top: 1px solid var(--line);
      box-shadow: 0 -10px 28px rgba(18, 20, 23, 0.11);
      backdrop-filter: blur(12px);
    }

    .mobile-buy-bar small {
      display: block;
      color: var(--muted);
      font-size: 10px;
      font-weight: 700;
    }

    .mobile-buy-bar strong {
      color: var(--ink);
      font-size: 20px;
      letter-spacing: -0.03em;
    }

    .mobile-buy-bar button {
      min-height: 45px;
      padding: 0 17px;
      color: #ffffff;
      font-size: 13px;
      font-weight: 800;
      background: var(--orange);
      border: 0;
      border-radius: 10px;
    }

    .modal {
      position: fixed;
      inset: 0;
      z-index: 100;
      display: none;
      align-items: center;
      justify-content: center;
      padding: 16px;
    }

    .modal.active {
      display: flex;
    }

    .modal-backdrop {
      position: absolute;
      inset: 0;
      background: rgba(9, 11, 14, 0.72);
      backdrop-filter: blur(4px);
    }

    .modal-dialog {
      position: relative;
      z-index: 2;
      width: min(100%, 560px);
      max-height: min(760px, calc(100vh - 32px));
      overflow-y: auto;
      padding: 25px;
      background: #ffffff;
      border-radius: 20px;
      box-shadow: 0 25px 80px rgba(0, 0, 0, 0.35);
    }

    .modal-close {
      position: absolute;
      top: 13px;
      right: 13px;
      width: 34px;
      height: 34px;
      display: grid;
      place-items: center;
      color: #4e5866;
      font-size: 24px;
      line-height: 1;
      background: #f2f4f6;
      border: 0;
      border-radius: 50%;
    }

    .modal-product {
      display: flex;
      gap: 13px;
      align-items: center;
      padding: 13px;
      margin-bottom: 21px;
      background: var(--paper);
      border-radius: 13px;
    }

    .modal-product img {
      width: 75px;
      height: 75px;
      object-fit: cover;
      border-radius: 10px;
    }

    .modal-product span {
      display: block;
      margin-bottom: 4px;
      color: var(--muted);
      font-size: 11px;
      font-weight: 700;
    }

    .modal-product h3 {
      margin-bottom: 5px;
      font-size: 15px;
    }

    .modal-product strong {
      color: var(--orange);
      font-size: 19px;
    }

    .modal-dialog h2 {
      margin-bottom: 7px;
      font-family: "Barlow Condensed", sans-serif;
      font-size: 35px;
      font-style: italic;
      font-weight: 800;
      line-height: 0.95;
      text-transform: uppercase;
    }

    .modal-intro {
      margin-bottom: 19px;
      color: var(--muted);
      font-size: 13px;
      line-height: 1.55;
    }

    .form-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 12px;
    }

    .form-group {
      margin-bottom: 12px;
    }

    .form-group.full {
      grid-column: 1 / -1;
    }

    .form-group label {
      display: block;
      margin-bottom: 6px;
      color: #394351;
      font-size: 12px;
      font-weight: 800;
    }

    .form-group input,
    .form-group select,
    .form-group textarea {
      width: 100%;
      min-height: 47px;
      padding: 11px 12px;
      color: var(--ink);
      font-size: 14px;
      outline: none;
      background: #ffffff;
      border: 1px solid #dce0e5;
      border-radius: 10px;
      transition: border 0.2s ease, box-shadow 0.2s ease;
    }

    .form-group textarea {
      min-height: 74px;
      resize: vertical;
    }

    .form-group input:focus,
    .form-group select:focus,
    .form-group textarea:focus {
      border-color: var(--orange);
      box-shadow: 0 0 0 3px rgba(241, 90, 36, 0.12);
    }

    .quantity-row {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 15px;
      padding: 13px;
      margin: 4px 0 16px;
      background: var(--paper);
      border-radius: 11px;
    }

    .quantity-row p {
      margin: 0;
      color: #424b58;
      font-size: 12px;
      font-weight: 800;
    }

    .quantity-control {
      display: inline-flex;
      align-items: center;
      overflow: hidden;
      background: #ffffff;
      border: 1px solid var(--line);
      border-radius: 9px;
    }

    .quantity-control button {
      width: 34px;
      height: 34px;
      color: var(--ink);
      font-size: 19px;
      background: #ffffff;
      border: 0;
    }

    .quantity-control input {
      width: 32px;
      height: 34px;
      padding: 0;
      font-size: 13px;
      font-weight: 800;
      text-align: center;
      background: transparent;
      border: 0;
      outline: 0;
    }

    .order-total {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 15px;
      padding: 15px 0;
      margin-bottom: 15px;
      border-top: 1px solid var(--line);
      border-bottom: 1px solid var(--line);
    }

    .order-total span {
      color: var(--muted);
      font-size: 13px;
      font-weight: 700;
    }

    .order-total strong {
      color: var(--orange);
      font-size: 25px;
      letter-spacing: -0.04em;
    }

    .form-submit {
      width: 100%;
      min-height: 54px;
      color: #ffffff;
      font-size: 15px;
      font-weight: 800;
      background: var(--orange);
      border: 0;
      border-radius: 11px;
      box-shadow: 0 10px 20px rgba(241, 90, 36, 0.22);
    }

    .form-note {
      margin: 13px 0 0;
      color: var(--muted);
      font-size: 10px;
      line-height: 1.55;
      text-align: center;
    }

    .success-box {
      padding: 15px;
      margin-top: 15px;
      color: #126e39;
      font-size: 13px;
      font-weight: 700;
      line-height: 1.5;
      background: #eaf8ef;
      border: 1px solid #c6ead3;
      border-radius: 11px;
    }

    @media (max-width: 900px) {
      .hero-grid,
      .kit-grid {
        grid-template-columns: 1fr;
      }

      .hero-content {
        order: 2;
      }

      .product-showcase {
        order: 1;
      }

      .product-image-wrap,
      .product-image-wrap img {
        min-height: 440px;
      }

      .float-card.one {
        left: 13px;
      }

      .float-card.two {
        right: 13px;
      }

      .quick-benefits-grid {
        grid-template-columns: repeat(2, 1fr);
        gap: 16px 0;
      }

      .quick-benefit:nth-child(2) {
        border-right: 0;
      }

      .cta-inner {
        grid-template-columns: 1fr;
        text-align: center;
      }

      .cta-price {
        text-align: left;
      }
    }

    @media (max-width: 650px) {
      .topbar {
        padding: 8px 12px;
        font-size: 10px;
      }

      .topbar-inner {
        gap: 8px 12px;
      }

      .header-inner {
        min-height: 61px;
      }

      .header-action {
        min-height: 38px;
        padding: 0 11px;
        font-size: 11px;
      }

      .hero {
        padding: 18px 0 37px;
      }

      .hero-grid {
        gap: 27px;
      }

      .product-image-wrap,
      .product-image-wrap img {
        min-height: 385px;
      }

      .product-caption {
        right: 12px;
        bottom: 12px;
        left: 12px;
        padding: 11px;
      }

      .float-card {
        padding: 9px 10px;
      }

      .float-card.two {
        display: none;
      }

      h1 {
        margin-top: 13px;
      }

      .hero-copy {
        font-size: 14px;
      }

      .hero-actions .btn {
        width: 100%;
      }

      .hero-trust {
        gap: 9px 14px;
      }

      .quick-benefits {
        padding: 18px 0;
      }

      .quick-benefits-grid {
        grid-template-columns: 1fr;
        gap: 6px;
      }

      .quick-benefit,
      .quick-benefit:nth-child(2) {
        min-height: auto;
        padding: 8px 2px;
        border-right: 0;
      }

      .section {
        padding: 57px 0;
      }

      .section-heading {
        margin-bottom: 27px;
      }

      .problems-grid,
      .features-grid {
        grid-template-columns: 1fr;
      }

      .kit-list {
        grid-template-columns: 1fr;
      }

      .kit-image,
      .kit-image img {
        min-height: 320px;
      }

      .video-placeholder {
        min-height: 320px;
      }

      .cta-band {
        padding: 49px 0;
      }

      .cta-price {
        text-align: center;
      }

      .whatsapp-float {
        right: 15px;
        bottom: 77px;
        min-height: 46px;
        padding: 0 14px;
        font-size: 12px;
      }

      .mobile-buy-bar {
        display: flex;
      }

      .footer {
        padding-bottom: 96px;
      }

      .form-grid {
        grid-template-columns: 1fr;
      }

      .modal-dialog {
        padding: 20px 16px;
      }

      .modal-product {
        padding: 10px;
      }
    }
  </style>
</head>

<body>

  <!--
    ========================================================
    CAMBIAR ANTES DE PUBLICAR:
    1. Número WhatsApp en JavaScript: 573001234567
    2. Precio actual: 149900
    3. Precio anterior: 249900
    4. Reemplaza IMG_2881.jpg e IMG_2880.jpg por tus fotos.
    ========================================================
  -->

  <div class="topbar">
    <div class="topbar-inner">
      <span class="topbar-item"><i class="topbar-dot"></i> Envíos a toda Colombia</span>
      <span class="topbar-item"><i class="topbar-dot"></i> Pago contra entrega según cobertura</span>
      <span class="topbar-item"><i class="topbar-dot"></i> Atención por WhatsApp</span>
    </div>
  </div>

  <header class="site-header" id="siteHeader">
    <div class="container header-inner">
      <a class="brand" href="#inicio" aria-label="Inicio">
        <span class="brand-mark">H</span>
        <span>
          <small>Soluciones para el hogar</small>
          <span class="brand-name">Hogar Pro Colombia</span>
        </span>
      </a>

      <button class="header-action" type="button" onclick="openOrderModal()">
        Pedir ahora
      </button>
    </div>
  </header>

  <main>

    <section class="hero" id="inicio">
      <div class="container hero-grid">

        <div class="hero-content">
          <div class="eyebrow"><span></span> Portátil · inalámbrica · práctica</div>

          <h1>
            Hidrolavadora<br>
            inalámbrica <em>48V</em>
          </h1>

          <p class="hero-copy">
            Limpia la moto, el carro, el patio y más sin depender de una toma corriente cerca. Compacta, fácil de usar y lista para las tareas del día a día.
          </p>

          <div class="rating">
            <span class="stars">★★★★★</span>
            <span>Una solución práctica para limpieza en casa</span>
          </div>

          <div class="hero-price">
            <div>
              <div class="old-price">Antes: <s id="oldPriceHero">$249.900</s></div>
              <div class="price-big" id="priceHero">$149.900</div>
            </div>
            <span class="price-tag">OFERTA ESPECIAL</span>
          </div>

          <div class="hero-actions">
            <button class="btn btn-primary" type="button" onclick="openOrderModal()">
              Pedir ahora · pago al recibir
            </button>

            <a class="btn btn-secondary" id="heroWhatsapp" href="#" target="_blank" rel="noopener">
              <span>◉</span> Resolver dudas por WhatsApp
            </a>
          </div>

          <div class="hero-trust">
            <span><i class="check">✓</i> Doble batería incluida</span>
            <span><i class="check">✓</i> Boquilla 6 en 1</span>
            <span><i class="check">✓</i> Envío nacional</span>
          </div>
        </div>

        <div class="product-showcase">
          <div class="float-card one">
            <div class="icon-box">⚡</div>
            <div>
              <strong>Sin cables</strong>
              <small>Úsala donde la necesites</small>
            </div>
          </div>

          <div class="product-image-wrap">
            <!-- Cambia IMG_2881.jpg por la foto principal real de tu producto -->
            <img
              src="IMG_2881.jpg"
              alt="Hidrolavadora inalámbrica 48V para limpieza de motos y carros"
              width="720"
              height="920"
              fetchpriority="high"
            >

            <div class="product-caption">
              <div>
                <strong>Potencia portátil para tu día a día</strong>
                <span>Ideal para moto, carro, patio, bicicleta y más.</span>
              </div>
              <span class="product-caption-badge">48V</span>
            </div>
          </div>

          <div class="float-card two">
            <div class="icon-box">🔋</div>
            <div>
              <strong>2 baterías</strong>
              <small>Una trabaja y otra respalda</small>
            </div>
          </div>
        </div>

      </div>
    </section>

    <section class="quick-benefits">
      <div class="container quick-benefits-grid">
        <div class="quick-benefit">
          <div class="quick-icon">⚡</div>
          <div>
            <strong>Sin cables</strong>
            <span>Más libertad para limpiar.</span>
          </div>
        </div>

        <div class="quick-benefit">
          <div class="quick-icon">🔋</div>
          <div>
            <strong>Doble batería</strong>
            <span>Respaldo para seguir trabajando.</span>
          </div>
        </div>

        <div class="quick-benefit">
          <div class="quick-icon">💧</div>
          <div>
            <strong>Uso con balde</strong>
            <span>Puede tomar agua de varias fuentes.</span>
          </div>
        </div>

        <div class="quick-benefit">
          <div class="quick-icon">🧰</div>
          <div>
            <strong>Kit completo</strong>
            <span>Accesorios para empezar a usarla.</span>
          </div>
        </div>
      </div>
    </section>

    <section class="section section-soft" id="problemas">
      <div class="container">
        <div class="section-heading">
          <div class="section-kicker">Hecha para la vida real</div>
          <h2>Menos esfuerzo. Más tiempo para ti.</h2>
          <p>
            Una limpieza más práctica para esas tareas que normalmente toman tiempo, agua y mucho esfuerzo.
          </p>
        </div>

        <div class="problems-grid">
          <article class="problem-card">
            <div class="problem-number">01</div>
            <div>
              <h3>La moto o el carro se ensucian y lavarlos toma demasiado tiempo.</h3>
              <p>La suciedad de las llantas, el barro y el polvo se acumulan rápido, especialmente cuando usas el vehículo todos los días.</p>
              <span class="solution-line">✓ Limpieza más práctica con chorro dirigido</span>
            </div>
          </article>

          <article class="problem-card">
            <div class="problem-number">02</div>
            <div>
              <h3>No siempre tienes una llave o toma corriente cerca.</h3>
              <p>En parqueaderos, patios, fincas o zonas exteriores puede ser difícil conectar una hidrolavadora tradicional.</p>
              <span class="solution-line">✓ Diseño portátil y funcionamiento inalámbrico</span>
            </div>
          </article>

          <article class="problem-card">
            <div class="problem-number">03</div>
            <div>
              <h3>Una batería se puede descargar cuando todavía falta limpiar.</h3>
              <p>Quedarse a medias es incómodo cuando estás lavando más de una moto, el carro o varias zonas del patio.</p>
              <span class="solution-line">✓ Dos baterías para tener respaldo</span>
            </div>
          </article>

          <article class="problem-card">
            <div class="problem-number">04</div>
            <div>
              <h3>Las máquinas grandes ocupan espacio y son difíciles de mover.</h3>
              <p>Muchas personas necesitan una alternativa sencilla de guardar y transportar sin llenar media bodega.</p>
              <span class="solution-line">✓ Compacta, liviana y fácil de guardar</span>
            </div>
          </article>
        </div>
      </div>
    </section>

    <section class="section" id="beneficios">
      <div class="container">
        <div class="section-heading">
          <div class="section-kicker">Beneficios principales</div>
          <h2>Todo lo que necesitas para limpiar mejor</h2>
          <p>
            Diseñada para ayudarte con la limpieza de la casa, el vehículo y espacios exteriores, de una manera más cómoda.
          </p>
        </div>

        <div class="features-grid">
          <article class="feature-card">
            <div class="feature-icon">⚡</div>
            <h3>Llévala donde la necesites</h3>
            <p>No dependes de una toma corriente al lado. Úsala en el patio, garaje, parqueadero o finca.</p>
          </article>

          <article class="feature-card">
            <div class="feature-icon">🔋</div>
            <h3>Doble batería de respaldo</h3>
            <p>Mientras usas una batería, tienes otra disponible para continuar la limpieza con más tranquilidad.</p>
          </article>

          <article class="feature-card">
            <div class="feature-icon">💧</div>
            <h3>Compatible con varias fuentes de agua</h3>
            <p>La manguera de succión permite usarla con balde, recipiente, tanque o llave, según tu espacio.</p>
          </article>

          <article class="feature-card">
            <div class="feature-icon">🎯</div>
            <h3>Boquilla 6 en 1</h3>
            <p>Ajusta el tipo de chorro según la tarea: llantas, rincones, carro, moto, patio o enjuague general.</p>
          </article>

          <article class="feature-card">
            <div class="feature-icon">🧼</div>
            <h3>Depósito para jabón</h3>
            <p>Incluye recipiente para aplicar jabón o espuma durante el proceso de limpieza.</p>
          </article>

          <article class="feature-card">
            <div class="feature-icon">🧳</div>
            <h3>Fácil de guardar</h3>
            <p>Todos los accesorios pueden ir organizados en su maletín para que no ocupen demasiado espacio.</p>
          </article>
        </div>
      </div>
    </section>

    <section class="section section-soft" id="kit">
      <div class="container kit-grid">
        <div class="kit-image">
          <!-- Cambia IMG_2880.jpg por una foto real del kit completo -->
          <img
            src="IMG_2880.jpg"
            alt="Kit de hidrolavadora inalámbrica 48V con baterías y accesorios"
            width="720"
            height="850"
            loading="lazy"
          >
        </div>

        <div class="kit-copy">
          <div class="section-kicker">Kit completo</div>
          <h2>Ábrela, arma lo necesario y comienza a limpiar</h2>

          <p>
            La idea es que no tengas que comprar accesorios aparte para empezar. Recibes lo esencial para usarla en diferentes tipos de limpieza.
          </p>

          <ul class="kit-list">
            <li><i>✓</i> Hidrolavadora inalámbrica 48V</li>
            <li><i>✓</i> Dos baterías recargables</li>
            <li><i>✓</i> Cargador de batería</li>
            <li><i>✓</i> Boquilla ajustable 6 en 1</li>
            <li><i>✓</i> Manguera de succión</li>
            <li><i>✓</i> Filtro para el agua</li>
            <li><i>✓</i> Recipiente para jabón</li>
            <li><i>✓</i> Maletín para guardar el kit</li>
          </ul>

          <button class="btn btn-primary" type="button" onclick="openOrderModal()">
            Quiero pedir mi hidrolavadora
          </button>
        </div>
      </div>
    </section>

    <section class="section" id="video">
      <div class="container">
        <div class="section-heading">
          <div class="section-kicker">Mírala en acción</div>
          <h2>La diferencia se nota desde el primer uso</h2>
          <p>
            Agrega aquí un video corto de tu producto trabajando. Lo ideal es mostrar una moto, una llanta, el patio o el carro antes y después.
          </p>
        </div>

        <!--
          PARA AGREGAR TU VIDEO:
          Reemplaza todo el bloque "video-placeholder" por:

          <video controls playsinline preload="metadata" poster="portada-video.webp">
            <source src="tu-video.mp4" type="video/mp4">
            Tu navegador no puede reproducir el video.
          </video>
        -->

        <div class="video-card">
          <div class="video-placeholder">
            <div>
              <div class="play-circle">▶</div>
              <strong>Agrega aquí tu video demostrativo</strong>
              <span>Recomendado: video vertical de 8 a 15 segundos mostrando el antes y después.</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="cta-band">
      <div class="container cta-inner">
        <div>
          <h2>Tu limpieza no tiene que quitarte todo el día.</h2>
          <p>
            Pide tu hidrolavadora inalámbrica y te confirmamos por WhatsApp la disponibilidad, cobertura de envío y tiempo estimado para tu ciudad.
          </p>
        </div>

        <div>
          <div class="cta-price">
            <span>Oferta especial de hoy</span>
            <span id="priceCta">$149.900</span>
          </div>

          <button class="btn btn-primary" type="button" onclick="openOrderModal()">
            Pedir ahora
          </button>
        </div>
      </div>
    </section>

    <section class="section section-soft" id="preguntas">
      <div class="container">
        <div class="section-heading">
          <div class="section-kicker">Preguntas frecuentes</div>
          <h2>Antes de pedir, resuelve tus dudas</h2>
          <p>
            Información clara para que compres con más tranquilidad.
          </p>
        </div>

        <div class="faq-list">
          <div class="faq-item">
            <button class="faq-question" type="button">
              ¿Para qué puedo usar la hidrolavadora?
              <span>+</span>
            </button>
            <div class="faq-answer">
              Es útil para limpiezas de moto, carro, bicicleta, llantas, patios, pisos, ventanas, muebles de exterior y otras tareas similares de casa.
            </div>
          </div>

          <div class="faq-item">
            <button class="faq-question" type="button">
              ¿Puede tomar agua de un balde?
              <span>+</span>
            </button>
            <div class="faq-answer">
              Sí. Incluye manguera de succión y filtro para que puedas usarla con un balde, recipiente, tanque o una fuente de agua disponible.
            </div>
          </div>

          <div class="faq-item">
            <button class="faq-question" type="button">
              ¿Qué incluye el pedido?
              <span>+</span>
            </button>
            <div class="faq-answer">
              Incluye la hidrolavadora, dos baterías, cargador, boquilla 6 en 1, manguera, filtro, recipiente para jabón y maletín. Confirma siempre el contenido final del kit antes de despachar.
            </div>
          </div>

          <div class="faq-item">
            <button class="faq-question" type="button">
              ¿Puedo pagar cuando reciba el pedido?
              <span>+</span>
            </button>
            <div class="faq-answer">
              Sí, el pago contra entrega está disponible en ciudades y zonas con cobertura. Después de completar el formulario, se confirma por WhatsApp antes del envío.
            </div>
          </div>

          <div class="faq-item">
            <button class="faq-question" type="button">
              ¿Hacen envíos a toda Colombia?
              <span>+</span>
            </button>
            <div class="faq-answer">
              Se realizan envíos nacionales. El tiempo de entrega y la disponibilidad de pago contra entrega pueden variar según tu ciudad, municipio o zona de cobertura.
            </div>
          </div>
        </div>
      </div>
    </section>

  </main>

  <footer class="footer">
    <div class="container footer-inner">
      <div>
        <strong>Hogar Pro Colombia</strong>
        <p>
          La información, disponibilidad, cobertura de pago contra entrega, tiempos de entrega y condiciones de garantía se confirman por WhatsApp antes del despacho.
        </p>
      </div>

      <div class="footer-copy">
        © <span id="year"></span> Hogar Pro Colombia
      </div>
    </div>
  </footer>

  <a class="whatsapp-float" id="whatsappFloat" href="#" target="_blank" rel="noopener">
    <span class="wa-icon">◉</span>
    ¿Tienes dudas? Escríbenos
  </a>

  <div class="mobile-buy-bar">
    <div>
      <small>Oferta especial</small>
      <strong id="mobilePrice">$149.900</strong>
    </div>

    <button type="button" onclick="openOrderModal()">
      Pedir ahora
    </button>
  </div>

  <!-- MODAL / FORMULARIO DE PEDIDO -->
  <div class="modal" id="orderModal" aria-hidden="true">
    <div class="modal-backdrop" onclick="closeOrderModal()"></div>

    <section class="modal-dialog" role="dialog" aria-modal="true" aria-labelledby="modalTitle">
      <button class="modal-close" type="button" onclick="closeOrderModal()" aria-label="Cerrar formulario">
        ×
      </button>

      <div class="modal-product">
        <img
          src="IMG_2880.jpg"
          alt="Hidrolavadora inalámbrica 48V"
          width="100"
          height="100"
        >
        <div>
          <span>Tu pedido</span>
          <h3>Hidrolavadora inalámbrica 48V</h3>
          <strong id="modalProductPrice">$149.900</strong>
        </div>
      </div>

      <h2 id="modalTitle">Completa tus datos</h2>

      <p class="modal-intro">
        Al enviar la solicitud, te llevamos a WhatsApp con el resumen de tu pedido para confirmar disponibilidad, dirección y entrega.
      </p>

      <form id="orderForm">
        <div class="form-grid">
          <div class="form-group full">
            <label for="nombre">Nombre completo</label>
            <input id="nombre" name="nombre" type="text" placeholder="Ejemplo: María González" required>
          </div>

          <div class="form-group">
            <label for="telefono">Celular con WhatsApp</label>
            <input id="telefono" name="telefono" type="tel" inputmode="numeric" placeholder="Ejemplo: 300 123 4567" required>
          </div>

          <div class="form-group">
            <label for="ciudad">Ciudad o municipio</label>
            <input id="ciudad" name="ciudad" type="text" placeholder="Ejemplo: Bogotá" required>
          </div>

          <div class="form-group">
            <label for="departamento">Departamento</label>
            <input id="departamento" name="departamento" type="text" placeholder="Ejemplo: Cundinamarca" required>
          </div>

          <div class="form-group">
            <label for="entrega">Tipo de entrega</label>
            <select id="entrega" name="entrega" required>
              <option value="A domicilio">A domicilio</option>
              <option value="Oficina transportadora">Oficina transportadora</option>
            </select>
          </div>

          <div class="form-group full">
            <label for="direccion">Dirección completa y barrio</label>
            <input id="direccion" name="direccion" type="text" placeholder="Ejemplo: Cra 45 # 12-30, Barrio..." required>
          </div>

          <div class="form-group full">
            <label for="nota">Observación opcional</label>
            <textarea id="nota" name="nota" placeholder="Ejemplo: Llamar antes de entregar, referencia de ubicación, etc."></textarea>
          </div>
        </div>

        <div class="quantity-row">
          <p>Cantidad de unidades</p>

          <div class="quantity-control">
            <button type="button" onclick="changeQuantity(-1)" aria-label="Disminuir cantidad">−</button>
            <input id="cantidad" type="number" min="1" max="10" value="1" readonly>
            <button type="button" onclick="changeQuantity(1)" aria-label="Aumentar cantidad">+</button>
          </div>
        </div>

        <div class="order-total">
          <span>Total estimado</span>
          <strong id="totalPrice">$149.900</strong>
        </div>

        <button class="form-submit" type="submit">
          Confirmar solicitud por WhatsApp
        </button>

        <p class="form-note">
          Al enviar, se abrirá WhatsApp para confirmar tu pedido. El pago contra entrega depende de cobertura en tu ciudad. Verifica condiciones de garantía, precio y disponibilidad antes de despachar.
        </p>
      </form>

      <div id="formSuccess"></div>
    </section>
  </div>

  <script>
    /*
      =========================================================
      CONFIGURACIÓN PRINCIPAL
      =========================================================
      Reemplaza el número por tu WhatsApp real:
      Colombia: 57 + número celular
      Ejemplo: 573001234567
    */
    const WHATSAPP_NUMBER = "573001234567";

    const PRODUCT_NAME = "Hidrolavadora Inalámbrica 48V";
    const CURRENT_PRICE = 149900;
    const OLD_PRICE = 249900;

    let quantity = 1;

    function formatCOP(value) {
      return new Intl.NumberFormat("es-CO", {
        style: "currency",
        currency: "COP",
        minimumFractionDigits: 0,
        maximumFractionDigits: 0
      }).format(value);
    }

    function updatePrices() {
      document.getElementById("priceHero").textContent = formatCOP(CURRENT_PRICE);
      document.getElementById("priceCta").textContent = formatCOP(CURRENT_PRICE);
      document.getElementById("mobilePrice").textContent = formatCOP(CURRENT_PRICE);
      document.getElementById("modalProductPrice").textContent = formatCOP(CURRENT_PRICE);
      document.getElementById("oldPriceHero").textContent = formatCOP(OLD_PRICE);
      updateTotal();
    }

    function updateTotal() {
      const total = CURRENT_PRICE * quantity;
      document.getElementById("cantidad").value = quantity;
      document.getElementById("totalPrice").textContent = formatCOP(total);
    }

    function changeQuantity(value) {
      quantity += value;

      if (quantity < 1) quantity = 1;
      if (quantity > 10) quantity = 10;

      updateTotal();
    }

    function openOrderModal() {
      const modal = document.getElementById("orderModal");
      modal.classList.add("active");
      modal.setAttribute("aria-hidden", "false");
      document.body.classList.add("modal-open");

      setTimeout(() => {
        document.getElementById("nombre").focus();
      }, 150);
    }

    function closeOrderModal() {
      const modal = document.getElementById("orderModal");
      modal.classList.remove("active");
      modal.setAttribute("aria-hidden", "true");
      document.body.classList.remove("modal-open");
    }

    function openWhatsApp(message) {
      const url = `https://wa.me/${WHATSAPP_NUMBER}?text=${encodeURIComponent(message)}`;
      window.open(url, "_blank", "noopener");
    }

    function setWhatsAppLinks() {
      const genericMessage = `Hola, quiero información sobre la ${PRODUCT_NAME}. Vi la oferta de ${formatCOP(CURRENT_PRICE)} y quiero conocer disponibilidad, cobertura y tiempo de entrega para mi ciudad.`;

      document.getElementById("heroWhatsapp").href =
        `https://wa.me/${WHATSAPP_NUMBER}?text=${encodeURIComponent(genericMessage)}`;

      document.getElementById("whatsappFloat").href =
        `https://wa.me/${WHATSAPP_NUMBER}?text=${encodeURIComponent(genericMessage)}`;
    }

    document.getElementById("orderForm").addEventListener("submit", function(event) {
      event.preventDefault();

      const nombre = document.getElementById("nombre").value.trim();
      const telefono = document.getElementById("telefono").value.trim();
      const ciudad = document.getElementById("ciudad").value.trim();
      const departamento = document.getElementById("departamento").value.trim();
      const entrega = document.getElementById("entrega").value;
      const direccion = document.getElementById("direccion").value.trim();
      const nota = document.getElementById("nota").value.trim();

      const total = CURRENT_PRICE * quantity;

      const message = [
        "Hola, quiero confirmar mi solicitud de pedido.",
        "",
        `Producto: ${PRODUCT_NAME}`,
        `Cantidad: ${quantity}`,
        `Valor estimado: ${formatCOP(total)}`,
        "",
        "DATOS DEL CLIENTE",
        `Nombre: ${nombre}`,
        `Celular: ${telefono}`,
        `Ciudad: ${ciudad}`,
        `Departamento: ${departamento}`,
        `Entrega: ${entrega}`,
        `Dirección: ${direccion}`,
        nota ? `Observación: ${nota}` : "",
        "",
        "Quedo atento(a) a la confirmación de disponibilidad, cobertura de pago contra entrega y tiempo de entrega."
      ].filter(Boolean).join("\n");

      document.getElementById("formSuccess").innerHTML = `
        <div class="success-box">
          ✓ Solicitud preparada. En unos segundos se abrirá WhatsApp para que confirmes el pedido directamente con nuestro equipo.
        </div>
      `;

      setTimeout(() => {
        openWhatsApp(message);
      }, 500);
    });

    document.querySelectorAll(".faq-question").forEach((button) => {
      button.addEventListener("click", () => {
        const currentItem = button.parentElement;

        document.querySelectorAll(".faq-item").forEach((item) => {
          if (item !== currentItem) {
            item.classList.remove("active");
          }
        });

        currentItem.classList.toggle("active");
      });
    });

    window.addEventListener("scroll", () => {
      const header = document.getElementById("siteHeader");
      header.classList.toggle("scrolled", window.scrollY > 15);
    }, { passive: true });

    document.addEventListener("keydown", (event) => {
      if (event.key === "Escape") {
        closeOrderModal();
      }
    });

    document.getElementById("year").textContent = new Date().getFullYear();

    updatePrices();
    setWhatsAppLinks();
  </script>

</body>
</html>
