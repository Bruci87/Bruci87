
<div align="center">
  <svg width="200" height="200" viewBox="-10 -10 20 20" xmlns="http://www.w3.org/2000/svg">
    <style>
      .pixel { shape-rendering: crispedges; }
      @keyframes fly {
        0%, 100% { display: block; }
        50% { display: none; }
      }
      .frame1 { animation: fly 0.4s infinite; }
      .frame2 { animation: fly 0.4s infinite reverse; }
    </style>

    <g>
      <animateTransform attributeName="transform" type="translate" values="0 0; 0 -2; 0 0" dur="2s" repeatCount="indefinite" />
      
      <g class="frame1" fill="white">
        <rect x="-1" y="-2" width="2" height="3" /> <rect x="-1" y="-3" width="1" height="1" /> <rect x="1" y="-3" width="1" height="1" /> <rect x="-1" y="-2" width="1" height="1" fill="red" /> <rect x="1" y="-2" width="1" height="1" fill="red" /> <path d="M-2 -1 h-1 v-1 h-1 v-1 h-1 v1 h1 v1 h1 v1 Z" /> <path d="M2 -1 h1 v-1 h1 v-1 h1 v1 h-1 v1 h-1 v1 Z" /> </g>

      <g class="frame2" fill="white">
        <rect x="-1" y="-2" width="2" height="3" /> <rect x="-1" y="-3" width="1" height="1" /> <rect x="1" y="-3" width="1" height="1" /> <rect x="-1" y="-2" width="1" height="1" fill="red" /> <rect x="1" y="-2" width="1" height="1" fill="red" /> <path d="M-2 0 h-1 v1 h-1 v1 h-1 v-1 h1 v-1 h1 v-1 Z" /> <path d="M2 0 h1 v1 h1 v1 h1 v-1 h-1 v-1 h-1 v-1 Z" /> </g>
    </g>
  </svg>
</div>
