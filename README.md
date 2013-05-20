##操作

每次修改好了以後，可以先將修改存入stage<pre><code>
git add "檔名"
</pre></code>
若一次修改大量檔案，可以將所有檔案修改都add進去stage<pre><code>
git add .
</pre></code>
之後commit提交一次的修改<pre><code>
git commit -m "註解"
</pre></code>
另外也可以把git add與git commit用一個指令完成<pre><code>
git commit -a -m "註解"</pre></code>
改好了使用<pre><code>
git push</pre></code>
如果您在github上的版本較新，也可以輸入git pull
更新本地端的repo<pre><code>
git pull git://github.com/ken800314/Simple-words.git
</pre></code>
