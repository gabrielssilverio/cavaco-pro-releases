# Cavaco Pro — versões

Este repositório guarda apenas os arquivos de instalação do Cavaco Pro. O
código do aplicativo não está aqui.

- `latest.json` — a versão mais recente, que o aplicativo consulta.
- `CavacoPro-<versão>.apk` — o instalador, assinado.

O APK ser público não é descuido: quem tem o aplicativo instalado já tem o
arquivo. O aplicativo confere o SHA-256 antes de instalar qualquer coisa, e
o Android só aceita a atualização se ela vier assinada com a mesma chave da
versão já instalada.
