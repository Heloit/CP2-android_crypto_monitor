README: 


Aplicativo Android simples para monitorar em tempo real a cotação do Bitcoin (BTC) em reais (R$), utilizando API pública. 

O objetivo deste projeto é demonstrar o consumo de uma API externa com atualização via botão, exibindo dados de forma clara ao usuário. 

  

Funcionalidades: 

- Monitoramento em Tempo Real: Acompanhe as cotações de diversas criptomoedas com atualizações periódicas. 

- Interface Intuitiva: Design simples e direto, com foco na experiência do usuário. 

- Suporte a Múltiplas Moedas: Visualize as cotações em diferentes moedas fiduciárias. 

- Favoritos: Marque suas criptomoedas preferidas para acesso rápido. 

- Persistência de Dados: Armazenamento local para histórico de cotações. 

  

  

Tecnologias Utilizadas: 

- Kotlin: Linguagem principal para desenvolvimento Android. 

- Retrofit: Biblioteca para chamadas HTTP e integração com APIs RESTful. 

- LiveData & ViewModel: Arquitetura MVVM para gerenciamento de UI. 

- Coroutines: Execução assíncrona de tarefas. 

- Room: Banco de dados local para armazenamento de dados persistentes. 

- Jetpack Navigation: Navegação entre componentes da interface. 

- Glide: Carregamento eficiente de imagens. 

  

Como funciona: 

- O app inicia exibindo um valor zerado (R$ 0,00) como placeholder. Ao pressionar o botão "ATUALIZAR", ele realiza os seguintes passos: 

- Conecta-se à API pública do AwesomeAPI 

- Faz uma requisição para obter o valor atual do Bitcoin em reais (BTC/BRL) 

- Atualiza o valor na interface 

- Exibe a data e hora da última atualização 

  

Estrutura do Projeto: 

  

android-crypto-monitor/ 

├── app/ 

│   ├── src/ 

│   │   ├── main/ 

│   │   │   ├── java/ 

│   │   │   │   └── com/ 

│   │   │   │       └── carreiras/ 

│   │   │   │           └── cryptomonitor/ 

│   │   │   │               ├── ui/            # Atividades e fragmentos 

│   │   │   │               ├── viewmodel/     # ViewModels 

│   │   │   │               ├── model/         # Modelos de dados 

│   │   │   │               ├── repository/    # Repositórios de dados 

│   │   │   │               └── network/       # Interfaces de API 

│   │   │   └── res/                          # Recursos (layouts, strings, etc.) 

├── build.gradle.kts 

├── settings.gradle.kts 

└── ... 

  

  

Capturas de Tela: 

- Tela Inicial com Cotação Zerada 
- ![zerado](https://github.com/user-attachments/assets/a53ea88e-3193-4a26-8edb-b415a40616a8)


- Tela com Cotação Atualizada
![com valor](https://github.com/user-attachments/assets/7292fdd9-ce21-41d5-ba2e-b20123d8c973)

