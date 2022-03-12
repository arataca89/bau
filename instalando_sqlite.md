# Instalando o SQLite no Windows

1. Vá na [página de download do SQLite](https://www.sqlite.org/download.html) e baixe os binários pré-compilados para Windows.
2. Baixe os arquivos <tt>sqlite-shell-win32-*.zip</tt> e <tt>sqlite-dll-win32-*.zip</tt>.
3. Crie um diretório <tt>C:\>sqlite</tt> e descompacte os arquivos zipados citados acima neste diretório. Após a descompactação você terá os arquivos: <tt>sqlite3.def</tt>, <tt>sqlite3.dll</tt> e <tt>sqlite3.exe</tt>.
4. Adiciona o diretório <tt>C:\>sqlite</tt> ao seu <tt>PATH</tt> e finalmente vá para a linha de comando e digite o comando <tt>sqlite3</tt>, o qual deverá retornar algo como:
<pre>
SQLite version 3.38.0 2022-02-22 18:58:40
Enter ".help" for usage hints.
Connected to a transient in-memory database.
Use ".open FILENAME" to reopen on a persistent database.
sqlite>
</pre>
<p>Data: 12/03/2022</p>

## Fonte:
[www.tutorialspoint.com/sqlite/sqlite_installation.htm](https://www.tutorialspoint.com/sqlite/sqlite_installation.htm)
