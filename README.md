# Consulta API Bitcoin

Painel web que exibe a cotacao do **Bitcoin em tempo real** (em Reais), consumindo uma API publica de mercado de criptomoedas. O painel mostra o valor atual, as maximas e minimas do periodo e a data da ultima atualizacao, com refresh automatico.

## Funcionalidades

- Exibicao da cotacao atual do Bitcoin em Real (R$)
- Maxima e minima do periodo
- Data/hora da ultima atualizacao
- Atualizacao automatica dos dados em intervalos regulares

## Tecnologias

- **HTML5** e **CSS3** para a estrutura e o estilo
- **Vue.js** para a reatividade da interface (data binding)
- **Axios** para o consumo da API de cotacao

## Como executar

Por ser um projeto estatico (front-end), basta abrir o arquivo no navegador:

```bash
# Clonar o repositorio
git clone https://github.com/AlexandreJuniork1/Consulta_api_bitcoin.git
cd Consulta_api_bitcoin
```

Em seguida, abra o arquivo `index.html` diretamente no navegador (duplo clique) ou sirva a pasta com um servidor local, por exemplo:

```bash
# Usando a extensao Live Server do VS Code, ou:
python -m http.server 8000
# depois acesse http://localhost:8000
```

## Estrutura

```
Consulta_api_bitcoin/
├── index.html   # Estrutura da pagina + logica Vue/Axios
└── style.css    # Estilos do painel
```

---

Projeto desenvolvido por [Alexandre Junior](https://github.com/AlexandreJuniork1) como pratica de consumo de APIs e Vue.js.
