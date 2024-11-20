# 📝 Relatório Discente de Acompanhamento

## Informações do Curso

- **Projeto:** Visualização de Dados IoT com Azure IoT Hub
- **Curso:** Full Stack
- **Universidade:** Estácio de Sá - Campus São José dos Pinhais
- **Período:** 4º Período
- **Turma:** 9001
- **Tecnologia:** Azure IoT Hub e Node.js
- **Tutor:** Alessandro Dos Santos Calin
- **Matéria:** Vamos Interligar as Coisas Com a Nuvem! (RPG0027)

## Informações do Aluno

- **Nome:** Dilnae Rennan Souza dos Santos
- **Matrícula:** 202302631631

## Estruturação do Projeto de Visualização de Dados IoT

O projeto de visualização de dados IoT foi desenvolvido para permitir a coleta, processamento e exibição de dados provenientes de dispositivos IoT usando o Azure IoT Hub e um aplicativo web em Node.js. O objetivo é centralizar e analisar informações geradas por sensores conectados ao IoT Hub, facilitando a visualização e o monitoramento em tempo real.

### Componentes Utilizados

O projeto foi estruturado utilizando os seguintes componentes principais:

- **Azure IoT Hub:** Gerencia a comunicação entre dispositivos IoT e a aplicação na nuvem.
- **Node.js Web App:** Um servidor web foi configurado para receber e visualizar dados dos dispositivos IoT conectados.
- **Azure Event Hub:** Utilizado para o armazenamento de mensagens recebidas e integração com o aplicativo de visualização.

### Configuração do Azure IoT Hub

1. **Criação do IoT Hub** no Azure, utilizando um **grupo de recursos** existente para a empresa.
2. Configuração de um **grupo de consumidores** para permitir a leitura dos dados transmitidos pelos dispositivos IoT.
3. **Conexão dos dispositivos** ao IoT Hub usando strings de conexão seguras.
4. **Configuração do Event Hub** para armazenar e gerenciar mensagens recebidas do IoT Hub.

## Funcionalidades Implementadas

### Visualização de Dados IoT em Tempo Real

O aplicativo web permite a visualização de dados IoT em tempo real, proporcionando:

- **Leitura de mensagens** enviadas pelos dispositivos IoT conectados.
- **Exibição gráfica** dos dados recebidos, facilitando a interpretação das informações coletadas pelos sensores.
- **Monitoramento contínuo**, permitindo que o usuário visualize atualizações assim que novas mensagens são recebidas.

### Armazenamento e Consulta de Dados

Além da visualização em tempo real, foram implementadas funcionalidades para:

- **Armazenamento dos dados recebidos** no Azure Event Hub para análise posterior.
- **Consultas filtradas** e ordenadas dos dados históricos, permitindo a geração de relatórios e gráficos baseados nos dados armazenados.

## Organização do Projeto no GitHub

Os arquivos e scripts do projeto foram organizados da seguinte maneira:

- **server.js:** Código principal do servidor Node.js, responsável por gerenciar a conexão com o IoT Hub e exibir os dados.
- **public/**: Pasta contendo arquivos estáticos, incluindo HTML, CSS e JavaScript para a interface do usuário.
- **scripts/**: Scripts auxiliares para configurar e gerenciar o ambiente IoT no Azure.

## Conclusão e Impacto

A solução desenvolvida proporciona uma plataforma robusta para monitoramento e análise de dados IoT, hospedada na nuvem através do Azure. Com a centralização dos dados em um único dashboard, a empresa tem agora uma ferramenta eficaz para tomar decisões baseadas em dados coletados de dispositivos IoT, melhorando o gerenciamento e a eficiência operacional.
