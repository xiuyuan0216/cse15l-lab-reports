<!DOCTYPE html>
<html>
<head>
<title>index.md</title>
<meta http-equiv="Content-type" content="text/html;charset=UTF-8">

<style>
/* https://github.com/microsoft/vscode/blob/master/extensions/markdown-language-features/media/markdown.css */
/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

body {
	font-family: var(--vscode-markdown-font-family, -apple-system, BlinkMacSystemFont, "Segoe WPC", "Segoe UI", "Ubuntu", "Droid Sans", sans-serif);
	font-size: var(--vscode-markdown-font-size, 14px);
	padding: 0 26px;
	line-height: var(--vscode-markdown-line-height, 22px);
	word-wrap: break-word;
}

#code-csp-warning {
	position: fixed;
	top: 0;
	right: 0;
	color: white;
	margin: 16px;
	text-align: center;
	font-size: 12px;
	font-family: sans-serif;
	background-color:#444444;
	cursor: pointer;
	padding: 6px;
	box-shadow: 1px 1px 1px rgba(0,0,0,.25);
}

#code-csp-warning:hover {
	text-decoration: none;
	background-color:#007acc;
	box-shadow: 2px 2px 2px rgba(0,0,0,.25);
}

body.scrollBeyondLastLine {
	margin-bottom: calc(100vh - 22px);
}

body.showEditorSelection .code-line {
	position: relative;
}

body.showEditorSelection .code-active-line:before,
body.showEditorSelection .code-line:hover:before {
	content: "";
	display: block;
	position: absolute;
	top: 0;
	left: -12px;
	height: 100%;
}

body.showEditorSelection li.code-active-line:before,
body.showEditorSelection li.code-line:hover:before {
	left: -30px;
}

.vscode-light.showEditorSelection .code-active-line:before {
	border-left: 3px solid rgba(0, 0, 0, 0.15);
}

.vscode-light.showEditorSelection .code-line:hover:before {
	border-left: 3px solid rgba(0, 0, 0, 0.40);
}

.vscode-light.showEditorSelection .code-line .code-line:hover:before {
	border-left: none;
}

.vscode-dark.showEditorSelection .code-active-line:before {
	border-left: 3px solid rgba(255, 255, 255, 0.4);
}

.vscode-dark.showEditorSelection .code-line:hover:before {
	border-left: 3px solid rgba(255, 255, 255, 0.60);
}

.vscode-dark.showEditorSelection .code-line .code-line:hover:before {
	border-left: none;
}

.vscode-high-contrast.showEditorSelection .code-active-line:before {
	border-left: 3px solid rgba(255, 160, 0, 0.7);
}

.vscode-high-contrast.showEditorSelection .code-line:hover:before {
	border-left: 3px solid rgba(255, 160, 0, 1);
}

.vscode-high-contrast.showEditorSelection .code-line .code-line:hover:before {
	border-left: none;
}

img {
	max-width: 100%;
	max-height: 100%;
}

a {
	text-decoration: none;
}

a:hover {
	text-decoration: underline;
}

a:focus,
input:focus,
select:focus,
textarea:focus {
	outline: 1px solid -webkit-focus-ring-color;
	outline-offset: -1px;
}

hr {
	border: 0;
	height: 2px;
	border-bottom: 2px solid;
}

h1 {
	padding-bottom: 0.3em;
	line-height: 1.2;
	border-bottom-width: 1px;
	border-bottom-style: solid;
}

h1, h2, h3 {
	font-weight: normal;
}

table {
	border-collapse: collapse;
}

table > thead > tr > th {
	text-align: left;
	border-bottom: 1px solid;
}

table > thead > tr > th,
table > thead > tr > td,
table > tbody > tr > th,
table > tbody > tr > td {
	padding: 5px 10px;
}

table > tbody > tr + tr > td {
	border-top: 1px solid;
}

blockquote {
	margin: 0 7px 0 5px;
	padding: 0 16px 0 10px;
	border-left-width: 5px;
	border-left-style: solid;
}

code {
	font-family: Menlo, Monaco, Consolas, "Droid Sans Mono", "Courier New", monospace, "Droid Sans Fallback";
	font-size: 1em;
	line-height: 1.357em;
}

body.wordWrap pre {
	white-space: pre-wrap;
}

pre:not(.hljs),
pre.hljs code > div {
	padding: 16px;
	border-radius: 3px;
	overflow: auto;
}

pre code {
	color: var(--vscode-editor-foreground);
	tab-size: 4;
}

/** Theming */

.vscode-light pre {
	background-color: rgba(220, 220, 220, 0.4);
}

.vscode-dark pre {
	background-color: rgba(10, 10, 10, 0.4);
}

.vscode-high-contrast pre {
	background-color: rgb(0, 0, 0);
}

.vscode-high-contrast h1 {
	border-color: rgb(0, 0, 0);
}

.vscode-light table > thead > tr > th {
	border-color: rgba(0, 0, 0, 0.69);
}

.vscode-dark table > thead > tr > th {
	border-color: rgba(255, 255, 255, 0.69);
}

.vscode-light h1,
.vscode-light hr,
.vscode-light table > tbody > tr + tr > td {
	border-color: rgba(0, 0, 0, 0.18);
}

.vscode-dark h1,
.vscode-dark hr,
.vscode-dark table > tbody > tr + tr > td {
	border-color: rgba(255, 255, 255, 0.18);
}

</style>

<style>
/* Tomorrow Theme */
/* http://jmblog.github.com/color-themes-for-google-code-highlightjs */
/* Original theme - https://github.com/chriskempson/tomorrow-theme */

/* Tomorrow Comment */
.hljs-comment,
.hljs-quote {
	color: #8e908c;
}

/* Tomorrow Red */
.hljs-variable,
.hljs-template-variable,
.hljs-tag,
.hljs-name,
.hljs-selector-id,
.hljs-selector-class,
.hljs-regexp,
.hljs-deletion {
	color: #c82829;
}

/* Tomorrow Orange */
.hljs-number,
.hljs-built_in,
.hljs-builtin-name,
.hljs-literal,
.hljs-type,
.hljs-params,
.hljs-meta,
.hljs-link {
	color: #f5871f;
}

/* Tomorrow Yellow */
.hljs-attribute {
	color: #eab700;
}

/* Tomorrow Green */
.hljs-string,
.hljs-symbol,
.hljs-bullet,
.hljs-addition {
	color: #718c00;
}

/* Tomorrow Blue */
.hljs-title,
.hljs-section {
	color: #4271ae;
}

/* Tomorrow Purple */
.hljs-keyword,
.hljs-selector-tag {
	color: #8959a8;
}

.hljs {
	display: block;
	overflow-x: auto;
	color: #4d4d4c;
	padding: 0.5em;
}

.hljs-emphasis {
	font-style: italic;
}

.hljs-strong {
	font-weight: bold;
}
</style>

<style>
/*
 * Markdown PDF CSS
 */

 body {
	font-family: -apple-system, BlinkMacSystemFont, "Segoe WPC", "Segoe UI", "Ubuntu", "Droid Sans", sans-serif, "Meiryo";
	padding: 0 12px;
}

pre {
	background-color: #f8f8f8;
	border: 1px solid #cccccc;
	border-radius: 3px;
	overflow-x: auto;
	white-space: pre-wrap;
	overflow-wrap: break-word;
}

pre:not(.hljs) {
	padding: 23px;
	line-height: 19px;
}

blockquote {
	background: rgba(127, 127, 127, 0.1);
	border-color: rgba(0, 122, 204, 0.5);
}

.emoji {
	height: 1.4em;
}

code {
	font-size: 14px;
	line-height: 19px;
}

/* for inline code */
:not(pre):not(.hljs) > code {
	color: #C9AE75; /* Change the old color so it seems less like an error */
	font-size: inherit;
}

/* Page Break : use <div class="page"/> to insert page break
-------------------------------------------------------- */
.page {
	page-break-after: always;
}

</style>
<link rel="stylesheet" href="file:///users/xiuyuan/desktop/markdown-pdf_css-master/markdown.css" type="text/css">
<script src="https://unpkg.com/mermaid/dist/mermaid.min.js"></script>
</head>
<body>
  <script>
    mermaid.initialize({
      startOnLoad: true,
      theme: document.body.classList.contains('vscode-dark') || document.body.classList.contains('vscode-high-contrast')
          ? 'dark'
          : 'default'
    });
  </script>
<h1 id="tutorials-for-cse-15l-week-1-lab">Tutorials for CSE 15L Week 1 Lab</h1>
<p><em><strong>Step 1: Installing Visual Studio Code</strong></em></p>
<blockquote>
<p>It is the very start of your extraoridinary journey in CSE 15L. Just go download VS Code in this
<a href="https://code.visualstudio.com/">website</a>. After downloading VS Code, you will see this page below.</p>
</blockquote>
<img src="file:///Users/xiuyuan/Documents/GitHub/cse15l-lab-reports/F81FD3A7-4AAA-4016-90B2-53F5AA67CD2F_1_105_c.jpeg" width="500" height="300">
&gt;Then you need to download Extension Pack in VS Code to dive into the wonderland of Java. 
<hr>
<p><em><strong>Step 2: Remotely Connecting</strong></em></p>
<blockquote>
<p>The second step is to connect to your account. If you are using Windows operating system, you have an extra thing to do: install
<a href="https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse">OpenSSH</a>. Use your course-specific account: cs15lwi22zz@ieng6.ucsd.edu, zz is your account name in UCSD.</p>
</blockquote>
<blockquote>
<p>To remotely connect in VS Code, type the following command to your terminal:</p>
</blockquote>
<pre><code>        $ssh cs15lwi22zz@ieng6.ucsd.edu
</code></pre>
<blockquote>
<p>Choose yes if you are asked yes or no. If nothing goes wrong, you will come to the page below.</p>
</blockquote>
<img src="file:///Users/xiuyuan/Documents/GitHub/cse15l-lab-reports/8B19653C-DEFB-4594-830D-DEF600CAE9F5.jpeg" width="500" height="300">
<hr>
<p><em><strong>Step 3: Trying some commands</strong></em></p>
<blockquote>
<p>Some commands you can try are listed below</p>
</blockquote>
<table>
<thead>
<tr>
<th style="text-align:center">command names</th>
<th style="text-align:center">commands names</th>
<th style="text-align:center">commands names</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center"><em><strong>cd</strong></em></td>
<td style="text-align:center"><em><strong>cat</strong></em></td>
<td style="text-align:center"><em><strong>pwd</strong></em></td>
</tr>
<tr>
<td style="text-align:center"><em><strong>ls -a</strong></em></td>
<td style="text-align:center"><em><strong>ls -lat</strong></em></td>
<td style="text-align:center"><em><strong>ls -l</strong></em></td>
</tr>
</tbody>
</table>
<blockquote>
<p>The result of these commands is as follows:</p>
</blockquote>
<img src="file:///Users/xiuyuan/Documents/GitHub/cse15l-lab-reports/B22401A6-AAC3-4BAA-BAF8-B0367D1D54CB.jpeg" width="500" height="300">
<hr>
<p><em><strong>Step 4: Moving files with scp command</strong></em></p>
<blockquote>
<p>scp is a command that copies a file from your computer to remote server. Create a file on your computer called WhereAmI.java and put the following code in it:</p>
</blockquote>
<pre><code>class WhereAmI { 
    public static void main(String[] args) { System.out.println(System.getProperty(“os.name”)); System.out.println(System.getProperty(“user.name”)); System.out.println(System.getProperty(“user.home”)); System.out.println(System.getProperty(“user.dir”)); } }
</code></pre>
<blockquote>
<p>Then use the following command to copy the file into remote server:</p>
</blockquote>
<pre><code>$scp WhereAmI.java cs15lwi22zz@ieng6.ucsd.edu:~/
</code></pre>
<blockquote>
<p>If you successfully finish it, you will see the following picture</p>
</blockquote>
<img src="file:///Users/xiuyuan/Documents/GitHub/cse15l-lab-reports/7516A757-ED28-4E8E-9651-CACCF9977A81.jpeg" width="500" height="300">
<blockquote>
<p>Then you can try to run the program on server by using javac and java command.</p>
</blockquote>
<hr>
<p><em><strong>Step 5: Setting an SSH key</strong></em></p>
<blockquote>
<p>To avoid typing your password every time you log into the server, you can use an SSH key to solve this.</p>
</blockquote>
<img src="file:///Users/xiuyuan/Documents/GitHub/cse15l-lab-reports/F73FA9A4-14E1-4057-B656-B93C11784374.jpeg" width="500" height="300">
<blockquote>
<p>This created two new files on your system; the private key (in a file id_rsa) and the public key (in a file id_rsa.pub), stored in the .ssh directory on your computer.Now we need to copy the public (not the private) key to the .ssh directory of your user account on the server.</p>
</blockquote>
<pre><code>$ ssh cs15lwi22zz@ieng6.ucsd.edu
&lt;Enter Password&gt;
# now on server
$ mkdir .ssh
$ &lt;logout&gt;
# back on client
$ scp /Users/joe/.ssh/id_rsa.pub cs15lwi22@ieng6.ucsd.edu:~/.ssh/authorized_keys
# You use your username and the path you saw in the command above
</code></pre>
<p><em><strong>Step 6: Making remote running even more pleasant</strong></em></p>
<ol>
<li>
<p>You can write a command in quotes at the end of an ssh command to directly run it on the remote server.</p>
<pre><code>    $ ssh cs15lwi22@ieng6.ucsd.edu &quot;ls&quot;
</code></pre>
</li>
</ol>
<img src="file:///Users/xiuyuan/Documents/GitHub/cse15l-lab-reports/B9915899-796D-4F27-8205-C02B01AA5E6C_1_105_c.jpeg" width="500" height="300">
 2. You can use semicolons to run multiple commands on the same line in most terminals.
<pre><code>        $ cp WhereAmI.java OtherMain java; javac OtherMain.java; java WhereAmI
</code></pre>
<ol start="3">
<li>You can use the up-arrow on your keyboard to recall the last command that was run</li>
</ol>

</body>
</html>
