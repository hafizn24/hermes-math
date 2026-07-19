# Diagram Geometri Koordinat

## Diagram 1: Sistem Koordinat Cartesian

<svg viewBox="0 0 400 400" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="200" x2="400" y2="200" stroke="black" stroke-width="1"/>
  <line x1="200" y1="0" x2="200" y2="400" stroke="black" stroke-width="1"/>
  <circle cx="260" cy="110" r="4" fill="red"/>
  <text x="266" y="106" font-size="14">A(2, 3)</text>
  <circle cx="170" cy="80" r="4" fill="red"/>
  <text x="120" y="76" font-size="14">B(-1, 4)</text>
  <circle cx="290" cy="260" r="4" fill="red"/>
  <text x="296" y="264" font-size="14">C(3, -2)</text>
  <circle cx="110" cy="230" r="4" fill="red"/>
  <text x="40" y="244" font-size="14">D(-3, -1)</text>
</svg>

**Koordinat Utama:**
- A(2, 3)
- B(-1, 4) 
- C(3, -2)
- D(-3, -1)

**Sukuan:**
- Sukuan I: (+, +)
- Sukuan II: (-, +)
- Sukuan III: (-, -)
- Sukuan IV: (+, -)

**Nota:** Diagram 2 hingga Diagram 7 dalam fail ini masih belum mempunyai visual sebenar (hanya teks/formula). Ini masih tertunda dan bukan sebahagian daripada pembetulan semasa.

## Diagram 2: Formula Jarak

<svg viewBox="0 0 400 400" xmlns="http://www.w3.org/2000/svg">
  <!-- Grid lines -->
  <defs>
    <pattern id="grid" width="20" height="20" patternUnits="userSpaceOnUse">
      <path d="M 20 0 L 0 0 0 20" fill="none" stroke="#e0e0e0" stroke-width="0.5"/>
    </pattern>
  </defs>
  <rect width="400" height="400" fill="url(#grid)"/>
  
  <!-- Axes -->
  <line x1="0" y1="200" x2="400" y2="200" stroke="black" stroke-width="2"/>
  <line x1="200" y1="0" x2="200" y2="400" stroke="black" stroke-width="2"/>
  
  <!-- Points A and B -->
  <circle cx="80" cy="260" r="5" fill="red"/>
  <circle cx="300" cy="80" r="5" fill="blue"/>
  
  <!-- Labels -->
  <text x="85" y="275" font-size="14" font-weight="bold">A(-3, -1)</text>
  <text x="305" y="75" font-size="14" font-weight="bold">B(1, 4)</text>
  
  <!-- Distance line -->
  <line x1="80" y1="260" x2="300" y2="80" stroke="green" stroke-width="2" stroke-dasharray="5,5"/>
  
  <!-- Right angle indicators -->
  <path d="M 80 260 L 80 80 L 300 80" stroke="gray" stroke-width="1" fill="none"/>
  <path d="M 80 260 L 300 260" stroke="gray" stroke-width="1" fill="none"/>
  
  <!-- Distance formula -->
  <text x="150" y="180" font-size="12" fill="green">AB = √[(1-(-3))² + (4-(-1))²]</text>
  <text x="170" y="200" font-size="12" fill="green">AB = √[16 + 25] = √41 ≈ 6.4</text>
</svg>

**Contoh:** Jarak antara A(-3, -1) dan B(1, 4)

**Pengiraan:**
\[ AB = \sqrt{(1-(-3))^2 + (4-(-1))^2} \]
\[ AB = \sqrt{4^2 + 5^2} = \sqrt{41} \approx 6.4 \text{ unit} \]

## Diagram 3: Titik Tengah

<svg viewBox="0 0 400 400" xmlns="http://www.w3.org/2000/svg">
  <!-- Grid lines -->
  <defs>
    <pattern id="grid" width="20" height="20" patternUnits="userSpaceOnUse">
      <path d="M 20 0 L 0 0 0 20" fill="none" stroke="#e0e0e0" stroke-width="0.5"/>
    </pattern>
  </defs>
  <rect width="400" height="400" fill="url(#grid)"/>
  
  <!-- Axes -->
  <line x1="0" y1="200" x2="400" y2="200" stroke="black" stroke-width="2"/>
  <line x1="200" y1="0" x2="200" y2="400" stroke="black" stroke-width="2"/>
  
  <!-- Points A and B -->
  <circle cx="80" cy="60" r="5" fill="red"/>
  <circle cx="320" cy="180" r="5" fill="blue"/>
  
  <!-- Midpoint M -->
  <circle cx="200" cy="120" r="6" fill="green" stroke="black" stroke-width="2"/>
  
  <!-- Labels -->
  <text x="85" y="55" font-size="14" font-weight="bold">A(-2, 6)</text>
  <text x="325" y="175" font-size="14" font-weight="bold">B(4, 2)</text>
  <text x="205" y="115" font-size="14" font-weight="bold" fill="green">M(1, 4)</text>
  
  <!-- Lines connecting points -->
  <line x1="80" y1="60" x2="320" y2="180" stroke="gray" stroke-width="1" stroke-dasharray="3,3"/>
  <line x1="80" y1="60" x2="200" y2="120" stroke="orange" stroke-width="1"/>
  <line x1="320" y1="180" x2="200" y2="120" stroke="orange" stroke-width="1"/>
  
  <!-- Midpoint formula -->
  <text x="150" y="90" font-size="12" fill="orange">M = ((-2+4)/2, (6+2)/2)</text>
  <text x="170" y="110" font-size="12" fill="orange">M = (1, 4)</text>
</svg>

**Contoh:** Titik tengah antara A(-2, 6) dan B(4, 2)

**Pengiraan:**
\[ M\left( \frac{-2+4}{2}, \frac{6+2}{2} \right) = M(1,4) \]

## Diagram 4: Segi Tiga

<svg viewBox="0 0 400 400" xmlns="http://www.w3.org/2000/svg">
  <!-- Grid lines -->
  <defs>
    <pattern id="grid" width="20" height="20" patternUnits="userSpaceOnUse">
      <path d="M 20 0 L 0 0 0 20" fill="none" stroke="#e0e0e0" stroke-width="0.5"/>
    </pattern>
  </defs>
  <rect width="400" height="400" fill="url(#grid)"/>
  
  <!-- Axes -->
  <line x1="0" y1="200" x2="400" y2="200" stroke="black" stroke-width="2"/>
  <line x1="200" y1="0" x2="200" y2="400" stroke="black" stroke-width="2"/>
  
  <!-- Triangle points -->
  <circle cx="120" cy="200" r="5" fill="red"/>
  <circle cx="320" cy="200" r="5" fill="blue"/>
  <circle cx="240" cy="80" r="5" fill="green"/>
  
  <!-- Triangle -->
  <polygon points="120,200 320,200 240,80" fill="rgba(255,255,0,0.2)" stroke="black" stroke-width="2"/>
  
  <!-- Labels -->
  <text x="125" y="195" font-size="14" font-weight="bold">A(-1,0)</text>
  <text x="325" y="195" font-size="14" font-weight="bold">B(4,0)</text>
  <text x="245" y="75" font-size="14" font-weight="bold">C(2,5)</text>
  
  <!-- Side labels -->
  <text x="220" y="190" font-size="12">AB = 5</text>
  <text x="280" y="130" font-size="12">BC ≈ 5.39</text>
  <text x="160" y="130" font-size="12">AC ≈ 5.83</text>
</svg>

**Contoh:** Segi tiga ABC dengan A(-1,0), B(4,0), C(2,5)

**Ciri-ciri:**
- AB = 5 unit
- BC = \(\sqrt{(4-2)^2 + (0-5)^2} = \sqrt{29} \approx 5.39\)
- AC = \(\sqrt{(2-(-1))^2 + (5-0)^2} = \sqrt{34} \approx 5.83\)
- Perimeter = 5 + 5.39 + 5.83 = 16.22 unit

## Diagram 5: Segi Empat Tepat

<svg viewBox="0 0 400 400" xmlns="http://www.w3.org/2000/svg">
  <!-- Grid lines -->
  <defs>
    <pattern id="grid" width="20" height="20" patternUnits="userSpaceOnUse">
      <path d="M 20 0 L 0 0 0 20" fill="none" stroke="#e0e0e0" stroke-width="0.5"/>
    </pattern>
  </defs>
  <rect width="400" height="400" fill="url(#grid)"/>
  
  <!-- Axes -->
  <line x1="0" y1="200" x2="400" y2="200" stroke="black" stroke-width="2"/>
  <line x1="200" y1="0" x2="200" y2="400" stroke="black" stroke-width="2"/>
  
  <!-- Rectangle points -->
  <circle cx="120" cy="200" r="5" fill="red"/>
  <circle cx="280" cy="200" r="5" fill="blue"/>
  <circle cx="280" cy="80" r="5" fill="green"/>
  <circle cx="120" cy="80" r="5" fill="orange"/>
  
  <!-- Rectangle -->
  <polygon points="120,200 280,200 280,80 120,80" fill="rgba(0,255,0,0.2)" stroke="black" stroke-width="2"/>
  
  <!-- Diagonal -->
  <line x1="120" y1="200" x2="280" y2="80" stroke="purple" stroke-width="2" stroke-dasharray="5,5"/>
  
  <!-- Labels -->
  <text x="125" y="195" font-size="14" font-weight="bold">A(-2,0)</text>
  <text x="285" y="195" font-size="14" font-weight="bold">B(2,0)</text>
  <text x="285" y="75" font-size="14" font-weight="bold">C(2,6)</text>
  <text x="125" y="75" font-size="14" font-weight="bold">D(-2,6)</text>
  
  <!-- Dimension labels -->
  <text x="200" y="190" font-size="12">Panjang = 4</text>
  <text x="290" y="140" font-size="12">Lebar = 6</text>
  <text x="190" y="140" font-size="12" fill="purple">Pepenjuru ≈ 7.21</text>
</svg>

**Contoh:** Segi empat tepat ABCD dengan A(-2,0), B(2,0), C(2,6), D(-2,6)

**Ciri-ciri:**
- Panjang = 4 unit
- Lebar = 6 unit
- Luas = 24 unit persegi
- Pepenjuru = \(\sqrt{4^2 + 6^2} = \sqrt{52} = 2\sqrt{13} \approx 7.21\)

## Diagram 6: Segi Empat Selari

<svg viewBox="0 0 400 400" xmlns="http://www.w3.org/2000/svg">
  <!-- Grid lines -->
  <defs>
    <pattern id="grid" width="20" height="20" patternUnits="userSpaceOnUse">
      <path d="M 20 0 L 0 0 0 20" fill="none" stroke="#e0e0e0" stroke-width="0.5"/>
    </pattern>
  </defs>
  <rect width="400" height="400" fill="url(#grid)"/>
  
  <!-- Axes -->
  <line x1="0" y1="200" x2="400" y2="200" stroke="black" stroke-width="2"/>
  <line x1="200" y1="0" x2="200" y2="400" stroke="black" stroke-width="2"/>
  
  <!-- Parallelogram points -->
  <circle cx="100" cy="160" r="5" fill="red"/>
  <circle cx="200" cy="120" r="5" fill="blue"/>
  <circle cx="300" cy="200" r="5" fill="green"/>
  <circle cx="200" cy="240" r="5" fill="orange"/>
  
  <!-- Parallelogram -->
  <polygon points="100,160 200,120 300,200 200,240" fill="rgba(255,165,0,0.2)" stroke="black" stroke-width="2"/>
  
  <!-- Labels -->
  <text x="105" y="155" font-size="14" font-weight="bold">A(-2,2)</text>
  <text x="205" y="115" font-size="14" font-weight="bold">B(0,4)</text>
  <text x="305" y="195" font-size="14" font-weight="bold">C(4,0)</text>
  <text x="205" y="255" font-size="14" font-weight="bold">D(0,-2)</text>
  
  <!-- Diagonals -->
  <line x1="100" y1="160" x2="300" y2="200" stroke="purple" stroke-width="1" stroke-dasharray="5,5"/>
  <line x1="200" y1="120" x2="200" y2="240" stroke="purple" stroke-width="1" stroke-dasharray="5,5"/>
  
  <!-- Midpoint intersection -->
  <circle cx="200" cy="180" r="3" fill="purple"/>
  <text x="205" y="175" font-size="10" fill="purple">M(0,1)</text>
</svg>

**Contoh:** Segi empat selari ABCD dengan A(-2,2), B(0,4), C(4,0), D(0,-2)

**Ciri-ciri:**
- AB = CD = \(\sqrt{(0-(-2))^2 + (4-2)^2} = \sqrt{8} \approx 2.83\)
- AD = BC = \(\sqrt{(0-(-2))^2 + (-2-2)^2} = \sqrt{20} \approx 4.47\)
- Luas = 12 unit persegi
- Pepenjuru berpotongan di titik tengah M(0,1)

## Diagram 7: Aplikasi Dunia Sebenar

**Contoh:** Lokasi Azri

**Jarak Perjalanan:**
- Rumah ke sekolah: 3 km
- Sekolah ke masjid: \(\sqrt{(-1-0)^2 + (2-0)^2} = \sqrt{5} \approx 2.24\) km
- Masjid ke kedai: \(\sqrt{(2-(-1))^2 + (-1-2)^2} = \sqrt{18} \approx 4.24\) km
- Jumlah jarak: 9.48 km
