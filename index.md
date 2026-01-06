<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>陶思言_技术简历</title>
    <style>
        /* 基础样式：模拟 A4 比例 */
        :root {
            --primary-color: #1a4a7c;
            --text-color: #333;
            --line-height: 1.4;
        }

        body {
            font-family: 'Segoe UI', 'PingFang SC', sans-serif;
            line-height: var(--line-height);
            color: var(--text-color);
            margin: 0;
            background: #f0f0f0;
        }

        .page {
            width: 210mm;
            min-height: 296mm; /* A4 标准高度减去误差 */
            margin: 10mm auto;
            background: white;
            padding: 12mm 15mm; /* 缩减边距以容纳更多内容 */
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            box-sizing: border-box;
            position: relative;
        }

        /* 打印优化：强制单页 */
        @media print {
            body { background: none; }
            .page { 
                margin: 0; 
                box-shadow: none; 
                width: 100%;
                height: 100%;
            }
            @page {
                size: A4;
                margin: 0;
            }
        }

        header {
            border-bottom: 2px solid var(--primary-color);
            padding-bottom: 8px;
            margin-bottom: 12px;
            display: flex;
            justify-content: space-between;
            align-items: flex-end;
        }

        h1 { margin: 0; color: var(--primary-color); font-size: 24pt; }
        .contact { font-size: 9pt; text-align: right; }

        section { margin-bottom: 12px; }
        h2 { 
            font-size: 13pt; 
            background: #f4f7fa; 
            color: var(--primary-color); 
            padding: 3px 8px; 
            border-left: 4px solid var(--primary-color);
            margin: 8px 0;
        }

        .item { margin-bottom: 6px; }
        .item-header { display: flex; justify-content: space-between; font-weight: bold; font-size: 10.5pt; }
        .item-sub { color: #666; font-size: 9pt; font-style: italic; margin-bottom: 2px; }
        
        ul { margin: 0; padding-left: 18px; font-size: 9.5pt; }
        li { margin-bottom: 2px; }

        /* 技术栈紧凑排列 */
        .skills-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 5px 20px;
            font-size: 9.5pt;
        }

        b { color: var(--primary-color); }
    </style>
</head>
<body>
    <div class="page">
        <header>
            <div>
                <h1>陶思言 (Tao Siyan)</h1>
                <p style="margin:4px 0 0 0; font-weight:bold;">空间数据科学 | 人文地理与城乡规划</p>
            </div>
            <div class="contact">
                Email: ZTA069843@GMAIL.COM<br>
                Tel: +44 7770963613<br>
                London, UK / 北京
            </div>
        </header>

        <section>
            <h2>教育背景</h2>
            <div class="item">
                <div class="item-header">
                    <span>伦敦大学学院 (UCL)</span>
                    <span>2025.09 - 2026.09 (预计)</span>
                </div>
                <div class="item-sub">城市空间科学 硕士 (MSc Urban Spatial Science)</div>
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
                    <li><b>技术架构：</b>整合 Amap API POI、OSM 路网及房价数据，利用 <b>Mapbox</b> 引擎构建 300m-1000m 步行等时圈。</li>
                    <li><b>空间分析：</b>应用 <b>Global/Local Moran's I (LISA)</b> 识别空间聚集特征，通过皮尔逊相关系数分析建筑年份对服务便利性的影响。</li>
                    <li><b>评价体系：</b>结合环境行为理论，利用<b>信息熵权法</b>与累积机会法量化供需匹配度，提出适老化改造建议。</li>
                </ul>
            </div>
        </section>

        <section>
            <h2>实习经历</h2>
            <div class="item">
                <div class="item-header">
                    <span>好未来教育集团 (TAL) - 教研实习生</span>
                    <span>2025.06 - 2025.09</span>
                </div>
                <ul>
                    <li>基于国家课程标准进行小学数学教材研发，参与教学内容与练习题的设计。</li>
                    <li>利用 <b>Python</b> 进行学生表现数据建模，挖掘学习痛点以迭代教学策略。</li>
                </ul>
            </div>
            <div class="item">
                <div class="item-header">
                    <span>北京剧目文化 - 新媒体运营实习生</span>
                    <span>2023.07 - 2023.10</span>
                </div>
                <ul>
                    <li>运营微信、小红书多平台账号，产出 5000+ 阅读量深度稿件，带动粉丝增长 1000+。</li>
                </ul>
            </div>
        </section>

        <section>
            <h2>专业技能</h2>
            <div class="skills-grid">
                <div><b>编程语言:</b> Python (精通), R (熟练), SQL</div>
                <div><b>GIS 工具:</b> ArcGIS, QGIS, ENVI, Google Earth Engine</div>
                <div><b>数据科学:</b> 空间统计、机器学习、数据可视化</div>
                <div><b>语言能力:</b> 英语 (IELTS 6.5), 普通话 (母语)</div>
            </div>
        </section>
    </div>
</body>
</html>
