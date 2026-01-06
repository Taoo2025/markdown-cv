<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>陶思言 - 简历</title>
    <style>
        :root { --theme-color: rgb(37, 70, 101); --text-color: #747474; }
        body { font-family: "微软雅黑", sans-serif; background: #f5f5f5; margin: 0; padding: 40px; display: flex; justify-content: center; }
        .resume-container { width: 820px; background: #fff; box-shadow: 0 0 10px rgba(0,0,0,0.1); padding: 40px; color: var(--text-color); }
        
        /* 基本资料 */
        .header { display: flex; align-items: center; border-bottom: 2px solid var(--theme-color); padding-bottom: 20px; margin-bottom: 30px; }
        .avatar { width: 120px; height: 150px; border: 3px solid #eee; object-fit: cover; margin-right: 30px; }
        .info-text h1 { color: #121c26; font-size: 30px; margin: 0; }
        .info-text p { margin: 10px 0; font-size: 14px; }
        .contact-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 5px; font-size: 13px; }

        /* 模块标题 */
        .section-title { font-size: 20px; font-weight: 600; color: var(--theme-color); border-bottom: 1px solid var(--theme-color); margin: 25px 0 15px 0; padding-bottom: 5px; display: flex; align-items: center; }
        .section-title span { border-bottom: 3px solid #000; padding-bottom: 2px; }

        /* 内容样式 */
        .edu-item, .project-item { margin-bottom: 15px; }
        .row { display: flex; justify-content: space-between; font-weight: 600; color: var(--theme-color); margin-bottom: 5px; }
        .content { font-size: 14px; line-height: 1.7; text-align: justify; padding-left: 18px; }
        ul { padding-left: 20px; margin: 5px 0; }
    </style>
</head>
<body>
    <div class="resume-container">
        <div class="header">
            <img src="https://maobucv.com:9000/resume/avatar/微信图片_20251230205222_7686_5-1767640881322.jpg" class="avatar" alt="头像">
            <div class="info-text">
                <h1>陶思言</h1>
                <p><strong>一句话简介：</strong>热爱空间数据科学，激情与探索是我积极生活的动力</p>
                <div class="contact-grid">
                    <span>年龄：22岁</span>
                    <span>地址：北京</span>
                    <span>电话：18510539125</span>
                    <span>邮箱：taosiyan2025@163.com</span>
                </div>
            </div>
        </div>

        <div class="section-title"><span>求职意向</span></div>
        <div class="contact-grid">
            <span>意向岗位：GIS工程师、数据分析师</span>
            <span>求职类型：实习</span>
            <span>薪资：面议</span>
        </div>

        <div class="section-title"><span>教育背景</span></div>
        <div class="edu-item">
            <div class="row"><span>伦敦大学学院（UCL） | 城市空间科学</span><span>2025-09 至 2026-09</span></div>
            <div class="content">硕士 | 主修课程：GIS空间分析（R语言）、数据分析基础（Python）</div>
        </div>
        <div class="edu-item">
            <div class="row"><span>北京师范大学（BNU） | 人文地理与城乡规划</span><span>2021-09 至 2025-06</span></div>
            <div class="content">全日制本科 | 成绩排名50%；大学生艺术团“优秀学生干部”</div>
        </div>

        <div class="section-title"><span>实习经历</span></div>
        <div class="project-item">
            <div class="row"><span>好未来教育科技有限公司（学而思） | 教研实习生</span><span>2025-06 至 2025-09</span></div>
            <div class="content">
                <ul>
                    <li>参与小学数学课程研究与教学材料开发。</li>
                    <li>根据国家课程标准，协助起草课程内容、练习题及教学设计。</li>
                    <li>对学生成绩模式进行数据分析，以支持课程的迭代改进。</li>
                    <li>与高级研究员协作优化教学策略，并评估试点课程效果。</li>
                </ul>
            </div>
        </div>
        <div class="project-item">
            <div class="row"><span>北京剧萌文化发展有限公司 | 新媒体实习生</span><span>2023-06 至 2023-10</span></div>
            <div class="content">
                <ul>
                    <li>负责多平台社交媒体运营（微信、小红书）。</li>
                    <li>创作单篇阅读量超过 5,000 次的深度剧场相关内容。</li>
                    <li>创建并管理票务社群，实现粉丝增长 1000+。</li>
                </ul>
            </div>
        </div>

        <div class="section-title"><span>毕业论文</span></div>
        <div class="content">
            <strong>《北京市石景山区适老化社区生活圈评价》</strong>
            <ul>
                <li><strong>理论框架：</strong>基于环境行为学及“以人为本”理念构建评价体系，分析设施供给与需求错配。</li>
                <li><strong>技术实现：</strong>整合高德 POI、OSM 路网及房价数据，利用 Mapbox 引擎构建多级等时圈。</li>
                <li><strong>空间分析：</strong>采用熵权法确定权重，结合累计机会法评估可及性，应用莫兰指数识别聚类。</li>
                <li><strong>数据建模：</strong>通过 Python/R 进行数据清洗，利用 Pearson 相关性分析房龄对便利性的影响。</li>
            </ul>
        </div>

        <div class="section-title"><span>校园经历</span></div>
        <div class="edu-item">
            <div class="row"><span>大学生艺术团文化传媒部 | 部长</span><span>2021-10 至 2023-07</span></div>
            <div class="content">组织协调艺术团内部宣传工作，协助举办游园夜等活动；负责公众号运营及媒体课程，获“优秀学生干部”荣誉。</div>
        </div>
    </div>
</body>
</html>
