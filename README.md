<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>剪映专业版全功能解决方案</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css" rel="stylesheet">
    <style>
        :root {
            --primary-blue: #2563eb;
            --secondary-blue: #3b82f6;
            --light-bg: #f8fafc;
        }

        body {
            background-color: var(--light-bg);
            font-family: 'Helvetica Neue', sans-serif;
        }

        .nav-brand {
            font-weight: 600;
            letter-spacing: 0.5px;
        }

        .download-main-btn {
            background: linear-gradient(135deg, var(--primary-blue), var(--secondary-blue));
            color: white;
            padding: 1rem 2.5rem;
            border-radius: 30px;
            font-size: 1.1rem;
            transition: transform 0.3s, box-shadow 0.3s;
            border: none;
        }

        .download-main-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(59,130,246,0.3);
        }

        .version-card {
            border: none;
            border-radius: 12px;
            overflow: hidden;
            transition: transform 0.2s;
            background: white;
        }

        .version-card:hover {
            transform: translateY(-5px);
        }

        .feature-card {
            background: white;
            border-radius: 12px;
            padding: 2rem;
            height: 100%;
        }

        .accordion-button:focus {
            box-shadow: none;
        }
    </style>
</head>
<body>

<!-- 导航栏 -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
        <a class="navbar-brand nav-brand" href="#">
            <i class="bi bi-camera-reels me-2"></i>
            剪映PRO
        </a>
    </div>
</nav>

<!-- 软件介绍 -->
<section class="container my-5 pt-4">
    <div class="row align-items-center g-5">
        <!-- 截图 -->
        <div class="col-lg-6">
            <img src="software-preview.jpg" 
                 class="img-fluid rounded-3 shadow-lg"
                 alt="软件界面预览"
                 loading="lazy">
        </div>

        <!-- 介绍 -->
        <div class="col-lg-6">
            <h1 class="mb-4">剪映专业版 6.8</h1>
            <p class="lead text-muted mb-4">
                全平台视频编辑解决方案，集成AI智能工具与特效库，支持4K超清导出与多轨道专业剪辑。
            </p>
            <div class="d-grid d-md-block">
               <button class="download-main-btn" 
        onclick="window.open('https://pan.quark.cn/s/5dc2bfc55f55', '_blank')">
    <i class="bi bi-download me-2"></i>
    立即下载完整版
</button>
            </div>
        </div>
    </div>
</section>

<!-- 版本展示 -->
<section class="container my-5">
    <h3 class="text-center mb-4">多平台版本</h3>
    <div class="row g-4">
        <div class="col-md-6 col-lg-3">
            <div class="version-card shadow-sm">
                <img src="win-version.jpg" class="card-img-top" alt="Windows版">
                <div class="p-3">
                    <h5>Windows 专业版</h5>
                    <div class="text-muted small">
                        <div>v6.8.0</div>
                        <div>1.2GB</div>
                    </div>
                </div>
            </div>
        </div>

        <div class="col-md-6 col-lg-3">
            <div class="version-card shadow-sm">
                <img src="mac-version.jpg" class="card-img-top" alt="macOS版">
                <div class="p-3">
                    <h5>macOS 专业版</h5>
                    <div class="text-muted small">
                        <div>v6.7.5</div>
                        <div>1.1GB</div>
                    </div>
                </div>
            </div>
        </div>

        <div class="col-md-6 col-lg-3">
            <div class="version-card shadow-sm">
                <img src="android-version.jpg" class="card-img-top" alt="Android版">
                <div class="p-3">
                    <h5>Android 版</h5>
                    <div class="text-muted small">
                        <div>v9.2.0</div>
                        <div>342MB</div>
                    </div>
                </div>
            </div>
        </div>

        <div class="col-md-6 col-lg-3">
            <div class="version-card shadow-sm">
                <img src="ios-version.jpg" class="card-img-top" alt="iOS版">
                <div class="p-3">
                    <h5>iOS 版</h5>
                    <div class="text-muted small">
                        <div>v9.1.8</div>
                        <div>298MB</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- 核心功能 -->
<section class="container my-5">
    <h3 class="text-center mb-4">核心功能特性</h3>
    <div class="row g-4">
        <div class="col-md-6 col-lg-3">
            <div class="feature-card shadow-sm">
                <div class="text-primary fs-1 mb-3">
                    <i class="bi bi-film"></i>
                </div>
                <h5>多轨道编辑</h5>
                <p class="text-muted small">支持无限视频/音频轨道</p>
            </div>
        </div>

        <div class="col-md-6 col-lg-3">
            <div class="feature-card shadow-sm">
                <div class="text-primary fs-1 mb-3">
                    <i class="bi bi-magic"></i>
                </div>
                <h5>智能特效</h5>
                <p class="text-muted small">200+专业级滤镜/转场</p>
            </div>
        </div>

        <div class="col-md-6 col-lg-3">
            <div class="feature-card shadow-sm">
                <div class="text-primary fs-1 mb-3">
                    <i class="bi bi-4k"></i>
                </div>
                <h5>4K导出</h5>
                <p class="text-muted small">支持HDR10+输出</p>
            </div>
        </div>

        <div class="col-md-6 col-lg-3">
            <div class="feature-card shadow-sm">
                <div class="text-primary fs-1 mb-3">
                    <i class="bi bi-shield-check"></i>
                </div>
                <h5>稳定运行</h5>
                <p class="text-muted small">自动崩溃恢复机制</p>
            </div>
        </div>
    </div>
</section>

<!-- 热点问题 -->
<section class="container my-5">
    <h3 class="text-center mb-4">常见问题解答</h3>
    <div class="accordion">
        <!-- 问题1 -->
        <div class="accordion-item">
            <h4 class="accordion-header">
                <button class="accordion-button" data-bs-toggle="collapse" data-bs-target="#q1">
                    系统兼容性要求
                </button>
            </h4>
            <div id="q1" class="accordion-collapse collapse show">
                <div class="accordion-body">
                    <p>Windows 10 20H2及以上 / macOS 12 Monterey及以上</p>
                    <p class="text-muted small">建议配备独立显卡</p>
                </div>
            </div>
        </div>

        <!-- 问题2 -->
        <div class="accordion-item">
            <h4 class="accordion-header">
                <button class="accordion-button collapsed" data-bs-toggle="collapse" data-bs-target="#q2">
                    激活失败解决方案
                </button>
            </h4>
            <div id="q2" class="accordion-collapse collapse">
                <div class="accordion-body">
                    <ol>
                        <li>关闭杀毒软件</li>
                        <li>管理员身份运行</li>
                        <li>检查安装路径</li>
                    </ol>
                </div>
            </div>
        </div>

        <!-- 问题3 -->
        <div class="accordion-item">
            <h4 class="accordion-header">
                <button class="accordion-button collapsed" data-bs-toggle="collapse" data-bs-target="#q3">
                    如何验证激活状态
                </button>
            </h4>
            <div id="q3" class="accordion-collapse collapse">
                <div class="accordion-body">
                    <p>使用VIP滤镜并导出4K视频，检查是否包含水印</p>
                </div>
            </div>
        </div>

        <!-- 问题4 -->
        <div class="accordion-item">
            <h4 class="accordion-header">
                <button class="accordion-button collapsed" data-bs-toggle="collapse" data-bs-target="#q4">
                    更新策略说明
                </button>
            </h4>
            <div id="q4" class="accordion-collapse collapse">
                <div class="accordion-body">
                    <p>每月提供增量更新包，需手动下载安装</p>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- 页脚 -->
<footer class="bg-dark text-white py-4 mt-5">
    <div class="container text-center">
        <div class="mb-3">
            <a href="#" class="text-white me-3">用户协议</a>
            <a href="#" class="text-white me-3">隐私政策</a>
            <a href="#" class="text-white">技术支持</a>
        </div>
        <small>© 2024 剪映技术社区 · 仅供学习交流</small>
    </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
