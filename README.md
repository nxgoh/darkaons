### INSTALL SCRIPT

<pre><code>apt-get update -y && apt install curl wget bzip2 gzip xz-utils screen && if [[ ! -d /etc/xdtmp ]]; then mkdir -p /etc/xdtmp; fi && wget -q https://raw.githubusercontent.com/genome96/darkaons/main/v5.sh && chmod +x v5.sh && screen -S install ./v5.sh
</code></pre>