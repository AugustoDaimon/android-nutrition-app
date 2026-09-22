# Aplicação Android de Nutrição

Aplicação mobile nativa desenvolvida em **Java para Android** como projeto acadêmico, com foco na criação de uma experiência personalizada de planejamento alimentar a partir das características e objetivos do utilizador.

O projeto explora fluxos de cadastro em múltiplas etapas, apresentação de refeições, favoritos, exercícios e diferentes interfaces para acompanhamento do plano alimentar.

> **Status:** Arquivado — projeto acadêmico desenvolvido durante uma etapa inicial de aprendizado em desenvolvimento Android.

## 📱 Funcionalidades

### Cadastro e personalização

A aplicação possui um fluxo de cadastro dividido em múltiplas etapas para coletar informações utilizadas na personalização da experiência:

* Informações pessoais;
* Características físicas;
* Restrições alimentares;
* Objetivos relacionados à alimentação;
* Definição de perfil para diferentes objetivos.

O fluxo direciona o utilizador para diferentes experiências de acordo com o objetivo selecionado.

### 🍽️ Planejamento alimentar

A aplicação apresenta refeições organizadas de acordo com diferentes momentos do dia, incluindo:

* Café da manhã;
* Almoço;
* Jantar;
* Visualização de pratos através de cartões;
* Navegação horizontal e vertical entre opções;
* Sistema de favoritos.

### 🏃 Exercícios

Além do planejamento alimentar, a aplicação possui uma seção dedicada à apresentação de exercícios complementares ao plano.

### 👤 Perfil

O perfil do utilizador permite visualizar informações e acessar as refeições marcadas como favoritas.

---

## 🏗️ Estrutura

A aplicação foi desenvolvida utilizando a arquitetura tradicional de aplicações Android baseada em **Activities, Fragments, Adapters e XML Layouts**.

Entre os principais componentes estão:

```text
Cadastro1NomeFragment
Cadastro5FisicoFragment
Cadastro6RestAlimFragment
Cadastro8ObjetivoFragment

Cadastro9GanharActivity
Cadastro9PerderActivity

PratosCardView
PrincipalSlideAdapter
FavoriteDishesAdapter

Exercicios22Fragment
UserProfile
Usuario
```

A interface utiliza layouts XML e componentes visuais baseados em Views e Cards para apresentação das informações.

---

## 🛠️ Tecnologias

* **Java**
* **Android SDK**
* **Android Activities**
* **Android Fragments**
* **XML Layouts**
* **Adapters**
* **CardView**

---

## 🎯 Objetivos do projeto

O projeto teve como principais objetivos:

* Praticar desenvolvimento de aplicações Android nativas;
* Trabalhar com Activities e Fragments;
* Desenvolver interfaces utilizando XML;
* Criar fluxos de navegação entre diferentes telas;
* Trabalhar com componentes reutilizáveis através de Adapters;
* Implementar uma experiência de cadastro em múltiplas etapas;
* Desenvolver uma aplicação orientada a um problema específico de domínio.

---

## 📚 Contexto acadêmico

Este projeto representa uma etapa inicial da minha formação em desenvolvimento de software e foi desenvolvido no contexto acadêmico.

A implementação utiliza padrões e decisões arquiteturais compatíveis com o estágio de aprendizado em que o projeto foi desenvolvido.

---

## 📌 Status

**Arquivado.**

O projeto não recebe mais desenvolvimento ativo e é mantido principalmente como registro de aprendizado e experiência acadêmica em desenvolvimento Android nativo.
