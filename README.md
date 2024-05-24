# FECAP - Fundação de Comércio Álvares Penteado

<p align="center">
<a href= "https://www.fecap.br/"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRhZPrRa89Kma0ZZogxm0pi-tCn_TLKeHGVxywp-LXAFGR3B1DPouAJYHgKZGV0XTEf4AE&usqp=CAU" alt="FECAP - Fundação de Comércio Álvares Penteado" border="0"></a>
</p>

# Sistema de detecção de umidade.

## AgriSense

## Integrantes: <a href="https://www.linkedin.com/in/lucas-gomes-de-souza-526b1730a/">Lucas Gomes de Souza</a> e <a href="https:https://www.linkedin.com/in/lucca-brand%C3%A3o-821044243/">Lucca Brandão</a></a>

## Professores Orientadores: <a href="https://www.linkedin.com/in/victorbarq/">Victor Bruno Alexander Rossetti de Queiroz</a> e <a href="https://www.linkedin.com/in/adriano-valente-534576135/">Adriano Felix Valente</a>.
## Descrição
O projeto visa implementar um sistema de monitoramento e controle de umidade do solo em estufas agrícolas para otimizar a irrigação, reduzir desperdícios de recursos e melhorar a produtividade das plantas. Os principais objetivos incluem a instalação de sensores de umidade em pontos estratégicos, automatização do sistema de irrigação com base em dados coletados, desenvolvimento de um aplicativo para monitoramento e controle remoto, e implementação de alertas e relatórios detalhados.

![Imagem projeto](https://github.com/2024-1-NADS1-A/Projeto10/assets/163611404/dd5d485e-c5d3-483d-8d56-3b4ace23a275)
<p align="center">
<img src= alt="NOME DO JOGO" border="0">
  Projeto desenvolvido por: <a href="https://www.linkedin.com/in/lucas-gomes-de-souza-526b1730a/">Lucas Gomes de Souza</a> e <a href="https:https://www.linkedin.com/in/lucca-brand%C3%A3o-821044243/">Lucca Brandão</a>
</p>

<br><br>
O projeto de Sistema de Detecção de Umidade utiliza o microcontrolador ESP32 e o aplicativo Blynk para monitorar remotamente os níveis de umidade do solo. O sistema é composto por um sensor de umidade do solo, que envia dados para o ESP32. Estes dados são transmitidos ao Blynk, onde o usuário pode visualizá-los através de uma interface personalizada.

Inicialmente, o projeto é criado no Blynk e as credenciais de autenticação são obtidas. No código do ESP32, a biblioteca Blynk é incluída e as credenciais são configuradas. Em seguida, o ESP32 é conectado ao servidor Blynk e os pinos virtuais são configurados para receber os dados do sensor.

Após a integração e a configuração online do ESP32, o sistema permite atualizações de firmware Over-The-Air (OTA) para facilitar a manutenção. A interface do usuário é construída no aplicativo Blynk, incluindo gráficos e indicadores de umidade, além de configurações de alertas e automações, como o acionamento de sistemas de irrigação quando a umidade estiver baixa.

Com todas as etapas concluídas, o sistema oferece um monitoramento eficiente e em tempo real, melhorando a gestão da irrigação e a saúde das plantas.
<br><br>

## 🛠 Estrutura de pastas

-Raiz<br>
|<br>
|-->documentos<br>
  &emsp;|-->antigos<br>
  &emsp;|Documentação.docx<br>
|-->imagens<br>
|-->src<br>
|readme.md<br>

A pasta raiz contem dois arquivos que devem ser alterados:

<b>README.MD</b>: Arquivo que serve como guia e explicação geral sobre seu projeto. O mesmo que você está lendo agora.

Há também 4 pastas que seguem da seguinte forma:

<b>documentos</b>: Toda a documentação estará nesta pasta.

<b>executáveis</b>: Binários e executáveis do projeto devem estar nesta pasta.

<b>imagens</b>: Imagens do sistema

<b>src</b>: Pasta que contém o código fonte.

## 🛠 Materiais utilizados

<br>•Esp8266</br>
<br>•Jumpers macho/ femea</br>
<br>•Sensor de umidade</br>
<br>•Protoboard</br>
<br>•Relay 5v</br>
<br>•I2C module</br>
<br>•Lcd display</br>


## 🛠 Instalação Arduino IDE

<br>•Instale o <a href="https://www.arduino.cc/en/software">Arduino IDE</a> a partir do site oficial.</br>
<br>Faça o downloand das bibliotecas necessárias;</br>
<br> Faça a conexão do esp8266 ao Blynk</br>

## 🛠 Instalação Blynk
Inicie um novo projeto e obtenha as credenciais necessárias com o token de autenticação;

No código do ESP32, inclua a biblioteca do Blynk e insira as credenciais obtidas;

Estabeleça a conexão com o servidor do Blynk;

Após estabelecer a conexão, integre o ESP82 ao Blynk;

Configure o modelo de funcionamento, além de alertas, notificações e automações;

Após completar todas essas etapas, a integração e a interface estarão prontas.

## 🗃 Histórico de lançamentos

A cada atualização os detalhes devem ser lançados aqui.

* 0.1.1 - 09/05/2024
    * Inicío do projeto (montagem e código).
* 0.1.02- 11/05/2024
    * Testes e correção de erros.
* 0.1.03 - 18/05/2024
    * Integrar o ESP82 ao Blynk.
* 0.1.04 - 23/05/2024
    * Integração ao Blynk e ultimos testes.
* 0.1.05 - 24/05/2024
    * Finalização do projeto.

## 📋 Licença/License
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/2024-1-NADS1-A/Projeto10">AgriSense</a> by <span property="cc:attributionName">Fecap, Lucas Gomes de Souza e Lucca Brandão</span> is licensed under <a href="https://creativecommons.org/licenses/by-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Creative Commons Attribution-ShareAlike 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" alt=""></a></p>

## 🎓 Referências

Aqui estão as referências usadas no projeto.

1. <https://sigmasensors.com.br/sensor-de-umidade-do-solo/>
2. <https://youtu.be/jqIaC1zXJ9E?si=lzcG4uUlg0lv4Ep1/>
3. <https://youtu.be/zUZpPkVHAcs?si=98qi5MxGaFJ_ZNcX/>
4. <https://youtu.be/H9UWv0zsmlQ?si=xq8lAF5zGVLA2RPy/>
5. <https://www.marconi.com.br/produto/273/sensor-de-umidade-do-solo-em-varias-profundidades/>
