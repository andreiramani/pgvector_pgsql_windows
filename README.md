# [pgvector](https://github.com/pgvector/pgvector) binary compile, Microsoft Windows x64, PostgreSQL
<hr>
<b>***** Unofficial release *****</b>
<br>Intended for individuals who encountered difficulties in compiling.<br>
<hr>
See <a href="https://github.com/andreiramani/pgvector_pgsql_windows/releases">releases</a> for available version
<br><br><p></p>
<b>How to's v0.8.x</b>:
<br>
1. Check readme.txt (inside archive)<br>
<br>
<b>How to's v0.7.3, v0.7.4</b>:
<br>
1. Extracted zip file to "[pg_installed folder]\share\extension\"<br>
2. Activate extension with <code>create extension vector</code>
<br>
<a href="https://www.navicat.com/en/products/navicat-premium">
    <img src="img/01-create_extension.jpg" alt="Screenshot made with Navicat Premium">
</a><br><br>
3. Run this query to check if the extension is enable (t) <br> <code>SELECT extname,extrelocatable,extversion FROM pg_extension where extname='vector'</code>
<br>
<a href="https://www.navicat.com/en/products/navicat-premium">
    <img src="img/02-check_extension.jpg" alt="Screenshot made with Navicat Premium">
</a>

<p></p>
<hr>
Contributor compiler: <a href="https://github.com/vjivandro">vjivandro</a> (v0.7.3, v0.7.4), <a href="https://github.com/andreiramani">andreiramani</a> (v0.8.0, v0.8.1)
