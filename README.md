<!-- ═════ CYBER PIXEL GRID HEADER (PRO VERSION) ═════ -->
<div align="center">

<svg width="100%" height="180" viewBox="0 0 1200 180" xmlns="http://www.w3.org/2000/svg">

  <defs>

    <!-- 🔵 Soft cyber gradient background -->
    <linearGradient id="fade" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#000000"/>
      <stop offset="45%" stop-color="#070b14"/>
      <stop offset="55%" stop-color="#0a0f1c"/>
      <stop offset="100%" stop-color="#000000"/>
    </linearGradient>

    <!-- ⚡ refined cyber grid (more realistic + layered feel) -->
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      
      <!-- main grid lines -->
      <path d="M 40 0 L 0 0 0 40"
            fill="none"
            stroke="#00F7FF"
            stroke-width="0.6"
            opacity="0.25"/>

      <!-- inner pixel dot (gives tech feel) -->
      <circle cx="0" cy="0" r="1.2" fill="#00F7FF" opacity="0.35"/>
    </pattern>

    <!-- ✨ glow overlay -->
    <radialGradient id="glow" cx="50%" cy="50%" r="70%">
      <stop offset="0%" stop-color="#00F7FF" opacity="0.08"/>
      <stop offset="100%" stop-color="#000000" opacity="0"/>
    </radialGradient>

  </defs>

  <!-- background -->
  <rect width="1200" height="180" fill="url(#fade)" />

  <!-- glow layer -->
  <rect width="1200" height="180" fill="url(#glow)" />

  <!-- grid layer -->
  <rect width="1200" height="180" fill="url(#grid)" opacity="0.7"/>

  <!-- center scan line -->
  <line x1="0" y1="90" x2="1200" y2="90"
        stroke="#00F7FF"
        stroke-width="1.2"
        opacity="0.35"/>

  <!-- subtle top highlight -->
  <line x1="0" y1="30" x2="1200" y2="30"
        stroke="#00F7FF"
        stroke-width="0.5"
        opacity="0.15"/>

</svg>

</div>
