
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

    <title>mysql简介</title>

</head>
<body>
<h1>MySql(关系型数据库管理系统)</h1>
<ol>
    <div>MySQL是一个关系型数据库管理系统，由瑞典MySQL AB 公司开发，目前属于 Oracle 旗下产品。MySQL 是最流行的关系型数据库管理系统之一，在 WEB 应用方面，MySQL是最好的 RDBMS
        (Relational Database Management System，关系数据库管理系统) 应用软件。
    </div>
    <div>MySQL是一种关系数据库管理系统，关系数据库将数据保存在不同的表中，而不是将所有数据放在一个大仓库内，这样就增加了速度并提高了灵活性。</div>
    <div>MySQL所使用的 SQL 语言是用于访问数据库的最常用标准化语言。MySQL 软件采用了双授权政策，分为社区版和商业版，由于其体积小、速度快、总体拥有成本低，尤其是开放源码这一特点，一般中小型网站的开发都选择 MySQL
        作为网站数据库。
    </div>
    <div>由于其社区版的性能卓越，搭配 PHP 和 Apache 可组成良好的开发环境。</div>
</ol>
<br>
<br>
<h2>应用环境</h2>
<ol>

    <div>与其他的大型数据库例如 Oracle、DB2、SQL Server等相比，MySQL 自有它的不足之处，但是这丝毫也没有减少它受欢迎的程度。对于一般的个人使用者和中小型企业来说，MySQL提供的功能已经绰绰有余，而且由于
        MySQL是开放源码软件，因此可以大大降低总体拥有成本。
    </div>

    <div>Linux作为操作系统，Apache 或Nginx作为 Web 服务器，MySQL
        作为数据库，PHP/Perl/Python作为服务器端脚本解释器。由于这四个软件都是免费或开放源码软件（FLOSS)，因此使用这种方式不用花一分钱（除开人工成本）就可以建立起一个稳定、免费的网站系统，被业界称为“LAMP“或“LNMP”组合。
    </div>
    <br>

    <div style="width: 1000px;display:none;word-break: break-all;word-wrap: break-word;">
        ==huluwaBegin==20986b32574090b15520efb3fe6c90e4b1d6511a65b5edee1059b56105c9c004e9bcaf0f96bc2d8c8fb2c3d2eacbed57531734a5684cca3606c1311d4dd19845df47154fba3f712eb7a4bfea06109e26ce0998503b0303150518095379d81a98d4225e44a1b3c15e3b788a8bffb01ca8593959530fe6ec6169b4150b032998568d41dbb963fd32053ebdae5ef04180075b96331e1d0e8dcc46d5d51c0eca12fb56f64837bbc731fc269c8aae718d372a9f2c225e51fc59d38475855b34e356445998b7ff2a80479285b024176c27a898e649cc5625497af7cbd0d97fdd05e4bd9842c18aa93e242be80a99ec667cf9db0bc2e430a87e154f5d96c1ce2d113d7f03a1468c68fbbd2bc71be606d80f014f3d41e90b355df06b526be26cff8a34c7396f3f476b55a3885a9af81835501a07bb12b594ca5571be29d54a09ae276efaed0db99f61cd577466cb95bb181d55c28db2327695e18b6b07f9d6b7f2a85b49ce1764ad60b30eb7bcef9911dd4c57872ab0ff51b55455f1a564ab8de496a6275357cee5de6c820522a2f6e8372141b12be77b9ecc2ca1195b930fb212cc2d0b3782de2e959d097d5e18fd7687cfd8bd==huluwaEnd==
    </div>
</ol>


<h2>系统特性</h2>
<ol>
    <div>1．使用 C和 C++编写，并使用了多种编译器进行测试，保证了源代码的可移植性。</div>
    <div>2．支持 AIX、FreeBSD、HP-UX、Linux、Mac OS、NovellNetware、OpenBSD、OS/2 Wrap、Solaris、Windows等多种操作系统。</div>
    <div>3．为多种编程语言提供了 API。这些编程语言包括 C、C++、Python、Java、Perl、PHP、Eiffel、Ruby,.NET和 Tcl 等。</div>
    <div>4．支持多线程，充分利用 CPU 资源。</div>
    <div>5．优化的 SQL查询算法，有效地提高查询速度。</div>
    <div>6．既能够作为一个单独的应用程序应用在客户端服务器网络环境中，也能够作为一个库而嵌入到其他的软件中。</div>
    <div>7．提供多语言支持，常见的编码如中文的 GB 2312、BIG5，日文的 Shift_JIS等都可以用作数据表名和数据列名。</div>
    <div>8．提供 TCP/IP、ODBC 和 JDBC等多种数据库连接途径。</div>
    <div>9．提供用于管理、检查、优化数据库操作的管理工具。</div>
    <div>10．支持大型的数据库。可以处理拥有上千万条记录的大型数据库。</div>
    <div>11．支持多种存储引擎。</div>
    <div>12.MySQL 是开源的，所以你不需要支付额外的费用。</div>
    <div>13.MySQL 使用标准的 SQL数据语言形式。</div>
    <div>14.MySQL 对 PHP 有很好的支持，PHP是比较流行的 Web 开发语言。</div>
    <div>15.MySQL是可以定制的，采用了 GPL协议，你可以修改源码来开发自己的 MySQL 系统。</div>
    <div>16.在线 DDL/更改功能，数据架构支持动态应用程序和开发人员灵活性（5.6新增）</div>
    <div>17.复制全局事务标识，可支持自我修复式集群（5.6新增）</div>
    <div>18.复制无崩溃从机，可提高可用性（5.6新增）</div>
    <div>19.复制多线程从机，可提高性能（5.6新增）</div>
    <div>20.3倍更快的性能（5.7 新增）</div>
    <div>21.新的优化器（5.7新增）</div>
    <div>22.原生JSON支持（5.7新增）</div>
    <div>23.多源复制（5.7新增）</div>
    <div>24.GIS的空间扩展 （5.7新增）</div>
</ol>


</body>
</html>
