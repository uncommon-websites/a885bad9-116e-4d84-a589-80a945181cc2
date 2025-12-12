<script>
    import Navbar from '$lib/components/Navbar.svelte';
    import Footer from '$lib/components/Footer.svelte';
    import FeatureRow from '$lib/components/FeatureRow.svelte';
</script>

<div class="bg-[var(--color-tactic-dark)] min-h-screen flex flex-col">
    <Navbar />

    <main class="flex-grow">
        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="max-w-4xl mx-auto text-center">
                    <!-- Search/Notification Pill -->
                    <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-sm border border-white/10 rounded-full px-4 py-1.5 mb-8">
                        <span class="w-2 h-2 rounded-full bg-[var(--color-tactic-primary)]"></span>
                        <span class="text-white text-sm font-medium">300+ Teams</span>
                        <span class="text-gray-400 text-sm">trust Tactic Systems</span>
                        <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                    </div>

                    <h1 class="text-5xl md:text-7xl font-bold text-white tracking-tight mb-6 text-balance">
                        Turn sales data into actionable insights.
                    </h1>
                    
                    <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed text-balance">
                        Centralize your business data into interactive dashboards with automated API integration. Built for automotive dealerships and sales teams who need real-time performance insights without the complexity.
                    </p>
                    
                    <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                        <button class="bg-[var(--color-tactic-primary)] hover:bg-[var(--color-tactic-primary-hover)] text-white px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            Start Free Trial
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                        <button class="bg-transparent border border-white/20 hover:bg-white/10 text-white px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            View Demo
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Hero Images/Cards -->
            <div class="mt-20 relative">
                <div class="flex justify-center gap-6 overflow-hidden px-6">
                    <!-- Card 1 -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform -rotate-2 mt-8">
                        <div class="bg-white p-4">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-600">Team Performance</div>
                                <div class="h-8 w-24 bg-[var(--color-tactic-primary)]/20 rounded text-[var(--color-tactic-primary)] text-xs flex items-center justify-center font-bold">+24.5%</div>
                            </div>
                            <div class="space-y-3">
                                <div class="h-24 bg-gradient-to-br from-gray-100 to-gray-200 rounded-lg w-full flex items-end justify-around p-2">
                                    <div class="w-8 bg-[var(--color-tactic-primary)] rounded-t" style="height: 60%"></div>
                                    <div class="w-8 bg-[var(--color-tactic-primary)]/70 rounded-t" style="height: 80%"></div>
                                    <div class="w-8 bg-[var(--color-tactic-primary)]/50 rounded-t" style="height: 45%"></div>
                                    <div class="w-8 bg-[var(--color-tactic-primary)]/30 rounded-t" style="height: 70%"></div>
                                </div>
                                <div class="h-4 w-full bg-gray-50 rounded"></div>
                                <div class="h-4 w-2/3 bg-gray-50 rounded"></div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 2 (Center) -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 z-10">
                        <div class="bg-white h-full flex flex-col">
                            <div class="bg-[var(--color-tactic-primary)] p-6">
                                <div class="flex justify-between items-center">
                                    <div class="text-white font-bold text-sm">Sales Dashboard</div>
                                    <div class="h-8 w-8 bg-white/20 rounded-full"></div>
                                </div>
                            </div>
                            <div class="p-6 flex-grow">
                                <div class="grid grid-cols-2 gap-4 mb-6">
                                    <div class="space-y-2">
                                        <div class="text-xs text-gray-500">Total Sales</div>
                                        <div class="text-2xl font-bold text-gray-900">$2.4M</div>
                                    </div>
                                    <div class="space-y-2">
                                        <div class="text-xs text-gray-500">Conversions</div>
                                        <div class="text-2xl font-bold text-gray-900">342</div>
                                    </div>
                                </div>
                                <div class="space-y-2">
                                    <div class="h-2 w-full bg-gray-100 rounded"></div>
                                    <div class="h-2 w-full bg-gray-100 rounded"></div>
                                    <div class="h-2 w-full bg-gray-100 rounded"></div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 3 -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform rotate-2 mt-8">
                        <div class="bg-white p-4">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-600">Monthly KPIs</div>
                                <div class="h-8 w-24 bg-green-100 rounded text-green-600 text-xs flex items-center justify-center font-bold">On Track</div>
                            </div>
                            <div class="space-y-3">
                                <div class="h-24 bg-gray-100 rounded-lg w-full p-3 flex flex-col justify-around">
                                    <div class="flex justify-between items-center">
                                        <span class="text-xs text-gray-500">Avg Response</span>
                                        <div class="h-2 w-24 bg-[var(--color-tactic-primary)] rounded-full"></div>
                                    </div>
                                    <div class="flex justify-between items-center">
                                        <span class="text-xs text-gray-500">Close Rate</span>
                                        <div class="h-2 w-20 bg-[var(--color-tactic-primary)] rounded-full"></div>
                                    </div>
                                    <div class="flex justify-between items-center">
                                        <span class="text-xs text-gray-500">Follow-ups</span>
                                        <div class="h-2 w-16 bg-[var(--color-tactic-primary)] rounded-full"></div>
                                    </div>
                                </div>
                                <div class="h-4 w-full bg-gray-50 rounded"></div>
                                <div class="h-4 w-2/3 bg-gray-50 rounded"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Logos Section -->
        <section class="py-12 border-y border-white/5 bg-black/20">
            <div class="container mx-auto px-6">
                <p class="text-center text-gray-500 text-sm mb-8">Trusted by leading automotive brands</p>
                <div class="flex flex-wrap justify-center items-center gap-12 md:gap-20 opacity-60">
                    <div class="text-white font-bold text-2xl tracking-wider">BMW</div>
                    <div class="text-white font-bold text-2xl tracking-wider">MINI</div>
                    <div class="text-white font-bold text-2xl tracking-wider">VOLVO</div>
                    <div class="text-white font-bold text-2xl tracking-wider">BYD</div>
                    <div class="text-white font-bold text-2xl tracking-wider">CHEVROLET</div>
                </div>
            </div>
        </section>

        <!-- Tactic Platform Section -->
        <section class="py-32 relative overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="text-center mb-24">
                    <h2 class="text-[var(--color-tactic-primary)] font-mono text-xs tracking-[0.2em] uppercase mb-6">Tactic Platform</h2>
                    <h3 class="text-4xl md:text-6xl font-bold text-white mb-2 tracking-tight">A business intelligence platform.</h3>
                    <h3 class="text-4xl md:text-6xl font-bold text-gray-600 tracking-tight">Built for sales teams.</h3>
                </div>

                <div class="grid md:grid-cols-2 gap-16 items-center max-w-6xl mx-auto">
                    <!-- Dashboard Card -->
                    <div class="bg-gradient-to-br from-[var(--color-tactic-primary)] to-[var(--color-tactic-primary-hover)] rounded-3xl p-12 aspect-[4/3] relative overflow-hidden flex items-center justify-center shadow-2xl">
                        <!-- Abstract UI Elements -->
                        <div class="relative z-10 w-full max-w-[320px]">
                            <!-- Dashboard Card -->
                            <div class="bg-white/10 backdrop-blur-xl border border-white/20 rounded-2xl p-6 mb-8 shadow-xl relative overflow-hidden group hover:scale-105 transition-transform duration-500">
                                <div class="text-white/80 text-xs uppercase tracking-wider font-medium mb-4">Real-Time Analytics</div>
                                <div class="grid grid-cols-2 gap-4 mb-4">
                                    <div>
                                        <div class="text-white/60 text-[10px] uppercase">Sales Today</div>
                                        <div class="text-white font-bold text-2xl">$47.2K</div>
                                    </div>
                                    <div>
                                        <div class="text-white/60 text-[10px] uppercase">Conversions</div>
                                        <div class="text-white font-bold text-2xl">23</div>
                                    </div>
                                </div>
                                <div class="h-16 flex items-end gap-1">
                                    {#each [40, 60, 30, 70, 50, 80, 65, 90] as h}
                                        <div class="w-full bg-white/40 rounded-t" style="height: {h}%"></div>
                                    {/each}
                                </div>
                            </div>
                            
                            <!-- Floating Pills -->
                            <div class="relative">
                                <div class="absolute -left-4 top-0 bg-white text-black px-5 py-2.5 rounded-full text-sm font-semibold shadow-lg flex items-center gap-2 transform -rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-[var(--color-tactic-primary)]/20 flex items-center justify-center text-[var(--color-tactic-primary)]">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path d="M9 2a1 1 0 000 2h2a1 1 0 100-2H9z"/><path fill-rule="evenodd" d="M4 5a2 2 0 012-2 3 3 0 003 3h2a3 3 0 003-3 2 2 0 012 2v11a2 2 0 01-2 2H6a2 2 0 01-2-2V5zm3 4a1 1 0 000 2h.01a1 1 0 100-2H7zm3 0a1 1 0 000 2h3a1 1 0 100-2h-3zm-3 4a1 1 0 100 2h.01a1 1 0 100-2H7zm3 0a1 1 0 100 2h3a1 1 0 100-2h-3z" clip-rule="evenodd"/></svg>
                                    </div>
                                    50+ Visualizations
                                </div>
                                <div class="absolute -right-4 top-12 bg-white/10 backdrop-blur-md text-white px-5 py-2.5 rounded-full text-sm font-semibold border border-white/20 flex items-center gap-2 transform rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-white/20 flex items-center justify-center">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path d="M2 11a1 1 0 011-1h2a1 1 0 011 1v5a1 1 0 01-1 1H3a1 1 0 01-1-1v-5zM8 7a1 1 0 011-1h2a1 1 0 011 1v9a1 1 0 01-1 1H9a1 1 0 01-1-1V7zM14 4a1 1 0 011-1h2a1 1 0 011 1v12a1 1 0 01-1 1h-2a1 1 0 01-1-1V4z"/></svg>
                                    </div>
                                    API Integration
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Text Content -->
                    <div class="space-y-8">
                        <h3 class="text-4xl md:text-5xl font-bold text-white tracking-tight">Data-driven decisions in real-time.</h3>
                        <p class="text-gray-400 text-lg leading-relaxed max-w-lg">
                            From individual sales advisors to entire dealerships, Tactic Systems aggregates your data into actionable insights. Track performance, measure KPIs, and drive results with automated reporting.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- White Section -->
        <div class="bg-[#F9FAFB] text-black rounded-t-[4rem] relative z-20 mt-[-2rem] pt-32 pb-32">
            <div class="container mx-auto px-6">
                <!-- Header -->
                <div class="max-w-4xl mb-24">
                    <div class="flex items-center gap-4 mb-6">
                        <div class="h-px w-12 bg-gray-300"></div>
                        <span class="text-gray-500 font-mono text-xs tracking-[0.2em] uppercase">Platform Features</span>
                    </div>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-900 mb-2 tracking-tight">Everything you need to track, analyze, and optimize performance.</h2>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-400 tracking-tight mb-8">All in one platform.</h2>
                    
                    <a href="#" class="inline-flex items-center gap-2 text-sm font-semibold border-b border-black pb-0.5 hover:text-gray-600 transition-colors">
                        Explore features
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </a>
                </div>

                <!-- Features Grid -->
                <div class="flex flex-col lg:flex-row gap-12">
                    <!-- Sidebar Navigation (Sticky) -->
                    <div class="hidden lg:block w-64 flex-shrink-0">
                        <div class="sticky top-32 space-y-4">
                            <div class="flex items-center gap-2 text-sm font-semibold text-black border-l-2 border-black pl-4 py-1">
                                <span class="w-1.5 h-1.5 rounded-full bg-[var(--color-tactic-primary)]"></span>
                                Real-Time Dashboards
                            </div>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">API Integration</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Performance Tracking</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Data Visualization</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Automated Reports</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Team Analytics</a>
                        </div>
                    </div>

                    <!-- Feature Cards -->
                    <div class="flex-grow space-y-8">
                        <FeatureRow 
                            title="Real-Time Dashboards" 
                            description="Monitor performance instantly. Interactive dashboards provide live insights into sales metrics, team performance, and KPIs with granular data from brand to individual advisor level."
                            icon="data"
                            image="data"
                        />
                         <FeatureRow 
                            title="API Integration" 
                            description="Connect seamlessly with your systems. Powerful API integration with CRM and ERP platforms automates data collection, eliminating manual entry and ensuring accuracy."
                            icon="connect"
                            image="connect"
                        />
                         <FeatureRow 
                            title="Performance Tracking" 
                            description="Measure what matters. Track individual sales advisor performance, team metrics, and conversion rates with detailed monthly KPI tracking and advisor-level filtering."
                            icon="preview"
                            image="preview"
                        />
                         <FeatureRow 
                            title="Data Visualization" 
                            description="See your data clearly. Choose from 50+ charts, tables, and visualization options to present insights that drive action and improve decision-making."
                            icon="lab"
                            image="lab"
                        />
                         <FeatureRow 
                            title="Automated Reports" 
                            description="Save time with automation. Automated report building and email feedback systems keep your team informed without manual effort, improving engagement and accountability."
                            icon="guard"
                            image="guard"
                        />
                         <FeatureRow 
                            title="Team Analytics" 
                            description="Understand team dynamics. Analyze performance patterns, identify top performers, and spot areas for improvement with comprehensive team-level analytics and historical data."
                            icon="lock"
                            image="collateral"
                        />
                    </div>
                </div>

                <!-- Pricing Section -->
                <div class="mt-32 text-center max-w-4xl mx-auto mb-24">
                    <div class="w-24 h-24 mx-auto bg-gradient-to-br from-[var(--color-tactic-primary)]/20 to-[var(--color-tactic-primary)]/10 rounded-full flex items-center justify-center mb-8 relative">
                        <div class="absolute inset-0 bg-white/50 blur-xl rounded-full"></div>
                        <svg class="w-10 h-10 text-[var(--color-tactic-primary)] relative z-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                    </div>
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-8 leading-tight">
                        Start free, scale as you grow. From 5 team members to unlimited enterprise solutions.
                    </h2>
                    <button class="bg-white border border-gray-200 hover:border-gray-400 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2 mx-auto">
                        View pricing plans
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>
                </div>

                <!-- Trusted By Section -->
                <div class="mb-32">
                    <p class="text-xl text-gray-500 mb-12">Trusted by automotive dealerships and sales teams worldwide.</p>
                    
                    <div class="grid md:grid-cols-3 gap-6">
                        <!-- BMW Card (Large) -->
                        <div class="md:col-span-2 bg-[#0A0A0A] rounded-3xl p-10 relative overflow-hidden group min-h-[400px] flex flex-col justify-end">
                            <div class="absolute inset-0 bg-gradient-to-t from-black via-black/50 to-transparent"></div>
                            
                            <div class="relative z-10">
                                <div class="flex items-center gap-4 mb-6">
                                    <div class="text-white font-bold text-3xl tracking-wider">BMW</div>
                                    <div class="w-8 h-8 rounded-full bg-[var(--color-tactic-primary)] flex items-center justify-center text-white font-bold">+</div>
                                    <div class="flex items-center gap-2 text-white font-semibold text-xl tracking-tight">
                                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <rect x="3" y="3" width="8" height="8" rx="1" stroke="white" stroke-width="2"/>
                                            <rect x="13" y="3" width="8" height="8" rx="1" stroke="white" stroke-width="2"/>
                                            <rect x="3" y="13" width="8" height="8" rx="1" stroke="white" stroke-width="2"/>
                                            <rect x="13" y="13" width="8" height="8" rx="1" stroke="white" stroke-width="2"/>
                                        </svg>
                                        Tactic Systems
                                    </div>
                                </div>
                                <h3 class="text-3xl font-bold text-white mb-4 max-w-md">
                                    "Detailed sales advisor measurement has improved our team's performance tracking significantly."
                                </h3>
                                <p class="text-gray-400 mb-4">— Sales Manager, BMW Dealership</p>
                                <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                    <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                </div>
                            </div>
                        </div>

                        <!-- Smaller Cards -->
                        <div class="space-y-6">
                            <!-- Volvo Card -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-[var(--color-tactic-primary)]/20 to-black"></div>
                                <div class="relative z-10">
                                    <div class="text-white font-bold text-xl mb-2">VOLVO</div>
                                    <p class="text-gray-400 text-sm">"Consolidated reporting eliminates the need for multiple tools."</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                            <!-- Chevrolet Card -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-blue-900/20 to-black"></div>
                                <div class="relative z-10">
                                    <div class="text-white font-bold text-xl mb-2">CHEVROLET</div>
                                    <p class="text-gray-400 text-sm">"Monthly KPI tracking with advisor-level filtering is a game changer."</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Banner -->
                <div class="bg-[#0A0A0A] rounded-3xl p-12 md:p-20 relative overflow-hidden mb-32 text-center">
                    <div class="absolute inset-0 bg-[url('/grid-pattern.svg')] opacity-10"></div>
                    <div class="absolute left-0 top-0 w-64 h-64 bg-[var(--color-tactic-primary)]/10 blur-[100px] rounded-full"></div>
                    <div class="absolute right-0 bottom-0 w-64 h-64 bg-[var(--color-tactic-primary)]/10 blur-[100px] rounded-full"></div>
                    
                    <div class="relative z-10 max-w-3xl mx-auto">
                        <h2 class="text-4xl md:text-6xl font-bold text-white mb-6 tracking-tight">
                            Powerful API integration. <span class="text-[var(--color-tactic-primary)]">Seamless data flow.</span>
                        </h2>
                        <p class="text-gray-400 mb-10">
                            Built for developers and sales teams alike. Our robust API connects with your CRM and ERP systems for automated, real-time data synchronization.
                        </p>
                        <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-md border border-white/10 rounded-full px-4 py-2 text-white text-sm hover:bg-white/20 transition-colors cursor-pointer">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path></svg>
                            API Documentation
                            <kbd class="bg-black/30 px-1.5 py-0.5 rounded text-xs text-gray-400 font-mono">D</kbd>
                        </div>
                    </div>
                </div>

                <!-- Integrations -->
                <div class="text-center mb-32">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
                        CRM systems. ERP platforms.<br>
                        Analytics tools. <span class="text-gray-400">Whatever you use,<br>Tactic Systems connects.</span>
                    </h2>
                    <button class="bg-gray-100 hover:bg-gray-200 text-black px-6 py-2 rounded-full text-sm font-medium transition-colors flex items-center gap-2 mx-auto mb-16 mt-8">
                        View all integrations
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>

                    <div class="grid grid-cols-2 md:grid-cols-4 gap-px bg-gray-200 border border-gray-200 rounded-2xl overflow-hidden">
                        {#each ['Salesforce', 'Google Maps', 'AWS', 'Google Analytics', 'Microsoft', 'SAP', 'Oracle', 'Tableau'] as logo}
                        <div class="bg-[#F9FAFB] p-12 flex items-center justify-center grayscale opacity-60 hover:grayscale-0 hover:opacity-100 transition-all duration-300">
                            <span class="font-bold text-xl uppercase tracking-wider">{logo}</span>
                        </div>
                        {/each}
                    </div>
                </div>

                <!-- Blog Section -->
                <div class="mb-12">
                    <h2 class="text-4xl font-bold text-gray-900 mb-12">Learn more about sales analytics.</h2>
                    <div class="grid md:grid-cols-2 gap-8">
                        <!-- Post 1 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gradient-to-br from-gray-200 to-gray-300 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden">
                                <div class="absolute inset-0 flex items-center justify-center">
                                    <div class="grid grid-cols-6 gap-4 opacity-50">
                                        {#each Array(24) as _}
                                            <svg class="w-6 h-6 text-[var(--color-tactic-primary)] transform -rotate-45" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"></path></svg>
                                        {/each}
                                    </div>
                                </div>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Industry Insights</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-[var(--color-tactic-primary)] transition-colors">How data analytics is transforming automotive sales</h3>
                        </div>
                        <!-- Post 2 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gray-100 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden flex items-center justify-center">
                                <div class="flex gap-4">
                                    <div class="w-16 h-16 rounded-full bg-[var(--color-tactic-primary)] blur-xl opacity-60"></div>
                                    <div class="w-20 h-20 rounded-full bg-[var(--color-tactic-primary)] blur-xl opacity-80"></div>
                                    <div class="w-12 h-12 rounded-full bg-[var(--color-tactic-primary)] blur-xl opacity-40"></div>
                                </div>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Best Practices</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-[var(--color-tactic-primary)] transition-colors">5 KPIs every sales manager should track daily</h3>
                        </div>
                    </div>
                </div>


    </main>

    <Footer />
</div>

