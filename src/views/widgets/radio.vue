<template>
    <div class="radio-box" v-cloak>
        <h1>Radio Button</h1>
        <p><span class="point-text"> input </span>标签与<span class="point-text"> label </span>标签一起使用。在<span class="point-text"> label </span>标签上设置<span class="point-text"> class="radio" </span>, 即可实现单选按钮效果。</p>
        <p>如需将单选按钮设为不可用状态, 只需增设<span class="point-text"> .disable-radio </span>即可。</p>
        <h3>简单使用</h3>
        <p>为更好的使用, 最好在<span class="point-text"> i </span>标签设置<span class="point-text"> class="radio-icon" </span>, <span class="point-text"> span </span>标签设置<span class="point-text"> class="redio-text" </span>, 当然不设置也没有影响。</p>
        <p>代码示例:</p>
        <div class="code">
            <div class="examples">
                <span class="d">&lt;label</span> <span class="cn">class=</span><span class="cv">"radio"</span><span class="d">&gt;</span><br>
                &nbsp;&nbsp;&nbsp;&nbsp;<span class="d">&lt;input</span> <span class="cn">type=</span><span class="cv">"radio"</span> <span class="cn">name=</span><span class="cv">"type"</span><span class="d">&gt;</span><br>
                &nbsp;&nbsp;&nbsp;&nbsp;<span class="d">&lt;i&gt;</span><span class="d">&lt;/i&gt;</span><br>
                &nbsp;&nbsp;&nbsp;&nbsp;<span class="d">&lt;span&gt;</span><span class="v">SPCC/DC01</span><span class="d">&lt;/span&gt;</span><br>
                <span class="d">&lt;/label&gt;</span><br><br>

                <span class="d">&lt;label</span> <span class="cn">class=</span><span class="cv">"radio"</span><span class="d">&gt;</span><br>
                &nbsp;&nbsp;&nbsp;&nbsp;<span class="d">&lt;input</span> <span class="cn">type=</span><span class="cv">"radio"</span> <span class="cn">name=</span><span class="cv">"type"</span><span class="d">&gt;</span><br>
                &nbsp;&nbsp;&nbsp;&nbsp;<span class="d">&lt;i </span><span class="cn">class=</span><span class="cv">"radio-icon"</span><span class="v">&gt;</span></span><span class="d">&lt;/i&gt;</span><br>
                &nbsp;&nbsp;&nbsp;&nbsp;<span class="d">&lt;span </span><span class="cn">class=</span><span class="cv">"radio-text"</span><span class="v">&gt;</span><span class="v">SPCC/DC01</span><span class="d">&lt;/span&gt;</span><br>
                <span class="d">&lt;/label&gt;</span>
            </div>
        </div>
        <p>效果图:</p>
        <div class="examples">
            <div class="radio-widgets">
                <label class="radio">
                    <input type="radio" name="type">
                    <i class="radio-icon"></i>
                    <span class="radio-text">SPCC/DC01</span>
                </label>
                <label class="radio">
                    <input type="radio" name="type">
                    <i></i>
                    <span>SPCC/DC02</span>
                </label>
                <label class="radio disable-radio">
                    <input type="radio">
                    <i></i>
                    <span>SPCC/DC01</span>
                </label>
            </div>
        </div>
    </div>
</template>