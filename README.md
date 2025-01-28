# YTDLP-TERMUX-V2
Ejecuta de forma legible YT-DLP en Termux.


<h1>INSTALACIÓN DE YTDLP-TERMUX-V2</h1>
<p>~ $ yes | termux-setup-storage</p>
<p>~ $ yes | pkg upgrade && pkg update</p>
<p>~ $ yes | pkg install ffmpeg</p>
<p>~ $ yes | pkg install python</p>
<p>~ $ pip install yt-dlp</p>
<p>~ $ yes | pkg install git</p>
<p>~ $ git clone https://github.com/wolfkrypter/YTDLP-TERMUX-V2.git</p>

<p>~ $ cd YTDLP-TERMUX-V2</p>
<p>~ $ chmod +x ytermux-v2</p>
<p>~ $ mv ytermux-v2 $PATH</p>
<p>~ $ ytermux-v2</p>





<h1>DESINSTALACIÓN DE YTDLP-TERMUX-V2</h1>
<p>~ $ cd $PATH && yes | rm -r ytermux-v2 && cd</p>
<p>~ $ yes | rm -r YTDLP-TERMUX-V2</p>

<h2>DESINSTALACIÓN DE DEPENDENCIAS DE YTDLP-TERMUX-V2</h2>

<p>~ $ yes | pkg uninstall ffmpeg</p>
<p>~ $ yes | pip uninstall yt-dlp</p>
<p>~ $ yes | pkg uninstall python</p>
<p>~ $ echo -e "\n\n\033[0;666;32m[INF]\033[0;666;32m Desinstalación de dependencias de YTDLP-TERMUX-V2 completada.\n\n"</p>

<p><strong>INF:</strong> El siguiente comando desinstala el paquete de git, el cual es indispensable para clonar repositorios e útil para el servicio de instalación de software de código abierto publicados en git,etcétera.</p>
<p>~ $ yes | pkg uninstall git</p>
