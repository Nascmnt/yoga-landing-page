# 🧘 Serena Yoga

## 📌 Sobre o projeto

Este projeto foi desenvolvido como parte de uma atividade prática da disciplina **Fundamentos da Programação Web**.

A proposta da atividade consiste na criação de uma **landing page para um pequeno negócio ou profissional autônomo**, utilizando apenas **HTML e CSS**.

Para a realização do projeto, foi escolhido o ramo de **yoga**, criando uma página para divulgar os serviços de uma instrutora fictícia chamada **Serena Yoga**.

---

## 🎯 Objetivo da atividade

O objetivo da atividade é desenvolver uma página web única que apresente informações importantes sobre uma empresa ou profissional e incentive os visitantes a entrarem em contato.

A página deve ser acessível tanto em computadores quanto em dispositivos móveis.

Os principais requisitos da atividade são:

- Criar uma landing page para um pequeno negócio ou profissional autônomo;
- Utilizar HTML e CSS puros;
- Aplicar o conceito de layout responsivo;
- Utilizar Flexbox para organizar os elementos da página;
- Criar pelo menos cinco seções com informações relevantes;
- Incluir produtos ou serviços, benefícios e formas de contato.

---

## 💡 Minha solução

Para atender aos requisitos, desenvolvi uma landing page para uma **instrutora de yoga**.

A página foi organizada em diferentes seções para apresentar informações sobre a profissional e incentivar o usuário a entrar em contato.

As principais seções desenvolvidas foram:

### 🏠 Apresentação

A primeira seção apresenta a proposta da instrutora e contém uma chamada para ação, convidando o usuário a agendar uma aula.

### 👩 Sobre a instrutora

Apresenta informações sobre a profissional e sua proposta de trabalho.

### 🧘 Serviços

Apresenta as modalidades de aulas oferecidas:

- Yoga para iniciantes;
- Aulas individuais;
- Aulas em grupo.

### 🌿 Benefícios

Apresenta alguns benefícios relacionados à prática de yoga, como:

- Maior flexibilidade;
- Redução do estresse;
- Melhoria da concentração;
- Bem-estar.

### 📋 Como funciona

Explica de forma simples o processo para começar as aulas.

### 💬 Depoimentos

Apresenta exemplos de experiências de alunos para tornar a página mais atrativa e gerar maior confiança no serviço.

### 📧 Contato

A última seção contém um formulário para que o visitante possa informar seus dados e entrar em contato com a instrutora.

---

## 🛠️ Tecnologias utilizadas

O projeto foi desenvolvido utilizando:

- **HTML5** — estrutura da página;
- **CSS3** — estilização e aparência;
- **Flexbox** — organização dos elementos na tela;
- **Media Queries** — adaptação do layout para diferentes tamanhos de tela.

Também foram utilizadas:

- **Google Fonts** para as fontes;
- **Unsplash** para imagens gratuitas.

---

## 📱 Responsividade

A página foi desenvolvida para funcionar em diferentes tamanhos de tela.

Em telas maiores, alguns elementos são apresentados lado a lado utilizando **Flexbox**.

Em dispositivos menores, como celulares, o layout é reorganizado para que os elementos sejam exibidos em coluna, facilitando a leitura e a navegação.

Exemplo:

```css
@media (max-width: 48rem) {
    .hero-container {
        flex-direction: column;
    }
}
```

---

## 📁 Estrutura do projeto

```text
yoga-landing-page/
│
├── index.html
├── README.md
│
└── css/
|    └── style.css
└── images
```

---

## ✨ Considerações finais

Este projeto foi desenvolvido com foco na prática dos conceitos básicos de desenvolvimento web.

Durante a atividade, foram aplicados conhecimentos de estruturação com HTML, estilização com CSS, organização de layouts utilizando Flexbox e técnicas básicas de responsividade.

A proposta foi criar uma solução visualmente organizada, simples de navegar e adaptável para diferentes dispositivos, atendendo aos requisitos apresentados na atividade.