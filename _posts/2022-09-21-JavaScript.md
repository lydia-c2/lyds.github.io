---
keywords: fastai
description: JavaScript Codes
title: JavaScript
toc: false
comments: true
permalink: /notebooks/javascript_commands
categories: [week 5]
nb_path: _notebooks/2022-09-21-JavaScript.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-09-21-JavaScript.ipynb
-->

<div class="container" id="notebook-container">
        
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-javascript"><pre><span></span><span class="nx">console</span><span class="p">.</span><span class="nx">log</span><span class="p">(</span><span class="s2">&quot;Hello, my name is Lydia!&quot;</span><span class="p">);</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Hello, my name is Lydia!
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
<div class=" highlight hl-javascript"><pre><span></span><span class="kd">var</span> <span class="nx">msg</span> <span class="o">=</span> <span class="s2">&quot;Hello, my name is Lydia!&quot;</span><span class="p">;</span>
<span class="nx">console</span><span class="p">.</span><span class="nx">log</span><span class="p">(</span><span class="nx">msg</span><span class="p">);</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Hello, my name is Lydia!
Reuse of logIT
</pre>
</div>
</div>

<div class="output_area">

<div class="output_subarea output_text output_error">
<pre>
evalmachine.&lt;anonymous&gt;:5
logIt(&#34;Hello, Students!&#34;);
^

ReferenceError: logIt is not defined
    at evalmachine.&lt;anonymous&gt;:5:1
    at Script.runInThisContext (vm.js:96:20)
    at Object.runInThisContext (vm.js:303:38)
    at run ([eval]:1020:15)
    at onRunRequest ([eval]:864:18)
    at onMessage ([eval]:828:13)
    at process.emit (events.js:182:13)
    at emit (internal/child_process.js:812:12)
    at process._tickCallback (internal/process/next_tick.js:63:19)</pre>
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
<div class=" highlight hl-javascript"><pre><span></span><span class="kd">function</span> <span class="nx">logIt</span><span class="p">(</span><span class="nx">output</span><span class="p">)</span> <span class="p">{</span>
    <span class="nx">console</span><span class="p">.</span><span class="nx">log</span><span class="p">(</span><span class="nx">output</span><span class="p">);</span>
<span class="p">}</span>
<span class="nx">logIt</span><span class="p">(</span><span class="nx">msg</span><span class="p">);</span>
<span class="nx">console</span><span class="p">.</span><span class="nx">log</span><span class="p">(</span><span class="s2">&quot;Reuse of logIT&quot;</span><span class="p">)</span>
<span class="nx">logIt</span><span class="p">(</span><span class="s2">&quot;Mr. Yeung is so cool!&quot;</span><span class="p">);</span>
<span class="nx">logIt</span><span class="p">(</span><span class="mf">2022</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Hello, my name is Lydia!
Reuse of logIT
Mr. Yeung is so cool!
2022
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
<div class=" highlight hl-javascript"><pre><span></span><span class="kd">function</span> <span class="nx">logItType</span><span class="p">(</span><span class="nx">output</span><span class="p">)</span> <span class="p">{</span>
    <span class="nx">console</span><span class="p">.</span><span class="nx">log</span><span class="p">(</span><span class="k">typeof</span> <span class="nx">output</span><span class="p">,</span> <span class="s2">&quot;;&quot;</span><span class="p">,</span> <span class="nx">output</span><span class="p">);</span>
<span class="p">}</span>
<span class="nx">console</span><span class="p">.</span><span class="nx">log</span><span class="p">(</span><span class="s2">&quot;This is the best class ever&quot;</span><span class="p">)</span>
<span class="nx">logItType</span><span class="p">(</span><span class="s2">&quot;AP compsci&quot;</span><span class="p">);</span> 
<span class="nx">logItType</span><span class="p">(</span><span class="mf">2022</span><span class="p">);</span>   
<span class="nx">logItType</span><span class="p">([</span><span class="mf">1</span><span class="p">,</span> <span class="mf">2</span><span class="p">,</span> <span class="mf">3</span><span class="p">]);</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>This is the best class ever
string ; AP compsci
number ; 2022
object ; [ 1, 2, 3 ]
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
<div class=" highlight hl-javascript"><pre><span></span><span class="kd">function</span> <span class="nx">Person</span><span class="p">(</span><span class="nx">name</span><span class="p">,</span> <span class="nx">ghID</span><span class="p">,</span> <span class="nx">classOf</span><span class="p">)</span> <span class="p">{</span>
    <span class="k">this</span><span class="p">.</span><span class="nx">name</span> <span class="o">=</span> <span class="nx">name</span><span class="p">;</span>
    <span class="k">this</span><span class="p">.</span><span class="nx">ghID</span> <span class="o">=</span> <span class="nx">ghID</span><span class="p">;</span>
    <span class="k">this</span><span class="p">.</span><span class="nx">classOf</span> <span class="o">=</span> <span class="nx">classOf</span><span class="p">;</span>
    <span class="k">this</span><span class="p">.</span><span class="nx">role</span> <span class="o">=</span> <span class="s2">&quot;&quot;</span><span class="p">;</span>
<span class="p">}</span>

<span class="nx">Person</span><span class="p">.</span><span class="nx">prototype</span><span class="p">.</span><span class="nx">setRole</span> <span class="o">=</span> <span class="kd">function</span><span class="p">(</span><span class="nx">role</span><span class="p">)</span> <span class="p">{</span>
    <span class="k">this</span><span class="p">.</span><span class="nx">role</span> <span class="o">=</span> <span class="nx">role</span><span class="p">;</span>
<span class="p">}</span>

<span class="nx">Person</span><span class="p">.</span><span class="nx">prototype</span><span class="p">.</span><span class="nx">toJSON</span> <span class="o">=</span> <span class="kd">function</span><span class="p">()</span> <span class="p">{</span>
    <span class="kr">const</span> <span class="nx">obj</span> <span class="o">=</span> <span class="p">{</span><span class="nx">name</span><span class="o">:</span> <span class="k">this</span><span class="p">.</span><span class="nx">name</span><span class="p">,</span> <span class="nx">ghID</span><span class="o">:</span> <span class="k">this</span><span class="p">.</span><span class="nx">ghID</span><span class="p">,</span> <span class="nx">classOf</span><span class="o">:</span> <span class="k">this</span><span class="p">.</span><span class="nx">classOf</span><span class="p">,</span> <span class="nx">role</span><span class="o">:</span> <span class="k">this</span><span class="p">.</span><span class="nx">role</span><span class="p">};</span>
    <span class="kr">const</span> <span class="nx">json</span> <span class="o">=</span> <span class="nx">JSON</span><span class="p">.</span><span class="nx">stringify</span><span class="p">(</span><span class="nx">obj</span><span class="p">);</span>
    <span class="k">return</span> <span class="nx">json</span><span class="p">;</span>
<span class="p">}</span>


<span class="kd">var</span> <span class="nx">teacher</span> <span class="o">=</span> <span class="k">new</span> <span class="nx">Person</span><span class="p">(</span><span class="s2">&quot;Mr M&quot;</span><span class="p">,</span> <span class="s2">&quot;jm1021&quot;</span><span class="p">,</span> <span class="mf">1977</span><span class="p">);</span> 
<span class="nx">logItType</span><span class="p">(</span><span class="nx">teacher</span><span class="p">);</span>  
<span class="nx">logItType</span><span class="p">(</span><span class="nx">teacher</span><span class="p">.</span><span class="nx">toJSON</span><span class="p">());</span>  


<span class="nx">teacher</span><span class="p">.</span><span class="nx">setRole</span><span class="p">(</span><span class="s2">&quot;Teacher&quot;</span><span class="p">);</span>   
<span class="nx">logItType</span><span class="p">(</span><span class="nx">teacher</span><span class="p">);</span> 
<span class="nx">logItType</span><span class="p">(</span><span class="nx">teacher</span><span class="p">.</span><span class="nx">toJSON</span><span class="p">());</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>object ; Person { name: &#39;Mr M&#39;, ghID: &#39;jm1021&#39;, classOf: 1977, role: &#39;&#39; }
string ; {&#34;name&#34;:&#34;Mr M&#34;,&#34;ghID&#34;:&#34;jm1021&#34;,&#34;classOf&#34;:1977,&#34;role&#34;:&#34;&#34;}
object ; Person { name: &#39;Mr M&#39;, ghID: &#39;jm1021&#39;, classOf: 1977, role: &#39;Teacher&#39; }
string ; {&#34;name&#34;:&#34;Mr M&#34;,&#34;ghID&#34;:&#34;jm1021&#34;,&#34;classOf&#34;:1977,&#34;role&#34;:&#34;Teacher&#34;}
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
<div class=" highlight hl-javascript"><pre><span></span><span class="kd">var</span> <span class="nx">students</span> <span class="o">=</span> <span class="p">[</span> 
    <span class="k">new</span> <span class="nx">Person</span><span class="p">(</span><span class="s2">&quot;Lydia&quot;</span><span class="p">,</span> <span class="s2">&quot;lydia-c2&quot;</span><span class="p">,</span> <span class="mf">2024</span><span class="p">),</span>
    <span class="k">new</span> <span class="nx">Person</span><span class="p">(</span><span class="s2">&quot;Alexa&quot;</span><span class="p">,</span> <span class="s2">&quot;alexac54767&quot;</span><span class="p">,</span> <span class="mf">2024</span><span class="p">),</span>
    <span class="k">new</span> <span class="nx">Person</span><span class="p">(</span><span class="s2">&quot;Ava&quot;</span><span class="p">,</span> <span class="s2">&quot;avac54765&quot;</span><span class="p">,</span> <span class="mf">2024</span><span class="p">),</span>
    <span class="k">new</span> <span class="nx">Person</span><span class="p">(</span><span class="s2">&quot;Naja&quot;</span><span class="p">,</span> <span class="s2">&quot;najaafoncesa&quot;</span><span class="p">,</span> <span class="mf">2025</span><span class="p">),</span>

<span class="p">];</span>

<span class="kd">function</span> <span class="nx">Classroom</span><span class="p">(</span><span class="nx">teacher</span><span class="p">,</span> <span class="nx">students</span><span class="p">){</span> <span class="c1">// 1 teacher, many student</span>
    <span class="c1">// start Classroom with Teacher</span>
    <span class="nx">teacher</span><span class="p">.</span><span class="nx">setRole</span><span class="p">(</span><span class="s2">&quot;Teacher&quot;</span><span class="p">);</span>
    <span class="k">this</span><span class="p">.</span><span class="nx">teacher</span> <span class="o">=</span> <span class="nx">teacher</span><span class="p">;</span>
    <span class="k">this</span><span class="p">.</span><span class="nx">classroom</span> <span class="o">=</span> <span class="p">[</span><span class="nx">teacher</span><span class="p">];</span>
    <span class="c1">// add each Student to Classroom</span>
    <span class="k">this</span><span class="p">.</span><span class="nx">students</span> <span class="o">=</span> <span class="nx">students</span><span class="p">;</span>
    <span class="k">this</span><span class="p">.</span><span class="nx">students</span><span class="p">.</span><span class="nx">forEach</span><span class="p">(</span><span class="nx">student</span> <span class="p">=&gt;</span> <span class="p">{</span> <span class="nx">student</span><span class="p">.</span><span class="nx">setRole</span><span class="p">(</span><span class="s2">&quot;Student&quot;</span><span class="p">);</span> <span class="k">this</span><span class="p">.</span><span class="nx">classroom</span><span class="p">.</span><span class="nx">push</span><span class="p">(</span><span class="nx">student</span><span class="p">);</span> <span class="p">});</span>
    <span class="c1">// build json/string format of Classroom</span>
    <span class="k">this</span><span class="p">.</span><span class="nx">json</span> <span class="o">=</span> <span class="p">[];</span>
    <span class="k">this</span><span class="p">.</span><span class="nx">classroom</span><span class="p">.</span><span class="nx">forEach</span><span class="p">(</span><span class="nx">person</span> <span class="p">=&gt;</span> <span class="k">this</span><span class="p">.</span><span class="nx">json</span><span class="p">.</span><span class="nx">push</span><span class="p">(</span><span class="nx">person</span><span class="p">.</span><span class="nx">toJSON</span><span class="p">()));</span>
<span class="p">}</span>

<span class="c1">// make a CompSci classroom from formerly defined teacher and students</span>
<span class="nx">compsci</span> <span class="o">=</span> <span class="k">new</span> <span class="nx">Classroom</span><span class="p">(</span><span class="nx">teacher</span><span class="p">,</span> <span class="nx">students</span><span class="p">);</span>

<span class="c1">// output of Objects and JSON in CompSci classroom</span>
<span class="nx">logItType</span><span class="p">(</span><span class="nx">compsci</span><span class="p">.</span><span class="nx">classroom</span><span class="p">);</span> 
<span class="nx">logItType</span><span class="p">(</span><span class="nx">compsci</span><span class="p">.</span><span class="nx">classroom</span><span class="p">[</span><span class="mf">0</span><span class="p">].</span><span class="nx">name</span><span class="p">);</span>  
<span class="nx">logItType</span><span class="p">(</span><span class="nx">compsci</span><span class="p">.</span><span class="nx">json</span><span class="p">[</span><span class="mf">0</span><span class="p">]);</span>  
<span class="nx">logItType</span><span class="p">(</span><span class="nx">JSON</span><span class="p">.</span><span class="nx">parse</span><span class="p">(</span><span class="nx">compsci</span><span class="p">.</span><span class="nx">json</span><span class="p">[</span><span class="mf">0</span><span class="p">]));</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>object ; [ Person { name: &#39;Mr M&#39;, ghID: &#39;jm1021&#39;, classOf: 1977, role: &#39;Teacher&#39; },
  Person {
    name: &#39;Lydia&#39;,
    ghID: &#39;lydia-c2&#39;,
    classOf: 2024,
    role: &#39;Student&#39; },
  Person {
    name: &#39;Alexa&#39;,
    ghID: &#39;alexac54767&#39;,
    classOf: 2024,
    role: &#39;Student&#39; },
  Person { name: &#39;Ava&#39;, ghID: &#39;avac54765&#39;, classOf: 2024, role: &#39;Student&#39; },
  Person {
    name: &#39;Naja&#39;,
    ghID: &#39;najaafoncesa&#39;,
    classOf: 2025,
    role: &#39;Student&#39; } ]
string ; Mr M
string ; {&#34;name&#34;:&#34;Mr M&#34;,&#34;ghID&#34;:&#34;jm1021&#34;,&#34;classOf&#34;:1977,&#34;role&#34;:&#34;Teacher&#34;}
object ; { name: &#39;Mr M&#39;, ghID: &#39;jm1021&#39;, classOf: 1977, role: &#39;Teacher&#39; }
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
<div class=" highlight hl-javascript"><pre><span></span><span class="nx">Classroom</span><span class="p">.</span><span class="nx">prototype</span><span class="p">.</span><span class="nx">_toHtml</span> <span class="o">=</span> <span class="kd">function</span><span class="p">()</span> <span class="p">{</span>
    <span class="c1">// HTML Style is build using inline structure</span>
    <span class="kd">var</span> <span class="nx">style</span> <span class="o">=</span> <span class="p">(</span>
      <span class="s2">&quot;display:inline-block;&quot;</span> <span class="o">+</span>
      <span class="s2">&quot;border: 2px solid grey;&quot;</span> <span class="o">+</span>
      <span class="s2">&quot;box-shadow: 0.8em 0.4em 0.4em grey;&quot;</span>
    <span class="p">);</span>
  
    <span class="c1">// HTML Body of Table is build as a series of concatenations (+=)</span>
    <span class="kd">var</span> <span class="nx">body</span> <span class="o">=</span> <span class="s2">&quot;&quot;</span><span class="p">;</span>
    <span class="c1">// Heading for Array Columns</span>
    <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;tr&gt;&quot;</span><span class="p">;</span>
    <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;th&gt;&lt;mark&gt;&quot;</span> <span class="o">+</span> <span class="s2">&quot;Name&quot;</span> <span class="o">+</span> <span class="s2">&quot;&lt;/mark&gt;&lt;/th&gt;&quot;</span><span class="p">;</span>
    <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;th&gt;&lt;mark&gt;&quot;</span> <span class="o">+</span> <span class="s2">&quot;GitHub ID&quot;</span> <span class="o">+</span> <span class="s2">&quot;&lt;/mark&gt;&lt;/th&gt;&quot;</span><span class="p">;</span>
    <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;th&gt;&lt;mark&gt;&quot;</span> <span class="o">+</span> <span class="s2">&quot;Class Of&quot;</span> <span class="o">+</span> <span class="s2">&quot;&lt;/mark&gt;&lt;/th&gt;&quot;</span><span class="p">;</span>
    <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;th&gt;&lt;mark&gt;&quot;</span> <span class="o">+</span> <span class="s2">&quot;Role&quot;</span> <span class="o">+</span> <span class="s2">&quot;&lt;/mark&gt;&lt;/th&gt;&quot;</span><span class="p">;</span>
    <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;/tr&gt;&quot;</span><span class="p">;</span>
    <span class="c1">// Data of Array, iterate through each row of compsci.classroom </span>
    <span class="k">for</span> <span class="p">(</span><span class="kd">var</span> <span class="nx">row</span> <span class="k">of</span> <span class="nx">compsci</span><span class="p">.</span><span class="nx">classroom</span><span class="p">)</span> <span class="p">{</span>
      <span class="c1">// tr for each row, a new line</span>
      <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;tr&gt;&quot;</span><span class="p">;</span>
      <span class="c1">// td for each column of data</span>
      <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;td&gt;&quot;</span> <span class="o">+</span> <span class="nx">row</span><span class="p">.</span><span class="nx">name</span> <span class="o">+</span> <span class="s2">&quot;&lt;/td&gt;&quot;</span><span class="p">;</span>
      <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;td&gt;&quot;</span> <span class="o">+</span> <span class="nx">row</span><span class="p">.</span><span class="nx">ghID</span> <span class="o">+</span> <span class="s2">&quot;&lt;/td&gt;&quot;</span><span class="p">;</span>
      <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;td&gt;&quot;</span> <span class="o">+</span> <span class="nx">row</span><span class="p">.</span><span class="nx">classOf</span> <span class="o">+</span> <span class="s2">&quot;&lt;/td&gt;&quot;</span><span class="p">;</span>
      <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;td&gt;&quot;</span> <span class="o">+</span> <span class="nx">row</span><span class="p">.</span><span class="nx">role</span> <span class="o">+</span> <span class="s2">&quot;&lt;/td&gt;&quot;</span><span class="p">;</span>
      <span class="c1">// tr to end line</span>
      <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;tr&gt;&quot;</span><span class="p">;</span>
    <span class="p">}</span>
  
     <span class="c1">// Build and HTML fragment of div, table, table body</span>
    <span class="k">return</span> <span class="p">(</span>
      <span class="s2">&quot;&lt;div style=&#39;&quot;</span> <span class="o">+</span> <span class="nx">style</span> <span class="o">+</span> <span class="s2">&quot;&#39;&gt;&quot;</span> <span class="o">+</span>
        <span class="s2">&quot;&lt;table&gt;&quot;</span> <span class="o">+</span>
          <span class="nx">body</span> <span class="o">+</span>
        <span class="s2">&quot;&lt;/table&gt;&quot;</span> <span class="o">+</span>
      <span class="s2">&quot;&lt;/div&gt;&quot;</span>
    <span class="p">);</span>
  
  <span class="p">};</span>
  
  <span class="c1">// IJavaScript HTML processor receive parameter of defined HTML fragment</span>
  <span class="nx">$$</span><span class="p">.</span><span class="nx">html</span><span class="p">(</span><span class="nx">compsci</span><span class="p">.</span><span class="nx">_toHtml</span><span class="p">());</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">


<div class="output_html rendered_html output_subarea output_execute_result">
<div style='display:inline-block;border: 2px solid grey;box-shadow: 0.8em 0.4em 0.4em grey;'><table><tr><th><mark>Name</mark></th><th><mark>GitHub ID</mark></th><th><mark>Class Of</mark></th><th><mark>Role</mark></th></tr><tr><td>Mr M</td><td>jm1021</td><td>1977</td><td>Teacher</td><tr><tr><td>Lydia</td><td>lydia-c2</td><td>2024</td><td>Student</td><tr><tr><td>Alexa</td><td>alexac54767</td><td>2024</td><td>Student</td><tr><tr><td>Ava</td><td>avac54765</td><td>2024</td><td>Student</td><tr><tr><td>Naja</td><td>najaafoncesa</td><td>2025</td><td>Student</td><tr></table></div>
</div>

</div>

</div>
</div>

</div>
    {% endraw %}

</div>
 

