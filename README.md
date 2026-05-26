<!DOCTYPE html>
<html lang="zh-CN" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>新范式开发者 | 业务问题的终结者</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&family=JetBrains+Mono:wght@400;700&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                        mono: ['JetBrains Mono', 'monospace'],
                    },
                    colors: {
                        dark: '#0a0a0a',
                        accent: '#3b82f6',
                        neon: '#10b981',
                    }
                }
            }
        }
    </script>
    <style>
        body { background-color: #0a0a0a; color: #e5e7eb; }
        .gradient-text {
            background: linear-gradient(90deg, #3b82f6, #10b981);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .glass {
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }
        .glow:hover {
            box-shadow: 0 0 30px rgba(59, 130, 246, 0.15);
            border-color: rgba(59, 130, 246, 0.3);
        }
        .fade-in {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.8s ease, transform 0.8s ease;
        }
        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }
        /* 自定义滚动条 */
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #0a0a0a; }
        ::-webkit-scrollbar-thumb { background: #333; border-radius: 4px; }
    </style>
</head>
<body class="font-sans antialiased selection:bg-blue-500 selection:text-white">

    <!-- Navigation -->
    <nav class="fixed top-0 w-full z-50 glass border-b border-white/5">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="font-mono font-bold text-xl tracking-tight">&lt;Dev /&gt;</a>
            <div class="hidden md:flex space-x-8 text-sm font-medium text-gray-400">
                <a href="#about" class="hover:text-white transition">About</a>
                <a href="#case" class="hover:text-white transition">Case Study</a>
                <a href="#stack" class="hover:text-white transition">Tech Stack</a>
                <a href="#playbook" class="hover:text-white transition">Playbook</a>
            </div>
            <a href="#contact" class="px-4 py-2 bg-white text-black rounded-full text-sm font-semibold hover:bg-gray-200 transition">Contact Me</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="min-h-screen flex items-center justify-center relative overflow-hidden pt-20">
        <div class="absolute top-1/4 left-1/4 w-96 h-96 bg-blue-600/20 rounded-full blur-3xl"></div>
        <div class="absolute bottom-1/4 right-1/4 w-96 h-96 bg-emerald-600/10 rounded-full blur-3xl"></div>
        
        <div class="max-w-5xl mx-auto px-6 text-center relative z-10">
            <div class="inline-block px-4 py-1.5 mb-6 rounded-full glass text-xs font-mono text-emerald-400 tracking-wider">
                SYSTEM.ONLINE // NEW PARADIGM DEVELOPER
            </div>
            <h1 class="text-5xl md:text-7xl font-extrabold tracking-tight mb-6 leading-tight">
                不写废代码，<br>
                <span class="gradient-text">只做业务终结者。</span>
            </h1>
            <p class="text-xl text-gray-400 max-w-2xl mx-auto mb-12 leading-relaxed">
                懂业务、懂技术、善用 AI 杠杆。用 80 小时碎片时间，交付支撑 39 个项目全面投产的企业级数字基座。
            </p>
            
            <!-- Core Stats -->
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4 max-w-3xl mx-auto">
                <div class="glass rounded-2xl p-6 glow transition-all">
                    <div class="text-3xl font-bold text-white mb-1">80<span class="text-blue-500">h</span></div>
                    <div class="text-xs text-gray-500 uppercase tracking-wider">有效工时</div>
                </div>
                <div class="glass rounded-2xl p-6 glow transition-all">
                    <div class="text-3xl font-bold text-white mb-1">39<span class="text-emerald-500">+</span></div>
                    <div class="text-xs text-gray-500 uppercase tracking-wider">覆盖项目</div>
                </div>
                <div class="glass rounded-2xl p-6 glow transition-all">
                    <div class="text-3xl font-bold text-white mb-1">168</div>
                    <div class="text-xs text-gray-500 uppercase tracking-wider">自动化报告</div>
                </div>
                <div class="glass rounded-2xl p-6 glow transition-all">
                    <div class="text-3xl font-bold text-white mb-1">150<span class="text-blue-500">+</span></div>
                    <div class="text-xs text-gray-500 uppercase tracking-wider">API 端点</div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-32 px-6">
        <div class="max-w-4xl mx-auto fade-in">
            <h2 class="text-3xl font-bold mb-8 flex items-center gap-3">
                <span class="w-8 h-[2px] bg-blue-500"></span> 关于我
            </h2>
            <div class="grid md:grid-cols-2 gap-12">
                <div class="space-y-6 text-gray-400 leading-relaxed text-lg">
                    <p>我不是传统的“接单型”程序员，而是<strong class="text-white">业务问题的终结者</strong>。</p>
                    <p>在数字化转型的深水区，企业不缺会写 CRUD 的人，缺的是能<strong class="text-white">把模糊的业务痛点，翻译成极简、健壮、可落地的系统</strong>的人。</p>
                    <p>我擅长在业务一线的现场，用碎片化时间结合 AI 工具链，快速构建 MVP并直接投入生产验证。</p>
                </div>
                <div class="glass rounded-2xl p-8 font-mono text-sm text-gray-300 space-y-3">
                    <div class="text-emerald-400">// core_competencies.json</div>
                    <div>{</div>
                    <div class="pl-4">"business_modeling": <span class="text-blue-400">"Expert"</span>,</div>
                    <div class="pl-4">"rapid_delivery": <span class="text-blue-400">"80h_MVP"</span>,</div>
                    <div class="pl-4">"ai_leverage": <span class="text-blue-400">"Cursor/Copilot"</span>,</div>
                    <div class="pl-4">"engineering_intuition": <span class="text-blue-400">"Prod-Ready"</span></div>
                    <div>}</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Case Study: QES -->
    <section id="case" class="py-32 px-6 bg-white/[0.01]">
        <div class="max-w-6xl mx-auto fade-in">
            <h2 class="text-3xl font-bold mb-4 flex items-center gap-3">
                <span class="w-8 h-[2px] bg-emerald-500"></span> 核心案例：QES 物业质量评估系统
            </h2>
            <p class="text-gray-500 mb-12 max-w-2xl">从 0 到 1，20天 × 4小时/天。没有冗长的评审，只有“边检查边改代码”的极致敏捷。系统已全面投产，成为一线员工追着用的“香馍馍”。</p>

            <div class="grid md:grid-cols-3 gap-6 mb-12">
                <!-- Card 1 -->
                <div class="glass rounded-2xl p-8 glow transition-all">
                    <div class="text-blue-500 mb-4">
                        <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 7v10c0 2.21 3.582 4 8 4s8-1.79 8-4V7M4 7c0 2.21 3.582 4 8 4s8-1.79 8-4M4 7c0-2.21 3.582-4 8-4s8 1.79 8 4m0 5c0 2.21-3.582 4-8 4s-8-1.79-8-4"></path></svg>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-white">柔性三表架构</h3>
                    <p class="text-gray-400 text-sm leading-relaxed mb-4">抛弃僵化的单表设计。构建 <code class="text-xs bg-white/10 px-1 rounded">CheckItemLibrary</code> → <code class="text-xs bg-white/10 px-1 rounded">ContentItems</code> → <code class="text-xs bg-white/10 px-1 rounded">ProblemOptions</code> 三表模型。</p>
                    <ul class="text-xs text-gray-500 space-y-1 font-mono">
                        <li>✓ 支持排他组互斥逻辑</li>
                        <li>✓ 支持一票否决与自定义算分</li>
                        <li>✓ 系统预设与个人创建权限隔离</li>
                    </ul>
                </div>
                <!-- Card 2 -->
                <div class="glass rounded-2xl p-8 glow transition-all">
                    <div class="text-emerald-500 mb-4">
                        <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path></svg>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-white">无模板 Word 直出</h3>
                    <p class="text-gray-400 text-sm leading-relaxed mb-4">彻底消灭模板维护噩梦。踩坑 SkiaSharp 冲突后，采用 <code class="text-xs bg-white/10 px-1 rounded">DocX + 原生 OpenXML</code> 代码直出。</p>
                    <ul class="text-xs text-gray-500 space-y-1 font-mono">
                        <li>✓ 156份项目报告 + 12份区域总结</li>
                        <li>✓ 现场图片原生注入与标注</li>
                        <li>✓ 耗时从 3小时 压缩至 45分钟</li>
                    </ul>
                </div>
                <!-- Card 3 -->
                <div class="glass rounded-2xl p-8 glow transition-all">
                    <div class="text-purple-500 mb-4">
                        <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 12h14M5 12a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v4a2 2 0 01-2 2M5 12a2 2 0 00-2 2v4a2 2 0 002 2h14a2 2 0 002-2v-4a2 2 0 00-2-2m-2-4h.01M17 16h.01"></path></svg>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-white">极简工程化底座</h3>
                    <p class="text-gray-400 text-sm leading-relaxed mb-4">没有 K8s，没有过度设计。用 <code class="text-xs bg-white/10 px-1 rounded">Nginx + systemd + rsync</code> 打造最稳健的发布流。</p>
                    <ul class="text-xs text-gray-500 space-y-1 font-mono">
                        <li>✓ 生产/测试双环境物理隔离</li>
                        <li>✓ 发布脚本自动防配置覆盖</li>
                        <li>✓ 浏览器即APP，零安装门槛</li>
                    </ul>
                </div>
            </div>

            <!-- Tech Specs Banner -->
            <div class="glass rounded-2xl p-8 border-l-4 border-blue-500">
                <h4 class="font-mono text-sm text-blue-400 mb-4">// SYSTEM_SPECS</h4>
                <div class="grid grid-cols-2 md:grid-cols-4 gap-6 text-sm">
                    <div><span class="text-gray-500 block">Backend</span> <span class="text-white font-semibold">ASP.NET Core 8</span></div>
                    <div><span class="text-gray-500 block">Frontend</span> <span class="text-white font-semibold">Vue 3 + Vite</span></div>
                    <div><span class="text-gray-500 block">Database</span> <span class="text-white font-semibold">SQL Server (Linux)</span></div>
                    <div><span class="text-gray-500 block">Controllers</span> <span class="text-white font-semibold">35 Modules</span></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Playbook Section -->
    <section id="playbook" class="py-32 px-6">
        <div class="max-w-4xl mx-auto fade-in">
            <h2 class="text-3xl font-bold mb-12 flex items-center gap-3">
                <span class="w-8 h-[2px] bg-purple-500"></span> 我的方法论 (Playbook)
            </h2>
            <div class="space-y-8">
                <div class="flex gap-6">
                    <div class="flex-shrink-0 w-12 h-12 rounded-full glass flex items-center justify-center font-mono text-blue-400 font-bold">01</div>
                    <div>
                        <h3 class="text-xl font-bold text-white mb-2">业务即需求，用户即测试</h3>
                        <p class="text-gray-400">不在会议室里空想需求。在检查现场，每天 1-2 个用户真实反馈，5分钟修复，全流程测试验证，无问题部署生产服务，即修即用，直接验证。告别冗长的瀑布流。</p>
                    </div>
                </div>
                <div class="flex gap-6">
                    <div class="flex-shrink-0 w-12 h-12 rounded-full glass flex items-center justify-center font-mono text-emerald-400 font-bold">02</div>
                    <div>
                        <h3 class="text-xl font-bold text-white mb-2">工具链 > 造轮子</h3>
                        <p class="text-gray-400">善用 AI 生成基础代码，把核心精力留给“业务建模”、“边界校验”和“数据流转”。不炫技，只交付结果。</p>
                    </div>
                </div>
                <div class="flex gap-6">
                    <div class="flex-shrink-0 w-12 h-12 rounded-full glass flex items-center justify-center font-mono text-purple-400 font-bold">03</div>
                    <div>
                        <h3 class="text-xl font-bold text-white mb-2">浏览器即 APP</h3>
                        <p class="text-gray-400">用响应式 Web + JWT 轻量认证，砍掉 80% 的原生 APP 开发与更新成本，换取一线员工的“零安装、打开即用”。</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-32 px-6 bg-white/[0.01] border-t border-white/5">
        <div class="max-w-3xl mx-auto text-center fade-in">
            <h2 class="text-4xl font-bold mb-6">寻找业务问题的终结者？</h2>
            <p class="text-gray-400 text-lg mb-12">如果你需要一个能把模糊业务痛点转化为高可用数字基座的伙伴，欢迎联系我。</p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                <a href="mailto:3165184647＠qq.com" class="px-8 py-4 bg-blue-600 hover:bg-blue-700 text-white rounded-xl font-semibold transition-all transform hover:scale-105">
                    发送邮件 →
                </a>
                <a href="https://github.com/Ryanlmr" target="_blank" class="px-8 py-4 glass hover:bg-white/5 text-white rounded-xl font-semibold transition-all">
                    GitHub 主页
                </a>
            </div>
            <p class="mt-12 text-xs text-gray-600 font-mono">© 2026 New Paradigm Developer. Built with Passion & AI.</p>
        </div>
    </section>

    <script>
        // 简单的滚动渐入动画
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, { threshold: 0.1 });

        document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));
    </script>
</body>
</html>
