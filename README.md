### 🚀 Progresso do Curso (20%)

<!-- Barra de progresso animada em SVG -->
<svg width="350" height="30" xmlns="http://www.w3.org/2000/svg">
  <!-- Fundo -->
  <rect width="350" height="30" fill="#ddd" rx="5" />
  
  <!-- Barra animada -->
  <rect id="bar" height="30" fill="#4caf50" rx="5">
    <animate 
      attributeName="width"
      from="0"
      to="70"  <!-- 20% de 350px = 70px -->
      dur="2s"
      fill="freeze"
    />
  </rect>

  <!-- Texto 20% -->
  <text x="175" y="20" font-size="16" text-anchor="middle" fill="#000">
    20%
  </text>
</svg>
