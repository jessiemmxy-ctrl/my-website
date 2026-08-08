[index.html](https://github.com/user-attachments/files/30855388/index.html)
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>短视频编导 & IP操盘手 | 个人作品集</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600;800&family=Noto+Sans+SC:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Noto Sans SC', system-ui, -apple-system, sans-serif;
            background-color: #080a0f;
            color: #e2e8f0;
            background-image: 
                radial-gradient(at 0% 0%, rgba(30, 58, 138, 0.15) 0px, transparent 50%),
                radial-gradient(at 100% 100%, rgba(88, 28, 135, 0.15) 0px, transparent 50%);
            background-attachment: fixed;
        }
        .font-cinzel { font-family: 'Cinzel', serif; }
        
        .glass-panel {
            background: rgba(15, 22, 36, 0.65);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.07);
        }
        
        .glass-panel-hover {
            transition: all 0.4s cubic-bezier(0.16, 1, 0.3, 1);
        }
        .glass-panel-hover:hover {
            transform: translateY(-4px);
            border-color: rgba(99, 102, 241, 0.35);
            box-shadow: 0 20px 40px -15px rgba(99, 102, 241, 0.2);
        }

        .text-glow {
            text-shadow: 0 0 20px rgba(96, 165, 250, 0.4);
        }

        .badge-glow {
            box-shadow: 0 0 12px rgba(59, 130, 246, 0.3);
        }
    </style>
</head>
<body class="min-h-screen pb-20 selection:bg-indigo-500 selection:text-white">

    <!-- Top Navigation / Brand -->
    <nav class="sticky top-0 z-50 glass-panel border-b border-gray-800/80 px-6 py-4">
        <div class="max-w-6xl mx-auto flex justify-between items-center">
            <div class="flex items-center gap-3">
                <span class="w-3 h-3 rounded-full bg-indigo-500 animate-ping"></span>
                <span class="font-cinzel font-bold tracking-wider text-lg text-white">DIRECTOR PORTFOLIO</span>
            </div>
            <div class="text-xs text-gray-400 font-mono hidden sm:block">
                <span>FOCUS: 知识科普 / 单人IP打造 / 商业变现</span>
            </div>
        </div>
    </nav>

    <!-- Header / Hero Section (个人审美与风格化名片) -->
    <header class="pt-16 pb-12 px-6 max-w-6xl mx-auto">
        <div class="glass-panel rounded-3xl p-8 sm:p-12 relative overflow-hidden">
            <!-- 背景艺术微光 -->
            <div class="absolute -right-10 -bottom-10 w-80 h-80 bg-indigo-600/10 rounded-full blur-3xl pointer-events-none"></div>
            
            <div class="flex flex-col lg:flex-row justify-between items-start lg:items-center gap-8">
                <div class="space-y-4 max-w-2xl">
                    <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-indigo-950/80 border border-indigo-700/50 text-indigo-300 text-xs font-semibold badge-glow">
                        <i class="fa-solid fa-clapperboard text-indigo-400"></i> 短视频编导 & IP全流程操盘手
                    </div>
                    <h1 class="text-3xl sm:text-5xl font-extrabold tracking-tight text-white leading-tight">
                        用视觉叙事构建信任，<br>
                        用爆款逻辑驱动 <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 via-indigo-300 to-purple-400 text-glow">商业增长</span>
                    </h1>
                    <p class="text-gray-300 text-sm sm:text-base leading-relaxed pt-2">
                        具备 <strong>4 年新媒体运营沉淀</strong> 与 <strong>7 个月一线短视频编导实战经验</strong>。独立操盘过千万级播放量的医生与科普矩阵账号，擅长将硬核医学知识转化为极具传播力的“高完播、强共鸣”爆款内容，并建立标准化的团队带教与商业化 SOP。
                    </p>
                </div>

                <!-- 个人信息速览片 Zone -->
                <div class="w-full lg:w-auto flex flex-col gap-3 glass-panel p-5 rounded-2xl border-gray-700/50 min-w-[260px]">
                    <div class="text-xs font-bold text-gray-400 uppercase tracking-wider mb-1 border-b border-gray-800 pb-2">
                        <i class="fa-solid fa-address-card text-indigo-400 mr-1.5"></i> 编导个人档案
                    </div>
                    <div class="text-xs text-gray-300 flex justify-between">
                        <span class="text-gray-500">编导经验</span>
                        <span class="font-semibold text-white">7 个月一线操盘</span>
                    </div>
                    <div class="text-xs text-gray-300 flex justify-between">
                        <span class="text-gray-500">运营积淀</span>
                        <span class="font-semibold text-white">4 年新媒体经验</span>
                    </div>
                    <div class="text-xs text-gray-300 flex justify-between">
                        <span class="text-gray-500">核心擅长</span>
                        <span class="font-semibold text-indigo-300">知识科普 / 单人IP</span>
                    </div>
                    <div class="text-xs text-gray-300 flex justify-between">
                        <span class="text-gray-500">辅助工具</span>
                        <span class="font-semibold text-white">ChatGPT / Gemini / AI视频</span>
                    </div>
                    <a href="#contact" class="mt-2 text-center bg-indigo-600 hover:bg-indigo-500 text-white text-xs font-medium py-2 rounded-xl transition">
                        联系合作 / 获取完整作品
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- Key Metrics 看板 -->
    <section class="py-6 px-6 max-w-6xl mx-auto grid grid-cols-2 lg:grid-cols-4 gap-4">
        <div class="glass-panel p-5 rounded-2xl glass-panel-hover">
            <div class="text-gray-400 text-xs font-medium mb-1">单条现象级爆款</div>
            <div class="text-2xl sm:text-3xl font-bold text-blue-400">500W+</div>
            <div class="text-[11px] text-gray-400 mt-1">播放量 / 60W+ 点赞</div>
        </div>
        <div class="glass-panel p-5 rounded-2xl glass-panel-hover">
            <div class="text-gray-400 text-xs font-medium mb-1">稳定月度产能</div>
            <div class="text-2xl sm:text-3xl font-bold text-purple-400">20+ 篇</div>
            <div class="text-[11px] text-gray-400 mt-1">兼顾品质与高频交付</div>
        </div>
        <div class="glass-panel p-5 rounded-2xl glass-panel-hover">
            <div class="text-gray-400 text-xs font-medium mb-1">商业化变现突破</div>
            <div class="text-2xl sm:text-3xl font-bold text-emerald-400">8-10 单</div>
            <div class="text-[11px] text-gray-400 mt-1">单账号月商单量突破</div>
        </div>
        <div class="glass-panel p-5 rounded-2xl glass-panel-hover">
            <div class="text-gray-400 text-xs font-medium mb-1">矩阵带教掌控</div>
            <div class="text-2xl sm:text-3xl font-bold text-amber-400">4 大 IP</div>
            <div class="text-[11px] text-gray-400 mt-1">主操盘 + 资深带教 SOP</div>
        </div>
    </section>

    <!-- 操盘账号矩阵 + 单个视频作品嵌入区域 -->
    <section id="matrix" class="py-12 px-6 max-w-6xl mx-auto">
        <div class="flex flex-col md:flex-row justify-between items-start md:items-end mb-8 gap-4">
            <div>
                <h2 class="text-2xl font-bold text-white flex items-center gap-2">
                    <i class="fa-solid fa-layer-group text-indigo-400"></i> 操盘账号矩阵与作品通道
                </h2>
                <p class="text-gray-400 text-xs sm:text-sm mt-1">点击下方账号直达主页，或直接播放核心代表作</p>
            </div>
        </div>

        <div class="grid md:grid-cols-2 gap-6">
            
            <!-- 账号卡片 1：懂你孟大夫 -->
            <div class="glass-panel p-6 rounded-2xl glass-panel-hover flex flex-col justify-between border-indigo-500/20">
                <div>
                    <div class="flex justify-between items-start mb-3">
                        <div>
                            <h3 class="font-bold text-lg text-white flex items-center gap-2">
                                懂你孟大夫
                                <span class="text-[10px] bg-blue-950 text-blue-400 border border-blue-800 px-2 py-0.5 rounded-full font-normal">主操盘</span>
                            </h3>
                            <div class="text-xs text-indigo-300 mt-1">抖音 31.2W 粉丝 | 小红书 46W 粉丝</div>
                        </div>
                    </div>
                    <p class="text-xs text-gray-300 leading-relaxed mb-4">
                        独立负责选题、脚本、拍摄指导、剪辑审核及运营全流程。操盘打造女性急救科普，创造单条 500W+ 播放、60W+ 点赞爆款。
                    </p>

                    <!-- 单个作品插入展示区 -->
                    <div class="bg-black/40 rounded-xl p-3 border border-gray-800 mb-4">
                        <div class="text-[11px] font-semibold text-gray-400 mb-2 flex items-center justify-between">
                            <span><i class="fa-solid fa-play text-red-400 mr-1"></i> 代表作：女性紧急救援科普 (500W+播放)</span>
                            <span class="text-[10px] text-gray-500">01:15</span>
                        </div>
                        <!-- 视频播放区 (可替换为你的本地视频文件路径或视频流) -->
                        <div class="relative aspect-video rounded-lg overflow-hidden bg-gray-900 border border-gray-800 group">
                            <video controls class="w-full h-full object-cover" poster="https://via.placeholder.com/640x360/1e1e2e/ffffff?text=Meng+Doctor+Viral+Video">
                                <source src="your-video-file-1.mp4" type="video/mp4">
                                您的浏览器不支持视频播放。
                            </video>
                        </div>
                    </div>
                </div>

                <div class="pt-3 border-t border-gray-800 flex flex-col gap-2">
                    <a href="https://v.douyin.com/md6TrUHS2NI/" target="_blank" class="bg-gray-800/80 hover:bg-gray-700 text-gray-200 text-xs py-2 px-3 rounded-lg flex items-center justify-between transition">
                        <span><i class="fa-brands fa-tiktok text-red-400 mr-1.5"></i> 访问 孟圆 抖音主页</span>
                        <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                    </a>
                    <a href="https://xhslink.cn/m/mz4Jc3qHLU" target="_blank" class="bg-gray-800/80 hover:bg-gray-700 text-gray-200 text-xs py-2 px-3 rounded-lg flex items-center justify-between transition">
                        <span><i class="fa-solid fa-bookmark text-red-500 mr-1.5"></i> 访问 孟圆 小红书主页</span>
                        <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                    </a>
                </div>
            </div>

            <!-- 账号卡片 2：儿科主任沈定荣 -->
            <div class="glass-panel p-6 rounded-2xl glass-panel-hover flex flex-col justify-between border-purple-500/20">
                <div>
                    <div class="flex justify-between items-start mb-3">
                        <div>
                            <h3 class="font-bold text-lg text-white flex items-center gap-2">
                                儿科主任沈定荣
                                <span class="text-[10px] bg-purple-950 text-purple-400 border border-purple-800 px-2 py-0.5 rounded-full font-normal">主操盘</span>
                            </h3>
                            <div class="text-xs text-purple-300 mt-1">抖音 44.7W 粉丝 | 小红书 12.9W 粉丝</div>
                        </div>
                    </div>
                    <p class="text-xs text-gray-300 leading-relaxed mb-4">
                        独立全流程操盘。低迷期创新使用自制教具模型破局（获1.2W+赞），并成功将账号月商单量提升至 8-10 单。
                    </p>

                    <!-- 单个作品插入展示区 -->
                    <div class="bg-black/40 rounded-xl p-3 border border-gray-800 mb-4">
                        <div class="text-[11px] font-semibold text-gray-400 mb-2 flex items-center justify-between">
                            <span><i class="fa-solid fa-play text-red-400 mr-1"></i> 代表作：教具视觉破局科普 (1.2W+赞)</span>
                            <span class="text-[10px] text-gray-500">00:58</span>
                        </div>
                        <div class="relative aspect-video rounded-lg overflow-hidden bg-gray-900 border border-gray-800">
                            <video controls class="w-full h-full object-cover" poster="https://via.placeholder.com/640x360/2a1b3d/ffffff?text=Shen+Doctor+Prop+Video">
                                <source src="your-video-file-2.mp4" type="video/mp4">
                                您的浏览器不支持视频播放。
                            </video>
                        </div>
                    </div>
                </div>

                <div class="pt-3 border-t border-gray-800 flex flex-col gap-2">
                    <a href="https://v.douyin.com/6MxYXB7u0xg/" target="_blank" class="bg-gray-800/80 hover:bg-gray-700 text-gray-200 text-xs py-2 px-3 rounded-lg flex items-center justify-between transition">
                        <span><i class="fa-brands fa-tiktok text-red-400 mr-1.5"></i> 访问 沈定荣 抖音主页</span>
                        <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                    </a>
                    <a href="https://xhslink.cn/m/3wpa08Hwb5J" target="_blank" class="bg-gray-800/80 hover:bg-gray-700 text-gray-200 text-xs py-2 px-3 rounded-lg flex items-center justify-between transition">
                        <span><i class="fa-solid fa-bookmark text-red-500 mr-1.5"></i> 访问 沈定荣 小红书主页</span>
                        <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                    </a>
                </div>
            </div>

            <!-- 账号卡片 3：硕士青姐很温柔 -->
            <div class="glass-panel p-6 rounded-2xl glass-panel-hover flex flex-col justify-between border-emerald-500/20">
                <div>
                    <div class="flex justify-between items-start mb-3">
                        <div>
                            <h3 class="font-bold text-lg text-white flex items-center gap-2">
                                硕士青姐很温柔
                                <span class="text-[10px] bg-emerald-950 text-emerald-400 border border-emerald-800 px-2 py-0.5 rounded-full font-normal">编导带新人</span>
                            </h3>
                            <div class="text-xs text-emerald-300 mt-1">抖音 41W 粉丝 | 小红书 11.9W 粉丝</div>
                        </div>
                    </div>
                    <p class="text-xs text-gray-300 leading-relaxed mb-4">
                        作为资深编导把控选题、脚本撰写与镜头审核，带领新人团队搭建标准化生产流程，实现稳定保质产出。
                    </p>

                    <div class="bg-black/40 rounded-xl p-3 border border-gray-800 mb-4">
                        <div class="text-[11px] font-semibold text-gray-400 mb-2 flex items-center justify-between">
                            <span><i class="fa-solid fa-play text-red-400 mr-1"></i> 代表作：高口碑女性情感与知识科普</span>
                            <span class="text-[10px] text-gray-500">01:05</span>
                        </div>
                        <div class="relative aspect-video rounded-lg overflow-hidden bg-gray-900 border border-gray-800">
                            <video controls class="w-full h-full object-cover" poster="https://via.placeholder.com/640x360/1b3d2b/ffffff?text=Qing+Jie+Video+Preview">
                                <source src="your-video-file-3.mp4" type="video/mp4">
                                您的浏览器不支持视频播放。
                            </video>
                        </div>
                    </div>
                </div>

                <div class="pt-3 border-t border-gray-800 flex flex-col gap-2">
                    <a href="https://v.douyin.com/53riDpkRfDc/" target="_blank" class="bg-gray-800/80 hover:bg-gray-700 text-gray-200 text-xs py-2 px-3 rounded-lg flex items-center justify-between transition">
                        <span><i class="fa-brands fa-tiktok text-red-400 mr-1.5"></i> 访问 青姐 抖音主页</span>
                        <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                    </a>
                    <a href="https://xhslink.cn/m/6rrimqyeSSs" target="_blank" class="bg-gray-800/80 hover:bg-gray-700 text-gray-200 text-xs py-2 px-3 rounded-lg flex items-center justify-between transition">
                        <span><i class="fa-solid fa-bookmark text-red-500 mr-1.5"></i> 访问 林青 小红书主页</span>
                        <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                    </a>
                </div>
            </div>

            <!-- 账号卡片 4：硕士玲姐不太冷 -->
            <div class="glass-panel p-6 rounded-2xl glass-panel-hover flex flex-col justify-between border-amber-500/20">
                <div>
                    <div class="flex justify-between items-start mb-3">
                        <div>
                            <h3 class="font-bold text-lg text-white flex items-center gap-2">
                                硕士玲姐不太冷
                                <span class="text-[10px] bg-amber-950 text-amber-400 border border-amber-800 px-2 py-0.5 rounded-full font-normal">编导带新人</span>
                            </h3>
                            <div class="text-xs text-amber-300 mt-1">抖音 53.1W 粉丝 | 小红书 7.9W 粉丝</div>
                        </div>
                    </div>
                    <p class="text-xs text-gray-300 leading-relaxed mb-4">
                        全面掌控矩阵品质与镜头语言，建立编导创作 SOP，指导新人快速上手选题逻辑与剪辑节奏。
                    </p>

                    <div class="bg-black/40 rounded-xl p-3 border border-gray-800 mb-4">
                        <div class="text-[11px] font-semibold text-gray-400 mb-2 flex items-center justify-between">
                            <span><i class="fa-solid fa-play text-red-400 mr-1"></i> 代表作：单人IP情绪感口播爆款</span>
                            <span class="text-[10px] text-gray-500">01:20</span>
                        </div>
                        <div class="relative aspect-video rounded-lg overflow-hidden bg-gray-900 border border-gray-800">
                            <video controls class="w-full h-full object-cover" poster="https://via.placeholder.com/640x360/3d2b1b/ffffff?text=Ling+Jie+Video+Preview">
                                <source src="your-video-file-4.mp4" type="video/mp4">
                                您的浏览器不支持视频播放。
                            </video>
                        </div>
                    </div>
                </div>

                <div class="pt-3 border-t border-gray-800 flex flex-col gap-2">
                    <a href="https://v.douyin.com/uk-XkhGudPY/" target="_blank" class="bg-gray-800/80 hover:bg-gray-700 text-gray-200 text-xs py-2 px-3 rounded-lg flex items-center justify-between transition">
                        <span><i class="fa-brands fa-tiktok text-red-400 mr-1.5"></i> 访问 玲姐 抖音主页</span>
                        <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                    </a>
                    <a href="https://xhslink.cn/m/3B27uYJlR8a" target="_blank" class="bg-gray-800/80 hover:bg-gray-700 text-gray-200 text-xs py-2 px-3 rounded-lg flex items-center justify-between transition">
                        <span><i class="fa-solid fa-bookmark text-red-500 mr-1.5"></i> 访问 卫玲 小红书主页</span>
                        <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                    </a>
                </div>
            </div>

        </div>
    </section>

    <!-- 编导核心方法论 / 爆款拆解模块 -->
    <section class="py-12 px-6 max-w-6xl mx-auto">
        <h2 class="text-2xl font-bold text-white mb-6 flex items-center gap-2">
            <i class="fa-solid fa-wand-magic-sparkles text-amber-400"></i> 编导方法论与爆款拆解
        </h2>
        
        <div class="grid md:grid-cols-2 gap-6">
            <div class="glass-panel p-6 rounded-2xl border-gray-800">
                <div class="text-xs font-bold text-blue-400 uppercase tracking-wider mb-2">METHODOLOGY 01</div>
                <h3 class="text-base font-bold text-white mb-3">知识科普的“前 3 秒黄金钩子”与软化算法</h3>
                <p class="text-xs text-gray-300 leading-relaxed mb-3">
                    硬核科普最忌讳说教感。在《孟大夫》女性急救爆款中，将专业医学原理拆解为“痛点场景前置 + 具象化三步法”，极大提升了完播率，引导自发社交转发。
                </p>
                <div class="text-[11px] bg-blue-950/40 border border-blue-800/50 p-3 rounded-xl text-blue-200">
                    💡 <strong>成果：</strong> 单条突破 500W+ 播放，60W+ 点赞，涨粉效率提升 300%。
                </div>
            </div>

            <div class="glass-panel p-6 rounded-2xl border-gray-800">
                <div class="text-xs font-bold text-purple-400 uppercase tracking-wider mb-2">METHODOLOGY 02</div>
                <h3 class="text-base font-bold text-white mb-3">道具视觉突破与商业化植入 SOP</h3>
                <p class="text-xs text-gray-300 leading-relaxed mb-3">
                    在《沈主任》流量低迷期，通过自制手作教具模型将病理可视化。建立“场景体验 + 视觉展示 + 自然带货”模式，在不伤害粉丝体验的前提下实现变现。
                </p>
                <div class="text-[11px] bg-purple-950/40 border border-purple-800/50 p-3 rounded-xl text-purple-200">
                    💡 <strong>成果：</strong> 单月商单交付稳定在 8-10 单，教具视频获 1.2W+ 点赞。
                </div>
            </div>
        </div>
    </section>

    <!-- Footer / 联系沟通区域 -->
    <footer id="contact" class="mt-16 border-t border-gray-800/80 pt-12 pb-12 px-6">
        <div class="max-w-6xl mx-auto glass-panel p-8 rounded-3xl flex flex-col sm:flex-row justify-between items-center gap-6">
            <div>
                <h3 class="text-xl font-bold text-white mb-1">期待与您的团队合作</h3>
                <p class="text-xs text-gray-400">短视频编导 | 知识科普IP操盘 | 剧情与商业短片探讨</p>
            </div>
            <div class="flex flex-wrap items-center gap-4">
                <span class="text-xs font-mono bg-gray-800 px-4 py-2 rounded-xl text-gray-300 border border-gray-700">
                    <i class="fa-solid fa-envelope text-indigo-400 mr-2"></i> 欢迎通过微信/电话联系沟通
                </span>
            </div>
        </div>
        <div class="text-center text-[11px] text-gray-600 mt-8">
            © 2026 Short Video Director Portfolio. All Rights Reserved.
        </div>
    </footer>

</body>
</html>
