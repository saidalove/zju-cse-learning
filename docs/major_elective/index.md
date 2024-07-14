# 专业选修课

<div class="select-container" markdown="1">
  <label for="specialization-select">选择专业：</label>
  <select id="specialization-select" onchange="showTable(this.value)">
    <option value="automation" selected>自动化</option>
    <option value="robotics">机器人</option>
  </select>
</div>

<div id="automation-table" class="course-table" style="display: table" markdown="1">
  |课程名称|学分|建议学年学期|资料情况|
  |:--|:--|:--|:--:|
  |<span style="font-weight: bold;">★公共基础类</span>| | | |
  |[数据结构与算法分析](./example.md)|2.0|二（秋）|暂无|
  |[面向对象的编程技术（JAVA）](./example.md)|2.0|二（冬）|暂无|
  |[面向对象的编程技术（C++）](./example.md)|2.0|二（冬）|暂无|
  |[数值计算方法](./example.md)|2.0|二（春）|暂无|
  |[计算机网络原理](./example.md)|2.5|二（春）|暂无|
  |[运筹学](./example.md)|2.0|二（夏）|暂无|
  |<span style="font-weight: bold;">★先进控制与智能自动化类</span>| | | |
  |[控制与决策系统仿真](./example.md)|2.0|二（夏）|暂无|
  |[电气控制技术](./example.md)|2.5|三（秋）|暂无|
  |[智能控制技术](./example.md)|1.5|三（冬）|暂无|
  |[智能供配电技术](./example.md)|2.0|三（春）|暂无|
  |[智能制造与企业自动化](./example.md)|2.0|三（夏）|暂无|
  |[先进控制基础 ](./example.md)|1.5|四（秋）|暂无|
  |<span style="font-weight: bold;">★机器人与智能系统</span>| | | |
  |[机器人导论](./example.md)|2.0|二（春）|暂无|
  |[DSP系统设计](./example.md)|2.0|三（秋）|暂无|
  |[智能电子设备开发](./example.md)|1.5|三（秋）|暂无|
  |[FPGA系统原理与应用](./example.md)|2.5|三（冬）|暂无|
  |[空中机器人](./example.md)|2.0|三（春）|暂无|
  |[智能移动技术](./example.md)|2.0|三（春）|暂无|
  |[数字图像处理与机器视觉](./example.md)|3.0|三（春夏）|暂无|
  |[智能仪器设计与开发](./example.md)|2.0|三（夏）|暂无|
  |<span style="font-weight: bold;">★人工智能与大数据</span>| | | |
  |[信息物理系统安全](./example.md)|2.5|二（夏）|暂无|
  |[大数据解析与应用导论](./example.md)|2.0|三（秋）|暂无|
  |[数据驱动建模与应用](./example.md)|2.0|三（冬）|暂无|
  |[信息安全导论](./example.md)|2.0|三（冬）|暂无|
  |[智联网平台技术](./example.md)|2.0|三（春）|暂无|
  |[物联网安全](./example.md)|3.0|三（夏）|暂无|
  |[深度学习 ](./example.md)|1.5|三（夏）|暂无|
</div>

<div id="robotics-table" class="course-table" style="display: none" markdown="1">
  | 课程名称 | 学分 | 建议学年学期 | 资料情况 |
  |:--|:--:|:--:|:--|
  |<span style="font-weight: bold;">★公共基础类</span>| | | |
  | 数据结构 | 2.0 | 二(秋) | 暂无 |
  | 数值计算方法 | 2.0 | 二(春) | 暂无 |
  | 信号与系统 | 2.0 | 二(春) | 暂无 |
  | 面向对象程序设计 | 2.5 | 二(春夏) | 暂无 |
  | 运筹学 | 2.0 | 二(夏) | 暂无 |
  | 大数据解析与应用导论 | 2.0 | 三(秋) | 暂无 |
  |<span style="font-weight: bold;">★自动化控制类</span>| | | |
  | 电气控制技术 | 2.5 | 三(秋) | 暂无 |
  | 运动控制 | 3.5 | 三(秋冬) | 暂无 |
  | 智能控制技术 | 1.5 | 三(冬) | 暂无 |
  | 最优化与最优控制 | 3.0 | 三(春夏) | 暂无 |
  |<span style="font-weight: bold;">★先进机器人类</span>| | | |
  | ROS与机器人仿真软件 | 1.0 | 一(短) | 暂无 |
  | 机器视觉 | 2.5 | 三(秋) | 暂无 |
  | 机器人智能感知与分析 | 2.0 | 三(冬) | 暂无 |
  | 空中机器人 | 2.0 | 三(春) | 暂无 |
  | 软体仿生机器人与智能材料 | 1.0 | 三(夏) | 暂无 |
  | 机器人前沿 | 1.0 | 三(夏) | 暂无 |
  | 机器人集成控制系统 | 2.0 | 三(夏) | 暂无 |
  | 网络化智能无人系统 | 3.0 | 四(秋冬) | 暂无 |
  |<span style="font-weight: bold;">★机械工程类</span>| | | |
  | 机械制图及CAD基础 | 1.5 | 一(春) | 暂无 |
  | 设计与制造II | 3.0 | 二(春夏) | 暂无 |


</div>


<script>
function showTable(specialization) {
    document.getElementById('automation-table').style.display = specialization === 'automation' ? 'table' : 'none';
    document.getElementById('robotics-table').style.display = specialization === 'robotics' ? 'table' : 'none';
}
</script>

<style>
.md-typeset table:not([class]) th {
    min-width: 1em;
}
.course-table {
    margin: 0 auto;
    text-align: center;
}


.select-container {
    text-align: center;
    margin-bottom: 20px;
}

.select-container select {
    font-size: inherit;
    font-family: inherit;
    padding: 6px 8px;
    border-radius: 4px;
    border: 1px solid #ccc;
}

.course-table th {
    font-weight: bold;
    color: #b22222;
}

.course-table a {
    color: inherit;
}

</style>