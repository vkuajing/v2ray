# v2ray
VPS搭建VPN教程2019-V2ray教程
<div>
<div>关于自建VPN翻墙教程，本文是利用V2ray的一个VPS搭建VPN教程。仅供交流和学习使用。</div>
</div>
<div></div>
<div>
<div><strong>本文分两部分：</strong></div>
<div>1.<a href="#01"><span style="text-decoration: underline; color: #0000ff;">VPN的设置教程</span></a></div>
<div>2.<a href="#02"><span style="text-decoration: underline; color: #0000ff;">V2Ray的连接教程</span></a></div>
</div>
<h3></h3>
<strong>前提：搭建之前首先要做两件事</strong>
<ol>
 	<li>注册VPS服务器  【<a href="https://vpsland.xyz/vultr/" target="_blank" rel="noopener noreferrer"><span style="text-decoration: underline; color: #0000ff;">Vultr主机</span></a> / <a href="https://vpsland.xyz/get-bwh/" target="_blank" rel="noopener noreferrer"><span style="text-decoration: underline; color: #0000ff;">BWH主机</span></a>  / <a href="https://vpsland.xyz/get-hostwinds/" target="_blank" rel="noopener noreferrer"><span style="text-decoration: underline;"><span style="color: #0000ff; text-decoration: underline;">HostWinds主机</span></span></a> 都可以】</li>
 	<li><span style="text-decoration: underline; color: #0000ff;"><a style="color: #0000ff;" href="https://vkuajing.net/ssh-vps-link/" target="_blank" rel="noopener noreferrer">用SSH工具连接进入VPS主机服务器</a></span></li>
 	<li>如果搭建不适合，移步<a href="https://vkuajing.net/paid-vpn-list/" target="_blank" rel="noopener noreferrer"><span style="text-decoration: underline; color: #0000ff;">好用的vpn推荐</span></a></li>
</ol>
<div>

<hr />

<h4 id="01"><span style="color: #000000;"><strong>第一、VPN的设置及连接</strong></span></h4>
<div><strong>1.避免VPS没装Curl，保险起见运行一下 Curl的安装命令, 两种系统下随便用一个命令就可以。</strong></div>
<div>ubuntu/debian 系统下  【我现在的版本是 CentOS7，所以<span style="color: #ff0000;"><strong>不用</strong></span>这个命令】</div>
<blockquote>
<div>
<div>
<div>apt-get install curl -y</div>
</div>
</div></blockquote>
<div><img class="aligncenter size-full wp-image-294" src="https://vpsland.xyz/wp-content/uploads/2019/07/vpn搭建教程-V2Ray教程-1.png" alt="vpn搭建教程-V2Ray教程 (1)" width="586" height="150" /></div>
<div>
<div>centos 系统下 【我现在的版本是 CentOS7，所以<span style="color: #ff0000;"><strong>用</strong></span>这个命令】</div>
</div>
<blockquote>
<div>
<div>
<div>yum install curl -y</div>
</div>
</div></blockquote>
<div>
<div><strong>2.右键复制粘贴如下代码，只能鼠标右键粘贴，Ctrl + V不管用</strong></div>
<div>
<div>
<blockquote>
<div>
<div>bash &lt;(curl -s -L https://git.io/v2ray.sh)</div>
</div></blockquote>
<div>
<div>粘贴后，Enter， 进入下列菜单</div>
<div>输入 1 按 Enter 继续</div>
</div>
<div><img class="aligncenter size-full wp-image-295" src="https://vpsland.xyz/wp-content/uploads/2019/07/vpn搭建教程-V2Ray教程-2.png" alt="vpn搭建教程-V2Ray教程 (2)" width="622" height="269" /></div>
<div>
<div>V2Ray的功能比较多，我们不用管</div>
<div>看到以下界面直接按 Enter 继续</div>
<div><img class="aligncenter size-full wp-image-296" src="https://vpsland.xyz/wp-content/uploads/2019/07/vpn搭建教程-V2Ray教程-3.png" alt="vpn搭建教程-V2Ray教程 (3)" width="1248" height="235" /></div>
</div>
<div></div>
<div>
<div>继续 Enter</div>
<div><img class="aligncenter size-full wp-image-297" src="https://vpsland.xyz/wp-content/uploads/2019/07/vpn搭建教程-V2Ray教程-4.png" alt="vpn搭建教程-V2Ray教程 (4)" width="611" height="99" /></div>
</div>
</div>
<div></div>
<div>
<div>继续 Enter</div>
<div><img class="aligncenter size-full wp-image-298" src="https://vpsland.xyz/wp-content/uploads/2019/07/vpn搭建教程-V2Ray教程-5.png" alt="vpn搭建教程-V2Ray教程 (5)" width="550" height="122" /></div>
</div>
<div></div>
<div>
<div>继续 Enter</div>
<div><img class="aligncenter size-full wp-image-299" src="https://vpsland.xyz/wp-content/uploads/2019/07/vpn搭建教程-V2Ray教程-6.png" alt="vpn搭建教程-V2Ray教程 (6)" width="595" height="89" /></div>
</div>
<div></div>
<div>
<div>还是Enter</div>
<div></div>
</div>
<div><img class="aligncenter wp-image-1994 lazyautosizes lazyloaded" src="https://vkuajing.net/wp-content/uploads/2019/07/VPN%E6%90%AD%E5%BB%BA%E6%95%99%E7%A8%8B-V2RAY-9.png" sizes="384px" srcset="https://vkuajing.net/wp-content/uploads/2019/07/VPN搭建教程-V2RAY-9-200x116.png 200w, https://vkuajing.net/wp-content/uploads/2019/07/VPN搭建教程-V2RAY-9-300x174.png 300w, https://vkuajing.net/wp-content/uploads/2019/07/VPN搭建教程-V2RAY-9-400x232.png 400w, https://vkuajing.net/wp-content/uploads/2019/07/VPN搭建教程-V2RAY-9.png 436w" alt="VPN搭建教程-V2RAY (9)" width="384" height="223" data-orig-src="https://vkuajing.net/wp-content/uploads/2019/07/VPN搭建教程-V2RAY-9.png" data-srcset="https://vkuajing.net/wp-content/uploads/2019/07/VPN搭建教程-V2RAY-9-200x116.png 200w, https://vkuajing.net/wp-content/uploads/2019/07/VPN搭建教程-V2RAY-9-300x174.png 300w, https://vkuajing.net/wp-content/uploads/2019/07/VPN搭建教程-V2RAY-9-400x232.png 400w, https://vkuajing.net/wp-content/uploads/2019/07/VPN搭建教程-V2RAY-9.png 436w" data-sizes="auto" data-orig-sizes="(max-width: 384px) 100vw, 384px" /></div>
<div>
<div>等个几十秒，根据电脑性能不同等待时间不同，</div>
<div></div>
<div><strong>3. 看到如下界面之后 ，</strong></div>
<div>
<div>输入 v2ray url 复制出来 Vmess Url 【选中后用鼠标右键复制】</div>
<div><img class="aligncenter size-full wp-image-301" src="https://vpsland.xyz/wp-content/uploads/2019/07/vpn搭建教程-V2Ray教程-8.png" alt="vpn搭建教程-V2Ray教程 (8)" width="711" height="406" /></div>
</div>
<div></div>
</div>
<div>
<div>复制黄色区域 / 鼠标右键复制</div>
</div>
</div>
</div>
</div>
<div></div>
<div>
<div>
<div>
<div>
<div><img class="aligncenter size-full wp-image-302" src="https://vpsland.xyz/wp-content/uploads/2019/07/vpn搭建教程-V2Ray教程-9.png" alt="vpn搭建教程-V2Ray教程 (9)" width="1379" height="691" /></div>
</div>
<div></div>
<div>

<hr />

</div>
</div>
<div>
<h4 id="“02”"><strong>第二、 V2ray 的连接 【以Windows为例]</strong></h4>
<div>下载 V2ray 软件:  <a href="https://github.com/2dust/v2rayN/releases" target="_blank" rel="noopener nofollow noreferrer">https://github.com/2dust/v2rayN/releases</a></div>
<div>下载 v2rayN-Core.zip 到桌面解压</div>
</div>
</div>
</div>
<div>
<div>打开 V2rayN 程序</div>
</div>
<div></div>
<div><img class="aligncenter wp-image-303" src="https://vpsland.xyz/wp-content/uploads/2019/07/vpn搭建教程-V2Ray教程-10.png" alt="vpn搭建教程-V2Ray教程 (10)" width="738" height="221" /></div>
<div>添加 Vmess 服务器</div>
<div></div>
<div><img class="aligncenter wp-image-305" src="https://vpsland.xyz/wp-content/uploads/2019/07/vpn搭建教程-V2Ray教程-11.png" alt="vpn搭建教程-V2Ray教程 (11)" width="286" height="196" /></div>
<div>
<div>复制刚才复制的代码 Vmess地址</div>
</div>
<div>我把这个共享在 Free SS 资源    有需要的直接拿来用，也可以用来测试下速度</div>
<div></div>
<div>
<div>从剪切板导入URL ； 点确定</div>
<div></div>
</div>
<div><img class="aligncenter wp-image-289" src="https://vpsland.xyz/wp-content/uploads/2019/07/vpn搭建教程-V2Ray教程-12.png" alt="vpn搭建教程-V2Ray教程 (12)" width="670" height="516" /></div>
<div></div>
<div>
<div></div>
<div>回到V2ray 主界面，这里多了一个 新的服务器</div>
<div></div>
<div><img class="aligncenter size-full wp-image-290" src="https://vpsland.xyz/wp-content/uploads/2019/07/vpn搭建教程-V2Ray教程-13.png" alt="vpn搭建教程-V2Ray教程 (13)" width="805" height="174" /></div>
</div>
<div></div>
<div></div>
<div>
<div>参数设置 2333</div>
<div>点确定</div>
</div>
<div><img class="aligncenter wp-image-291" src="https://vpsland.xyz/wp-content/uploads/2019/07/vpn搭建教程-V2Ray教程-14.png" alt="vpn搭建教程-V2Ray教程 (14)" width="681" height="383" /></div>
<div></div>
<div>
<div>和 SS类似，右键点图标启用即可，</div>
<div>有风险提示，就点允许</div>
</div>
<div><img class="aligncenter wp-image-292" src="https://vpsland.xyz/wp-content/uploads/2019/07/vpn搭建教程-V2Ray教程-15.png" alt="vpn搭建教程-V2Ray教程 (15)" width="200" height="165" /></div>
<div>
<div>连接完成</div>
</div>
<div></div>
<div><img class="aligncenter wp-image-306" src="https://vpsland.xyz/wp-content/uploads/2019/07/vpn搭建教程-V2Ray教程-16-1.png" alt="vpn搭建教程-V2Ray教程 (16)" width="560" height="213" /></div>
