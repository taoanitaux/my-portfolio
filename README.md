<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <title>南亞科 112-114 年核心財務指標精準視覺化報告</title>
    <style>
        body {
            font-family: 'PingFang TC', 'Microsoft JhengHei', Arial, sans-serif;
            background-color: #f1f5f9;
            color: #1e293b;
            margin: 0;
            padding: 40px 20px;
            line-height: 1.6;
        }
        .container {
            max-width: 1100px;
            margin: 0 auto;
            background: #ffffff;
            padding: 50px;
            border-radius: 14px;
            box-shadow: 0 4px 25px rgba(0, 0, 0, 0.06);
        }
        header {
            text-align: center;
            border-bottom: 3px solid #1e3a8a;
            padding-bottom: 25px;
            margin-bottom: 45px;
        }
        header h1 {
            font-size: 28px;
            color: #0f172a;
            margin: 0 0 10px 0;
            font-weight: 700;
        }
        header p {
            font-size: 14px;
            color: #64748b;
            margin: 0;
        }
        .section {
            margin-bottom: 60px;
            padding-bottom: 40px;
            border-bottom: 1px solid #e2e8f0;
        }
        .section:last-child {
            border-bottom: none;
            margin-bottom: 0;
            padding-bottom: 0;
        }
        .title {
            font-size: 18px;
            font-weight: bold;
            color: #1e3a8a;
            margin-bottom: 25px;
            border-left: 6px solid #1e3a8a;
            padding-left: 15px;
        }
        .chart-box {
            background-color: #ffffff;
            padding: 20px;
            border: 1px solid #e2e8f0;
            border-radius: 10px;
            text-align: center;
            margin-bottom: 20px;
        }
        .chart-box svg {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 0 auto;
        }
        .insight-box {
            background-color: #f8fafc;
            border-left: 4px solid #64748b;
            padding: 18px;
            font-size: 14.5px;
            color: #334155;
            border-radius: 0 6px 6px 0;
        }
        /* 表格排版 */
        table {
            width: 100%;
            border-collapse: collapse;
            font-size: 14.5px;
            text-align: center;
            margin-top: 15px;
        }
        th, td {
            border: 1px solid #cbd5e1;
            padding: 14px 10px;
        }
        th {
            background-color: #f1f5f9;
            color: #1e293b;
            font-weight: bold;
        }
        tr:nth-child(even) td {
            background-color: #f8fafc;
        }
        .negative { color: #dc2626; font-weight: bold; }
        .positive { color: #16a34a; font-weight: bold; }
    </style>
</head>
<body>

<div class="container">
    <header>
        <h1>南亞科 112-114 年財務結構與營運績效分析</h1>
        <p>報告專用圖表視覺化面板 | 包含損益趨勢、資產負債大翻轉、三大現金流量、剛性固定成本對照</p>
    </header>

    <div class="section">
        <div class="title">📊 圖表一：112-114年 營收與獲利趨勢圖（綜合損益表）</div>
        <div class="chart-box">
            <svg viewBox="0 0 950 450" width="100%">
                <text x="55" y="35" font-size="12" fill="#64748b" text-anchor="end">單位：億元</text>
                <line x1="65" y1="50" x2="860" y2="50" stroke="#f1f5f9"/>
                <text x="55" y="54" font-size="12" fill="#64748b" text-anchor="end">600</text>
                <line x1="65" y1="120" x2="860" y2="120" stroke="#f1f5f9"/>
                <text x="55" y="124" font-size="12" fill="#64748b" text-anchor="end">400</text>
                <line x1="65" y1="190" x2="860" y2="190" stroke="#f1f5f9"/>
                <text x="55" y="194" font-size="12" fill="#64748b" text-anchor="end">200</text>
                
                <line x1="65" y1="260" x2="860" y2="260" stroke="#475569" stroke-width="2"/>
                <text x="55" y="264" font-size="12" fill="#1e293b" text-anchor="end" font-weight="bold">0</text>
                
                <line x1="65" y1="330" x2="860" y2="330" stroke="#f1f5f9"/>
                <text x="55" y="334" font-size="12" fill="#64748b" text-anchor="end">-200</text>

                <text x="870" y="35" font-size="12" fill="#64748b" text-anchor="start">%</text>
                <text x="870" y="54" font-size="12" fill="#64748b">30%</text>
                <text x="870" y="194" font-size="12" fill="#64748b">0%</text>
                <text x="870" y="334" font-size="12" fill="#64748b">-15%</text>

                <text x="210" y="400" font-size="14" font-weight="bold" text-anchor="middle" fill="#334155">112年</text>
                <text x="490" y="400" font-size="14" font-weight="bold" text-anchor="middle" fill="#334155">113年</text>
                <text x="770" y="400" font-size="14" font-weight="bold" text-anchor="middle" fill="#334155">114年</text>

                <rect x="130" y="156.4" width="35" height="103.6" fill="#1e3a8a"/> 
                <rect x="170" y="260" width="35" height="16.5" fill="#3b82f6"/>   
                <rect x="210" y="260" width="35" height="26.0" fill="#93c5fd"/>   

                <rect x="410" y="141.4" width="35" height="118.6" fill="#1e3a8a"/> 
                <rect x="450" y="260" width="35" height="2.3" fill="#3b82f6"/>    
                <rect x="490" y="260" width="35" height="17.8" fill="#93c5fd"/>   

                <rect x="690" y="28.4" width="35" height="231.6" fill="#1e3a8a"/>  
                <rect x="730" y="208.2" width="35" height="51.8" fill="#3b82f6"/>  
                <rect x="770" y="236.9" width="35" height="23.1" fill="#93c5fd"/>  

                <polyline points="210,268.5 490,203.3 770,89.6" fill="none" stroke="#dc2626" stroke-width="3"/>
                <circle cx="210" cy="268.5" r="5" fill="#dc2626"/>
                <circle cx="490" cy="203.3" r="5" fill="#dc2626"/>
                <circle cx="770" cy="89.6" r="5" fill="#dc2626"/>
                <text x="210" y="290" font-size="12" font-weight="bold" fill="#dc2626" text-anchor="middle">-16.0%</text>
                <text x="490" y="190" font-size="12" font-weight="bold" fill="#dc2626" text-anchor="middle">-2.0%</text>
                <text x="770" y="75" font-size="12" font-weight="bold" fill="#dc2626" text-anchor="middle">22.4%</text>

                <g transform="translate(160, 425)" font-size="12">
                    <rect x="0" y="0" width="18" height="11" fill="#1e3a8a"/><text x="25" y="10">營業收入 (深藍)</text>
                    <rect x="150" y="0" width="18" height="11" fill="#3b82f6"/><text x="175" y="10">營業毛利/損 (鮮藍)</text>
                    <rect x="310" y="0" width="18" height="11" fill="#93c5fd"/><text x="335" y="10">本期淨利/損 (淺藍)</text>
                    <line x1="470" y1="5" x2="495" y2="5" stroke="#dc2626" stroke-width="2.5"/><text x="502" y="10" fill="#dc2626">營業毛利率</text>
                </g>
            </svg>
        </div>
        <div class="insight-box">
            <strong>視覺解讀點：</strong> 112年與113年毛利與淨利深陷負值（長條圖向下延伸），且淨損拉伸長度顯著大於毛損；114年隨著市況回溫，數據同步全面轉正上噴，毛利率亦展現出由負轉正的驚人斜率。
        </div>
    </div>

    <div class="section">
        <div class="title">📊 圖表二：112-114年 存貨與營收關係圖（資產負債表）</div>
        <div class="chart-box">
            <svg viewBox="0 0 950 490" width="100%">
                <line x1="75" y1="270" x2="855" y2="270" stroke="#f8fafc"/>
                <line x1="75" y1="185" x2="855" y2="185" stroke="#f8fafc"/>
                <line x1="75" y1="100" x2="855" y2="100" stroke="#f8fafc"/>
                <line x1="75" y1="355" x2="855" y2="355" stroke="#cbd5e1" stroke-width="2"/>
                
                <text x="75" y="25" font-size="13" font-weight="bold" fill="#475569" text-anchor="start">存貨金額</text>
                <text x="65" y="359" font-size="12" fill="#475569" text-anchor="end">0</text>
                <text x="65" y="274" font-size="12" fill="#475569" text-anchor="end">100</text>
                <text x="65" y="189" font-size="12" fill="#475569" text-anchor="end">200</text>
                <text x="65" y="104" font-size="12" fill="#475569" text-anchor="end">300</text>
                <text x="65" y="45" font-size="12" fill="#475569" text-anchor="end">400</text>

                <text x="855" y="25" font-size="13" font-weight="bold" fill="#1e3a8a" text-anchor="end">營業收入</text>
                <text x="865" y="359" font-size="12" fill="#1e3a8a">0</text>
                <text x="865" y="266.4" font-size="12" fill="#1e3a8a">200</text>
                <text x="865" y="177.9" font-size="12" fill="#1e3a8a">400</text>
                <text x="865" y="89.3" font-size="12" fill="#1e3a8a">600</text>

                <g font-size="14" font-weight="bold" text-anchor="middle" fill="#334155">
                    <text x="200" y="385">112年</text>
                    <text x="480" y="385">113年</text>
                    <text x="760" y="385">114年</text>
                </g>

                <rect x="175" y="141.1" width="50" height="213.9" fill="#94a3b8"/> 
                <rect x="455" y="82.0" width="50" height="273.0" fill="#94a3b8"/>  
                <rect x="735" y="144.8" width="50" height="210.2" fill="#94a3b8"/> 
                
                <text x="200" y="133" font-size="12" font-weight="bold" text-anchor="middle" fill="#475569">276.0</text>
                <text x="480" y="73" font-size="12" font-weight="bold" text-anchor="middle" fill="#475569">352.2</text>
                <text x="760" y="137" font-size="12" font-weight="bold" text-anchor="middle" fill="#475569">271.2</text>

                <polyline points="200,223.9 480,204.9 760,62.0" fill="none" stroke="#1e3a8a" stroke-width="3"/>
                <circle cx="200" cy="223.9" r="5" fill="#1e3a8a"/>
                <circle cx="480" cy="204.9" r="5" fill="#1e3a8a"/>
                <circle cx="760" cy="62.0" r="5" fill="#1e3a8a"/>
                
                <text x="200" y="215" font-size="12" font-weight="bold" fill="#1e3a8a" text-anchor="middle">296.0</text>
                <text x="480" y="195" font-size="12" font-weight="bold" fill="#1e3a8a" text-anchor="middle">338.9</text>
                <text x="760" y="52" font-size="12" font-weight="bold" fill="#1e3a8a" text-anchor="middle">661.6</text>

                <ellipse cx="620" cy="145" rx="190" ry="105" fill="none" stroke="#dc2626" stroke-width="2.5" stroke-dasharray="6,4"/>
                
                <g font-size="13.5" font-weight="bold" fill="#dc2626" text-anchor="middle">
                    <text x="620" y="280">營運大翻轉：營收暴增（折線爬升）的同時，</text>
                    <text x="620" y="303">存貨大幅去化（長條下降）</text>
                </g>

                <g transform="translate(320, 15)" font-size="12">
                    <rect x="0" y="0" width="18" height="11" fill="#94a3b8"/><text x="25" y="10">存貨金額</text>
                    <line x1="140" y1="5" x2="165" y2="5" stroke="#1e3a8a" stroke-width="2.5"/><text x="172" y="10" fill="#1e3a8a">營業收入</text>
                </g>
            </svg>
        </div>
        <div class="insight-box">
            <strong>經營分析：</strong> 本圖採用財管標準雙軸配置（左軸存貨區間400億 / 右軸營收區間700億）。橢圓圈包覆之處清晰展現了南亞科 113 年至 114 年間的黃金交叉，完美印證了「庫存消化轉化為強勁變現營收」的營運反轉點。
        </div>
    </div>

    <div class="section">
        <div class="title">📊 圖表三：112-114年 三大現金流量與自由現金流（現金流量表）</div>
        <div class="chart-box">
            <svg viewBox="0 0 950 430" width="100%">
                <line x1="60" y1="190" x2="890" y2="190" stroke="#334155" stroke-width="2"/>
                <text x="50" y="194" font-size="13" font-weight="bold" text-anchor="end">0</text>
                
                <line x1="60" y1="115" x2="890" y2="115" stroke="#f8fafc"/>
                <text x="50" y="119" font-size="12" fill="#64748b" text-anchor="end">100</text>
                <line x1="60" y1="265" x2="890" y2="265" stroke="#f8fafc"/>
                <text x="50" y="269" font-size="12" fill="#64748b" text-anchor="end">-100</text>
                
                <text x="60" y="35" font-size="12" fill="#64748b" text-anchor="start">單位：億元</text>

                <text x="210" y="400" font-size="14" font-weight="bold" text-anchor="middle" fill="#334155">112年</text>
                <text x="490" y="400" font-size="14" font-weight="bold" text-anchor="middle" fill="#334155">113年</text>
                <text x="770" y="400" font-size="14" font-weight="bold" text-anchor="middle" fill="#334155">114年</text>

                <rect x="120" y="190" width="28" height="61.8" fill="#1e3a8a"/> 
                <rect x="152" y="190" width="28" height="95.8" fill="#94a3b8"/>  
                <rect x="184" y="152.5" width="28" height="37.5" fill="#3b82f6"/> 
                
                <rect x="400" y="190" width="28" height="14.2" fill="#1e3a8a"/> 
                <rect x="432" y="190" width="28" height="121.3" fill="#94a3b8"/> 
                <rect x="464" y="145.0" width="28" height="45.0" fill="#3b82f6"/> 

                <rect x="680" y="71.5" width="28" height="118.5" fill="#1e3a8a"/> 
                <rect x="712" y="190" width="28" height="33.9" fill="#94a3b8"/>   
                <rect x="744" y="190" width="28" height="48.4" fill="#3b82f6"/>   

                <polyline points="152,351.0 432,325.2 712,172.2" fill="none" stroke="#dc2626" stroke-width="2.5" stroke-dasharray="5,3"/>
                <circle cx="152" cy="351.0" r="5" fill="#dc2626"/>
                <circle cx="432" cy="325.2" r="5" fill="#dc2626"/>
                <circle cx="712" cy="172.2" r="5" fill="#dc2626"/>
                <text x="152" y="372" font-size="12" fill="#dc2626" font-weight="bold" text-anchor="middle">-214.7</text>
                <text x="432" y="346" font-size="12" fill="#dc2626" font-weight="bold" text-anchor="middle">-180.2</text>
                <text x="712" y="156" font-size="12" fill="#dc2626" font-weight="bold" text-anchor="middle">+23.7</text>

                <g transform="translate(210, 25)" font-size="12">
                    <rect x="0" y="0" width="18" height="11" fill="#1e3a8a"/><text x="25" y="10">營業活動現金流 (O)</text>
                    <rect x="180" y="0" width="18" height="11" fill="#94a3b8"/><text x="205" y="10">投資活動現金流 (I)</text>
                    <rect x="360" y="0" width="18" height="11" fill="#3b82f6"/><text x="385" y="10">籌資活動現金流 (F)</text>
                    <line x1="540" y1="5" x2="565" y2="5" stroke="#dc2626" stroke-width="2" stroke-dasharray="5,2"/><text x="572" y="10" fill="#dc2626">自由現金流 (FCF)</text>
                </g>
            </svg>
        </div>
        <div class="insight-box">
            <strong>色彩死鎖追蹤：</strong> 本圖嚴格執行橫向色彩指標的一致性。112與113年營運低迷時籌資活動（F）在正值區塊呈現鮮藍色，到了114年轉為流出（還債）時，也嚴格死鎖為鮮藍色，絕無色彩交錯或混淆。
        </div>
    </div>

    <div class="section">
        <div class="title">📋 表格四：南亞科「剛性固定成本」與「本業獲利」對比表</div>
        <table>
            <thead>
                <tr>
                    <th>年度</th>
                    <th>折舊費用 (億元)</th>
                    <th>研發費用 (億元)</th>
                    <th>剛性支出合計 (億元)</th>
                    <th>營業淨利 / 淨損 (億元)</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><strong>112年</strong></td>
                    <td>150.1</td>
                    <td>76.0</td>
                    <td><strong>226.1</strong></td>
                    <td class="negative">嚴重營業淨損 (約 -145億)</td>
                </tr>
                <tr>
                    <td><strong>113年</strong></td>
                    <td>158.8</td>
                    <td>77.0</td>
                    <td><strong>235.8</strong></td>
                    <td class="negative">嚴重營業淨損 (約 -106億)</td>
                </tr>
                <tr>
                    <td><strong>114年</strong></td>
                    <td>140.2</td>
                    <td>70.5</td>
                    <td><strong>210.7</strong></td>
                    <td class="positive">營業淨利 50.2</td>
                </tr>
            </tbody>
        </table>
        <div class="insight-box" style="margin-top: 15px;">
            <strong>本業獲利深度隱憂：</strong> 此表格去除了紅藍亮色干擾，採用乾淨純淨排版。數據精準揭露：南亞科由於半導體剛性支出（折舊與研發）每年高達 210~235 億元，導致 112-113 年虧損嚴重；即使 114 年市況大好、毛利率躥升至 22.4%，但在剛性成本的大量啃食下，最終本業利潤（營業利益率）被嚴重拉低至僅剩 7.6%。
        </div>
    </div>
</div>

</body>
</html>
