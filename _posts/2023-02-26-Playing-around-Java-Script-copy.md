---
keywords: fastai
description: Code stuff.
title: Playing around with Java Script
toc: true
badges: true
comments: true
categories: [jupyter]
image: images/chart-preview.png
nb_path: _notebooks/2022-10-1-Playing-around-Java-Script copy.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-10-1-Playing-around-Java-Script copy.ipynb
-->

<div class="container" id="notebook-container">
        
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-javascript"><pre><span></span><span class="nb">Math</span><span class="p">.</span><span class="nx">round</span><span class="p">(</span><span class="mf">93.5</span><span class="p">);</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">



<div class="output_text output_subarea output_execute_result">
<pre>94</pre>
</div>

</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-javascript"><pre><span></span><span class="kr">const</span> <span class="nx">removeDuplicates</span> <span class="o">=</span> <span class="p">(</span><span class="nx">arr</span><span class="p">)</span> <span class="p">=&gt;</span> <span class="p">[...</span><span class="k">new</span> <span class="nx">Set</span><span class="p">(</span><span class="nx">arr</span><span class="p">)]</span>

<span class="nx">removeDuplicates</span><span class="p">([</span><span class="mf">31</span><span class="p">,</span> <span class="mf">56</span><span class="p">,</span> <span class="mf">12</span><span class="p">,</span> <span class="mf">31</span><span class="p">,</span> <span class="mf">45</span><span class="p">,</span> <span class="mf">12</span><span class="p">,</span> <span class="mf">31</span><span class="p">])</span>
<span class="c1">//[ 31, 56, 12, 45 ]</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">



<div class="output_text output_subarea output_execute_result">
<pre>[ 31, 56, 12, 45 ]</pre>
</div>

</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-javascript"><pre><span></span><span class="kr">const</span> <span class="nx">dayDif</span> <span class="o">=</span> <span class="p">(</span><span class="nx">date1</span><span class="p">,</span> <span class="nx">date2</span><span class="p">)</span> <span class="p">=&gt;</span> <span class="nb">Math</span><span class="p">.</span><span class="nx">ceil</span><span class="p">(</span><span class="nb">Math</span><span class="p">.</span><span class="nx">abs</span><span class="p">(</span><span class="nx">date1</span><span class="p">.</span><span class="nx">getTime</span><span class="p">()</span> <span class="o">-</span> <span class="nx">date2</span><span class="p">.</span><span class="nx">getTime</span><span class="p">())</span> <span class="o">/</span> <span class="mf">86400000</span><span class="p">)</span>

<span class="nx">dayDif</span><span class="p">(</span><span class="k">new</span> <span class="nb">Date</span><span class="p">(</span><span class="s2">&quot;2022-09-30&quot;</span><span class="p">),</span> <span class="k">new</span> <span class="nb">Date</span><span class="p">(</span><span class="s2">&quot;2022-10-13&quot;</span><span class="p">))</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">



<div class="output_text output_subarea output_execute_result">
<pre>13</pre>
</div>

</div>

</div>
</div>

</div>
    {% endraw %}

</div>
 
