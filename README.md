<div align="center">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 200" width="100%" height="100%">
    <defs>
      <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" style="stop-color:#00F2FE;stop-opacity:1" />
        <stop offset="100%" style="stop-color:#4FACFE;stop-opacity:1" />
      </linearGradient>
      <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="8" result="blur" />
        <feComposite in="SourceGraphic" in2="blur" operator="over" />
      </filter>
    </defs>
    <!-- Background Card -->
    <rect width="100%" height="100%" rx="16" fill="#0D1117" stroke="#30363D" stroke-width="2"/>
    <!-- Logo Text -->
    <text x="50%" y="55%" dominant-baseline="middle" text-anchor="middle" 
          font-family="system-ui, -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif" 
          font-size="72" font-weight="900" letter-spacing="6" 
          fill="url(#grad)" filter="url(#glow)">
      FARDIN
    </text>
    <!-- Accent Line -->
    <rect x="350" y="145" width="100" height="4" rx="2" fill="url(#grad)" />
  </svg>
</div>
