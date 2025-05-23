<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>白晨阳 - 个人简历</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #3498db;
            --secondary-color: #2ecc71;
            --accent-color: #e74c3c;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Segoe UI', sans-serif;
            line-height: 1.6;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            padding: 2rem;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: rgba(255,255,255,0.95);
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            padding: 2rem;
            backdrop-filter: blur(10px);
        }

        /* 头部样式 */
        .header {
            text-align: center;
            margin-bottom: 2rem;
            position: relative;
        }

        .avatar {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 3px solid var(--primary-color);
            margin: 1rem auto;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
            transition: transform 0.3s ease;
        }

        .avatar:hover {
            transform: rotate(5deg) scale(1.05);
        }

        /* 卡片样式 */
        .card {
            background: white;
            border-radius: 15px;
            padding: 1.5rem;
            margin: 1.5rem 0;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        /* 图标动画 */
        .section-title {
            display: flex;
            align-items: center;
            margin: 1.5rem 0;
            color: var(--accent-color);
        }

        .section-title i {
            font-size: 1.8rem;
            margin-right: 1rem;
            transition: all 0.3s ease;
        }

        .section-title:hover i {
            transform: rotate(15deg) scale(1.2);
            color: var(--primary-color);
        }

        /* 信息项样式 */
        .info-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
            padding: 1rem;
        }

        .info-item {
            display: flex;
            align-items: center;
            padding: 1rem;
            background: #f8f9fa;
            border-radius: 10px;
            transition: all 0.3s ease;
        }

        .info-item:hover {
            background: var(--primary-color);
            color: white;
            transform: translateX(10px);
        }

        .info-item i {
            font-size: 1.5rem;
            margin-right: 1rem;
            min-width: 30px;
        }

        /* 动画关键帧 */
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }

        .floating {
            animation: float 3s ease-in-out infinite;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- 头部 -->
        <header class="header floating">
            <img src="3CFEE1B510A40F0CE181B4730130EC0C.jpg" alt="白晨阳" class="avatar">
            <h1>白晨阳</h1>
            <p>软件工程师 | 前端开发</p>
        </header>

        <!-- 基本信息 -->
        <section class="card">
            <div class="section-title">
                <i class="fas fa-user"></i>
                <h2>基本信息</h2>
            </div>
            <div class="info-grid">
                <div class="info-item">
                    <i class="fas fa-birthday-cake"></i>
                    <div>
                        <h3>出生日期：2004.10.31  邮箱：3380759787@qq.com</h3>
                        <p>性别：男  民族：汉族  电话：15506382932  地址：山东省烟台市芝罘区鲁东大学北苑23</p>
                    </div>
                </div>
                <!-- 更多信息项... -->
            </div>
        </section>

        <!-- 教育背景 -->
        <section class="card">
            <div class="section-title">
                <i class="fas fa-graduation-cap"></i>
                <h2>教育背景</h2>
            </div>
            <div class="info-grid">
                <div class="info-item">
                    <i class="fas fa-university"></i>
                    <div>
                        <h3>鲁东大学</h3>
                        <p>软件工程专业 本科</p>
                        <p>2023.09 - 2027.06</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="card">
            <div class="section-title">
                <i class="fas fa-graduation-cap"></i>
                <h2>技能证书</h2>
            </div>
            <div class="info-grid">
                <div class="info-item">
                    <i class="fas fa-university"></i>
                    <div>
                        <p>英语CET-4</p>
                        <p>计算机四级证书</p>
                    </div>
                </div>
            </div>
        </section>
        <!-- 技能证书 -->
        <section class="card">
            <div class="section-title">
                <i class="fas fa-certificate"></i>
                <h2>技能证书</h2>
            </div>
            <div class="info-grid">
                <div class="info-item">
                    <i class="fas fa-code"></i>
                    <div>
                        <h3>编程语言</h3>
                        <p>Java/Python/JavaScript</p>
                    </div>
                </div>
            </div>
        </section>
		<section class="card">
		    <div class="section-title">
		        <i class="fas fa-certificate"></i>
		        <h2>自我介绍</h2>
		    </div>
		    <div class="info-grid">
		        <div class="info-item">
		            <i class="fas fa-code"></i>
		            <div>
		                <h3>自我评价</h3>
		                <p>本人高中毕业于山东省青岛市城阳区第一高级中学，个人爱好打篮球，听音乐，偶像是NBA球星科比，对学校的前端设计开发比较感兴趣，性格开朗、积极向上，具有良好的团队协作能力和沟通能力。与同学相处融洽，互相之间关系良好并且友谊深厚，在校期间担任班委，组织过多次校园技术分享活动，培养了优秀的组织协调能力。热爱编程，熟悉Java、Python等开发语言，熟悉MySQL数据库开发，具有扎实的算法基础。对待工作认真负责，具有较强的学习能力和问题解决能力。曾获得校级程序设计大赛一等奖，并通过了PMP项目管理专业认证。日常喜欢钻研新技术，我始终坚持活到老学到老的信条，认为学无止境，无论什么时候都要坚持学习，无论是技能还是知识，都会对自己的人生有所帮助，听完我的自我评价，希望能对你有所帮助。</p>
		            </div>
		        </div>
		    </div>
		</section>
    </div>
</body>
</html>
