# Como Usar o Copy\_to\_usb #

Para usar esse script tudo o que você precisa fazer é (depois de fazer o download [aqui](http://code.google.com/p/copy-to-usb/downloads/list)) coloca-lo no diretório .gnome2/nautilus-scripts/ (localizado na sua pasta pessoal) e dar a ele permissão para ser executado através do seguinte comando:

```
chmod +x _nomedoarquivo_
```

Onde _nomedoarquivo_ deve ser substituido pelo nome do script (você pode renomear o arquivo como achar melhor, mas o padrão é copy\_to\_usb-_versão_).

Você precisa também instalar o [Zenity](http://live.gnome.org/Zenity), usado para mostrar as janelas necessárias. Para fazer isto, basta utilizar o gerenciador de pacotes de sua distribuição. No caso do Ubuntu, basta digitar:

```
sudo aptitude install zenity
```

Depois de seguir estes passos, um menu chamado "scripts" deve aparecer quando você clicar com o botão direito em algum arquivo. Dentro deste menu, deve haver a opção copy\_to\_usb. Agora basta clicar nesta opção para copiar o arquivo selecionado para o dispositivo usb.