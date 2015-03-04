<div class="entry-content"><p>作者：<a href="http://lucida.me/">Lucida</a></p>

<ul>
<li>微博：<a href="http://www.weibo.com/pegong/">@peng_gong</a></li>
<li>豆瓣：<a href="http://www.douban.com/people/figure9/">@figure9</a></li>
</ul>


<p>原文链接：<a href="http://lucida.me/blog/developer-reading-list/">http://lucida.me/blog/developer-reading-list/</a></p>

<h2>关于</h2>

<p>本文把程序员所需掌握的关键知识总结为三大类19个关键概念，然后给出了掌握每个关键概念所需的入门书籍，必读书籍，以及延伸阅读。旨在成为最好最全面的程序员必读书单。</p>

<h2>前言</h2>

<blockquote><p>Reading makes a full man; conference a ready man; and writing an exact man.</p>

<p>Francis Bacon</p></blockquote>

<p>优秀的程序员应该具备两方面能力：</p>

<ul>
<li>良好的<a href="http://zh.wikipedia.org/wiki/%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1">程序设计</a>能力：

<ul>
<li>掌握常用的数据结构和算法（例如链表，栈，堆，队列，排序和散列）；</li>
<li>理解计算机科学的核心概念（例如计算机系统结构、操作系统、编译原理和计算机网络）；</li>
<li>熟悉至少两门以上编程语言（例如C++，Java，C#，和Python）；</li>
</ul>
</li>
<li>专业的<a href="http://zh.wikipedia.org/wiki/%E8%BD%AF%E4%BB%B6%E5%BC%80%E5%8F%91">软件开发</a>素养：

<ul>
<li>具备良好的编程实践，能够编写可测试（Testable），可扩展（Extensible），可维护（Maintainable）的代码；</li>
<li>把握客户需求，按时交付客户所需要的软件产品；</li>
<li>理解现代软件开发过程中的核心概念（例如面向对象程序设计，测试驱动开发，持续集成，和持续交付等等）。</li>
</ul>
</li>
</ul>


<p>和其它能力一样，<a href="http://zh.wikipedia.org/wiki/%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1">程序设计</a>能力和<a href="http://zh.wikipedia.org/wiki/%E8%BD%AF%E4%BB%B6%E5%BC%80%E5%8F%91">软件开发</a>素养源自项目经验和书本知识。项目经验因人而异（来自不同领域的程序员，项目差异会很大）；但书本知识是相通的——尤其是经典图书，它们都能够拓宽程序员的视野，提高程序员的成长速度。</p>

<p>在过去几年的学习和工作中，我阅读了大量的程序设计/软件开发书籍。随着阅读量的增长，我意识到：</p>

<ul>
<li>经典书籍需要不断被重读——每一次重读都会有新的体会；</li>
<li>书籍并非读的越多越好——大多数书籍只是经典书籍中的概念延伸（有时甚至是照搬）；</li>
</ul>


<p>意识到这两点之后，我开始思考一个很<a href="http://zh.wikipedia.org/wiki/%E6%95%88%E7%9B%8A%E4%B8%BB%E7%BE%A9">功利</a>的问题：<strong>如何从尽可能少的书中，获取尽可能多的关键知识？</strong>换句话说：</p>

<ul>
<li>优秀的程序员应该掌握哪些关键概念？</li>
<li>哪些书籍来可以帮助程序员掌握这些关键概念？</li>
</ul>


<p>这即是这篇文章的出发点——我试图通过<a href="http://lucida.me/blog/developer-reading-list/">程序员必读书单</a>这篇文章来回答上面两个问题。</p>

<!-- more -->


<h2>标准</h2>

<p>进入必读书单之前，我先介绍下书单里的书籍选择标准和领域选择标准。当然你也<a href="#reading-list">点击这里</a>直接跳转到书单开始阅读。</p>

<h3>书籍选择标准</h3>

<ol>
<li><strong>必读</strong>：什么是必读书籍呢？如果学习某项技术有一本书无论如何都不能错过，那么这本书就是必读书籍——例如<a href="http://www.amazon.cn/gp/product/B001PTGR52/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001PTGR52&amp;linkCode=as2&amp;creative=3132">Effective Java</a>于Java，<a href="http://www.amazon.cn/gp/product/B00P8VZ8T4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00P8VZ8T4&amp;linkCode=as2&amp;creative=3132">CLR via C#</a>于C#；

<ul>
<li>注意我没有使用“经典”这个词，因为<strong>经典</strong>计算机书籍往往和<strong>计算机科学</strong>联系在一起，而且经典往往需要10年甚至更长的时间进行考验；</li>
</ul>
</li>
<li><strong>注重实践，而非理论</strong>：所以这个书单不会包含过于原理性的书籍；</li>
<li><strong>入门—必读—延伸</strong>：必读书籍的问题在于：1. 大多不适合入门；2. 不够全面。考虑到没有入门阅读和延伸阅读的阅读列表是不完整的——所以书单中每个关键概念都会由一本入门书籍，一本必读书籍（有时入门书籍和必读书籍是同一本），和若干延伸阅读书籍所构成。</li>
</ol>


<h3>概念选择标准</h3>

<ol>
<li><strong>全面</strong>：全面覆盖软件开发中重要的概念；</li>
<li><strong>通用</strong>：适用于每一个程序员，和领域特定方向无关；</li>
<li><strong>注重基础，但不过于深入</strong>：优秀的程序员需要<strong>良好</strong>的计算机科学基础，但程序员并没必要掌握<strong>过于深入</strong>的计算机科学知识。以算法为例，每个程序员都应该掌握排序、链表、栈以及队列这些基本数据结构和算法，但计算几何、线性规划和网络流这些算法可能就不是每个程序员都需要掌握的了；</li>
</ol>


<p>通过这几个标准，我把程序员应掌握的关键概念分为程序设计，软件开发，以及个人成长三大类，每一大类均由若干关键概念组成。</p>

<h2><a name="fast-lane">快速通道</a></h2>

<p>自从开博以来，经常会有朋友在论坛，微博，和QQ上提问学习X技术读什么书合适（例如：学习Java读什么书合适？如何学习程序设计？）所以我在这里列出了一个“快速通道”——把常见的问题集中在一起，点击问题，即可直接进入答案。（当然，如果你把本文从头读到尾帮助会更大 :–)）</p>

<ul>
<li><a href="#foundation">如何学习计算机基础知识？</a></li>
<li><a href="#c">如何学习C语言？</a></li>
<li><a href="#cpp">如何学习C++？</a></li>
<li><a href="#java">如何学习Java？</a></li>
<li><a href="#csharp">如何学习C#？</a></li>
<li><a href="#javascript">如何学习JavaScript？</a></li>
<li><a href="#python">如何学习Python？</a></li>
<li><a href="#programming_language_theory">如何加深对编程语言的理解？</a></li>
<li><a href="#programming_technique">如何学习程序设计技巧？</a></li>
<li><a href="#algorithm_data_structure">如何学习算法？</a></li>
<li><a href="#debugging">如何高效的调试程序？</a></li>
<li><a href="#programming_practice">如何掌握良好的编程实践？</a></li>
<li><a href="#oop">如何学习面向对象程序设计？</a></li>
<li><a href="#refactoring">如何对代码进行重构？</a></li>
<li><a href="#software_testing">如何更好的进行软件测试？</a></li>
<li><a href="#project_management">如何管理软件团队/软件项目？</a></li>
<li><a href="#professional_developing">如何成为一名更专业的程序员？</a></li>
<li><a href="#interface_design">程序员如何学习设计？</a></li>
<li><a href="#career_development">程序员如何进行职业规划？</a></li>
<li><a href="#thinking">如何提高自己的思维能力？</a></li>
<li><a href="#job_interview">如何进行高效求职面试？</a></li>
<li><a href="#english_writing">如何提高自己的英语写作能力？</a></li>
</ul>


<h2><a name="reading-list">程序员必读书单</a></h2>

<h3><a name="starter-reading-list">入门书籍</a></h3>

<h4>程序设计：</h4>

<ol>
<li><a href="#foundation">基础理论</a>：<a href="#code">编码：隐匿在计算机软硬件背后的语言</a></li>
<li><a href="#programming_language">编程语言</a>：

<ul>
<li><a href="#c">C</a>：<a href="#pointers_on_c">C和指针</a></li>
<li><a href="#cpp">C++</a>：<a href="#pppcpp">C++程序设计原理与实践</a></li>
<li><a href="#java">Java</a>：<a href="#core_java">Java核心技术（第9版）</a></li>
<li><a href="#csharp">C#</a>：<a href="#pro_csharp">精通C#（第6版）</a></li>
<li><a href="#javascript">JavaScript</a>：<a href="#js_dom_scripting">JavaScript DOM编程艺术（第2版）</a></li>
<li><a href="#python">Python</a>：<a href="#beginning_python">Python基础教程（第二版）</a></li>
</ul>
</li>
<li><a href="#programming_language_theory">编程语言理论</a>：<a href="#language_implementation_patterns">编程语言实现模式</a></li>
<li><a href="#programming_technique">程序设计</a>：<a href="#htdp">程序设计方法</a></li>
<li><a href="#algorithm_data_structure">算法与数据结构</a>：<a href="#algorithms_4e">算法（第4版）</a></li>
<li><a href="#debugging">程序调试</a>：<a href="#debugging_9_rules">调试九法——软硬件错误的排查之道</a></li>
</ol>


<h4>软件开发：</h4>

<ol>
<li><a href="#programming_practice">编程实践</a>：<a href="#the_programming_practice">程序设计实践</a></li>
<li><a href="#oop">面向对象程序设计</a>：<a href="#head_first_design_patterns">Head First设计模式</a></li>
<li><a href="#refactoring">重构</a>：<a href="#refactoring_book">重构</a></li>
<li><a href="#software_testing">软件测试</a>：<a href="#how_to_break_software">How to Break Software</a></li>
<li><a href="#project_management">项目管理</a>：<a href="#team_geek">极客与团队</a></li>
<li><a href="#professional_developing">专业开发</a>：<a href="#the_pragmatic_programmer">程序员修炼之道：从小工到专家</a></li>
<li><a href="#master_saying">大师之言</a>：<a href="#out_of_their_minds">奇思妙想：15位计算机天才及其重大发现</a></li>
<li><a href="#interface_design">界面设计</a>：<a href="#non_designer_design_book">写给大家看的设计书</a></li>
<li><a href="#interaction_design">交互设计</a>：<a href="#universal_design_principles">通用设计法则</a></li>
</ol>


<h4>个人成长：</h4>

<ol>
<li><a href="#career_development">职业规划</a>：<a href="#apprentice_patterns">软件开发者路线图</a></li>
<li><a href="#thinking">思维方式</a>：<a href="#pragmatic_thinking_and_learning">程序员的思维修炼：开发认知潜能的九堂课</a></li>
<li><a href="#job_interview">求职面试</a>：<a href="#google_resume">金领简历：敲开苹果微软谷歌的大门</a></li>
<li><a href="#english_writing">英语写作</a>：<a href="#the_only_grammar_book">The Only Grammar Book You’ll Ever Need</a></li>
</ol>


<h3><a name="classic-reading-list">必读书籍</a></h3>

<h4>程序设计：</h4>

<ol>
<li><a href="#foundation">基础理论</a>：<a href="#csapp">深入理解计算机系统（第2版）</a></li>
<li><a href="#programming_language">编程语言</a>：

<ul>
<li><a href="#c">C</a>：<a href="#tcpl">C程序设计语言（第2版）</a></li>
<li><a href="#cpp">C++</a>：<a href="#tcpppl">C++程序设计语言（第4版）</a></li>
<li><a href="#java">Java</a>：<a href="#effective_java">Effective Java（第2版）</a></li>
<li><a href="#csharp">C#</a>：<a href="#clr_via_csharp">CLR via C#（第4版）</a></li>
<li><a href="#javascript">JavaScript</a>：<a href="#js_good_parts">JavaScript语言精粹</a></li>
<li><a href="#python">Python</a>：<a href="#python_essential_reference">Python参考手册（第4版）</a></li>
</ul>
</li>
<li><a href="#programming_language_theory">编程语言理论</a>：<a href="#plp">程序设计语言——实践之路（第3版）</a></li>
<li><a href="#programming_technique">程序设计</a>：<a href="#sicp">计算机程序的构造与解释（第2版）</a></li>
<li><a href="#algorithm_data_structure">算法与数据结构</a>：<a href="#programming_pearls">编程珠玑（第2版）</a></li>
<li><a href="#debugging">程序调试</a>：<a href="#debugging_9_rules">调试九法——软硬件错误的排查之道</a></li>
</ol>


<h4>软件开发：</h4>

<ol>
<li><a href="#programming_practice">编程实践</a>：<a href="#code_complete">代码大全（第2版）</a></li>
<li><a href="#oop">面向对象程序设计</a>：<a href="#design_patterns">设计模式</a></li>
<li><a href="#refactoring">重构</a>：<a href="#working_effectively_with_legacy_code">修改代码的艺术</a></li>
<li><a href="#software_testing">软件测试</a>：<a href="#xunit_test_patterns">xUnit Test Patterns</a></li>
<li><a href="#project_management">项目管理</a>：<a href="#mythical_man_month">人月神话</a></li>
<li><a href="#professional_developing">专业开发</a>：<a href="#clean_coder">程序员职业素养</a></li>
<li><a href="#master_saying">大师之言</a>：<a href="#coders_at_work">编程人生：15位软件先驱访谈录</a></li>
<li><a href="#interface_design">界面设计</a>：<a href="#design_with_mind_in_mind">认知与设计：理解UI设计准则（第2版）</a></li>
<li><a href="#interaction_design">交互设计</a>：<a href="#about_face">交互设计精髓（第3版）</a></li>
</ol>


<h4>个人成长：</h4>

<ol>
<li><a href="#career_development">职业规划</a>：<a href="#apprentice_patterns">软件开发者路线图</a></li>
<li><a href="#thinking">思维方式</a>：<a href="#mastery">如何把事情做到最好</a></li>
<li><a href="#job_interview">求职面试</a>：<a href="#cracking_the_coding_interview">程序员面试金典（第5版）</a></li>
<li><a href="#english_writing">英语写作</a>：<a href="#elements_of_style">风格的要素</a></li>
</ol>


<p>这个阅读列表覆盖了软件开发各个关键领域的入门书籍和必读书籍，我相信它可以满足绝大多数程序员的需求，无论你是初学者，还是进阶者，都可以从中获益：</p>

<ul>
<li><a href="#foundation">基础理论</a>包括了程序员应该掌握的计算机基础知识；</li>
<li><a href="#programming_language">编程语言</a>对软件开发至关重要，我选择了<a href="#c">C</a>，<a href="#cpp">C++</a>，<a href="#java">Java</a>，<a href="#csharp">C#</a>，<a href="#python">Python</a>，和<a href="#javascript">JavaScript</a>这六门<a href="http://www.tiobe.com/index.php/content/paperinfo/tpci/index.html">主流编程语言</a>进行介绍，如果想进一步理解编程语言，可以阅读<a href="#programming_language_theory">编程语言理论</a>里的书目；</li>
<li>在理解编程语言的基础上，优秀的程序员还应该了解各种<a href="#programming_technique">程序设计</a>技巧，熟悉基本的<a href="#algorithm_data_structure">算法数据结构</a>，并且能够高效的进行<a href="#debugging">程序调试</a>。</li>
<li>良好的程序设计能力是成为优秀程序员的前提，但软件开发知识也是必不可少的：优秀的程序员应具备良好的<a href="#programming_practice">编程实践</a>，知道如何利用<a href="#oop">面向对象</a>，<a href="#refactoring">重构</a>，和<a href="#software_testing">软件测试</a>编写可复用，可扩展，可维护的代码，并具备软件<a href="#project_management">项目管理</a>知识和<a href="#professional_developing">专业开发</a>素养；</li>
<li>就像我们可以从名人传记里学习名人的成功经验，程序员也可以通过追随优秀程序员的足迹使自己少走弯路。<a href="#master_saying">大师之言</a>包含一系列对大师程序员/计算机科学家的访谈，任何程序员都可以从中获益良多；</li>
<li>为了打造用户满意的软件产品，程序员应当掌握一定的<a href="#interface_design">界面设计</a>知识和<a href="#interaction_design">交互设计</a>知识（是的，这些工作应该交给UI和UX，但如果你想独自打造一个产品呢？）；</li>
<li>专业程序员应当对自己进行<a href="#career_development">职业规划</a>，并熟悉程序员<a href="#job_interview">求职面试</a>的流程，以便在职业道路上越走越远；</li>
<li>软件开发是一项需要不断学习的技能，学习<a href="#thinking">思维方式</a>可以有效的提升学习能力和学习效率；</li>
<li>软件开发是一项国际化的工作，为了让更多的人了解你的代码（工作），良好的<a href="#english_writing">英语写作</a>能力必不可少。</li>
</ul>


<p>尽管我尽可能的去完善这个书单，但受限于我的个人经历，这个书单难免会有所偏颇。所以如果你有不同的意见，或者认为这个书单漏掉了某些重要书籍，请在评论中指出，我会及时更新。:–)</p>

<h2>程序设计</h2>

<h3><a name="foundation">1. 基础理论</a></h3>

<p><a name="code"></a><a href="http://www.amazon.cn/gp/product/B009RSXIB4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B009RSXIB4&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/FDMMp2w.jpg" alt="编码：隐匿在计算机软硬件背后的语言"></a></p>

<p><a href="http://www.amazon.cn/gp/product/B009RSXIB4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B009RSXIB4&amp;linkCode=as2&amp;creative=3132">编码：隐匿在计算机软硬件背后的语言</a>这本书其实不应该叫编码——它更应该叫“Petzold教你造计算机”——作者<a href="http://en.wikipedia.org/wiki/Charles_Petzold">Charles Petzold</a>创造性的以编码为主题，从电报机和手电筒讲到数字电路，然后利用<a href="http://zh.wikipedia.org/wiki/%E6%95%B0%E5%AD%97%E7%94%B5%E8%B7%AF">数字电路</a>中的逻辑门构造出<a href="http://zh.wikipedia.org/wiki/%E5%8A%A0%E6%B3%95%E5%99%A8">加法器</a>和<a href="http://zh.wikipedia.org/wiki/%E8%A7%A6%E5%8F%91%E5%99%A8">触发器</a>，最后构造出一个完整的<a href="http://zh.wikipedia.org/wiki/%E5%AD%98%E5%82%A8%E7%A8%8B%E5%BA%8F%E8%AE%A1%E7%AE%97%E6%9C%BA">存储程序计算机</a>。不要被这些电路概念吓到——<a href="http://www.amazon.cn/gp/product/B009RSXIB4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B009RSXIB4&amp;linkCode=as2&amp;creative=3132">编码</a>使用大量形象贴切的类比简化了这些概念，使其成为最精彩最通俗易懂的计算机入门读物。</p>

<p><a name="csapp"></a><a href="http://www.amazon.cn/gp/product/B004BJ18KM/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004BJ18KM&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/CkWOTm2.jpg" alt="深入理解计算机系统（第2版）"></a></p>

<p><a href="http://www.amazon.cn/gp/product/B004BJ18KM/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004BJ18KM&amp;linkCode=as2&amp;creative=3132">深入理解计算机系统（第2版）</a>这本书的全名是：Computer Systems：A Programmer’s Perspective（所以它又被称为CSAPP），我个人习惯把它翻译为程序员所需了解的计算机系统知识，尽管土了些，但更名副其实。</p>

<p><a href="http://www.amazon.cn/gp/product/B004BJ18KM/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004BJ18KM&amp;linkCode=as2&amp;creative=3132">深入理解计算机系统</a>是我读过的最优秀的计算机系统导论型作品，它创造性的把操作系统，计算机组成结构，数字电路，以及编译原理这些计算机基础学科中的核心概念汇集在一起，从而覆盖了指令集体系架构，汇编语言，代码优化，计算机存储体系架构，链接，装载，进程，以及虚拟内存这些程序员所需了解的关键计算机系统知识。如果想打下扎实的计算机基础又不想把操作系统计算机结构编译原理这些书统统读一遍，阅读<a href="http://www.amazon.cn/gp/product/B004BJ18KM/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004BJ18KM&amp;linkCode=as2&amp;creative=3132">深入理解计算机系统</a>是最有效率的方式。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/B00DSQZBDE/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00DSQZBDE&amp;linkCode=as2&amp;creative=3132">世界是数字的</a>：<a href="http://www.amazon.cn/gp/product/B0011425T8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011425T8&amp;linkCode=as2&amp;creative=3132">K&amp;R</a>中的K（<a href="http://www.cs.princeton.edu/~bwk/">Brian Kernighan</a>）的近作，这本书源自Brian在普林斯顿大学所教授的计算机基础课程，以通俗易懂的方式讲述了现代人所应了解的计算机知识和网络知识；</li>
<li><a href="http://www.amazon.cn/gp/product/B00AAQXKXS/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00AAQXKXS&amp;linkCode=as2&amp;creative=3132">图灵的秘密：他的生平、思想及论文解读</a>：<a href="http://en.wikipedia.org/wiki/Charles_Petzold">Charles Petzold</a>的另一部作品，这本书以图灵的论文<strong>论可计算数及其在判定问题上的应用</strong>（<a href="http://www.cs.virginia.edu/~robins/Turing_Paper_1936.pdf">On Computable Numbers, with an Application to the Entscheidungsproblem</a>）为主题，阐述了图灵机（现代计算机的始祖）的构造，原理，以及应用。</li>
<li><a href="http://www.amazon.cn/gp/product/B0011F9OQE/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011F9OQE&amp;linkCode=as2&amp;creative=3132">计算机系统概论（第2版）</a>：另一部优秀的计算机系统导论型作品，和<a href="http://www.amazon.cn/gp/product/B004BJ18KM/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004BJ18KM&amp;linkCode=as2&amp;creative=3132">深入理解计算机系统</a>不同，这本书采用自下而上的方式，从二进制，和数字逻辑这些底层知识一步步过渡到高级编程语言（C），从而以另一种方式理解计算机系统。</li>
</ul>


<h3><a name="programming_language">2. 编程语言</a></h3>

<p>编程语言是程序员必不可少的日常工具。工欲善其事，必先利其器。我在这里给出了C，C++，Java，C#，JavaScript，和Python这六种<a href="http://www.tiobe.com/index.php/content/paperinfo/tpci/index.html">常用编程语言</a>的书单（我个人不熟悉Objective-C和PHP，因此它们不在其中）。</p>

<p>需要注意的是：我在这里给出的是编程语言（Programming Language）书籍，而非编程平台（Programming Platform）书籍。以Java为例，<a href="http://www.amazon.cn/gp/product/B001PTGR52/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001PTGR52&amp;linkCode=as2&amp;creative=3132">Effective Java</a>属于编程语言书籍，而<a href="http://www.amazon.cn/gp/product/B00J4DXWDG/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00J4DXWDG&amp;linkCode=as2&amp;creative=3132">Android编程权威指南</a>就属于编程平台书籍。</p>

<h4><a name="c">C</a></h4>

<p><a name="pointers_on_c"></a><a href="http://www.amazon.cn/gp/product/B00163LU68/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00163LU68&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/ZXrZwIk.jpg" alt="C和指针"></a></p>

<p>忘记谭浩强那本糟糕不堪的C程序设计，<a href="http://www.amazon.cn/gp/product/B00163LU68/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00163LU68&amp;linkCode=as2&amp;creative=3132">C和指针</a>才是C语言的最佳入门书籍。它详细但又不失简练的介绍了C语言以及C标准库的方方面面。</p>

<p>对于C语言初学者，最难的概念不仅仅是指针和数组，还有指向数组的指针和指向指针的指针。<a href="http://www.amazon.cn/gp/product/B00163LU68/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00163LU68&amp;linkCode=as2&amp;creative=3132">C和指针</a>花了大量的篇幅和图示来把这些难懂但重要的概念讲的清清楚楚，这也是我推荐它作为C语言入门读物的原因。</p>

<p><a name="tcpl"></a><a href="http://www.amazon.cn/gp/product/B0011425T8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011425T8&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/ch4KuSt.jpg" alt="C程序设计语言（第2版）"></a></p>

<p>尽管<a href="http://www.amazon.cn/gp/product/B0011425T8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011425T8&amp;linkCode=as2&amp;creative=3132">C程序设计语言</a>是二十多年前的书籍，但它仍然是C语言——以及计算机科学中最重要的书籍之一，它的重要性不仅仅在于它用清晰的语言和简练的代码描述了C语言全貌，而且在于它为之后的计算机书籍——尤其是编程语言书籍树立了新的标杆。以至于在很多计算机书籍的扉页，都会有“感谢Kernighan教会我写作”这样的字样。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/B0012NIW9K/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0012NIW9K&amp;linkCode=as2&amp;creative=3132">C专家编程</a>：不要被标题中的“专家”吓到，这实际是一本很轻松的书籍，它既包含了大量C语言技术细节和编程技巧，也包含了很多有趣的编程轶事；</li>
<li><a href="http://www.amazon.cn/gp/product/B0012UMPBY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0012UMPBY&amp;linkCode=as2&amp;creative=3132">C陷阱与缺陷</a>：书如其名，这本书介绍了C语言中常见的坑和一些稀奇古怪的编程“技巧”，不少刁钻的C语言面试题都源自这本小册子；</li>
<li><a href="http://book.douban.com/subject/6519268/">C语言参考手册</a>：全面且权威的C语言参考手册，而且覆盖C99，如果你打算成为C语言专家，那么这本书不可错过；</li>
<li><a href="http://www.amazon.cn/gp/product/B00IZW4DK8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00IZW4DK8&amp;linkCode=as2&amp;creative=3132">C标准库</a>：给出了15个C标准库的设计思路，实现代码，以及测试代码，配合<a href="http://www.amazon.cn/gp/product/B0011425T8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011425T8&amp;linkCode=as2&amp;creative=3132">C程序设计语言</a>阅读效果更佳；</li>
<li><a href="http://www.amazon.cn/gp/product/B005LAJ9F6/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B005LAJ9F6&amp;linkCode=as2&amp;creative=3132">C语言接口与实现</a>：这本书展示了如何使用C语言实现可复用的数据结构，其中包含大量C语言高级技巧，以至于Amazon上排行第一的评论是“Probably the best advanced C book in existance”，而排行第二的评论则是“By far the most advanced C book I read”。</li>
</ul>


<h4><a name="cpp">C++</a></h4>

<p><a name="pppcpp"></a><a href="http://www.amazon.cn/gp/product/B003VPX6YS/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B003VPX6YS&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/5KPyCw8.jpg" alt="C++程序设计原理与实践"></a></p>

<p>作为C++的发明者，没有人能比<a href="http://en.wikipedia.org/wiki/Bjarne_Stroustrup">Bjarne Stroustrup</a>更理解C++。Bjarne在Texas A&amp;M大学任教时使用C++为大学新生讲授编程，从而就有了<a href="http://www.amazon.cn/gp/product/B003VPX6YS/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B003VPX6YS&amp;linkCode=as2&amp;creative=3132">C++程序设计原理与实践</a>这本书——它面向编程初学者，既包含C++教程，也包含大量程序设计原则。它不但是我读过最好的C++入门书，也是我读过最好的编程入门书。</p>

<p>比较有趣的是，<a href="http://www.amazon.cn/gp/product/B003VPX6YS/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B003VPX6YS&amp;linkCode=as2&amp;creative=3132">C++程序设计原理与实践</a>直到全书过半都没有出现指针，我想这可能是Bjarne为了证明不学C也可以学好C++吧。</p>

<p><a name="tcpppl"></a><a href="http://www.amazon.cn/gp/product/0321958322/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0321958322&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/gCHJXQJ.jpg" alt="C++程序设计语言（第4版）"></a></p>

<p>同样是<a href="http://en.wikipedia.org/wiki/Bjarne_Stroustrup">Bjarne Stroustrup</a>的作品，<a href="http://www.amazon.cn/gp/product/0321958322/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0321958322&amp;linkCode=as2&amp;creative=3132">C++程序设计语言</a>是C++<strong>最权威且最全面</strong>的书籍。第4版相对于之前的版本进行了全面的更新，覆盖了第二新的C++ 11标准，并砍掉了部分过时的内容。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.com/Tour-C--Depth/dp/0321958314/">A Tour of C++</a>：如果你觉得<a href="http://www.amazon.cn/gp/product/0321958322/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0321958322&amp;linkCode=as2&amp;creative=3132">C++程序设计语言</a>过于庞大，但你又想快速的浏览一遍新版C++的语言特色，那么可以试试这本小红书；</li>
<li><a href="http://book.douban.com/subject/1096216/">C++语言的设计与演化</a>：C++的“历史书”，讲述了C++是如何一步一步从C with Classes走到如今这一步，以及C++语言特性背后的故事；</li>
<li><a href="http://www.amazon.cn/gp/product/B00APCO6DA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00APCO6DA&amp;linkCode=as2&amp;creative=3132">C++标准库（第2版）</a>：相对于其它语言的标准库，C++标准库虽然强大，但学习曲线十分陡峭，这本书是学习C++标准库有力的补充；</li>
<li><a href="http://www.amazon.cn/gp/product/B006QXQXTM/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B006QXQXTM&amp;linkCode=as2&amp;creative=3132">深度探索C++对象模型</a>：这本书系统的讲解了C++是如何以最小的性能代价实现对象模型，很多C++面试题（包括被问烂的虚函数指针）都可以在这本书里找到答案；</li>
<li><a href="http://www.amazon.cn/gp/product/B004G72P24/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004G72P24&amp;linkCode=as2&amp;creative=3132">Effective C++</a>和<a href="http://www.amazon.cn/gp/product/B004IP8BD6/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004IP8BD6&amp;linkCode=as2&amp;creative=3132">More Effective C++</a>：由于C++的特性实在繁杂，因此很容易就掉到坑里。Effective系列既讲述了C++的良好编程实践，也包含C++的使用误区，从而帮你绕过这些坑。</li>
</ul>


<h4><a name="java">Java</a></h4>

<p><a name="core_java"></a><a href="http://www.amazon.cn/gp/product/B00G9KF4JC/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00G9KF4JC&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/LOiRwUO.jpg" alt="Java核心技术（第9版）"></a></p>

<p>平心而论<a href="http://www.amazon.cn/gp/product/B00G9KF4JC/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00G9KF4JC&amp;linkCode=as2&amp;creative=3132">Java核心技术</a>（即Core Java）并不算是一本特别出色的书籍：示例代码不够严谨，充斥着很多与C/C++的比较，语言也不够简洁——问题在于Java并没有一本很出色的入门书籍，与同类型的<a href="http://www.amazon.cn/gp/product/B0011F7WU4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011F7WU4&amp;linkCode=as2&amp;creative=3132">Java编程思想</a>相比，<a href="http://www.amazon.cn/gp/product/B00G9KF4JC/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00G9KF4JC&amp;linkCode=as2&amp;creative=3132">Java核心技术</a>至少做到了废话不多，与时俱进（<a href="http://www.amazon.cn/gp/product/B0011F7WU4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011F7WU4&amp;linkCode=as2&amp;creative=3132">Java编程思想</a>还停留在Java 6之前），矮子里面选将军，<a href="http://www.amazon.cn/gp/product/B00G9KF4JC/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00G9KF4JC&amp;linkCode=as2&amp;creative=3132">Java核心技术</a>算不错了。</p>

<p><a name="effective_java"></a><a href="http://www.amazon.cn/gp/product/B001PTGR52/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001PTGR52&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/93uhytH.jpg" alt="Effective Java（第2版）"></a></p>

<p>尽管Java没有什么出色的入门书籍，但这不代表Java没有出色的必读书籍。<a href="http://www.amazon.cn/gp/product/B001PTGR52/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001PTGR52&amp;linkCode=as2&amp;creative=3132">Effective Java</a>是我读过的最好的编程书籍之一，它包含大量的优秀Java编程实践，并对泛型和并发这两个充满陷阱的Java特性给出了充满洞察力的建议，以至于Java之父<a href="http://en.wikipedia.org/wiki/James_Gosling">James Gosling</a>为这本书作序：<em>“我很希望10年前就拥有这本书。可能有人认为我不需要任何Java方面的书籍，但是我需要这本书。”</em></p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/B00D2ID4PK/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00D2ID4PK&amp;linkCode=as2&amp;creative=3132">深入理解Java虚拟机（第2版）</a>：非常优秀且难得的国产佳作，系统的介绍了Java虚拟机和相关工具，并给出了一些调优建议；</li>
<li><a href="http://www.amazon.cn/gp/product/B00E0D2OX4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00E0D2OX4&amp;linkCode=as2&amp;creative=3132">Java程序员修炼之道</a>：在这本书之前，并没有一本Java书籍系统详细的介绍Java 7的新特性（例如新的垃圾收集器，<code>try using</code>结构和<code>invokedynamic</code>指令），这本书填补了这个空白；</li>
<li><a href="http://www.amazon.cn/gp/product/B0077K9XHW/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0077K9XHW&amp;linkCode=as2&amp;creative=3132">Java并发编程实践</a>：系统全面的介绍了Java的并发，如何设计支持并发的数据结构，以及如何编写正确的并发程序；</li>
<li><a href="http://book.douban.com/subject/1328664/">Java Puzzlers</a>：包含了大量的Java陷阱——以至于读这本书时我说的最多的一个词就是WTF，这本书的意义在于它是一个<a href="http://zh.wikipedia.org/wiki/%E5%8F%8D%E9%9D%A2%E6%A8%A1%E5%BC%8F">反模式</a>大全，<a href="http://www.amazon.cn/gp/product/B001PTGR52/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001PTGR52&amp;linkCode=as2&amp;creative=3132">Effective Java</a>告诉你如何写好的Java程序，而<a href="http://book.douban.com/subject/1328664/">Java Puzzlers</a>则告诉你糟糕的Java程序是什么样子。更有意思的是，这两本书的作者都是<a href="http://en.wikipedia.org/wiki/Joshua_Bloch">Joshua Bloch</a>。</li>
</ul>


<h4><a name="csharp">C#</a></h4>

<p><a name="pro_csharp"></a><a href="http://www.amazon.cn/gp/product/B00DVDDP0K/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00DVDDP0K&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/A6lMyB1.jpg" alt="精通C#（第6版）"></a></p>

<p>可能你会疑问我为什么会推荐这本接近1200页的“巨著”用作C#入门，这是我的答案：</p>

<ol>
<li>C#的语言特性非常丰富，很难用简短的篇幅概括这些特性；</li>
<li><a href="http://www.amazon.cn/gp/product/B00DVDDP0K/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00DVDDP0K&amp;linkCode=as2&amp;creative=3132">精通C#</a>之所以有近1200页的篇幅，是因为它不但全面介绍了C#语言，而且还覆盖了ADO.NET，WCF，WF，WPF，以及ASP.NET这些.Net框架。你可以把这本书视为两本书——一本500多页的C#语言教程和一本600多页的.Net平台框架快速上手手册。</li>
<li>尽管标题带有“精通”两字，<a href="http://www.amazon.cn/gp/product/B00DVDDP0K/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00DVDDP0K&amp;linkCode=as2&amp;creative=3132">精通C#</a>实际上是一本面向初学者的C#书籍，你甚至不需要太多编程知识，就可以读懂它。</li>
</ol>


<p><a name="clr_via_csharp"></a><a href="http://www.amazon.cn/gp/product/B00P8VZ8T4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00P8VZ8T4&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/5sEqC1N.jpg" alt="CLR via C#（第4版）"></a></p>

<p><a href="http://www.amazon.cn/gp/product/B00P8VZ8T4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00P8VZ8T4&amp;linkCode=as2&amp;creative=3132">CLR via C#</a>是C#/.Net最重要的书籍，没有之一。它全面介绍了.Net的基石——<a href="http://en.wikipedia.org/wiki/Common_Language_Runtime">CLR</a>的运行原理，以及构建于CLR之上的C#类型系统，运行时关系，泛型，以及线程/并行等高级内容。任何一个以C#为工作内容的程序员都应该阅读此书。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/B00J94AG2A/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00J94AG2A&amp;linkCode=as2&amp;creative=3132">深入理解C#（第3版）</a>：C#进阶必读，这本书偏重于C#的语言特性，它系统的介绍了C#从1.0到C# 4.0的语言特性演化，并展示了如何利用C#的语言特性编写优雅的程序;</li>
<li><a href="http://book.douban.com/subject/4231292/">.NET设计规范（第2版）</a>：C#<strong>专业</strong>程序员必读，从变量命名规范讲到类型系统设计原则，这本书提供了一套完整的.Net编程规范，使得程序员可以编写出一致，严谨的代码，</li>
<li><a href="http://www.amazon.cn/gp/product/B00G51PUDA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00G51PUDA&amp;linkCode=as2&amp;creative=3132">C# 5.0权威指南</a>：来自O’Reilly的C#参考手册，严谨的介绍了C#语法，使用，以及核心类库，C#程序员案头必备；</li>
<li><a href="http://www.amazon.cn/gp/product/0321637003/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0321637003&amp;linkCode=as2&amp;creative=3132">LINQ to Objects Using C# 4.0</a>和<a href="http://www.amazon.cn/gp/product/1449337163/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=1449337163&amp;linkCode=as2&amp;creative=3132">Async in C# 5.0</a>：LINQ和<code>async</code>分别是.Net 3.5和.Net 4.5中所引入的最重要的语言特性，所以我认为有必要在它们上面花点功夫——这两本书是介绍LINQ和<code>async</code>编程的最佳读物。</li>
</ul>


<h4><a name="javascript">JavaScript</a></h4>

<p><a name="js_dom_scripting"></a><a href="http://www.amazon.cn/gp/product/B004VJM5KE/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004VJM5KE&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/xnRA9b6.jpg" alt="JavaScript DOM编程艺术（第2版）"></a></p>

<p>尽管JavaScript现在可以做到客户端服务器端通吃，尽管<a href="http://jquery.com/">JQuery</a>之类的前端框架使得一些人可以不懂JavaScript也可以编程，但我还是认为学习JavaScript从HTML DOM开始最为适合，因为这是JavaScript设计的初衷。<a href="http://www.amazon.cn/gp/product/B004VJM5KE/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004VJM5KE&amp;linkCode=as2&amp;creative=3132">JavaScript DOM编程艺术</a>系统的介绍了如何使用JavaScript，HTML，以及CSS创建可用的Web页面，是一本前端入门佳作。</p>

<p><a name="js_good_parts"></a><a href="http://www.amazon.cn/gp/product/B0097CON2S/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0097CON2S&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/LLq0LC5.jpg" alt="JavaScript语言精粹"></a></p>

<p>JavaScript语言包含大量的陷阱和误区，但它却又有一些相当不错的特性，这也是为什么<a href="http://javascript.crockford.com/">Douglas Crockford</a>称JavaScript为<a href="http://javascript.crockford.com/javascript.html">世界上最被误解的语言</a>，并编写了<a href="http://www.amazon.cn/gp/product/B0097CON2S/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0097CON2S&amp;linkCode=as2&amp;creative=3132">JavaScript语言精粹</a>一书来帮助前端开发者绕开JavaScript中的陷阱。和同类书籍不同，<a href="http://www.amazon.cn/gp/product/B0097CON2S/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0097CON2S&amp;linkCode=as2&amp;creative=3132">JavaScript语言精粹</a>用精炼的语言讲解了JavaScript语言中好的那部分（例如闭包，函数是头等对象，以及对象字面量），并建议读者<strong>不要</strong>使用其它不好的部分（例如混乱的类型转换，默认全局命名空间，以及<a href="https://dorey.github.io/JavaScript-Equality-Table/">奇葩的相等判断符</a>），毕竟，用糟糕的特性编写出来的程序往往也是糟糕的。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/B007OQQVMY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B007OQQVMY&amp;linkCode=as2&amp;creative=3132">JavaScript高级程序设计（第3版）</a>：详尽且深入的介绍了Javascript语言，DOM，以及Ajax，并针对HTML5做了对应更新；</li>
<li><a href="http://www.amazon.cn/gp/product/B007VISQ1Y/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B007VISQ1Y&amp;linkCode=as2&amp;creative=3132">JavaScript权威指南（第6版）</a>：这本书的第5版曾被前端专家<a href="http://javascript.crockford.com/">Douglas Crockford</a>称之为<em>“唯一靠谱的JavaScript书”</em>。相对于<a href="http://www.amazon.cn/gp/product/B007OQQVMY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B007OQQVMY&amp;linkCode=as2&amp;creative=3132">JavaScript高级程序设计</a>，<a href="http://www.amazon.cn/gp/product/B007VISQ1Y/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B007VISQ1Y&amp;linkCode=as2&amp;creative=3132">JavaScript权威指南</a>更像是一本案头参考书，当然如果你感兴趣也可以从头读到尾；</li>
<li><a href="http://www.amazon.cn/gp/product/B00BQ7RMW0/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00BQ7RMW0&amp;linkCode=as2&amp;creative=3132">编写可维护的JavaScript</a>：书如其名，这本书给出了大量的优秀JavaScript编程实践，使得程序员编写出健壮且易于维护的JavaScript代码；</li>
<li><a href="http://www.amazon.cn/gp/product/B00CYM0Z8Y/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00CYM0Z8Y&amp;linkCode=as2&amp;creative=3132">JavaScript异步编程</a>：和常见的支持并发的编程语言（例如Java和C#）不同，JavaScript本身是<strong>单线程</strong>的，因此不能把其它语言处理并发的方式照搬到JavaScript。<a href="http://www.amazon.cn/gp/product/B00CYM0Z8Y/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00CYM0Z8Y&amp;linkCode=as2&amp;creative=3132">JavaScript异步编程</a>系统的介绍了JavaScript中的并发原理，并阐述了如何使用<code>Promise</code>、<code>Deferred</code>以及<code>Async.js</code>编写出简洁高效的异步程序。</li>
</ul>


<h4><a name="python">Python</a></h4>

<p><a name="beginning_python"></a><a href="http://www.amazon.cn/gp/product/B00KAFX65Q/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00KAFX65Q&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/oUHltzm.jpg" alt="Python基础教程（第二版）"></a></p>

<p>Python的入门书籍很多，而且据说质量大多不错，我推荐<a href="http://www.amazon.cn/gp/product/B00KAFX65Q/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00KAFX65Q&amp;linkCode=as2&amp;creative=3132">Python基础教程</a>的原因是因为它是我的Python入门读物——简洁，全面，代码质量很不错，而且有几个很有趣的课后作业，使得我可以快速上手。</p>

<p>这里顺便多说一句，不要用<a href="http://www.amazon.cn/gp/product/B004TUJ7A6/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004TUJ7A6&amp;linkCode=as2&amp;creative=3132">Python学习手册</a>作为Python入门——它的废话实在太多，你能想象它用了15页的篇幅去讲解<code>if</code>语句吗？尽管O’Reilly出了很多经典编程书，但这本<a href="http://www.amazon.cn/gp/product/B004TUJ7A6/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004TUJ7A6&amp;linkCode=as2&amp;creative=3132">Python学习手册</a>绝对不在其中。</p>

<p><a name="python_essential_reference"></a><a href="http://www.amazon.cn/gp/product/B004H0784U/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004H0784U&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/0oznmLb.jpg" alt="Python参考手册（第4版）"></a></p>

<p>权威且实用的Python书籍，覆盖Python 2和Python 3。尽管它名为参考手册，但<a href="http://www.amazon.cn/gp/product/B004H0784U/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004H0784U&amp;linkCode=as2&amp;creative=3132">Python参考手册</a>在Python语法和标准库基础之上对其实现机制也给出了深入的讲解，不容错过。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/B00QT9IA2G/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00QT9IA2G&amp;linkCode=as2&amp;creative=3132">Python袖珍指南（第5版）</a>：实用且便携的Python参考手册，我会说我在飞机上写程序时用的就是它么 –_–#；</li>
<li><a href="http://www.amazon.cn/gp/product/B00IZRMQAM/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00IZRMQAM&amp;linkCode=as2&amp;creative=3132">Python Cookbook（第3版）</a>：非常好的Python进阶读物，包含各种常用场景下的Python代码，使得读者可以写出更加Pythonic的代码；</li>
<li><a href="http://www.amazon.cn/gp/product/B00MHDPIJ6/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00MHDPIJ6&amp;linkCode=as2&amp;creative=3132">Python编程实战：运用设计模式、并发和程序库创建高质量程序</a>：Python高级读物，针对Python 3，2014年的<a href="http://www.drdobbs.com/joltawards/jolt-awards-the-best-books/240169070?pgno=7">Jolt大奖图书</a>，不可错过；</li>
<li><a href="http://book.douban.com/subject/3117898/">Python源码剖析</a>：少见的国产精品，这本书以Python 2.5为例，从源代码出发，一步步分析了CPython是如何实现类型，控制流，函数/方法的声明与调用，类型以及装饰器等Python核心概念，读过之后会大大加深对Python的理解。尽管这本书有些过时，但我们仍然可以按照它分析源代码的方式来分析新版Python。</li>
</ul>


<h3><a name="programming_language_theory">3. 编程语言理论</a></h3>

<p><a name="language_implementation_patterns"></a><a href="http://www.amazon.cn/gp/product/B007HYMPBY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B007HYMPBY&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/SixMs8m.jpg" alt="编程语言实现模式"></a></p>

<p>大多数程序员并不需要从头编写一个编译器或解释器，因此<a href="http://www.amazon.cn/gp/product/B001NGO85I/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001NGO85I&amp;linkCode=as2&amp;creative=3132">龙书（编译原理）</a>就显得过于重量级；然而多数程序员还是需要解析文本，处理配置文件，或者写一个小语言，<a href="http://www.amazon.cn/gp/product/B007HYMPBY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B007HYMPBY&amp;linkCode=as2&amp;creative=3132">编程语言实现模式</a>很好的满足了这个需求。它把常用的文本解析/代码生成方法组织成一个个模式，并为每个模式给出了实例和应用场景。这本书既会提高你的动手能力，也会加深你对编程语言的理解。Python发明者Guido van Rossum甚至为这本书给出了<em>“Throw away your compiler theory book!”</em>这样的超高评价。</p>

<p><a name="plp"></a><a href="http://www.amazon.cn/gp/product/B008FQHHW0/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B008FQHHW0&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/3H08lMv.jpg" alt="程序设计语言——实践之路（第3版）"></a></p>

<p>程序员每天都要和编程语言打交道，但是思考编程语言为什么会被设计成这个样子的程序员并不多，<a href="http://www.amazon.cn/gp/product/B008FQHHW0/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B008FQHHW0&amp;linkCode=as2&amp;creative=3132">程序设计语言——实践之路</a>完美的回答了这个问题。这本书从编程语言的解析和运行开始讲起，系统了介绍了命名空间，作用域，控制流，数据类型以及方法（控制抽象）这些程序设计语言的核心概念，然后展示了这些概念是如何被应用到过程式语言，面向对象语言，函数式语言，脚本式，逻辑编程语言以及并发编程语言这些具有不同编程范式的编程语言之上。这本书或极大的拓宽你的视野——无论你使用什么编程语言，都会从这本书中获益良多。理解这一本书，胜过学习十门新的编程语言。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/B008041DUY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B008041DUY&amp;linkCode=as2&amp;creative=3132">七周七语言：理解多种编程范型</a>：尽管我们在日常工作中可能只使用两三门编程语言，但是了解其它编程语言范式是很重要的。<a href="http://www.amazon.cn/gp/product/B008041DUY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B008041DUY&amp;linkCode=as2&amp;creative=3132">七周七语言</a>一书用精简的篇幅介绍了Ruby，Io，Prolog，Scala，Erlang，Clojure，和Haskell这七种具有不同编程范式的语言——是的，你没法通过这本书变成这七种语言的专家，但你的视野会得到极大的拓宽；</li>
<li><a href="http://www.amazon.cn/gp/product/B00GAUNDYY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00GAUNDYY&amp;linkCode=as2&amp;creative=3132">自制编程语言</a>：另一本优秀的编译原理作品，<a href="http://www.amazon.cn/gp/product/B00GAUNDYY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00GAUNDYY&amp;linkCode=as2&amp;creative=3132">自制编程语言</a>通过从零开始制作一门无类型语言<code>Crowbar</code>和一门静态类型语言<code>Diksam</code>，把类型系统，垃圾回收，和代码生成等编程语言的关键概念讲的清清楚楚；</li>
<li><a href="http://www.amazon.cn/gp/product/B00PG0MM3C/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00PG0MM3C&amp;linkCode=as2&amp;creative=3132">计算的本质：深入剖析程序和计算机</a>：披着Ruby外衣的<a href="http://en.wikipedia.org/wiki/Theory_of_computation">计算理论</a>入门书籍，使你对编程语言的理解更上一层楼。</li>
</ul>


<h3><a name="programming_technique">4. 程序设计</a></h3>

<p><a name="htdp"></a><a href="http://book.douban.com/subject/1140942/"><img src="http://i.imgur.com/ifN25u3.jpg" alt="程序设计方法"></a></p>

<p>现代编程语言的语法大多很繁杂，初学者使用这些语言学习编程会导致花大量的时间在编程语言语法（诸如指针，引用和类型定义）而不是程序设计方法（诸如数据抽象和过程抽象）之上。<a href="http://book.douban.com/subject/1140942/">程序设计方法</a>解决了这个问题——它专注于程序设计方法，使得读者无需把大量时间花在编程语言上。这本书还有一个与之配套的教学开发环境<a href="http://plt-scheme.org/software/drscheme/">DrScheme</a>，这个环境会根据读者的程度变换编程语言的深度，使得读者可以始终把注意力集中在程序设计方法上。</p>

<p>我个人很奇怪<a href="http://book.douban.com/subject/1140942/">程序设计方法</a>这样的佳作为什么会绝版，而谭浩强C语言这样的垃圾却大行其道——好在是程序设计方法<a href="http://www.ccs.neu.edu/home/matthias/HtDP2e/">第二版</a>已经被免费发布在网上。</p>

<p><a name="sicp"></a><a href="http://www.amazon.cn/gp/product/B0011AP7RY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011AP7RY&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/kZZWblP.jpg" alt="计算机程序的构造与解释（第2版）"></a></p>

<p><a href="http://www.amazon.cn/gp/product/B0011AP7RY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011AP7RY&amp;linkCode=as2&amp;creative=3132">计算机程序的构造与解释</a>是另一本被国内大学忽视（至少在我本科时很少有人知道这本书）的教材，这本书和<a href="http://book.douban.com/subject/1140942/">程序设计方法</a>有很多共同点——都使用<a href="http://en.wikipedia.org/wiki/Scheme_(programming_language">Scheme</a>)作为教学语言；都专注于程序设计方法而非编程语言本身；都拥有相当出色的课后题。相对于<a href="http://book.douban.com/subject/1140942/">程序设计方法</a>，<a href="http://www.amazon.cn/gp/product/B0011AP7RY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011AP7RY&amp;linkCode=as2&amp;creative=3132">计算机程序的构造与解释</a>要更加深入程序设计的本质（过程抽象，数据抽象，以及元语言抽象），以至于Google技术总监<a href="http://norvig.com/">Peter Norvig</a>给了这本书<a href="http://www.amazon.com/gp/review/R403HR4VL71K8/ref=cm_cr_pr_rvw_ttl?ie=UTF8&amp;ASIN=0262510871">超高的评价</a>。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/B006P7V73G/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B006P7V73G&amp;linkCode=as2&amp;creative=3132">编程原本</a>：<a href="https://www.sgi.com/tech/stl/">STL</a>作者的关于程序设计方法佳作——他把关系代数和群论引入编程之中，试图为程序设计提供一个坚实的理论基础，从而构建出更加稳固的软件。这本书是<a href="http://book.douban.com/subject/1140942/">程序设计方法</a>和<a href="http://www.amazon.cn/gp/product/B0011AP7RY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011AP7RY&amp;linkCode=as2&amp;creative=3132">计算机程序的构造与解释</a>的绝好补充——前者使用函数式语言（Scheme）讲授程序设计，而<a href="http://www.amazon.cn/gp/product/B006P7V73G/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B006P7V73G&amp;linkCode=as2&amp;creative=3132">编程原本</a>则使用命令式语言（C++）;</li>
<li><a href="http://www.amazon.cn/gp/product/B00LPQ6KAW/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00LPQ6KAW&amp;linkCode=as2&amp;creative=3132">元素模式</a>：<a href="http://www.amazon.cn/gp/product/B001130JN8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001130JN8&amp;linkCode=as2&amp;creative=3132">设计模式</a>总结了<strong>面向对象程序设计</strong>中的模式，而<a href="http://www.amazon.cn/gp/product/B00LPQ6KAW/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00LPQ6KAW&amp;linkCode=as2&amp;creative=3132">元素模式</a>这本书分析了<strong>程序设计</strong>中的常见模式的本质，阅读这本书会让你对程序设计有更深的理解；</li>
<li><a href="http://www.amazon.cn/gp/product/0387964800/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0387964800&amp;linkCode=as2&amp;creative=3132">The Science of Programming</a>：会编程的人很多，但能够编写正确程序的人就少多了。<a href="http://www.amazon.cn/gp/product/0387964800/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0387964800&amp;linkCode=as2&amp;creative=3132">The Science of Programming</a>通过<strong>前条件——不变式——后条件</strong>以及逻辑谓词演算，为编写正确程序提供了强有力的理论基础，然后这本书通过实例阐述了如何应用这些理论到具体程序上。任何一个想大幅提高开发效率的程序员都应阅读此书。</li>
</ul>


<h3><a name="algorithm_data_structure">5. 算法与数据结构</a></h3>

<p><a name="algorithms_4e"></a><a href="http://www.amazon.cn/gp/product/B009OCFQ0O/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B009OCFQ0O&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/vKnkD4B.jpg" alt="算法（第4版）"></a></p>

<p>我在<a href="http://lucida.me/blog/on-learning-algorithms/">算法学习之路</a>一文中提到我的算法入门教材是<a href="http://www.amazon.cn/gp/product/B002WC7NGS/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B002WC7NGS&amp;linkCode=as2&amp;creative=3132">数据结构与算法分析：C语言描述</a>，我曾经认为它是最好的算法入门教材，但自从我读到<a href="http://www.cs.princeton.edu/~rs/">Sedgewick</a>的<a href="http://www.amazon.cn/gp/product/B009OCFQ0O/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B009OCFQ0O&amp;linkCode=as2&amp;creative=3132">算法</a>之后我就改变了观点——这本<a href="http://www.amazon.cn/gp/product/B009OCFQ0O/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B009OCFQ0O&amp;linkCode=as2&amp;creative=3132">算法</a>才是最好的算法入门教材：</p>

<ul>
<li>使用更为容易的Java语言作为教学语言；</li>
<li>覆盖所有常用的数据结构和算法，并均给出其完整实现；</li>
<li>包含大量的图示用于可视化算法——事实上这是我读过的图示最为丰富形象的书籍，这也是我称其为最好的算法入门书籍的原因。</li>
</ul>


<p><a name="programming_pearls"></a><a href="http://www.amazon.cn/gp/product/B00SFZH0DC/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00SFZH0DC&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/uNnVH86.jpg" alt="编程珠玑（第2版）"></a></p>

<p><a href="http://www.amazon.cn/gp/product/B00SFZH0DC/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00SFZH0DC&amp;linkCode=as2&amp;creative=3132">编程珠玑（第2版）</a>是一本少见的实践型算法书籍——它并非一一介绍数据结构/算法的教材，而是实践性极强的算法应用手册。作者（<a href="http://en.wikipedia.org/wiki/Jon_Bentley">Jon Bentley</a>）从他多年的实际经验精选出一些有趣而又实用的问题，然后展示了他解决这些问题的过程（分析问题，选择合适的算法，解决问题，以及验证答案）。任何程序员都可以从中获益。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/B004ZWBW5G/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004ZWBW5G&amp;linkCode=as2&amp;creative=3132">编程珠玑（续）</a>：严格来说这本书并非<a href="http://www.amazon.cn/gp/product/B00SFZH0DC/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00SFZH0DC&amp;linkCode=as2&amp;creative=3132">编程珠玑</a>的续作，而是一本类似于番外篇的编程技巧/实践手册；它不像<a href="http://www.amazon.cn/gp/product/B00SFZH0DC/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00SFZH0DC&amp;linkCode=as2&amp;creative=3132">编程珠玑</a>那般重视算法的应用，而是全面覆盖了程序员所需的能力；</li>
<li><a href="http://www.amazon.cn/gp/product/B00AK7BYJY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00AK7BYJY&amp;linkCode=as2&amp;creative=3132">算法导论（第3版）</a>：尽管我在这边文章开头提到会尽量避免理论性的书籍，但没有<a href="http://www.amazon.cn/gp/product/B00AK7BYJY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00AK7BYJY&amp;linkCode=as2&amp;creative=3132">算法导论</a>的算法阅读列表是不完整的，我想这本书就不需要我多介绍了； :–)</li>
<li><a href="http://www.amazon.cn/gp/product/B00S4HCQUI/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00S4HCQUI&amp;linkCode=as2&amp;creative=3132">算法设计与分析基础（第3版）</a>：侧重于算法设计，这本书创新的把常见算法分为分治，减治，变治三大类，并覆盖了动态规划，回溯，以及分支定界等高级算法设计方法，属于算法设计的入门佳作；</li>
</ul>


<h3><a name="debugging">6. 程序调试</a></h3>

<p><a name="debugging_9_rules"></a><a href="http://www.amazon.cn/gp/product/B00CBBLUFK/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00CBBLUFK&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/x4o6psE.jpg" alt="调试九法——软硬件错误的排查之道"></a></p>

<p>一个让非编程从业人员惊讶的事实是程序员的绝大多时间都花在调试上，而不是写程序上，以至于<a href="http://en.wikipedia.org/wiki/Robert_Cecil_Martin">Bob大叔</a>把<strong>调试时间占工作时间的比例</strong>作为衡量程序员开发能力的标准。<a href="http://www.amazon.cn/gp/product/B00CBBLUFK/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00CBBLUFK&amp;linkCode=as2&amp;creative=3132">调试九法——软硬件错误的排查之道</a>既是调试领域的入门作品，也是必读经典之作。<a href="http://www.amazon.cn/gp/product/B00CBBLUFK/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00CBBLUFK&amp;linkCode=as2&amp;creative=3132">调试九法</a>的作者是一个具有丰富实战经验的硬件工程师，他把他多年的调试经验总结成九条调试法则，并对每一条法则都给对应的实际案例。任何程序员都应通过阅读这本书改善调试效率，即便是非程序员，也可以从这本书中学到系统解决问题的方法。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.com/Writing-Solid-Code-20th-Anniversary/dp/1570740550/">Writing Solid Code</a>：<strong>最好的调试是不调试</strong>——<a href="http://www.amazon.com/Writing-Solid-Code-20th-Anniversary/dp/1570740550/">Writing Solid Code</a>介绍了断言，设计清晰的API，以及单步代码等技巧，用于编写健壮的代码，减少调试的时间；</li>
<li><a href="http://www.amazon.cn/gp/product/B00IOAM6VE/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00IOAM6VE&amp;linkCode=as2&amp;creative=3132">软件调试的艺术</a>：调试工具书——这本书详细的介绍了常见的调试器工具，并通过具体案例展示了它们的使用技巧；</li>
</ul>


<h2>软件开发</h2>

<h3><a name="programming_practice">1. 编程实践</a></h3>

<p><a name="the_programming_practice"></a><a href="http://book.douban.com/subject/1173548/"><img src="http://i.imgur.com/dUBXTog.jpg" alt="程序设计实践"></a></p>

<p><a href="http://en.wikipedia.org/wiki/Brian_Kernighan">Brian Kernighan</a>是这个星球上最好的计算机书籍作者：从上古时期的<a href="http://www.amazon.cn/gp/product/020103669X/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=020103669X&amp;linkCode=as2&amp;creative=3132">Software Tools</a>，到早期的<a href="http://www.amazon.cn/gp/product/B00IYTQBYS/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00IYTQBYS&amp;linkCode=as2&amp;creative=3132">Unix编程环境</a>和<a href="http://www.amazon.cn/gp/product/B0011425T8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011425T8&amp;linkCode=as2&amp;creative=3132">C程序设计语言</a>，再到这本<a href="http://book.douban.com/subject/1173548/">程序设计实践</a>，每本书都是<strong>必读</strong>之作。</p>

<p>尽管程序设计实践只有短短200余页，但它使用精炼的代码和简要的原则覆盖了程序设计的所有关键概念（包括编程风格，算法与数据结构，API设计，调试，测试，优化，移植，以及领域特定语言等概念）。如果你想快速掌握良好的编程实践，或者你觉着900多页的<a href="http://www.amazon.cn/gp/product/B0061XKRXA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0061XKRXA&amp;linkCode=as2&amp;creative=3132">代码大全</a>过于沉重，那么程序设计实践是你的不二之选。我第一次读这本书就被它简洁的语言和优雅的代码所吸引，以至于读研时我买了三本程序设计实践——一本放在学校实验室，一本放在宿舍，一本随身携带阅读。我想我至少把它读了十遍以上——每一次都有新的收获。</p>

<p><a name="code_complete"></a><a href="http://www.amazon.cn/gp/product/B0061XKRXA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0061XKRXA&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/d09nO65.jpg" alt="代码大全（第2版）"></a></p>

<p>无论在哪个版本的程序员必读书单，<a href="http://www.amazon.cn/gp/product/B0061XKRXA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0061XKRXA&amp;linkCode=as2&amp;creative=3132">代码大全</a>都会高居首位。和其它程序设计书籍不同，<a href="http://www.amazon.cn/gp/product/B0061XKRXA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0061XKRXA&amp;linkCode=as2&amp;creative=3132">代码大全</a>用通俗清晰的语言覆盖了软件构建（Software Construction）中各个层次上<strong>所有</strong>的重要概念——从变量命名到类型设计，从控制循环到代码结构，从测试和调试到构建和集成，<a href="http://www.amazon.cn/gp/product/B0061XKRXA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0061XKRXA&amp;linkCode=as2&amp;creative=3132">代码大全</a>可谓无所不包，你可以把这本书看作为程序员的一站式（Once and for all）阅读手册。更珍贵的是，<a href="http://www.amazon.cn/gp/product/B0061XKRXA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0061XKRXA&amp;linkCode=as2&amp;creative=3132">代码大全</a>在每一章末尾都给出了价值很高的参考书目（参考我之前的<a href="http://lucida.me/blog/on-reading-books/">如何阅读书籍</a>一文），如果你是一个初出茅庐的程序员，<a href="http://www.amazon.cn/gp/product/B0061XKRXA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0061XKRXA&amp;linkCode=as2&amp;creative=3132">代码大全</a>是绝好的阅读起点。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/B008B4DTG4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B008B4DTG4&amp;linkCode=as2&amp;creative=3132">编写可读代码的艺术</a>：专注于代码可读性（Code Readability），这本书来自Google的两位工程师对<a href="http://www.quora.com/What-is-Googles-internal-code-review-policy-process">Google Code Readability</a>的总结。它给出了大量命名，注释，代码结构，以及API设计等日常编码的最佳实践，并包含了很多看似细微但却可以显著提升代码可读性的编程技巧。这本书的翻译还不错，但如果你想体会书中的英语幽默（例如Tyrannosaurus——Stegosaurus——Thesaurus），建议阅读它的<a href="http://www.amazon.cn/gp/product/B008IBND20/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B008IBND20&amp;linkCode=as2&amp;creative=3132">英文影印版</a>；</li>
<li><a href="http://www.amazon.cn/gp/product/B001XCWFOI/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001XCWFOI&amp;linkCode=as2&amp;creative=3132">卓有成效的程序员</a>：专注于生产效率（Productivity），它既包含源自作者多年经验的高生产率原则，也包含大量的提高生产率的小工具，每个追求高生产率的程序员都应该阅读这本书；</li>
<li><a href="http://www.amazon.cn/gp/product/B008Z1IEQ8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B008Z1IEQ8&amp;linkCode=as2&amp;creative=3132">UNIX编程艺术</a>：专注于程序设计哲学，这本书首先总结出包括模块化，清晰化，可组合，可分离等17个Unix程序设计哲学，接下来通过Unix历史以及各种Unix编程工具展示了这些原则的应用。尽管个人觉的这本书有些过度拔高Unix且过度贬低Windows和M$，但书中的Unix设计哲学非常值得借鉴。</li>
</ul>


<h3><a name="oop">2. 面向对象程序设计</a></h3>

<p><a name="head_first_design_patterns"></a><a href="http://www.amazon.cn/gp/product/B0011FBU34/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011FBU34&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/4EWfMHV.jpg" alt="Head First设计模式"></a></p>

<p>无论是在Amazon还是在Google上搜索设计模式相关书籍，<a href="http://www.amazon.cn/gp/product/B0011FBU34/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011FBU34&amp;linkCode=as2&amp;creative=3132">Head First设计模式</a>都会排在首位——它使用风趣的语言和诙谐的图示讲述了观察者，装饰者，抽象工厂，和单例等关键设计模式，使得初学者可以迅速的理解并掌握设计模式。<a href="http://www.amazon.cn/gp/product/B0011FBU34/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011FBU34&amp;linkCode=as2&amp;creative=3132">Head First设计模式</a>在Amazon上<a href="http://www.amazon.com/Head-First-Design-Patterns-Freeman/product-reviews/0596007124/">好评如潮</a>，就连设计模式原书作者<a href="http://en.wikipedia.org/wiki/Erich_Gamma">Erich Gamma</a>都对它给出了很高的评价。</p>

<p>需要注意，<a href="http://www.amazon.cn/gp/product/B0011FBU34/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011FBU34&amp;linkCode=as2&amp;creative=3132">Head First设计模式</a>是非常好的设计模式入门书，但<strong>千万不要</strong>把这本书作为学习设计模式的唯一的书——是的，Head First设计模式拥有风趣的语言和诙谐的例子，但它既缺乏<strong>实际</strong>的工程范例，也没有给出设计模式的应用/适用场景。我个人建议是在读过这本书之后立即阅读<a href="http://en.wikipedia.org/wiki/Gang_of_Four_(disambiguation">“四人帮”</a>)的<a href="http://www.amazon.cn/gp/product/B001130JN8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001130JN8&amp;linkCode=as2&amp;creative=3132">设计模式</a>或<a href="http://en.wikipedia.org/wiki/Robert_Cecil_Martin">Bob大叔</a>的<a href="http://www.amazon.cn/gp/product/B00116MMA8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00116MMA8&amp;linkCode=as2&amp;creative=3132">敏捷软件开发</a>，以便理解设计模式在实际中的应用。</p>

<p><a name="design_patterns"></a><a href="http://www.amazon.cn/gp/product/B001130JN8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001130JN8&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/okXMrxW.jpg" alt="设计模式"></a></p>

<p><a href="http://www.amazon.cn/gp/product/B001130JN8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001130JN8&amp;linkCode=as2&amp;creative=3132">设计模式</a>作为设计模式领域的开山之作，Erich Gamma，Richard Helm，Ralph Johnson等四位作者将各个领域面向对象程序开发的经验总结成三大类23种模式，并给出了每个模式的使用场景，变体，不足，以及如何克服这些不足。这本书行文严谨紧凑（四位作者都是PhD），并且代码源自实际项目，属于设计模式领域的必读之作。</p>

<p>需要注意：<a href="http://www.amazon.cn/gp/product/B001130JN8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001130JN8&amp;linkCode=as2&amp;creative=3132">设计模式</a><strong>不适合</strong>初学者阅读——它更像是一篇博士论文而非技术书籍，加上它的范例都具有很强的领域背景（诸如GUI窗口系统和富文本编辑器），缺乏实际经验的程序员很难理解这本书。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/B00116MMA8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00116MMA8&amp;linkCode=as2&amp;creative=3132">敏捷软件开发（原则模式与实践）</a>：尽管标题带有“敏捷”，但这本书实际是一本面向对象程序设计读物——<a href="http://en.wikipedia.org/wiki/Robert_Cecil_Martin">Bob大叔</a>通过丰富的例子讲解设计模式的应用和<a href="http://en.wikipedia.org/wiki/SOLID_(object-oriented_design">SOLID面向对象设计原则</a>)，如果你觉着<a href="http://www.amazon.cn/gp/product/B001130JN8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001130JN8&amp;linkCode=as2&amp;creative=3132">设计模式</a>过于晦涩，那么你完全可以从这本书开始学习。这本书使用Java作为讲解语言，它也有对应的<a href="http://www.amazon.cn/gp/product/B00ACXX034/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00ACXX034&amp;linkCode=as2&amp;creative=3132">C#版本</a>；</li>
<li><a href="http://www.amazon.cn/gp/product/B0031M9GHC/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0031M9GHC&amp;linkCode=as2&amp;creative=3132">代码整洁之道</a>：同样是<a href="http://en.wikipedia.org/wiki/Robert_Cecil_Martin">Bob大叔</a>的作品，这本书教导读者使用面向对象+敏捷开发原则编写清晰可维护的代码；</li>
<li><a href="http://www.amazon.cn/gp/product/B003LBSRDM/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B003LBSRDM&amp;linkCode=as2&amp;creative=3132">企业应用架构模式</a>：这本书专注于架构，作者<a href="http://en.wikipedia.org/wiki/Martin_Fowler">Martin Fowler</a>针对企业应用的特点（诸如持久化数据，多人访问，操作数据的界面以及复杂的业务逻辑），总结出若干企业架构模式，以便程序员构建强大且可扩展的企业应用。</li>
</ul>


<h3><a name="refactoring">3. 重构</a></h3>

<p><a name="refactoring_book"></a><a href="http://book.douban.com/subject/4262627/"><img src="http://i.imgur.com/F6GCcGr.jpg" alt="重构"></a></p>

<p>任何产品代码都不是一蹴而就，而是在反复不断的修改中进化而来。<a href="http://book.douban.com/subject/4262627/">重构</a>正是这样一本介绍如何改进代码的书籍——如何在保持代码行为的基础上，提升代码的质量（这也是重构的定义）。</p>

<p>我见过很多程序员，他们经常声称自己在重构代码，但他们实际只做了第二步（提升代码的质量），却没有保证第一步（保持代码行为），因此他们所谓的重构往往会适得其反——破坏现有代码或是引入新bug。这也是我推荐<a href="http://book.douban.com/subject/4262627/">重构</a>这本书的原因——它既介绍糟糕代码的特征（Bad smell）和改进代码的方法，也给出了重构的完整流程——1. 编写单元测试保持（Preserve）程序行为；2. 重构代码；3. 保证单元测试通过。<a href="http://book.douban.com/subject/4262627/">重构</a>还引入了一套重构术语（诸如封装字段，内联方法，和字段上移），以便程序员之间交流。只有理解了这三个方面，才能算是理解重构。</p>

<p><a name="working_effectively_with_legacy_code"></a><a href="http://www.amazon.cn/gp/product/B00KMJ2Q1U/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00KMJ2Q1U&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/guFET2p.jpg" alt="修改代码的艺术"></a></p>

<p>这里再重复一遍重构的定义——<strong>在保持代码行为的基础上，提升代码的质量。</strong><a href="http://book.douban.com/subject/4262627/">重构</a>专注于第二步，即如何提升代码的质量，而<a href="http://www.amazon.cn/gp/product/B00KMJ2Q1U/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00KMJ2Q1U&amp;linkCode=as2&amp;creative=3132">修改代码的艺术</a>专注于第一步，即如何保持代码的行为。</p>

<p>提升代码质量并不困难，但保持代码行为就难多了，尤其是对没有测试的遗留代码（Legacy Code）而言——你需要首先引入测试，但遗留代码往往可测试性（Testability）很差，这时你就需要把代码变的可测试。<a href="http://www.amazon.cn/gp/product/B00KMJ2Q1U/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00KMJ2Q1U&amp;linkCode=as2&amp;creative=3132">修改代码的艺术</a>包含大量的实用建议，用来把代码变的可测试（Testable），从而使重构变为可能，使提高代码质量变为可能。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/B00A9YD7A2/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00A9YD7A2&amp;linkCode=as2&amp;creative=3132">重构与模式</a>：这本书的中文书名存在误导，它的原书书名是Refactoring to Patterns——通过重构，把模式引入代码。这本书阐述了重构和设计模式之间的关系，使得程序员可以在更高的层次上思考重构，进行重构。</li>
</ul>


<h3><a name="software_testing">4. 软件测试</a></h3>

<p><a name="how_to_break_software"></a><a href="http://www.amazon.cn/gp/product/0201796198/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0201796198&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/8Jy3C0g.jpg" alt="How to Break Software"></a></p>

<p>关于软件测试的书籍很多，但很少有一本测试书籍能像<a href="http://www.amazon.cn/gp/product/0201796198/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0201796198&amp;linkCode=as2&amp;creative=3132">How to Break Software</a>这般既有趣又实用。不同于传统的软件测试书籍（往往空话连篇，无法直接应用），<a href="http://www.amazon.cn/gp/product/0201796198/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0201796198&amp;linkCode=as2&amp;creative=3132">How to Break Software</a>非常实际——它从程序员的心理出发，分析软件错误/Bug最可能产生的路径，然后针对这些路径进行<strong>残酷</strong>的测试，以保证软件质量。</p>

<p>我在第一次阅读这本书时大呼作者太过“残忍”——连这些刁钻诡异的测试招数都能想出来。但这种毫不留情（Relentless）的测试风格正是每个专业程序员所应具备的心态。</p>

<p><strong>注意</strong>：如果你是一个测试工程师，那么在阅读这本书前请三思——因为阅读它之后你会让你身边的程序员苦不堪言，甚至连掐死你的心都有 :-D。</p>

<p><a name="xunit_test_patterns"></a><a href="http://www.amazon.cn/gp/product/0131495054/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0131495054&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/eHxp0PG.jpg" alt="xUnit Test Patterns"></a></p>

<p><a href="http://www.amazon.cn/gp/product/0201796198/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0201796198&amp;linkCode=as2&amp;creative=3132">How to Break Software</a>注重黑盒测试，而这本<a href="http://www.amazon.cn/gp/product/0131495054/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0131495054&amp;linkCode=as2&amp;creative=3132">xUnit Test Patterns</a>则注重白盒测试。正如书名所示，<a href="http://www.amazon.cn/gp/product/0131495054/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0131495054&amp;linkCode=as2&amp;creative=3132">xUnit Test Patterns</a>覆盖了单元测试的每个方面：从如何编写良好的单元测试，到如何设计可测试（Testable）的软件，再到如何重构测试——可以把它看作为单元测试的百科全书。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.com/Practical-Unit-Testing-JUnit-Mockito/dp/8393489393/">Practical Unit Testing with JUnit and Mockito</a>：尽管<a href="http://www.amazon.cn/gp/product/0131495054/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0131495054&amp;linkCode=as2&amp;creative=3132">xUnit Test Patterns</a>覆盖了单元测试的方方面面，但它的问题在于不够与时俱进（07年出版）。<a href="http://www.amazon.com/Practical-Unit-Testing-JUnit-Mockito/dp/8393489393/">Practical Unit Testing</a>弥补了这个缺陷——它详细介绍了如何通过测试框架<a href="http://junit.org/">JUnit</a>和Mock框架<a href="http://code.google.com/p/mockito/">Mockito</a>编写良好的单元测试，并给出了大量优秀单元测试的原则；</li>
<li><a href="http://www.amazon.cn/gp/product/B00MBQMFLI/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00MBQMFLI&amp;linkCode=as2&amp;creative=3132">单元测试的艺术（第2版）</a>：可以把这本书看作为前一本书的.Net版，适合.Net程序员；</li>
<li><a href="http://www.amazon.cn/gp/product/B00FH36R6G/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00FH36R6G&amp;linkCode=as2&amp;creative=3132">Google软件测试之道</a>：这本书详细介绍了Google如何测试软件——包括Google的软件测试流程以及Google软件测试工程师的日常工作/职业发展。需要注意的是：这本书中的测试流程在国内很可能行不通（国内企业缺乏像Google那般强大的基础设施（Infrastructure）），但它至少可以让国内企业有一个可以效仿的目标；</li>
<li><a href="http://www.amazon.cn/gp/product/B003JBIV0S/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B003JBIV0S&amp;linkCode=as2&amp;creative=3132">探索式软件测试</a>：<a href="http://blogs.msdn.com/b/jw_on_tech/">James Whittaker</a>的另一本测试著作，不同于传统的黑盒/白盒测试，这本书创造性的把测试比喻为“探索”（Exploration），然后把不同的探索方式对应到不同的测试方式上，以便尽早发现更多的软件错误/Bug。</li>
</ul>


<h3><a name="project_management">5. 项目管理</a></h3>

<p><a name="team_geek"></a><a href="http://www.amazon.cn/gp/product/B00BLZMG8W/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00BLZMG8W&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/Z5spMnq.jpg" alt="极客与团队"></a></p>

<p>很多程序员都向往成为横扫千军（One-man Army）式的“编程英雄”，但卓越的软件并非一人之力，而是由团队合力而成。<a href="http://www.amazon.cn/gp/product/B00BLZMG8W/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00BLZMG8W&amp;linkCode=as2&amp;creative=3132">极客与团队</a>就是这样一本写给程序员的如何在团队中工作的绝好书籍，它围绕着HRT三大原则（Humility谦逊，Respect尊重，和Trust信任），系统的介绍了如何融入团队，如何打造优秀的团队，如何领导团队，以及如何应对团队中的害群之马（Poisonous People）。这本书实用性极强，以至于Python之父<a href="http://en.wikipedia.org/wiki/Guido_van_Rossum">Guido van Rossum</a>都盛赞这本书<em>“说出了我一直在做但总结不出来的东西”</em>。</p>

<p><a name="mythical_man_month"></a><a href="http://www.amazon.cn/gp/product/B0011C2P7W/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011C2P7W&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/6t9kqTI.jpg" alt="人月神话"></a></p>

<p>尽管<a href="http://www.amazon.cn/gp/product/B0011C2P7W/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011C2P7W&amp;linkCode=as2&amp;creative=3132">人月神话</a>成书于40年前，但它仍是软件项目管理<strong>最</strong>重要的书籍。<a href="http://www.amazon.cn/gp/product/B0011C2P7W/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011C2P7W&amp;linkCode=as2&amp;creative=3132">人月神话</a>源自作者<a href="http://en.wikipedia.org/wiki/Fred_Brooks">Fred Brooks</a>领导并完成<a href="http://en.wikipedia.org/wiki/IBM_System/360">System/360</a>和<a href="http://en.wikipedia.org/wiki/OS/360_and_successors">OS/360</a>这两个即是放到现在也是巨型软件项目的里程碑项目的经验总结。它覆盖了软件项目各个方面的关键概念：从工期管理（<a href="http://en.wikipedia.org/wiki/Brooks%27s_law">Brooks定律</a>）到团队建设（<a href="http://en.wikipedia.org/wiki/The_Mythical_Man-Month#The_surgical_team">外科团队</a>），从程序设计（编程的本质是使用正确的数据结构）到架构设计（<a href="http://en.wikipedia.org/wiki/The_Mythical_Man-Month#Conceptual_integrity">概念完整性</a>），从原型设计（Plan to Throw one away）到团队交流（形式化文档+会议）。令人惊讶的是，即便40年之后，<a href="http://www.amazon.cn/gp/product/B0011C2P7W/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011C2P7W&amp;linkCode=as2&amp;creative=3132">人月神话</a>中的关键概念（包括焦油坑，<a href="http://en.wikipedia.org/wiki/Brooks%27s_law">Brooks定律</a>，<a href="http://en.wikipedia.org/wiki/The_Mythical_Man-Month#Conceptual_integrity">概念完整性</a>，<a href="http://en.wikipedia.org/wiki/The_Mythical_Man-Month#The_surgical_team">外科团队</a>，<a href="http://en.wikipedia.org/wiki/The_Mythical_Man-Month#The_second-system_effect">第二版效应</a>等等）依然适用，而软件开发的<a href="http://en.wikipedia.org/wiki/Essential_complexity">核心复杂度</a>仍然没有得到解决（<a href="http://en.wikipedia.org/wiki/The_Mythical_Man-Month#No_silver_bullet">没有银弹</a>）。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/B00MO7R1SG/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00MO7R1SG&amp;linkCode=as2&amp;creative=3132">人件（原书第3版）</a>：从人的角度分析软件项目。<a href="http://www.amazon.cn/gp/product/B00MO7R1SG/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00MO7R1SG&amp;linkCode=as2&amp;creative=3132">人件</a>从雇佣正确的人，创建健康的工作环境，以及打造高效的开发团队等角度阐述了如何改善人，从而改善软件项目；</li>
<li><a href="http://www.amazon.cn/gp/product/B00CBBKRQ8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00CBBKRQ8&amp;linkCode=as2&amp;creative=3132">门后的秘密：卓越管理的故事</a>：这本书生动的再现了软件项目管理工作的场景，并给出了各种实用管理技巧，如果你有意转向管理岗位，这本书不容错过；</li>
<li><a href="http://www.amazon.cn/gp/product/B00KQDTZ4S/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00KQDTZ4S&amp;linkCode=as2&amp;creative=3132">大教堂与集市</a>：这本书从黑客的历史说起，系统而又风趣的讲述了开源运动的理论和实践，以及开源软件项目是如何运作并发展的。了解开源，从这本书开始。</li>
</ul>


<h3><a name="professional_developing">6. 专业开发</a></h3>

<p><a name="the_pragmatic_programmer"></a><a href="http://www.amazon.cn/gp/product/B004GV08CY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004GV08CY&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/2gi4sTz.jpg" alt="程序员修炼之道：从小工到专家"></a></p>

<p>不要被庸俗的译名迷惑，<a href="http://www.amazon.cn/gp/product/B004GV08CY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004GV08CY&amp;linkCode=as2&amp;creative=3132">程序员修炼之道</a>是一本价值极高的程序员成长手册。这本书并不局限于特定的编程语言或框架，而是提出了一套切实可行的实效（Pragmatic）开发哲学，并通过程序设计，测试，编程工具，以及项目管理等方面的实例展示了如何应用这套开发哲学，从而使得程序员更加高效专业。有人把这本书称之为迷你版<a href="http://www.amazon.cn/gp/product/B0061XKRXA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0061XKRXA&amp;linkCode=as2&amp;creative=3132">代码大全</a>——<a href="http://www.amazon.cn/gp/product/B0061XKRXA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0061XKRXA&amp;linkCode=as2&amp;creative=3132">代码大全</a>给出了大量的优秀程序设计实践，偏向术；而<a href="http://www.amazon.cn/gp/product/B004GV08CY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004GV08CY&amp;linkCode=as2&amp;creative=3132">程序员修炼之道</a>给出了程序设计实践背后的思想，注重道。</p>

<p><a name="clean_coder"></a><a href="http://www.amazon.cn/gp/product/B0098NRHHY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0098NRHHY&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/s0Hbcax.jpg" alt="程序员职业素养"></a></p>

<p><a href="http://www.amazon.cn/gp/product/B004GV08CY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004GV08CY&amp;linkCode=as2&amp;creative=3132">程序员修炼之道</a>指出了<strong>如何</strong>成为专业程序员，这本<a href="http://www.amazon.cn/gp/product/B0098NRHHY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0098NRHHY&amp;linkCode=as2&amp;creative=3132">程序员职业素养</a>则指出了专业程序员应该是<strong>什么</strong>样子——承担责任；知道自己在做什么；知道何时说不/何时说是；在正确的时间编写正确的代码；懂得自我时间管理和工期预估；知道如何应对压力。如果你想成为专业程序员（Professional Developer）（而不是码农（Code Monkey）），这本书会为你指明前进的方向。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/B00OA9L3NU/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00OA9L3NU&amp;linkCode=as2&amp;creative=3132">高效程序员的45个习惯</a>：“敏捷”版的<a href="http://www.amazon.cn/gp/product/B004GV08CY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004GV08CY&amp;linkCode=as2&amp;creative=3132">程序员修炼之道</a>，可以把这本书作为<a href="http://www.amazon.cn/gp/product/B004GV08CY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004GV08CY&amp;linkCode=as2&amp;creative=3132">程序员修炼之道</a>的补充；</li>
<li><a href="http://www.amazon.cn/gp/product/B008MIFWJG/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B008MIFWJG&amp;linkCode=as2&amp;creative=3132">精益创业</a>：尽管这是一本讲如何创业的书，但其中的精益生产，最小价值产品，以及构建-度量-学习循环都值得程序员借鉴。</li>
</ul>


<h3><a name="master_saying">7. 大师之言</a></h3>

<p><a name="out_of_their_minds"></a><a href="http://www.amazon.cn/gp/product/B007ED88CI/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B007ED88CI&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/zvIzokH.jpg" alt="奇思妙想：15位计算机天才及其重大发现"></a></p>

<p><a href="http://www.amazon.cn/gp/product/B007ED88CI/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B007ED88CI&amp;linkCode=as2&amp;creative=3132">奇思妙想：15位计算机天才及其重大发现</a>是一本极具眼光的技术访谈书籍——在这本书访谈的15位计算机科学家中，竟出现了12位<a href="http://zh.wikipedia.org/wiki/%E5%9B%BE%E7%81%B5%E5%A5%96">图灵奖</a>获得者——要知道图灵奖从1966年设奖到现在也只有六十几位获奖者而已。</p>

<p><a href="http://www.amazon.cn/gp/product/B007ED88CI/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B007ED88CI&amp;linkCode=as2&amp;creative=3132">奇思妙想</a>把计算机科学分为四大领域：编程语言；算法；架构；人工智能。并选取了每个领域下最具代表性的计算机科学家进行访谈。因为这些计算机科学家都是其所在领域的开拓者，因此他们能给出常人无法给出的深刻见解。通过这本书，你可以了解前三十年的计算机科学的发展历程——计算机科学家做了什么，而计算机又能做到/做不到什么。从而避免把时间浪费在前人已经解决的问题（或者根本无法解决的问题）上面。</p>

<p><a name="coders_at_work"></a><a href="http://www.amazon.cn/gp/product/B00QA7GA2Y/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00QA7GA2Y&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/hdakKdE.jpg" alt="编程人生：15位软件先驱访谈录"></a></p>

<p>同样是访谈录，同样访谈15个人，<a href="http://www.amazon.cn/gp/product/B00QA7GA2Y/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00QA7GA2Y&amp;linkCode=as2&amp;creative=3132">编程人生</a>把重点放在程序员（Coders at work）上。它从各个领域选取了15位顶尖的程序员，这些程序员既包括<a href="http://en.wikipedia.org/wiki/Ken_Thompson">Ken Thompson</a>和<a href="http://en.wikipedia.org/wiki/Jamie_Zawinski">Jamie Zawinski</a>这些老牌Unix黑客，也包括<a href="http://en.wikipedia.org/wiki/Brad_Fitzpatrick">Brad Fitzpatrick</a>这样的80后新生代，还包括<a href="http://en.wikipedia.org/wiki/Frances_E._Allen">Frances Allen</a>和<a href="http://en.wikipedia.org/wiki/Donald_Knuth">Donald Knuth</a>这样的计算机科学家。这种多样性（Diversity）使得<a href="http://www.amazon.cn/gp/product/B00QA7GA2Y/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00QA7GA2Y&amp;linkCode=as2&amp;creative=3132">编程人生</a>兼具严谨性和趣味性，无论你是什么类型的程序员，都能从中受益良多。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/B008G80O9K/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B008G80O9K&amp;linkCode=as2&amp;creative=3132">图灵和ACM图灵奖（1966-2011）</a>：通过图灵奖介绍整个计算机科学发展史，非常难得的国产精品图书；</li>
<li><a href="http://www.amazon.cn/gp/product/B00ALPRKMA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00ALPRKMA&amp;linkCode=as2&amp;creative=3132">编程大师访谈录</a>：可以把这本书看作为二十年前的<a href="http://www.amazon.cn/gp/product/B00QA7GA2Y/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00QA7GA2Y&amp;linkCode=as2&amp;creative=3132">编程人生</a>，被访谈者都是当时叱咤风云的人物（例如微软的创造者<a href="http://en.wikipedia.org/wiki/Bill_Gates">Bill Gates</a>，Macintosh的发明者<a href="http://en.wikipedia.org/wiki/Jef_Raskin">Jeff Raskin</a>，以及Adobe的创始人<a href="http://en.wikipedia.org/wiki/John_Warnock">John Warnock</a>等等）。有趣的是这本书中大量的经验和建议到如今依然适用；</li>
<li><a href="http://www.amazon.cn/gp/product/B00451BP72/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00451BP72&amp;linkCode=as2&amp;creative=3132">编程大师智慧</a>：类似于<a href="http://www.amazon.cn/gp/product/B00QA7GA2Y/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00QA7GA2Y&amp;linkCode=as2&amp;creative=3132">编程人生</a>，不同的是被访谈者都是编程语言的设计者——这本书覆盖了除C语言以外的几乎所有主流编程语言。通过这本书，你可以从中学到编程语言背后的设计思想——编程语言为什么要被设计成这样，是什么促使设计者要在语言中加入这个特性（或拒绝那个特性）。从而提升对编程语言的理解。</li>
</ul>


<h3><a name="interface_design">8. 界面设计</a></h3>

<p><a name="non_designer_design_book"></a><a href="http://www.amazon.cn/gp/product/B00KQBLI5E/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00KQBLI5E&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/Hr65W4l.jpg" alt="写给大家看的设计书"></a></p>

<p>书如其名，<a href="http://www.amazon.cn/gp/product/B00KQBLI5E/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00KQBLI5E&amp;linkCode=as2&amp;creative=3132">写给大家看的设计书</a>是一本面向初学者的快速设计入门。它覆盖了版式，色彩，和字体这三个设计中的关键元素，并创造性的为版式设计总结出CRAP四大原则（Contrast对比，Repetition重复，Alignment对齐，Proximity亲密）。全书使用丰富生动的范例告诉读者什么是好的设计，什么是不好的设计，使得即便是对设计一无所知的人，也可以从这本书快速入门。</p>

<p><a name="design_with_mind_in_mind"></a><a href="http://www.amazon.cn/gp/product/B00MFHRAK4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00MFHRAK4&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/P9U10qJ.jpg" alt="认知与设计：理解UI设计准则（第2版）"></a></p>

<p><a href="http://www.amazon.cn/gp/product/B00KQBLI5E/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00KQBLI5E&amp;linkCode=as2&amp;creative=3132">写给大家看的设计书</a>强调实践，即<strong>如何</strong>做出好的设计；<a href="http://www.amazon.cn/gp/product/B00MFHRAK4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00MFHRAK4&amp;linkCode=as2&amp;creative=3132">认知与设计：理解UI设计准则</a>强调理论，即<strong>为什么</strong>我们会接受这样的设计而反感那样的设计。如果你想要搞清楚设计背后的心理学知识，但又不想阅读大部头的心理学著作，那么<a href="http://www.amazon.cn/gp/product/B00MFHRAK4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00MFHRAK4&amp;linkCode=as2&amp;creative=3132">认知与设计</a>是你的首选。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/0123706432/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0123706432&amp;linkCode=as2&amp;creative=3132">GUI设计禁忌 2.0</a>：这本书指出了GUI设计的原则和常见误区，然后通过具体范例指出了如何避免这些误区。如果你的工作涉及到用户界面，那么这本书会为你减少很多麻烦；</li>
<li><a href="http://www.amazon.cn/gp/product/B00EV562SY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00EV562SY&amp;linkCode=as2&amp;creative=3132">界面设计模式（第2版）</a>：这本书将用户界面中的常见元素/行为组织成彼此关联的模式，以便读者理解并举一反三，从而将其运用到自己的应用中；</li>
<li><a href="http://www.amazon.cn/gp/product/B00SFZGX08/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00SFZGX08&amp;linkCode=as2&amp;creative=3132">移动应用UI设计模式</a>：类似于<a href="http://www.amazon.cn/gp/product/B00EV562SY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00EV562SY&amp;linkCode=as2&amp;creative=3132">界面设计模式</a>，但面向移动平台。它给出了iOS，Android，以及Windows Phones上常用的90余种界面设计模式，从而使得你不必把这些平台的应用挨个玩一遍也可以掌握各个平台的设计精髓。如果你主攻Android平台，那么<a href="http://www.amazon.cn/gp/product/B00GU73RHA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00GU73RHA&amp;linkCode=as2&amp;creative=3132">Android应用UI设计模式</a>会是更好的选择；</li>
<li><a href="http://www.amazon.cn/gp/product/B0030IMDUY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0030IMDUY&amp;linkCode=as2&amp;creative=3132">配色设计原理</a>和<a href="http://www.amazon.cn/gp/product/B0011C25KY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011C25KY&amp;linkCode=as2&amp;creative=3132">版式设计原理</a>：如果你读过<a href="http://www.amazon.cn/gp/product/B00KQBLI5E/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00KQBLI5E&amp;linkCode=as2&amp;creative=3132">写给大家看的设计书</a>之后想继续深入学习设计，这两本书是不错的起点。</li>
</ul>


<h3><a name="interaction_design">9. 交互设计</a></h3>

<p><a name="universal_design_principles"></a><a href="http://www.amazon.cn/gp/product/B00ES8JL8W/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00ES8JL8W&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/ksNw2bM.jpg" alt="通用设计法则"></a></p>

<p>书如其名，<a href="http://www.amazon.cn/gp/product/B00ES8JL8W/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00ES8JL8W&amp;linkCode=as2&amp;creative=3132">通用设计法则</a>给出了重要的125个设计原则，并用简练的语言和范例展示了这些原则的实际应用。每个原则都有对应的参考文献，以便读者进一步学习。我之所以推荐这本书，是因为：1. 程序员需要对设计有全面的认识；2. 程序员并不需要知道这些设计原则是怎么来的，知道怎么用即可。这本书很好的满足了这两个要求。</p>

<p><a name="about_face"></a><a href="http://www.amazon.cn/gp/product/B007Q2XXXG/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B007Q2XXXG&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/gObk7fx.jpg" alt="交互设计精髓（第3版）"></a></p>

<p><a href="http://www.amazon.cn/gp/product/B007Q2XXXG/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B007Q2XXXG&amp;linkCode=as2&amp;creative=3132">交互设计精髓</a>是交互设计领域的圣经级著作。交互设计专家（以及VB之父）<a href="http://en.wikipedia.org/wiki/Alan_Cooper">Alan Cooper</a>在这本书中详细介绍了交互设计的原则，流程，以及方法，然后通过各种范例（主要来自桌面系统）展示了如何应用这些原则。</p>

<p>需要注意的是这本书的<a href="http://www.amazon.cn/gp/product/1118766571/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=1118766571&amp;linkCode=as2&amp;creative=3132">第4版</a>已经出版，它在第三版的基础上增加了移动设计以及Web设计等内容。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/0465050654/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0465050654&amp;linkCode=as2&amp;creative=3132">The Design of Everyday Things</a>：交互设计领域的另一本经典之作，它通过解读人类行动背后的心理活动，展示了设计问题的根源，并给出了一系列方法用以解决设计问题（需要注意，尽管这本书有中译版，但中译版对应的是02年的旧版，而非13年的新版）；</li>
<li><a href="http://www.amazon.cn/gp/product/0672326140/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0672326140&amp;linkCode=as2&amp;creative=3132">The Inmates Are Running the Asylum</a>：<a href="http://en.wikipedia.org/wiki/Alan_Cooper">Alan Cooper</a>的另一本经典，这本书非常辛辣的指出让不具备人机交互知识的程序员直接编写面向用户的软件就像让精神病人管理疯人院（The Inmates Are Running the Asylum），然后给出了一套交互设计流程以挽救这个局面；</li>
<li><a href="http://www.amazon.cn/gp/product/B004I91HCY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004I91HCY&amp;linkCode=as2&amp;creative=3132">简约至上：交互式设计四策略</a>：专注于把产品变的更加简单易用。作者通过删除，组织，隐藏，和转移这四个策略，展示了如何创造出简约优质的用户体验。</li>
</ul>


<h2>个人成长</h2>

<h3><a name="career_development">1. 职业规划</a></h3>

<p><a name="apprentice_patterns"></a><a href="http://www.amazon.cn/gp/product/B00H6X6LD4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00H6X6LD4&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/9k3Nek8.jpg" alt="软件开发者路线图"></a></p>

<p><a href="http://www.amazon.cn/gp/product/B00H6X6LD4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00H6X6LD4&amp;linkCode=as2&amp;creative=3132">软件开发者路线图</a>是一本优秀且实用的程序员职业规划手册。这本书由若干个模式组成，每个模式都对应于程序员职业生涯中的特定阶段。通过这本书，读者可以很方便的找到自己目前所处的模式（阶段），应该做什么，目标是什么，以及下一个模式（阶段）会是什么。如果你时常感到迷茫，那么请阅读这本<a href="http://www.amazon.cn/gp/product/B00H6X6LD4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00H6X6LD4&amp;linkCode=as2&amp;creative=3132">路线图</a>，找到自己的位置，确定接下来的方向。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/B00F4NTD60/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00F4NTD60&amp;linkCode=as2&amp;creative=3132">卡耐基全集</a>：非常著名的为人处世书籍。很多人把这本书归类到成功学，但我并不这么认为——在我看来，这本书教的更多的是如何成为一个让大家喜欢的人。作为天天和机器打交道的程序员，这套书会帮助我们与人打交道；</li>
<li><a href="http://www.amazon.cn/gp/product/B008UOBZGQ/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B008UOBZGQ&amp;linkCode=as2&amp;creative=3132">沃顿商学院最受欢迎的谈判课</a>：这本书不是教你去谈判，而是教你通过谈判（Negotiation）去得到更多（Getting more，这也是这本书的原书书名）。小到买菜砍价，大到争取项目，这本书中的谈判原则会让你收益良多；</li>
<li><a href="http://www.amazon.cn/gp/product/B00N4LZ6RO/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00N4LZ6RO&amp;linkCode=as2&amp;creative=3132">程序员健康指南</a>：作为长期与计算机打交道的职业，程序员往往会受到各式各样疾病的困扰，这本书正是为了解决这个问题而出现：它从改善工作环境，调整饮食结构，预防头痛眼痛，以及进行室内/室外锻炼等方面出发，给出了一套全面且可行的程序员健康改善计划，以帮助程序员打造健康的身体。</li>
</ul>


<h3><a name="thinking">2. 思维方式</a></h3>

<p><a name="pragmatic_thinking_and_learning"></a><a href="http://www.amazon.cn/gp/product/B004GCCAFQ/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004GCCAFQ&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/STguKNr.jpg" alt="程序员的思维修炼：开发认知潜能的九堂课"></a></p>

<p>作为程序员，我们需要不断地学习——既要学习新技术，也要学习如何解决各种领域的问题。为了提升学习效率，我们需要学习<strong>如何学习</strong>。<a href="http://www.amazon.cn/gp/product/B004GCCAFQ/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004GCCAFQ&amp;linkCode=as2&amp;creative=3132">程序员的思维修炼</a>正是这样一本讲如何学习的书，它集合了认知科学，神经学，以及行为理论的最新研究成果，并系统的介绍了大脑的工作机制。通过这本书，你将学会如何高效的使用自己的大脑，从而提高思考能力，改善学习效率。</p>

<p><a name="mastery"></a><a href="http://www.amazon.cn/gp/product/B00ICWNKT6/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00ICWNKT6&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/zDuNUEB.jpg" alt="如何把事情做到最好"></a></p>

<blockquote><p>Mastery is not about perfection. It’s about a process, a journey. The master is the one who stays on the path day after day, year after year. The master is the one who is willing to try, and fail, and try again, for as long as he or she lives.</p></blockquote>

<p>为什么同样资质的人，大多数人会碌碌无为，而只有极少数能做到登峰造极？如何在领域内做到顶尖？如何克服通往顶尖之路上的重重险阻？<a href="http://www.amazon.cn/gp/product/B00ICWNKT6/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00ICWNKT6&amp;linkCode=as2&amp;creative=3132">如何把事情做到最好</a>回答了这些问题，并极具哲理的指出登峰造极并不是结果，而是一段永不停止的旅程。阅读这本书不会让你立刻脱胎换骨，但它会指引你走向正确的道路——通往登峰造极之路。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/B0011F6OGM/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011F6OGM&amp;linkCode=as2&amp;creative=3132">怎样解题：数学思维的新方法</a>：不要被标题中的“数学思维”吓到，它并不仅仅只是一本数学解题书，它所提出的四步解题法（理解题目-&gt;拟定方案-&gt;执行计划-&gt;总结反思）适用于任何领域；</li>
<li><a href="http://www.amazon.cn/gp/product/B005DSK4W8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B005DSK4W8&amp;linkCode=as2&amp;creative=3132">暗时间</a>：<a href="http://mindhacks.cn/">刘未鹏</a>所写的关于学习思维方法的文章集，既包含了他对学习方法的思考，也包含了大量进一步阅读的资源；</li>
<li><a href="http://www.amazon.cn/gp/product/B006PB30UK/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B006PB30UK&amp;linkCode=as2&amp;creative=3132">批判性思维：带你走出思维的误区</a>：这本书系统的分析了人类思维的常见误区，并针对各个误区给出了解决方案，从而帮助程序员养成严谨正确的思考方式；</li>
<li><a href="http://www.amazon.cn/gp/product/0738205370/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0738205370&amp;linkCode=as2&amp;creative=3132">Conceptual Blockbusting: A Guide to Better Ideas</a>：与批判性思维相反，这本书专注于创造性思维（Creative Thinking），它分析了阻碍创造性思维的常见思维障碍（Blockbuster）以及这些思维障碍背后的成因，并给出了各种方法以破除这些障碍。</li>
</ul>


<h3><a name="job_interview">3. 求职面试</a></h3>

<p><a name="google_resume"></a><a href="http://www.amazon.cn/gp/product/B008DYCYR2/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B008DYCYR2&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/hw1afyW.jpg" alt="金领简历：敲开苹果微软谷歌的大门"></a></p>

<p>知己知彼，百战不殆。<a href="http://www.amazon.cn/gp/product/B008DYCYR2/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B008DYCYR2&amp;linkCode=as2&amp;creative=3132">金领简历：敲开苹果微软谷歌的大门</a>是程序员求职的必读书籍，它覆盖了程序员求职的方方面面：从开始准备到编写简历，从技术面试到薪酬谈判。由于该书作者曾在Google，微软，和苹果任职并进行过技术招聘，因此这本书的内容非常实用。</p>

<p>顺便吐个槽：这本书翻译的还不错，但我实在无法理解封面上的“进入顶级科技公司的葵花宝典”这段文字——找个工作而已，用不着切JJ这么凶残吧。-_–#</p>

<p><a name="cracking_the_coding_interview"></a><a href="http://www.amazon.cn/gp/product/B00G8VOQOG/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00G8VOQOG&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/fIS1rHn.jpg" alt="程序员面试金典（第5版）"></a></p>

<p>同样是来自<a href="http://www.amazon.cn/gp/product/B008DYCYR2/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B008DYCYR2&amp;linkCode=as2&amp;creative=3132">金领简历</a>作者的作品，<a href="http://www.amazon.cn/gp/product/B00G8VOQOG/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00G8VOQOG&amp;linkCode=as2&amp;creative=3132">程序员面试金典（第5版）</a>专注于技术面试题，它既包含了IT企业（诸如微软，Google，和苹果）的面试流程以及如何准备技术面试，也包含了大量（超过200道）常见技术面试题题目以及解题思路。无论你打算进入国内企业还是外企，你都应该把这本书的题目练一遍，以找到技术面试的感觉（我在求职时就曾经专门搞了一块白板，然后每二十分钟一道题的练习，效果很不错）。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/B0016K8XGQ/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0016K8XGQ&amp;linkCode=as2&amp;creative=3132">编程之美：微软技术面试心得</a>：恐怕是国内技术面试第一书，这本书里面的多数题目都曾经是国内IT企业面试的必问题目。这本书的缺点是它太旧而且被用滥了（以至于一些企业开始避免使用这本书上的题目）——但你可以把它当成一本算法趣题来读；</li>
<li><a href="http://www.amazon.cn/gp/product/B00L5LKMVU/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00L5LKMVU&amp;linkCode=as2&amp;creative=3132">剑指Offer：名企面试官精讲典型编程题</a>：相对于东拼西凑的XX面试宝典，<a href="http://www.amazon.cn/gp/product/B00L5LKMVU/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00L5LKMVU&amp;linkCode=as2&amp;creative=3132">剑指Offer</a>是一本少见的国产精品技术面试书籍，尽管这本书的技术面试题目不多（60余道），但作者为大多数题目都给出了不同方式的解法，并分析了这些解法之间的优劣，此外作者还以面试官的视角分析了技术面试的各个环节，从而帮助读者把握技术面试；</li>
<li><a href="http://www.amazon.cn/gp/product/B004S04XC4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004S04XC4&amp;linkCode=as2&amp;creative=3132">人人都有好工作：IT行业求职面试必读</a>：可以把它看做<a href="http://www.amazon.cn/gp/product/B008DYCYR2/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B008DYCYR2&amp;linkCode=as2&amp;creative=3132">金领简历</a>的补充阅读——这本书的特点在于它给出了非常详细的简历/求职信/电子邮件编写技巧，而这正是不少国内程序员所缺乏的。</li>
</ul>


<h3><a name="english_writing">4. 英语写作</a></h3>

<p><a name="the_only_grammar_book"></a><a href="http://www.amazon.cn/gp/product/1580628559/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=1580628559&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/9sC6ezC.jpg" alt="The Only Grammar Book You'll Ever Need"></a></p>

<p>词汇量决定阅读能力，语法决定写作能力。计算机专业词汇并不多，但精确性非常重要，因此每个程序员都应具备良好的英语语法，但程序员并不需要过于专业的英语语法——掌握常用语法并把它用对就可以。<a href="http://www.amazon.cn/gp/product/1580628559/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=1580628559&amp;linkCode=as2&amp;creative=3132">The Only Grammar Book You’ll Ever Need</a>正好可以满足这个需求，尽管它篇幅不大（不足200页），却覆盖了英语中的关键语法以及常见错误。把这本书读两遍，它会大幅度提高你的英语写作能力。</p>

<p><a name="elements_of_style"></a><a href="http://www.amazon.cn/gp/product/B008H0PQPE/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B008H0PQPE&amp;linkCode=as2&amp;creative=3132"><img src="http://i.imgur.com/jtFHw4B.jpg" alt="风格的要素"></a></p>

<p>既是最畅销的英语写作书籍，也是计算机书籍中引用最多的非计算机书籍。<a href="http://www.amazon.cn/gp/product/B008H0PQPE/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B008H0PQPE&amp;linkCode=as2&amp;creative=3132">风格的要素</a>用极其简练的语言讲述了如何进行<strong>严肃</strong>，<strong>精确</strong>，<strong>清楚</strong>的英语写作。从这本书中，你不仅可以学到英语写作，更可以学到一种严谨至简的处事态度，而这正是专业开发所必需的。</p>

<p><strong>延伸阅读：</strong></p>

<ul>
<li><a href="http://www.amazon.cn/gp/product/B003IVY7Y8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B003IVY7Y8&amp;linkCode=as2&amp;creative=3132">牛津英语用法指南（第3版）</a>：全面且权威的英语用法指南，它覆盖语法，词汇，发音，以及修辞等方面，并兼顾口语和书面语，以帮助读者掌握合理的英语用法（Proper English Usage）。不要被这本书的篇幅（1000多页）吓到——原书并没有这么厚，因为这本书被翻译成中文但又得保留原有的英文内容，所以它的篇幅几乎翻了一倍。考虑到这本书使用的词汇都很基础，所以我认为具有英语基础的读者直接阅读原版（<a href="http://www.amazon.cn/gp/product/0194420981/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0194420981&amp;linkCode=as2&amp;creative=3132">Practical English Usage</a>）会更合适；</li>
<li><a href="http://www.amazon.cn/gp/product/B00EY8JUBO/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00EY8JUBO&amp;linkCode=as2&amp;creative=3132">写作法宝：非虚构写作指南（30周年纪念版）</a>：详尽的非虚构（Non-Fiction）写作指南，无论你要写地方，技术，商务，运动，艺术，还是自传，你都可以从这本书中找到珍贵的建议；</li>
<li><a href="http://www.amazon.cn/gp/product/B005NPZZYS/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B005NPZZYS&amp;linkCode=as2&amp;creative=3132">中式英语之鉴</a>：中国人使用英语最大的问题就是会把中式思维掺杂其中，从而形成啰里啰嗦不伦不类的中式英语（Chinglish）。<a href="http://www.amazon.cn/gp/product/B005NPZZYS/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B005NPZZYS&amp;linkCode=as2&amp;creative=3132">中式英语之鉴</a>系统的探讨了中式英语以及其成因，然后根据成因对中式英语进行归类，并对每个类别给出了大量的实际案例以及修改建议。如果你想摆脱中式英语，那么这本书是绝好的起点。</li>
</ul>


<h2>如何使用这个书单</h2>

<blockquote><p>学而不思则罔，思而不学则殆。</p>

<p>不愤不启，不悱不发。举一隅不以三隅反，则不复也。</p>

<p>不闻不若闻之，闻之不若见之，见之不若知之，知之不若行之，学至于行之而止矣。</p></blockquote>

<h2>来自他人的书单</h2>

<p>它山之石，可以攻玉。我在本文最后给出其他中外优秀程序员的书单，以便参考&amp;补充。</p>

<h3>刘未鹏（暗时间作者）</h3>

<p>以下同一条目下用“/”隔开的表示任选，当然也可以都读。</p>

<ol>
<li><a href="http://www.amazon.cn/gp/product/B009RSXIB4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B009RSXIB4&amp;linkCode=as2&amp;creative=3132">编码：隐匿在计算机软硬件背后的语言</a></li>
<li><a href="http://www.amazon.cn/gp/product/B004BJ18KM/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004BJ18KM&amp;linkCode=as2&amp;creative=3132">深入理解计算机系统</a> / <a href="http://www.amazon.cn/gp/product/B001GS7918/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001GS7918&amp;linkCode=as2&amp;creative=3132">Windows核心编程</a> / <a href="http://www.amazon.cn/gp/product/B0027VSA7U/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0027VSA7U&amp;linkCode=as2&amp;creative=3132">程序员的自我修养</a></li>
<li><a href="http://www.amazon.cn/gp/product/B0061XKRXA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0061XKRXA&amp;linkCode=as2&amp;creative=3132">代码大全</a> / <a href="http://www.amazon.cn/gp/product/B004GV08CY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004GV08CY&amp;linkCode=as2&amp;creative=3132">程序员修炼之道</a></li>
<li><a href="http://www.amazon.cn/gp/product/B00SFZH0DC/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00SFZH0DC&amp;linkCode=as2&amp;creative=3132">编程珠玑</a> / <a href="http://www.amazon.cn/gp/product/B001CZJEO0/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001CZJEO0&amp;linkCode=as2&amp;creative=3132">算法概论</a> / <a href="http://www.amazon.cn/gp/product/B0011EYUJG/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011EYUJG&amp;linkCode=as2&amp;creative=3132">算法设计</a> / <a href="http://www.amazon.cn/gp/product/B0016K8XGQ/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0016K8XGQ&amp;linkCode=as2&amp;creative=3132">编程之美</a></li>
<li><a href="http://www.amazon.cn/gp/product/B0011425T8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011425T8&amp;linkCode=as2&amp;creative=3132">C程序设计语言</a></li>
<li><a href="http://www.amazon.cn/gp/product/B003EIKI0C/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B003EIKI0C&amp;linkCode=as2&amp;creative=3132">C++程序设计语言</a> / <a href="http://www.amazon.cn/gp/product/B003VPX6YS/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B003VPX6YS&amp;linkCode=as2&amp;creative=3132">C++程序设计原理与实践</a> / <a href="http://www.amazon.cn/gp/product/020170353X/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=020170353X&amp;linkCode=as2&amp;creative=3132">Accelerated C++</a></li>
<li><a href="http://www.amazon.cn/gp/product/B0011AP7RY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011AP7RY&amp;linkCode=as2&amp;creative=3132">计算机程序的构造与解释</a></li>
<li><a href="http://www.amazon.cn/gp/product/B0031M9GHC/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0031M9GHC&amp;linkCode=as2&amp;creative=3132">代码整洁之道</a> / <a href="http://www.amazon.cn/gp/product/B00ADQPPLA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00ADQPPLA&amp;linkCode=as2&amp;creative=3132">实现模式</a></li>
<li><a href="http://www.amazon.cn/gp/product/B001130JN8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001130JN8&amp;linkCode=as2&amp;creative=3132">设计模式</a> / <a href="http://www.amazon.cn/gp/product/B00116MMA8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00116MMA8&amp;linkCode=as2&amp;creative=3132">敏捷软件开发（原则模式与实践）</a></li>
<li><a href="http://book.douban.com/subject/4262627/">重构</a></li>
</ol>


<h3>云风（中国游戏编程先行者，前网易游戏部门资深程序员，简悦创始人）</h3>

<ol>
<li><a href="http://www.amazon.cn/gp/product/B005CFUQR0/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B005CFUQR0&amp;linkCode=as2&amp;creative=3132">C++编程思想</a></li>
<li><a href="http://www.amazon.cn/gp/product/B004G72P24/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004G72P24&amp;linkCode=as2&amp;creative=3132">Effective C++</a></li>
<li><a href="http://www.amazon.cn/gp/product/B006QXQXTM/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B006QXQXTM&amp;linkCode=as2&amp;creative=3132">深度探索C++对象模型</a></li>
<li><a href="http://book.douban.com/subject/1096216/">C++语言的设计与演化</a></li>
<li><a href="http://www.amazon.cn/gp/product/B0012NIW9K/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0012NIW9K&amp;linkCode=as2&amp;creative=3132">C专家编程</a></li>
<li><a href="http://www.amazon.cn/gp/product/B0012UMPBY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0012UMPBY&amp;linkCode=as2&amp;creative=3132">C陷阱与缺陷</a></li>
<li><a href="http://www.amazon.cn/gp/product/B005LAJ9F6/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B005LAJ9F6&amp;linkCode=as2&amp;creative=3132">C语言接口与实现</a></li>
<li><a href="http://www.amazon.cn/gp/product/859037985X/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=859037985X&amp;linkCode=as2&amp;creative=3132">Lua程序设计</a></li>
<li><a href="http://book.douban.com/subject/4083265/">链接器和加载器</a></li>
<li><a href="http://book.douban.com/subject/1231481/">COM本质论</a></li>
<li><a href="http://www.amazon.cn/gp/product/B001GS7918/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001GS7918&amp;linkCode=as2&amp;creative=3132">Windows核心编程</a></li>
<li><a href="http://www.amazon.cn/gp/product/B00IS995HY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00IS995HY&amp;linkCode=as2&amp;creative=3132">深入解析Windows操作系统</a></li>
<li><a href="http://www.amazon.cn/gp/product/B004GV08CY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004GV08CY&amp;linkCode=as2&amp;creative=3132">程序员修炼之道</a></li>
<li><a href="http://www.amazon.cn/gp/product/B0061XKRXA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0061XKRXA&amp;linkCode=as2&amp;creative=3132">代码大全</a></li>
<li><a href="http://www.amazon.cn/gp/product/B008Z1IEQ8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B008Z1IEQ8&amp;linkCode=as2&amp;creative=3132">UNIX编程艺术</a></li>
<li><a href="http://www.amazon.cn/gp/product/B001130JN8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001130JN8&amp;linkCode=as2&amp;creative=3132">设计模式</a></li>
<li><a href="http://book.douban.com/subject/1193557/">代码优化：有效使用内存</a></li>
<li><a href="http://www.amazon.cn/gp/product/B004BJ18KM/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004BJ18KM&amp;linkCode=as2&amp;creative=3132">深入理解计算机系统</a></li>
<li><a href="http://www.amazon.cn/gp/product/B0011F5RYM/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011F5RYM&amp;linkCode=as2&amp;creative=3132">深入理解LINUX内核</a></li>
<li><a href="http://www.amazon.cn/gp/product/B00116OTVS/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00116OTVS&amp;linkCode=as2&amp;creative=3132">TCP/IP详解</a></li>
</ol>


<h3>洪强宁（豆瓣技术总监）</h3>

<ol>
<li><a href="http://www.amazon.cn/gp/product/B0061XKRXA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0061XKRXA&amp;linkCode=as2&amp;creative=3132">代码大全</a></li>
<li><a href="http://www.amazon.cn/gp/product/B0011C2P7W/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011C2P7W&amp;linkCode=as2&amp;creative=3132">人月神话</a></li>
<li><a href="http://www.amazon.cn/gp/product/B009RSXIB4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B009RSXIB4&amp;linkCode=as2&amp;creative=3132">编码：隐匿在计算机软硬件背后的语言</a></li>
<li><a href="http://www.amazon.cn/gp/product/B00478TO3A/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00478TO3A&amp;linkCode=as2&amp;creative=3132">计算机程序设计艺术</a></li>
<li><a href="http://www.amazon.cn/gp/product/B004GV08CY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004GV08CY&amp;linkCode=as2&amp;creative=3132">程序员修炼之道</a></li>
<li><a href="http://www.amazon.cn/gp/product/B001130JN8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001130JN8&amp;linkCode=as2&amp;creative=3132">设计模式</a></li>
<li><a href="http://www.amazon.cn/gp/product/B0011AP7RY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011AP7RY&amp;linkCode=as2&amp;creative=3132">计算机程序的构造与解释</a></li>
<li><a href="http://book.douban.com/subject/4262627/">重构</a></li>
<li><a href="http://www.amazon.cn/gp/product/B0011425T8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011425T8&amp;linkCode=as2&amp;creative=3132">C程序设计语言</a></li>
<li><a href="http://www.amazon.cn/gp/product/B00AK7BYJY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00AK7BYJY&amp;linkCode=as2&amp;creative=3132">算法导论</a></li>
</ol>


<h3>陈皓（CoolShell博主）</h3>

<ol>
<li><a href="http://www.amazon.cn/gp/product/B00QGA04RM/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00QGA04RM&amp;linkCode=as2&amp;creative=3132">点石成金：访客至上的Web和移动可用性设计秘笈</a></li>
<li><a href="http://www.amazon.cn/gp/product/B0048EKQS0/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0048EKQS0&amp;linkCode=as2&amp;creative=3132">重来：更为简单有效的商业思维</a></li>
<li><a href="http://www.amazon.cn/gp/product/B004WHZGZQ/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004WHZGZQ&amp;linkCode=as2&amp;creative=3132">黑客与画家</a></li>
<li><a href="http://www.amazon.cn/gp/product/B00AR8JWA4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00AR8JWA4&amp;linkCode=as2&amp;creative=3132">清醒思考的艺术</a></li>
<li><a href="http://www.amazon.cn/gp/product/B00116OTVS/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00116OTVS&amp;linkCode=as2&amp;creative=3132">TCP/IP详解</a></li>
<li><a href="http://www.amazon.cn/gp/product/B00KMR129E/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00KMR129E&amp;linkCode=as2&amp;creative=3132">UNIX环境高级编程</a></li>
<li><a href="http://www.amazon.cn/gp/product/B003SWP8XG/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B003SWP8XG&amp;linkCode=as2&amp;creative=3132">UNIX网络编程</a></li>
</ol>


<h3>张峥（微软亚洲研究院副院长）</h3>

<ol>
<li><a href="http://www.amazon.cn/gp/product/B001CZJEO0/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001CZJEO0&amp;linkCode=as2&amp;creative=3132">算法概论</a></li>
<li><a href="http://www.amazon.com/Data-Structures-Algorithms-Alfred-Aho/dp/0201000237/">Data Structure and Algorithms</a></li>
<li><a href="http://www.amazon.cn/gp/product/B0011425T8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011425T8&amp;linkCode=as2&amp;creative=3132">C程序设计语言</a></li>
<li><a href="http://book.douban.com/subject/10521297/">UNIX操作系统设计</a></li>
<li><a href="http://www.amazon.cn/gp/product/B001NGO85I/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B001NGO85I&amp;linkCode=as2&amp;creative=3132">编译原理</a></li>
<li><a href="http://www.amazon.cn/gp/product/B00AX9IENS/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00AX9IENS&amp;linkCode=as2&amp;creative=3132">计算机体系结构：量化研究方法</a></li>
<li><a href="http://www.amazon.cn/gp/product/B00HYSDJRC/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00HYSDJRC&amp;linkCode=as2&amp;creative=3132">当下的幸福</a></li>
<li><a href="http://www.amazon.cn/gp/product/B00JD436FA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00JD436FA&amp;linkCode=as2&amp;creative=3132">异类：不一样的成功启示录</a></li>
</ol>


<h3>Jeff Atwood（Stackoverflow联合创始人）</h3>

<ol>
<li><a href="http://www.amazon.cn/gp/product/B0061XKRXA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0061XKRXA&amp;linkCode=as2&amp;creative=3132">代码大全</a></li>
<li><a href="http://www.amazon.cn/gp/product/B0011C2P7W/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011C2P7W&amp;linkCode=as2&amp;creative=3132">人月神话</a></li>
<li><a href="http://www.amazon.cn/gp/product/B00QGA04RM/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00QGA04RM&amp;linkCode=as2&amp;creative=3132">点石成金：访客至上的Web和移动可用性设计秘笈</a></li>
<li><a href="http://book.douban.com/subject/3151486/">快速软件开发</a></li>
<li><a href="http://www.amazon.cn/gp/product/B00MO7R1SG/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00MO7R1SG&amp;linkCode=as2&amp;creative=3132">人件</a></li>
<li><a href="http://www.amazon.cn/gp/product/0465050654/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0465050654&amp;linkCode=as2&amp;creative=3132">The Design of Everyday Things</a></li>
<li><a href="http://www.amazon.cn/gp/product/B007Q2XXXG/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B007Q2XXXG&amp;linkCode=as2&amp;creative=3132">交互设计精髓</a></li>
<li><a href="http://www.amazon.cn/gp/product/0672326140/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0672326140&amp;linkCode=as2&amp;creative=3132">The Inmates Are Running the Asylum</a></li>
<li><a href="http://www.amazon.cn/gp/product/0123706432/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0123706432&amp;linkCode=as2&amp;creative=3132">GUI设计禁忌 2.0</a></li>
<li><a href="http://www.amazon.cn/gp/product/B00SFZH0DC/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00SFZH0DC&amp;linkCode=as2&amp;creative=3132">编程珠玑</a></li>
<li><a href="http://www.amazon.cn/gp/product/B004GV08CY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004GV08CY&amp;linkCode=as2&amp;creative=3132">程序员修炼之道</a></li>
<li><a href="http://www.amazon.cn/gp/product/B008UCHA58/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;creative=3132&amp;creativeASIN=B008UCHA58&amp;linkCode=as2&amp;tag=lucida-23">精通正则表达式</a></li>
</ol>


<h3>Joel Spolsky（Stackoverflow联合创始人）</h3>

<p><strong>软件项目管理</strong></p>

<ol>
<li><a href="http://www.amazon.cn/gp/product/B00MO7R1SG/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00MO7R1SG&amp;linkCode=as2&amp;creative=3132">人件</a></li>
<li><a href="http://www.amazon.cn/gp/product/B0011C2P7W/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011C2P7W&amp;linkCode=as2&amp;creative=3132">人月神话</a></li>
<li><a href="http://book.douban.com/subject/3151486/">快速软件开发</a></li>
</ol>


<p><strong>编程技艺</strong></p>

<ol>
<li><a href="http://www.amazon.cn/gp/product/B0061XKRXA/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0061XKRXA&amp;linkCode=as2&amp;creative=3132">代码大全</a></li>
<li><a href="http://www.amazon.cn/gp/product/B004GV08CY/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B004GV08CY&amp;linkCode=as2&amp;creative=3132">程序员修炼之道</a></li>
</ol>


<p><strong>编程哲学</strong></p>

<ol>
<li><a href="http://www.amazon.cn/gp/product/B005O4PUFC/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B005O4PUFC&amp;linkCode=as2&amp;creative=3132">禅与摩托车维修艺术</a></li>
<li><a href="http://www.amazon.cn/gp/product/B00L1VVUTC/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00L1VVUTC&amp;linkCode=as2&amp;creative=3132">哥德尔、艾舍尔、巴赫：集异璧之大成</a></li>
<li><a href="http://www.amazon.cn/gp/product/B002VUBI1C/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B002VUBI1C&amp;linkCode=as2&amp;creative=3132">建筑模式语言</a></li>
</ol>


<p><strong>界面设计</strong></p>

<ol>
<li><a href="http://www.amazon.cn/gp/product/B00QGA04RM/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00QGA04RM&amp;linkCode=as2&amp;creative=3132">点石成金：访客至上的Web和移动可用性设计秘笈</a></li>
<li><a href="http://www.amazon.cn/gp/product/B007Q2XXXG/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B007Q2XXXG&amp;linkCode=as2&amp;creative=3132">交互设计精髓</a></li>
<li><a href="http://www.amazon.cn/gp/product/0465050654/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=0465050654&amp;linkCode=as2&amp;creative=3132">The Design of Everyday Things</a></li>
</ol>


<p><strong>资本运作</strong></p>

<ol>
<li><a href="http://www.amazon.cn/gp/product/B00834SM32/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00834SM32&amp;linkCode=as2&amp;creative=3132">漫步华尔街</a></li>
</ol>


<p><strong>图形设计</strong></p>

<ol>
<li><a href="http://www.amazon.cn/gp/product/B00KQBLI5E/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00KQBLI5E&amp;linkCode=as2&amp;creative=3132">写给大家看的设计书</a></li>
</ol>


<p><strong>思维方式</strong></p>

<ol>
<li><a href="http://www.amazon.cn/gp/product/B0044KME2E/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0044KME2E&amp;linkCode=as2&amp;creative=3132">影响力</a></li>
<li><a href="http://book.douban.com/subject/3362251/">Helplessness On Depression, Development and Death</a></li>
</ol>


<p><strong>编程入门</strong></p>

<ol>
<li><a href="http://www.amazon.cn/gp/product/B009RSXIB4/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B009RSXIB4&amp;linkCode=as2&amp;creative=3132">编码：隐匿在计算机软硬件背后的语言</a></li>
<li><a href="http://www.amazon.cn/gp/product/B0011425T8/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B0011425T8&amp;linkCode=as2&amp;creative=3132">C程序设计语言</a></li>
</ol>


<h3>DHH（Ruby on Rails创始人）</h3>

<ol>
<li><a href="http://www.amazon.com/Smalltalk-Best-Practice-Patterns-Kent/dp/013476904X">Smalltalk Best Practice Patterns</a></li>
<li><a href="http://book.douban.com/subject/4262627/">重构</a></li>
<li><a href="http://www.amazon.cn/gp/product/B003LBSRDM/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B003LBSRDM&amp;linkCode=as2&amp;creative=3132">企业应用架构模式</a></li>
<li><a href="http://book.douban.com/subject/5344973/">领域驱动设计</a></li>
<li><a href="http://www.amazon.cn/gp/product/B00H1XNAIS/ref=as_li_ss_tl?ie=UTF8&amp;camp=536&amp;tag=lucida-23&amp;creativeASIN=B00H1XNAIS&amp;linkCode=as2&amp;creative=3132">你的灯亮着吗？发现问题的真正所在</a></li>
</ol>


<h2>参考</h2>

<ol>
<li><a href="http://mindhacks.cn/2011/11/04/how-to-interview-a-person-for-two-years/">怎样花两年时间去面试一个人</a></li>
<li><a href="http://stackoverflow.com/questions/1711/what-is-the-single-most-influential-book-every-programmer-should-read">What is the single most influential book every programmer should read?</a></li>
<li><a href="http://blog.codinghorror.com/recommended-reading-for-developers/">Recommended Reading for Developers</a></li>
<li><a href="http://www.joelonsoftware.com/navlinks/fog0000000262.html">Book Reviews — Joel Spolsky</a></li>
<li><a href="https://signalvnoise.com/posts/3375-the-five-programming-books-that-meant-most-to-me">The five programming books that meant most to me</a></li>
</ol>

