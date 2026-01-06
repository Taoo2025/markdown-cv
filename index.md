<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>陶思言_简历_一页版</title>
    <style>
        /* 强制 A4 页面设置 */
        @page { size: A4; margin: 0; }
        * { box-sizing: border-box; -webkit-print-color-adjust: exact; }
        
        body {
            font-family: 'PingFang SC', 'Microsoft YaHei', sans-serif;
            margin: 0; padding: 0;
            background: #f5f5f5;
            color: #333;
            line-height: 1.3; /* 紧凑行高 */
        }

        .page {
            width: 210mm;
            height: 297mm;
            padding: 10mm 12mm; /* 适中的内边距 */
            margin: 0 auto;
            background: white;
            overflow: hidden; /* 强制切断超出内容 */
        }

        /* 页眉紧凑化 */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1.5px solid #1a4a7c;
            padding-bottom: 5px;
            margin-bottom: 8px;
        }

        h1 { margin: 0; font-size: 20pt; color: #1a4a7c; letter-spacing: 1px; }
        .contact { text-align: right; font-size: 8.5pt; color: #555; line-height: 1.2; }

        /* 模块间距极度压缩 */
        section { margin-bottom: 5px; }
        
        h2 { 
            font-size: 11pt; 
            margin: 4px 0; 
            padding: 2px 6px;
            background: #f0f4f8; 
            color: #1a4a7c;
            border-left: 3px solid #1a4a7c;
        }

        /* 项目条目：标题与日期同行 */
        .item-header {
            display: flex;
            justify-content: space-between;
            font-weight: bold;
            font-size: 10pt;
            margin-top: 3px;
        }

        .item-sub {
            color: #666;
            font-size: 8.5pt;
            font-style: italic;
            margin-bottom: 1px;
        }

        /* 列表优化 */
        ul { margin: 2px 0; padding-left: 15px; }
        li { font-size: 9pt; margin-bottom: 1px; }

        /* 技能网格 */
        .skills-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 2px 15px;
            font-size: 9pt;
            padding: 2px 5px;
        }

        b { color: #1a4a7c; }

        /* 打印模式微调 */
        @media print {
            body { background: none; }
            .page { margin: 0; box-shadow: none; }
        }
    </style>
</head>
<body>
    <div class="page">
        <header>
            <div>
                <h1>陶思言</h1>
                <p style="margin:2px 0 0 0; font-size:10pt; font-weight:bold;">空间数据科学 | 城市治理研究</p>
            </div>
            <div class="contact">
                ZTA069843@GMAIL.COM | +44 7770963613<br>
                London, UK / 北京 | 2025届毕业生
            </div>
        </header>

        <section>
            <h2>教育背景</h2>
            <div class="item">
                <div class="item-header">
                    <span>伦敦大学学院 (UCL)</span>
                    <span>2025.09 - 2026.09 (预计)</span>
                </div>
                <div class="item-sub">MSc Urban Spatial Science (城市空间科学 硕士)</div>
            </div>
            <div class="item">
                <div class="item-header">
                    <span>北京师范大学 (BNU)</span>
                    <span>2021.09 - 2025.06</span>
                </div>
                <div class="item-sub">人文地理与城乡规划 本科 | GPA: 84/100</div>
            </div>
        </section>

        <section>
            <h2>科研项目</h2>
            <div class="item">
                <div class="item-header">
                    <span>本科毕业论文：基于多源数据的适老化生活圈评价</span>
                    <span>2024.11 - 2025.06</span>
                </div>
                <ul>
                    <li><b>技术架构：</b>整合高德 API POI、OSM 及房价数据，利用 <b>Mapbox</b> 引擎构建多尺度步行等时圈。</li>
                    <li><b>空间统计：</b>应用 <b>Moran's I (LISA)</b> 识别空间聚集，通过皮尔逊相关系数分析建筑年代对服务便利性的影响。</li>
                    <li><b>量化评价：</b>结合环境行为理论，利用 <b>熵权法</b> 测算供需匹配度，为老旧小区改造提供量化决策支持。</li>
                </ul>
            </div>
        </section>

        <section>
            <h2>实习经历</h2>
            <div class="item">
                <div class="item-header">
                    <span>好未来 (TAL) - 教研实习生</span>
                    <span>2025.06 - 2025.09</span>
                </div>
                <ul>
                    <li>负责小学数学教材研发，利用 <b>Python</b> 对学生表现数据建模，通过数据反馈迭代教学内容。</li>
                </ul>
            </div>
            <div class="item">
                <div class="item-header">
                    <span>北京剧目文化 - 新媒体运营实习生</span>
                    <span>2023.07 - 2023.10</span>
                </div>
                <ul>
                    <li>运营多平台账号，产出 5000+ 阅读量深度内容，实现粉丝增长 1000+ 并在社区转化。</li>
                </ul>
            </div>
        </section>

        <section>
            <h2>专业技能</h2>
            <div class="skills-grid">
                <div><b>编程语言:</b> Python (精通), R, SQL</div>
                <div><b>GIS 工具:</b> ArcGIS Pro, QGIS, GEE</div>
                <div><b>数据分析:</b> 空间计量、机器学习、数据清洗</div>
                <div><b>语言能力:</b> 英语 (IELTS 6.5), 普通话</div>
            </div>
        </section>
    </div>
</body>
</html>
