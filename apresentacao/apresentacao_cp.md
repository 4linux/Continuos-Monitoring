---
marp: true
theme: gaia
backgroundColor: #fff
paginate: true
color: black
backgroundImage: url('imagens/background.jpg')
style: |
    section{
      font-family: Arial, sans-serif, monospace;
    }
    
---

<style scoped>
  h1 {
    font-size: 125%;
    list-style-type: circle;
    text-align: center;
    font-weight: 900;
    color: #04067A
  }
  p {
    font-size: 21pt;
    text-align: right;
    list-style-type: circle;
    font-weight: 500;
    color: #024550
  }
  img[alt~="center"]{
    display: block;
    margin: 0 auto;
  }
</style>

<!-- _backgroundImage: url('imagens/ppt-business-613.jpg') -->
<!-- _paginate: false  -->
#
![width:360px center](imagens/Network-Monitoring.png)
# Monitoramento de Aplicações com ferramentas **OpenSource**
---
<style scoped>
  h3 {
    font-size: 35pt;
    text-align: center;
    list-style-type: circle;
    font-weight: 900;
    color: #04067A
  }
  p {
    font-size: 20pt;
    text-align: center;
  }
  h6 {
   font-size: 30px;
   text-align: center;
  }
  img[alt~="center"]{
    display: block;
    margin: 0 auto;
  }
</style>
#
 ![width:480px center](imagens/QRCode_git.png)
  ### Baixe esta apresentação!



---
<style scoped>
  li {
  list-style-type: disc;
  padding: 0;
  width: 70%;
  margin-left: -10px;
}
</style>

![bg right:32% 95%](imagens/IMG_20220608_120558.jpg)

###  Jeovany Batista da Silva

* Analista Linux na 4Linux
* Consultor de tecnologia para monitoramento
* Gamer 🎮
* Maker 🔨
* Player ⚽
* Adorador de café ☕


---

<style scoped>
  blockquote {
    font-size: 30pt;
    color: #04067A;
    text-align: center;
  }
  p {
    color: #00CFCC;
    text-align: center;
  }
</style>
#
<!-- _paginate: false -->

>#### Só depois que a tecnologia inventou o telefone, o telégrafo, a televisão, a internet, foi que se descobriu que o problema de comunicação mais sério era o de perto.

*Millôr Fernandes*

---
<style scoped>
  h3 {
    font-size: 40pt;
    text-align: center;
    list-style-type: circle;
    font-weight: 900;
    color: #04067A
  }
  p {
    font-size: 20pt;
    text-align: center;
  }
  h6 {
   font-size: 30px;
   text-align: center;
  }
</style>

 ### Corre aqui que teremos um sorteio no final!
 ![bg left:45% 80%](imagens/QRCode_4Linux.png)
 ###### Não deixe de participar!
Escaneie o QRCode ou [clique aqui!](https://sorteio.4linux.com.br/sorteio-palestra-monitoramento-de-aplicacoes-com-ferramentas-opensource)

---
<style scoped>
  h1 {
    font-size: 35pt;
    color: #04067A;
    text-align: center;
  }
  li {
  list-style-type: disc;
  padding: 0;
  width: 100%;
  margin-left: -10px;
  }
  img[alt~="right"]{
    display: block;
    margin: 0 auto;
  }
</style>

# Monitoramento de aplicações

*  Necessidades
*  Tecnologia e Processos 
*  Ferramentas OpenSource
    * Prometheus
    * Grafana
  
![bg right:50% w:500](imagens/suporte-de-ti-min.png)

  
---
<style scoped>
  li {
  list-style-type: disc;
  font-size: 23pt;
  padding: 0;
  width: 100%;
  margin-left: -10px;
  }
  h1 {
    font-size: 48pt;
    color: #04067A;
    text-align: center;
  }
</style>

# Prometheus

* TSDB - Time Series Data Base
* Coletas de métricas em modelo pull sobre HTTP
* PromQL
* Trabalha com qualquer arquitetura de serviço
* Configuração estática ou com serviços de descobertas para Targets

![bg right:55% w:650](imagens/architecture.png)

---
<style scoped>
  h6 {
   font-size: 30px;
   text-align: center;
  }
  h1 {
    font-size: 48pt;
    color: #04067A;
    text-align: center;
  }
</style>

# Grafana
O Grafana permite consultar, visualizar, alertar e explorar suas métricas, logs e rastreamentos, onde quer que estejam armazenados. Fornece ferramentas para transformar seus dados, armazenados em banco de dados de séries temporais (TSDB), em gráficos e visualizações inteligentes.

![bg left:40% 100%](imagens/grafana2.png)

---
<style scoped>
  h1 {
    font-size: 48pt;
    text-align: center;
    list-style-type: circle;
    font-weight: 900;
    color: #04067A
  }
  img[alt~="center"]{
    display: block;
    margin: 0 auto;
  }
  p{
    text-align: center;
  }
</style>

# Vamos ao Laboratório!

Siga-me os bons!
![w:480px center](imagens/wellguides_running-jumbo-v2.gif)

---
<style scoped>
  h1 {
    font-size: 48pt;
    text-align: center;
    list-style-type: circle;
    font-weight: 900;
    color: #04067A
  }
  h5{
    font-size: 30px;
    padding: 60px;
    text-align: center;
    margin-bottom: -100px;
  }
  h6{
    font-size: 35pt;
    text-align: center;
    padding: 80px;
    margin-bottom: -200px;
    color: #04067A;
  }
</style>

# Vamos nos conectar?

##### ![w:50px](imagens/insta.png) jeovanybatista
##### ![w:50px](imagens/linedin.png) Jeovany Batista
##### ![w:50px](imagens/telegram.png) jeovanybatista


###### Obrigado!!

---
<style scoped>
  h1 {
    font-size: 35pt;
    text-align: center;
    list-style-type: circle;
    font-weight: 900;
    color: #04067A
  }
  p{
    font-size: 21pt;
    padding: 80px;
  }
</style>

# Referências Bibliográficas

https://prometheus.io/docs/instrumenting/clientlibs/
https://prometheus.io/docs/introduction/overview/
https://grafana.com/
https://grafana.com/oss/grafana/
https://grafana.com/docs/?pg=oss-graf&plcmt=quick-links
https://github.com/prometheus-community/helm-charts/tree/main/charts/kube-prometheus-stack
https://github.com/grafana/helm-charts
