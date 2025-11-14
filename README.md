<p align="center">
  <img src="docs/images/banner.svg" alt="SkySentinel-AI banner" width="100%"/>
</p>

<?xml version="1.0" encoding="utf-8"?>
<svg xmlns="http://www.w3.org/2000/svg"
     width="1600" height="360" viewBox="0 0 1600 360" role="img" aria-labelledby="title desc">
  <title id="title">SkySentinel-AI banner</title>
  <desc id="desc">Dark neon cyber banner: SkySentinel-AI, DevSecOps • Cloud Security • AI-driven Automation</desc>

  <!-- Background gradients -->
  <defs>
    <linearGradient id="bg" x1="0" x2="1">
      <stop offset="0" stop-color="#021026"/>
      <stop offset="0.35" stop-color="#002338"/>
      <stop offset="1" stop-color="#001026"/>
    </linearGradient>

    <linearGradient id="glow" x1="0" x2="1">
      <stop offset="0" stop-color="#00f0ff" stop-opacity="0.25"/>
      <stop offset="0.45" stop-color="#2ee6c6" stop-opacity="0.12"/>
      <stop offset="1" stop-color="#003bff" stop-opacity="0.08"/>
    </linearGradient>

    <radialGradient id="rightOrb" cx="50%" cy="50%" r="50%">
      <stop offset="0" stop-color="#00eaff" stop-opacity="0.95"/>
      <stop offset="0.45" stop-color="#00a6ff" stop-opacity="0.25"/>
      <stop offset="1" stop-color="#001826" stop-opacity="0"/>
    </radialGradient>

    <!-- subtle grid pattern -->
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M40 0 L0 0 0 40" fill="none" stroke="#002b3a" stroke-opacity="0.06" stroke-width="1"/>
    </pattern>

    <!-- neon glow filter -->
    <filter id="neon" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="6" result="b"/>
      <feMerge>
        <feMergeNode in="b"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- thin stripe accent -->
    <linearGradient id="accent" x1="0" x2="1">
      <stop offset="0" stop-color="#00f0ff"/>
      <stop offset="0.6" stop-color="#2ee6c6"/>
      <stop offset="1" stop-color="#0066ff"/>
    </linearGradient>
  </defs>

  <!-- base -->
  <rect width="1600" height="360" fill="url(#bg)"/>

  <!-- subtle pattern overlay -->
  <rect width="1600" height="360" fill="url(#grid)" opacity="0.40"/>

  <!-- left faint cyber rays -->
  <g transform="translate(60,40)">
    <ellipse cx="180" cy="120" rx="420" ry="140" fill="url(#glow)" opacity="0.08"/>
    <ellipse cx="140" cy="120" rx="320" ry="100" fill="url(#glow)" opacity="0.06"/>
  </g>

  <!-- accent underline -->
  <rect x="120" y="160" width="720" height="6" rx="3" fill="url(#accent)" filter="url(#neon)" opacity="0.95"/>

  <!-- Title group -->
  <g transform="translate(120,82)" fill="#e6f9ff" font-family="Inter, system-ui, -apple-system, 'Segoe UI', Roboto, Arial" >
    <text x="0" y="48" font-size="44" font-weight="700" letter-spacing="-0.6">SkySentinel-AI</text>
    <text x="0" y="88" font-size="16" fill="#9fcbd6" font-weight="600">DevSecOps • Cloud Security • AI-driven Automation</text>
  </g>

  <!-- thin divider (neon) -->
  <g transform="translate(120,132)">
    <rect x="0" y="0" width="760" height="1" fill="#0b2f3a" opacity="0.5"/>
  </g>

  <!-- right orb / emblem -->
  <g transform="translate(1200,60)">
    <circle cx="120" cy="120" r="82" fill="url(#rightOrb)" opacity="0.95"/>
    <!-- inner shape (diamond) -->
    <g transform="translate(120,120) rotate(45)">
      <rect x="-22" y="-44" width="44" height="88" rx="6" ry="6" fill="#002b3a" opacity="0.15"/>
      <path d="M0 -34 L20 0 L0 34 L -20 0 Z" fill="none" stroke="#67f3ff" stroke-width="4" stroke-linejoin="round" stroke-linecap="round" filter="url(#neon)"/>
      <path d="M0 -22 L12 0 L0 22 L -12 0 Z" fill="none" stroke="#00b3ff" stroke-width="2" opacity="0.9"/>
    </g>
    <!-- subtle ring -->
    <circle cx="120" cy="120" r="100" fill="none" stroke="#003b5c" stroke-opacity="0.18" stroke-width="6"/>
  </g>

  <!-- faint top-left corner label -->
  <g transform="translate(40,20)">
    <rect x="0" y="0" width="120" height="28" rx="6" fill="#001a24" opacity="0.28"/>
    <text x="12" y="19" font-size="12" fill="#8adbe6" font-weight="700">DevSecOps</text>
  </g>

  <!-- optional small accent icon near text (stack of docs) -->
  <g transform="translate(100,200)" opacity="0.98" fill="#94f7ff">
    <rect x="0" y="0" width="44" height="30" rx="3" fill="#001a24" opacity="0.06"/>
    <path d="M6 6h28v2H6zM6 12h28v2H6zM6 18h18v2H6z" fill="#69f0ff" opacity="0.85"/>
  </g>

  <!-- bottom cyber frame line -->
  <rect x="90" y="310" width="1420" height="6" rx="3" fill="url(#accent)" opacity="0.18"/>

  <!-- accessibility: fallback text for non-SVG renders (screen readers ignore visually) -->
  <foreignObject x="0" y="0" width="1" height="1" style="overflow:visible">
    <p xmlns="http://www.w3.org/1999/xhtml" style="font-size:1px;opacity:0">SkySentinel-AI — DevSecOps • Cloud Security • AI-driven Automation</p>
  </foreignObject>

</svg>
</div>
