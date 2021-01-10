# REFISEFUQUI

**ReFiSeFuQui** é acrônimo para "Criador de Remasterizações de Fim de Semana e Fundo de Quintal". Ele é um fork do famoso [Remastersys (ver. 3.0.0-1)](https://web.archive.org/web/20110628083055/http://www.remastersys.com/) de Tony "Fragadelic" Brijeski, descontinuado no começo de 2013.

ReFiSeFuQui é um programa feito para Debian GNU/Linux, provavelmente funcionando em seus derivados.

O objetivo do programa é criar Live CD ou DVD contendo ou uma distribuição completa (como o saudoso Kurumin) ou uma cópia de backup completo do sistema instalado em sua máquina. Ou seja, ele faz uma Remasterização do seu sistema, criando um CD dele para você distribuir entre seus amigos (ou guardar como backup do sistema).

Basta gravar a imagem do Live CD/DVD ou de Backup numa mídia de CD/DVD ou num pendrive (com programas como o [Balena Etcher](https://www.balena.io/etcher/)), inserir a mídia/pendrive no PC e reinicializar. O sistema será carregado sem instalar nada no computador. Haverá um botão na Área de Trabalho que permitirá instalar no Disco Rígido (restauração do backup ou instalação da distro). Acompanha ferramentas de particionamento.

Totalmente em português do Brasil!

## Instalação

O programa precisa apenas do pacote **refisefuqui_1.22_all.deb** para funcionar, mas para usar uma interface gráfica será preciso instalar também o pacote gui: **refisefuqui-gui_1.22_all.deb**.

Para instalar no Debian digite:

_$ sudo dpkg -i refisefuqui_1.22_all.deb refisefuqui-gui_1.22_all.deb_

Instale as dependências:

_$ sudo aptitude install -f_

Caso o LiveCD peça senha ou usuário, use:

_live_

