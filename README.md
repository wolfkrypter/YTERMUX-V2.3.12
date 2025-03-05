# YTDLP-TERMUX-V2
Ejecuta de forma legible YT-DLP en Termux.</p>
<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjroJO_37lpunqm_-Hee7yeY4Uo39s-iBnSWo5MA5RtGhLnKLRwVWz2ZsvX94yvNbyFIIBybgDmyVwIHdGnOCgHyEsmJjjBywdG-sby5Cx9Y8yfp3zKC3lOr0SeWWvEBjimNqZfiQaATJWH08mKazbII4Q7SKBZlyVU0cHnDdxu9dIzCgf6asMrJyDbddRc/s400/Screenshot_20250219-005737.jpg"/>

<h2>ESTADO DEL REPOSITORIO</h2>
<p><strong>Status:</strong> Activo | Disponible</p>
<p><strong>Edición:</strong> 04/03/2025/17:45:05</p>
<p><strong>Tamaño:</strong> 1 GB</p>


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
