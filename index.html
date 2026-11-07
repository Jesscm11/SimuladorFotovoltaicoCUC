<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="color-scheme" content="dark">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>SIMULADOR FOTOVOLTAICO – PVWatts</title>
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;600;800&display=swap" rel="stylesheet">
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.min.js"></script>
<style>
:root{color-scheme:dark;--bg:#0B1625;--surf:#1E293B;--surf2:#17233A;--ink:#F8FAFC;--mut:#CBD5E1;--line:rgba(96,140,220,.22);--blu:#2563EB;--blut:#60A5FA;--grn:#10B981;--sun:#2563EB;--grnbg:rgba(16,185,129,.12);--hero:#0B1625;--bad:#F87171;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
*{box-sizing:border-box}
html{scroll-padding-top:env(safe-area-inset-top,0px);-webkit-text-size-adjust:100%}
body{margin:0;background:var(--bg);color:var(--ink);font-family:"Outfit",system-ui,-apple-system,"Segoe UI",Arial,sans-serif;line-height:1.55;background-image:radial-gradient(900px 420px at 85% -80px,rgba(37,99,235,.16),transparent 70%)}
.wrap{max-width:1120px;margin:0 auto;padding:0 clamp(14px,3vw,24px)}
.ic{width:20px;height:20px;flex:none;fill:none;stroke:currentColor;stroke-width:1.8;stroke-linecap:round;stroke-linejoin:round}
header.hero{position:relative;overflow:hidden;color:var(--ink);padding:48px 0 44px;border-bottom:1px solid var(--line);background:linear-gradient(135deg,#0B1625 0%,#10203A 60%,#0F2A3A 100%)}
header.hero::before{content:"";position:absolute;inset:0;background-image:linear-gradient(rgba(96,140,220,.08) 1px,transparent 1px),linear-gradient(90deg,rgba(96,140,220,.08) 1px,transparent 1px);background-size:44px 44px;-webkit-mask-image:linear-gradient(90deg,transparent,#000 70%);mask-image:linear-gradient(90deg,transparent,#000 70%)}
header.hero::after{content:"";position:absolute;left:0;right:0;bottom:0;height:2px;background:linear-gradient(90deg,var(--blu),var(--grn),transparent)}
.hero .wrap{position:relative}
.hero h1{margin:0 0 12px;font-size:clamp(1.6rem,4.5vw,2.6rem);font-weight:600;letter-spacing:-.4px;line-height:1.15}
.hero h1 span{color:var(--grn)}
.hero p{margin:0;max-width:64ch;color:var(--mut)}
.hero .sun{display:inline-block;width:.5em;height:.5em;border-radius:50%;background:var(--grn);box-shadow:0 0 0 .16em rgba(16,185,129,.28),0 0 18px rgba(16,185,129,.6);margin-right:.6em;vertical-align:.1em}
main{margin-top:24px;padding-bottom:40px}
.card{background:linear-gradient(180deg,var(--surf),#1A2538);border:1px solid var(--line);border-radius:16px;padding:clamp(18px,3vw,28px);margin-bottom:22px;box-shadow:0 10px 30px rgba(0,0,0,.28)}
.card h2{margin:0 0 4px;font-size:1.3rem;font-weight:600;letter-spacing:-.2px}
.sub{color:var(--mut);font-size:.92rem;margin:0 0 16px;opacity:.9}
.grid{display:grid;gap:16px}.grid>*{min-width:0}
.g2{grid-template-columns:repeat(3,minmax(0,1fr))}
.gh{grid-column:1/-1;margin:6px 0 -4px;font-size:.78rem;font-weight:600;letter-spacing:.08em;text-transform:uppercase;color:var(--blut);display:flex;align-items:center;gap:10px}
.gh::after{content:"";flex:1;height:1px;background:var(--line)}
label{display:block;font-weight:600;font-size:.88rem;margin-bottom:6px}
input,select{width:100%;min-height:46px;padding:11px 13px;border:1.5px solid var(--line);border-radius:10px;background:#0F1B2E;color:var(--ink);font:inherit;transition:border-color .2s,box-shadow .2s,background .2s}
input:hover,select:hover{border-color:rgba(96,165,250,.5)}
input:focus,select:focus{outline:0;border-color:var(--blu);box-shadow:0 0 0 3px rgba(37,99,235,.3)}
button:focus-visible,summary:focus-visible{outline:2px solid var(--blut);outline-offset:2px}
input.bad{border-color:var(--bad);box-shadow:0 0 0 3px rgba(248,113,113,.15)}
.err{color:var(--bad);font-size:.8rem;min-height:1.1em;margin-top:3px}
.hint{color:var(--mut);font-size:.78rem;opacity:.85}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-bottom:18px}
.chip{border:1px solid var(--line);background:rgba(37,99,235,.1);color:var(--ink);border-radius:999px;padding:8px 16px;font:inherit;font-size:.85rem;cursor:pointer;transition:background .2s,border-color .2s,transform .15s}
.chip:hover{border-color:var(--blut);background:rgba(37,99,235,.24)}
.chip:active{transform:scale(.97)}
.btns{display:flex;flex-wrap:wrap;gap:10px;margin-top:20px}
.btn{border:0;border-radius:10px;padding:13px 22px;font:inherit;font-weight:600;cursor:pointer;transition:transform .15s,box-shadow .2s,background .2s,border-color .2s}
.btn:active{transform:translateY(1px) scale(.98)}
.btn.main{background:linear-gradient(135deg,#2563EB,#1D4ED8);color:#fff;letter-spacing:.4px;flex:1 1 220px;font-size:1rem;box-shadow:0 6px 18px rgba(37,99,235,.35)}
.btn.main:hover{background:linear-gradient(135deg,#3B82F6,#2563EB);box-shadow:0 8px 24px rgba(37,99,235,.5);transform:translateY(-1px)}
.btn.alt{background:rgba(37,99,235,.08);border:1.5px solid var(--line);color:var(--ink)}
.btn.alt:hover{border-color:var(--blut);background:rgba(37,99,235,.2)}
.kpis{display:grid;gap:16px;grid-template-columns:repeat(3,minmax(0,1fr));align-items:stretch}
.kpis+.kpis{margin-top:16px}
.kpi{container-type:inline-size;display:flex;flex-direction:column;min-width:0;border-radius:14px;padding:18px 20px;border:1px solid var(--line);background:var(--surf2);position:relative;overflow:hidden;transition:border-color .2s,transform .2s}
.kpi::before{content:"";position:absolute;left:0;right:0;top:0;height:3px;background:var(--blu)}
.kpi.grn::before{background:var(--grn)}
.kpi:hover{border-color:rgba(96,165,250,.5)}
.kpi .l{display:flex;align-items:center;gap:10px;font-size:.85rem;color:var(--mut);line-height:1.3;margin-bottom:10px}
.kpi .ic{box-sizing:content-box;width:18px;height:18px;padding:7px;border-radius:10px;background:rgba(37,99,235,.18);color:var(--blut)}
.kpi.grn .ic{background:var(--grnbg);color:var(--grn)}
.kpi .v{font-size:clamp(1.4rem,4vw,2rem);font-size:clamp(1.3rem,11cqi,2.1rem);font-weight:600;line-height:1.15;white-space:nowrap;font-variant-numeric:tabular-nums}
.kpi .u{font-size:.8rem;color:var(--mut);line-height:1.35;margin-top:4px;overflow-wrap:anywhere}
.kpi.grn .v{color:var(--grn)}
.kpi.blu .v{color:var(--blut)}
.kpis.two{grid-template-columns:repeat(2,minmax(0,1fr))}
@media (max-width:900px){.kpis,.g2{grid-template-columns:repeat(2,minmax(0,1fr))}}
@media (max-width:560px){.kpis,.kpis.two,.g2{grid-template-columns:minmax(0,1fr)}}
.bar{height:10px;border-radius:99px;background:rgba(148,163,184,.2);overflow:hidden;margin-top:12px}
.bar i{display:block;height:100%;background:linear-gradient(90deg,var(--blu),var(--grn));width:0;transition:width .6s}
.chartbox{position:relative;width:100%;min-width:0;height:clamp(300px,44vw,420px)}
.chartbox canvas{display:block}
.scroll{overflow-x:auto;border:1px solid var(--line);border-radius:12px}
table{width:100%;border-collapse:collapse;min-width:520px;font-variant-numeric:tabular-nums}
th,td{padding:13px 16px;text-align:left;border-bottom:1px solid var(--line)}
th{background:rgba(37,99,235,.28);color:#fff;font-weight:600;font-size:.9rem}
tbody tr:nth-child(even){background:rgba(255,255,255,.025)}
tbody tr:hover{background:rgba(37,99,235,.1)}
tbody tr:last-child td{border-bottom:0}
td:first-child{font-weight:600}
td:last-child{color:var(--grn);font-weight:600}
.note{background:rgba(37,99,235,.1);border:1px solid var(--line);border-left:4px solid var(--blu);padding:14px 16px;border-radius:12px;font-size:.9rem;color:var(--mut)}
.note b{color:var(--ink)}
.steps{display:grid;gap:16px;grid-template-columns:repeat(auto-fit,minmax(min(100%,230px),1fr))}
.steps:has(>.step:nth-child(5):last-child){grid-template-columns:repeat(auto-fit,minmax(min(100%,170px),1fr))}
.step{background:var(--surf2);border:1px solid var(--line);border-radius:14px;padding:18px;color:var(--mut);font-size:.92rem;transition:border-color .2s}
.step:hover{border-color:rgba(96,165,250,.5)}
.step .ic{box-sizing:content-box;display:block;width:20px;height:20px;padding:9px;margin-bottom:12px;border-radius:11px;background:rgba(37,99,235,.18);color:var(--blut)}
.step b{display:block;color:var(--ink);font-size:1rem;margin-bottom:4px}
footer{text-align:center;color:var(--mut);font-size:.8rem;padding:14px 16px 34px;opacity:.8}
.msg{padding:13px 16px;border-radius:12px;background:var(--grnbg);border:1px solid rgba(16,185,129,.35);margin-top:14px;font-size:.92rem}
.tabs{background:rgba(11,22,37,.85);-webkit-backdrop-filter:blur(12px);backdrop-filter:blur(12px);border-bottom:1px solid var(--line);position:sticky;top:env(safe-area-inset-top,0px);z-index:5}
.tabs .wrap{display:flex;gap:6px;overflow-x:auto;padding-top:8px;padding-bottom:8px;scrollbar-width:none}
.tabs .wrap::-webkit-scrollbar{display:none}
.tabbtn{border:0;background:none;color:var(--mut);font:inherit;font-weight:600;padding:10px 18px;border-radius:10px;cursor:pointer;white-space:nowrap;transition:background .2s,color .2s}
.tabbtn:hover{background:rgba(37,99,235,.15);color:var(--ink)}
.tabbtn.on{color:#fff;background:var(--blu);box-shadow:0 4px 14px rgba(37,99,235,.4)}
.tab{display:none}.tab.on{display:block;animation:fin .35s ease}
@keyframes fin{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:none}}
.pgrid{display:grid;gap:16px;grid-template-columns:repeat(auto-fit,minmax(min(100%,230px),1fr))}
.pcard{border:1px solid var(--line);border-radius:14px;overflow:hidden;background:var(--surf2);cursor:pointer;text-align:left;padding:0;color:inherit;font:inherit;transition:border-color .2s,transform .2s,box-shadow .2s}
.pcard:hover{border-color:var(--blut);transform:translateY(-2px);box-shadow:0 10px 24px rgba(0,0,0,.3)}
.pcard svg,dialog svg,#roof svg{display:block;width:100%;height:auto}
#roof svg{border-radius:12px;border:1px solid var(--line)}
.pcard div{padding:14px 16px}
.pcard b{display:block}
.pcard span{color:var(--mut);font-size:.85rem}
dialog{border:1px solid var(--line);border-radius:16px;background:var(--surf);color:var(--ink);max-width:520px;width:calc(100% - 32px);padding:0;box-shadow:0 20px 60px rgba(0,0,0,.5)}
dialog::backdrop{background:rgba(5,10,18,.75);backdrop-filter:blur(3px)}
#dlgc{padding:20px}
#dlgc table{min-width:0}
details{border-bottom:1px solid var(--line);padding:4px 0}
summary{font-weight:600;cursor:pointer;padding:12px 0;list-style:none;display:flex;justify-content:space-between;gap:16px;align-items:center}
summary::-webkit-details-marker{display:none}
summary::after{content:"+";color:var(--blut);font-size:1.4rem;line-height:1;flex:none}
details[open] summary::after{content:"–"}
details p{margin:0 0 12px;color:var(--mut)}
.row{display:flex;flex-wrap:wrap;gap:10px;margin-top:14px;align-items:center}
.chk{font-weight:400;margin-bottom:8px;display:flex;align-items:center;gap:10px;padding:10px 14px;border:1px solid var(--line);border-radius:10px;background:var(--surf2);cursor:pointer}
.chk input{width:auto;min-height:0;margin:0;accent-color:var(--blu)}
@media (prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}}
</style>
</head>
<body>
<svg width="0" height="0" style="position:absolute" aria-hidden="true"><symbol id="i-sun" viewBox="0 0 24 24"><circle cx="12" cy="12" r="4"/><path d="M12 2v2M12 20v2M4.9 4.9l1.4 1.4M17.7 17.7l1.4 1.4M2 12h2M20 12h2M4.9 19.1l1.4-1.4M17.7 6.3l1.4-1.4"/></symbol><symbol id="i-bolt" viewBox="0 0 24 24"><path d="M13 2L4 14h7l-1 8 9-12h-7z"/></symbol><symbol id="i-pct" viewBox="0 0 24 24"><path d="M19 5L5 19"/><circle cx="7" cy="7" r="2"/><circle cx="17" cy="17" r="2"/></symbol><symbol id="i-coin" viewBox="0 0 24 24"><circle cx="12" cy="12" r="9"/><path d="M12 7v10M9.5 9.5h4a1.5 1.5 0 010 3h-3a1.5 1.5 0 000 3h4"/></symbol><symbol id="i-cal" viewBox="0 0 24 24"><rect x="3" y="5" width="18" height="16" rx="2"/><path d="M3 10h18M8 3v4M16 3v4"/></symbol><symbol id="i-down" viewBox="0 0 24 24"><path d="M22 17l-9-9-4 4-7-7M16 17h6v-6"/></symbol><symbol id="i-leaf" viewBox="0 0 24 24"><path d="M11 20A7 7 0 019.8 6.1C15.5 5 17 4.5 19 2c1 2 2 4.2 2 8 0 5.5-4.8 10-10 10zM2 21c0-3 1.9-5.2 5-7"/></symbol><symbol id="i-tree" viewBox="0 0 24 24"><path d="M12 22v-6M12 16c-4 0-6-2.5-6-5 0-2 1-3 2-3.5C8 5 10 3 12 3s4 2 4 4.5c1 .5 2 1.5 2 3.5 0 2.5-2 5-6 5z"/></symbol><symbol id="i-wallet" viewBox="0 0 24 24"><path d="M3 7h16a2 2 0 012 2v9a2 2 0 01-2 2H5a2 2 0 01-2-2zM3 7l2-3h12M17 13h2"/></symbol><symbol id="i-clock" viewBox="0 0 24 24"><circle cx="12" cy="12" r="9"/><path d="M12 7v5l3 2"/></symbol><symbol id="i-chart" viewBox="0 0 24 24"><path d="M3 3v18h18M7 15l4-4 3 3 5-6"/></symbol><symbol id="i-panel" viewBox="0 0 24 24"><rect x="3" y="4" width="18" height="12" rx="1.5"/><path d="M3 10h18M9 4v12M15 4v12M12 16v4M8 20h8"/></symbol><symbol id="i-wrench" viewBox="0 0 24 24"><path d="M14.7 6.3a4 4 0 00-5.4 5.4L3 18l3 3 6.3-6.3a4 4 0 005.4-5.4l-2.5 2.5-2.5-.5-.5-2.5z"/></symbol><symbol id="i-shield" viewBox="0 0 24 24"><path d="M12 3l8 3v6c0 5-3.5 8-8 9-4.5-1-8-4-8-9V6z"/></symbol><symbol id="i-check" viewBox="0 0 24 24"><path d="M5 12l5 5 9-10"/></symbol></svg>
<header class="hero"><div class="wrap">
<h1><span class="sun"></span>SIMULADOR FOTOVOLTAICO – <span>PVWatts</span></h1>
<p>Estima cuánta energía solar podría producir tu vivienda y cuánto bajaría tu consumo y tu factura de electricidad. Proyecto académico de Ingeniería de Sistemas sobre eficiencia energética y energías renovables.</p>
</div></header>
<nav class='tabs'><div class='wrap'><button class='tabbtn on' data-t='sim'>Simulador</button><button class='tabbtn' data-t='pan'>Tipos de paneles</button><button class='tabbtn' data-t='guia'>Guía de instalación</button><button class='tabbtn' data-t='faq'>Preguntas frecuentes</button></div></nav>

<main class='wrap'>
<div class='tab on' id='tab-sim'>
<section class='card' id='form'>
<h2>Datos de tu vivienda y del sistema</h2>
<p class="sub">Prueba un ejemplo o escribe tus propios valores. Los resultados se actualizan al instante.</p>
<div class="chips" id="chips"></div>
<div class="grid g2">
<h3 class="gh">Tu vivienda</h3>
<div><label for="ciudad">Ubicación (ciudad o municipio)</label><select id="ciudad"></select><div class="hint" id="psh"></div></div>
<div><label for="kwh">Consumo mensual (kWh)</label><input id="kwh" type="number" inputmode="decimal" min="1" max="20000" step="any"><div class="err" data-e="kwh"></div></div>
<div><label for="fact">Factura mensual de electricidad (COP)</label><input id="fact" type="number" inputmode="decimal" min="1000" step="any"><div class="err" data-e="fact"></div></div>
<h3 class="gh">Sistema fotovoltaico</h3>
<div><label for="kw">Potencia del sistema fotovoltaico (kW)</label><input id="kw" type="number" inputmode="decimal" min="0.1" max="1000" step="0.1"><div class="err" data-e="kw"></div><div class="hint" id="rec"></div></div>
<div><label for="perd">Pérdidas del sistema (%)</label><input id="perd" type="number" inputmode="decimal" min="0" max="60" step="0.5"><div class="err" data-e="perd"></div><div class="hint">PVWatts usa 14 % por defecto (inversor, cableado, suciedad, temperatura).</div></div>
<div><label for="cub">Energía que deseas cubrir con paneles (%)</label><input id="cub" type="number" inputmode="decimal" min="1" max="100" step="1"><div class="err" data-e="cub"></div></div>
<div><label for='tipo'>Tipo de panel</label><select id='tipo'></select><div class='hint'>Ajusta las pérdidas típicas del tipo elegido.</div></div>
<div><label for='costo'>Costo estimado por kW instalado (COP)</label><input id='costo' type='number' inputmode='decimal' min='500000' max='20000000' step='50000' value='4500000'><div class='err' data-e='costo'></div></div>
</div>
<div class="btns">
<button class="btn main" id="calc">CALCULAR SIMULACIÓN</button>
<button class="btn alt" id="nueva">Nueva simulación</button>
<button class="btn alt" id="reset">Reiniciar datos</button>
</div>
<div id="msg"></div>
</section>

<section class="card" id="res">
<h2>Resultados y ahorro energético</h2>
<p class="sub" id="resSub"></p>
<div class="kpis">
<div class="kpi sun"><div class="l"><svg class="ic" aria-hidden="true"><use href="#i-sun"/></svg>Energía solar generada</div><div class="v" id="k1">–</div><div class="u">kWh por mes</div></div>
<div class="kpi blu"><div class="l"><svg class="ic" aria-hidden="true"><use href="#i-bolt"/></svg>Energía comprada a la red después</div><div class="v" id="k2">–</div><div class="u">kWh por mes</div></div>
<div class="kpi grn"><div class="l"><svg class="ic" aria-hidden="true"><use href="#i-pct"/></svg>Ahorro energético</div><div class="v" id="k3">–</div><div class="u">del consumo mensual</div><div class="bar"><i id="bar"></i></div></div>
<div class="kpi grn"><div class="l"><svg class="ic" aria-hidden="true"><use href="#i-coin"/></svg>Ahorro económico mensual</div><div class="v" id="k4">–</div><div class="u">COP estimados</div></div>
<div class="kpi grn"><div class="l"><svg class="ic" aria-hidden="true"><use href="#i-cal"/></svg>Ahorro económico anual</div><div class="v" id="k5">–</div><div class="u">COP estimados</div></div>
<div class="kpi blu"><div class="l"><svg class="ic" aria-hidden="true"><use href="#i-down"/></svg>Reducción de consumo de la red</div><div class="v" id="k6">–</div><div class="u">kWh menos por año</div></div>
</div>
<div class='kpis two'>
<div class='kpi grn'><div class='l'><svg class="ic" aria-hidden="true"><use href="#i-leaf"/></svg>CO₂ evitado al año</div><div class='v' id='k7'>–</div><div class='u'>kg (≈0,126 kg CO₂ por kWh)</div></div>
<div class='kpi grn'><div class='l'><svg class="ic" aria-hidden="true"><use href="#i-tree"/></svg>Equivale a plantar</div><div class='v' id='k8'>–</div><div class='u'>árboles (≈20 kg CO₂ por árbol al año)</div></div>
<div class='kpi sun'><div class='l'><svg class="ic" aria-hidden="true"><use href="#i-wallet"/></svg>Inversión estimada</div><div class='v' id='k9'>–</div><div class='u'>COP</div></div>
<div class='kpi sun'><div class='l'><svg class="ic" aria-hidden="true"><use href="#i-clock"/></svg>Retorno de la inversión</div><div class='v' id='k10'>–</div><div class='u'>tiempo estimado</div></div>
</div>
<div class='row'><button class='btn alt' id='cp'>Copiar resumen</button><button class='btn alt' data-go='pan'>Ver tipos de paneles</button><span class='hint' id='cm'></span></div>
</section>

<section class="card">
<h2>Comparativo mensual de energía</h2>
<p class="sub">Consumo antes, consumo después y generación solar durante el año (kWh).</p>
<div class="chartbox"><canvas id="chart" role="img" aria-label="Gráfica comparativa mensual de consumo y generación"></canvas></div>
</section>

<section class="card">
<h2>Tabla comparativa: antes y después</h2>
<p class="sub">Valores estimados con las tarifas calculadas a partir de tu factura.</p>
<div class="scroll"><table>
<thead><tr><th>Indicador</th><th>Antes de los paneles</th><th>Después de los paneles</th></tr></thead>
<tbody id="tb"></tbody></table></div>
</section>

<section class="card">
<h2>¿Cómo funciona el simulador?</h2>
<div class="steps">
<div class="step"><svg class="ic" aria-hidden="true"><use href="#i-sun"/></svg><b>1. El sol llega a los paneles</b>Los paneles solares reciben la radiación del sol y la convierten en electricidad.</div>
<div class="step"><svg class="ic" aria-hidden="true"><use href="#i-panel"/></svg><b>2. Se estima la producción</b>El simulador calcula cuánta energía pueden producir según tu ciudad, la potencia instalada y las pérdidas del sistema.</div>
<div class="step"><svg class="ic" aria-hidden="true"><use href="#i-chart"/></svg><b>3. Se compara con tu consumo</b>Esa energía se compara con lo que consume tu vivienda para saber cuánta energía dejarías de comprar a la red eléctrica.</div>
<div class="step"><svg class="ic" aria-hidden="true"><use href="#i-coin"/></svg><b>4. Se calcula el ahorro</b>La diferencia se convierte en kWh y en pesos usando el precio por kWh de tu factura.</div>
</div>
<p class="hint" style="margin-top:14px"><b>Modelo:</b> energía mensual = potencia (kW) × horas sol pico diarias de la ciudad × factor estacional del mes × días del mes × (1 − pérdidas). Es una aproximación inspirada en PVWatts del NREL, con valores de radiación promedio por ciudad.</p>
</section>

<div class="note"><b>Aviso:</b> los resultados son estimaciones con fines educativos, no mediciones reales. La producción real depende de la orientación e inclinación de los paneles, sombras, clima, equipos y condiciones de la red. Para un proyecto real, consulta a un instalador certificado. El cálculo del costo no incluye cargos fijos, subsidios, contribuciones ni excedentes vendidos a la red.</div>
</div>
<div class='tab' id='tab-pan'>
<section class='card'><h2>Tipos de paneles solares</h2><p class='sub'>Toca un panel para ver sus detalles y usarlo en el simulador. Las imágenes son ilustraciones esquemáticas.</p><div id='roof'></div><div class='pgrid' id='pgrid' style='margin-top:16px'></div></section>
<section class='card'><h2>Componentes de un sistema fotovoltaico</h2><div class='steps' style='margin-top:12px'>
<div class='step'><svg class="ic" aria-hidden="true"><use href="#i-panel"/></svg><b>Paneles</b>Convierten la luz del sol en electricidad de corriente continua.</div>
<div class='step'><svg class="ic" aria-hidden="true"><use href="#i-bolt"/></svg><b>Inversor</b>Transforma la corriente continua en corriente alterna, la que usa tu vivienda.</div>
<div class='step'><svg class="ic" aria-hidden="true"><use href="#i-wrench"/></svg><b>Estructura de soporte</b>Fija los paneles al techo con la inclinación y orientación adecuadas.</div>
<div class='step'><svg class="ic" aria-hidden="true"><use href="#i-shield"/></svg><b>Protecciones y cableado</b>Breakers, fusibles y puesta a tierra que cuidan equipos y personas.</div>
<div class='step'><svg class="ic" aria-hidden="true"><use href="#i-clock"/></svg><b>Medidor bidireccional</b>Registra la energía que tomas de la red y la que entregas como excedente.</div></div></section>
</div>
<div class='tab' id='tab-guia'>
<section class='card'><h2>Pasos para instalar paneles solares</h2><p class='sub'>Un recorrido típico, desde el análisis hasta el mantenimiento.</p><div class='steps'>
<div class='step'><svg class="ic" aria-hidden="true"><use href="#i-chart"/></svg><b>1. Analiza tu consumo</b>Revisa tus facturas y define cuánta energía quieres cubrir.</div>
<div class='step'><svg class="ic" aria-hidden="true"><use href="#i-check"/></svg><b>2. Visita técnica y diseño</b>Un instalador evalúa sombras, estructura, orientación e inclinación del techo.</div>
<div class='step'><svg class="ic" aria-hidden="true"><use href="#i-bolt"/></svg><b>3. Trámite con el operador de red</b>Se solicita la conexión del sistema y la instalación del medidor adecuado.</div>
<div class='step'><svg class="ic" aria-hidden="true"><use href="#i-panel"/></svg><b>4. Instalación</b>Montaje de estructura, paneles, inversor, protecciones y cableado.</div>
<div class='step'><svg class="ic" aria-hidden="true"><use href="#i-sun"/></svg><b>5. Puesta en marcha</b>Pruebas, revisión eléctrica y activación del sistema.</div>
<div class='step'><svg class="ic" aria-hidden="true"><use href="#i-wrench"/></svg><b>6. Mantenimiento</b>Limpieza periódica y revisión eléctrica anual para conservar el rendimiento.</div></div></section>
<section class='card'><h2>Lista de verificación antes de instalar</h2><p class='sub' id='ckt'>0 de 6 listos</p><div class='bar' style='margin:0 0 14px'><i id='ckb'></i></div><div id='ck'></div></section>
<div class='note'><b>Normativa en Colombia:</b> la Ley 1715 de 2014 y la Ley 2099 de 2021 promueven las energías renovables con incentivos tributarios, y la regulación de la CREG (Resolución 174 de 2021) cubre la autogeneración a pequeña escala. Verifica los requisitos vigentes con tu operador de red.</div>
</div>
<div class='tab' id='tab-faq'>
<section class='card'><h2>Preguntas frecuentes y glosario</h2>
<details open><summary>¿Cuál es la diferencia entre kW y kWh?</summary><p>El kW mide potencia, es decir, qué tan grande es el sistema en un instante. El kWh mide energía, es decir, la cantidad producida o consumida durante un tiempo. Tu factura se cobra en kWh.</p></details>
<details><summary>¿Qué son las horas sol pico?</summary><p>Es la radiación diaria expresada como horas con una intensidad de 1 kW por metro cuadrado. Si una ciudad tiene 5 horas sol pico, recibe unos 5 kWh/m² al día.</p></details>
<details><summary>¿Por qué hay pérdidas en el sistema?</summary><p>Por el inversor, el cableado, la temperatura de los paneles, la suciedad y las sombras. PVWatts usa 14 % por defecto.</p></details>
<details><summary>¿Funcionan los paneles en días nublados?</summary><p>Sí, pero producen menos. Con luz difusa generan solo una fracción de su potencia.</p></details>
<details><summary>¿Cuánto duran y qué mantenimiento necesitan?</summary><p>Suelen durar entre 20 y 30 años, perdiendo un poco de rendimiento cada año. Requieren limpieza con agua y una revisión técnica periódica.</p></details>
<details><summary>¿Puedo vender los excedentes?</summary><p>La regulación colombiana contempla la entrega de excedentes bajo ciertas condiciones. Consulta los requisitos con tu operador de red.</p></details>
<details><summary>¿Qué pasa si hay un apagón?</summary><p>Los sistemas conectados a la red se desconectan por seguridad durante un apagón. Para tener energía en ese caso se necesitan baterías.</p></details>
</section>
</div>
</main>
<dialog id='dlg'><div id='dlgc'></div></dialog>
<footer>Simulador Fotovoltaico – PVWatts · Proyecto de Ingeniería de Sistemas · Eficiencia energética y energías renovables</footer>

<script>
const CIUDADES={"Barranquilla":5.5,"Santa Marta":5.6,"Cartagena":5.4,"Riohacha":6.0,"Valledupar":5.3,"Montería":5.0,"Sincelejo":5.2,"Cúcuta":5.0,"Bucaramanga":4.6,"Medellín":4.6,"Cali":4.7,"Bogotá":4.2,"Tunja":4.4,"Manizales":4.2,"Pereira":4.4,"Neiva":5.0,"Villavicencio":4.5,"Pasto":4.2,"Quibdó":3.9,"Leticia":4.3};
const CARIBE=["Barranquilla","Santa Marta","Cartagena","Riohacha","Valledupar","Montería","Sincelejo"];
const F_CARIBE=[1.10,1.12,1.10,1.00,0.92,0.93,0.97,0.96,0.92,0.90,0.92,1.02];
const F_ANDES=[1.08,1.05,0.97,0.93,0.95,1.02,1.08,1.07,1.00,0.92,0.93,1.00];
const MESES=["Ene","Feb","Mar","Abr","May","Jun","Jul","Ago","Sep","Oct","Nov","Dic"];
const DIAS=[31,28,31,30,31,30,31,31,30,31,30,31];
const EJEMPLOS=[
{n:"Apartamento pequeño",c:"Bogotá",kwh:120,fact:95000,kw:1,perd:14,cub:80},
{n:"Casa mediana",c:"Barranquilla",kwh:300,fact:270000,kw:2.5,perd:14,cub:80},
{n:"Casa grande con aire acondicionado",c:"Barranquilla",kwh:650,fact:620000,kw:5,perd:14,cub:90},
{n:"Familia en Medellín",c:"Medellín",kwh:220,fact:180000,kw:1.8,perd:14,cub:75}];
const $=id=>document.getElementById(id);
const nf=(v,d=0)=>new Intl.NumberFormat("es-CO",{maximumFractionDigits:d,minimumFractionDigits:d}).format(v);
const cop=v=>"$ "+nf(v);
const RULES={kwh:[1,20000,"Consumo mensual"],fact:[1000,1e9,"Factura"],kw:[0.1,1000,"Potencia"],perd:[0,60,"Pérdidas"],cub:[1,100,"Cobertura"],costo:[500000,2e7,"Costo por kW"]};
let chart;Chart.defaults.font.family="Outfit,system-ui,sans-serif";const cs=getComputedStyle(document.documentElement);Chart.defaults.color=cs.getPropertyValue("--mut").trim();Chart.defaults.borderColor=cs.getPropertyValue("--line").trim();

$("ciudad").innerHTML=Object.keys(CIUDADES).map(c=>`<option>${c}</option>`).join("");
$("chips").innerHTML=EJEMPLOS.map((e,i)=>`<button class="chip" data-i="${i}">${e.n}</button>`).join("");

function load(e){$("ciudad").value=e.c;["kwh","fact","kw","perd","cub"].forEach(k=>$(k).value=e[k]);run()}
function read(){
  let ok=true;const v={};
  for(const k in RULES){
    const [mn,mx,nm]=RULES[k],el=$(k),raw=el.value.trim(),x=parseFloat(raw);
    let m="";
    if(raw===""||isNaN(x))m="Ingresa un número.";
    else if(x<mn||x>mx)m=`Debe estar entre ${nf(mn,1)} y ${nf(mx)}.`;
    el.classList.toggle("bad",!!m);
    document.querySelector(`[data-e="${k}"]`).textContent=m;
    if(m)ok=false;v[k]=x;
  }
  v.c=$("ciudad").value;
  return ok?v:null;
}
function model(v){
  const psh=CIUDADES[v.c],f=CARIBE.includes(v.c)?F_CARIBE:F_ANDES;
  const avg=f.reduce((a,b)=>a+b,0)/12;
  const gen=f.map((x,i)=>v.kw*psh*(x/avg)*DIAS[i]*(1-v.perd/100));
  const tarifa=v.fact/v.kwh;
  const meta=v.kwh*v.cub/100;
  // energía solar aprovechada: limitada por consumo y por la meta de cobertura
  const usada=gen.map(g=>Math.min(g,meta));
  const despues=usada.map(u=>v.kwh-u);
  const genM=gen.reduce((a,b)=>a+b,0)/12,usM=usada.reduce((a,b)=>a+b,0)/12;
  const redM=v.kwh-usM;
  const kwRec=meta/(psh*30.4*(1-v.perd/100));
  return{psh,gen,usada,despues,tarifa,genM,usM,redM,kwRec,genA:gen.reduce((a,b)=>a+b,0),
    redA:despues.reduce((a,b)=>a+b,0),
    ahM:usM*tarifa,ahA:usada.reduce((a,b)=>a+b,0)*tarifa,pct:usM/v.kwh*100};
}
function render(v,r){
  $("psh").textContent=`Radiación estimada: ${nf(r.psh,1)} horas sol pico/día (kWh/m²·día).`;
  $("rec").textContent=`Para cubrir ${nf(v.cub)} % necesitarías unos ${nf(r.kwRec,2)} kW. Ocuparía unos ${nf(v.kw/PAN[$('tipo').value].ef,0)} m² de techo.`;
  $("resSub").textContent=`${v.c} · ${nf(v.kw,1)} kW instalados · tarifa implícita de ${cop(r.tarifa)} por kWh`;
  $("k1").textContent=nf(r.genM,1);$("k2").textContent=nf(r.redM,1);
  $("k3").textContent=nf(r.pct,1)+" %";$("bar").style.width=Math.min(100,r.pct)+"%";
  $("k4").textContent=cop(r.ahM);$("k5").textContent=cop(r.ahA);
  $("k6").textContent=nf(v.kwh*12-r.redA,0);
  const co2=(v.kwh*12-r.redA)*.126,inv=v.kw*v.costo;$('k7').textContent=nf(co2,0);$('k8').textContent=nf(co2/20,0);$('k9').textContent=cop(inv);$('k10').textContent=r.ahA>0?nf(inv/r.ahA,1)+' años':'–';L={v,r};
  const costoD=r.redM*r.tarifa;
  $("tb").innerHTML=[
   ["Consumo energético mensual",nf(v.kwh,1)+" kWh",nf(r.redM,1)+" kWh (de la red)"],
   ["Consumo anual",nf(v.kwh*12)+" kWh",nf(r.redA)+" kWh"],
   ["Energía solar generada","0 kWh",nf(r.genM,1)+" kWh/mes · "+nf(r.genA)+" kWh/año"],
   ["Costo mensual",cop(v.fact),cop(costoD)],
   ["Costo anual",cop(v.fact*12),cop(costoD*12)]
  ].map(a=>`<tr><td>${a[0]}</td><td>${a[1]}</td><td>${a[2]}</td></tr>`).join("");
  const exc=r.genM-r.usM;
  $("msg").innerHTML=exc>1?`<div class="msg">Tu sistema produce en promedio ${nf(exc,1)} kWh/mes más de lo que necesitas para tu meta de cobertura. Podrías reducir la potencia o aumentar la cobertura deseada.</div>`:
   r.genM<v.kwh*v.cub/100-1?`<div class="msg">Con ${nf(v.kw,1)} kW no alcanzas el ${nf(v.cub)} % deseado. Prueba con unos ${nf(r.kwRec,2)} kW.</div>`:"";
  const data={labels:MESES,datasets:[
   {type:"line",label:"Consumo antes (kWh)",data:MESES.map(()=>+v.kwh.toFixed(1)),borderColor:"#CBD5E1",backgroundColor:"#CBD5E1",borderWidth:2,borderDash:[6,4],pointRadius:0,tension:0,order:0},
   {type:"bar",label:"Consumo después (kWh)",data:r.despues.map(x=>+x.toFixed(1)),backgroundColor:"#2563EB",borderRadius:6,order:1},
   {type:"bar",label:"Generación solar (kWh)",data:r.gen.map(x=>+x.toFixed(1)),backgroundColor:"#10B981",borderRadius:6,order:2}]};
  if(chart){chart.data=data;chart.update()}
  else chart=new Chart($("chart"),{data,options:{responsive:true,maintainAspectRatio:false,interaction:{mode:"index",intersect:false},
   plugins:{legend:{position:"bottom",labels:{boxWidth:10,boxHeight:10,usePointStyle:true,padding:16}},tooltip:{backgroundColor:"#0B1625",borderColor:"#2563EB",borderWidth:1,padding:12,cornerRadius:10,boxPadding:4,titleColor:"#F8FAFC",bodyColor:"#CBD5E1",callbacks:{label:c=>`${c.dataset.label}: ${nf(c.parsed.y,1)}`}}},
   scales:{x:{grid:{display:false},ticks:{autoSkip:false,maxRotation:60,minRotation:0}},y:{beginAtZero:true,grid:{color:"rgba(148,163,184,.14)"},title:{display:true,text:"kWh por mes"}}}}});
}
function run(){const v=read();if(!v)return;render(v,model(v))}
document.querySelectorAll("input,select").forEach(e=>e.addEventListener("input",run));
$("calc").onclick=()=>{run();$("res").scrollIntoView({behavior:"smooth"})};
$("chips").onclick=e=>{const b=e.target.closest(".chip");if(b)load(EJEMPLOS[b.dataset.i])};
$("reset").onclick=()=>load(EJEMPLOS[1]);
$("nueva").onclick=()=>{["kwh","fact","kw"].forEach(k=>$(k).value="");$("perd").value=14;$("cub").value=80;
  document.querySelectorAll(".err").forEach(e=>e.textContent="");document.querySelectorAll("input").forEach(e=>e.classList.remove("bad"));
  $("kwh").focus();$("form").scrollIntoView({behavior:"smooth"})};
let L;
const PAN={mono:{n:'Monocristalino',ef:.21,p:14,r:'20–23 %',v:'25–30 años',d:'Fabricado con un solo cristal de silicio. Es el más eficiente y ocupa menos espacio, aunque cuesta algo más.',u:'Techos pequeños o con poco espacio.'},poli:{n:'Policristalino',ef:.165,p:16,r:'15–18 %',v:'20–25 años',d:'Hecho con varios cristales de silicio fundidos. Es más económico y su rendimiento es menor.',u:'Techos amplios y presupuestos ajustados.'},fina:{n:'Película delgada',ef:.115,p:18,r:'10–13 %',v:'15–20 años',d:'Capas muy finas de material fotovoltaico. Es ligero y flexible, pero necesita más área para la misma potencia.',u:'Cubiertas livianas o superficies curvas.'},bi:{n:'Bifacial',ef:.21,p:12,r:'20–22 % más aporte posterior',v:'25–30 años',d:'Capta luz por ambas caras, incluida la reflejada por el suelo o la cubierta. Rinde más sobre superficies claras.',u:'Techos planos claros y estructuras elevadas.'}};
function psvg(t,w=240,h=150){const C={mono:['#12203a','#152642','#101c33'],poli:['#2a5a96','#2f66a6','#244f86'],fina:['#1d2733','#222e3b','#1a232e'],bi:['#1a2b44','#1d3150','#17263c']}[t];const f=t==='fina',cn=f?14:8,rn=f?1:5,gw=(w-36)/cn,gh=(h-36)/rn;let s=`<svg viewBox='0 0 ${w} ${h}' xmlns='http://www.w3.org/2000/svg' role='img' aria-label='Ilustración de panel ${PAN[t].n}'><rect width='${w}' height='${h}' fill='#13233A'/><rect x='12' y='12' width='${w-24}' height='${h-24}' rx='4' fill='${t==='bi'?'#c9d3de':'#aab6c4'}'/>`;for(let i=0;i<cn;i++)for(let j=0;j<rn;j++)s+=`<rect x='${18+i*gw+.8}' y='${18+j*gh+.8}' width='${gw-1.6}' height='${gh-1.6}' rx='${t==='mono'||t==='bi'?3:.5}' fill='${C[(i*7+j*3)%3]}'/>`;if(!f)for(let i=0;i<cn;i++)s+=`<path d='M${18+(i+.5)*gw} 18V${h-18}' stroke='#7f93b0' stroke-width='.5' opacity='.6'/>`;return s+`<path d='M12 ${h-12}L${w*.55} 12H${w*.8}L${w*.3} ${h-12}Z' fill='#fff' opacity='.1'/></svg>`}
function roofsvg(){let s=`<svg viewBox='0 0 600 240' xmlns='http://www.w3.org/2000/svg' role='img' aria-label='Ilustración de una vivienda con paneles solares'><rect width='600' height='240' fill='#13233A'/><circle cx='520' cy='56' r='26' fill='#CBD5E1'/><rect x='130' y='132' width='340' height='98' fill='#f7f9fb'/><rect x='170' y='160' width='50' height='70' fill='#2d5a7f'/><rect x='270' y='158' width='60' height='40' fill='#9fb2c8'/><rect x='370' y='158' width='60' height='40' fill='#9fb2c8'/><polygon points='100,132 190,50 410,50 500,132' fill='#6b7a8c'/><rect y='230' width='600' height='10' fill='#7f93a8'/>`;const tx=u=>210+180*u,bx=u=>150+300*u;for(let r=0;r<2;r++)for(let c=0;c<4;c++){const u0=c/4+.01,u1=(c+1)/4-.01,v0=r/2+.02,v1=(r+1)/2-.02,P=(u,v)=>[tx(u)+(bx(u)-tx(u))*v,62+66*v];s+=`<polygon points='${[P(u0,v0),P(u1,v0),P(u1,v1),P(u0,v1)].map(p=>p.map(Math.round).join(',')).join(' ')}' fill='#17304f' stroke='#9fb2c8' stroke-width='1'/>`}return s+'</svg>'}
function openP(k){const p=PAN[k];$('dlgc').innerHTML=`${psvg(k,320,180)}<h3 style='margin:14px 0 4px'>${p.n}</h3><p class='sub'>${p.d}</p><table><tr><td>Eficiencia</td><td>${p.r}</td></tr><tr><td>Vida útil</td><td>${p.v}</td></tr><tr><td>Pérdidas típicas</td><td>${p.p} %</td></tr><tr><td>Ideal para</td><td>${p.u}</td></tr></table><div class='row'><button class='btn main' data-use='${k}'>Usar en el simulador</button><button class='btn alt' data-x>Cerrar</button></div>`;$('dlg').showModal()}
function tab(t){document.querySelectorAll('.tab').forEach(e=>e.classList.toggle('on',e.id==='tab-'+t));document.querySelectorAll('.tabbtn').forEach(b=>b.classList.toggle('on',b.dataset.t===t));window.scrollTo({top:0,behavior:'smooth'})}
function copiar(){if(!L)return;const{v,r}=L,t=`Simulación fotovoltaica – ${v.c}\nSistema: ${nf(v.kw,1)} kW (${PAN[$('tipo').value].n})\nGeneración: ${nf(r.genM,1)} kWh/mes\nEnergía de la red después: ${nf(r.redM,1)} kWh/mes\nAhorro: ${nf(r.pct,1)} % · ${cop(r.ahM)} al mes · ${cop(r.ahA)} al año\nEstimación con fines educativos.`;const ok=()=>{$('cm').textContent='Resumen copiado.'},fb=()=>{const a=document.createElement('textarea');a.value=t;document.body.appendChild(a);a.select();try{document.execCommand('copy');ok()}catch(e){$('cm').textContent='No se pudo copiar automáticamente.'}a.remove()};if(navigator.clipboard)navigator.clipboard.writeText(t).then(ok,fb);else fb()}
const CK=['Revisé mi factura de los últimos 12 meses','Verifiqué que mi techo reciba sol sin sombras','Medí el área disponible','Confirmé que la estructura del techo es resistente','Pedí al menos tres cotizaciones','Consulté a mi operador de red sobre la conexión'];
$('roof').innerHTML=roofsvg();
$('pgrid').innerHTML=Object.keys(PAN).map(k=>`<button class='pcard' data-k='${k}'>${psvg(k)}<div><b>${PAN[k].n}</b><span>Eficiencia ${PAN[k].r} · Vida útil ${PAN[k].v}</span></div></button>`).join('');
$('tipo').innerHTML=Object.keys(PAN).map(k=>`<option value='${k}'>${PAN[k].n}</option>`).join('');
$('ck').innerHTML=CK.map(t=>`<label class='chk'><input type='checkbox'> ${t}</label>`).join('');
$('ck').onchange=()=>{const n=$('ck').querySelectorAll('input:checked').length;$('ckb').style.width=n/CK.length*100+'%';$('ckt').textContent=`${n} de ${CK.length} listos`};
$('tipo').onchange=()=>{$('perd').value=PAN[$('tipo').value].p;run()};
$('cp').onclick=copiar;
document.addEventListener('click',e=>{const t=e.target.closest('[data-t]'),g=e.target.closest('[data-go]'),c=e.target.closest('.pcard'),u=e.target.closest('[data-use]');if(t)tab(t.dataset.t);if(g)tab(g.dataset.go);if(c)openP(c.dataset.k);if(u){$('tipo').value=u.dataset.use;$('perd').value=PAN[u.dataset.use].p;$('dlg').close();tab('sim');run()}if(e.target.closest('[data-x]'))$('dlg').close()});
load(EJEMPLOS[1]);
</script>
</body>
</html>
