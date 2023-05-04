FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/mvac1991/whaticketdeploy && sudo chmod -R 777 whaticketdeploy && cd whaticketdeploy && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd && rm -rf whaticketdeploy && git clone https://github.com/mvac1991/whaticketdeploy && sudo chmod -R 777 whaticketdeploy && cd whaticketdeploy && sudo ./install_instancia
```

