# YTDLP-TERMUX-V2
Ejecuta de forma legible YT-DLP en Termux.

<h2>ESTADO DEL REPOSITORIO</h2>
<p><strong>Status:</strong> Activó | Disponible</p>
<p><strong>Edición:</strong> 31/01/2025/19:34:04</p>


<h1>INSTALACIÓN DE YTDLP-TERMUX-V2</h1>
<p>~ $ yes | termux-setup-storage</p>
<p>~ $ yes | pkg upgrade && yes | pkg update</p>
<p>~ $ yes | pkg install ffmpeg</p>
<p>~ $ yes | pkg install python</p>
<p>~ $ pip install yt-dlp</p>
<p>~ $ yes | pkg install git</p>
<p>~ $ git clone https://github.com/wolfkrypter/YTDLP-TERMUX-V2.git</p>

<p>~ $ cd YTDLP-TERMUX-V2</p>
<p>~/YTDLP-TERMUX-V2 $ chmod +x ytermux-v2</p>
<p>~/YTDLP-TERMUX-V2 $ mv ytermux-v2 $PATH</p>

<h2>EJECUCIÓN DE YTDLP-TERMUX-V2</h2>
<p>~YTDLP-TERMUX-V2 $ ytermux-v2</p>
<p>or</p>
<p>~ $ ytermux-v2</p>
<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiV8woAiOaNKndqnfDCcoVSGk8k76iK7Vaxf2WfaCXJ6WzWy223kNjEc-AFX6A8OvzgjW7HBFrIDh7Ps_59rPh7FEaHHg4lVuEoDfHTuX2ZjJwBRLWubXxZDd1BCUWkxkbA5ilhlupJAc4S5qauUCYlbHSi4pvy2HfYzG6mgTaWTia6OM2Xh93lbz1GNtXe/s1600/Polish_20250131_130801176.png">

<h1>DESINSTALACIÓN DE YTDLP-TERMUX-V2</h1>
<p>~ $ cd $PATH && rm -r ytermux-v2 && cd</p>
<p>~ $ yes | rm -r YTDLP-TERMUX-V2</p>

<h2>DESINSTALACIÓN DE DEPENDENCIAS DE YTDLP-TERMUX-V2</h2>

<p>~ $ yes | pkg uninstall ffmpeg</p>
<p>~ $ yes | pip uninstall yt-dlp</p>
<p>~ $ yes | pkg uninstall python</p>
<p>~ $ echo -e "\n\n\033[0;666;32m[INF]\033[0;666;32m Desinstalación de dependencias de YTDLP-TERMUX-V2 completada.\n\n"</p>

<p><strong>INF:</strong> El siguiente comando desinstala la dependencia y el paquete de git el cual es indispensable para clonar repositorios e útil para el servicio de instalación de software de código abierto publicados en git,etcétera.</p>
<p>~ $ yes | pkg uninstall git</p>
