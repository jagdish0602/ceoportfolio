<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta name="color-scheme" content="dark">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Bhavana Rajpurohit — Founder. Builder. Problem Solver.</title>
  <meta name="description"
    content="Bhavana Rajpurohit, founder of Redes Creation Private Limited. Technology, SaaS, ERP, higher education systems and business automation.">
  <meta property="og:title" content="Bhavana Rajpurohit — Founder Portfolio">
  <meta property="og:description" content="I build businesses. I build technology. I solve problems.">
  <meta property="og:type" content="website">
  <link rel="icon"
    href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 32 32'%3E%3Crect width='32' height='32' rx='8' fill='%230B0B0B'/%3E%3Cpath d='M18 4 8 18h7l-2 10 11-15h-7z' fill='%232563FF'/%3E%3C/svg%3E">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cabin:ital,wght@0,400..700;1,400..700&family=Source+Code+Pro:ital,wght@0,200..900;1,200..900&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #05070D;         /* Paper */
      --bg2: #0B1020;        /* Stone */
      --card: #0E1424;       /* Clean Paper card */
      --coral: #4D8DFF;      /* Coral Accent & Button color */
      --black: #F4F7FF;      /* Pure Black */
      --tx: #F4F7FF;         /* Primary text */
      --mu: #9BA6BC;         /* Muted text for readability */
      --r: 28px
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0
    }

    html {
      scroll-behavior: auto
    }

    body {
      background: var(--bg);
      color: var(--tx);
      font: 400 17px/1.6 'Cabin', sans-serif;
      -webkit-font-smoothing: antialiased;
      overflow-x: hidden
    }

    @media(hover:hover) and (pointer:fine) {

      body.cur,
      body.cur a,
      body.cur button,
      body.cur summary {
        cursor: none
      }
    }

    a {
      color: inherit;
      text-decoration: none
    }

    ul {
      list-style: none
    }

    button {
      font: inherit;
      color: inherit;
      background: none;
      border: 0
    }

    :focus-visible {
      outline: 2px solid var(--coral);
      outline-offset: 4px
    }

    h1,
    h2,
    h3,
    .d {
      font-family: 'Cabin', sans-serif;
      font-weight: 400;
      text-transform: uppercase;
      line-height: .95;
      letter-spacing: -.02em
    }

    h2 {
      font-size: clamp(34px, 6.4vw, 104px)
    }

    .sg {
      font-family: 'Cabin', sans-serif
    }

    .lab {
      font: 500 14px 'Cabin', sans-serif;
      color: var(--coral);
      margin-bottom: 22px;
      display: block
    }

    .sec {
      padding: clamp(70px, 11vw, 160px) clamp(20px, 5vw, 72px);
      position: relative
    }

    .panel {
      margin: 0 clamp(8px, 1.4vw, 20px);
      border-radius: var(--r);
      background: var(--bg2);
      overflow: hidden
    }

    .mu {
      color: var(--mu)
    }

    /* All buttons strictly use Coral color (#2563FF) */
    .btn,
    .btn.l,
    .btn.g {
      display: inline-flex;
      align-items: center;
      gap: 10px;
      padding: 14px 28px;
      border-radius: 999px;
      background: var(--coral) !important;
      color: #FFFFFF !important;
      border: 1px solid var(--coral) !important;
      font: 600 15px 'Cabin', sans-serif;
      box-shadow: 0 4px 18px rgba(37, 99, 255, 0.28);
      will-change: transform;
      transition: transform .25s ease, box-shadow .25s ease, opacity .25s ease;
      cursor: pointer;
    }

    .btn:hover,
    .btn.l:hover,
    .btn.g:hover {
      background: var(--coral) !important;
      color: #FFFFFF !important;
      transform: translateY(-2px);
      box-shadow: 0 8px 25px rgba(37, 99, 255, 0.42);
      opacity: 0.94;
    }

    /* reveal elements fallback */
    .rv {
      opacity: 1;
      transform: none;
      transition: opacity .8s ease, transform .8s ease;
    }

    #pg {
      position: fixed;
      left: 0;
      top: 0;
      height: 3px;
      width: 100%;
      background: var(--coral);
      transform: scaleX(0);
      transform-origin: 0;
      z-index: 90
    }

    #cu {
      position: fixed;
      left: 0;
      top: 0;
      width: 14px;
      height: 14px;
      margin: -7px;
      border-radius: 50%;
      background: var(--coral);
      mix-blend-mode: multiply;
      pointer-events: none;
      z-index: 95;
      transition: width .25s, height .25s, margin .25s;
      display: none
    }

    #cu.b {
      width: 56px;
      height: 56px;
      margin: -28px;
      background: rgba(37, 99, 255, 0.25);
      border: 1px solid var(--coral);
    }

    /* nav */
    nav.top {
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      z-index: 50;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 18px clamp(20px, 3vw, 44px)
    }

    .logo {
      display: inline-flex;
      align-items: center;
      gap: 2px;
      font: 400 20px 'Cabin', sans-serif;
      letter-spacing: 1.5px;
      color: var(--black);
      background: rgba(11, 16, 32, 0.85);
      border: 1px solid rgba(255, 255, 255, 0.08);
      backdrop-filter: blur(14px);
      padding: 10px 24px;
      border-radius: 999px;
      box-shadow: 0 4px 16px rgba(0, 0, 0, 0.04);
      transition: background 0.25s ease, border-color 0.25s ease;
    }

    .logo:hover {
      background: rgba(5, 7, 13, 0.95);
      border-color: rgba(37, 99, 255, 0.35);
    }

    .logo b {
      color: var(--coral);
      margin: 0 1px;
    }

    .nl {
      display: flex;
      gap: 30px;
      font: 500 14px 'Cabin', sans-serif;
      background: rgba(11, 16, 32, 0.85);
      border: 1px solid rgba(255, 255, 255, 0.08);
      backdrop-filter: blur(14px);
      padding: 12px 28px;
      border-radius: 999px;
      color: var(--black);
    }

    .nl a {
      color: var(--black);
      transition: color .2s
    }

    .nl a:hover {
      color: var(--coral)
    }

    .bg {
      display: none;
      width: 46px;
      height: 46px;
      border-radius: 50%;
      background: rgba(255, 255, 255, .05);
      border: 1px solid rgba(255, 255, 255, .15);
      flex-direction: column;
      justify-content: center;
      gap: 6px;
      padding: 0 13px
    }

    .bg i {
      height: 2px;
      background: var(--black);
      transition: transform .4s
    }

    .mm {
      position: fixed;
      inset: 0;
      background: rgba(5, 7, 13, 0.98);
      color: var(--black);
      z-index: 45;
      display: flex;
      flex-direction: column;
      justify-content: center;
      gap: 10px;
      padding: 30px;
      clip-path: circle(0 at 100% 0);
      transition: clip-path .7s cubic-bezier(.22, 1, .36, 1)
    }

    .mm a {
      font: 400 clamp(34px, 10vw, 60px) 'Cabin', sans-serif;
      text-transform: uppercase;
      color: var(--black);
    }

    body.mo .mm {
      clip-path: circle(150% at 100% 0)
    }

    body.mo .bg i:first-child {
      transform: translateY(4px) rotate(45deg)
    }

    body.mo .bg i:last-child {
      transform: translateY(-4px) rotate(-45deg)
    }

    /* Anime.js hero text character wrappers */
    .anime-char {
      display: inline-block;
      will-change: transform, opacity;
    }

    /* hero */
    .hero {
      min-height: 100vh;
      min-height: 100svh;
      margin: 10px;
      border-radius: var(--r);
      position: relative;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      justify-content: flex-end;
      padding: clamp(90px, 10vw, 130px) clamp(20px, 4vw, 64px) 40px;
      background: radial-gradient(circle at 50% 38%, rgba(11, 16, 32, 0.6) 0%, rgba(5, 7, 13, 0.95) 70%), var(--bg);
      border: 1px solid rgba(255, 255, 255, 0.06);
    }

    #cv {
      position: absolute;
      inset: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      opacity: 0.25;
    }

    /* Giant watermark text behind person */
    .hero-bg-name {
      position: absolute;
      top: 36%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: 96%;
      max-width: 1400px;
      display: flex;
      justify-content: center;
      align-items: center;
      gap: clamp(14px, 2.5vw, 40px);
      user-select: none;
      pointer-events: none;
      z-index: 1;
    }

    .hero-bg-name span {
      font-family: 'Cabin', sans-serif;
      font-size: clamp(34px, 7.2vw, 115px);
      font-weight: 400;
      line-height: 0.95;
      letter-spacing: clamp(3px, 0.7vw, 12px);
      text-transform: uppercase;
      white-space: nowrap;
      color: rgba(255, 255, 255, 0.09);
    }

    /* Center cutout portrait of founder */
    .hero-person-wrap {
      position: absolute;
      bottom: 0;
      left: 50%;
      transform: translateX(-50%);
      height: min(84vh, 760px);
      width: min(92vw, 680px);
      display: flex;
      justify-content: center;
      align-items: flex-end;
      pointer-events: none;
      z-index: 2;
    }

    .hero-person-wrap img {
      max-height: 100%;
      max-width: 100%;
      width: auto;
      height: auto;
      object-fit: contain;
      object-position: bottom center;
      filter: drop-shadow(0 20px 45px rgba(0, 0, 0, 0.16));
      will-change: transform, opacity;
    }

    /* Content container split into left intro & right CTA */
    .hero-content-split {
      position: relative;
      z-index: 3;
      width: 100%;
      display: flex;
      justify-content: space-between;
      align-items: flex-end;
      gap: 30px;
      margin-bottom: 24px;
    }

    .hero-left-desc {
      max-width: 440px;
    }

    .hero-tagline {
      font-family: 'Cabin', sans-serif;
      font-size: clamp(24px, 3.2vw, 44px);
      line-height: 1.05;
      color: var(--black);
      margin-bottom: 12px;
    }

    .hero-tagline span {
      color: var(--coral);
      font-style: italic;
    }

    .hero-left-desc p {
      color: var(--mu);
      font-size: clamp(14px, 1.15vw, 16px);
      line-height: 1.55;
    }

    .hero-right-action {
      display: flex;
      flex-direction: column;
      align-items: flex-end;
      gap: 14px;
    }

    /* Glowing Coral Action Button like inspiration */
    .hero-action-card {
      position: relative;
      display: inline-flex;
    }

    .hero-action-card::before {
      content: "";
      position: absolute;
      inset: -6px;
      border-radius: 999px;
      background: var(--coral);
      filter: blur(16px);
      opacity: 0.55;
      z-index: -1;
      transition: opacity 0.3s ease, filter 0.3s ease;
    }

    .hero-action-card:hover::before {
      opacity: 0.85;
      filter: blur(22px);
    }

    .hero-action-btn {
      display: inline-flex;
      align-items: center;
      gap: 12px;
      padding: 16px 36px;
      border-radius: 999px;
      background: var(--coral) !important;
      color: #FFFFFF !important;
      border: 1px solid var(--coral) !important;
      font: 600 16px 'Cabin', sans-serif;
      box-shadow: 0 8px 24px rgba(37, 99, 255, 0.35);
      cursor: pointer;
      transition: transform 0.25s ease, box-shadow 0.25s ease;
    }

    .hero-action-btn:hover {
      transform: translateY(-2px);
      box-shadow: 0 12px 30px rgba(37, 99, 255, 0.45);
    }

    /* Bottom pills row inspired by the reference footer chips */
    .hero-pills {
      position: relative;
      z-index: 3;
      width: 100%;
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      padding-top: 18px;
      border-top: 1px solid rgba(255, 255, 255, 0.08);
    }

    .hero-pill {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      padding: 9px 20px;
      background: rgba(11, 16, 32, 0.55);
      backdrop-filter: blur(10px);
      border: 1px solid rgba(255, 255, 255, 0.08);
      border-radius: 999px;
      font: 500 13px 'Cabin', sans-serif;
      color: var(--black);
      transition: background 0.25s, transform 0.25s, color 0.25s;
    }

    .hero-pill:hover {
      background: var(--black);
      color: #FFFFFF;
      transform: translateY(-2px);
    }

    .hero-pill i {
      display: inline-block;
      width: 6px;
      height: 6px;
      border-radius: 50%;
      background: var(--coral);
    }

    .scr {
      position: absolute;
      right: 36px;
      top: 50%;
      transform: translateY(-50%);
      z-index: 3;
      font: 500 12px 'Cabin', sans-serif;
      writing-mode: vertical-rl;
      color: var(--black);
      display: flex;
      align-items: center;
      gap: 10px;
      opacity: 0.65;
    }

    .scr:after {
      content: "";
      width: 1px;
      height: 50px;
      background: var(--coral);
      animation: sc 2s infinite
    }

    @keyframes sc {
      50% {
        transform: scaleY(.3);
        transform-origin: top
      }
    }

    .mq {
      overflow: hidden;
      white-space: nowrap;
      padding: 26px 0;
      border-block: 1px solid rgba(255, 255, 255, 0.08);
      margin-top: 10px
    }

    .mq div {
      display: inline-block;
      font: 400 clamp(30px, 5vw, 70px) 'Cabin', sans-serif;
      text-transform: uppercase;
      color: transparent;
      -webkit-text-stroke: 1px rgba(255, 255, 255, 0.25);
      animation: mq 30s linear infinite
    }

    @keyframes mq {
      to {
        transform: translateX(-50%)
      }
    }

    /* intro */
    .two {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: clamp(24px, 5vw, 80px);
      align-items: center
    }

    .ph {
      aspect-ratio: 4/5;
      border-radius: var(--r);
      background: var(--bg2);
      display: flex;
      justify-content: center;
      align-items: flex-end;
      text-align: center;
      padding: 0;
      color: var(--mu);
      font: 500 14px 'Cabin', sans-serif;
      border: 1px solid rgba(255, 255, 255, 0.08);
      overflow: hidden;
      box-shadow: 0 12px 36px rgba(0, 0, 0, 0.08);
      position: relative;
    }

    .ph img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      object-position: center top;
      transition: transform 0.4s ease;
    }

    .fr p {
      margin-top: 18px;
      max-width: 520px;
      color: var(--mu)
    }

    .fr p b {
      color: var(--black);
      font-weight: 600
    }

    .fr p.big {
      font: 400 clamp(22px, 2.4vw, 34px)/1.25 'Cabin', sans-serif;
      color: var(--black)
    }

    /* brain */
    .brain {
      min-height: 100vh;
      overflow: hidden;
      position: relative;
    }

    .ic {
      position: absolute;
      padding: 16px 22px;
      background: var(--card);
      border: 1px solid rgba(255, 255, 255, 0.1);
      border-radius: 20px;
      font: 500 15px 'Cabin', sans-serif;
      color: var(--black);
      box-shadow: 0 4px 14px rgba(0, 0, 0, 0.05);
      transition: border-color .3s, background .3s, color .3s;
      will-change: transform;
      z-index: 2
    }

    .ic:hover {
      background: var(--black);
      color: #FFFFFF;
      border-color: var(--black)
    }

    .brain .w,
    .brain .brain-content {
      position: relative;
      z-index: 3;
      opacity: 1 !important;
      display: block !important;
      pointer-events: none
    }

    .brain h2 {
      color: var(--tx) !important;
      opacity: 1 !important;
    }

    .brain h3 {
      font-size: clamp(18px, 2.4vw, 34px);
      color: var(--coral) !important;
      opacity: 1 !important;
      margin-top: 26px
    }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 40px
    }

    .tags span {
      border: 1px solid rgba(255, 255, 255, 0.15);
      background: var(--card);
      border-radius: 99px;
      padding: 8px 18px;
      font: 500 14px 'Cabin', sans-serif;
      color: var(--black);
      pointer-events: auto
    }

    /* expertise */
    details {
      border-top: 1px solid rgba(255, 255, 255, 0.12)
    }

    details:last-child {
      border-bottom: 1px solid rgba(255, 255, 255, 0.12)
    }

    summary {
      list-style: none;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 30px 0;
      font: 400 clamp(24px, 4.4vw, 64px) 'Cabin', sans-serif;
      text-transform: uppercase;
      color: var(--black);
      transition: color .3s, padding .4s
    }

    summary::-webkit-details-marker {
      display: none
    }

    summary:hover {
      color: var(--coral);
      padding-left: 18px
    }

    summary small {
      font: 500 14px 'Cabin', sans-serif;
      color: var(--coral);
      margin-right: 20px
    }

    summary:after {
      content: "+";
      font: 300 44px 'Cabin', sans-serif;
      color: var(--coral);
      transition: transform .3s
    }

    details[open] summary:after {
      transform: rotate(45deg)
    }

    details ul {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
      gap: 10px 30px;
      padding: 0 0 36px
    }

    details li {
      color: var(--mu);
      padding: 10px 0;
      border-bottom: 1px solid rgba(255, 255, 255, 0.08)
    }

    details li:before {
      content: "↳ ";
      color: var(--coral)
    }

    /* experience */
    .exp {
      display: grid;
      grid-template-columns: 1.1fr 1fr;
      gap: clamp(24px, 5vw, 80px)
    }

    .exp .role {
      font: 400 clamp(50px, 9vw, 150px) 'Cabin', sans-serif;
      line-height: .9;
      color: var(--coral)
    }

    .cols {
      columns: 2;
      gap: 30px;
      margin-top: 20px
    }

    .cols li {
      break-inside: avoid;
      padding: 9px 0;
      border-bottom: 1px solid rgba(255, 255, 255, 0.1);
      color: var(--mu);
      font-size: 15px
    }

    /* redes */
    .svc {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-top: 40px
    }

    .svc a {
      padding: 16px 26px;
      border-radius: 99px;
      background: var(--bg2);
      border: 1px solid rgba(255, 255, 255, 0.08);
      font: 500 16px 'Cabin', sans-serif;
      color: var(--black);
      transition: background .3s, color .3s, transform .3s
    }

    .svc a:hover {
      background: var(--black);
      color: #FFFFFF;
      transform: translateY(-4px) rotate(-1.5deg)
    }

    .rl {
      display: inline-flex;
      align-items: center;
      gap: 14px;
      margin-bottom: 30px;
      font: 400 24px 'Cabin', sans-serif;
      color: var(--black);
    }

    .rl i {
      width: 46px;
      height: 46px;
      border-radius: 14px;
      background: var(--coral);
      display: grid;
      place-items: center;
      font-style: normal;
      color: #FFFFFF;
      font-family: 'Cabin', sans-serif;
      font-weight: 700
    }

    /* compliance */
    .grid {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 2px;
      margin-top: 60px;
      background: rgba(255, 255, 255, 0.1);
      border: 1px solid rgba(255, 255, 255, 0.1);
      border-radius: var(--r);
      overflow: hidden
    }

    .cell {
      background: var(--card);
      padding: 30px 24px;
      min-height: 230px;
      position: relative;
      transition: background .35s
    }

    .cell:hover {
      background: #FAFAFA
    }

    .cell:hover h3 {
      color: var(--coral)
    }

    .cell small {
      font: 500 13px 'Cabin', sans-serif;
      color: var(--coral)
    }

    .cell h3 {
      font-size: clamp(22px, 2.3vw, 34px);
      margin: 16px 0 14px;
      color: var(--black);
      transition: color .3s
    }

    .cell p {
      color: var(--mu);
      font-size: 14px
    }

    .cell:after {
      content: "";
      position: absolute;
      right: 22px;
      top: 26px;
      width: 9px;
      height: 9px;
      border-radius: 50%;
      background: var(--coral);
      animation: pl 2.4s infinite
    }

    @keyframes pl {
      50% {
        opacity: .2
      }
    }

    /* projects */
    .hs {
      display: flex;
      gap: 18px;
      overflow-x: auto;
      scroll-snap-type: x mandatory;
      padding: 50px clamp(20px, 5vw, 72px) 30px;
      scrollbar-width: thin;
      scrollbar-color: var(--coral) var(--bg2)
    }

    .pc {
      flex: 0 0 min(78vw, 420px);
      scroll-snap-align: start;
      height: 520px;
      border-radius: var(--r);
      background: var(--card);
      border: 1px solid rgba(255, 255, 255, 0.08);
      padding: 30px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      position: relative;
      overflow: hidden;
      box-shadow: 0 6px 20px rgba(0, 0, 0, 0.04);
      transition: transform .4s, box-shadow .4s
    }

    .pc:before {
      content: "";
      position: absolute;
      inset: 0;
      background: radial-gradient(90% 60% at 80% 0, var(--coral), transparent 70%);
      opacity: .0;
      transition: opacity .5s
    }

    .pc:hover:before {
      opacity: .25
    }

    .pc:hover {
      transform: translateY(-8px);
      box-shadow: 0 14px 34px rgba(0, 0, 0, 0.08);
    }

    .pc>* {
      position: relative
    }

    .pc .n {
      font: 500 14px 'Cabin', sans-serif;
      color: var(--coral);
      transition: color .3s
    }

    .pc:hover .n {
      color: var(--black)
    }

    .pc h3 {
      font-size: clamp(28px, 3vw, 44px);
      margin-bottom: 16px;
      color: var(--black);
    }

    .pc p {
      color: var(--mu);
      transition: color .3s
    }

    .pc:hover p {
      color: var(--black)
    }

    /* principles */
    .pr {
      min-height: 70vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      border-top: 1px solid rgba(255, 255, 255, 0.1)
    }

    .pr .d {
      font-size: clamp(34px, 7.4vw, 124px);
      color: var(--black);
    }

    .pr .n {
      font: 500 15px 'Cabin', sans-serif;
      color: var(--coral);
      margin-bottom: 18px
    }

    /* philosophy */
    .lime {
      background: var(--bg2);
      color: var(--black);
      margin: 10px;
      border-radius: var(--r);
      border: 1px solid rgba(255, 255, 255, 0.06);
    }

    .lime .lab {
      color: var(--coral)
    }

    .bl {
      padding: 34px 0;
      border-top: 2px solid rgba(255, 255, 255, 0.12);
      display: flex;
      gap: 30px;
      align-items: baseline
    }

    .bl span {
      font: 600 15px 'Cabin', sans-serif;
      color: var(--coral);
    }

    .bl p {
      font: 400 clamp(26px, 4.6vw, 70px)/1 'Cabin', sans-serif;
      text-transform: uppercase;
      letter-spacing: -.02em;
      color: var(--black);
    }

    /* human */
    .gal {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 14px;
      margin-top: 50px
    }

    .gal .ph {
      aspect-ratio: 3/4;
      border-radius: 22px;
      transition: transform .5s
    }

    .gal .ph:nth-child(even) {
      margin-top: 50px
    }

    .gal .ph:hover {
      transform: scale(1.04) rotate(-1deg)
    }

    /* future / next */
    .fut {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      background: radial-gradient(80% 60% at 50% 100%, #12204A, transparent 70%), var(--bg2)
    }

    .fut h2 span {
      display: block
    }

    .fut h2 .o {
      color: var(--coral)
    }

    .nx {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      background: var(--black);
      color: #FFFFFF;
      margin: 10px;
      border-radius: var(--r)
    }

    .nx h2 {
      font-size: clamp(50px, 13vw, 230px);
      color: #FFFFFF;
    }

    .nx h2 span {
      display: block;
      overflow: hidden
    }

    .wd {
      margin-top: 50px;
      font: 400 clamp(22px, 3.6vw, 52px) 'Cabin', sans-serif;
      text-transform: uppercase;
      height: 1.2em;
      overflow: hidden;
      color: var(--coral)
    }

    .wd ul li {
      height: 1.2em
    }

    /* contact + footer */
    .ct h2 span {
      display: block
    }

    .ct .cta {
      margin-top: 40px
    }

    .dt {
      margin-top: 60px;
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 20px;
      border-top: 1px solid rgba(255, 255, 255, 0.1);
      padding-top: 30px
    }

    .dt small {
      color: var(--mu);
      font: 500 13px 'Cabin', sans-serif;
      display: block;
      margin-bottom: 6px
    }

    .dt a {
      border-bottom: 1px solid rgba(255, 255, 255, 0.3)
    }

    footer {
      padding: 80px clamp(20px, 5vw, 72px) 30px
    }

    footer .t {
      font: 400 clamp(40px, 8vw, 130px) 'Cabin', sans-serif;
      text-transform: uppercase;
      line-height: .95;
      color: var(--coral)
    }

    .fl {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      gap: 20px;
      margin-top: 60px;
      padding-top: 26px;
      border-top: 1px solid rgba(255, 255, 255, 0.1);
      color: var(--mu);
      font-size: 14px
    }

    .fl nav {
      display: flex;
      gap: 22px;
      flex-wrap: wrap
    }

    .fl a:hover {
      color: var(--coral)
    }

    @media(max-width:900px) {
      .nl {
        display: none
      }

      .bg {
        display: flex
      }

      .two,
      .exp {
        grid-template-columns: 1fr
      }

      .grid {
        grid-template-columns: 1fr 1fr
      }

      .gal {
        grid-template-columns: 1fr 1fr
      }

      .gal .ph:nth-child(even) {
        margin-top: 0
      }

      .dt {
        grid-template-columns: 1fr 1fr
      }

      .cols {
        columns: 1
      }

      .scr {
        display: none
      }

      .hero {
        align-items: stretch;
        padding: clamp(80px, 12vw, 110px) 20px 24px;
        min-height: auto;
      }

      .hero-bg-name {
        top: 18%;
        flex-direction: column;
        gap: 0;
      }

      .hero-bg-name span {
        font-size: clamp(28px, 8vw, 44px);
        letter-spacing: 3px;
      }

      .hero-person-wrap {
        position: relative;
        transform: none;
        left: auto;
        bottom: auto;
        height: min(52vh, 440px);
        width: 100%;
        margin-top: 10px;
        margin-bottom: 10px;
      }

      .hero-content-split {
        flex-direction: column;
        align-items: flex-start;
        gap: 20px;
      }

      .hero-right-action {
        align-items: flex-start;
        width: 100%;
      }

      .hero-action-card,
      .hero-action-btn {
        width: 100%;
        justify-content: center;
      }

      .hero-pills {
        justify-content: center;
      }

      .ic {
        font-size: 13px;
        padding: 10px 14px
      }
    }

    @media(max-width:520px) {
      .grid {
        grid-template-columns: 1fr
      }

      .bl {
        flex-direction: column;
        gap: 8px
      }
    }

    @media(prefers-reduced-motion:reduce) {
      * {
        animation: none !important;
        transition-duration: .001s !important
      }

      .rv {
        opacity: 1;
        transform: none
      }
    }

    
#about-img{opacity:0!important}
#fly{position:absolute;left:0;top:0;z-index:3;pointer-events:none;transform-origin:0 0;object-fit:contain;opacity:0;filter:drop-shadow(0 20px 45px rgba(0,0,0,.16))}
.idrow{display:flex;align-items:center;gap:clamp(24px,5vw,72px);margin:48px 0 8px;flex-wrap:wrap}
.idc{perspective:1200px}
.idc .t{transition:transform .2s ease-out;transform-style:preserve-3d}
.idc button{display:block;width:min(260px,70vw);aspect-ratio:1024/1440;position:relative;transform-style:preserve-3d;transition:transform .9s cubic-bezier(.2,.8,.2,1);border-radius:18px;cursor:pointer}
.idc button[aria-pressed="true"]{transform:rotateY(180deg)}
.idc button:focus-visible{outline:3px solid #2563FF;outline-offset:6px}
.idc img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;border-radius:18px;backface-visibility:hidden;-webkit-backface-visibility:hidden;box-shadow:0 24px 60px rgba(37,99,255,.28)}
.idc img.bk{transform:rotateY(180deg)}
.gal .ph img{filter:grayscale(1);transition:filter .5s,transform .5s}
.gal .ph:hover img{filter:none;transform:scale(1.05)}
@media(prefers-reduced-motion:reduce){.idc button,.idc .t{transition:none}}

/* contrast: lighter blue on dark surfaces (AA) */
.nx,.off-footer,.hero-pill:hover,.ic:hover,.svc a:hover{--coral:#4D8DFF}
.nx .lab,.nx h2 span,.off-footer a:hover{color:#4D8DFF}
/* text cards */
.tcjs .tc{opacity:0;transform:translateY(32px) rotateX(-10deg);transform-origin:50% 100%;transition:opacity .7s ease,transform .8s cubic-bezier(.2,.8,.2,1);transition-delay:var(--d,0s)}
.tcjs .tc.on{opacity:1;transform:none}
.tcjs .tc>*:not(.spot){opacity:0;transform:translateY(14px);transition:opacity .6s ease,transform .6s ease;transition-delay:calc(var(--d,0s) + .15s + var(--i,0)*.08s)}
.tcjs .tc.on>*:not(.spot){opacity:1;transform:none}
.tc{position:relative;overflow:hidden}
.tc .spot{position:absolute;inset:0;pointer-events:none;opacity:0;transition:opacity .3s;background:radial-gradient(280px circle at var(--mx,50%) var(--my,50%),rgba(37,99,255,.18),transparent 65%)}
.tc:hover .spot{opacity:1}
.tc h3{transition:color .3s,transform .3s}
.tc:hover h3{color:#2563FF;transform:translateX(6px)}
span.w{opacity:.18;display:inline-block;margin-right:.25em}
@media(prefers-reduced-motion:reduce){.tcjs .tc,.tcjs .tc>*{opacity:1!important;transform:none!important;transition:none!important}span.w{opacity:1}}

:root{color-scheme:dark}
.btn,.btn.l,.btn.g,.hero-action-btn{background:#2563FF!important;border-color:#2563FF!important;color:#fff!important}
.hero-pill:hover,.ic:hover,.svc a:hover{background:#2563FF!important;border-color:#2563FF!important;color:#fff!important}
.nx{background:#000;color:#fff}
.tc:hover h3{color:#4D8DFF}
.hero-person-wrap img,#fly{filter:drop-shadow(0 20px 60px rgba(37,99,255,.38))}
.ph{box-shadow:0 12px 36px rgba(0,0,0,.5)}
/* footer */
.ft{position:relative;margin:10px;border-radius:var(--r);background:#000;color:#F4F7FF;overflow:hidden;isolation:isolate;padding:clamp(56px,8vw,110px) clamp(20px,4vw,64px) 28px;border:1px solid rgba(255,255,255,.1)}
.ft::before{content:"";position:absolute;left:-10%;right:-10%;bottom:-45%;height:85%;z-index:-1;background:radial-gradient(50% 60% at 50% 100%,rgba(37,99,255,.5),transparent 70%)}
.ft-top{display:flex;justify-content:space-between;align-items:flex-end;gap:32px;flex-wrap:wrap;padding-bottom:clamp(36px,6vw,72px);border-bottom:1px solid rgba(255,255,255,.16)}
.ft-cta{font:400 clamp(40px,8vw,120px)/.95 'Cabin',serif;text-transform:uppercase}
.ft-cta span{display:block;color:#4D8DFF}
.ft-btn{display:inline-flex;align-items:center;gap:10px;padding:16px 30px;border-radius:999px;background:#2563FF;color:#fff;font:600 16px 'Cabin',sans-serif;transition:transform .3s,box-shadow .3s;box-shadow:0 8px 30px rgba(37,99,255,.4)}
.ft-btn:hover{transform:translateY(-3px);box-shadow:0 14px 40px rgba(37,99,255,.6)}
.ft-grid{display:grid;grid-template-columns:1.5fr 1fr 1fr;gap:32px;padding:clamp(32px,5vw,56px) 0 0}
.ft h3{font:500 14px 'Cabin',sans-serif;color:#9BA6BC;margin-bottom:12px}
.ft-grid p{color:#C3CBDB;max-width:340px;margin-top:10px}
.ft-name{font:400 28px 'Cabin',serif;color:#fff}
.ft-grid a{position:relative;display:block;width:fit-content;padding:5px 0;color:#F4F7FF}
.ft-grid a::after{content:"";position:absolute;left:0;bottom:2px;height:1px;width:100%;background:#4D8DFF;transform:scaleX(0);transform-origin:0 50%;transition:transform .35s}
.ft-grid a:hover::after,.ft-grid a:focus-visible::after{transform:scaleX(1)}
.ft-word{font:400 clamp(64px,19vw,300px)/.8 'Cabin',serif;text-align:center;color:transparent;-webkit-text-stroke:1px rgba(255,255,255,.3);margin:clamp(28px,4vw,56px) 0 0;white-space:nowrap;user-select:none;transition:color .6s}
.ft-word:hover{color:rgba(77,141,255,.2)}
.ft-bottom{display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:16px;padding-top:20px;margin-top:20px;border-top:1px solid rgba(255,255,255,.16);color:#9BA6BC;font-size:14px}
.ft-up{width:48px;height:48px;border-radius:50%;border:1px solid rgba(255,255,255,.35);color:#fff;display:grid;place-items:center;font-size:20px;transition:background .3s,transform .3s}
.ft-up:hover{background:#2563FF;border-color:#2563FF;transform:translateY(-4px)}
.ft a:focus-visible,.ft button:focus-visible{outline:3px solid #4D8DFF;outline-offset:4px}
.ftjs .ft-a{opacity:0;transform:translateY(28px);transition:opacity .8s ease,transform .8s cubic-bezier(.2,.8,.2,1);transition-delay:var(--d,0s)}
.ftjs .ft.in .ft-a{opacity:1;transform:none}
.ftjs .ft-word{clip-path:inset(100% 0 0 0);transition:clip-path 1.3s cubic-bezier(.2,.8,.2,1) .3s,color .6s}
.ftjs .ft.in .ft-word{clip-path:inset(0)}
@media(max-width:800px){.ft-grid{grid-template-columns:1fr 1fr}.ft-grid>div:first-child{grid-column:1/-1}}
@media(prefers-reduced-motion:reduce){.ftjs .ft-a,.ftjs .ft-word{opacity:1!important;transform:none!important;clip-path:none!important;transition:none!important}}
</style>
</head>

<body>
  <div id="pg"></div>
  <div id="cu"></div>
  <nav class="top" aria-label="Primary">
    <a class="logo" href="#home">BHAVANA<b>.</b>RAJPUROHIT</a>
    <div class="nl"><a href="#home">Home</a><a href="#about">About</a><a href="#expertise">Expertise</a><a
        href="#experience">Experience</a><a href="#projects">Projects</a><a href="#contact">Contact</a></div>
    <button class="bg" id="bg" aria-label="Open menu" aria-expanded="false"><i></i><i></i></button>
  </nav>
  <div class="mm" id="mm"><a href="#home">Home</a><a href="#about">About</a><a href="#expertise">Expertise</a><a
      href="#experience">Experience</a><a href="#projects">Projects</a><a href="#contact">Contact</a></div>

  <main>
    <header class="hero" id="home">
      <canvas id="cv" aria-hidden="true"></canvas>

      <!-- Giant typography watermark behind image -->
      <div class="hero-bg-name" aria-hidden="true">
        <span>BHAVANA</span>
        <span>RAJPUROHIT</span>
      </div>

      <!-- Cutout image centered in hero -->
      <div class="hero-person-wrap">
        <img src="assets/hero-cutout.png" alt="Bhavana Rajpurohit" loading="eager">
      </div>

      <!-- Two-sided content overlay -->
      <div class="hero-content-split">
        <div class="hero-left-desc">
          <div class="hero-tagline">
            I build <span>businesses</span>,<br>technology &amp; smart systems.
          </div>
          <p>
            Founder. Idea collector. Problem solver. Turning complex institutional workflows and business challenges into seamless digital solutions.
          </p>
        </div>

        <div class="hero-right-action">
          <div class="hero-action-card">
            <a class="hero-action-btn" href="#contact">
              Let's talk <span>→</span>
            </a>
          </div>
        </div>
      </div>

      <!-- Bottom feature pills -->
      <div class="hero-pills">
        <span class="hero-pill"><i></i>SaaS Platforms</span>
        <span class="hero-pill"><i></i>ERP &amp; Automation</span>
        <span class="hero-pill"><i></i>Higher Ed Tech</span>
        <span class="hero-pill"><i></i>Compliance Systems</span>
        <span class="hero-pill"><i></i>Digital Transformation</span>
      </div>

      <div class="scr">Scroll</div>
    </header>
    <div class="mq" aria-hidden="true">
      <div>CEO ✦ Builder ✦ Problem Solver ✦ CEO ✦ Builder ✦ Problem Solver ✦ CEO ✦ Builder ✦ Problem Solver
        ✦ CEO ✦ Builder ✦ Problem Solver ✦ </div>
    </div>

    <section class="sec" id="about">
      <div class="two">
        <div class="ph" id="about-ph"><img src="assets/hero-cutout.png" alt="Bhavana Rajpurohit" id="about-img" loading="lazy"></div>
        <div class="fr"><span class="lab rv">The CEO</span>
          <h2 class="rv">So… what do I actually do?</h2>
          <p class="big rv">I'm a founder who sees a broken process and can't leave it alone.</p>
          <p class="rv">I build <b>businesses</b> and <b>technology</b>, and I like the space where the two meet.</p>
          <p class="rv">My approach to technology is simple: it should solve a real problem, not just look impressive.
          </p>
          <p class="rv">I'm interested in business, systems, automation and anything that could work better than it does
            today.</p>
        </div>
      </div>
    </section>

    <section class="sec brain panel" id="brain">
      <div class="brain-content w"><span class="lab">The founder's brain</span>
        <h2>My brain is basically a startup.</h2>
        <h3>Warning: too many ideas.<br>Not enough hours.</h3>
        <div class="tags"><span>Creative thinking</span><span>Exploring ideas</span><span>Problem
            solving</span><span>Experimentation</span><span>Innovation</span></div>
      </div>
      <div class="ic" style="left:8%;top:62%">What if we build this?</div>
      <div class="ic" style="left:52%;top:70%">Why does this process suck?</div>
      <div class="ic" style="right:6%;top:18%">Let's launch something.</div>
      <div class="ic" style="right:10%;top:48%">Wait. I have another idea.</div>
    </section>

    <section class="sec" id="expertise">
      <span class="lab">Core expertise</span>
      <h2>What I know.<br>What I build.<br>What I work on.</h2>
      <div style="margin-top:60px">
        <details open>
          <summary><span><small>A</small>IT &amp; Technology</span></summary>
          <ul>
            <li>IT &amp; Technology Strategy</li>
            <li>IT Consulting &amp; Technology Management</li>
            <li>Software &amp; Web Application Development</li>
            <li>ERP &amp; CRM Solutions</li>
            <li>SaaS Product Development</li>
            <li>Digital Transformation</li>
            <li>AI &amp; Business Automation</li>
            <li>Software Product Strategy</li>
            <li>Business Process Automation</li>
          </ul>
        </details>
        <details>
          <summary><span><small>B</small>Business &amp; Growth</span></summary>
          <ul>
            <li>Business Development &amp; Strategy</li>
            <li>Digital Marketing &amp; SEO</li>
            <li>Lead Generation</li>
            <li>Client Relationship Management</li>
            <li>Business Growth Strategy</li>
            <li>Project &amp; Team Management</li>
            <li>Product Management</li>
            <li>Technology Consulting</li>
          </ul>
        </details>
        <details>
          <summary><span><small>C</small>Higher Education Tech</span></summary>
          <ul>
            <li>Higher Education Technology Solutions</li>
            <li>University ERP &amp; Automation</li>
            <li>Digital Academic Infrastructure</li>
            <li>Institutional Process Automation</li>
            <li>University Website &amp; Digital Platforms</li>
            <li>Academic Technology Systems</li>
          </ul>
        </details>
        <details>
          <summary><span><small>D</small>Accreditation &amp; Compliance</span></summary>
          <ul>
            <li>NAAC Accreditation Support</li>
            <li>UGC Regulations &amp; Compliance</li>
            <li>DigiLocker &amp; NAD Integration</li>
            <li>NBA Accreditation Support</li>
            <li>PCI Compliance</li>
            <li>BCI Compliance</li>
            <li>Academic Data Management</li>
            <li>Institutional Digital Compliance Support</li>
          </ul>
        </details>
      </div>
    </section>

    <section class="sec panel" id="experience">
      <div class="exp">
        <div><span class="lab">Professional experience</span>
          <div class="role rv">Founder</div>
          <h3 class="rv" style="font-size:clamp(20px,2.4vw,34px);margin-top:20px">Redes Creation Private Limited</h3>
          <p class="mu rv" style="margin-top:18px">Technology · IT Consulting · Digital Solutions · Software · SaaS</p>
          <p class="rv" style="margin-top:18px;max-width:460px">Founder journey, business strategy, technology
            management, product development, client solutions, team management and business growth.</p>
        </div>
        <ul class="cols">
          <li>IT Consulting</li>
          <li>University Technology Solutions</li>
          <li>ERP Implementation</li>
          <li>Business Process Automation</li>
          <li>Website &amp; Software Development</li>
          <li>Digital Marketing</li>
          <li>Lead Generation</li>
          <li>SaaS Product Development</li>
          <li>Regulatory Compliance Support</li>
          <li>DigiLocker &amp; NAD Integration</li>
          <li>Project Leadership</li>
        </ul>
      </div>
    </section>

    <section class="sec" id="redes">
      <div class="rl"><i>R</i>Redes Creation <span class="mu" style="font:500 14px 'Cabin',sans-serif">(add logo +
          website link)</span></div>
      <h2 class="rv">I build things through Redes Creation.</h2>
      <p class="mu rv" style="max-width:640px;margin-top:30px;font-size:19px">Redes Creation is a technology and digital
        solutions company focused on helping businesses, institutions, and brands move forward in a digital world.</p>
      <div class="svc"><a href="#">Website Design &amp; Development</a><a href="#">Software &amp; Application
          Development</a><a href="#">ERP &amp; CRM Systems</a><a href="#">SaaS Product Development</a><a
          href="#">Digital Marketing</a><a href="#">SEO</a><a href="#">Business Automation</a><a href="#">AI
          Solutions</a><a href="#">University Technology Solutions</a><a href="#">Digital Transformation</a></div>
    </section>

    <section class="sec panel" id="compliance">
      <span class="lab">Higher education &amp; compliance technology</span>
      <h2>Universities don't just need websites.<br>They need systems.</h2>
      <div class="grid">
        <div class="cell"><small>01</small>
          <h3>NAAC</h3>
          <p>Accreditation Support &amp; Institutional Digital Systems</p>
        </div>
        <div class="cell"><small>02</small>
          <h3>UGC</h3>
          <p>Regulations, Requirements &amp; Institutional Technology</p>
        </div>
        <div class="cell"><small>03</small>
          <h3>NBA</h3>
          <p>Accreditation Support &amp; Outcome-Oriented Systems</p>
        </div>
        <div class="cell"><small>04</small>
          <h3>DigiLocker / NAD</h3>
          <p>Academic Credential Digitization &amp; Integration</p>
        </div>
        <div class="cell"><small>05</small>
          <h3>PCI</h3>
          <p>Pharmacy Education Regulatory Requirements</p>
        </div>
        <div class="cell"><small>06</small>
          <h3>BCI</h3>
          <p>Legal Education Standards &amp; Institutional Systems</p>
        </div>
        <div class="cell"><small>07</small>
          <h3>University ERP</h3>
          <p>Academic &amp; Administrative Automation</p>
        </div>
        <div class="cell"><small>08</small>
          <h3>Higher Ed IT</h3>
          <p>Institutional Digital Infrastructure</p>
        </div>
      </div>
    </section>

    <section class="sec" id="projects" style="padding-inline:0">
      <div style="padding-inline:clamp(20px,5vw,72px)"><span class="lab">What I build</span>
        <h2>Ideas are good.<br>Building them is better.</h2>
      </div>
      <div class="hs" tabindex="0" aria-label="Project categories, scroll horizontally">
        <article class="pc"><span class="n">01</span>
          <div>
            <h3>Enterprise Systems</h3>
            <p>ERP, CRM, management dashboards, automation and workflow systems.</p>
          </div>
        </article>
        <article class="pc"><span class="n">02</span>
          <div>
            <h3>SaaS Products</h3>
            <p>Subscription-based products, platforms and software ecosystems.</p>
          </div>
        </article>
        <article class="pc"><span class="n">03</span>
          <div>
            <h3>Education Technology</h3>
            <p>University portals, academic systems, digital credentials and campus platforms.</p>
          </div>
        </article>
        <article class="pc"><span class="n">04</span>
          <div>
            <h3>Business Automation</h3>
            <p>AI-powered workflows, integrations, operational tools and smart systems.</p>
          </div>
        </article>
        <article class="pc"><span class="n">05</span>
          <div>
            <h3>Future Products</h3>
            <p>New concepts, experiments, prototypes and ideas.</p>
          </div>
        </article>
      </div>
    </section>

    <section aria-label="How I work">
      <div class="sec"><span class="lab">How I work</span>
        <h2>I don't have a 5-year plan carved in stone.</h2>
        <p class="mu" style="margin-top:30px;font-size:20px;max-width:560px">I have direction. I have ambitions. I have
          things I want to build.</p>
      </div>
      <div class="sec pr">
        <div class="n">01</div>
        <div class="d rv">Think big.<br>Start messy.</div>
      </div>
      <div class="sec pr">
        <div class="n">02</div>
        <div class="d rv">Make mistakes.<br>Learn fast.</div>
      </div>
      <div class="sec pr">
        <div class="n">03</div>
        <div class="d rv">Don't wait<br>for permission.</div>
      </div>
      <div class="sec pr">
        <div class="n">04</div>
        <div class="d rv">Build before<br>you overthink.</div>
      </div>
      <div class="sec pr">
        <div class="n">05</div>
        <div class="d rv">Stay hungry.<br>Stay curious.</div>
      </div>
      <div class="sec pr">
        <div class="n">06</div>
        <div class="d rv">Never confuse looking busy with making progress.</div>
      </div>
      <div class="sec pr">
        <div class="n">07</div>
        <div class="d rv">Stay adaptable.</div>
      </div>
    </section>

    <section class="sec lime" id="mind">
      <span class="lab">Unpopular opinions. Maybe not.</span>
      <h2 style="margin-bottom:60px">Things I believe in.</h2>
      <div class="bl rv"><span>01</span>
        <p>Ideas are cheap. Execution is everything.</p>
      </div>
      <div class="bl rv"><span>02</span>
        <p>You don't need to be ready. You need to start.</p>
      </div>
      <div class="bl rv"><span>03</span>
        <p>Failure is only expensive when you learn nothing.</p>
      </div>
      <div class="bl rv"><span>04</span>
        <p>Being busy isn't the same as building something.</p>
      </div>
      <div class="bl rv"><span>05</span>
        <p>The best opportunities rarely look obvious at first.</p>
      </div>
    </section>

    <section class="sec" id="human">
      <span class="lab">The human side</span>
      <h2>Plot twist:<br>I'm a human, not a business pitch.</h2>
      <p class="mu" style="margin-top:26px;max-width:560px">Conversations, new experiences, random discoveries and
        behind-the-scenes moments.</p>
      <div class="idrow"><div class="idc" id="idc"><div class="t" id="idt"><button type="button" id="idb" aria-pressed="false" aria-label="Flip ID card"><img src="assets/id-card-front.png" alt="ID card front"><img class="bk" src="assets/id-card-back.png" alt="ID card back"></button></div></div>
<p class="mu">The card behind the founder. Tap it to see the other side.</p></div>
<div class="gal">
        <div class="ph"><img src="assets/founder-portrait.jpg" alt="Founder portrait"></div>
        <div class="ph">Real photo 2</div>
        <div class="ph">Real photo 3</div>
        <div class="ph">Real photo 4</div>
      </div>
    </section>

    <section class="sec fut panel" id="future">
      <span class="lab">Future vision</span>
      <h2><span class="rv">The future isn't something I want to watch.</span><span class="o rv"
          style="margin-top:20px">It's something I want to build.</span></h2>
      <div class="tags"><span>Artificial Intelligence</span><span>Business Automation</span><span>Software
          Development</span><span>Digital Ecosystems</span><span>Future Technology</span><span>Innovative
          Products</span><span>Scalable Business Systems</span></div>
    </section>

    <section class="sec nx" id="next">
      <h2><span class="rv">I'm not done.</span><span class="rv" style="color:var(--coral)">Not even close.</span></h2>
      <div class="wd" aria-live="off">
        <ul id="wd">
          <li>Ideas I haven't explored</li>
          <li>Products I haven't built</li>
          <li>Businesses I haven't started</li>
          <li>Problems I haven't solved</li>
          <li>People I haven't met</li>
          <li>Versions of myself I haven't become yet</li>
          <li>Ideas I haven't explored</li>
        </ul>
      </div>
    </section>

    <section class="sec ct" id="contact">
      <span class="lab">Let's connect</span>
      <h2><span>Let's make something</span><span style="color:var(--coral)">interesting.</span></h2>
      <p class="mu" style="margin-top:30px;font-size:20px">Have an idea? A challenge? Something crazy to build? I'm
        listening.</p>
      <div class="cta"><a class="btn l mg" href="mailto:YOUR_EMAIL">Let's talk</a><a class="btn g mg" href="#">Connect
          on LinkedIn</a><a class="btn g mg" href="mailto:YOUR_EMAIL">Email me</a><a class="btn g mg" href="#">Explore
          Redes Creation</a></div>
      <div class="dt">
        <div><small>Email</small><a href="mailto:YOUR_EMAIL">YOUR_EMAIL</a></div>
        <div><small>LinkedIn</small><a href="#">Add profile URL</a></div>
        <div><small>Instagram</small><a href="#">Add profile URL</a></div>
        <div><small>Redes Creation</small><a href="#">Add website URL</a></div>
      </div>
    </section>
  </main>

  <footer class="ft" id="site-footer" aria-label="Site footer">
    <div class="ft-top"><h2 class="ft-cta ft-a">Too many ideas.<br>One life.<span>Let's build.</span></h2>
      <a class="ft-btn ft-a" style="--d:.15s" href="#contact">Let's talk <span aria-hidden="true">↗</span></a></div>
    <div class="ft-grid">
      <div class="ft-a" style="--d:.1s"><div class="ft-name">Bhavana Rajpurohit</div>
        <p>Founder. Idea collector. Problem solver. Building businesses and technology at Redes Creation Private Limited.</p></div>
      <nav class="ft-a" style="--d:.2s" aria-label="Footer"><h3>Explore</h3><a href="#home">Home</a><a href="#about">About</a><a href="#expertise">Expertise</a><a href="#experience">Experience</a><a href="#projects">Projects</a><a href="#contact">Contact</a></nav>
      <div class="ft-a" style="--d:.3s"><h3>Connect</h3><a href="mailto:YOUR_EMAIL">Email me</a><a href="#">LinkedIn</a><a href="#">Instagram</a><a href="#">Redes Creation</a></div>
    </div>
    <div class="ft-word" aria-hidden="true">Bhavana</div>
    <div class="ft-bottom ft-a"><span>© 2026 Bhavana Rajpurohit. All rights reserved.</span>
      <button class="ft-up" id="ftup" type="button" aria-label="Back to top">↑</button></div>
  </footer>

<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/ScrollTrigger.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/lenis@1.1.13/dist/lenis.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/animejs/3.2.2/anime.min.js"></script>
  <script>
    (function () {
      var $ = function (s, c) { return (c || document).querySelector(s) }, $$ = function (s, c) { return [].slice.call((c || document).querySelectorAll(s)) };
      var RM = matchMedia('(prefers-reduced-motion:reduce)').matches, fine = matchMedia('(hover:hover) and (pointer:fine)').matches, small = innerWidth < 900;
      $('#yr').textContent = new Date().getFullYear();
      /* menu */
      var bg = $('#bg'); function mo(o) { document.body.classList.toggle('mo', o); bg.setAttribute('aria-expanded', o); bg.setAttribute('aria-label', o ? 'Close menu' : 'Open menu') }
      bg.onclick = function () { mo(!document.body.classList.contains('mo')) };
      $$('#mm a').forEach(function (a) { a.onclick = function () { mo(false) } });
      addEventListener('keydown', function (e) { if (e.key === 'Escape') mo(false) });
      /* smooth scroll + anchors */
      var lenis = null;
      if (window.Lenis && !RM) { lenis = new Lenis({ lerp: .09 }); if (window.gsap && window.ScrollTrigger) { lenis.on('scroll', ScrollTrigger.update); gsap.ticker.add(function (t) { lenis.raf(t * 1000) }); gsap.ticker.lagSmoothing(0) } else { (function r(t) { lenis.raf(t); requestAnimationFrame(r) })(0) } }
      $$('a[href^="#"]').forEach(function (a) { a.addEventListener('click', function (e) { var h = a.getAttribute('href'); if (h.length < 2) return; var t = $(h); if (!t) return; e.preventDefault(); lenis ? lenis.scrollTo(t, { offset: 0 }) : t.scrollIntoView({ behavior: RM ? 'auto' : 'smooth' }) }) });
      /* progress */
      var pg = $('#pg'); function prog() { var m = document.documentElement.scrollHeight - innerHeight; pg.style.transform = 'scaleX(' + (m > 0 ? scrollY / m : 0) + ')' } addEventListener('scroll', prog, { passive: true });
      /* cursor + magnetic */
      if (fine) {
        document.body.classList.add('cur'); var cu = $('#cu'); cu.style.display = 'block'; var cx = 0, cy = 0, tx = 0, ty = 0;
        addEventListener('mousemove', function (e) { tx = e.clientX; ty = e.clientY });
        (function l() { cx += (tx - cx) * .2; cy += (ty - cy) * .2; cu.style.transform = 'translate(' + cx + 'px,' + cy + 'px)'; requestAnimationFrame(l) })();
        $$('a,button,summary,.ic,.pc').forEach(function (el) { el.addEventListener('mouseenter', function () { cu.classList.add('b') }); el.addEventListener('mouseleave', function () { cu.classList.remove('b') }) });
        if (window.gsap && !RM) $$('.mg').forEach(function (b) { b.addEventListener('mousemove', function (e) { var r = b.getBoundingClientRect(); gsap.to(b, { x: (e.clientX - r.left - r.width / 2) * .3, y: (e.clientY - r.top - r.height / 2) * .3, duration: .3 }) }); b.addEventListener('mouseleave', function () { gsap.to(b, { x: 0, y: 0, duration: .6, ease: 'elastic.out(1,.4)' }) }) })
      }
      /* floating idea cards */
      $$('.ic').forEach(function (c, i) { if (!window.gsap || RM) return; gsap.to(c, { x: '+=' + (30 + i * 12), y: '+=' + (26 + i * 8), rotation: (i % 2 ? 4 : -4), duration: 3 + i * .6, repeat: -1, yoyo: true, ease: 'sine.inOut' }) });
      /* word transitions */
      var wd = $('#wd'); if (wd && window.gsap && window.ScrollTrigger && !RM) { var n = wd.children.length - 1, h = wd.firstElementChild.offsetHeight || 40, tl = gsap.timeline({ repeat: -1 }); for (var i = 1; i <= n; i++)tl.to(wd, { y: function () { return -i * (wd.firstElementChild.offsetHeight) }, duration: .8, ease: 'power3.inOut' }, '+=1.1'); tl.to({}, { duration: .01 }).set(wd, { y: 0 }) }
      /* loader + reveals */
      function reveal() {
        if (!window.gsap) { $$('.rv').forEach(function (e) { e.style.opacity = 1; e.style.transform = 'none' }); return }
        if (window.ScrollTrigger) gsap.registerPlugin(ScrollTrigger);
        if (RM) return;

        // Anime.js hero text animations. Keep text visible if the CDN is unavailable.
        if (window.anime) {
          var heroHeading = document.querySelector('.hero-left-desc .hero-tagline');
          var heroDescription = document.querySelector('.hero-left-desc p');
          var heroPills = Array.prototype.slice.call(document.querySelectorAll('.hero-pill'));

          // Split text nodes into characters while preserving colored spans and <br> tags.
          function splitTextIntoChars(element) {
            if (!element || element.dataset.animeSplit === 'true') return;
            var walker = document.createTreeWalker(element, NodeFilter.SHOW_TEXT);
            var nodes = [], node;
            while ((node = walker.nextNode())) nodes.push(node);
            nodes.forEach(function (textNode) {
              var fragment = document.createDocumentFragment();
              Array.from(textNode.nodeValue).forEach(function (character) {
                if (character === ' ' || character === '\\n' || character === '\\t') {
                  fragment.appendChild(document.createTextNode(character));
                } else {
                  var span = document.createElement('span');
                  span.className = 'anime-char';
                  span.textContent = character;
                  fragment.appendChild(span);
                }
              });
              textNode.parentNode.replaceChild(fragment, textNode);
            });
            element.dataset.animeSplit = 'true';
          }

          // 1) Split Text Reveal on the main hero heading.
          splitTextIntoChars(heroHeading);
          if (heroHeading) {
            anime({
              targets: heroHeading.querySelectorAll('.anime-char'),
              translateY: ['1.15em', '0em'],
              opacity: [0, 1],
              duration: 850,
              delay: anime.stagger(24),
              easing: 'easeOutCubic',
              complete: function () {
                heroHeading.querySelectorAll('.anime-char').forEach(function (char) {
                  char.style.willChange = 'auto';
                });
              }
            });
          }

          // 2) Slide Up Text on the supporting description.
          if (heroDescription) {
            anime({
              targets: heroDescription,
              translateY: [32, 0],
              opacity: [0, 1],
              duration: 850,
              delay: 420,
              easing: 'easeOutCubic'
            });
          }

          // 3) Stagger Text Animation for the hero feature pills.
          if (heroPills.length) {
            anime({
              targets: heroPills,
              translateY: [22, 0],
              opacity: [0, 1],
              delay: anime.stagger(100, { start: 720 }),
              duration: 650,
              easing: 'easeOutCubic'
            });
          }
        }

        // Cinematic Step-by-Step Staggered Sequence for Hero
        var heroTL = gsap.timeline({ defaults: { ease: 'power3.out' } });

        // Step 1: Nav Bar fades in smoothly from top
        heroTL.from('nav.top', { y: -25, opacity: 0, duration: 0.8 })
        
        // Step 2: Giant Background Watermark Name expands gently
        .from('.hero-bg-name span', {
          y: 40,
          scale: 0.92,
          opacity: 0,
          duration: 1.1,
          stagger: 0.18
        }, '-=0.4')

        // Step 3: Center Portrait Slides Up Elegantly from Bottom
        .from('.hero-person-wrap img', {
          y: 180,
          opacity: 0,
          duration: 1.5,
          ease: 'power3.out'
        }, '-=0.8')

        // Hero text is animated by Anime.js below (avoid GSAP conflict).\n\n        // Step 5: Right Coral Glowing CTA Button pops up
        .from('.hero-right-action', {
          scale: 0.82,
          y: 25,
          opacity: 0,
          duration: 0.9,
          ease: 'back.out(1.5)'
        }, '-=0.6')

        // Hero pills are animated by Anime.js below.\n\n        // Step 7: Scroll Indicator indicator appears
        .from('.scr', {
          opacity: 0,
          duration: 0.7
        }, '-=0.3');

        if (!window.ScrollTrigger) { $$('.rv').forEach(function (e) { e.style.opacity = 1; e.style.transform = 'none' }); return }

        // Continuous Hero to About Image Transition on Scroll
        if (false) { ScrollTrigger.matchMedia({
            "(min-width: 901px)": function () {
              var heroImg = document.querySelector('.hero-person-wrap img');
              var aboutBox = document.getElementById('about-ph');
              var aboutImg = document.getElementById('about-img');

              if (heroImg && aboutBox) {
                gsap.timeline({
                  scrollTrigger: {
                    trigger: '#home',
                    start: 'top top',
                    endTrigger: '#about',
                    end: 'center center',
                    scrub: 1.2,
                    invalidateOnRefresh: true
                  }
                })
                .to(heroImg, {
                  x: function () {
                    var r1 = heroImg.getBoundingClientRect();
                    var r2 = aboutBox.getBoundingClientRect();
                    return (r2.left + r2.width / 2) - (r1.left + r1.width / 2);
                  },
                  y: function () {
                    var r1 = heroImg.getBoundingClientRect();
                    var r2 = aboutBox.getBoundingClientRect();
                    return (r2.top + r2.height / 2) - (r1.top + r1.height / 2);
                  },
                  scale: 0.68,
                  ease: 'power1.inOut'
                })
                .to(aboutImg, {
                  opacity: 1,
                  duration: 0.2
                }, '-=0.2')
                .to(heroImg, {
                  opacity: 0,
                  duration: 0.2
                }, '-=0.2');
              }
            }
          });
        }

        // Line-by-Line reveal for About Section right content
        gsap.timeline({
          scrollTrigger: {
            trigger: '#about',
            start: 'top 75%',
            end: 'center 45%',
            scrub: 0.8
          }
        })
        .from('#about .fr .lab', { opacity: 0, y: 30, duration: 0.5 })
        .from('#about .fr h2', { opacity: 0, y: 35, duration: 0.7 })
        .from('#about .fr .big', { opacity: 0, y: 30, duration: 0.7 })
        .from('#about .fr p:not(.big)', {
          opacity: 0,
          y: 25,
          duration: 0.6,
          stagger: 0.25
        });

        // Other page reveals
        $$('.cell').forEach(function (e, i) { gsap.from(e, { opacity: 0, y: 30, duration: .7, delay: (i % 4) * .08, scrollTrigger: { trigger: e, start: 'top 92%' } }) });
        $$('.pr .d').forEach(function (e) { gsap.fromTo(e, { opacity: .12 }, { opacity: 1, ease: 'none', scrollTrigger: { trigger: e, start: 'top 85%', end: 'top 40%', scrub: true } }) });
      }

      // Trigger reveal immediately on page ready
      if (document.readyState === 'interactive' || document.readyState === 'complete') {
        reveal();
      } else {
        addEventListener('DOMContentLoaded', reveal);
      }
      /* 3D */
      if (!window.THREE) return;
      var cv = $('#cv'), R = new THREE.WebGLRenderer({ canvas: cv, antialias: !small, alpha: true }); R.setPixelRatio(Math.min(devicePixelRatio, small ? 1.5 : 2));
      var S = new THREE.Scene(), C = new THREE.PerspectiveCamera(35, 1, .1, 50); C.position.set(0, .2, 9);
      S.add(new THREE.AmbientLight(0xffffff, .45));
      var k = new THREE.DirectionalLight(0x4d8dff, 1.6); k.position.set(-4, 3, 4); S.add(k);
      var rim = new THREE.DirectionalLight(0x2563ff, 1.4); rim.position.set(4, 2, -3); S.add(rim);
      var skin = new THREE.MeshStandardMaterial({ color: 0x0a1020, roughness: .55, metalness: .15 }),
        jk = new THREE.MeshStandardMaterial({ color: 0x2563ff, roughness: .5, metalness: .1 }),
        vz = new THREE.MeshStandardMaterial({ color: 0x0b0b0b, roughness: .1, metalness: .9, emissive: 0x2563ff, emissiveIntensity: .35 });
      var ch = new THREE.Group(); S.add(ch);
      var body = new THREE.Mesh(new THREE.CylinderGeometry(.95, 1.25, 2.1, 24), jk); body.position.y = -1.6; ch.add(body);
      var sh = new THREE.Mesh(new THREE.SphereGeometry(1.05, 24, 16), jk); sh.scale.set(1.25, .5, .8); sh.position.y = -.65; ch.add(sh);
      var head = new THREE.Group(); head.position.y = .35; ch.add(head);
      head.add(new THREE.Mesh(new THREE.SphereGeometry(.9, 32, 24), skin));
      var vs = new THREE.Mesh(new THREE.BoxGeometry(1.5, .34, .4), vz); vs.position.set(0, .1, .72); head.add(vs);
      var cap = new THREE.Mesh(new THREE.SphereGeometry(.95, 32, 16, 0, Math.PI * 2, 0, Math.PI * .42), new THREE.MeshStandardMaterial({ color: 0x0b0b0b, roughness: .8 })); cap.position.y = .06; head.add(cap);
      var arm = new THREE.Group(); arm.position.set(1.35, -.75, 0); var am = new THREE.Mesh(new THREE.CylinderGeometry(.22, .26, 1.5, 16), jk); am.position.y = -.65; arm.add(am);
      var hd = new THREE.Mesh(new THREE.SphereGeometry(.28, 16, 12), skin); hd.position.y -= 1.45; arm.add(hd); arm.rotation.z = .18; ch.add(arm);
      var fl = [], gm = [new THREE.IcosahedronGeometry(.4, 0), new THREE.TorusGeometry(.35, .12, 10, 24), new THREE.OctahedronGeometry(.4)];
      for (var i = 0; i < (small ? 5 : 9); i++) { var m = new THREE.Mesh(gm[i % 3], new THREE.MeshStandardMaterial({ color: i % 2 ? 0x2563ff : 0xffffff, wireframe: i % 3 == 0, roughness: .4, metalness: .5 })); m.position.set((Math.random() - .5) * 10, (Math.random() - .5) * 5, -1 + Math.random() * -3); m.userData = { s: .3 + Math.random() * .5, p: Math.random() * 6 }; S.add(m); fl.push(m) }
      function rs() { var w = cv.clientWidth, h = cv.clientHeight; R.setSize(w, h, false); C.aspect = w / h; C.updateProjectionMatrix(); var wide = w >= 900; ch.position.set(wide ? 2.9 : 0, wide ? -.1 : 1.1, 0); ch.scale.setScalar(wide ? 1 : .7) }
      rs(); addEventListener('resize', rs);
      var mx = 0, my = 0, wv = 0, wt = 0;
      addEventListener('pointermove', function (e) { mx = e.clientX / innerWidth * 2 - 1; my = e.clientY / innerHeight * 2 - 1 });
      cv.parentNode.addEventListener('click', function (e) { if (e.target.closest('a')) return; wt = 1 });
      var vis = true; new IntersectionObserver(function (e) { vis = e[0].isIntersecting }).observe(cv);
      var clk = new THREE.Clock();
      function tick() {
        requestAnimationFrame(tick); if (!vis) return; var t = clk.getElapsedTime();
        head.rotation.y += (mx * .7 - head.rotation.y) * .08; head.rotation.x += (my * .35 - head.rotation.x) * .08;
        ch.rotation.y += (mx * .25 - ch.rotation.y) * .05; ch.position.y += (Math.sin(t * 1.2) * .08 - (ch.position.y - (innerWidth >= 900 ? -.1 : 1.1))) * .02;
        if (!RM) {
          var cyc = t % 9; wv = cyc > 7 ? Math.sin(t * 10) * .5 : wv * .9; if (wt) { wv = Math.sin(t * 10) * .6; wt = (t % 1 < .98) ? wt : 0; setTimeout(function () { wt = 0 }, 1200) }
          arm.rotation.z = cyc > 7 || wt ? 2.4 + wv * .5 : .18; arm.position.y = -.75
        }
        fl.forEach(function (m) { m.rotation.x += .004 * m.userData.s; m.rotation.y += .006; m.position.y += Math.sin(t * m.userData.s + m.userData.p) * .003 });
        R.render(S, C)
      }
      tick();
    })();

    /* --- OFFLINE FOOTER CONTROLLER --- */
  </script>
<script>
(function(){
var RM=matchMedia('(prefers-reduced-motion:reduce)').matches;
/* 1. hero image travels into About and stops on the left */
var hw=document.querySelector('.hero-person-wrap img'),box=document.getElementById('about-ph');
if(hw&&box&&!RM){
 var fly=document.createElement('img');fly.id='fly';fly.alt='';fly.setAttribute('aria-hidden','true');fly.src=hw.src;document.body.appendChild(fly);
 var H=null,cur=0;
 function mH(){var r=hw.getBoundingClientRect(),y=window.gsap?(gsap.getProperty(hw,'y')||0):0;if(r.width>0)H={l:r.left+scrollX,t:r.top+scrollY-y,w:r.width,h:r.height}}
 (function frame(){
  var sy=scrollY,b=box.getBoundingClientRect(),A={l:b.left+scrollX,t:b.top+sy,w:b.width,h:b.height};
  if(sy<2||!H)mH();
  if(H){
   var end=Math.max(1,A.t+A.h/2-innerHeight/2),tg=Math.min(1,sy/end);
   cur+=(tg-cur)*.14;if(Math.abs(tg-cur)<.0005)cur=tg;
   var e=cur*cur*(3-2*cur),fh=A.w*H.h/H.w,w=H.w+(A.w-H.w)*e,h=H.h+(fh-H.h)*e,
   l=H.l+(A.l-H.l)*e,bot=(H.t+H.h)+((A.t+A.h)-(H.t+H.h))*e;
   fly.style.width=w+'px';fly.style.height=h+'px';fly.style.transform='translate3d('+l+'px,'+(bot-h)+'px,0)';
   var on=sy>2||cur>.001;fly.style.opacity=on?1:0;hw.style.visibility=on?'hidden':'';
  }
  requestAnimationFrame(frame)})();
}
/* 2. ID card flip + pointer tilt */
var b=document.getElementById('idb'),t=document.getElementById('idt'),c=document.getElementById('idc');
if(b){b.addEventListener('click',function(){b.setAttribute('aria-pressed',b.getAttribute('aria-pressed')!=='true')});
 if(!RM)c.addEventListener('pointermove',function(e){var r=c.getBoundingClientRect();t.style.transform='rotateY('+(((e.clientX-r.left)/r.width-.5)*16)+'deg) rotateX('+(-((e.clientY-r.top)/r.height-.5)*16)+'deg)'});
 c.addEventListener('pointerleave',function(){t.style.transform=''})}
/* 3. magnetic CTA buttons */
if(!RM&&matchMedia('(hover:hover)').matches)document.querySelectorAll('.hero-action-btn,.ct .cta a').forEach(function(el){
 el.style.transition='transform .25s ease-out';
 el.addEventListener('pointermove',function(e){var r=el.getBoundingClientRect();el.style.transform='translate('+((e.clientX-r.left-r.width/2)*.25)+'px,'+((e.clientY-r.top-r.height/2)*.25)+'px)'});
 el.addEventListener('pointerleave',function(){el.style.transform=''})});
/* 4. connected-systems network behind the compliance section */
var sec=document.getElementById('compliance');
if(sec&&!RM){
 var cv=document.createElement('canvas');cv.setAttribute('aria-hidden','true');cv.style.cssText='position:absolute;inset:0;width:100%;height:100%;z-index:-1;pointer-events:none;border-radius:inherit;opacity:.55';
 sec.style.position='relative';sec.style.isolation='isolate';sec.prepend(cv);
 var x=cv.getContext('2d'),W,Hh,N=[],vis=false,dpr=Math.min(devicePixelRatio||1,1.5);
 function rs(){W=sec.clientWidth;Hh=sec.clientHeight;cv.width=W*dpr;cv.height=Hh*dpr;x.setTransform(dpr,0,0,dpr,0,0)}
 rs();addEventListener('resize',rs);
 for(var i=0;i<(innerWidth<700?22:42);i++)N.push({x:Math.random()*W,y:Math.random()*Hh,vx:(Math.random()-.5)*.35,vy:(Math.random()-.5)*.35});
 new IntersectionObserver(function(e){vis=e[0].isIntersecting}).observe(sec);
 (function loop(){requestAnimationFrame(loop);if(!vis)return;x.clearRect(0,0,W,Hh);
  N.forEach(function(n){n.x+=n.vx;n.y+=n.vy;if(n.x<0||n.x>W)n.vx*=-1;if(n.y<0||n.y>Hh)n.vy*=-1});
  for(var i=0;i<N.length;i++){for(var j=i+1;j<N.length;j++){var dx=N[i].x-N[j].x,dy=N[i].y-N[j].y,d=Math.sqrt(dx*dx+dy*dy);
   if(d<150){x.strokeStyle='rgba(37,99,255,'+(1-d/150)*.5+')';x.beginPath();x.moveTo(N[i].x,N[i].y);x.lineTo(N[j].x,N[j].y);x.stroke()}}
   x.fillStyle='#2563FF';x.beginPath();x.arc(N[i].x,N[i].y,2.4,0,6.283);x.fill()}})();
}
})();
</script>
<script>
(function(){
var RM=matchMedia('(prefers-reduced-motion:reduce)').matches;
var cards=[].slice.call(document.querySelectorAll('.cell,.pc'));
cards.forEach(function(c){c.classList.add('tc');var sp=document.createElement('i');sp.className='spot';c.appendChild(sp);
 [].forEach.call(c.children,function(k,i){k.style.setProperty('--i',i)});
 c.addEventListener('pointermove',function(e){var r=c.getBoundingClientRect();c.style.setProperty('--mx',(e.clientX-r.left)+'px');c.style.setProperty('--my',(e.clientY-r.top)+'px')})});
if(!RM&&'IntersectionObserver'in window){
 document.documentElement.classList.add('tcjs');
 var io=new IntersectionObserver(function(es){es.forEach(function(e){if(e.isIntersecting){e.target.classList.add('on');io.unobserve(e.target)}})},{rootMargin:'-6% 1200px -6% 1200px'});
 cards.forEach(function(c,i){c.style.setProperty('--d',((i%4)*.1)+'s');io.observe(c)});
 setTimeout(function(){cards.forEach(function(c){if(!c.classList.contains('on')&&c.getBoundingClientRect().top<innerHeight)c.classList.add('on')})},1800);
}
/* word-by-word text reveal tied to scroll */
if(!RM&&window.gsap&&window.ScrollTrigger){
 document.querySelectorAll('.bl p,.big').forEach(function(el){
  if(el.children.length)return;var t=el.textContent.trim().split(/\s+/);el.setAttribute('aria-label',el.textContent.trim());
  el.innerHTML=t.map(function(w){return '<span class="w" aria-hidden="true">'+w+'</span>'}).join('');
  gsap.to(el.querySelectorAll('.w'),{opacity:1,stagger:.12,ease:'none',scrollTrigger:{trigger:el,start:'top 88%',end:'bottom 58%',scrub:true}});
 });
}else document.querySelectorAll('.w').forEach(function(w){w.style.opacity=1});
})();
</script>
<script>
(function(){
var f=document.getElementById('site-footer'),RM=matchMedia('(prefers-reduced-motion:reduce)').matches;
document.getElementById('ftup').addEventListener('click',function(){scrollTo({top:0,behavior:RM?'auto':'smooth'})});
if(!RM&&'IntersectionObserver'in window){document.documentElement.classList.add('ftjs');
 new IntersectionObserver(function(e,o){if(e[0].isIntersecting){f.classList.add('in');o.disconnect()}},{threshold:.15}).observe(f)}
})();
</script>
</body>

</html>