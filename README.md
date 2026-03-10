# Projeto Extensionista - Sistema de gerenciamento para o Centro de Informação à pessoa com deficiência
Integrantes:
- Pedro Lucas Câmara Rodrigues Lopes - 10753510
- Luana de Paiva Brito - 10750121
- Louisy Dalchiavon Tomazi - 10755895
- Murilo Arevalo - 10743851
- Victor Pereira - 10755205

## Sumário
- Introdução / Ideação
- Protótipo
- ...

## Ideação
A ideia do nosso projeto veio pela denúncia de uma das integrantes do grupo frente a falta de divulgação de um importantíssimo projeto do governo, o "Centro de Informação à pessoa com deficiência". O projeto busca divulgar a existência do projeto, ampliar sua relevância e auxiliar os profissionais envolvidos em tarefas administrativas, como na coleta e preenchimento eletrônico de formulários para requisitar o serviço de manutenção de aparelhos fornecido pelo projeto. 
Para resolver estes problemas, o projeto será composto por:
- Uma landing page introdutória, com visual moderno e acessível
- Uma página de formulário para o agendamento dos consertos
- Uma visualização em calendário, com status de aceitação e dados informados, para os consertos agendados (visando acesso administrativo apenas)

O caráter extensionista tem o objetivo de atingir a comunidade de pessoas com deficiência (cegos/baixa visão e pessoas com restrição de mobilidade, principalmente), pois o conhecimento dessa Central de Informação é muito raro, geralmente apenas funcionários do metrô das estações Santa Cruz, Tatuapé e Barra Funda divulgam essas informações oralmente. Além do desconhecimento desse auxílio do governo, as pessoas que o conhecem não possuem acesso aos dias de funcionamento do recurso, o que resulta em viagens perdidas ou necessidade de deslocamento a uma rota completamente diferente do caminho planejado pela pessoa.
Visto a dificuldade de locomoção dessas pessoas, a falta dessas informações e de facilidade de comunicação com esses serviços acaba se tornando um empencílio à essa comunidade. A proposta se torna parte do nosso cotidiano por um dos integrantes trabalhar na operação da estação de metrô "Santa Cruz", tendo contato com o público todos os dias.

## Protótipo

~ Não conseguimos adicionar o wireframe por conta do github

## Tutorial
---

# 1. Cabeçalho do Site (Header)

O cabeçalho é a parte superior do site e normalmente contém o **menu de navegação**.

```html
<header>
    <nav>
        <img src="logo.png" alt="Logo">
        <a href="index.html">Home</a>
        <a href="index.html">Sobre nós</a>
        <a href="index.html">Galeria</a>
        <a href="index.html">Eventos</a>
        <a href="index.html">Depoimentos</a>
        <a href="index.html">Locais</a>
        <a href="index.html">Agendar reparo</a>
        <a href="index.html">Entrar</a>
    </nav>
</header>
````

### Elementos presentes no menu:

* **Logo do site**
* **Links de navegação**

  * Home
  * Sobre nós
  * Galeria
  * Eventos
  * Depoimentos
  * Locais
* **Botões de ação**

  * Agendar reparo
  * Entrar

A tag `<nav>` indica que o conteúdo dentro dela é responsável pela **navegação do site**.

---

# 2. Seção de Introdução

Essa seção apresenta o projeto logo no início da página.

```html
<section>
    <h3>INTRODUÇÃO</h3>
    <h1>Centro de Informação à pessoa com deficiência</h1>
    <p>Lorem ipsum...</p>
    <a href="index.html">Agendar reparo</a>
</section>
```

### Elementos da seção

* **Subtítulo (`h3`)** – identifica a introdução.
* **Título principal (`h1`)** – nome do projeto.
* **Parágrafo (`p`)** – texto de apresentação.
* **Botão (`a`)** – link para agendamento de reparo.

Essa área geralmente é chamada de **Hero Section** em desenvolvimento web.

---

# 3. Seção "Sobre Nós"

Apresenta informações sobre a instituição ou projeto.

```html
<section>
    <h1>Sobre Nós</h1>
    <p>Lorem ipsum...</p>
    <img src="https://img.freepik.com/...">
</section>
```

### Conteúdo da seção

* **Título da seção**
* **Texto explicativo**
* **Imagem ilustrativa**

O objetivo dessa seção é **explicar o propósito do projeto e sua importância**.

---

# 4. Seção Galeria

Mostra imagens relacionadas ao projeto ou às atividades realizadas.

```html
<section>
    <h1>Galeria</h1>
    <p>Lorem ipsum...</p>

    <section>
        <img src="galeria1.png" alt="Galeria 1">
        <img src="galeria2.png" alt="Galeria 2">
        <img src="galeria3.png" alt="Galeria 3">
        <img src="galeria1.png" alt="Galeria 4">
        <img src="galeria2.png" alt="Galeria 5">
        <img src="galeria3.png" alt="Galeria 6">
    </section>
</section>
```

### Características da galeria

* Contém **6 imagens**.
* Cada imagem possui o atributo `alt`, importante para:

  * acessibilidade
  * leitores de tela
  * SEO

Normalmente essas imagens são organizadas com **CSS Grid ou Flexbox**.

---

# 5. Seção de Eventos

Essa área apresenta **eventos ou atividades organizadas pelo projeto**.

Estrutura de um evento:

```html
<section>
    <section>
        <h3>Lorem Ipsum is simply dummy</h3>
        <p>Lorem ipsum dolor sit amet...</p>
        <button>Ver mais</button>
    </section>

    <section>
        <img src="imagem.jpg" alt="Imagem do evento">
    </section>
</section>
```

### Cada evento possui

* **Título**
* **Descrição**
* **Botão "Ver mais"**
* **Imagem representativa**

O evento é dividido em duas partes:

* **informações**
* **imagem**

---

# 6. Seção de Depoimentos

Mostra opiniões ou comentários de pessoas sobre o serviço.

```html
<section>
    <section>
        <img src="imagem.jpg" alt="Imagem de postagem">
    </section>

    <section>
        <p>“Definitely one of the best burgers in town!”</p>
        <p>Jennifer Silva</p>
    </section>
</section>
```

### Estrutura do depoimento

* Foto da pessoa
* Comentário
* Nome do autor

Esse tipo de seção ajuda a **gerar confiança no site**.

---

# 7. Seção de Locais

Apresenta informações sobre locais ou unidades.

```html
<section>
    <section>
        <h1>Locais</h1>
        <p>Lorem ipsum dolor sit amet...</p>
    </section>

    <section>
        <img src="imagem.jpg" alt="Imagens dos postos">
    </section>
</section>
```

### Conteúdo da seção

* Título da área
* Texto explicativo
* Imagem representando os locais

---

# 8. Rodapé do Site (Footer)

O rodapé aparece no final da página e contém informações institucionais.

```html
<footer>
    <section>
        <img src="logo_exemplo.png">
        <p>
        A inclusão acontece quando se aprende com as diferenças
        e não com as igualdades.” — Paulo Freire
        </p>
    </section>

    <section id="nomes">
        <p>
        © 2026 - Centro de Informação à pessoa com deficiência.
        Desenvolvido por: Pedro Lopes, Luana Brito, Louisy Tomazi,
        Murilo Arevalo e Victor Pereira | Site desenvolvido com software livre
        </p>
    </section>
</footer>
```

### Elementos do rodapé

**Primeira seção**

* Logo do projeto
* Frase inspiradora de **Paulo Freire**

**Segunda seção**

* Direitos autorais
* Nome do projeto
* Créditos dos desenvolvedores
* Informação sobre uso de software livre

O `id="nomes"` permite **aplicar estilos específicos no CSS**.

---

# 9. Resumo Geral da Estrutura do Site

O código HTML organiza o site usando **tags semânticas**, que ajudam na organização e acessibilidade.

### Principais tags usadas

* `<header>` → cabeçalho do site
* `<nav>` → menu de navegação
* `<section>` → divisão de conteúdos
* `<footer>` → rodapé da página

### Estrutura da página

1. **Header**

   * Logo
   * Menu de navegação

2. **Introdução**

   * Apresentação do projeto
   * Botão de ação

3. **Sobre Nós**

   * Informações institucionais

4. **Galeria**

   * Imagens do projeto

5. **Eventos**

   * Lista de atividades

6. **Depoimentos**

   * Comentários de usuários

7. **Locais**

   * Informações sobre unidades

8. **Footer**

   * Frase institucional
   * Créditos do site

---

# Conclusão

Esse código HTML cria a **estrutura básica de um site institucional**.
Com essa base é possível adicionar:

* **CSS** → para estilização e layout
* **JavaScript** → para interatividade
* **Responsividade** → adaptação para celulares e tablets

