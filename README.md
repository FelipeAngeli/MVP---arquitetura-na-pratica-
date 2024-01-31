# README - Projeto de Arquitetura MVP (Swift)


## 🚀 Sobre o Projeto

Este projeto é uma implementação da arquitetura Model-View-Presenter (MVP) em Swift, destinada ao desenvolvimento de aplicações iOS. A arquitetura MVP é uma evolução do MVC, focando na melhoria da separação de responsabilidades e facilitando a testabilidade. Nesta arquitetura, o Presenter atua como intermediário entre a View (interface do usuário) e o Model (lógica de negócios e dados).



## 🚀 Estrutura do Projeto

O projeto segue a estrutura padrão MVP, organizada da seguinte forma:

*  **Model**: Representa a camada de dados e lógica de negócios. Gerencia o estado do aplicativo, lógica de negócios, e comunicação com fontes de dados externas.
*  **View**: Composta por elementos de UI e é responsável por exibir as informações ao usuário. Envia as ações do usuário para o Presenter.
*  **Presenter**: Camada intermediária que recebe as ações da View, manipula os dados através do Model e atualiza a View.


### 📋 Requisitos

*  **iOS 13.0+**
*  **Xcode 11.0+**
*  **Swift 5.0+**



### ⚙️ Configuração

Para executar este projeto, clone o repositório e abra o arquivo .xcodeproj no Xcode:

```
git clone https://github.com/FelipeAngeli/MVP---arquitetura-na-pratica-
cd SwiftArquiteturas
open SwiftArquiteturas.xcodeproj

```


## ⌨️ Como Usar

1. **Models**: Desenvolva seus modelos de dados na pasta Models. Eles devem gerenciar os dados e a lógica de negócios.

2. **View**: As telas e componentes de UI são criados na pasta Views. Eles devem ser passivos e delegar a interação do usuário para o Presenter.

3. **Presenters**: Na pasta Presenters, implemente a lógica para responder às ações do usuário, interagir com o Model e atualizar a View.

4. **Fluxo e Navegação**: O controle de fluxo e navegação entre telas é geralmente gerido pelos Presenters.

5. **Testes**: É recomendado escrever testes unitários para Models e Presenters para assegurar a funcionalidade e robustez da aplicação.


## 🛠️ Construído com

Mencione as ferramentas que você usou para criar seu projeto

* [Swift](https://www.apple.com/br/swift/) - Linguagem Usada





## 📄 Licença

Este projeto está sob a licença (Felipe Angeli) - veja o arquivo [LICENSE.md](https://github.com/FelipeAngeli/VipCleanSwift) para detalhes.



---
