---
layout: "0.8/documentation"
title: "Getting Started"
---
# Overview of Origami <span class="heading-accent">Current Version {{ site.data.globals.version }}</span>
<p>Origami is, in it's current state, my idea of what a framework should be. Tools to help you create a layout rapidly for your projects that leaves more than enough room for you to customize the living <span class="italic">$#!@</span> out of as the project progresses.</p>
<p>It was written in SASS, plain old JavaScript and compiled / minified with Gulp.js. But you can compile with whatever you like.</p>
<p>There are no dependencies like JQuery. Just plug it in and you are good to go.</p>
<br />
<a href="{{ site.data.globals.downloadUrl }}" target="_blank" class="btn mr-half"><span class="ti-cloud-down mr-half"></span>Source Files</a>
<div class="mt-3 mt-5-l"></div>


#### Browser Support
<p>Origami was written for the modern browser but, Origami does support <span class="highlight">IE11+</span>. Technically you can use the Origami in IE10 and the layouts will holdup beautifully but some JavaScript components haven't been fully tested hence why it is stated as supporting IE11+.</p>
<div class="mt-3 mt-5-l"></div>



#### Installation
<p>Starting a project with Origami is pretty straight forward. Simply <a href="{{ site.data.globals.downloadUrl }}" target="_blank">download the Origami files</a>. Once downloaded, you will have access to both source files and compiled files (minified versions as well) so if you want to get started quickly, just find the compiled files from the <span class="highlight">dist</span> folder and add them to your project. I recommend using the minified versions for speed purposes.</p>
<p>Once you have your Origami files in the respective css / js folders for your project, you can set up your first page like so: </p>
<pre><code class="language-html">&lt;!DOCTYPE html&gt;
&lt;html lang="en" class="no-js"&gt;
    &lt;head&gt;
        &lt;meta charset="utf-8"&gt;
        &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
        &lt;title&gt;&lt;/title&gt;
        &lt;!-- Origami CSS Files Linked Here --&gt;
        &lt;link rel="stylesheet" href="/path/to/origami.min.css"&gt;
    &lt;/head&gt;
    &lt;body&gt;
        &lt;main class="page-body"&gt;
            &lt;!-- your awesome content goes here --&gt;
        &lt;/main&gt;
        &lt;!-- Origami JavaScript Files Linked Here --&gt;
        &lt;script type="text/javascript" src="/path/to/origami.min.js"&gt;&lt;/script&gt;
    &lt;/body&gt;
&lt;/html&gt;</code></pre>
<p>As you can see, we try to abide by best practices. Keep your JavaScript near the closing body tag to allow your page to load before your script.</p>
