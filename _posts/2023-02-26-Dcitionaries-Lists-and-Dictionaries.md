---
keywords: fastai
description: Code.
title: Python Lists and Dictionaries 
toc: true 
badges: true
comments: true
categories: [jupyter]
image: images/chart-preview.png
nb_path: _notebooks/2022-09-8-Dcitionaries Lists and Dictionaries.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-09-8-Dcitionaries Lists and Dictionaries.ipynb
-->

<div class="container" id="notebook-container">
        
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="s2">&quot;What is the variable name/key?&quot;</span><span class="p">,</span> <span class="s2">&quot;value?&quot;</span><span class="p">,</span> <span class="s2">&quot;type?&quot;</span><span class="p">,</span> <span class="s2">&quot;primitive or collection, why?&quot;</span><span class="p">)</span>
<span class="n">name</span> <span class="o">=</span> <span class="s2">&quot;Luke Riggins&quot;</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;name&quot;</span><span class="p">,</span> <span class="n">name</span><span class="p">,</span> <span class="nb">type</span><span class="p">(</span><span class="n">name</span><span class="p">))</span>

<span class="nb">print</span><span class="p">()</span>


<span class="c1"># variable of type integer</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;What is the variable name/key?&quot;</span><span class="p">,</span> <span class="s2">&quot;value?&quot;</span><span class="p">,</span> <span class="s2">&quot;type?&quot;</span><span class="p">,</span> <span class="s2">&quot;primitive or collection, why?&quot;</span><span class="p">)</span>
<span class="n">age</span> <span class="o">=</span> <span class="mi">17</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;age&quot;</span><span class="p">,</span> <span class="n">age</span><span class="p">,</span> <span class="nb">type</span><span class="p">(</span><span class="n">age</span><span class="p">))</span>

<span class="nb">print</span><span class="p">()</span>

<span class="c1"># variable of type float</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;What is the variable name/key?&quot;</span><span class="p">,</span> <span class="s2">&quot;value?&quot;</span><span class="p">,</span> <span class="s2">&quot;type?&quot;</span><span class="p">,</span> <span class="s2">&quot;primitive or collection, why?&quot;</span><span class="p">)</span>
<span class="n">score</span> <span class="o">=</span> <span class="mf">90.0</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;score&quot;</span><span class="p">,</span> <span class="n">score</span><span class="p">,</span> <span class="nb">type</span><span class="p">(</span><span class="n">score</span><span class="p">))</span>

<span class="nb">print</span><span class="p">()</span>

<span class="c1"># variable of type list (many values in one variable)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;What is variable name/key?&quot;</span><span class="p">,</span> <span class="s2">&quot;value?&quot;</span><span class="p">,</span> <span class="s2">&quot;type?&quot;</span><span class="p">,</span> <span class="s2">&quot;primitive or collection?&quot;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;What is different about the list output?&quot;</span><span class="p">)</span>
<span class="n">langs</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Python&quot;</span><span class="p">,</span> <span class="s2">&quot;JavaScript&quot;</span><span class="p">,</span> <span class="s2">&quot;Java&quot;</span><span class="p">,</span> <span class="s2">&quot;Bash&quot;</span><span class="p">]</span> <span class="c1"># *I added bash as a language*</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;langs&quot;</span><span class="p">,</span> <span class="n">langs</span><span class="p">,</span> <span class="nb">type</span><span class="p">(</span><span class="n">langs</span><span class="p">),</span> <span class="s2">&quot;length&quot;</span><span class="p">,</span> <span class="nb">len</span><span class="p">(</span><span class="n">langs</span><span class="p">))</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;- langs[3]&quot;</span><span class="p">,</span> <span class="n">langs</span><span class="p">[</span><span class="mi">3</span><span class="p">],</span> <span class="nb">type</span><span class="p">(</span><span class="n">langs</span><span class="p">[</span><span class="mi">3</span><span class="p">]))</span> <span class="c1"># *I changed the index from 0 to 3 so that the print command will print Bash instead of Python*</span>

<span class="nb">print</span><span class="p">()</span>

<span class="c1"># variable of type dictionary (a group of keys and values)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;What is the variable name/key?&quot;</span><span class="p">,</span> <span class="s2">&quot;value?&quot;</span><span class="p">,</span> <span class="s2">&quot;type?&quot;</span><span class="p">,</span> <span class="s2">&quot;primitive or collection, why?&quot;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;What is different about the dictionary output?&quot;</span><span class="p">)</span>
<span class="n">person</span> <span class="o">=</span> <span class="p">{</span>
    <span class="s2">&quot;name&quot;</span><span class="p">:</span> <span class="n">name</span><span class="p">,</span>
    <span class="s2">&quot;age&quot;</span><span class="p">:</span> <span class="n">age</span><span class="p">,</span>
    <span class="s2">&quot;score&quot;</span><span class="p">:</span> <span class="n">score</span><span class="p">,</span>
    <span class="s2">&quot;langs&quot;</span><span class="p">:</span> <span class="n">langs</span>
<span class="p">}</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;person&quot;</span><span class="p">,</span> <span class="n">person</span><span class="p">,</span> <span class="nb">type</span><span class="p">(</span><span class="n">person</span><span class="p">),</span> <span class="s2">&quot;length&quot;</span><span class="p">,</span> <span class="nb">len</span><span class="p">(</span><span class="n">person</span><span class="p">))</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;- person[&quot;name&quot;]&#39;</span><span class="p">,</span> <span class="n">person</span><span class="p">[</span><span class="s2">&quot;name&quot;</span><span class="p">],</span> <span class="nb">type</span><span class="p">(</span><span class="n">person</span><span class="p">[</span><span class="s2">&quot;name&quot;</span><span class="p">]))</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>What is the variable name/key? value? type? primitive or collection, why?
name Luke Riggins &lt;class &#39;str&#39;&gt;

What is the variable name/key? value? type? primitive or collection, why?
age 17 &lt;class &#39;int&#39;&gt;

What is the variable name/key? value? type? primitive or collection, why?
score 90.0 &lt;class &#39;float&#39;&gt;

What is variable name/key? value? type? primitive or collection?
What is different about the list output?
langs [&#39;Python&#39;, &#39;JavaScript&#39;, &#39;Java&#39;, &#39;Bash&#39;] &lt;class &#39;list&#39;&gt; length 4
- langs[3] Bash &lt;class &#39;str&#39;&gt;

What is the variable name/key? value? type? primitive or collection, why?
What is different about the dictionary output?
person {&#39;name&#39;: &#39;Luke Riggins&#39;, &#39;age&#39;: 17, &#39;score&#39;: 90.0, &#39;langs&#39;: [&#39;Python&#39;, &#39;JavaScript&#39;, &#39;Java&#39;, &#39;Bash&#39;]} &lt;class &#39;dict&#39;&gt; length 4
- person[&#34;name&#34;] Luke Riggins &lt;class &#39;str&#39;&gt;
</pre>
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
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">InfoDb</span> <span class="o">=</span> <span class="p">[]</span>

<span class="c1"># InfoDB is a data structure with expected Keys and Values</span>

<span class="c1"># Append to List a Dictionary of key/values related to a person and cars</span>
<span class="n">InfoDb</span><span class="o">.</span><span class="n">append</span><span class="p">({</span>
    <span class="s2">&quot;FirstName&quot;</span><span class="p">:</span> <span class="s2">&quot;Ethan&quot;</span><span class="p">,</span>
    <span class="s2">&quot;LastName&quot;</span><span class="p">:</span> <span class="s2">&quot;Nyguen&quot;</span><span class="p">,</span>
    <span class="s2">&quot;DOB&quot;</span><span class="p">:</span> <span class="s2">&quot;October 3&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Residence&quot;</span><span class="p">:</span> <span class="s2">&quot;San Diego&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Email&quot;</span><span class="p">:</span> <span class="s2">&quot;EthanN45233@stu.powayusd.com&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Owns_Cars&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;2015-Fusion&quot;</span><span class="p">,</span> <span class="s2">&quot;2011-Ranger&quot;</span><span class="p">,</span> <span class="s2">&quot;2003-Excursion&quot;</span><span class="p">,</span> <span class="s2">&quot;1997-F350&quot;</span><span class="p">,</span> <span class="s2">&quot;1969-Cadillac&quot;</span><span class="p">]</span>
<span class="p">})</span>

<span class="c1"># Append to List a 2nd Dictionary of key/values</span>
<span class="n">InfoDb</span><span class="o">.</span><span class="n">append</span><span class="p">({</span>
    <span class="s2">&quot;FirstName&quot;</span><span class="p">:</span> <span class="s2">&quot;Luke&quot;</span><span class="p">,</span>
    <span class="s2">&quot;LastName&quot;</span><span class="p">:</span> <span class="s2">&quot;Riggins&quot;</span><span class="p">,</span>
    <span class="s2">&quot;DOB&quot;</span><span class="p">:</span> <span class="s2">&quot;December 2&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Residence&quot;</span><span class="p">:</span> <span class="s2">&quot;San Diego&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Email&quot;</span><span class="p">:</span> <span class="s2">&quot;luker56233@powayusd.com&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Owns_Cars&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;Volkswagon Passat&quot;</span><span class="p">]</span>
<span class="p">})</span>

<span class="c1"># PUTTING MY INFORMATION (HACK!)</span>
<span class="n">InfoDb</span><span class="o">.</span><span class="n">append</span><span class="p">({</span>
    <span class="s2">&quot;FirstName&quot;</span><span class="p">:</span> <span class="s2">&quot;Luke&quot;</span><span class="p">,</span>
    <span class="s2">&quot;LastName&quot;</span><span class="p">:</span> <span class="s2">&quot;Riggins&quot;</span><span class="p">,</span>
    <span class="s2">&quot;DOB&quot;</span><span class="p">:</span> <span class="s2">&quot;December 2&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Residence&quot;</span><span class="p">:</span> <span class="s2">&quot;Rancho Bernardo&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Email&quot;</span><span class="p">:</span> <span class="s2">&quot;luke120204@gmail.com&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Owns_Cars&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;Toyota&quot;</span><span class="p">]</span>
<span class="p">})</span>

<span class="c1"># PUTTING MY PARTER&#39;S INFORMATION (HACK!)</span>
<span class="n">InfoDb</span><span class="o">.</span><span class="n">append</span><span class="p">({</span>
    <span class="s2">&quot;FirstName&quot;</span><span class="p">:</span> <span class="s2">&quot;Jeffery&quot;</span><span class="p">,</span>
    <span class="s2">&quot;LastName&quot;</span><span class="p">:</span> <span class="s2">&quot;Lee&quot;</span><span class="p">,</span>
    <span class="s2">&quot;DOB&quot;</span><span class="p">:</span> <span class="s2">&quot;December 27&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Residence&quot;</span><span class="p">:</span> <span class="s2">&quot;4S Ranch&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Email&quot;</span><span class="p">:</span> <span class="s2">&quot;jefferyl56783@stu.powayusd.com&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Owns_Cars&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;Honda Accord&quot;</span><span class="p">]</span>
<span class="p">})</span>

<span class="c1"># Print the data structure</span>
<span class="nb">print</span><span class="p">(</span><span class="n">InfoDb</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>[{&#39;FirstName&#39;: &#39;Ethan&#39;, &#39;LastName&#39;: &#39;Nyguen&#39;, &#39;DOB&#39;: &#39;October 3&#39;, &#39;Residence&#39;: &#39;San Diego&#39;, &#39;Email&#39;: &#39;EthanN45233@stu.powayusd.com&#39;, &#39;Owns_Cars&#39;: [&#39;2015-Fusion&#39;, &#39;2011-Ranger&#39;, &#39;2003-Excursion&#39;, &#39;1997-F350&#39;, &#39;1969-Cadillac&#39;]}, {&#39;FirstName&#39;: &#39;Luke&#39;, &#39;LastName&#39;: &#39;Riggins&#39;, &#39;DOB&#39;: &#39;December 2&#39;, &#39;Residence&#39;: &#39;San Diego&#39;, &#39;Email&#39;: &#39;luker56233@powayusd.com&#39;, &#39;Owns_Cars&#39;: [&#39;Volkswagon Passat&#39;]}, {&#39;FirstName&#39;: &#39;Luke&#39;, &#39;LastName&#39;: &#39;Riggins&#39;, &#39;DOB&#39;: &#39;December 2&#39;, &#39;Residence&#39;: &#39;Rancho Bernardo&#39;, &#39;Email&#39;: &#39;luke120204@gmail.com&#39;, &#39;Owns_Cars&#39;: [&#39;Toyota&#39;]}, {&#39;FirstName&#39;: &#39;Jeffery&#39;, &#39;LastName&#39;: &#39;Lee&#39;, &#39;DOB&#39;: &#39;December 27&#39;, &#39;Residence&#39;: &#39;4S Ranch&#39;, &#39;Email&#39;: &#39;jefferyl56783@stu.powayusd.com&#39;, &#39;Owns_Cars&#39;: [&#39;Honda Accord&#39;]}]
</pre>
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
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">print_data</span><span class="p">(</span><span class="n">d_rec</span><span class="p">):</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;FirstName&quot;</span><span class="p">],</span> <span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;LastName&quot;</span><span class="p">])</span>  <span class="c1"># using comma puts space between values</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="se">\t</span><span class="s2">&quot;</span><span class="p">,</span> <span class="s2">&quot;Residence:&quot;</span><span class="p">,</span> <span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;Residence&quot;</span><span class="p">])</span> <span class="c1"># \t is a tab indent</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="se">\t</span><span class="s2">&quot;</span><span class="p">,</span> <span class="s2">&quot;Birth Day:&quot;</span><span class="p">,</span> <span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;DOB&quot;</span><span class="p">])</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="se">\t</span><span class="s2">&quot;</span><span class="p">,</span> <span class="s2">&quot;Cars: &quot;</span><span class="p">,</span> <span class="n">end</span><span class="o">=</span><span class="s2">&quot;&quot;</span><span class="p">)</span>  <span class="c1"># end=&quot;&quot; make sure no return occurs</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;, &quot;</span><span class="o">.</span><span class="n">join</span><span class="p">(</span><span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;Owns_Cars&quot;</span><span class="p">]))</span>  <span class="c1"># join allows printing a string list with separator</span>
    <span class="nb">print</span><span class="p">()</span>


<span class="c1"># for loop algorithm iterates on length of InfoDb</span>
<span class="k">def</span> <span class="nf">for_loop</span><span class="p">():</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;For loop output</span><span class="se">\n</span><span class="s2">&quot;</span><span class="p">)</span>
    <span class="k">for</span> <span class="n">record</span> <span class="ow">in</span> <span class="n">InfoDb</span><span class="p">:</span>
        <span class="n">print_data</span><span class="p">(</span><span class="n">record</span><span class="p">)</span>

<span class="n">for_loop</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>For loop output

Ethan Nyguen
	 Residence: San Diego
	 Birth Day: October 3
	 Cars: 2015-Fusion, 2011-Ranger, 2003-Excursion, 1997-F350, 1969-Cadillac

Luke Riggins
	 Residence: San Diego
	 Birth Day: December 2
	 Cars: Volkswagon Passat

Luke Riggins
	 Residence: Rancho Bernardo
	 Birth Day: December 2
	 Cars: Toyota

Jeffery Lee
	 Residence: 4S Ranch
	 Birth Day: December 27
	 Cars: Honda Accord

</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Formatted output of List/Dictionary - for loop</p>
<ul>
<li><p>Prepare a function to format the data</p>
</li>
<li><p>Prepare a function to iterate through the list</p>
</li>
<li><p>Activate your function</p>
</li>
</ul>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">print_data</span><span class="p">(</span><span class="n">d_rec</span><span class="p">):</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;FirstName&quot;</span><span class="p">],</span> <span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;LastName&quot;</span><span class="p">])</span>  <span class="c1"># using comma puts space between values</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="se">\t</span><span class="s2">&quot;</span><span class="p">,</span> <span class="s2">&quot;Residence:&quot;</span><span class="p">,</span> <span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;Residence&quot;</span><span class="p">])</span> <span class="c1"># \t is a tab indent</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="se">\t</span><span class="s2">&quot;</span><span class="p">,</span> <span class="s2">&quot;Birth Day:&quot;</span><span class="p">,</span> <span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;DOB&quot;</span><span class="p">])</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="se">\t</span><span class="s2">&quot;</span><span class="p">,</span> <span class="s2">&quot;Cars: &quot;</span><span class="p">,</span> <span class="n">end</span><span class="o">=</span><span class="s2">&quot;&quot;</span><span class="p">)</span>  <span class="c1"># end=&quot;&quot; make sure no return occurs</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;, &quot;</span><span class="o">.</span><span class="n">join</span><span class="p">(</span><span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;Owns_Cars&quot;</span><span class="p">]))</span>  <span class="c1"># join allows printing a string list with separator</span>
    <span class="nb">print</span><span class="p">()</span>


<span class="c1"># for loop algorithm iterates on length of InfoDb</span>
<span class="k">def</span> <span class="nf">for_loop</span><span class="p">():</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;For loop output</span><span class="se">\n</span><span class="s2">&quot;</span><span class="p">)</span>
    <span class="k">for</span> <span class="n">record</span> <span class="ow">in</span> <span class="n">InfoDb</span><span class="p">:</span>
        <span class="n">print_data</span><span class="p">(</span><span class="n">record</span><span class="p">)</span>

<span class="n">for_loop</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>For loop output

Ethan Nyguen
	 Residence: San Diego
	 Birth Day: October 3
	 Cars: 2015-Fusion, 2011-Ranger, 2003-Excursion, 1997-F350, 1969-Cadillac

Luke Riggins
	 Residence: San Diego
	 Birth Day: December 2
	 Cars: Volkswagon Passat

Luke Riggins
	 Residence: Rancho Bernardo
	 Birth Day: December 2
	 Cars: Toyota

Jeffery Lee
	 Residence: 4S Ranch
	 Birth Day: December 27
	 Cars: Honda Accord

</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Alternate Methods for iteration</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">while_loop</span><span class="p">():</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;While loop output</span><span class="se">\n</span><span class="s2">&quot;</span><span class="p">)</span>
    <span class="n">i</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="k">while</span> <span class="n">i</span> <span class="o">&lt;</span> <span class="nb">len</span><span class="p">(</span><span class="n">InfoDb</span><span class="p">):</span>
        <span class="n">record</span> <span class="o">=</span> <span class="n">InfoDb</span><span class="p">[</span><span class="n">i</span><span class="p">]</span>
        <span class="n">print_data</span><span class="p">(</span><span class="n">record</span><span class="p">)</span>
        <span class="n">i</span> <span class="o">+=</span> <span class="mi">1</span>
    <span class="k">return</span>

<span class="n">while_loop</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>While loop output

Ethan Nyguen
	 Residence: San Diego
	 Birth Day: October 3
	 Cars: 2015-Fusion, 2011-Ranger, 2003-Excursion, 1997-F350, 1969-Cadillac

Luke Riggins
	 Residence: San Diego
	 Birth Day: December 2
	 Cars: Volkswagon Passat

Luke Riggins
	 Residence: Rancho Bernardo
	 Birth Day: December 2
	 Cars: Toyota

Jeffery Lee
	 Residence: 4S Ranch
	 Birth Day: December 27
	 Cars: Honda Accord

</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Recursion</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">recursive_loop</span><span class="p">(</span><span class="n">i</span><span class="p">):</span>
    <span class="k">if</span> <span class="n">i</span> <span class="o">&lt;</span> <span class="nb">len</span><span class="p">(</span><span class="n">InfoDb</span><span class="p">):</span>
        <span class="n">record</span> <span class="o">=</span> <span class="n">InfoDb</span><span class="p">[</span><span class="n">i</span><span class="p">]</span>
        <span class="n">print_data</span><span class="p">(</span><span class="n">record</span><span class="p">)</span>
        <span class="n">recursive_loop</span><span class="p">(</span><span class="n">i</span> <span class="o">+</span> <span class="mi">1</span><span class="p">)</span>
    <span class="k">return</span>
    
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Recursive loop output</span><span class="se">\n</span><span class="s2">&quot;</span><span class="p">)</span>
<span class="n">recursive_loop</span><span class="p">(</span><span class="mi">0</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Recursive loop output

Ethan Nyguen
	 Residence: San Diego
	 Birth Day: October 3
	 Cars: 2015-Fusion, 2011-Ranger, 2003-Excursion, 1997-F350, 1969-Cadillac

Luke Riggins
	 Residence: San Diego
	 Birth Day: December 2
	 Cars: Volkswagon Passat

Luke Riggins
	 Residence: Rancho Bernardo
	 Birth Day: December 2
	 Cars: Toyota

Jeffery Lee
	 Residence: 4S Ranch
	 Birth Day: December 27
	 Cars: Honda Accord

</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Creating a For Loop with Index</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">for</span> <span class="n">indx</span><span class="p">,</span> <span class="n">record</span> <span class="ow">in</span> <span class="nb">enumerate</span><span class="p">(</span><span class="n">InfoDb</span><span class="p">):</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Record #&quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">indx</span><span class="o">+</span><span class="mi">1</span><span class="p">)</span> <span class="o">+</span> <span class="s2">&quot;: &quot;</span><span class="p">,</span> <span class="n">end</span> <span class="o">=</span> <span class="s2">&quot;&quot;</span><span class="p">)</span>
    <span class="n">print_data</span><span class="p">(</span><span class="n">record</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Record #1: Ethan Nyguen
	 Residence: San Diego
	 Birth Day: October 3
	 Cars: 2015-Fusion, 2011-Ranger, 2003-Excursion, 1997-F350, 1969-Cadillac

Record #2: Luke Riggins
	 Residence: San Diego
	 Birth Day: December 2
	 Cars: Volkswagon Passat

Record #3: Luke Riggins
	 Residence: Rancho Bernardo
	 Birth Day: December 2
	 Cars: Toyota

Record #4: Jeffery Lee
	 Residence: 4S Ranch
	 Birth Day: December 27
	 Cars: Honda Accord

</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Reverse Order</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">for</span> <span class="n">record</span> <span class="ow">in</span> <span class="nb">reversed</span><span class="p">(</span><span class="n">InfoDb</span><span class="p">):</span>
    <span class="n">print_data</span><span class="p">(</span><span class="n">record</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Jeffery Lee
	 Residence: 4S Ranch
	 Birth Day: December 27
	 Cars: Honda Accord

Luke Riggins
	 Residence: Rancho Bernardo
	 Birth Day: December 2
	 Cars: Toyota

Luke Riggins
	 Residence: San Diego
	 Birth Day: December 2
	 Cars: Volkswagon Passat

Ethan Nyguen
	 Residence: San Diego
	 Birth Day: October 3
	 Cars: 2015-Fusion, 2011-Ranger, 2003-Excursion, 1997-F350, 1969-Cadillac

</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

</div>
 
