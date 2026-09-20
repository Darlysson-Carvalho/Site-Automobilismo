# 🏁 Templo do Automobilismo

Site estático em **HTML puro** (sem CSS e sem JavaScript) reunindo história, tecnologia, regras e finanças das principais modalidades do automobilismo mundial — Rally (WRC), Endurance (WEC) e NASCAR — além de conteúdo complementar sobre lendas, pistas icônicas e um comparativo entre categorias.

## 📄 Páginas

Todos os arquivos abaixo ficam dentro da pasta `html/`.

| Página | Arquivo | Descrição |
|---|---|---|
| Main | `html/Main.html` | História, Acontecimentos do Automobilismo|
| Evolução | `html/Evolucao.html` | Evolução e avanço cientifico e tecnológico do Automobilismo |
| Formula1 | `html/Formula1.html` | História, tecnologia, Evolução e modernização dos carros |
| Mundial de Rally (WRC) | `html/Rally.html` | História, tecnologia (era híbrida Rally1) |
| Mundial de Endurance (WEC) | `html/WEC.html` | História, Hypercars (LMH/LMDh), Balance of Performance |
| NASCAR | `html/Nascar.html` | História, carro Next Gen, sistema de Charters e TV |
| Lendas do Automobilismo | `html/Lendas.html` | Grandes pilotos da história, com foco em Ayrton Senna |
| Pistas Famosas | `html/Pistas.html` | Os circuitos mais icônicos do automobilismo (Monza, Spa, Mônaco, Silverstone, Suzuka) |
| Inscrição | `html/Formulario.html` | Formulário de inscrição com checkboxes de categorias e frequência de contato |
| Comparativo | `html/Tabela.html` | Tabela comparando custos, audiência e outros dados entre F1, WRC, WEC e NASCAR |

Todas as páginas compartilham o mesmo menu de navegação (`<nav>`) no topo, permitindo circular livremente entre elas.

## 🛠️ Tecnologias

- **HTML5 puro** — sem `<style>`, sem `class`/`id` de estilização e sem CSS externo
- Sem JavaScript e sem dependências externas
- Formulário nativo (`<form>`, `<fieldset>`, `<input type="checkbox">`, validação HTML5 com `required`)
- Tabela nativa (`<table>`) para os dados comparativos
- Tags `<meta>` em todas as páginas (description, keywords, author,) 

## 📁 Estrutura de arquivos

```
├── html/
│   ├── Main.html
│   ├── Evolucao.html
│   ├── Formula1.html
│   ├── WEC.html
│   ├── Nascar.html
│   ├── Rally.html
│   ├── Lendas.html
│   ├── Pistas.html
│   ├── Formulario.html
│   └── Tabela.html
├── audio/
├── img/
├── video/
└── README.md
```

As pastas `audio/`, `img/` e `video/` guardam os recursos de mídia usados pelo site.

## ▶️ Como visualizar

Não há build, servidor ou dependências — é só abrir os arquivos no navegador.

```bash
git clone https://github.com/Darlysson-Carvalho/Site-Automobilismo.git
cd Site-Automobilismo
```

Depois, abra qualquer página (por exemplo `html/Rally.html`) diretamente no navegador.

## 🗺️ Roadmap

- [ ] Estilização visual (CSS) em uma versão futura, opcional
- [ ] Conectar `html/Formulario.html` a um backend real (hoje o `<form>` não envia dados a lugar nenhum)
- [ ] Avaliar a inclusão de novas categorias (Fórmula 1 como página própria, MotoGP, IndyCar)

## 🏷️ Versão

Este README documenta a **v1.0**, a primeira versão completa e funcional do site.

## 👤 Autor

**Darlysson Carvalho**
[GitHub](https://github.com/Darlysson-Carvalho)
