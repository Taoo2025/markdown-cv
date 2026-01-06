<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <style>
        @page { size: A4; margin: 0; }
        * { box-sizing: border-box; -webkit-print-color-adjust: exact; margin: 0; padding: 0; }
        
        body {
            font-family: 'PingFang SC', 'Microsoft YaHei', sans-serif;
            background: #fff;
            color: #222;
            line-height: 1.2; /* 极致行高 */
            font-size: 9.5pt;
        }

        .page {
            width: 210mm;
            height: 297mm;
            padding: 8mm 12mm; /* 略微缩小上下页边距 */
            margin: 0 auto;
        }

        /* 页眉：姓名与联系方式同行 */
        header {
            display: flex;
            justify-content: space-between;
            align-items: flex-end;
            border-bottom: 2px solid #1a4a7c;
            padding-bottom: 3px;
            margin-bottom: 6px;
        }

        h1 { font-size: 18pt; color: #1a4a7c; }
        .contact { text-align: right; font-size: 8.5pt; color: #444; }

        /* 模块标题：极简设计 */
        h2 { 
            font-size: 10.5pt; 
            margin: 5px 0 3px 0; 
            color: #1a4a7c;
            border-bottom: 1px solid #eee;
            padding-bottom: 1px;
            text-transform: uppercase;
        }

        /* 列表与内容间距 */
        .item { margin-bottom: 4px; }
        .item-header {
            display: flex;
            justify-content: space-between;
            font-weight: bold;
            font-size: 9.5pt;
        }

        .item-sub {
            color: #555;
            font-size: 8.5pt;
            margin: 1px 0;
        }

        ul { margin: 1px 0 3px 14px; }
        li { margin-bottom: 1px; }

        /* 技能网格 */
        .skills-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 1px 15px;
            font-size: 9pt;
        }

        b { color: #1a4a7c; font-weight: 600; }
    </style>
</head>
<body>
    <div class="page">
        <header>
            <div><h1>陶思言</h1></div>
            <div class="contact">
                ZTA069843@GMAIL.COM | +44 7770963613 | London / 北京
            </div>
        </header>

        <section>
            <h2>教育背景</h2>
            <div class="item">
                <div class="item-header"><span>伦敦大学学院 (UCL)</span><span>2025.09 - 2026.09</span></div>
                <div class="item-sub">MSc Urban Spatial Science (城市空间科学 硕士)</div>
            </div>
            <div class="item" style="margin-top:-2px;">
                <div class="item-header"><span>北京师范大学 (BNU)</span><span>2021.09 - 2025.06</span></div>
                <div class="item-sub">人文地理与城乡规划 本科 | GPA: 84/100</div>
            </div>
        </section>

        <section>
            <h2>科研项目</h2>
            <div class="item">
                <div class="item-header"><span>本科毕业论文：基于多源数据的适老化生活圈评价</span><span>2024.11 - 2025.06</span></div>
                <ul>
                    <li><b>技术架构：</b>整合高德POI、OSM路网及房价数据，利用 <b>Mapbox</b> 引擎构建多尺度步行等时圈。</li>
                    <li><b>空间统计：</b>应用 <b>Moran's I (LISA)</b> 识别空间聚集，通过皮尔逊系数分析建筑年代对服务便利性的影响。</li>
                    <li><b>量化评价：</b>结合环境行为理论，利用 <b>熵权法</b> 测算供需匹配度，为适老化改造提供量化支持。</li>
                </ul>
            </div>
        </section>

        <section>
            <h2>实习经历</h2>
            <div class="item">
                <div class="item-header"><span>好未来 (TAL) - 教研实习生</span><span>2025.06 - 2025.09</span></div>
                <ul>
                    <li>利用 <b>Python</b> 对学生表现数据建模，通过数据反馈迭代教学内容与教材研发。</li>
                </ul>
            </div>
            <div class="item">
                <div class="item-header"><span>北京剧目文化 - 新媒体运营实习生</span><span>2023.07 - 2023.10</span></div>
                <ul>
                    <li>负责多平台账号运营，产出5000+阅读量深度内容，实现粉丝增长1000+。</li>
                </ul>
            </div>
        </section>

        <section>
            <h2>专业技能</h2>
            <div class="skills-grid">
                <div><b>编程语言:</b> Python (精通), R, SQL</div>
                <div><b>GIS 工具:</b> ArcGIS Pro, QGIS, GEE</div>
                <div><b>数据分析:</b> 空间计量、机器学习</div>
                <div><b>语言能力:</b> 英语 (IELTS 6.5), 普通话</div>
            </div>
        </section>
    </div>
</body>
</html>
