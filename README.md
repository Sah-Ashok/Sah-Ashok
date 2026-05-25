<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 860 1080" width="860" height="1080">
  <defs>
    <linearGradient id="headerBg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#1e1b4b"/>
      <stop offset="50%" stop-color="#312e81"/>
      <stop offset="100%" stop-color="#4c1d95"/>
    </linearGradient>
    <linearGradient id="nameLine" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#818cf8"/>
      <stop offset="100%" stop-color="#c084fc"/>
    </linearGradient>
    <linearGradient id="avatarRing" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#818cf8"/>
      <stop offset="100%" stop-color="#c084fc"/>
    </linearGradient>
    <linearGradient id="bodyBg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#f8fafc"/>
      <stop offset="100%" stop-color="#f1f5f9"/>
    </linearGradient>
    <linearGradient id="codeCardBg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0f172a"/>
      <stop offset="100%" stop-color="#1e293b"/>
    </linearGradient>
    <filter id="cardShadow">
      <feDropShadow dx="0" dy="2" stdDeviation="6" flood-color="#6366f1" flood-opacity="0.12"/>
    </filter>
    <filter id="avatarGlow">
      <feDropShadow dx="0" dy="0" stdDeviation="10" flood-color="#818cf8" flood-opacity="0.6"/>
    </filter>
    <filter id="softShadow">
      <feDropShadow dx="0" dy="3" stdDeviation="8" flood-color="#000" flood-opacity="0.08"/>
    </filter>
    <style>
      @keyframes blink { 0%,100%{opacity:1} 50%{opacity:0.3} }
      .blink { animation: blink 2s infinite; }
    </style>
  </defs>

  <!-- ══════════════════════════════════════════ -->
  <!--  BACKGROUND                                -->
  <!-- ══════════════════════════════════════════ -->
  <rect width="860" height="1080" fill="url(#bodyBg)" rx="16"/>

  <!-- decorative top-right orb -->
  <circle cx="820" cy="60" r="120" fill="#818cf8" opacity="0.06"/>
  <circle cx="40" cy="900" r="80" fill="#c084fc" opacity="0.06"/>

  <!-- ══════════════════════════════════════════ -->
  <!--  HEADER BANNER                             -->
  <!-- ══════════════════════════════════════════ -->
  <rect x="0" y="0" width="860" height="210" fill="url(#headerBg)" rx="16"/>
  <rect x="0" y="194" width="860" height="16" fill="url(#bodyBg)"/>

  <!-- dot pattern overlay in header -->
  <g fill="#ffffff" opacity="0.04">
    <circle cx="100" cy="40" r="60"/>
    <circle cx="760" cy="180" r="90"/>
    <circle cx="430" cy="-20" r="80"/>
  </g>

  <!-- Avatar ring -->
  <circle cx="108" cy="108" r="58" fill="url(#avatarRing)" filter="url(#avatarGlow)"/>
  <circle cx="108" cy="108" r="52" fill="#1e1b4b"/>
  <text x="108" y="122" text-anchor="middle" font-family="Georgia, serif" font-size="44" font-weight="900" fill="#818cf8">A</text>

  <!-- Name -->
  <text x="188" y="82" font-family="'Trebuchet MS', sans-serif" font-size="40" font-weight="900" fill="#ffffff" letter-spacing="0.5">Ashok Sah</text>

  <!-- Accent underline -->
  <rect x="188" y="90" width="220" height="3" rx="2" fill="url(#nameLine)"/>

  <!-- Subtitle -->
  <text x="190" y="118" font-family="'Trebuchet MS', sans-serif" font-size="14" fill="#a5b4fc" letter-spacing="3" font-weight="600">FULL STACK DEVELOPER</text>

  <!-- Info line -->
  <text x="190" y="146" font-family="'Trebuchet MS', sans-serif" font-size="12.5" fill="#c7d2fe">
    <tspan>📍 Rajkot, Gujarat, India</tspan>
    <tspan dx="14" fill="#6366f1">|</tspan>
    <tspan dx="14">🎓 BCA · RK University (CGPA 8.6)</tspan>
  </text>

  <!-- Social pill badges -->
  <g font-family="'Trebuchet MS', sans-serif" font-size="11.5" font-weight="700">
    <!-- Portfolio -->
    <rect x="190" y="160" width="90" height="26" rx="13" fill="#4f46e5" opacity="0.85"/>
    <text x="235" y="177" text-anchor="middle" fill="#ffffff">🌐 Portfolio</text>
    <!-- LinkedIn -->
    <rect x="290" y="160" width="90" height="26" rx="13" fill="#0077b5" opacity="0.9"/>
    <text x="335" y="177" text-anchor="middle" fill="#ffffff">in LinkedIn</text>
    <!-- LeetCode -->
    <rect x="390" y="160" width="90" height="26" rx="13" fill="#ffa116" opacity="0.9"/>
    <text x="435" y="177" text-anchor="middle" fill="#1c1c1c">⚡ LeetCode</text>
    <!-- Gmail -->
    <rect x="490" y="160" width="80" height="26" rx="13" fill="#ea4335" opacity="0.9"/>
    <text x="530" y="177" text-anchor="middle" fill="#ffffff">✉ Gmail</text>
  </g>

  <!-- Open to work badge top-right -->
  <rect x="698" y="84" width="138" height="32" rx="16" fill="#052e16" stroke="#22c55e" stroke-width="1.5"/>
  <circle cx="716" cy="100" r="5" fill="#22c55e" class="blink"/>
  <text x="766" y="105" text-anchor="middle" font-family="'Trebuchet MS', sans-serif" font-size="11.5" font-weight="700" fill="#22c55e">Open to Work</text>

  <!-- ══════════════════════════════════════════ -->
  <!--  CODE BLOCK — ABOUT                        -->
  <!-- ══════════════════════════════════════════ -->
  <rect x="30" y="218" width="800" height="148" rx="14" fill="url(#codeCardBg)" filter="url(#softShadow)"/>
  <!-- traffic dots -->
  <circle cx="52" cy="235" r="5" fill="#ff5f57"/>
  <circle cx="70" cy="235" r="5" fill="#febc2e"/>
  <circle cx="88" cy="235" r="5" fill="#28c840"/>
  <text x="106" y="239" font-family="monospace" font-size="10.5" fill="#475569">about.ts</text>

  <!-- code lines -->
  <g font-family="'Courier New', Courier, monospace" font-size="13">
    <text x="50" y="264"><tspan fill="#7c3aed">const </tspan><tspan fill="#e2e8f0">ashok </tspan><tspan fill="#f472b6">= </tspan><tspan fill="#e2e8f0">{</tspan></text>
    <text x="70" y="283"><tspan fill="#67e8f9">role</tspan><tspan fill="#94a3b8">: </tspan><tspan fill="#86efac">"Full Stack Developer"</tspan><tspan fill="#94a3b8">,</tspan></text>
    <text x="70" y="300"><tspan fill="#67e8f9">stack</tspan><tspan fill="#94a3b8">: </tspan><tspan fill="#86efac">["Node.js", "PostgreSQL", "Docker", "Kafka"]</tspan><tspan fill="#94a3b8">,</tspan></text>
    <text x="70" y="317"><tspan fill="#67e8f9">focus</tspan><tspan fill="#94a3b8">: </tspan><tspan fill="#86efac">"Microservices · Cloud · Android/Kotlin"</tspan><tspan fill="#94a3b8">,</tspan></text>
    <text x="70" y="334"><tspan fill="#67e8f9">goal</tspan><tspan fill="#94a3b8">: </tspan><tspan fill="#fbbf24">"First professional role 🚀"</tspan></text>
    <text x="50" y="351" fill="#e2e8f0">}</text>
  </g>

  <!-- ══════════════════════════════════════════ -->
  <!--  TECH STACK SECTION                        -->
  <!-- ══════════════════════════════════════════ -->
  <!-- Section heading -->
  <rect x="30" y="382" width="5" height="26" rx="3" fill="#6366f1"/>
  <text x="44" y="400" font-family="'Trebuchet MS', sans-serif" font-size="17" font-weight="800" fill="#1e293b">Tech Stack</text>

  <!-- Stack card -->
  <rect x="30" y="412" width="800" height="270" rx="14" fill="#ffffff" stroke="#e2e8f0" stroke-width="1.5" filter="url(#softShadow)"/>

  <!-- ── Row: Languages ── -->
  <text x="50" y="435" font-family="'Trebuchet MS', sans-serif" font-size="10" font-weight="700" fill="#94a3b8" letter-spacing="2">LANGUAGES</text>

  <!-- JS -->
  <rect x="50" y="440" width="52" height="52" rx="10" fill="#f7df1e"/>
  <text x="76" y="474" text-anchor="middle" font-family="monospace" font-size="22" font-weight="900" fill="#1c1c1c">JS</text>
  <!-- TS -->
  <rect x="112" y="440" width="52" height="52" rx="10" fill="#3178c6"/>
  <text x="138" y="474" text-anchor="middle" font-family="monospace" font-size="22" font-weight="900" fill="#fff">TS</text>
  <!-- C# -->
  <rect x="174" y="440" width="52" height="52" rx="10" fill="#9b4993"/>
  <text x="200" y="474" text-anchor="middle" font-family="monospace" font-size="20" font-weight="900" fill="#fff">C#</text>
  <!-- HTML -->
  <rect x="236" y="440" width="52" height="52" rx="10" fill="#e34c26"/>
  <text x="262" y="474" text-anchor="middle" font-family="monospace" font-size="14" font-weight="900" fill="#fff">HTML</text>
  <!-- CSS -->
  <rect x="298" y="440" width="52" height="52" rx="10" fill="#264de4"/>
  <text x="324" y="474" text-anchor="middle" font-family="monospace" font-size="16" font-weight="900" fill="#fff">CSS</text>
  <!-- Kotlin -->
  <rect x="360" y="440" width="52" height="52" rx="10" fill="#7f52ff"/>
  <text x="386" y="474" text-anchor="middle" font-family="monospace" font-size="12" font-weight="900" fill="#fff">KT</text>
  <!-- SQL -->
  <rect x="422" y="440" width="52" height="52" rx="10" fill="#336791"/>
  <text x="448" y="474" text-anchor="middle" font-family="monospace" font-size="14" font-weight="900" fill="#fff">SQL</text>

  <line x1="50" y1="504" x2="810" y2="504" stroke="#f1f5f9" stroke-width="1.5"/>

  <!-- ── Row: Backend ── -->
  <text x="50" y="522" font-family="'Trebuchet MS', sans-serif" font-size="10" font-weight="700" fill="#94a3b8" letter-spacing="2">BACKEND &amp; MESSAGING</text>

  <!-- Node -->
  <rect x="50" y="527" width="52" height="52" rx="10" fill="#339933"/>
  <text x="76" y="558" text-anchor="middle" font-family="monospace" font-size="11" font-weight="900" fill="#fff">Node</text>
  <!-- Express -->
  <rect x="112" y="527" width="52" height="52" rx="10" fill="#1c1c1c"/>
  <text x="138" y="558" text-anchor="middle" font-family="monospace" font-size="10" font-weight="900" fill="#fff">Expr</text>
  <!-- .NET -->
  <rect x="174" y="527" width="52" height="52" rx="10" fill="#512bd4"/>
  <text x="200" y="558" text-anchor="middle" font-family="monospace" font-size="11" font-weight="900" fill="#fff">.NET</text>
  <!-- Prisma -->
  <rect x="236" y="527" width="52" height="52" rx="10" fill="#0c344b"/>
  <text x="262" y="558" text-anchor="middle" font-family="monospace" font-size="10" font-weight="900" fill="#fff">Prisma</text>
  <!-- Kafka -->
  <rect x="298" y="527" width="52" height="52" rx="10" fill="#231f20"/>
  <text x="324" y="558" text-anchor="middle" font-family="monospace" font-size="11" font-weight="900" fill="#fff">Kafka</text>
  <!-- REST -->
  <rect x="360" y="527" width="52" height="52" rx="10" fill="#ff6c37"/>
  <text x="386" y="558" text-anchor="middle" font-family="monospace" font-size="11" font-weight="900" fill="#fff">REST</text>
  <!-- JWT -->
  <rect x="422" y="527" width="52" height="52" rx="10" fill="#d63aff"/>
  <text x="448" y="558" text-anchor="middle" font-family="monospace" font-size="13" font-weight="900" fill="#fff">JWT</text>

  <line x1="50" y1="591" x2="810" y2="591" stroke="#f1f5f9" stroke-width="1.5"/>

  <!-- ── Row: DB & DevOps ── -->
  <text x="50" y="609" font-family="'Trebuchet MS', sans-serif" font-size="10" font-weight="700" fill="#94a3b8" letter-spacing="2">DATABASES · CLOUD · DEVOPS</text>

  <!-- MongoDB -->
  <rect x="50" y="614" width="52" height="52" rx="10" fill="#47a248"/>
  <text x="76" y="645" text-anchor="middle" font-family="monospace" font-size="10" font-weight="900" fill="#fff">Mongo</text>
  <!-- PostgreSQL -->
  <rect x="112" y="614" width="52" height="52" rx="10" fill="#336791"/>
  <text x="138" y="645" text-anchor="middle" font-family="monospace" font-size="10" font-weight="900" fill="#fff">Postgr</text>
  <!-- MySQL -->
  <rect x="174" y="614" width="52" height="52" rx="10" fill="#00758f"/>
  <text x="200" y="645" text-anchor="middle" font-family="monospace" font-size="11" font-weight="900" fill="#fff">MySQL</text>
  <!-- Redis -->
  <rect x="236" y="614" width="52" height="52" rx="10" fill="#dc382d"/>
  <text x="262" y="645" text-anchor="middle" font-family="monospace" font-size="11" font-weight="900" fill="#fff">Redis</text>
  <!-- Docker -->
  <rect x="298" y="614" width="52" height="52" rx="10" fill="#2496ed"/>
  <text x="324" y="645" text-anchor="middle" font-family="monospace" font-size="10" font-weight="900" fill="#fff">Docker</text>
  <!-- Azure -->
  <rect x="360" y="614" width="52" height="52" rx="10" fill="#0089d6"/>
  <text x="386" y="645" text-anchor="middle" font-family="monospace" font-size="11" font-weight="900" fill="#fff">Azure</text>
  <!-- Linux -->
  <rect x="422" y="614" width="52" height="52" rx="10" fill="#fcc624"/>
  <text x="448" y="645" text-anchor="middle" font-family="monospace" font-size="11" font-weight="900" fill="#1c1c1c">Linux</text>
  <!-- Nginx -->
  <rect x="484" y="614" width="52" height="52" rx="10" fill="#009900"/>
  <text x="510" y="645" text-anchor="middle" font-family="monospace" font-size="11" font-weight="900" fill="#fff">Nginx</text>
  <!-- Git -->
  <rect x="546" y="614" width="52" height="52" rx="10" fill="#f05032"/>
  <text x="572" y="645" text-anchor="middle" font-family="monospace" font-size="14" font-weight="900" fill="#fff">Git</text>

  <!-- ══════════════════════════════════════════ -->
  <!--  PROJECTS SECTION                          -->
  <!-- ══════════════════════════════════════════ -->
  <rect x="30" y="698" width="5" height="26" rx="3" fill="#6366f1"/>
  <text x="44" y="716" font-family="'Trebuchet MS', sans-serif" font-size="17" font-weight="800" fill="#1e293b">Featured Projects</text>

  <!-- ── Project Card 1: RentLio ── -->
  <rect x="30" y="726" width="382" height="150" rx="14" fill="#ffffff" stroke="#e0e7ff" stroke-width="1.5" filter="url(#softShadow)"/>
  <rect x="30" y="726" width="382" height="6" rx="7" fill="#6366f1"/>
  <rect x="30" y="730" width="382" height="2" fill="#6366f1"/>
  <!-- icon circle -->
  <circle cx="58" cy="762" r="18" fill="#eef2ff"/>
  <text x="58" y="768" text-anchor="middle" font-size="16">🏠</text>
  <text x="86" y="758" font-family="'Trebuchet MS', sans-serif" font-size="15" font-weight="800" fill="#1e293b">RentLio</text>
  <text x="86" y="774" font-family="'Trebuchet MS', sans-serif" font-size="11" fill="#64748b">Rental Home Platform</text>
  <text x="44" y="800" font-family="'Trebuchet MS', sans-serif" font-size="11.5" fill="#475569">Connect home seekers with property providers.</text>
  <text x="44" y="816" font-family="'Trebuchet MS', sans-serif" font-size="11.5" fill="#475569">Role-based auth, listings, Azure deployment.</text>
  <!-- tech chips -->
  <g font-family="'Trebuchet MS', sans-serif" font-size="10" font-weight="700">
    <rect x="44" y="830" width="52" height="18" rx="9" fill="#e0e7ff"/>
    <text x="70" y="843" text-anchor="middle" fill="#4338ca">Node.js</text>
    <rect x="102" y="830" width="58" height="18" rx="9" fill="#dcfce7"/>
    <text x="131" y="843" text-anchor="middle" fill="#166534">MongoDB</text>
    <rect x="166" y="830" width="44" height="18" rx="9" fill="#dbeafe"/>
    <text x="188" y="843" text-anchor="middle" fill="#1d4ed8">Azure</text>
    <rect x="216" y="830" width="36" height="18" rx="9" fill="#fae8ff"/>
    <text x="234" y="843" text-anchor="middle" fill="#86198f">JWT</text>
  </g>
  <rect x="320" y="828" width="76" height="22" rx="11" fill="#f0fdf4" stroke="#22c55e" stroke-width="1.5"/>
  <text x="358" y="843" text-anchor="middle" font-family="'Trebuchet MS', sans-serif" font-size="10.5" font-weight="700" fill="#16a34a">Live ↗</text>

  <!-- ── Project Card 2: J&S Sofa ── -->
  <rect x="448" y="726" width="382" height="150" rx="14" fill="#ffffff" stroke="#ffe4e6" stroke-width="1.5" filter="url(#softShadow)"/>
  <rect x="448" y="726" width="382" height="6" rx="7" fill="#f43f5e"/>
  <rect x="448" y="730" width="382" height="2" fill="#f43f5e"/>
  <circle cx="476" cy="762" r="18" fill="#fff1f2"/>
  <text x="476" y="768" text-anchor="middle" font-size="16">🛋️</text>
  <text x="504" y="758" font-family="'Trebuchet MS', sans-serif" font-size="15" font-weight="800" fill="#1e293b">J&amp;S Sofa</text>
  <text x="504" y="774" font-family="'Trebuchet MS', sans-serif" font-size="11" fill="#64748b">E-Commerce Furniture Store</text>
  <text x="462" y="800" font-family="'Trebuchet MS', sans-serif" font-size="11.5" fill="#475569">Full-featured store with cart, orders, admin.</text>
  <text x="462" y="816" font-family="'Trebuchet MS', sans-serif" font-size="11.5" fill="#475569">Google OAuth, Redis cache, Razorpay payments.</text>
  <g font-family="'Trebuchet MS', sans-serif" font-size="10" font-weight="700">
    <rect x="462" y="830" width="52" height="18" rx="9" fill="#e0e7ff"/>
    <text x="488" y="843" text-anchor="middle" fill="#4338ca">Node.js</text>
    <rect x="520" y="830" width="44" height="18" rx="9" fill="#fee2e2"/>
    <text x="542" y="843" text-anchor="middle" fill="#b91c1c">Redis</text>
    <rect x="570" y="830" width="60" height="18" rx="9" fill="#fef9c3"/>
    <text x="600" y="843" text-anchor="middle" fill="#854d0e">Razorpay</text>
  </g>
  <rect x="738" y="828" width="76" height="22" rx="11" fill="#f0fdf4" stroke="#22c55e" stroke-width="1.5"/>
  <text x="776" y="843" text-anchor="middle" font-family="'Trebuchet MS', sans-serif" font-size="10.5" font-weight="700" fill="#16a34a">Live ↗</text>

  <!-- ── Project Card 3: Microservice ── -->
  <rect x="30" y="892" width="382" height="140" rx="14" fill="#ffffff" stroke="#ede9fe" stroke-width="1.5" filter="url(#softShadow)"/>
  <rect x="30" y="892" width="382" height="6" rx="7" fill="#8b5cf6"/>
  <rect x="30" y="896" width="382" height="2" fill="#8b5cf6"/>
  <circle cx="58" cy="927" r="18" fill="#f5f3ff"/>
  <text x="58" y="933" text-anchor="middle" font-size="16">⚡</text>
  <text x="86" y="923" font-family="'Trebuchet MS', sans-serif" font-size="14" font-weight="800" fill="#1e293b">Microservice Project</text>
  <text x="86" y="939" font-family="'Trebuchet MS', sans-serif" font-size="11" fill="#64748b">Event-Driven E-Commerce</text>
  <text x="44" y="963" font-family="'Trebuchet MS', sans-serif" font-size="11.5" fill="#475569">Product, Order &amp; Payment services via Kafka.</text>
  <text x="44" y="979" font-family="'Trebuchet MS', sans-serif" font-size="11.5" fill="#475569">Containerized with Docker Compose.</text>
  <g font-family="'Trebuchet MS', sans-serif" font-size="10" font-weight="700">
    <rect x="44" y="993" width="42" height="18" rx="9" fill="#fafafa" stroke="#e2e8f0" stroke-width="1"/>
    <text x="65" y="1006" text-anchor="middle" fill="#374151">Kafka</text>
    <rect x="92" y="993" width="48" height="18" rx="9" fill="#dbeafe"/>
    <text x="116" y="1006" text-anchor="middle" fill="#1d4ed8">Docker</text>
    <rect x="146" y="993" width="44" height="18" rx="9" fill="#e0f2fe"/>
    <text x="168" y="1006" text-anchor="middle" fill="#0369a1">MySQL</text>
  </g>
  <rect x="284" y="991" width="110" height="22" rx="11" fill="#f5f3ff" stroke="#8b5cf6" stroke-width="1.5"/>
  <text x="339" y="1006" text-anchor="middle" font-family="'Trebuchet MS', sans-serif" font-size="10.5" font-weight="700" fill="#7c3aed">GitHub ↗</text>

  <!-- ── Project Card 4: Exploria ── -->
  <rect x="448" y="892" width="382" height="140" rx="14" fill="#ffffff" stroke="#fef3c7" stroke-width="1.5" filter="url(#softShadow)"/>
  <rect x="448" y="892" width="382" height="6" rx="7" fill="#f59e0b"/>
  <rect x="448" y="896" width="382" height="2" fill="#f59e0b"/>
  <circle cx="476" cy="927" r="18" fill="#fffbeb"/>
  <text x="476" y="933" text-anchor="middle" font-size="16">✈️</text>
  <text x="504" y="923" font-family="'Trebuchet MS', sans-serif" font-size="14" font-weight="800" fill="#1e293b">Exploria</text>
  <text x="504" y="939" font-family="'Trebuchet MS', sans-serif" font-size="11" fill="#64748b">Tours &amp; Travel Booking</text>
  <text x="462" y="963" font-family="'Trebuchet MS', sans-serif" font-size="11.5" fill="#475569">Trip booking with Razorpay refundable payments.</text>
  <text x="462" y="979" font-family="'Trebuchet MS', sans-serif" font-size="11.5" fill="#475569">Admin panel, CRUD, email recovery.</text>
  <g font-family="'Trebuchet MS', sans-serif" font-size="10" font-weight="700">
    <rect x="462" y="993" width="52" height="18" rx="9" fill="#ede9fe"/>
    <text x="488" y="1006" text-anchor="middle" fill="#5b21b6">ASP.NET</text>
    <rect x="520" y="993" width="68" height="18" rx="9" fill="#fee2e2"/>
    <text x="554" y="1006" text-anchor="middle" fill="#991b1b">SQL Server</text>
    <rect x="594" y="993" width="60" height="18" rx="9" fill="#fef9c3"/>
    <text x="624" y="1006" text-anchor="middle" fill="#854d0e">Razorpay</text>
  </g>
  <rect x="702" y="991" width="110" height="22" rx="11" fill="#fffbeb" stroke="#f59e0b" stroke-width="1.5"/>
  <text x="757" y="1006" text-anchor="middle" font-family="'Trebuchet MS', sans-serif" font-size="10.5" font-weight="700" fill="#b45309">GitHub ↗</text>

  <!-- ══════════════════════════════════════════ -->
  <!--  FOOTER                                    -->
  <!-- ══════════════════════════════════════════ -->
  <rect x="0" y="1048" width="860" height="32" fill="url(#headerBg)" rx="0"/>
  <rect x="0" y="1064" width="860" height="16" fill="url(#headerBg)" rx="16"/>
  <text x="430" y="1068" text-anchor="middle" font-family="'Trebuchet MS', sans-serif" font-size="11.5" fill="#a5b4fc">sah.ashok.me@gmail.com  ·  github.com/Sah-Ashok  ·  ashok-sah.me</text>

</svg>
