# 🗺️ Criando sua Aventura

História interativa "Em busca da cidade perdida" com HTML, CSS e JavaScript - projeto da Alura.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## 📑 Sumário

- [Sobre](#sobre)
- [Como funciona](#como-funciona)
- [Tecnologias](#tecnologias)
- [Como executar](#como-executar)
- [Estrutura](#estrutura)
- [Licença](#licença)

## 📖 Sobre

Aventura de escolhas múltiplas: o jogador encontra uma carta antiga e decide entre Rio de Janeiro e Pernambuco, avançando por passos até a cidade perdida no Amazonas. Cada escolha mostra/esconde um `.passo`.

## ⚙️ Como funciona

- Cada cena é uma `div.passo` com `id="passo-N"`
- Botões `.btn-proximo` têm `data-proximo="N"` com o próximo passo
- `script js` alterna a classe `ativo` para navegar

Exemplo:

```html
<button class="btn-proximo" data-proximo="1">Rio de Janeiro</button>
```

> [!TIP]
> Para criar um final novo, duplique um bloco `.passo`, dê um novo `id` e aponte um botão para ele.

## 🛠️ Tecnologias

- HTML5
- CSS3 (fonte Bai Jamjuree)
- JavaScript (navegação por passos)

## 🚀 Como executar

```bash
git clone https://github.com/VictorHFL/criando-sua-aventura.git
cd criando-sua-aventura
# abra index.html no navegador
```

## 📁 Estrutura

```text
criando-sua-aventura/
├── index.html
├── style.css
├── script js
├── img/
└── README.md
```

> [!NOTE]
> O arquivo de script se chama `script js` (com espaço). Renomeá-lo para `script.js` exige atualizar o `<script>` no HTML.

## 📄 Licença

Distribuído sob a licença MIT. Veja [LICENSE](LICENSE) para detalhes.

