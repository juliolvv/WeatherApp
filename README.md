# 🌦️ Weather App

Um aplicativo web simples e elegante para consulta de previsão do tempo em tempo real. O usuário pode digitar o nome de uma cidade e o aplicativo exibe instantaneamente as condições climáticas atuais

## ✨ Funcionalidades

* **Pesquisa por Cidade:** Permite ao usuário buscar o clima de qualquer cidade do mundo.
* **Dados em Tempo Real:** Exibe a temperatura atual, umidade e velocidade do vento.
* **Ícones Dinâmicos:** A imagem de fundo e o ícone mudam de acordo com as condições climáticas (ensolarado, nublado, chuvoso, neve, névoa, etc.).
* **Design Responsivo (Opcional):** O layout se adapta a diferentes tamanhos de tela. *(Se você não fez isso, pode remover esta linha)*
* **Tratamento de Erros:** Exibe uma mensagem de erro (usando a imagem `404.png`) se a cidade não for encontrada.

## 💻 Tecnologias Utilizadas

Este projeto foi construído utilizando as seguintes tecnologias:

* **HTML5:** Para a estrutura da página.
* **CSS3:** Para a estilização e design.
* **JavaScript (ES6+):** Para a lógica da aplicação, manipulação do DOM e requisições à API.
* **API (Ex: OpenWeatherMap):** Utilizado para buscar os dados de clima.

## 🚀 Como Executar o Projeto

Como é um projeto front-end simples, basta seguir os passos:

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/juliolvv/WeatherApp.git](https://github.com/juliolvv/WeatherApp.git)
    ```
2.  Navegue até o diretório do projeto:
    ```bash
    cd WeatherApp
    ```
3.  Abra o arquivo `index.html` no seu navegador de preferência.

### 🔑 Chave de API

Para que a aplicação funcione, é necessário ter uma chave de API de um serviço de meteorologia (como o [OpenWeatherMap](https://openweathermap.org/)).

* Crie sua conta e obtenha sua chave de API gratuita.
* No arquivo `index.js`, encontre a variável onde a chave deve ser inserida e cole a sua.

*(Exemplo de onde colar no `index.js` - ajuste conforme seu código)*
```javascript
// Dentro de index.js
const apiKey = "SUA_CHAVE_DE_API_VEM_AQUI";
