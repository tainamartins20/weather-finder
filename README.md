# 🌤️ Projeto de Previsão do Tempo

Este é um projeto simples de consulta de clima, onde o usuário pode digitar o nome de uma cidade e visualizar as informações climáticas atuais. O projeto foi desenvolvido com o objetivo de praticar integração com APIs, manipulação de DOM e design responsivo.

## 🔗 Visualizar Projeto

[Visualizar Projeto](https://tainamartins20.github.io/weather-finder)

## 📝 Descrição

A aplicação faz requisições à API da OpenWeatherMap e exibe na tela o nome da cidade, temperatura atual, umidade do ar, descrição do clima e um ícone representando a condição climática. Todo o layout foi desenvolvido com foco em um design moderno e agradável, utilizando efeito glassmorphism.

## 💻 Tecnologias Utilizadas

- HTML5  
- CSS3  
- JavaScript (ES6+)  
- OpenWeatherMap API

## 🌟 Funcionalidades

- Busca de clima por cidade digitada pelo usuário.
- Exibição de:
  - Nome da cidade.
  - Temperatura atual em Celsius.
  - Descrição atual do clima (ex: nublado, ensolarado, etc).
  - Umidade relativa do ar.
  - Ícone ilustrativo de acordo com o clima.
- Design responsivo e moderno com efeito de vidro (glassmorphism).
- Integração com a API OpenWeatherMap para dados em tempo real.

## 🗂️ Estrutura do Projeto

- `index.html`: Estrutura da aplicação.
- `style.css`: Estilização visual do projeto.
- `script.js`: Código JavaScript responsável pelas funcionalidades e integração com a API.

## ⚙️ Como Executar o Projeto

1. Faça o download ou clone o repositório:

```bash
git clone https://github.com/tainamartins20/weather-finder.git
```

2. Acesse a pasta do projeto:

```bash
cd weather-finder
```

3. Abra o arquivo `index.html` no seu navegador.

⚠️ **Atenção:** É necessário possuir uma chave da API da OpenWeatherMap. Insira sua chave na constante `key` localizada no arquivo `script.js`:

```javascript
const key = "sua-chave-aqui";
```

---

Desenvolvido por Tainá Martins 🚀
