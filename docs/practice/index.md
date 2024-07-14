# 实践教学

<div class="select-container" markdown="1">
  <label for="specialization-select">选择专业：</label>
  <select id="specialization-select" onchange="showTable(this.value)">
    <option value="automation" selected>自动化</option>
    <option value="robotics">机器人</option>
  </select>
</div>

<div id="automation-table" class="course-table" style="display: table" markdown="1">
  |课程名称|学分|建议学年学期|资料情况|
  |:--|:--:|:--:|:--|
  |<span style="font-weight: bold;">★必修课程</span>| | | |
  |[专业认知](./example.md)|0.5|一（短）|暂无|
  |[企业认知实习](./example.md)|0.5|一（短）|暂无|
  |<span style="font-weight: bold;">★选修课程</span>| | | |
  |[嵌入式系统高级实验](./example.md)|1.5|二（短）|暂无|
  |[自动化竞赛实训](./example.md)|1.5|二（短）|暂无|
  |[科研训练](./example.md)|1.5|三（短）|暂无|
  |[测控系统综合实践](./example.md)|1.5|三（短）|暂无|
  |[自动化综合创新实践](./example.md)|1.5|四（秋冬）|暂无|
  |[企业深度实习](./example.md)|3.0|四（秋冬）|暂无|
  |[电子工程训练（甲）](./example.md)|1.5|一（春夏）|暂无|
  |[实验技能训练](./example.md)|1.5|二（短）|暂无|
  |[机器人与智能系统综合实践](./example.md)|1.5|三（短）|暂无|
  |[人工智能与大数据综合实践](./example.md)|1.5|三（短）|暂无|
</div>

<div id="robotics-table" class="course-table" style="display: none" markdown="1">
  | 课程名称 | 学分 | 建议学年学期 | 资料情况 |
  |:--|:--:|:--:|:--|
  | 机器人基础实践 | 1.0 | 一(短) | 暂无 |
  | 专业认知 | 0.5 | 一(短) | 暂无 |
  | 工程训练 | 1.5 | 一(春夏) | 暂无 |
  | 嵌入式系统高级实验 | 1.5 | 二(短) | 暂无 |
  | 机器人学I强化训练与实践 | 2.0 | 三(秋) | 暂无 |
  | 机器人学II强化训练与实践 | 2.0 | 三(冬) | 暂无 |
  | 机器人竞赛实践 | 1.0 | 三(短) | 暂无 |
  | 机器人交叉创新设计与实践 | 4.0 | 三(春夏) | 暂无 |
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