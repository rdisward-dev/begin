<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>人偶苏醒协议 · 圣骸终端</title>
    <!-- Google Fonts 优雅衬线 + 无衬线 -->
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;500;600;700&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: radial-gradient(circle at 20% 30%, #0f0c08, #030201);
            font-family: 'Inter', sans-serif;
            color: #e2dccd;
            padding: 2rem 1.5rem;
            min-height: 100vh;
            position: relative;
        }

        /* 四角装饰 — 模仿原版奢华细节 */
        body::before {
            content: '';
            position: fixed;
            top: 1.5rem;
            left: 1.5rem;
            width: 40px;
            height: 40px;
            border-top: 2px solid #c5a059;
            border-left: 2px solid #c5a059;
            opacity: 0.5;
            pointer-events: none;
            z-index: 10;
        }

        body::after {
            content: '';
            position: fixed;
            bottom: 1.5rem;
            right: 1.5rem;
            width: 40px;
            height: 40px;
            border-bottom: 2px solid #c5a059;
            border-right: 2px solid #c5a059;
            opacity: 0.5;
            pointer-events: none;
            z-index: 10;
        }

        /* 主容器 玻璃质感 + 金框 */
        .terminal-container {
            max-width: 1300px;
            margin: 0 auto;
            background: rgba(6, 5, 4, 0.78);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(197, 160, 89, 0.45);
            box-shadow: 0 20px 35px -15px rgba(0,0,0,0.8), inset 0 1px 0 rgba(255,255,255,0.05);
            border-radius: 4px;
            padding: 1.8rem 2rem;
            transition: all 0.2s;
        }

        /* 标题区 */
        .title-gold {
            font-family: 'Cinzel', serif;
            text-align: center;
            font-size: 2rem;
            letter-spacing: 5px;
            color: #d4af37;
            text-shadow: 0 0 10px rgba(212, 175, 55, 0.4);
            border-bottom: 2px solid #c5a059;
            display: inline-block;
            width: auto;
            margin: 0 auto 1.2rem auto;
            padding-bottom: 10px;
        }

        .sub-gold {
            text-align: center;
            font-size: 0.7rem;
            letter-spacing: 3px;
            text-transform: uppercase;
            color: #c5a059aa;
            margin-top: -0.8rem;
            margin-bottom: 2rem;
        }

        /* 卡片区块 */
        .card-section {
            border: 1px solid rgba(197, 160, 89, 0.3);
            background: rgba(10, 8, 6, 0.55);
            border-radius: 8px;
            margin-bottom: 2rem;
            position: relative;
            transition: border-color 0.2s;
        }
        .card-section:hover {
            border-color: rgba(197, 160, 89, 0.6);
        }
        .section-badge {
            position: absolute;
            top: -12px;
            left: 18px;
            background: #1e1912;
            border: 1px solid #c5a059;
            border-radius: 30px;
            padding: 2px 18px;
            font-size: 0.7rem;
            font-weight: 600;
            letter-spacing: 2px;
            color: #e9d7b0;
            backdrop-filter: blur(4px);
            font-family: 'Cinzel', serif;
        }
        .inner-pad {
            padding: 1.5rem 1.8rem 1.5rem 1.8rem;
        }

        /* 表单栅格 */
        .form-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 1.2rem;
            margin-bottom: 1rem;
        }
        .field {
            flex: 1;
            min-width: 170px;
        }
        .field label {
            display: flex;
            justify-content: space-between;
            font-size: 0.7rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            font-weight: 400;
            color: #bfae85;
            margin-bottom: 6px;
        }
        .small-btn {
            background: transparent;
            border: 1px solid #c5a059;
            color: #c5a059;
            font-size: 0.6rem;
            padding: 2px 10px;
            border-radius: 20px;
            cursor: pointer;
            transition: 0.2s;
        }
        .small-btn:hover {
            background: #c5a059;
            color: #0c0a06;
            border-color: #efcd82;
        }

        input, select {
            width: 100%;
            background: #0a0805;
            border: 1px solid #4d3e2a;
            border-radius: 6px;
            padding: 8px 12px;
            color: #f2e5cf;
            font-family: 'Inter', monospace;
            font-size: 0.85rem;
            transition: all 0.2s;
        }
        input:focus, select:focus {
            outline: none;
            border-color: #c5a059;
            box-shadow: 0 0 6px rgba(197,160,89,0.4);
        }

        .desc-box {
            font-size: 0.7rem;
            margin-top: 8px;
            padding-left: 8px;
            border-left: 2px solid #7a6233;
            color: #bdab83;
            min-height: 2.6rem;
            line-height: 1.3;
            background: rgba(0,0,0,0.2);
            border-radius: 2px;
        }

        .skill-desc {
            border-left-color: #c87e2e;
            color: #f5cf9b;
        }

        /* 主按钮 */
        .rite-button {
            background: linear-gradient(135deg, #2d2418, #120f0a);
            border: 1px solid #c5a059;
            padding: 12px 32px;
            font-family: 'Cinzel', serif;
            font-size: 1rem;
            letter-spacing: 4px;
            font-weight: 600;
            color: #efdfb3;
            cursor: pointer;
            transition: all 0.25s ease;
            border-radius: 40px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.6);
            width: 100%;
            max-width: 360px;
            margin: 0 auto;
            display: block;
            text-transform: uppercase;
        }
        .rite-button:hover {
            background: #3b2d1e;
            border-color: #e9bc5e;
            color: #fff0cf;
            box-shadow: 0 0 14px rgba(197,160,89,0.5);
            transform: scale(1.02);
        }

        /* 输出区域 */
        .output-panel {
            margin-top: 2rem;
            border-top: 1px solid rgba(197,160,89,0.3);
            padding-top: 1.5rem;
        }
        .output-label {
            font-size: 0.7rem;
            text-align: center;
            text-transform: uppercase;
            letter-spacing: 3px;
            color: #c5a059bb;
            margin-bottom: 12px;
        }
        textarea {
            width: 100%;
            background: #0c0906;
            border: 1px solid #5e4a2c;
            border-radius: 10px;
            color: #eace9f;
            font-family: 'Courier New', monospace;
            font-size: 12px;
            padding: 16px;
            resize: vertical;
            transition: 0.2s;
        }
        textarea:focus {
            border-color: #c5a059;
            outline: none;
        }

        /* 响应式 */
        @media (max-width: 760px) {
            body { padding: 1rem; }
            .terminal-container { padding: 1.2rem; }
            .inner-pad { padding: 1rem; }
            .title-gold { font-size: 1.5rem; }
        }
        hr {
            border-color: #332818;
            margin: 0.5rem 0;
        }
        .flex-row {
            display: flex;
            align-items: center;
            gap: 10px;
            flex-wrap: wrap;
        }
        .text-gold {
            color: #d4af37;
        }
    </style>
</head>
<body>

<div class="terminal-container">
    <div style="text-align: center;">
        <div class="title-gold">⚜️ 人偶苏醒协议 ⚜️</div>
        <div class="sub-gold">Nechronica · 魂缮终端 V4.6</div>
    </div>

    <!-- 素体档案 -->
    <div class="card-section">
        <div class="section-badge">⚙️ 素体档案</div>
        <div class="inner-pad">
            <div class="form-grid">
                <div class="field">
                    <label>识别名</label>
                    <input type="text" id="name" placeholder="请输入编号或称呼...">
                    <div class="desc-box">人偶的身份标识，刻于颈后。</div>
                </div>
                <div class="field">
                    <label>肉体享年</label>
                    <input type="number" id="age_body" value="10" min="8" max="17">
                    <div class="desc-box">外表生理年龄（8~17）</div>
                </div>
                <div class="field">
                    <label>精神年龄</label>
                    <input type="number" id="age_mind" value="10">
                    <div class="desc-box">灵魂心理年龄</div>
                </div>
            </div>
            <div class="form-grid">
                <div class="field">
                    <label>职位 (Position)</label>
                    <select id="position" onchange="updateUI()"></select>
                    <div id="desc_pos" class="desc-box"></div>
                </div>
                <div class="field">
                    <label>主要职阶 (Main)</label>
                    <select id="main_class" onchange="updateUI()"></select>
                    <div id="desc_main" class="desc-box"></div>
                </div>
                <div class="field">
                    <label>辅助职阶 (Sub)</label>
                    <select id="sub_class" onchange="updateUI()"></select>
                    <div id="desc_sub" class="desc-box"></div>
                </div>
            </div>
        </div>
    </div>

    <!-- 技能植入 -->
    <div class="card-section">
        <div class="section-badge">🧠 技能植入</div>
        <div class="inner-pad">
            <div class="form-grid">
                <div class="field">
                    <label>职位专属技能</label>
                    <select id="skill_pos" onchange="updateSkillDesc()"></select>
                    <div id="sd_pos" class="desc-box skill-desc"></div>
                </div>
                <div class="field">
                    <label>职阶技能 I</label>
                    <select id="skill_main_1" onchange="updateSkillDesc()"></select>
                    <div id="sd_m1" class="desc-box skill-desc"></div>
                </div>
                <div class="field">
                    <label>职阶技能 II</label>
                    <select id="skill_main_2" onchange="updateSkillDesc()"></select>
                    <div id="sd_m2" class="desc-box skill-desc"></div>
                </div>
            </div>
            <div class="form-grid">
                <div class="field">
                    <label>辅助职阶技能</label>
                    <select id="skill_sub" onchange="updateSkillDesc()"></select>
                    <div id="sd_sub" class="desc-box skill-desc"></div>
                </div>
                <div class="field" id="spec_field" style="display:none;">
                    <label style="color: #e6b873;">✨ 特化解锁 (同职阶)</label>
                    <select id="skill_spec" onchange="updateSkillDesc()"></select>
                    <div id="sd_spec" class="desc-box skill-desc"></div>
                </div>
            </div>
        </div>
    </div>

    <!-- 记忆与锚点 -->
    <div class="card-section">
        <div class="section-badge">⛓️ 记忆与锚点</div>
        <div class="inner-pad">
            <div class="form-grid">
                <div class="field">
                    <label>记忆碎片 A <button class="small-btn" onclick="rollMem('mem_1')">🎲 ROLL</button></label>
                    <select id="mem_1" onchange="updateMemDesc('mem_1', 'md_1')"></select>
                    <div id="md_1" class="desc-box"></div>
                </div>
                <div class="field">
                    <label>记忆碎片 B <button class="small-btn" onclick="rollMem('mem_2')">🎲 ROLL</button></label>
                    <select id="mem_2" onchange="updateMemDesc('mem_2', 'md_2')"></select>
                    <div id="md_2" class="desc-box"></div>
                </div>
                <div class="field">
                    <label>宝物部件 <button class="small-btn" onclick="rollTrea()">🎲 ROLL</button></label>
                    <select id="treasure" onchange="updateTreaDesc()"></select>
                    <div id="td_1" class="desc-box"></div>
                </div>
            </div>
        </div>
    </div>

    <div style="display: flex; justify-content: center; margin: 1rem 0 0.5rem;">
        <button class="rite-button" onclick="generateSyncCommand()">🜂 苏醒指令生成 🜁</button>
    </div>

    <div id="output-area" style="display: none;" class="output-panel">
        <div class="output-label">✧ 刻印已铸 · 复制并传输 ✧</div>
        <textarea id="output-text" readonly rows="8" onclick="this.select(); navigator.clipboard.writeText(this.value); alert('✓ 指令已复制至剪贴板，等待苏醒仪式。');"></textarea>
    </div>
</div>

<script>
    // —————————— 原数据完整保留 ——————————
    const library = {
        pos: {
            "爱丽丝": { d: "维持人类心态，抗拒精神侵蚀的精神防线。", s: {
                "少女": "时机:即时/消费:0/射程:0。对一位姐妹进行对话判定。",
                "治愈": "时机:常时。其他的姐妹对你的对话判定修正值＋1。",
                "坚定之心": "时机:常时。自身的对话判定修正值＋1。",
                "公主": "时机:伤害/消费:0/射程:0～1。自身受损时，目标的下一行动消费-1。",
                "乐园的天使": "时机:即时/消费:2。不论位置如何，配置变更为“乐园”。"
            }},
            "狂人": { d: "顺从欲望，以暴走状态对抗绝望的狂战士。", s: {
                "疯狂加速": "时机:常时。拥有发狂依恋时，攻击判定修正值＋1。",
                "冲动": "时机:常时。每轮1次，可不支付正常消费而改为任选依恋增加1点狂气。",
                "修罗": "时机:裁定/消费:1狂气。支援3。",
                "业怒": "时机:伤害/消费:1狂气。自身造成伤害时，伤害＋2。",
                "奈落的引力": "时机:常时。向“奈落”移动的移动动作消费－1。"
            }},
            "自动人偶": { d: "抹杀自我，作为战斗的齿轮隔绝痛苦的冷酷人偶。", s: {
                "援护": "时机:常时/消费:1行动。令射程内其他姐妹宣言动作的消费变为0。",
                "乱来": "时机:常时/消费:破坏1部件。重骰行动/攻击/切断判定。",
                "冰心": "时机:常时。狂气判定的修正值＋1。",
                "人偶的自觉": "时机:常时。第1轮结束前，你可以无视“发狂状态”。",
                "炼狱之牢": "时机:常时。每轮结束时若身处“炼狱”，行动值恢复至最大值。"
            }},
            "废品": { d: "满心疮痍却死守底线的不屈幸存者。", s: {
                "随行": "时机:即时/消费:0。其他姐妹移动时，你可以移动1。",
                "半坏": "时机:常时。每轮结束与“宝物”损坏时，不会增加狂气点。",
                "地狱住人": "时机:常时。身处“地狱”时，攻击判定修正值＋1。",
                "挣扎": "时机:常时。使用狂气点重骰判定时，修正值＋1。",
                "抗拒奈落": "时机:常时。身处“奈落”时，所有行动动作消费－1。"
            }},
            "参谋": { d: "依靠思考与知识获取力量，排除感情干扰的冷静智囊。", s: {
                "建言": "时机:裁定/消费:0/射程:0～2。支援1或妨碍1。",
                "冷静": "时机:常时。行动判定的修正值＋1。",
                "看破": "时机:即时/消费:0/射程:0～3。选择目标的1个特殊时机行动将其无效化。",
                "作战": "时机:常时。战斗开始时可查看敌方配置，并配置我方一员到非奈落区。",
                "预知": "时机:行动/消费:1/射程:0～1。目标的下一个“行动”动作消费－1。"
            }},
            "队长": { d: "背负责任，统合姐妹心灵并引导队伍的领导者。", s: {
                "号令": "时机:即时/消费:2。全场姐妹可选择1个攻击动作以“即时”发动。",
                "克己": "时机:常时。发狂状态下，狂气/对话判定修正值＋1。",
                "花园的召集": "时机:即时/消费:2。全场姐妹不论位置配置变更为“花园”。",
                "悄悄话": "时机:常时。战斗开始和结束时，任选姐妹相互进行对话判定。",
                "优雅": "时机:常时。自身用狂气重骰时，任选姐妹进行对你的对话判定。"
            }}
        },
        cls: {
            "可爱少女": { d: "追求肉体顽强的不死性，作为盾牌保护同伴。", s: {
                "若无其事": "时机:常时。即便部件损伤，直到该轮结束仍能使用部件动作。",
                "死之延续": "时机:即时/消费:0。修复1个损伤的基本部件。",
                "庇护": "时机:伤害/消费:0/射程:0～1。代替目标承受伤害（非全体攻击）。",
                "肉盾": "时机:伤害/消费:0/射程:0～1。将目标受到的附加效果（切断等）无效化。",
                "失败品": "时机:常时。攻击/切断判定+1，但每轮结束必须破坏1个部件。"
            }, t: { "肉片蠕动": "时机:裁定/消费:0/射程:0～2。受损后且拥有损坏部件时使用。妨碍3。" }},
            "送断死镰": { d: "追求极致白刃战能力的近战专家。", s: {
                "死神": "时机:常时。白刃攻击动作的攻击判定修正值＋1。",
                "灾祸": "时机:伤害/消费:2。自身白刃攻击造成伤害时使用。附加“全体攻击”。",
                "杀剧": "时机:常时。在同一刻内和姐妹攻击同目标时，判定+1/伤害+1。",
                "刹那": "时机:常时。自身宣言攻击时，其他单位不可使用即时/裁定动作。",
                "必中": "时机:常时。攻击判定值为“6”时，可以任选命中部位。"
            }, t: { "无限解体": "时机:伤害/消费:0。造成伤害后只要行动值>0，可使用所有可用攻击。" }},
            "掠食异端": { d: "吞食死人的异端，具备强悍再生能力并能唤起敌人的恐惧。", s: {
                "肉宴": "时机:行动/消费:1。修复1个损坏的基本部件。",
                "捕食者": "时机:伤害/消费:2。使自身所处区域内所有的敌人“摔倒”。",
                "垂涎欲噬": "时机:即时/消费:0/射程:0～1。移动妨碍1。",
                "恶食": "时机:常时。自身的攻击令目标进行切断判定时，判定修正值－2。",
                "背德的悦乐": "时机:伤害/消费:0。令1个已使用的特殊时机动作恢复可用。"
            }, t: { "暴食": "时机:即时/消费:0。修复1个损坏的强化部件。" }},
            "镇魂枪手": { d: "远程攻击能力突出的枪使，作为游击兵破坏远处的敌人。", s: {
                "枪神": "时机:常时。射击攻击动作的攻击判定修正值＋1。",
                "死之手": "时机:即时/消费:0。任选1个攻击动作将时机作为“即时”使用。",
                "摇篮曲": "时机:常时。射击攻击动作修正值－1、消费－1（最低为1）。",
                "枪斗术": "时机:裁定/消费:2/射程:0～1。妨碍2，然后进行射击攻击1。",
                "集中": "时机:即时/消费:2。直到本轮结束，你的攻击判定修正值＋1。"
            }, t: { "魔弹": "时机:常时。射击攻击动作的最大射程可以＋1。" }},
            "纷繁异怪": { d: "具备超乎常理肉体的变异嵌合体，依靠异形器官完成特化动作。", s: {
                "狂鬼": "时机:常时。肉搏攻击动作的攻击判定修正值＋1。",
                "怪力": "时机:常时。肉搏/白刃攻击的伤害＋1。",
                "歪极": "习得时额外取得1个3级变异部件。",
                "业躯": "时机:常时。战斗结束时，可以修复2个损坏部件。",
                "再生": "时机:伤害/消费:1。防御1。每轮可无限使用。"
            }, t: { "异形存在": "时机:常时。受击时只要敌方未大成功，由你任选命中部位。" }},
            "热情舞女": { d: "以精妙动作与高速机动迷惑敌人，持续优雅舞蹈直至朽坏。", s: {
                "圆舞曲": "时机:即时/消费:1。本轮内以你为目标的攻击判定修正值－1。",
                "死亡舞蹈": "时机:裁定/消费:0。重骰攻击判定。",
                "调律": "时机:即时/消费:0。选择目标的1个损坏部件，本轮内可正常使用。",
                "爱抚": "时机:即时/消费:0。目标摔倒。",
                "机械装置": "习得时额外取得1个3级改造部件。"
            }, t: { "女武神": "时机:常时。最大行动值＋2。" }}
        },
        mem: {
            "01 蓝天": "记得过去清澈广阔的蓝色天空", "02 母亲的手": "残留着被母亲温暖双手拥抱的触感", "03 甜蜜的唇": "记得柔软嘴唇相触的感觉", "04 密室": "躲在密室中被未知存在逐渐逼近的恐惧记忆", "05 血宴": "独自坐在散落人体碎块的血池中的记忆",
            "06 雨中": "站在倾盆大雨中被淋湿的怀念感", "07 孤立": "被周围所有人远远嘲笑与排挤的记忆", "08 笑容": "脑海中浮现出某个重要之人发自内心的幸福笑容", "09 信": "收到一封与现状紧密相关但忘记内容的信件", "10 复盖之影": "被巨大黑影残酷对待并产生强烈憎恨的记忆",
            "11 花园": "在盛开的花海中唱歌散步的幸福时光", "12 父亲的臂": "被父亲强壮手臂拥抱的温暖触感", "13 恋爱之花": "苦涩又甜蜜的恋爱心动感", "14 诅咒": "怀着强烈憎恨对某人进行诅咒仪式的记忆", "15 歌": "心中残留着一首会不自觉哼唱的歌曲",
            "16 蛋糕": "品尝细腻奶油与水果蛋糕的甜美记忆", "17 火焰": "被熊熊烈火包围时产生的异样陶醉与恐怖", "18 割伤": "做家务时手指被割伤流血的微小痛楚", "19 白色房间": "躺在白色病房接受手术与药物注射的记忆", "20 黑色宅邸": "违背禁忌进入恐怖废墟宅邸的记忆",
            "21 锁": "被囚禁在铁栅栏与锁链中忍受苦痛的记忆", "22 星空": "眺望夜空中美丽星月的光芒", "23 少女": "身边陪伴着一位拥有治愈笑容的少女", "24 宝物": "拥有某件命中注定、无可替代的重要宝物", "25 葬礼": "参加某位重要之人葬礼时的悲伤情景",
            "26 聚会": "与家人朋友欢聚一堂的幸福时光", "27 生命": "体内孕育新生命时作为母亲的感动", "28 宠物犬": "记得宠物犬的叫声、触感与家人的羁绊", "29 翅膀": "从高处俯视并相信自己能够飞翔的记忆", "30 日常": "无聊但温暖、恒久不变的和平日常",
            "31 废弃": "遭到毫无理由的虐待并被破坏舍弃的记忆", "32 谢罪": "伤害了重要之人却未能说出抱歉的懊悔", "33 财欲": "不择手段收集金钱的强烈欲望", "34 死去": "亲眼目睹极其重要之人生命终结的瞬间", "35 故乡": "无法忘却的故乡风景与成长之地",
            "36 心愿": "拥有一个未能实现且回想时会心痛的愿望", "37 水": "沉浸在清澈水体中感到的宁静与幸福", "38 编织物": "为某人编织毛线物品的手部记忆", "39 感谢": "对某人怀有强烈感激却未能道谢的记忆", "40 土壤的味道": "照料花草时闻到的泥土与生命气息",
            "41 神灵": "虔诚向神明祈祷以求幸福的记忆", "42 教师": "坐在教室里与同学们一同学习玩闹的时光", "43 被窝": "沐浴着朝阳在温暖被窝中睡回笼觉的幸福感", "44 梳妆台": "对着镜子精心打扮、涂抹口红的记忆", "45 手术台": "被捆绑在手术台上看着手术刀逼近的恐惧",
            "46 跟踪者": "被未知存在紧紧尾随的悚然感", "47 嫉妒": "对周围人的幸福与笑容产生极度嫉妒", "48 家里蹲": "恐惧外界伤害而躲在小房间里的记忆", "49 洗浴": "享受温暖热水与肥皂香气的洗澡时光", "50 枪声": "听到爆破声后胸口发热倒下的记忆",
            "51 图书馆": "沉浸在寂静书海中阅读学习的记忆", "52 假面": "说了谎且无法信任任何人的防备心", "53 孤独": "极度寂寞并渴望得到朋友的孤独感", "54 演奏": "每天使用某种乐器演奏未知名乐曲的记忆", "55 雪": "看着纯白雪花从天而降覆盖一切的风景",
            "56 运动": "尽情活动身体带来的纯粹快乐", "57 双子": "拥有一个面容相同、心灵相通的双胞胎", "58 笼中鸟": "可怜并放飞笼中小鸟的记忆", "59 玩偶": "看到手脚断裂的玩偶并感到可怜的记忆", "60 窗外": "憧憬并眺望寒冷却美丽窗外景色的记忆",
            "61 占卜": "听到关于幸福未来占卜结果的话语", "62 牵手": "与某人牵手时传来的踏实安心感", "63 饥饿": "无法满足食欲引发的极度饥饿与撕咬冲动", "64 凌辱": "遭受无尽屈辱与自尊践踏的记忆", "65 可爱衣服": "想要将可爱的衣服穿给某人看的雀跃感",
            "66 料理": "在厨房切菜烹饪的动作记忆", "67 欺负": "与朋友一起残忍欺凌弱小者的愉悦感", "68 绘画": "留有一幅必须完成却想不起内容的画作", "69 官能": "沉浸在情欲与快乐渴求中的烧灼感", "70 亡者": "被死者追赶并被活活撕碎的惨痛记忆",
            "71 迷糊": "听着鸟鸣在朝阳中半梦半醒的慵懒感", "72 对话": "与朋友漫无边际闲聊的快乐时光", "73 行走的尸体": "哀悼死者时被其化作尸鬼袭击的记忆", "74 游戏": "不分昼夜沉迷于游戏画面的记忆", "75 售出": "出卖身体某部分换取金钱并看到买家笑容的记忆",
            "76 努力": "拼命学习以证明自身价值的强迫观念", "77 幸福时刻": "如梦似幻、令人害怕失去的纯粹幸福时光", "78 埋葬": "被冰冷泥土逐渐覆盖全身活埋的记忆", "79 购物": "看着橱窗快乐购物的记忆", "80 游乐园": "与亲密之人游玩五彩缤纷游乐园的记忆",
            "81 茶会": "在美丽庭院中享用红茶与曲奇的少女时光", "82 秘密": "藏有绝对不能被知道的可怕/羞耻秘密", "83 花圃": "长时间耐心照料花朵直至结出果实的记忆", "84 灵异": "遭遇不明黑影或灵异现象的恐怖体验", "85 秘密地点": "躲在阁楼或壁橱等狭小空间里的安心感",
            "86 离别": "与绝对不能忘记的重要之人永别的记忆", "87 故事": "写下某篇未知小说或诗歌的记忆", "88 哥哥": "憧憬并向温柔哥哥撒娇的记忆", "89 迷失": "在黑暗陌生之地迷路哭泣徘徊的记忆", "90 海岸": "眺望拍岸波浪与白色沙滩的生命之海",
            "91 战火": "在枪林弹雨与爆炸中逃亡丧失认知的记忆", "92 操弄死者": "坚信死去的重要之人会再次醒来的记忆", "93 药": "身体崩溃前疯狂渴求药物的记忆", "94 虫": "对爬行或飞行昆虫极度厌恶与憎恨的记忆", "95 死亡降临": "重要之人死后心中空洞的悲伤感",
            "96 谎言": "用谎言欺骗某人致其死亡的罪恶感", "97 死后世界": "死后看到另一个世界却被强行拉回的记忆", "98 杀戮天使": "被教导通过不断杀人来获得表扬的记忆", "99 死灵师": "对将自己变成人偶的造物主残留的模糊印象", "00 最终战争": "作为旁观者见证人类文明终结与惨剧的记忆"
        },
        trea: {
            "01 照片": "人类尚存时拍摄的照片", "02 书": "古老破旧且仅剩无意义文字的书", "03 小小的不死者": "猫、乌鸦或老鼠形态的小型不死者", "04 坏掉的部件": "某人或过去自己的废弃身体部件", "05 小镜子": "长期珍惜使用的小镜子",
            "06 玩偶": "存在破损的玩偶", "07 布娃娃": "经历长久战争磨损的布娃娃", "08 饰品": "戒指、项链或具有特殊价值的护身符", "09 篮子": "用于装载荒野中发现的零碎物品的篮子", "10 可爱服饰": "具有特定款式与意义的服饰"
        }
    };

    function populate(id, list) {
        const e = document.getElementById(id);
        e.innerHTML = "";
        list.forEach(i => {
            const o = document.createElement("option");
            o.value = o.text = i;
            e.add(o);
        });
    }

    function updateUI() {
        const p = document.getElementById('position').value;
        const m = document.getElementById('main_class').value;
        const s = document.getElementById('sub_class').value;
        document.getElementById('desc_pos').innerText = library.pos[p].d;
        document.getElementById('desc_main').innerText = library.cls[m].d;
        document.getElementById('desc_sub').innerText = library.cls[s].d;
        populate('skill_pos', Object.keys(library.pos[p].s));
        populate('skill_main_1', Object.keys(library.cls[m].s));
        populate('skill_main_2', Object.keys(library.cls[m].s));
        document.getElementById('skill_main_2').selectedIndex = Math.min(1, Object.keys(library.cls[m].s).length-1);
        populate('skill_sub', Object.keys(library.cls[s].s));
        const sf = document.getElementById('spec_field');
        if (m === s) {
            sf.style.display = "block";
            populate('skill_spec', [Object.keys(library.cls[m].t)[0]]);
        } else sf.style.display = "none";
        updateSkillDesc();
    }

    function updateSkillDesc() {
        const p = document.getElementById('position').value;
        const m = document.getElementById('main_class').value;
        const s = document.getElementById('sub_class').value;
        document.getElementById('sd_pos').innerText = library.pos[p].s[document.getElementById('skill_pos').value] || "";
        document.getElementById('sd_m1').innerText = library.cls[m].s[document.getElementById('skill_main_1').value] || "";
        document.getElementById('sd_m2').innerText = library.cls[m].s[document.getElementById('skill_main_2').value] || "";
        document.getElementById('sd_sub').innerText = library.cls[s].s[document.getElementById('skill_sub').value] || "";
        if (m === s) document.getElementById('sd_spec').innerText = library.cls[m].t[document.getElementById('skill_spec').value] || "";
    }

    function updateMemDesc(selId, descId) {
        document.getElementById(descId).innerText = library.mem[document.getElementById(selId).value];
    }
    function updateTreaDesc() {
        document.getElementById('td_1').innerText = library.trea[document.getElementById('treasure').value];
    }
    function rollMem(id) {
        const keys = Object.keys(library.mem);
        document.getElementById(id).value = keys[Math.floor(Math.random() * keys.length)];
        updateMemDesc(id, id === 'mem_1' ? 'md_1' : 'md_2');
    }
    function rollTrea() {
        const keys = Object.keys(library.trea);
        document.getElementById('treasure').value = keys[Math.floor(Math.random() * keys.length)];
        updateTreaDesc();
    }

    function generateSyncCommand() {
        const m = document.getElementById('main_class').value;
        const s = document.getElementById('sub_class').value;
        const t = document.getElementById('treasure').value;
        const p = document.getElementById('position').value;
        const patches = [
            { "op": "replace", "path": "/⚙️素体档案/识别名", "value": document.getElementById('name').value || "未定" },
            { "op": "replace", "path": "/⚙️素体档案/肉体享年", "value": parseInt(document.getElementById('age_body').value) },
            { "op": "replace", "path": "/⚙️素体档案/精神年龄", "value": parseInt(document.getElementById('age_mind').value) },
            { "op": "replace", "path": "/⚙️素体档案/职位", "value": p },
            { "op": "replace", "path": "/⚙️素体档案/主要职阶", "value": m },
            { "op": "replace", "path": "/⚙️素体档案/辅助职阶", "value": s },
            { "op": "replace", "path": "/🧠心智模块/技能/职位专属", "value": document.getElementById('skill_pos').value },
            { "op": "replace", "path": "/🧠心智模块/技能/主要职阶1", "value": document.getElementById('skill_main_1').value },
            { "op": "replace", "path": "/🧠心智模块/技能/主要职阶2", "value": document.getElementById('skill_main_2').value },
            { "op": "replace", "path": "/🧠心智模块/技能/辅助职阶", "value": document.getElementById('skill_sub').value },
            { "op": "replace", "path": "/🧠心智模块/技能/特化", "value": (m === s) ? document.getElementById('skill_spec').value : "无" },
            { "op": "replace", "path": "/🧠心智模块/记忆碎片/其一", "value": document.getElementById('mem_1').value },
            { "op": "replace", "path": "/🧠心智模块/记忆碎片/其二", "value": document.getElementById('mem_2').value },
            { "op": "replace", "path": "/⛓️依恋与狂气/宝物依存/物品", "value": t },
            { "op": "replace", "path": "/💎遗物/宝物部件", "value": t }
        ];
        const command = `<UpdateVariable>\n<Analysis>\n- 是否允许剧变式更新：是（初始化变量设置）。\n- 素体档案：${p} / ${m} / ${s}\n- 核心技能已配置，记忆锚点已同步。\n</Analysis>\n<JSONPatch>\n${JSON.stringify(patches, null, 2)}\n</JSONPatch>\n</UpdateVariable>`;
        const outArea = document.getElementById('output-area');
        const outText = document.getElementById('output-text');
        outText.value = command;
        outArea.style.display = 'block';
        outArea.scrollIntoView({ behavior: 'smooth', block: 'nearest' });
    }

    window.onload = function() {
        populate('position', Object.keys(library.pos));
        populate('main_class', Object.keys(library.cls));
        populate('sub_class', Object.keys(library.cls));
        populate('mem_1', Object.keys(library.mem));
        populate('mem_2', Object.keys(library.mem));
        populate('treasure', Object.keys(library.trea));
        updateUI();
        // 默认显示几条描述
        updateMemDesc('mem_1', 'md_1');
        updateMemDesc('mem_2', 'md_2');
        updateTreaDesc();
    };
</script>
</body>
</html>
