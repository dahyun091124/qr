<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>EXER (엑써싸이즈) - 스마트 프로토타입 운동 & 제작 디지털 가이드</title>
  
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            exer: {
              navy: '#111738',
              navyDark: '#0b0f26',
              indigo: '#222d69',
              slate: '#475569',
              lime: '#b8f000',
              limeHover: '#a3d600',
              limeLight: '#f3fce0',
              cardBg: '#f8fafc'
            }
          },
          fontFamily: {
            sans: ['Pretendard', 'Inter', 'Noto Sans KR', 'sans-serif']
          }
        }
      }
    }
  </script>

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />

  <style>
    @import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard.css');

    body {
      font-family: 'Pretendard', sans-serif;
      background-color: #f1f5f9;
      color: #0f172a;
    }

    /* Custom Scrollbar */
    ::-webkit-scrollbar {
      width: 8px;
      height: 8px;
    }
    ::-webkit-scrollbar-track {
      background: #e2e8f0;
    }
    ::-webkit-scrollbar-thumb {
      background: #94a3b8;
      border-radius: 4px;
    }
    ::-webkit-scrollbar-thumb:hover {
      background: #64748b;
    }

    /* Custom Transitions */
    .tab-active {
      background-color: #111738 !important;
      color: #b8f000 !important;
      border-color: #111738 !important;
      box-shadow: 0 4px 12px rgba(17, 23, 56, 0.15);
    }

    .glass-nav {
      background: rgba(255, 255, 255, 0.95);
      backdrop-filter: blur(10px);
    }
  </style>
</head>
<body class="min-h-screen flex flex-col">

  <!-- HEADER / NAVIGATION -->
  <header class="sticky top-0 z-40 glass-nav border-b border-slate-200 shadow-sm">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex justify-between items-center h-20">
        
        <!-- BRAND LOGO (EXACT SVG RECREATION OF USER LOGO) -->
        <a href="#" class="flex items-center gap-3 group focus:outline-none" onclick="resetFilters()">
          <div class="h-14 w-auto flex items-center">
            <!-- Exact EXER Logo SVG -->
            <svg class="h-14 w-auto drop-shadow-sm transition-transform duration-200 group-hover:scale-105" viewBox="0 0 320 380" fill="none" xmlns="http://www.w3.org/2000/svg">
              <!-- Top Left Droplet -->
              <path d="M121 48C121 21.49 99.51 0 73 0C46.49 0 25 21.49 25 48C25 78 73 115 121 115C121 115 121 74.51 121 48Z" fill="#B8F000"/>
              <ellipse cx="129" cy="20" rx="9" ry="14" fill="#B8F000"/>
              
              <!-- 'Pine' Text -->
              <text x="145" y="60" fill="#B8F000" font-family="'Inter', sans-serif" font-weight="900" font-size="52" letter-spacing="-1">ine</text>
              
              <!-- Cap Block -->
              <rect x="131" y="78" width="102" height="28" rx="6" fill="#111738"/>
              
              <!-- Central EXER Main Block -->
              <g fill="#111738">
                <!-- Top Arc Header -->
                <path d="M102 114H262C273 114 282 123 282 134V152H82V134C82 123 91 114 102 114Z"/>
                
                <!-- Large 'E' / Left Outer Frame -->
                <path d="M98 152H178C194 152 208 165 208 181V212H150V268H200V288H98C88 288 80 280 80 270V170C80 160 88 152 98 152Z"/>
                
                <!-- Cross Diagonal 'X' -->
                <path d="M182 190L238 274C244 283 256 286 265 280C274 274 277 262 271 253L218 174C212 165 200 162 191 168C182 174 179 186 182 190Z"/>
                <path d="M236 174L174 266C168 275 171 287 180 293C189 299 201 296 207 287L266 200C272 191 269 179 260 173C251 167 239 170 236 174Z"/>
                
                <!-- Bottom 'Er' Segment -->
                <path d="M98 268H182V346C182 357 173 366 162 366H118C107 366 98 357 98 346V268Z"/>
                <path d="M136 292H168V312H136V292Z"/>
                <path d="M136 324H168V344H136V324Z"/>
              </g>
              
              <!-- Bottom Right Lime Splash -->
              <path d="M210 326C210 304 228 286 250 286C272 286 290 304 290 326C290 351 250 380 210 380C210 380 210 348 210 326Z" fill="#B8F000"/>
              <circle cx="228" cy="365" r="10" fill="#B8F000"/>
            </svg>
          </div>
          <div class="hidden sm:flex flex-col border-l border-slate-200 pl-3">
            <span class="text-xl font-black tracking-tight text-exer-navy leading-none">EXER</span>
            <span class="text-xs text-slate-500 font-semibold tracking-wide">엑써싸이즈 디바이스 디지털 가이드</span>
          </div>
        </a>

        <!-- QUICK UTILITY ACTIONS -->
        <div class="flex items-center gap-2 sm:gap-3">
          <button onclick="openTimerModal()" class="inline-flex items-center gap-2 px-3 py-2 sm:px-4 sm:py-2.5 rounded-lg bg-slate-100 text-exer-navy hover:bg-slate-200 font-medium text-xs sm:text-sm transition-all border border-slate-200">
            <i class="fa-solid fa-stopwatch text-exer-indigo"></i>
            <span>휴식 타이머</span>
          </button>
          
          <button onclick="openQRModal()" class="inline-flex items-center gap-2 px-3 py-2 sm:px-4 sm:py-2.5 rounded-lg bg-exer-navy text-white hover:bg-exer-indigo font-medium text-xs sm:text-sm transition-all shadow-sm">
            <i class="fa-solid fa-qrcode text-exer-lime"></i>
            <span class="hidden md:inline">패키지 QR코드</span>
          </button>
        </div>

      </div>
    </div>
  </header>

  <!-- HERO BANNER -->
  <section class="bg-gradient-to-r from-exer-navyDark via-exer-navy to-exer-indigo text-white py-10 px-4 sm:px-6 lg:px-8 shadow-inner">
    <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-start md:items-center gap-6">
      <div class="space-y-2">
        <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-exer-lime/20 border border-exer-lime/30 text-exer-lime text-xs font-semibold">
          <i class="fa-solid fa-microchip text-xs"></i>
          <span>PROTOTYPE DEVICE GUIDE SYSTEM v2.4</span>
        </div>
        <h1 class="text-2xl sm:text-3xl lg:text-4xl font-extrabold tracking-tight">
          사용자 맞춤형 프로토타입 디바이스 가이드
        </h1>
        <p class="text-slate-300 text-sm sm:text-base max-w-2xl leading-relaxed">
          올바른 자극과 부상 방지를 위한 <strong class="text-exer-lime font-bold">운동 가이드</strong>와 thermo-plastic 커스텀 성형을 위한 <strong class="text-white font-bold">제작 가이드</strong>를 명확하게 구분하여 제공합니다.
        </p>
      </div>

      <!-- Quick Search Input -->
      <div class="w-full md:w-80 relative">
        <i class="fa-solid fa-magnifying-glass absolute left-3.5 top-1/2 -translate-y-1/2 text-slate-400 text-sm"></i>
        <input type="text" id="searchInput" oninput="handleSearch()" placeholder="가이드 내용 또는 부위 검색..." 
          class="w-full pl-10 pr-4 py-2.5 bg-white/10 border border-white/20 rounded-xl text-white placeholder-slate-400 text-sm focus:outline-none focus:ring-2 focus:ring-exer-lime transition-all">
      </div>
    </div>
  </section>

  <!-- MAIN NAVIGATION TABS & FILTERS -->
  <main class="flex-1 max-w-7xl w-full mx-auto px-4 sm:px-6 lg:px-8 py-8 space-y-8">
    
    <!-- PRIMARY TYPE SWITCHER: WORKOUT vs ASSEMBLY -->
    <div class="bg-white p-2 rounded-2xl border border-slate-200 shadow-sm flex flex-col sm:flex-row items-stretch justify-between gap-3">
      
      <!-- Main Guide Type Tabs -->
      <div class="grid grid-cols-2 gap-2 w-full sm:w-auto">
        <button id="btn-tab-workout" onclick="switchGuideType('workout')" 
          class="tab-active flex items-center justify-center gap-2 px-6 py-3 rounded-xl font-bold text-sm sm:text-base border border-transparent transition-all">
          <i class="fa-solid fa-person-running text-lg"></i>
          <span>운동 가이드 (Workout)</span>
        </button>
        
        <button id="btn-tab-diy" onclick="switchGuideType('diy')" 
          class="flex items-center justify-center gap-2 px-6 py-3 rounded-xl font-bold text-sm sm:text-base border border-transparent bg-slate-100 text-slate-700 hover:bg-slate-200 transition-all">
          <i class="fa-solid fa-wrench text-lg"></i>
          <span>제작 가이드 (DIY Assembly)</span>
        </button>
      </div>

      <!-- Product Filter Pills -->
      <div class="flex items-center gap-1.5 overflow-x-auto pb-1 sm:pb-0 scrollbar-none">
        <span class="text-xs font-semibold text-slate-400 uppercase tracking-wider px-2 hidden lg:inline">제품:</span>
        <button onclick="filterProduct('all')" id="filter-all" class="px-3 py-1.5 rounded-lg text-xs font-bold transition-all bg-exer-navy text-white">
          전체
        </button>
        <button onclick="filterProduct('p1')" id="filter-p1" class="px-3 py-1.5 rounded-lg text-xs font-medium text-slate-600 hover:bg-slate-100 transition-all whitespace-nowrap">
          01. 발지압 & 상체 밴드
        </button>
        <button onclick="filterProduct('p2')" id="filter-p2" class="px-3 py-1.5 rounded-lg text-xs font-medium text-slate-600 hover:bg-slate-100 transition-all whitespace-nowrap">
          02. 미세돌기 근육 롤러
        </button>
        <button onclick="filterProduct('p3')" id="filter-p3" class="px-3 py-1.5 rounded-lg text-xs font-medium text-slate-600 hover:bg-slate-100 transition-all whitespace-nowrap">
          03. 커스텀 그립 & 펙덱 플라이
        </button>
      </div>

    </div>

    <!-- GUIDE NOTICE BAR -->
    <div id="guideNotice" class="p-4 rounded-xl bg-slate-800 text-white flex items-start gap-3 border-l-4 border-exer-lime">
      <i class="fa-solid fa-circle-info text-exer-lime text-xl mt-0.5"></i>
      <div class="text-xs sm:text-sm text-slate-300 leading-relaxed">
        <strong id="noticeTitle" class="text-white font-bold block text-sm mb-0.5">운동 가이드 모드 활성화 중</strong>
        <span id="noticeDesc">동작 수행에 필요한 올바른 자세, 타겟 근육 자극 범위, 이동 방향 벡터 및 추천 세트수를 확인하세요.</span>
      </div>
    </div>

    <!-- CARDS CONTAINER GRID -->
    <div id="guidesGrid" class="grid grid-cols-1 lg:grid-cols-3 gap-6 sm:gap-8">
      <!-- Dynamic Javascript Content Injected Here -->
    </div>

    <!-- NO RESULTS STATE -->
    <div id="noResults" class="hidden text-center py-16 bg-white rounded-2xl border border-dashed border-slate-300">
      <i class="fa-solid fa-magnifying-glass-chart text-4xl text-slate-300 mb-3"></i>
      <p class="text-base font-bold text-slate-700">검색 결과가 없습니다.</p>
      <p class="text-xs text-slate-500 mt-1">다른 키워드로 검색하거나 필터를 변경해 보세요.</p>
    </div>

  </main>

  <!-- FOOTER -->
  <footer class="bg-exer-navyDark text-slate-400 py-12 border-t border-slate-800 mt-12">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 space-y-6">
      <div class="flex flex-col md:flex-row justify-between items-start md:items-center gap-6 border-b border-slate-800 pb-8">
        
        <div class="flex items-center gap-3">
          <div class="bg-white/10 p-2 rounded-xl">
            <!-- Footer Mini Logo -->
            <svg class="h-8 w-auto" viewBox="0 0 320 380" fill="none">
              <path d="M121 48C121 21.49 99.51 0 73 0C46.49 0 25 21.49 25 48C25 78 73 115 121 115Z" fill="#B8F000"/>
              <text x="145" y="60" fill="#B8F000" font-family="'Inter', sans-serif" font-weight="900" font-size="52">ine</text>
              <rect x="131" y="78" width="102" height="28" fill="#FFFFFF"/>
              <g fill="#FFFFFF">
                <path d="M98 152H178C194 152 208 165 208 181V212H150V268H200V288H98V152Z"/>
                <path d="M182 190L238 274C244 283 256 286 265 280C274 274 277 262 271 253L218 174Z"/>
              </g>
              <path d="M210 326C210 304 228 286 250 286C272 286 290 304 290 326C290 351 250 380 210 380Z" fill="#B8F000"/>
            </svg>
          </div>
          <div>
            <p class="text-white font-bold text-base">EXER (엑써싸이즈)</p>
            <p class="text-xs text-slate-500">Prototype Custom Exercise Systems</p>
          </div>
        </div>

        <div class="text-xs text-slate-400 space-y-1">
          <p><i class="fa-solid fa-shield-halved text-exer-lime mr-1"></i> 본 가이드는 EXER 맞춤형 운동기구 전용 가이드 시스템입니다.</p>
          <p><i class="fa-solid fa-triangle-exclamation text-amber-400 mr-1"></i> Polymorph 커스텀 성형 시 60~70°C 온수 사용에 유의하세요.</p>
        </div>
      </div>

      <div class="flex flex-col sm:flex-row justify-between items-center text-xs text-slate-500 gap-4">
        <p>&copy; 2026 EXER Inc. All rights reserved.</p>
        <div class="flex gap-4">
          <a href="#" class="hover:text-white transition-colors">이용약관</a>
          <a href="#" class="hover:text-white transition-colors">개인정보처리방침</a>
          <a href="#" class="hover:text-white transition-colors">고객지원 센터</a>
        </div>
      </div>
    </div>
  </footer>

  <!-- DETAIL MODAL -->
  <div id="detailModal" class="fixed inset-0 bg-slate-900/80 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4 overflow-y-auto">
    <div class="bg-white rounded-2xl max-w-3xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
      
      <!-- Modal Header -->
      <div id="modalHeader" class="sticky top-0 bg-exer-navy text-white px-6 py-4 flex justify-between items-center border-b border-slate-700 z-10">
        <div>
          <span id="modalCategory" class="text-xs font-bold text-exer-lime uppercase tracking-wider block">카테고리</span>
          <h3 id="modalTitle" class="text-lg font-bold text-white">가이드 상세 제목</h3>
        </div>
        <button onclick="closeModal()" class="w-9 h-9 flex items-center justify-center rounded-full bg-white/10 hover:bg-white/20 text-white transition-all">
          <i class="fa-solid fa-xmark text-lg"></i>
        </button>
      </div>

      <!-- Modal Body -->
      <div id="modalBody" class="p-6 space-y-6">
        <!-- Injected Content -->
      </div>

      <!-- Modal Footer -->
      <div class="bg-slate-50 px-6 py-4 border-t border-slate-200 flex justify-end gap-3">
        <button onclick="closeModal()" class="px-5 py-2.5 rounded-xl bg-slate-200 text-slate-800 font-bold text-xs sm:text-sm hover:bg-slate-300 transition-all">
          닫기
        </button>
      </div>
    </div>
  </div>

  <!-- REST TIMER MODAL -->
  <div id="timerModal" class="fixed inset-0 bg-slate-900/80 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
    <div class="bg-white rounded-2xl max-w-md w-full p-6 shadow-2xl text-center space-y-6 border border-slate-200">
      
      <div class="flex justify-between items-center border-b border-slate-100 pb-3">
        <div class="flex items-center gap-2">
          <i class="fa-solid fa-stopwatch text-exer-indigo text-xl"></i>
          <h3 class="font-bold text-slate-900 text-base">운동 세트간 휴식 타이머</h3>
        </div>
        <button onclick="closeTimerModal()" class="text-slate-400 hover:text-slate-600">
          <i class="fa-solid fa-xmark text-lg"></i>
        </button>
      </div>

      <div class="bg-slate-900 rounded-2xl p-6 text-white space-y-2">
        <div id="timerDisplay" class="text-5xl font-mono font-bold tracking-wider text-exer-lime">00:45</div>
        <p class="text-xs text-slate-400">추천 권장 휴식 시간</p>
      </div>

      <div class="grid grid-cols-3 gap-2">
        <button onclick="setTimerSec(30)" class="py-2 bg-slate-100 hover:bg-slate-200 font-bold text-xs rounded-lg text-slate-700">30초</button>
        <button onclick="setTimerSec(45)" class="py-2 bg-slate-100 hover:bg-slate-200 font-bold text-xs rounded-lg text-slate-700">45초</button>
        <button onclick="setTimerSec(60)" class="py-2 bg-slate-100 hover:bg-slate-200 font-bold text-xs rounded-lg text-slate-700">60초</button>
      </div>

      <div class="flex gap-3">
        <button id="timerStartBtn" onclick="toggleTimer()" class="flex-1 py-3 bg-exer-navy text-exer-lime font-bold rounded-xl hover:bg-exer-indigo transition-all shadow-md">
          <i class="fa-solid fa-play mr-1"></i> 시작
        </button>
        <button onclick="resetTimer()" class="px-4 py-3 bg-slate-200 text-slate-700 font-bold rounded-xl hover:bg-slate-300 transition-all">
          <i class="fa-solid fa-rotate-right"></i>
        </button>
      </div>

    </div>
  </div>

  <!-- PACKAGING QR CODE MODAL -->
  <div id="qrModal" class="fixed inset-0 bg-slate-900/80 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
    <div class="bg-white rounded-2xl max-w-md w-full p-6 shadow-2xl text-center space-y-5 border border-slate-200">
      
      <div class="flex justify-between items-center border-b border-slate-100 pb-3">
        <div class="flex items-center gap-2">
          <i class="fa-solid fa-qrcode text-exer-indigo text-xl"></i>
          <h3 class="font-bold text-slate-900 text-base">제품 패키지 첨부용 QR코드</h3>
        </div>
        <button onclick="closeQRModal()" class="text-slate-400 hover:text-slate-600">
          <i class="fa-solid fa-xmark text-lg"></i>
        </button>
      </div>

      <p class="text-xs text-slate-600">
        시제품 박스 또는 가이드 보드에 부착할 디지털 가이드 QR코드입니다.
      </p>

      <div class="bg-slate-50 p-6 rounded-2xl border border-slate-200 flex flex-col items-center justify-center space-y-3">
        <!-- Generated Clean SVG QR Mock -->
        <svg class="w-44 h-44 bg-white p-2 rounded-xl shadow-inner border border-slate-200" viewBox="0 0 100 100">
          <rect x="0" y="0" width="100" height="100" fill="#ffffff"/>
          <!-- Position Markers -->
          <rect x="10" y="10" width="25" height="25" fill="#111738"/>
          <rect x="15" y="15" width="15" height="15" fill="#ffffff"/>
          <rect x="18" y="18" width="9" height="9" fill="#111738"/>

          <rect x="65" y="10" width="25" height="25" fill="#111738"/>
          <rect x="70" y="15" width="15" height="15" fill="#ffffff"/>
          <rect x="73" y="18" width="9" height="9" fill="#111738"/>

          <rect x="10" y="65" width="25" height="25" fill="#111738"/>
          <rect x="15" y="70" width="15" height="15" fill="#ffffff"/>
          <rect x="18" y="73" width="9" height="9" fill="#111738"/>

          <!-- Pattern Blocks -->
          <rect x="40" y="10" width="8" height="8" fill="#111738"/>
          <rect x="50" y="18" width="8" height="8" fill="#111738"/>
          <rect x="42" y="30" width="16" height="8" fill="#111738"/>
          <rect x="10" y="42" width="12" height="12" fill="#111738"/>
          <rect x="30" y="45" width="10" height="10" fill="#b8f000"/>
          <rect x="48" y="48" width="14" height="14" fill="#111738"/>
          <rect x="68" y="42" width="22" height="8" fill="#111738"/>
          <rect x="78" y="55" width="12" height="12" fill="#111738"/>
          <rect x="42" y="70" width="8" height="20" fill="#111738"/>
          <rect x="55" y="68" width="12" height="12" fill="#b8f000"/>
          <rect x="72" y="72" width="18" height="18" fill="#111738"/>
        </svg>
        <span class="text-xs font-mono font-bold text-exer-navy">https://exer-guide.prototype/v2</span>
      </div>

      <button onclick="alert('QR코드가 인쇄용 이미지로 저장되었습니다.')" class="w-full py-3 bg-exer-navy text-white font-bold text-xs sm:text-sm rounded-xl hover:bg-exer-indigo transition-all">
        <i class="fa-solid fa-download mr-1"></i> QR코드 이미지 다운로드
      </button>

    </div>
  </div>


  <!-- APPLICATION DATA & LOGIC -->
  <script>
    // State management
    let currentGuideType = 'workout'; // 'workout' or 'diy'
    let currentProductFilter = 'all'; // 'all', 'p1', 'p2', 'p3'
    let searchQuery = '';

    // DATA BASE FOR 3 PROTOTYPE PRODUCTS
    const guideData = [
      // -------------------------------------------------------------
      // PRODUCT 01: SOLE-FLEX DUAL TRAINER
      // -------------------------------------------------------------
      {
        id: 'p1_w1',
        productId: 'p1',
        productName: '01. SOLE-FLEX DUAL TRAINER',
        type: 'workout',
        title: '스탠딩 발지압 & 튜빙 로잉 (Seated & Standing Sole Row)',
        badge: '전신 & 지압 순환',
        targetMuscles: ['등 (광배근)', '승모근 하부', '족저근막 스티뮬레이션'],
        difficulty: '초급 / 중급',
        reps: '15~20회 x 3세트',
        desc: '특수 발지압 돌기판 위에 균형을 잡고 서서 탄성 밴드를 이용해 상체 노젓기(Rowing) 동작을 수행합니다.',
        svgDiagram: `
          <svg viewBox="0 0 400 220" class="w-full h-auto bg-slate-900 rounded-xl">
            <!-- Grid lines -->
            <pattern id="grid1" width="20" height="20" patternUnits="userSpaceOnUse">
              <path d="M 20 0 L 0 0 0 20" fill="none" stroke="#1e293b" stroke-width="1"/>
            </pattern>
            <rect width="400" height="220" fill="url(#grid1)" />

            <!-- Sole Plate Graphic -->
            <rect x="80" y="170" width="120" height="20" rx="4" fill="#334155" stroke="#94a3b8" stroke-width="2"/>
            <!-- Acupressure Nodes -->
            <circle cx="95" cy="166" r="3" fill="#b8f000"/>
            <circle cx="110" cy="166" r="3" fill="#b8f000"/>
            <circle cx="125" cy="166" r="3" fill="#b8f000"/>
            <circle cx="140" cy="166" r="3" fill="#b8f000"/>
            <circle cx="155" cy="166" r="3" fill="#b8f000"/>
            <circle cx="170" cy="166" r="3" fill="#b8f000"/>
            <circle cx="185" cy="166" r="3" fill="#b8f000"/>

            <!-- Human Pose Vector (Standing & Rowing) -->
            <!-- Head -->
            <circle cx="140" cy="50" r="14" fill="#64748b"/>
            <!-- Spine -->
            <path d="M140 64 L140 120 L125 170" fill="none" stroke="#38bdf8" stroke-width="6" stroke-linecap="round"/>
            <!-- Back Leg -->
            <path d="M140 120 L155 170" fill="none" stroke="#38bdf8" stroke-width="6" stroke-linecap="round"/>
            
            <!-- Arm Pulling Vector -->
            <!-- Torso Back muscles highlight -->
            <path d="M135 75 C120 85 120 105 135 115" fill="none" stroke="#f43f5e" stroke-width="8" opacity="0.8"/>
            
            <!-- Band Pull Vector Arrows -->
            <path d="M190 130 L135 90" fill="none" stroke="#b8f000" stroke-width="4" stroke-dasharray="4,4"/>
            <polygon points="135,90 145,92 142,98" fill="#b8f000"/>

            <path d="M190 170 L190 130" fill="none" stroke="#f59e0b" stroke-width="4"/>
            <!-- Band Handle -->
            <circle cx="135" cy="90" r="6" fill="#b8f000"/>

            <!-- Muscle Target Overlay Label -->
            <rect x="10" y="10" width="130" height="26" rx="6" fill="#1e293b" opacity="0.9"/>
            <text x="20" y="27" fill="#b8f000" font-size="11" font-weight="bold">타겟: 광배근 & 족저근</text>

            <text x="240" y="100" fill="#ffffff" font-size="12" font-weight="bold">수행 지침:</text>
            <text x="240" y="120" fill="#94a3b8" font-size="11">1. 발바닥중앙을 지압점에 밀착</text>
            <text x="240" y="138" fill="#94a3b8" font-size="11">2. 호흡을 뱉으며 팔꿈치를 뒤로</text>
            <text x="240" y="156" fill="#94a3b8" font-size="11">3. 날개뼈를 가운데로 조임</text>
          </svg>
        `,
        instructions: [
          '발지압판의 세라믹 돌기 위에 양발을 11자로 수평에 맞춰 올려놓습니다.',
          '무릎을 아주 살짝 구부려 하체 중심을 안정적으로 고정합니다.',
          '탄성 밴드 손잡이를 잡고 숨을 내쉬며 팔꿈치를 옆구리 뒤쪽으로 당겨줍니다.',
          '광배근과 하부 승모근이 수축하는 것을 느끼며 1초간 멈춘 후 천천히 원위치로 돌아옵니다.'
        ],
        safetyTips: '발바닥 통증이 심할 경우 얇은 두께의 운동용 아쿠아 슈즈나 두꺼운 양말을 착용하세요.'
      },
      {
        id: 'p1_d1',
        productId: 'p1',
        productName: '01. SOLE-FLEX DUAL TRAINER',
        type: 'diy',
        title: '지압판 결합 및 탄성 밴드 테더링 (Base Assembly & Tethering)',
        badge: '조립 및 결합',
        difficulty: '조립 난이도: 쉬움',
        timeRequired: '약 10분 소요',
        materials: ['발지압 베이스 프레임 1개', '고탄성 튜빙 밴드 2조', 'M6 육각 고정 볼트 4개'],
        desc: '발지압 베이스 플레이트에 고무 튜빙 밴드를 안정적으로 결합하고 앵커를 고정하는 절차입니다.',
        svgDiagram: `
          <svg viewBox="0 0 400 220" class="w-full h-auto bg-slate-900 rounded-xl">
            <!-- Grid lines -->
            <rect width="400" height="220" fill="#0f172a" />
            
            <!-- Assembly Blueprint Graphics -->
            <!-- Main Board Base -->
            <rect x="60" y="110" width="180" height="50" rx="8" fill="#1e293b" stroke="#38bdf8" stroke-width="2" stroke-dasharray="6,3"/>
            <!-- Nodes -->
            <line x1="80" y1="110" x2="80" y2="95" stroke="#b8f000" stroke-width="2"/>
            <circle cx="80" cy="92" r="4" fill="#b8f000"/>
            <line x1="120" y1="110" x2="120" y2="95" stroke="#b8f000" stroke-width="2"/>
            <circle cx="120" cy="92" r="4" fill="#b8f000"/>
            <line x1="160" y1="110" x2="160" y2="95" stroke="#b8f000" stroke-width="2"/>
            <circle cx="160" cy="92" r="4" fill="#b8f000"/>

            <!-- Band Anchor Fitting -->
            <path d="M220 135 L280 135 L300 80" fill="none" stroke="#f59e0b" stroke-width="5" stroke-linecap="round"/>
            <circle cx="220" cy="135" r="8" fill="#ef4444"/>
            <!-- Arrow indicating insertion -->
            <path d="M210 135 L190 135" fill="none" stroke="#38bdf8" stroke-width="3"/>
            <polygon points="215,135 205,130 205,140" fill="#38bdf8"/>

            <text x="20" y="30" fill="#38bdf8" font-size="12" font-weight="bold">제작 청사진 [조립 구조도]</text>
            
            <!-- Step Callouts -->
            <circle cx="220" cy="135" r="14" fill="#ef4444" opacity="0.3"/>
            <text x="216" y="140" fill="#ffffff" font-size="12" font-weight="bold">1</text>

            <rect x="250" y="20" width="130" height="60" rx="6" fill="#1e293b" stroke="#475569"/>
            <text x="260" y="40" fill="#b8f000" font-size="11" font-weight="bold">앵커 규격 안내</text>
            <text x="260" y="58" fill="#cbd5e1" font-size="10">고강도 듀얼 스틸 핀</text>
            <text x="260" y="72" fill="#cbd5e1" font-size="10">최대 장력: 45kgf</text>
          </svg>
        `,
        instructions: [
          '발지압 하단 플레이트의 가이드 홀에 튜빙 밴드의 엔드 캡을 위치시킵니다.',
          '동봉된 M6 육각 볼트를 이용하여 튜빙 홀더를 시계 방향으로 강하게 체결합니다.',
          '밴드를 강하게 당겨 유격이 없는지 3회 이상 당김 테스트를 진행합니다.'
        ],
        safetyTips: '볼트 체결이 느슨할 경우 운동 중 밴드가 이탈할 수 있으니 완전 체결을 확인하세요.'
      },

      // -------------------------------------------------------------
      // PRODUCT 02: POLYMORTEX ERGO ROLLER
      // -------------------------------------------------------------
      {
        id: 'p2_w1',
        productId: 'p2',
        productName: '02. POLYMORTEX ERGO ROLLER',
        type: 'workout',
        title: '하체 근막 이완 & 롤링 모션 (ITB & Quadriceps Rolling)',
        badge: '근막 이완 & 롤링',
        targetMuscles: ['대퇴사두근', '장경인단(IT-Band)', '종아리 비복근'],
        difficulty: '중급',
        reps: '부위당 30초~1분 롤링',
        desc: '폴리모프 미세돌기가 배치된 코어 롤러를 활용하여 뭉친 대퇴근과 근막을 세밀하게 이완합니다.',
        svgDiagram: `
          <svg viewBox="0 0 400 220" class="w-full h-auto bg-slate-900 rounded-xl">
            <rect width="400" height="220" fill="#0b0f26" />

            <!-- Roller Graphic -->
            <circle cx="200" cy="140" r="30" fill="#1e293b" stroke="#b8f000" stroke-width="4"/>
            <!-- Micro bumps on roller -->
            <circle cx="200" cy="106" r="4" fill="#b8f000"/>
            <circle cx="224" cy="116" r="4" fill="#b8f000"/>
            <circle cx="234" cy="140" r="4" fill="#b8f000"/>
            <circle cx="224" cy="164" r="4" fill="#b8f000"/>
            <circle cx="200" cy="174" r="4" fill="#b8f000"/>
            <circle cx="176" cy="164" r="4" fill="#b8f000"/>
            <circle cx="166" cy="140" r="4" fill="#b8f000"/>
            <circle cx="176" cy="116" r="4" fill="#b8f000"/>

            <!-- Rolling Direction Arrows -->
            <path d="M140 140 L110 140" fill="none" stroke="#38bdf8" stroke-width="3"/>
            <polygon points="105,140 115,135 115,145" fill="#38bdf8"/>
            
            <path d="M260 140 L290 140" fill="none" stroke="#38bdf8" stroke-width="3"/>
            <polygon points="295,140 285,135 285,145" fill="#38bdf8"/>

            <!-- Human Leg Pose resting on roller -->
            <path d="M80 110 L195 125 L310 100" fill="none" stroke="#f43f5e" stroke-width="12" stroke-linecap="round" opacity="0.8"/>

            <!-- Action Tag -->
            <rect x="20" y="20" width="160" height="28" rx="6" fill="#1e293b"/>
            <text x="30" y="38" fill="#b8f000" font-size="11" font-weight="bold">운동 가이드: 수평 롤링 벡터</text>

            <text x="20" y="195" fill="#94a3b8" font-size="11">체중을 실어 전후로 15cm 범위 내에서 천천히 왕복하세요.</text>
          </svg>
        `,
        instructions: [
          '바닥에 엎드린 상태에서 허벅지 앞쪽(대퇴사두근)에 미세돌기 롤러를 위치시킵니다.',
          '팔꿈치로 매트를 지지하여 체중의 60~70%를 롤러에 실어줍니다.',
          '골반부터 무릎 위 5cm 지점까지 천천히 위아래로 롤링합니다.',
          '특히 유착이 심하고 통증이 있는 트리거 포인트에서는 10초간 정지하여 압박합니다.'
        ],
        safetyTips: '관절이나 무릎 뼈 자체에 직접적인 롤링 압박을 가하지 않도록 주의하세요.'
      },
      {
        id: 'p2_d1',
        productId: 'p2',
        productName: '02. POLYMORTEX ERGO ROLLER',
        type: 'diy',
        title: '폴리모프 미세돌기 열성형 & 커스텀 도포 (Thermo-Plastic Molding)',
        badge: '성형 & DIY 가이드',
        difficulty: '조립 난이도: 보통',
        timeRequired: '약 20분 소요 (식힘 시간 포함)',
        materials: ['Polymorph 열가소성 알갱이 150g', '65°C 온수', '내열성 에폭시 인너 코어 관'],
        desc: '60~70°C의 온수에서 투명하게 녹인 열가소성 폴리모프 소재를 롤러 코어 표면에 도포하여 미세 돌기를 형성하는 가이드입니다.',
        svgDiagram: `
          <svg viewBox="0 0 400 220" class="w-full h-auto bg-slate-900 rounded-xl">
            <rect width="400" height="220" fill="#0f172a" />

            <!-- Water Container Step 1 -->
            <rect x="40" y="80" width="80" height="90" rx="8" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
            <path d="M42 110 C60 105 100 115 118 110 L118 168 C118 170 110 168 80 168 C50 168 42 170 42 168 Z" fill="#0284c7" opacity="0.5"/>
            <text x="50" y="65" fill="#38bdf8" font-size="11" font-weight="bold">1. 온수 연화</text>
            <text x="52" y="140" fill="#ffffff" font-size="12" font-weight="bold">60~70°C</text>

            <!-- Arrow -->
            <path d="M135 125 L165 125" fill="none" stroke="#b8f000" stroke-width="3"/>
            <polygon points="170,125 160,120 160,130" fill="#b8f000"/>

            <!-- Core Coating Step 2 -->
            <rect x="185" y="80" width="80" height="90" rx="8" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
            <circle cx="225" cy="125" r="22" fill="#475569"/>
            <!-- Molded Bumps -->
            <circle cx="225" cy="98" r="4" fill="#ef4444"/>
            <circle cx="247" cy="125" r="4" fill="#ef4444"/>
            <circle cx="225" cy="152" r="4" fill="#ef4444"/>
            <circle cx="203" cy="125" r="4" fill="#ef4444"/>
            <text x="195" y="65" fill="#38bdf8" font-size="11" font-weight="bold">2. 돌기 성형</text>

            <!-- Arrow -->
            <path d="M280 125 L310 125" fill="none" stroke="#b8f000" stroke-width="3"/>
            <polygon points="315,125 305,120 305,130" fill="#b8f000"/>

            <!-- Curing Step 3 -->
            <rect x="330" y="80" width="55" height="90" rx="8" fill="#1e293b" stroke="#10b981" stroke-width="2"/>
            <text x="335" y="65" fill="#10b981" font-size="11" font-weight="bold">3. 굳힘</text>
            <text x="340" y="130" fill="#10b981" font-size="10" font-weight="bold">냉각 경화</text>
          </svg>
        `,
        instructions: [
          '비커나 내열 용기에 65°C 정도의 따뜻한 물을 준비하고 폴리모프 알갱이를 넣습니다.',
          '알갱이가 투명하게 변하면 건져내어 반죽한 뒤 롤러 코어 관 외주면에 얇게 입힙니다.',
          '손끝이나 전용 팁 몰드를 사용해 약 5~8mm 높이의 미세 돌기 패턴을 일정하게 생성합니다.',
          '찬물에 5분간 담그거나 상온에서 15분간 건조시켜 흰색으로 단단하게 경화시킵니다.'
        ],
        safetyTips: '70°C 이상의 너무 뜨거운 물을 사용하면 화상의 위험이 있으므로 반드시 온도계나 적정 온도를 확인하세요.'
      },

      // -------------------------------------------------------------
      // PRODUCT 03: PEC-FLY ERGO GRIP BANDS
      // -------------------------------------------------------------
      {
        id: 'p3_w1',
        productId: 'p3',
        productName: '03. PEC-FLY ERGO GRIP BANDS',
        type: 'workout',
        title: '커스텀 그립 펙덱 플라이 (Custom Ergonomic Pec-Fly)',
        badge: '가슴 근육 & 그립 맞춤',
        targetMuscles: ['대흉근 (가슴 중앙/내부)', '전면 삼각근'],
        difficulty: '초급 / 중급',
        reps: '12~15회 x 4세트',
        desc: '사용자의 손 모양에 완벽히 맞춘 성형 그립을 잡고 가슴 중앙으로 모아주는 플라이 동작을 실시합니다.',
        svgDiagram: `
          <svg viewBox="0 0 400 220" class="w-full h-auto bg-slate-900 rounded-xl">
            <rect width="400" height="220" fill="#0f172a" />

            <!-- Vector Diagram Pec Fly Dynamic -->
            <!-- Human Upper Body Top View / Front Stance -->
            <circle cx="200" cy="70" r="16" fill="#64748b"/> <!-- Head -->
            
            <!-- Shoulders -->
            <path d="M140 95 L260 95" fill="none" stroke="#38bdf8" stroke-width="12" stroke-linecap="round"/>
            
            <!-- Pectoral Muscles Highlight -->
            <path d="M170 95 C180 115 220 115 230 95 Z" fill="#f43f5e" opacity="0.8"/>

            <!-- Arms Opening Motion (Start Motion) -->
            <path d="M140 95 L100 140" fill="none" stroke="#94a3b8" stroke-width="6" stroke-dasharray="4,4"/>
            <path d="M260 95 L300 140" fill="none" stroke="#94a3b8" stroke-width="6" stroke-dasharray="4,4"/>

            <!-- Arms Closing Motion Vectors (End Motion) -->
            <path d="M140 95 L180 150" fill="none" stroke="#b8f000" stroke-width="6"/>
            <path d="M260 95 L220 150" fill="none" stroke="#b8f000" stroke-width="6"/>

            <!-- Direction Arrows -->
            <path d="M100 145 C130 165 160 165 175 155" fill="none" stroke="#b8f000" stroke-width="3"/>
            <polygon points="180,152 170,148 172,158" fill="#b8f000"/>

            <path d="M300 145 C270 165 240 165 225 155" fill="none" stroke="#b8f000" stroke-width="3"/>
            <polygon points="220,152 228,158 230,148" fill="#b8f000"/>

            <!-- Custom Ergonomics Grips at center -->
            <circle cx="180" cy="150" r="8" fill="#b8f000"/>
            <circle cx="220" cy="150" r="8" fill="#b8f000"/>

            <text x="20" y="25" fill="#b8f000" font-size="11" font-weight="bold">수축 벡터: 가슴 중앙 집중</text>
            <text x="20" y="200" fill="#cbd5e1" font-size="11">손목을 비틀지 않고 커스텀 그립의 인체공학 홈을 그대로 밀어주세요.</text>
          </svg>
        `,
        instructions: [
          '문틀 앵커 또는 고정대에 밴드를 걸고 양손으로 맞춤 성형된 그립을 쥡니다.',
          '팔꿈치를 살짝 굽혀 고정한 채로, 호흡을 내쉬며 양손을 가슴 앞 중앙으로 모아줍니다.',
          '대흉근 안쪽이 최대 수축되는 지점에서 1~2초간 지긋이 쥐어짜듯 자극합니다.',
          '마시는 호흡에 가슴이 가볍게 스트레칭되는 느낌을 받으며 원위치로 천천히 이완합니다.'
        ],
        safetyTips: '팔꿈치가 어깨 뒤쪽으로 너무 과도하게 넘어가지 않도록 관절 범위(ROM)를 조절하세요.'
      },
      {
        id: 'p3_d1',
        productId: 'p3',
        productName: '03. PEC-FLY ERGO GRIP BANDS',
        type: 'diy',
        title: '사용자 손바닥 커스텀 그립 음각 몰딩 (Palm Impression Grip Customizing)',
        badge: '핸들 맞춤 성형',
        difficulty: '조립 난이도: 쉬움',
        timeRequired: '약 15분 소요',
        materials: ['핸들 유닛 코어 2개', 'Polymorph 스틱 100g', '밴드 연결용 D링 카라비너'],
        desc: '사용자 개개인의 악력과 파악 자세에 맞춰 손가락 마디 및 아치 음각을 형성하는 핸들 성형 절차입니다.',
        svgDiagram: `
          <svg viewBox="0 0 400 220" class="w-full h-auto bg-slate-900 rounded-xl">
            <rect width="400" height="220" fill="#0f172a" />

            <!-- Grip Core Base -->
            <rect x="80" y="60" width="50" height="110" rx="12" fill="#334155" stroke="#94a3b8" stroke-width="2"/>
            
            <!-- Soft Polymorph Layer applied -->
            <rect x="75" y="70" width="60" height="90" rx="8" fill="#b8f000" opacity="0.4"/>
            
            <!-- Hand Impression Arrows -->
            <g stroke="#ef4444" stroke-width="3" fill="none">
              <path d="M 180 80 L 135 85" />
              <path d="M 185 105 L 135 105" />
              <path d="M 185 130 L 135 128" />
              <path d="M 180 155 L 135 148" />
            </g>
            
            <!-- Hand Symbol -->
            <text x="200" y="120" fill="#ffffff" font-size="14" font-weight="bold">손바닥 가압 (Impression)</text>
            <text x="200" y="140" fill="#94a3b8" font-size="11">악력 방향으로 10초간 파악</text>

            <rect x="20" y="20" width="170" height="26" rx="6" fill="#1e293b"/>
            <text x="30" y="37" fill="#38bdf8" font-size="11" font-weight="bold">제작 가이드: 맞춤 음각 형성</text>
          </svg>
        `,
        instructions: [
          '따뜻한 물에 연화시킨 폴리모프 몰딩재를 플라스틱 핸들 코어에 균일하게 감싸줍니다.',
          '본인이 평소 플라이 운동 시 사용하는 편안한 그립 각도로 핸들을 세게 쥐어 손가락 자국을 만듭니다.',
          '엄지손가락 받침대 부분의 굴곡을 다듬은 후 굳을 때까지 3분간 그립 상태를 유지합니다.',
          '완전히 하얗게 굳은 후 D링에 튜빙 밴드 카라비너를 걸어 조립을 완료합니다.'
        ],
        safetyTips: '손가락 자국을 너무 깊게 찌르면 내구성이 약해질 수 있으므로 최소 3mm 이상의 두께를 유지하세요.'
      }
    ];

    // INITIALIZATION & RENDER
    window.onload = function() {
      renderGuides();
    };

    // SWITCH TAB TYPE (WORKOUT vs DIY)
    function switchGuideType(type) {
      currentGuideType = type;
      
      const btnWorkout = document.getElementById('btn-tab-workout');
      const btnDiy = document.getElementById('btn-tab-diy');
      const noticeTitle = document.getElementById('noticeTitle');
      const noticeDesc = document.getElementById('noticeDesc');

      if (type === 'workout') {
        btnWorkout.className = 'tab-active flex items-center justify-center gap-2 px-6 py-3 rounded-xl font-bold text-sm sm:text-base border border-transparent transition-all';
        btnDiy.className = 'flex items-center justify-center gap-2 px-6 py-3 rounded-xl font-bold text-sm sm:text-base border border-transparent bg-slate-100 text-slate-700 hover:bg-slate-200 transition-all';
        
        noticeTitle.textContent = '운동 가이드 모드 활성화 중';
        noticeDesc.textContent = '동작 수행에 필요한 올바른 자세, 타겟 근육 자극 범위, 이동 방향 벡터 및 추천 세트수를 확인하세요.';
      } else {
        btnDiy.className = 'tab-active flex items-center justify-center gap-2 px-6 py-3 rounded-xl font-bold text-sm sm:text-base border border-transparent transition-all';
        btnWorkout.className = 'flex items-center justify-center gap-2 px-6 py-3 rounded-xl font-bold text-sm sm:text-base border border-transparent bg-slate-100 text-slate-700 hover:bg-slate-200 transition-all';
        
        noticeTitle.textContent = '제작 가이드 (DIY Assembly) 모드 활성화 중';
        noticeDesc.textContent = 'Polymorph 열가소성 성형 온도, 부품 조립 순서, 유격 및 안전 체결 가이드를 확인하세요.';
      }

      renderGuides();
    }

    // FILTER PRODUCT CATEGORY
    function filterProduct(prodId) {
      currentProductFilter = prodId;

      const filters = ['all', 'p1', 'p2', 'p3'];
      filters.forEach(f => {
        const btn = document.getElementById(`filter-${f}`);
        if (f === prodId) {
          btn.className = 'px-3 py-1.5 rounded-lg text-xs font-bold transition-all bg-exer-navy text-white';
        } else {
          btn.className = 'px-3 py-1.5 rounded-lg text-xs font-medium text-slate-600 hover:bg-slate-100 transition-all whitespace-nowrap';
        }
      });

      renderGuides();
    }

    // HANDLE SEARCH INPUT
    function handleSearch() {
      searchQuery = document.getElementById('searchInput').value.trim().toLowerCase();
      renderGuides();
    }

    function resetFilters() {
      currentGuideType = 'workout';
      currentProductFilter = 'all';
      searchQuery = '';
      document.getElementById('searchInput').value = '';
      switchGuideType('workout');
      filterProduct('all');
    }

    // RENDER GUIDES CARDS
    function renderGuides() {
      const grid = document.getElementById('guidesGrid');
      const noResults = document.getElementById('noResults');

      const filtered = guideData.filter(item => {
        // Filter by Guide Type
        if (item.type !== currentGuideType) return false;

        // Filter by Product ID
        if (currentProductFilter !== 'all' && item.productId !== currentProductFilter) return false;

        // Filter by Search Query
        if (searchQuery) {
          const matchTitle = item.title.toLowerCase().includes(searchQuery);
          const matchProduct = item.productName.toLowerCase().includes(searchQuery);
          const matchDesc = item.desc.toLowerCase().includes(searchQuery);
          const matchTarget = item.targetMuscles ? item.targetMuscles.some(m => m.toLowerCase().includes(searchQuery)) : false;
          const matchMaterials = item.materials ? item.materials.some(m => m.toLowerCase().includes(searchQuery)) : false;
          return matchTitle || matchProduct || matchDesc || matchTarget || matchMaterials;
        }

        return true;
      });

      if (filtered.length === 0) {
        grid.innerHTML = '';
        noResults.classList.remove('hidden');
        return;
      }

      noResults.classList.add('hidden');

      grid.innerHTML = filtered.map(item => {
        return `
          <div class="bg-white rounded-2xl border border-slate-200 shadow-sm hover:shadow-md transition-all overflow-hidden flex flex-col justify-between">
            
            <div>
              <!-- Card Header Badge & Product Name -->
              <div class="p-5 pb-3 border-b border-slate-100 flex justify-between items-start gap-2">
                <div>
                  <span class="text-[11px] font-bold tracking-wider text-exer-indigo uppercase block mb-1">${item.productName}</span>
                  <h3 class="text-base font-extrabold text-slate-900 leading-snug">${item.title}</h3>
                </div>
                <span class="px-2.5 py-1 rounded-md text-[11px] font-bold ${item.type === 'workout' ? 'bg-exer-limeLight text-exer-navy border border-exer-lime/40' : 'bg-slate-100 text-slate-700 border border-slate-200'}">
                  ${item.badge}
                </span>
              </div>

              <!-- Vector Diagram Area -->
              <div class="p-4 bg-slate-900">
                ${item.svgDiagram}
              </div>

              <!-- Content Summary -->
              <div class="p-5 space-y-3">
                <p class="text-xs text-slate-600 leading-relaxed font-normal">${item.desc}</p>
                
                ${item.type === 'workout' ? `
                  <div class="space-y-1.5 pt-2 border-t border-slate-100">
                    <div class="flex items-center gap-1.5 text-xs text-slate-700 font-semibold">
                      <i class="fa-solid fa-bullseye text-rose-500"></i>
                      <span>타겟 부위: ${item.targetMuscles.join(', ')}</span>
                    </div>
                    <div class="flex items-center gap-1.5 text-xs text-slate-500">
                      <i class="fa-solid fa-rotate text-exer-indigo"></i>
                      <span>권장 세트: ${item.reps}</span>
                    </div>
                  </div>
                ` : `
                  <div class="space-y-1.5 pt-2 border-t border-slate-100">
                    <div class="flex items-center gap-1.5 text-xs text-slate-700 font-semibold">
                      <i class="fa-solid fa-clock text-amber-500"></i>
                      <span>소요 시간: ${item.timeRequired}</span>
                    </div>
                    <div class="flex items-center gap-1.5 text-xs text-slate-500">
                      <i class="fa-solid fa-layer-group text-exer-indigo"></i>
                      <span>주요 재료: ${item.materials[0]} 등</span>
                    </div>
                  </div>
                `}
              </div>
            </div>

            <!-- Card Footer Action -->
            <div class="p-4 bg-slate-50 border-t border-slate-100">
              <button onclick="openDetailModal('${item.id}')" class="w-full py-2.5 rounded-xl bg-exer-navy text-white hover:bg-exer-indigo text-xs sm:text-sm font-bold flex items-center justify-center gap-2 transition-all shadow-sm">
                <span>상세 가이드 단계 보기</span>
                <i class="fa-solid fa-arrow-right text-exer-lime text-xs"></i>
              </button>
            </div>

          </div>
        `;
      }).join('');
    }

    // OPEN DETAIL MODAL
    function openDetailModal(itemId) {
      const item = guideData.find(g => g.id === itemId);
      if (!item) return;

      document.getElementById('modalCategory').textContent = item.productName;
      document.getElementById('modalTitle').textContent = item.title;

      const body = document.getElementById('modalBody');

      body.innerHTML = `
        <div class="space-y-6">
          
          <!-- Full Vector Schematic Diagram -->
          <div class="bg-slate-900 p-4 rounded-2xl shadow-inner border border-slate-800">
            <span class="text-xs font-bold text-exer-lime mb-2 block"><i class="fa-solid fa-diagram-project mr-1"></i> 시각적 구조 및 동작 다이어그램</span>
            ${item.svgDiagram}
          </div>

          <!-- Quick Metadata Badge Grid -->
          <div class="grid grid-cols-2 sm:grid-cols-3 gap-3">
            <div class="bg-slate-50 p-3 rounded-xl border border-slate-200">
              <span class="text-[10px] text-slate-400 font-bold block uppercase">구분</span>
              <span class="text-xs font-bold text-exer-navy">${item.type === 'workout' ? '운동 수행 가이드' : '제작/조립 가이드'}</span>
            </div>
            <div class="bg-slate-50 p-3 rounded-xl border border-slate-200">
              <span class="text-[10px] text-slate-400 font-bold block uppercase">${item.type === 'workout' ? '난이도' : '조립 난이도'}</span>
              <span class="text-xs font-bold text-slate-800">${item.difficulty}</span>
            </div>
            <div class="bg-slate-50 p-3 rounded-xl border border-slate-200 col-span-2 sm:col-span-1">
              <span class="text-[10px] text-slate-400 font-bold block uppercase">${item.type === 'workout' ? '권장 반복' : '소요시간'}</span>
              <span class="text-xs font-bold text-exer-indigo">${item.type === 'workout' ? item.reps : item.timeRequired}</span>
            </div>
          </div>

          ${item.materials ? `
            <div class="bg-amber-50 p-4 rounded-xl border border-amber-200">
              <h4 class="text-xs font-bold text-amber-900 mb-2 flex items-center gap-1.5">
                <i class="fa-solid fa-boxes-packing text-amber-600"></i> 필요 부품 및 재료 목록
              </h4>
              <ul class="list-disc list-inside text-xs text-amber-800 space-y-1">
                ${item.materials.map(m => `<li>${m}</li>`).join('')}
              </ul>
            </div>
          ` : ''}

          <!-- Step-by-Step Instructions -->
          <div class="space-y-3">
            <h4 class="text-sm font-extrabold text-slate-900 flex items-center gap-2 border-b border-slate-200 pb-2">
              <i class="fa-solid fa-list-check text-exer-indigo"></i>
              <span>단계별 세부 가이드</span>
            </h4>
            <div class="space-y-2.5">
              ${item.instructions.map((step, idx) => `
                <div class="flex items-start gap-3 p-3 rounded-xl bg-slate-50 border border-slate-100">
                  <span class="w-6 h-6 rounded-full bg-exer-navy text-exer-lime font-bold text-xs flex items-center justify-center shrink-0 mt-0.5">
                    ${idx + 1}
                  </span>
                  <p class="text-xs sm:text-sm text-slate-700 leading-relaxed font-medium">${step}</p>
                </div>
              `).join('')}
            </div>
          </div>

          <!-- Safety Notice -->
          <div class="bg-rose-50 p-4 rounded-xl border border-rose-200 flex items-start gap-3">
            <i class="fa-solid fa-shield-cat text-rose-500 text-lg mt-0.5"></i>
            <div>
              <strong class="text-xs font-bold text-rose-900 block mb-0.5">안전 가이드 및 주의사항</strong>
              <p class="text-xs text-rose-700 leading-relaxed">${item.safetyTips}</p>
            </div>
          </div>

        </div>
      `;

      document.getElementById('detailModal').classList.remove('hidden');
    }

    function closeModal() {
      document.getElementById('detailModal').classList.add('hidden');
    }

    // REST TIMER LOGIC
    let timerInterval = null;
    let timerSeconds = 45;
    let timerRunning = false;

    function openTimerModal() {
      document.getElementById('timerModal').classList.remove('hidden');
    }

    function closeTimerModal() {
      document.getElementById('timerModal').classList.add('hidden');
      pauseTimer();
    }

    function setTimerSec(sec) {
      pauseTimer();
      timerSeconds = sec;
      updateTimerDisplay();
    }

    function updateTimerDisplay() {
      const mins = Math.floor(timerSeconds / 60);
      const secs = timerSeconds % 60;
      document.getElementById('timerDisplay').textContent = 
        `${String(mins).padStart(2, '0')}:${String(secs).padStart(2, '0')}`;
    }

    function toggleTimer() {
      if (timerRunning) {
        pauseTimer();
      } else {
        startTimer();
      }
    }

    function startTimer() {
      if (timerSeconds <= 0) timerSeconds = 45;
      timerRunning = true;
      document.getElementById('timerStartBtn').innerHTML = `<i class="fa-solid fa-pause mr-1"></i> 일시정지`;
      
      timerInterval = setInterval(() => {
        timerSeconds--;
        updateTimerDisplay();
        if (timerSeconds <= 0) {
          pauseTimer();
          alert('휴식 시간이 완료되었습니다! 다음 세트를 시작하세요.');
        }
      }, 1000);
    }

    function pauseTimer() {
      timerRunning = false;
      clearInterval(timerInterval);
      document.getElementById('timerStartBtn').innerHTML = `<i class="fa-solid fa-play mr-1"></i> 시작`;
    }

    function resetTimer() {
      pauseTimer();
      timerSeconds = 45;
      updateTimerDisplay();
    }

    // QR MODAL LOGIC
    function openQRModal() {
      document.getElementById('qrModal').classList.remove('hidden');
    }

    function closeQRModal() {
      document.getElementById('qrModal').classList.add('hidden');
    }
  </script>

</body>
</html>
