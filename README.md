# CamPhish
Capture imagens da câmera frontal do telefone alvo ou da webcam do PC enviando apenas um link.
![CamPhish](https://media.discordapp.net/attachments/1266269802532438027/1268961860317741106/image.png?ex=66ae5453&is=66ad02d3&hm=d6ab73e8c538de19664efac81544e47af08cebeff8c1f9eb3826ccb6fe1de19d&=&format=webp&quality=lossless&width=680&height=473)

# O que é o CamPhish?
<p>O CamPhish é uma técnica para capturar imagens da câmera frontal do telefone alvo ou da webcam do PC. O CamPhish hospeda um site falso em um servidor PHP incorporado e utiliza o ngrok e o serveo para gerar um link que será enviado ao alvo, permitindo o acesso via internet. O site solicita permissão para usar a câmera e, se o alvo conceder, esta ferramenta captura imagens da câmera do dispositivo alvo.</p>

## Recursos
<p>Nesta ferramenta, adicionei dois modelos de páginas automáticas para engajar o alvo e obter mais imagens da câmera:</p>
<ul>
  <li>Desejo de Festival</li>
  <li>Live YouTube TV</li>
  <li>Reunião Online [Beta]</li>
</ul>
<p>Basta inserir o nome do festival ou o ID do vídeo do YouTube.</p>

## Esta ferramenta foi testada em:
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Parrot Sec OS</li>
</ul>

# Instalação e Requisitos
<p>Esta ferramenta requer PHP para o servidor web, e um link SSH ou serveo. Primeiro, execute o seguinte comando no seu terminal:</p>

```
apt-get -y install php openssh git wget
```

## Instalação (Kali Linux/Termux):

```
git clone https://github.com/3XV0T3R/CamPhish
cd CamPhish
bash camphish.sh
```


## Histórico de Versões:

<p><b>Versão: 1.0:</b> Integração com WebHooks do Discord</p>

#### O CamPhish foi criado para auxiliar em testes de penetração e não se responsabiliza por qualquer uso indevido ou ilegal.
