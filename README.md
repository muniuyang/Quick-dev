<article class="markdown-body entry-content" itemprop="text"><p><a href="https://camo.githubusercontent.com/51c2e8ce2152238688323b98488c3076e7e636a2/68747470733a2f2f7261772e6769746875622e636f6d2f6d656f6c752f77616c6c652d7765622f6d61737465722f646f63732f6c6f676f2e6a7067" target="_blank"><img src="https://camo.githubusercontent.com/51c2e8ce2152238688323b98488c3076e7e636a2/68747470733a2f2f7261772e6769746875622e636f6d2f6d656f6c752f77616c6c652d7765622f6d61737465722f646f63732f6c6f676f2e6a7067" alt="" data-canonical-src="https://raw.github.com/meolu/walle-web/master/docs/logo.jpg" style="max-width:100%;"></a></p>
<h1><a id="user-content-walle---a-deployment-tool" class="anchor" href="#walle---a-deployment-tool" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"/></svg></a>Walle - A Deployment Tool</h1>
<p><a href="https://travis-ci.org/meolu/walle-web"><img src="https://camo.githubusercontent.com/8a045fb15cecbbbf3a07b1dcd2435e5f6a9084a9/68747470733a2f2f7472617669732d63692e6f72672f6d656f6c752f77616c6c652d7765622e7376673f6272616e63683d6d6173746572" alt="Build Status" data-canonical-src="https://travis-ci.org/meolu/walle-web.svg?branch=master" style="max-width:100%;"></a>
<a href="https://packagist.org/packages/meolu/walle-web"><img src="https://camo.githubusercontent.com/3258982deb4943ee1849e1aef7fbc15ab2a11864/68747470733a2f2f696d672e736869656c64732e696f2f7061636b61676973742f762f6d656f6c752f77616c6c652d7765622e737667" alt="Packagist" data-canonical-src="https://img.shields.io/packagist/v/meolu/walle-web.svg" style="max-width:100%;"></a>
<a href="http://www.yiiframework.com/"><img src="https://camo.githubusercontent.com/d10ea4bd497025fc11f5d609258752fe68345290/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f506f77657265645f62792d5969695f4672616d65776f726b2d677265656e2e7376673f7374796c653d666c6174" alt="Yii2" data-canonical-src="https://img.shields.io/badge/Powered_by-Yii_Framework-green.svg?style=flat" style="max-width:100%;"></a></p>
<p>A web deployment tool, Easy for configuration, Fully functional, Smooth interface, Out of the box.
support git/svn Version control system, no matter what language you are, php/java/ruby/python, just as jenkins. you can deploy the code or output to multiple servers easily by walle.</p>
<p><a href="https://www.walle-web.io">Home Page</a> | <a href="https://www.walle-web.io">官方主页</a> | <a href="https://github.com/meolu/walle-web/blob/master/docs/README-zh.md">中文说明</a> | <a href="https://www.walle-web.io/docs/">文档手册</a>.</p>
<p>Now, there are more than hundreds of companies hosted walle for deployment, star walle if you like : )</p>
<ul>
<li>Support git/svn Version control system.</li>
<li>User signup by admin/develop identity.</li>
<li>Developer submit a task, deploy task.</li>
<li>Admin audit task.</li>
<li>Multiple project.</li>
<li>Multiple Task Parallel.</li>
<li>Quick rollback.</li>
<li>Group relation of project.</li>
<li>Task of pre-deploy（e.g: test ENV var）.</li>
<li>Task of post-deploy（e.g: mvn/ant, composer install for vendor）.</li>
<li>Task of pre-release（e.g: stop service）.</li>
<li>Task of post-release（e.g: restart service）.</li>
<li>Check up file md5.</li>
<li>Multi-process multi-server file transfer (Ansible).</li>
</ul>
<h2><a id="user-content-requirements" class="anchor" href="#requirements" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"/></svg></a>Requirements</h2>
<ul>
<li>Bash(git、ssh)</li>
<li>LNMP/LAMP(php5.4+)</li>
<li>Composer</li>
<li>Ansible(Optional)</li>
</ul>
<p>That's all. It's base package of PHP environment!</p>
<h2><a id="user-content-installation" class="anchor" href="#installation" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"/></svg></a>Installation</h2>
<pre><code>git clone git@github.com:meolu/walle-web.git
cd walle-web
vi config/web.php # set up module db mysql connection info
composer install  # error cause by bower-asset, install：composer global require "fxp/composer-asset-plugin:*"
./yii walle/setup # init walle
</code></pre>
<p>Or <a href="https://github.com/meolu/walle-web/blob/master/docs/install-en.md">The Most Detailed Installation Guide</a>, any questions refer to <a href="https://github.com/meolu/walle-web/blob/master/docs/faq-en.md">FAQ</a></p>
<h2><a id="user-content-quick-start" class="anchor" href="#quick-start" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"/></svg></a>Quick Start</h2>
<ul>
<li>Signup a admin user(<code>admin/admin</code> exists), then configure a project, add member to the project, detect it.
<ul>
<li><a href="https://github.com/meolu/walle-web/blob/master/docs/config-git-en.md">git demo</a></li>
<li><a href="https://github.com/meolu/walle-web/blob/master/docs/config-svn-en.md">svn demo</a></li>
</ul>
</li>
<li>Signup a develop user(<code>demo/demo</code> exists), submit a deployment.</li>
<li>Project admin audit the deployment.</li>
<li>Developer deploy the deployment.</li>
</ul>
<h2><a id="user-content-custom" class="anchor" href="#custom" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"/></svg></a>Custom</h2>
<p>you would like to adjust some params to make walle suited for your company.</p>
<ul>
<li>
<p>Set suffix of email while signing in</p>
<div class="highlight highlight-text-html-php"><pre><span class="pl-s1"><span class="pl-c1">vi</span> <span class="pl-c1">config</span><span class="pl-k">/</span><span class="pl-c1">params</span><span class="pl-k">.</span><span class="pl-c1">php</span></span>
<span class="pl-s1"></span>
<span class="pl-s1"><span class="pl-s"><span class="pl-pds">'</span>mail-suffix<span class="pl-pds">'</span></span>   <span class="pl-k">=&gt;</span> [  <span class="pl-c"><span class="pl-c">//</span> specify the suffix of email, multiple suffixes are allow.</span></span>
<span class="pl-s1">    <span class="pl-s"><span class="pl-pds">'</span>huamanshu.com<span class="pl-pds">'</span></span>,  <span class="pl-c"><span class="pl-c">//</span> e.g: allow xyz@huamanshu.com only</span></span>
<span class="pl-s1">]</span></pre></div>
</li>
<li>
<p>Configure email smtp</p>
<div class="highlight highlight-text-html-php"><pre><span class="pl-s1"><span class="pl-c1">vi</span> <span class="pl-c1">config</span><span class="pl-k">/</span><span class="pl-c1">local</span><span class="pl-k">.</span><span class="pl-c1">php</span></span>
<span class="pl-s1"></span>
<span class="pl-s1"><span class="pl-s"><span class="pl-pds">'</span>transport<span class="pl-pds">'</span></span> <span class="pl-k">=&gt;</span> [</span>
<span class="pl-s1">        <span class="pl-s"><span class="pl-pds">'</span>host<span class="pl-pds">'</span></span>       <span class="pl-k">=&gt;</span> <span class="pl-s"><span class="pl-pds">'</span>smtp.huamanshu.com<span class="pl-pds">'</span></span>,</span>
<span class="pl-s1">        <span class="pl-s"><span class="pl-pds">'</span>username<span class="pl-pds">'</span></span>   <span class="pl-k">=&gt;</span> <span class="pl-s"><span class="pl-pds">'</span>service@huamanshu.com<span class="pl-pds">'</span></span>,</span>
<span class="pl-s1">        <span class="pl-s"><span class="pl-pds">'</span>password<span class="pl-pds">'</span></span>   <span class="pl-k">=&gt;</span> <span class="pl-s"><span class="pl-pds">'</span>K84erUuxg1bHqrfD<span class="pl-pds">'</span></span>,</span>
<span class="pl-s1">        <span class="pl-s"><span class="pl-pds">'</span>port<span class="pl-pds">'</span></span>       <span class="pl-k">=&gt;</span> <span class="pl-c1">25</span>,</span>
<span class="pl-s1">        <span class="pl-s"><span class="pl-pds">'</span>encryption<span class="pl-pds">'</span></span> <span class="pl-k">=&gt;</span> <span class="pl-s"><span class="pl-pds">'</span>tls<span class="pl-pds">'</span></span>,</span>
<span class="pl-s1">    ],</span>
<span class="pl-s1">    <span class="pl-s"><span class="pl-pds">'</span>messageConfig<span class="pl-pds">'</span></span> <span class="pl-k">=&gt;</span> [</span>
<span class="pl-s1">        <span class="pl-s"><span class="pl-pds">'</span>charset<span class="pl-pds">'</span></span> <span class="pl-k">=&gt;</span> <span class="pl-s"><span class="pl-pds">'</span>UTF-8<span class="pl-pds">'</span></span>,</span>
<span class="pl-s1">        <span class="pl-s"><span class="pl-pds">'</span>from<span class="pl-pds">'</span></span>    <span class="pl-k">=&gt;</span> [<span class="pl-s"><span class="pl-pds">'</span>service@huamanshu.com<span class="pl-pds">'</span></span> <span class="pl-k">=&gt;</span> <span class="pl-s"><span class="pl-pds">'</span>花满树出品<span class="pl-pds">'</span></span>],  <span class="pl-c"><span class="pl-c">//</span> the same with username of mail module in config/web.php</span></span>
<span class="pl-s1">    ],</span></pre></div>
</li>
<li>
<p>Configure the path for log</p>
<div class="highlight highlight-text-html-php"><pre><span class="pl-s1"><span class="pl-c1">vi</span> <span class="pl-c1">config</span><span class="pl-k">/</span><span class="pl-c1">params</span><span class="pl-k">.</span><span class="pl-c1">php</span></span>
<span class="pl-s1"></span>
<span class="pl-s1"><span class="pl-s"><span class="pl-pds">'</span>log.dir<span class="pl-pds">'</span></span>   <span class="pl-k">=&gt;</span> <span class="pl-s"><span class="pl-pds">'</span>/tmp/walle/<span class="pl-pds">'</span></span>,</span></pre></div>
</li>
<li>
<p>Configure language</p>
<div class="highlight highlight-text-html-php"><pre><span class="pl-s1"><span class="pl-c1">vi</span> <span class="pl-c1">config</span><span class="pl-k">/</span><span class="pl-c1">web</span><span class="pl-k">.</span><span class="pl-c1">php</span> <span class="pl-k">+</span><span class="pl-c1">73</span></span>
<span class="pl-s1"></span>
<span class="pl-s1"><span class="pl-s"><span class="pl-pds">'</span>language<span class="pl-pds">'</span></span>   <span class="pl-k">=&gt;</span> <span class="pl-s"><span class="pl-pds">'</span>en<span class="pl-pds">'</span></span>,  <span class="pl-c"><span class="pl-c">#</span> zh =&gt; 中文,  en =&gt; English</span></span></pre></div>
</li>
</ul>
<h2><a id="user-content-to-do-list" class="anchor" href="#to-do-list" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"/></svg></a>To Do List</h2>
<ul>
<li>Travis CI integration</li>
<li>Mail events：specify kinds of events</li>
<li>Gray released：specify servers</li>
<li>Websocket instead of poll</li>
<li>A manager of static source</li>
<li>Configure variables</li>
<li>Support Docker</li>
<li>Open api</li>
<li>Command line</li>
</ul>
<h2><a id="user-content-update" class="anchor" href="#update" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"/></svg></a>Update</h2>
<pre><code>./yii walle/upgrade    # upgrade walle
</code></pre>
<h2><a id="user-content-architecture" class="anchor" href="#architecture" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"/></svg></a>Architecture</h2>
<h4><a id="user-content-gitsvn-user-host-servers" class="anchor" href="#gitsvn-user-host-servers" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"/></svg></a>git/svn, user, host, servers</h4>
<p><a href="https://camo.githubusercontent.com/9b1dd2ba47a6ac2d0989cfa59602894cfaeba52f/68747470733a2f2f7261772e6769746875622e636f6d2f6d656f6c752f646f63732f6d61737465722f77616c6c652d7765622e696f2f646f63732f656e2f7374617469632f77616c6c652d666c6f772d72656c6174696f6e2d656e2e706e67" target="_blank"><img src="https://camo.githubusercontent.com/9b1dd2ba47a6ac2d0989cfa59602894cfaeba52f/68747470733a2f2f7261772e6769746875622e636f6d2f6d656f6c752f646f63732f6d61737465722f77616c6c652d7765622e696f2f646f63732f656e2f7374617469632f77616c6c652d666c6f772d72656c6174696f6e2d656e2e706e67" alt="" data-canonical-src="https://raw.github.com/meolu/docs/master/walle-web.io/docs/en/static/walle-flow-relation-en.png" style="max-width:100%;"></a></p>
<h4><a id="user-content-deployment-flow" class="anchor" href="#deployment-flow" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"/></svg></a>deployment flow</h4>
<p><a href="https://camo.githubusercontent.com/f32098540c37353f7c43dedd89b17bf546c52b8f/68747470733a2f2f7261772e6769746875622e636f6d2f6d656f6c752f646f63732f6d61737465722f77616c6c652d7765622e696f2f646f63732f656e2f7374617469632f77616c6c652d666c6f772d656e2e706e67" target="_blank"><img src="https://camo.githubusercontent.com/f32098540c37353f7c43dedd89b17bf546c52b8f/68747470733a2f2f7261772e6769746875622e636f6d2f6d656f6c752f646f63732f6d61737465722f77616c6c652d7765622e696f2f646f63732f656e2f7374617469632f77616c6c652d666c6f772d656e2e706e67" alt="" data-canonical-src="https://raw.github.com/meolu/docs/master/walle-web.io/docs/en/static/walle-flow-en.png" style="max-width:100%;"></a></p>
<h2><a id="user-content-screenshots" class="anchor" href="#screenshots" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"/></svg></a>Screenshots</h2>
<h4><a id="user-content-project-config" class="anchor" href="#project-config" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"/></svg></a>project config</h4>
<p><a href="https://camo.githubusercontent.com/f35623150a07a5759a27ff789833364a4263922b/68747470733a2f2f7261772e6769746875622e636f6d2f6d656f6c752f646f63732f6d61737465722f77616c6c652d7765622e696f2f646f63732f656e2f7374617469632f77616c6c652d636f6e6669672d656469742d656e2e6a7067" target="_blank"><img src="https://camo.githubusercontent.com/f35623150a07a5759a27ff789833364a4263922b/68747470733a2f2f7261772e6769746875622e636f6d2f6d656f6c752f646f63732f6d61737465722f77616c6c652d7765622e696f2f646f63732f656e2f7374617469632f77616c6c652d636f6e6669672d656469742d656e2e6a7067" alt="" data-canonical-src="https://raw.github.com/meolu/docs/master/walle-web.io/docs/en/static/walle-config-edit-en.jpg" style="max-width:100%;"></a></p>
<h4><a id="user-content-sumbit-a-task" class="anchor" href="#sumbit-a-task" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"/></svg></a>sumbit a task</h4>
<p><a href="https://camo.githubusercontent.com/f9456f408025ceb1157e10e316fac55467e125d6/68747470733a2f2f7261772e6769746875622e636f6d2f6d656f6c752f646f63732f6d61737465722f77616c6c652d7765622e696f2f646f63732f656e2f7374617469632f77616c6c652d7375626d69742d656e2e6a7067" target="_blank"><img src="https://camo.githubusercontent.com/f9456f408025ceb1157e10e316fac55467e125d6/68747470733a2f2f7261772e6769746875622e636f6d2f6d656f6c752f646f63732f6d61737465722f77616c6c652d7765622e696f2f646f63732f656e2f7374617469632f77616c6c652d7375626d69742d656e2e6a7067" alt="" data-canonical-src="https://raw.github.com/meolu/docs/master/walle-web.io/docs/en/static/walle-submit-en.jpg" style="max-width:100%;"></a></p>
<h4><a id="user-content-list-of-task" class="anchor" href="#list-of-task" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"/></svg></a>list of task</h4>
<p><a href="https://camo.githubusercontent.com/cd87bc1c2e97edcc85f1fd02f9457232fc8e21c5/68747470733a2f2f7261772e6769746875622e636f6d2f6d656f6c752f646f63732f6d61737465722f77616c6c652d7765622e696f2f646f63732f656e2f7374617469632f77616c6c652d6465762d6c6973742d656e2e6a7067" target="_blank"><img src="https://camo.githubusercontent.com/cd87bc1c2e97edcc85f1fd02f9457232fc8e21c5/68747470733a2f2f7261772e6769746875622e636f6d2f6d656f6c752f646f63732f6d61737465722f77616c6c652d7765622e696f2f646f63732f656e2f7374617469632f77616c6c652d6465762d6c6973742d656e2e6a7067" alt="" data-canonical-src="https://raw.github.com/meolu/docs/master/walle-web.io/docs/en/static/walle-dev-list-en.jpg" style="max-width:100%;"></a></p>
<h4><a id="user-content-demo-show" class="anchor" href="#demo-show" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"/></svg></a>demo show</h4>
<p><a href="https://camo.githubusercontent.com/c4fc357ee771f4c6d859824f57efe866ee6e3c85/68747470733a2f2f7261772e6769746875622e636f6d2f6d656f6c752f646f63732f6d61737465722f77616c6c652d7765622e696f2f646f63732f656e2f7374617469632f77616c6c652d656e2e676966" target="_blank"><img src="https://camo.githubusercontent.com/c4fc357ee771f4c6d859824f57efe866ee6e3c85/68747470733a2f2f7261772e6769746875622e636f6d2f6d656f6c752f646f63732f6d61737465722f77616c6c652d7765622e696f2f646f63732f656e2f7374617469632f77616c6c652d656e2e676966" alt="" data-canonical-src="https://raw.github.com/meolu/docs/master/walle-web.io/docs/en/static/walle-en.gif" style="max-width:100%;"></a></p>
<h2><a id="user-content-changelog" class="anchor" href="#changelog" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"/></svg></a>CHANGELOG</h2>
<p><a href="https://github.com/meolu/walle-web/releases">CHANGELOG</a></p>
<h2><a id="user-content-discussing" class="anchor" href="#discussing" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"/></svg></a>Discussing</h2>
<ul>
<li><a href="https://github.com/meolu/walle-web/issues/new">submit issue</a></li>
<li>email: <a href="mailto:wushuiyong@huamanshu.com">wushuiyong@huamanshu.com</a></li>
</ul>
<h2><a id="user-content-勾搭下" class="anchor" href="#勾搭下" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"/></svg></a>勾搭下</h2>
<p><a href=" " target="_blank"><img src=" " alt="程进微信" style="max-width:100%;" width="244" align="left" height="314"></a></p>
</article>
