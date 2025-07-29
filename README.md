<div align="center">
  <img width="1536" height="700" alt="viacertamockup" src="https://github.com/user-attachments/assets/9c31c3a4-9ec8-41a0-be87-32b8a39d4058" />
  <h1>Via Certa: Desviando do Caos Urbano</h1>
  <p>
    <strong>Sua rota inteligente para uma jornada urbana sem surpresas.</strong>
    <br>
    <em>Projeto de conclusão de curso da <strong>Escola da Nuvem, Turma AWS re/Start + IA</strong>.</em>
  </p>
  <p>
    <img src="https://img.shields.io/badge/Plataforma-AWS-orange?logo=amazon-aws" alt="Plataforma AWS">
    <img src="https://img.shields.io/badge/Status_do_Projeto-Conceitual-blue" alt="Status do Projeto">
    <img src="https://img.shields.io/badge/AI_Powered-SageMaker-green?logo=amazon-sagemaker" alt="AI Powered">
  </p>
</div>

---

### 📚 Sumário
* [🎯 O Problema](#-o-problema)
* [💡 A Solução: Via Certa](#-a-solução-via-certa)
* [✨ Principais Funcionalidades](#-principais-funcionalidades)
* [🏆 Vantagem Competitiva](#-vantagem-competitiva)
* [☁️ Ecossistema AWS: O Coração da Solução](#️-ecossistema-aws-o-coração-da-solução)
* [💰 Análise de Custos e Sustentabilidade](#-análise-de-custos-e-sustentabilidade)
* [🗺️ Roteiro de Evolução (Roadmap)](#️-roteiro-de-evolução-roadmap)
* [🙏 Agradecimentos e Equipe](#-agradecimentos-e-equipe)

---

## 🎯 O Problema

A vida do passageiro de transporte público em grandes centros urbanos é marcada pela incerteza. Uma chuva inesperada pode significar:
* **Longas esperas** em pontos de ônibus, sem qualquer previsão. ⛈️
* **Atrasos constantes** em compromissos importantes. ⏳
* **Exposição a riscos**, como tentar atravessar áreas alagadas. 💧
* **Falta de informação**, já que os aplicativos de mobilidade tradicionais raramente focam nos imprevistos que afetam especificamente as linhas de ônibus.

## 💡 A Solução: Via Certa

O **Via Certa** é uma plataforma de mobilidade urbana hiperfocada em resolver essa dor. Nosso aplicativo transforma o celular de cada usuário em um sensor inteligente da cidade, criando um ecossistema colaborativo que informa e empodera o passageiro.

Com o Via Certa, o usuário antecipa o caos, visualiza os problemas em tempo real e planeja rotas mais inteligentes para chegar ao seu destino de forma segura e previsível.

## ✨ Principais Funcionalidades

* 🗺️ **Mapa Colaborativo em Tempo Real:** Visualize alagamentos, congestionamentos e vias bloqueadas reportados pela comunidade e validados por nossa IA.
* 🧠 **Inteligência Artificial Preditiva:** Nosso sistema usa **Amazon SageMaker** para analisar a credibilidade dos alertas, prever a duração de congestionamentos e garantir informações confiáveis.
* 🔔 **Alertas Proativos e Personalizados:** Salve suas rotas favoritas (casa, trabalho) e receba notificações automáticas sobre problemas no seu caminho, antes mesmo de você sair.
* 🛡️ **Segurança e Privacidade por Design:** Gestão de identidade segura com **AWS Cognito**, garantindo que os dados do usuário sejam tratados com a máxima segurança e em conformidade com a LGPD.

## 🏆 Vantagem Competitiva

1.  **Hiperfoco no Passageiro de Ônibus:** Diferente de apps genéricos, nossa solução é desenhada para as dores e necessidades específicas deste público.
2.  **Modelo Híbrido (Comunidade + IA):** A combinação de relatos humanos com a validação e predição de uma IA cria uma base de dados única, rica e extremamente precisa.
3.  **Arquitetura Resiliente:** Nosso sistema foi projetado para funcionar melhor justamente nos piores cenários (tempestades, picos de trânsito), quando outras plataformas falham.

## ☁️ Ecossistema AWS: O Coração da Solução

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/Amazon_Web_Services_Logo.svg/2560px-Amazon_Web_Services_Logo.svg.png" alt="AWS Logo" width="150"/>
</div>

Para entregar uma experiência em tempo real, segura e escalável, construímos uma arquitetura **100% Serverless** na AWS, guiada pelos 6 pilares do **Well-Architected Framework**.

#### **Core da Aplicação e APIs**
* **AWS Lambda:** O cérebro sem servidor da nossa aplicação. Executa toda a lógica de negócio sob demanda, do processamento de alertas ao cálculo de rotas.
* **Amazon API Gateway:** Nossa porta de entrada segura e gerenciada para todas as requisições do aplicativo.
* **Amazon DynamoDB:** Banco de dados NoSQL de altíssima performance, ideal para armazenar e consultar dados de geolocalização e alertas em tempo real.
* **Amazon DAX (DynamoDB Accelerator):** Camada de cache em memória que garante performance de microssegundos na leitura de dados, tornando o mapa incrivelmente rápido.

#### **Inteligência, Resiliência e Notificações**
* **Amazon SageMaker:** O coração da nossa inteligência. Usado para treinar e implantar modelos de Machine Learning que validam os relatos da comunidade.
* **Amazon SQS (Simple Queue Service):** Fila de mensagens que garante a resiliência do sistema. Nenhum alerta de usuário é perdido, mesmo em picos de 10.000 relatos por minuto.
* **Amazon SNS (Simple Notification Service):** Dispara notificações push em massa para os usuários, alertando-os sobre problemas em suas rotas salvas.

#### **Segurança e Entrega Contínua (CI/CD)**
* **Amazon Cognito:** Oferece uma gestão de identidade completa e segura, cuidando da autenticação e autorização dos nossos usuários.
* **AWS CodePipeline & CodeBuild:** Automatiza todo o nosso processo de build, teste e deploy, permitindo inovar com velocidade e segurança.

<p align="center">
  <img src="https://i.imgur.com/example_diagram.png" alt="Diagrama da Arquitetura" width="800"/>
  <br>
  <em>Substitua este link pela imagem do seu diagrama de arquitetura.</em>
</p>

## 💰 Análise de Custos e Sustentabilidade

A arquitetura serverless permite uma sustentabilidade financeira notável. Nossa projeção de custo anual para uma base de **10.000 usuários ativos/mês** demonstra a eficiência do modelo "pay-as-you-go".

| Categoria | Serviço Específico | Custo Anual (USD) | Premissas Chave |
| :--- | :--- | :--- | :--- |
| **Computação & APIs** | AWS Lambda & API Gateway | ~$1.400 | ~2.5 milhões de requisições/mês. |
| **Banco de Dados & Cache** | DynamoDB & DAX | ~$3.120 | **Investimento chave** para performance e resiliência. |
| **Inteligência Artificial**| Amazon SageMaker (Serverless) | ~$1.200 | **Investimento chave** para análise sob demanda. |
| **Suporte & Outros** | SNS, SQS, S3, Cognito, etc. | ~$1.030 | Serviços de apoio, mensageria e infraestrutura. |
| **Contingência** | *Buffer de ~10%* | ~$700 | Para cobrir picos e transferência de dados. |
| **TOTAL** | | **~ $7.450** | **Custo total anual projetado.** |


## 🗺️ Roteiro de Evolução (Roadmap)

A visão para o Via Certa é ampla e ambiciosa:
- [ ] 🤖 **Rotas Alternativas Inteligentes:** Sugestão de desvios gerados por IA.
- [ ] 🗣️ **Integração com Assistentes de Voz:** "Alexa, como está meu caminho para o trabalho?".
- [ ] 🏛️ **Parcerias Estratégicas:** Integração com dados de órgãos públicos de mobilidade.
- [ ] 🏆 **Gamificação:** Sistema de pontos e recompensas para os usuários mais ativos na comunidade.

## 🙏 Agradecimentos e Equipe

Este projeto é a materialização de uma jornada de aprendizado intenso e colaboração.

* **Instituições:** Um agradecimento especial à **Escola da Nuvem** e ao programa **AWS re/Start + IA** pela oportunidade e pela formação de excelência.
* **Instrutor:** Nossa gratidão ao mestre e mentor, **Anderson Albuquerque**, que nos ensinou a pensar como verdadeiros arquitetos de soluções na nuvem.
* **A Equipe Visionária:**
    * Felipe Kttu
    * Carlos Alberto
    * Alexandre Paulino
    * Gil Maik de Jesus
    * João Victor
    * José Winny
    * Mikael Kobama
    * Rodolfo Bianchi
    * Mariane Hessel
 
      ## 🔗 Conecte-se e Saiba Mais

Este projeto foi uma jornada incrível de aprendizado e aplicação prática. Para saber mais sobre a visão, a estratégia e ver a apresentação completa, confira os links abaixo.

* **🎥 Apresentação do Projeto:** [Assista à apresentação completa do Via Certa](https://gamma.app/docs/TrabalhoBRSAO187Grupo4-iko8dgdhgxs12tc?mode=present#card-aqvaadx96cvnp2j)
* **💼 Conecte-se comigo no LinkedIn:** [Visite meu perfil e vamos nos conectar!](https://www.linkedin.com/in/felipekttu)

---
