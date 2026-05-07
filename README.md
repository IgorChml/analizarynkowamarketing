<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html>
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <meta http-equiv="Content-Style-Type" content="text/css">
  <title></title>
  <meta name="Generator" content="Cocoa HTML Writer">
  <meta name="CocoaVersion" content="2685.4">
  <style type="text/css">
    p.p1 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica}
    p.p2 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica; min-height: 14.0px}
  </style>
</head>
<body>
<p class="p1">&lt;!DOCTYPE html&gt;</p>
<p class="p1">&lt;html lang="pl"&gt;</p>
<p class="p1">&lt;head&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;meta charset="UTF-8"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;title&gt;Infografika: Strategia Marketingowa SAP B1 w Polsce&lt;/title&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;script src="https://cdn.tailwindcss.com"&gt;&lt;/script&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;script src="https://cdn.jsdelivr.net/npm/chart.js"&gt;&lt;/script&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;style&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&amp;display=swap');</p>
<p class="p2"><span class="Apple-converted-space">        </span></p>
<p class="p1"><span class="Apple-converted-space">        </span>body {</p>
<p class="p1"><span class="Apple-converted-space">            </span>font-family: 'Poppins', sans-serif;</p>
<p class="p1"><span class="Apple-converted-space">            </span>background-color: #f8fafc;</p>
<p class="p1"><span class="Apple-converted-space">            </span>color: #0f172a;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.chart-container {</p>
<p class="p1"><span class="Apple-converted-space">            </span>position: relative;</p>
<p class="p1"><span class="Apple-converted-space">            </span>width: 100%;</p>
<p class="p1"><span class="Apple-converted-space">            </span>max-width: 600px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>margin-left: auto;</p>
<p class="p1"><span class="Apple-converted-space">            </span>margin-right: auto;</p>
<p class="p1"><span class="Apple-converted-space">            </span>height: 350px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>max-height: 400px;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>@media (min-width: 768px) {</p>
<p class="p1"><span class="Apple-converted-space">            </span>.chart-container {</p>
<p class="p1"><span class="Apple-converted-space">                </span>height: 400px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>}</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.metric-card {</p>
<p class="p1"><span class="Apple-converted-space">            </span>background: linear-gradient(135deg, #1d4ed8 0%, #2563eb 100%);</p>
<p class="p1"><span class="Apple-converted-space">            </span>color: white;</p>
<p class="p1"><span class="Apple-converted-space">            </span>transition: transform 0.3s ease;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><span class="Apple-converted-space">        </span></p>
<p class="p1"><span class="Apple-converted-space">        </span>.metric-card:hover {</p>
<p class="p1"><span class="Apple-converted-space">            </span>transform: translateY(-5px);</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.timeline-node {</p>
<p class="p1"><span class="Apple-converted-space">            </span>position: relative;</p>
<p class="p1"><span class="Apple-converted-space">            </span>padding-left: 2rem;</p>
<p class="p1"><span class="Apple-converted-space">            </span>border-left: 4px solid #f97316;</p>
<p class="p1"><span class="Apple-converted-space">            </span>margin-bottom: 1.5rem;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><span class="Apple-converted-space">        </span></p>
<p class="p1"><span class="Apple-converted-space">        </span>.timeline-node::before {</p>
<p class="p1"><span class="Apple-converted-space">            </span>content: '●';</p>
<p class="p1"><span class="Apple-converted-space">            </span>position: absolute;</p>
<p class="p1"><span class="Apple-converted-space">            </span>left: -11px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>top: 0;</p>
<p class="p1"><span class="Apple-converted-space">            </span>color: #f97316;</p>
<p class="p1"><span class="Apple-converted-space">            </span>font-size: 1.5rem;</p>
<p class="p1"><span class="Apple-converted-space">            </span>line-height: 1;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/style&gt;</p>
<p class="p1">&lt;/head&gt;</p>
<p class="p1">&lt;body class="antialiased"&gt;</p>
<p class="p2"><br></p>
<p class="p1">&lt;!--<span class="Apple-converted-space"> </span></p>
<p class="p1">Chosen Palette: Vibrant Tech (Blue-700, Orange-500, Teal-600, Slate-900)</p>
<p class="p1">Application Structure Plan: The infographic is structured as a vertical scrollable narrative. It starts with the "Hook" (market context and KPIs), moves into "Comparison" (radar chart of CompuTec vs Competitors), analyzes "Trends" (budget and conversion charts), and concludes with "Strategy" (a CSS-based flowchart of the new action plan). This structure takes the user from high-level context down to actionable steps logically.</p>
<p class="p1">Visualization &amp; Content Choices:<span class="Apple-converted-space"> </span></p>
<p class="p1">1. Key Metrics -&gt; Inform -&gt; Big Number Cards -&gt; High impact HTML/CSS styling.</p>
<p class="p1">2. Competitor Benchmarking -&gt; Compare -&gt; Radar Chart (Chart.js) -&gt; Best for multivariable gap analysis.</p>
<p class="p1">3. Budget Allocation -&gt; Organize -&gt; Doughnut Chart (Chart.js) -&gt; Shows part-to-whole clearly.</p>
<p class="p1">4. Channel Effectiveness -&gt; Compare -&gt; Horizontal Bar Chart (Chart.js) -&gt; Easy to read ranking of categories.</p>
<p class="p1">5. Strategic Blueprint -&gt; Organize -&gt; CSS Timeline Flow -&gt; No SVG/Mermaid used, pure structured HTML/CSS.</p>
<p class="p1">CONFIRMATION: NO SVG graphics used. NO Mermaid JS used.</p>
<p class="p1">--&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12"&gt;</p>
<p class="p2"><span class="Apple-converted-space">        </span></p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;header class="text-center mb-16"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;h1 class="text-4xl md:text-5xl font-bold text-slate-900 mb-4 tracking-tight"&gt;Transformacja Marketingowa: &lt;span class="text-blue-700"&gt;Ekosystem SAP B1&lt;/span&gt;&lt;/h1&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;p class="text-lg text-slate-600 max-w-3xl mx-auto"&gt;Strategiczna analiza krajobrazu konkurencyjnego w Polsce oraz mapa drogowa dla firmy CompuTec w celu dominacji w niszy rozwiązań ERP dla produkcji.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/header&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;section class="mb-20"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="bg-white rounded-2xl shadow-md p-8 border-t-4 border-blue-600"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;h2 class="text-2xl font-bold text-slate-800 mb-4"&gt;&amp;#128200; Krajobraz Rynkowy 2026&lt;/h2&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;p class="text-slate-600 mb-8 leading-relaxed"&gt;Polska branża ERP dla segmentu MŚP przechodzi ewolucję. Klienci podejmują decyzje w oparciu o samodzielny research i edukację, odrzucając tradycyjne, agresywne metody sprzedaży. Poniższe wskaźniki ilustrują tę zmianę paradygmatu zakupowego.&lt;/p&gt;</p>
<p class="p2"><span class="Apple-converted-space">                </span></p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="grid grid-cols-1 md:grid-cols-3 gap-6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="metric-card rounded-xl shadow-lg p-6 text-center"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;div class="text-4xl mb-2"&gt;&amp;#128269;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;div class="text-5xl font-bold mb-2"&gt;72%&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;div class="text-sm font-semibold opacity-90 uppercase tracking-wide"&gt;Decyzji zakupowych B2B&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;div class="text-xs opacity-75 mt-2"&gt;Jest podejmowanych przed pierwszym kontaktem z handlowcem.&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="metric-card rounded-xl shadow-lg p-6 text-center" style="background: linear-gradient(135deg, #0f766e 0%, #14b8a6 100%);"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;div class="text-4xl mb-2"&gt;&amp;#128187;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;div class="text-5xl font-bold mb-2"&gt;3.5x&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;div class="text-sm font-semibold opacity-90 uppercase tracking-wide"&gt;Wyższy ROI&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;div class="text-xs opacity-75 mt-2"&gt;Z działań Content Marketingowych w porównaniu do reklam Paid Ads.&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="metric-card rounded-xl shadow-lg p-6 text-center" style="background: linear-gradient(135deg, #ea580c 0%, #f97316 100%);"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;div class="text-4xl mb-2"&gt;&amp;#11088;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;div class="text-5xl font-bold mb-2"&gt;Nr 1&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;div class="text-sm font-semibold opacity-90 uppercase tracking-wide"&gt;Przewaga CompuTec&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;div class="text-xs opacity-75 mt-2"&gt;Własne rozwiązania IP (ProcessForce, PDC) stanowiące potężny unikalny wyróżnik.&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;section class="mb-20"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="bg-white rounded-2xl shadow-md p-8 border-t-4 border-orange-500"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;h2 class="text-2xl font-bold text-slate-800 mb-4"&gt;&amp;#9876;&amp;#65039; Benchmarking Konkurencji&lt;/h2&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;p class="text-slate-600 mb-8 leading-relaxed"&gt;Analiza aktywności głównych graczy na rynku (np. Altab, Supemis) w porównaniu do obecnych działań CompuTec. Wykres ukazuje istotną lukę w obszarze widoczności online i budowania wizerunku, przy jednoczesnej druzgocącej przewadze technologicznej CompuTec.&lt;/p&gt;</p>
<p class="p2"><span class="Apple-converted-space">                </span></p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="chart-container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;canvas id="radarChart"&gt;&lt;/canvas&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;h3 class="text-xl font-bold text-slate-800 mb-4"&gt;Wnioski z analizy:&lt;/h3&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;ul class="space-y-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                            </span>&lt;li class="bg-slate-50 p-4 rounded-lg border border-slate-100"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                                </span>&lt;strong class="text-orange-600 block mb-1"&gt;&amp;#128680; Deficyt Social Sellingu:&lt;/strong&gt; Konkurencja agresywnie wykorzystuje LinkedIn do budowania relacji i marek osobistych ekspertów. CompuTec opiera się na komunikacji korporacyjnej.</p>
<p class="p1"><span class="Apple-converted-space">                            </span>&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">                            </span>&lt;li class="bg-slate-50 p-4 rounded-lg border border-slate-100"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                                </span>&lt;strong class="text-blue-600 block mb-1"&gt;&amp;#128221; Dominacja Treści (SEO):&lt;/strong&gt; Konkurenci inwestują w blogi eksperckie, poradniki KSeF i studia przypadków (Case Studies), przechwytując ruch z wyszukiwarek na wczesnym etapie lejka.</p>
<p class="p1"><span class="Apple-converted-space">                            </span>&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">                            </span>&lt;li class="bg-slate-50 p-4 rounded-lg border border-slate-100"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                                </span>&lt;strong class="text-teal-600 block mb-1"&gt;&amp;#128640; Niewykorzystany Potencjał IP:&lt;/strong&gt; Niedościgniona przewaga CompuTec (ProcessForce) wymaga lepszego "opakowania" marketingowego, skupionego na korzyściach biznesowych zamiast list funkcji.</p>
<p class="p1"><span class="Apple-converted-space">                            </span>&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;/ul&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;section class="mb-20"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="bg-white rounded-2xl shadow-md p-8 border-t-4 border-teal-600"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;h2 class="text-2xl font-bold text-slate-800 mb-4"&gt;&amp;#128202; Analiza Kanałów i Skuteczności&lt;/h2&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;p class="text-slate-600 mb-8 leading-relaxed"&gt;Zrozumienie, gdzie rynek lokuje budżety marketingowe i które z tych inwestycji generują faktyczne konwersje, jest kluczowe dla optymalizacji wydatków CompuTec.&lt;/p&gt;</p>
<p class="p2"><span class="Apple-converted-space">                </span></p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="grid grid-cols-1 lg:grid-cols-2 gap-12"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;h3 class="text-center font-bold text-slate-700 mb-2"&gt;Alokacja Budżetu Marketingowego B2B (ERP)&lt;/h3&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;p class="text-center text-sm text-slate-500 mb-6"&gt;Procentowy podział wydatków wg kanałów&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;div class="chart-container" style="height: 300px;"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                            </span>&lt;canvas id="doughnutChart"&gt;&lt;/canvas&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;p class="mt-4 text-sm text-slate-600 text-center"&gt;Inwestycje płyną przede wszystkim w stronę wartościowych treści edukacyjnych i bezpośredniego kontaktu eksperckiego.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;h3 class="text-center font-bold text-slate-700 mb-2"&gt;Skuteczność Konwersji (Lead -&gt; Szansa Sprzedaży)&lt;/h3&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;p class="text-center text-sm text-slate-500 mb-6"&gt;Procent leadów kwalifikujących się do dalszego procesu&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;div class="chart-container" style="height: 300px;"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                            </span>&lt;canvas id="barChart"&gt;&lt;/canvas&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;p class="mt-4 text-sm text-slate-600 text-center"&gt;Najwyższą jakość generują rekomendacje oraz ruch z dobrze spozycjonowanych, specjalistycznych artykułów.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;section class="mb-10"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="bg-slate-900 rounded-2xl shadow-xl p-8 text-white"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;h2 class="text-2xl font-bold mb-4 text-orange-400"&gt;&amp;#128161; Strategiczny Blueprint dla CompuTec&lt;/h2&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;p class="text-slate-300 mb-10 leading-relaxed"&gt;Zalecana ewolucja działań od komunikacji technicznej w stronę strategii "Thought Leadership" skupionej wokół potrzeb branży produkcyjnej.&lt;/p&gt;</p>
<p class="p2"><span class="Apple-converted-space">                </span></p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="grid grid-cols-1 md:grid-cols-2 gap-8"&gt;</p>
<p class="p2"><span class="Apple-converted-space">                    </span></p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="timeline-node"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;h3 class="text-xl font-bold text-white mb-2"&gt;1. Ewolucja Przekazu (Value Proposition)&lt;/h3&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;p class="text-slate-400 text-sm"&gt;Zmiana narracji wokół ProcessForce. Zamiast mówić "Moduł Posiada Funkcję X", komunikujemy "Redukcja Przestojów o 15% z ProcessForce". Wdrożenie interaktywnych kalkulatorów ROI na stronie docelowej.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;/div&gt;</p>
<p class="p2"><span class="Apple-converted-space">                    </span></p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="timeline-node"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;h3 class="text-xl font-bold text-white mb-2"&gt;2. Employee Advocacy (Ludzkie Oblicze)&lt;/h3&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;p class="text-slate-400 text-sm"&gt;Firmy B2B kupują od ekspertów, nie od logo. Wytypowanie 3 ambasadorów wewnątrz CompuTec (konsultanci, zarząd) do regularnego dzielenia się ekspercką wiedzą z wdrożeń na prywatnych kontach LinkedIn.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;/div&gt;</p>
<p class="p2"><span class="Apple-converted-space">                    </span></p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="timeline-node"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;h3 class="text-xl font-bold text-white mb-2"&gt;3. Wąska Specjalizacja (Niche Dominance)&lt;/h3&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;p class="text-slate-400 text-sm"&gt;Unikanie kosztownej walki na ogólne hasło "SAP B1". Pozycjonowanie się jako absolutny lider wdrażania SAP B1 &lt;strong&gt;dla produkcji&lt;/strong&gt;. Tworzenie dedykowanych raportów branżowych ("Stan cyfryzacji produkcji 2026").&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="timeline-node"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;h3 class="text-xl font-bold text-white mb-2"&gt;4. Synergia Partnerska (Co-marketing)&lt;/h3&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;p class="text-slate-400 text-sm"&gt;Nawiązywanie strategicznych partnerstw z dostawcami maszyn przemysłowych i automatyki (Industry 4.0). Organizacja wspólnych webinarów prezentujących integrację sprzętu z systemem CompuTec PDC.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;script&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>const wrapLabelLogic = (label) =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">            </span>if (label.length &lt;= 16) return label;</p>
<p class="p1"><span class="Apple-converted-space">            </span>const words = label.split(' ');</p>
<p class="p1"><span class="Apple-converted-space">            </span>let lines = [];</p>
<p class="p1"><span class="Apple-converted-space">            </span>let currentLine = words[0];</p>
<p class="p1"><span class="Apple-converted-space">            </span>for (let i = 1; i &lt; words.length; i++) {</p>
<p class="p1"><span class="Apple-converted-space">                </span>if (currentLine.length + words[i].length + 1 &lt;= 16) {</p>
<p class="p1"><span class="Apple-converted-space">                    </span>currentLine += ' ' + words[i];</p>
<p class="p1"><span class="Apple-converted-space">                </span>} else {</p>
<p class="p1"><span class="Apple-converted-space">                    </span>lines.push(currentLine);</p>
<p class="p1"><span class="Apple-converted-space">                    </span>currentLine = words[i];</p>
<p class="p1"><span class="Apple-converted-space">                </span>}</p>
<p class="p1"><span class="Apple-converted-space">            </span>}</p>
<p class="p1"><span class="Apple-converted-space">            </span>lines.push(currentLine);</p>
<p class="p1"><span class="Apple-converted-space">            </span>return lines;</p>
<p class="p1"><span class="Apple-converted-space">        </span>};</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>const globalTooltipConfig = {</p>
<p class="p1"><span class="Apple-converted-space">            </span>tooltip: {</p>
<p class="p1"><span class="Apple-converted-space">                </span>callbacks: {</p>
<p class="p1"><span class="Apple-converted-space">                    </span>title: function(tooltipItems) {</p>
<p class="p1"><span class="Apple-converted-space">                        </span>const item = tooltipItems[0];</p>
<p class="p1"><span class="Apple-converted-space">                        </span>let label = item.chart.data.labels[item.dataIndex];</p>
<p class="p1"><span class="Apple-converted-space">                        </span>if (Array.isArray(label)) {</p>
<p class="p1"><span class="Apple-converted-space">                            </span>return label.join(' ');</p>
<p class="p1"><span class="Apple-converted-space">                        </span>} else {</p>
<p class="p1"><span class="Apple-converted-space">                            </span>return label;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>}</p>
<p class="p1"><span class="Apple-converted-space">                    </span>}</p>
<p class="p1"><span class="Apple-converted-space">                </span>},</p>
<p class="p1"><span class="Apple-converted-space">                </span>backgroundColor: 'rgba(15, 23, 42, 0.9)',</p>
<p class="p1"><span class="Apple-converted-space">                </span>titleFont: { family: 'Poppins', size: 14 },</p>
<p class="p1"><span class="Apple-converted-space">                </span>bodyFont: { family: 'Poppins', size: 13 },</p>
<p class="p1"><span class="Apple-converted-space">                </span>padding: 12</p>
<p class="p1"><span class="Apple-converted-space">            </span>}</p>
<p class="p1"><span class="Apple-converted-space">        </span>};</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>const initRadarChart = () =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">            </span>const ctx = document.getElementById('radarChart').getContext('2d');</p>
<p class="p1"><span class="Apple-converted-space">            </span>const rawLabels = ['Widoczność SEO (Artykuły/Blog)', 'Webinary i Eventy Edukacyjne', 'Social Selling (Eksperci LinkedIn)', 'Case Studies i Dowody ROI', 'Własne Produkty (IP) / Przewaga'];</p>
<p class="p2"><span class="Apple-converted-space">            </span></p>
<p class="p1"><span class="Apple-converted-space">            </span>new Chart(ctx, {</p>
<p class="p1"><span class="Apple-converted-space">                </span>type: 'radar',</p>
<p class="p1"><span class="Apple-converted-space">                </span>data: {</p>
<p class="p1"><span class="Apple-converted-space">                    </span>labels: rawLabels.map(wrapLabelLogic),</p>
<p class="p1"><span class="Apple-converted-space">                    </span>datasets: [</p>
<p class="p1"><span class="Apple-converted-space">                        </span>{</p>
<p class="p1"><span class="Apple-converted-space">                            </span>label: 'Średnia Konkurencji',</p>
<p class="p1"><span class="Apple-converted-space">                            </span>data: [8, 8, 7, 9, 4],</p>
<p class="p1"><span class="Apple-converted-space">                            </span>backgroundColor: 'rgba(148, 163, 184, 0.2)',</p>
<p class="p1"><span class="Apple-converted-space">                            </span>borderColor: 'rgba(100, 116, 139, 1)',</p>
<p class="p1"><span class="Apple-converted-space">                            </span>pointBackgroundColor: 'rgba(100, 116, 139, 1)',</p>
<p class="p1"><span class="Apple-converted-space">                            </span>borderWidth: 2</p>
<p class="p1"><span class="Apple-converted-space">                        </span>},</p>
<p class="p1"><span class="Apple-converted-space">                        </span>{</p>
<p class="p1"><span class="Apple-converted-space">                            </span>label: 'CompuTec Obecnie',</p>
<p class="p1"><span class="Apple-converted-space">                            </span>data: [5, 6, 4, 7, 10],</p>
<p class="p1"><span class="Apple-converted-space">                            </span>backgroundColor: 'rgba(29, 78, 216, 0.4)',</p>
<p class="p1"><span class="Apple-converted-space">                            </span>borderColor: 'rgba(29, 78, 216, 1)',</p>
<p class="p1"><span class="Apple-converted-space">                            </span>pointBackgroundColor: 'rgba(29, 78, 216, 1)',</p>
<p class="p1"><span class="Apple-converted-space">                            </span>borderWidth: 2</p>
<p class="p1"><span class="Apple-converted-space">                        </span>}</p>
<p class="p1"><span class="Apple-converted-space">                    </span>]</p>
<p class="p1"><span class="Apple-converted-space">                </span>},</p>
<p class="p1"><span class="Apple-converted-space">                </span>options: {</p>
<p class="p1"><span class="Apple-converted-space">                    </span>responsive: true,</p>
<p class="p1"><span class="Apple-converted-space">                    </span>maintainAspectRatio: false,</p>
<p class="p1"><span class="Apple-converted-space">                    </span>plugins: {</p>
<p class="p1"><span class="Apple-converted-space">                        </span>...globalTooltipConfig,</p>
<p class="p1"><span class="Apple-converted-space">                        </span>legend: { position: 'bottom', labels: { font: { family: 'Poppins' }, color: '#334155' } }</p>
<p class="p1"><span class="Apple-converted-space">                    </span>},</p>
<p class="p1"><span class="Apple-converted-space">                    </span>scales: {</p>
<p class="p1"><span class="Apple-converted-space">                        </span>r: {</p>
<p class="p1"><span class="Apple-converted-space">                            </span>angleLines: { color: 'rgba(0, 0, 0, 0.1)' },</p>
<p class="p1"><span class="Apple-converted-space">                            </span>grid: { color: 'rgba(0, 0, 0, 0.1)' },</p>
<p class="p1"><span class="Apple-converted-space">                            </span>pointLabels: { font: { family: 'Poppins', size: 11, weight: '600' }, color: '#475569' },</p>
<p class="p1"><span class="Apple-converted-space">                            </span>ticks: { min: 0, max: 10, stepSize: 2, display: false }</p>
<p class="p1"><span class="Apple-converted-space">                        </span>}</p>
<p class="p1"><span class="Apple-converted-space">                    </span>}</p>
<p class="p1"><span class="Apple-converted-space">                </span>}</p>
<p class="p1"><span class="Apple-converted-space">            </span>});</p>
<p class="p1"><span class="Apple-converted-space">        </span>};</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>const initDoughnutChart = () =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">            </span>const ctx = document.getElementById('doughnutChart').getContext('2d');</p>
<p class="p1"><span class="Apple-converted-space">            </span>const rawLabels = ['Treści Eksperckie i SEO', 'Wydarzenia i Webinary', 'Płatne Kampanie Ads', 'Social Media (Firmowe)', 'Inne (PR, Offline)'];</p>
<p class="p2"><span class="Apple-converted-space">            </span></p>
<p class="p1"><span class="Apple-converted-space">            </span>new Chart(ctx, {</p>
<p class="p1"><span class="Apple-converted-space">                </span>type: 'doughnut',</p>
<p class="p1"><span class="Apple-converted-space">                </span>data: {</p>
<p class="p1"><span class="Apple-converted-space">                    </span>labels: rawLabels.map(wrapLabelLogic),</p>
<p class="p1"><span class="Apple-converted-space">                    </span>datasets: [{</p>
<p class="p1"><span class="Apple-converted-space">                        </span>data: [35, 25, 20, 15, 5],</p>
<p class="p1"><span class="Apple-converted-space">                        </span>backgroundColor: [</p>
<p class="p1"><span class="Apple-converted-space">                            </span>'#1d4ed8',<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">                            </span>'#0f766e',<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">                            </span>'#f97316',<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">                            </span>'#eab308',<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">                            </span>'#64748b' <span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">                        </span>],</p>
<p class="p1"><span class="Apple-converted-space">                        </span>borderWidth: 0,</p>
<p class="p1"><span class="Apple-converted-space">                        </span>hoverOffset: 4</p>
<p class="p1"><span class="Apple-converted-space">                    </span>}]</p>
<p class="p1"><span class="Apple-converted-space">                </span>},</p>
<p class="p1"><span class="Apple-converted-space">                </span>options: {</p>
<p class="p1"><span class="Apple-converted-space">                    </span>responsive: true,</p>
<p class="p1"><span class="Apple-converted-space">                    </span>maintainAspectRatio: false,</p>
<p class="p1"><span class="Apple-converted-space">                    </span>cutout: '65%',</p>
<p class="p1"><span class="Apple-converted-space">                    </span>plugins: {</p>
<p class="p1"><span class="Apple-converted-space">                        </span>...globalTooltipConfig,</p>
<p class="p1"><span class="Apple-converted-space">                        </span>legend: { position: 'right', labels: { font: { family: 'Poppins', size: 12 } } }</p>
<p class="p1"><span class="Apple-converted-space">                    </span>}</p>
<p class="p1"><span class="Apple-converted-space">                </span>}</p>
<p class="p1"><span class="Apple-converted-space">            </span>});</p>
<p class="p1"><span class="Apple-converted-space">        </span>};</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>const initBarChart = () =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">            </span>const ctx = document.getElementById('barChart').getContext('2d');</p>
<p class="p1"><span class="Apple-converted-space">            </span>const rawLabels = ['Rekomendacje i Partnerzy', 'Organiczne Wyszukiwania (SEO)', 'Webinary Eksperckie', 'LinkedIn Social Selling', 'Zimne Maile i Telefony'];</p>
<p class="p2"><span class="Apple-converted-space">            </span></p>
<p class="p1"><span class="Apple-converted-space">            </span>new Chart(ctx, {</p>
<p class="p1"><span class="Apple-converted-space">                </span>type: 'bar',</p>
<p class="p1"><span class="Apple-converted-space">                </span>data: {</p>
<p class="p1"><span class="Apple-converted-space">                    </span>labels: rawLabels.map(wrapLabelLogic),</p>
<p class="p1"><span class="Apple-converted-space">                    </span>datasets: [{</p>
<p class="p1"><span class="Apple-converted-space">                        </span>label: 'Współczynnik Konwersji (%)',</p>
<p class="p1"><span class="Apple-converted-space">                        </span>data: [14.5, 9.2, 7.8, 4.5, 1.2],</p>
<p class="p1"><span class="Apple-converted-space">                        </span>backgroundColor: '#0f766e',</p>
<p class="p1"><span class="Apple-converted-space">                        </span>borderRadius: 6</p>
<p class="p1"><span class="Apple-converted-space">                    </span>}]</p>
<p class="p1"><span class="Apple-converted-space">                </span>},</p>
<p class="p1"><span class="Apple-converted-space">                </span>options: {</p>
<p class="p1"><span class="Apple-converted-space">                    </span>responsive: true,</p>
<p class="p1"><span class="Apple-converted-space">                    </span>maintainAspectRatio: false,</p>
<p class="p1"><span class="Apple-converted-space">                    </span>indexAxis: 'y',</p>
<p class="p1"><span class="Apple-converted-space">                    </span>plugins: {</p>
<p class="p1"><span class="Apple-converted-space">                        </span>...globalTooltipConfig,</p>
<p class="p1"><span class="Apple-converted-space">                        </span>legend: { display: false }</p>
<p class="p1"><span class="Apple-converted-space">                    </span>},</p>
<p class="p1"><span class="Apple-converted-space">                    </span>scales: {</p>
<p class="p1"><span class="Apple-converted-space">                        </span>x: {</p>
<p class="p1"><span class="Apple-converted-space">                            </span>grid: { color: 'rgba(0,0,0,0.05)' },</p>
<p class="p1"><span class="Apple-converted-space">                            </span>title: { display: true, text: 'Konwersja (%)', font: { family: 'Poppins' } }</p>
<p class="p1"><span class="Apple-converted-space">                        </span>},</p>
<p class="p1"><span class="Apple-converted-space">                        </span>y: {</p>
<p class="p1"><span class="Apple-converted-space">                            </span>grid: { display: false },</p>
<p class="p1"><span class="Apple-converted-space">                            </span>ticks: { font: { family: 'Poppins', size: 11, weight: '600' }, color: '#475569' }</p>
<p class="p1"><span class="Apple-converted-space">                        </span>}</p>
<p class="p1"><span class="Apple-converted-space">                    </span>}</p>
<p class="p1"><span class="Apple-converted-space">                </span>}</p>
<p class="p1"><span class="Apple-converted-space">            </span>});</p>
<p class="p1"><span class="Apple-converted-space">        </span>};</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>document.addEventListener('DOMContentLoaded', () =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">            </span>initRadarChart();</p>
<p class="p1"><span class="Apple-converted-space">            </span>initDoughnutChart();</p>
<p class="p1"><span class="Apple-converted-space">            </span>initBarChart();</p>
<p class="p1"><span class="Apple-converted-space">        </span>});</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/script&gt;</p>
<p class="p1">&lt;/body&gt;</p>
<p class="p1">&lt;/html&gt;</p>
</body>
</html>
