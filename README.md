# Flutter-2026-FIAP

Material Mobile Development


# Proposta de Grade Curricular

## Disciplina: Desenvolvimento Mobile com Flutter

### Cursos: 2º ano de Sistemas de Informação e 3º ano de Engenharia de Software

### Duração: 1 ano letivo

## 1. Objetivo da Disciplina

A disciplina tem como objetivo capacitar os alunos no desenvolvimento de aplicações mobile multiplataforma utilizando  **Dart e Flutter** , partindo dos fundamentos da linguagem até a construção de aplicativos completos, integrados com APIs, persistência local, autenticação, arquitetura, boas práticas e publicação.

Ao final da disciplina, o aluno deverá ser capaz de desenvolver aplicações mobile modernas para Android e iOS, utilizando uma única base de código, aplicando conceitos de interface, navegação, consumo de serviços, gerenciamento de estado, organização de projeto e entrega de produto.

## 2. Justificativa

O desenvolvimento mobile exige cada vez mais produtividade, escalabilidade e capacidade de entrega em múltiplas plataformas. Flutter se destaca como uma tecnologia moderna, mantida pelo Google, com forte adoção no mercado, excelente documentação, alta performance e grande comunidade.

A proposta também fortalece a formação prática dos alunos, aproximando a disciplina de demandas reais do mercado, com desenvolvimento de apps completos, integração com backend, persistência de dados e publicação.

## 3. Competências Desenvolvidas

Ao longo da disciplina, o aluno desenvolverá competências em:

* Programação com Dart;
* Criação de interfaces com Flutter;
* Uso de widgets stateless e stateful;
* Navegação entre telas;
* Organização de componentes;
* Consumo de APIs REST;
* Tratamento de erros e carregamento;
* Persistência local de dados;
* Gerenciamento de estado;
* Autenticação;
* Arquitetura de aplicações mobile;
* Testes básicos;
* Build e publicação de aplicativos;
* Desenvolvimento de projeto final com visão de produto.

## 4. Estrutura Anual da Disciplina

A disciplina será organizada em dois semestres:

* **1º semestre:** Fundamentos de Dart, Flutter, interface, navegação e primeiros aplicativos.
* **2º semestre:** Integração com APIs, persistência, arquitetura, autenticação, estado, testes, build e projeto final.

---

# 1º Semestre — Fundamentos de Dart e Flutter

## Módulo 1 — Introdução ao Desenvolvimento Mobile e ao Flutter

**Conteúdos:**

* Cenário do desenvolvimento mobile;
* Apps nativos x híbridos x multiplataforma;
* O que é Flutter;
* O que é Dart;
* Instalação do Flutter SDK;
* Configuração do ambiente;
* Android Studio, VS Code, emulador e dispositivo físico;
* Estrutura inicial de um projeto Flutter;
* Comandos básicos do Flutter CLI.

**Prática sugerida:**

Criar o primeiro app Flutter com alteração de textos, cores, tema e estrutura inicial.

**Entrega:**

App “Hello Flutter” personalizado com nome, imagem, cores e layout básico.

---

## Módulo 2 — Fundamentos da Linguagem Dart

**Conteúdos:**

* Variáveis e tipos de dados;
* String, int, double, bool;
* Operadores;
* Condicionais;
* Laços de repetição;
* List, Map e Set;
* Funções;
* Null Safety;
* Classes e objetos;
* Construtores;
* Encapsulamento;
* Herança e composição;
* Programação assíncrona com Future e async/await.

**Prática sugerida:**

Criar pequenos programas em Dart para resolver problemas de lógica e simular regras de negócio.

**Entrega:**

Lista de exercícios práticos em Dart com problemas de lógica, funções e orientação a objetos.

---

## Módulo 3 — Primeiros Widgets e Estrutura Visual

**Conteúdos:**

* MaterialApp;
* Scaffold;
* AppBar;
* Text;
* Container;
* Row;
* Column;
* Stack;
* Image;
* Icon;
* ElevatedButton;
* TextButton;
* FloatingActionButton;
* Padding e Margin;
* SizedBox;
* Card;
* ListTile;
* StatelessWidget;
* StatefulWidget;
* Hot Reload e Hot Restart.

**Prática sugerida:**

Construir telas estáticas inspiradas em apps reais, como perfil de usuário, card de produto, tela de login e tela de detalhes.

**Entrega:**

App com no mínimo três telas visuais utilizando widgets básicos e boas práticas de layout.

---

## Módulo 4 — Layouts Responsivos e Componentização

**Conteúdos:**

* Organização de widgets;
* Separação de arquivos;
* Componentização;
* Reaproveitamento de componentes;
* MediaQuery;
* Expanded;
* Flexible;
* SingleChildScrollView;
* ListView;
* GridView;
* Boas práticas de UI;
* Tema global;
* Cores, fontes e estilos;
* Criação de design system simples.

**Prática sugerida:**

Criar uma interface de catálogo de produtos, lista de cards ou tela de dashboard.

**Entrega:**

App com listagem de dados mockados, componentes reutilizáveis e layout responsivo.

---

## Módulo 5 — Navegação e Fluxo entre Telas

**Conteúdos:**

* Navigator;
* Rotas nomeadas;
* Passagem de parâmetros;
* Retorno de dados entre telas;
* BottomNavigationBar;
* Drawer;
* TabBar;
* Organização de navegação;
* Fluxo de login e área autenticada.

**Prática sugerida:**

Criar um app com menu inferior, tela inicial, tela de detalhes e tela de formulário.

**Entrega:**

App com navegação entre pelo menos quatro telas e passagem de dados entre elas.

---

## Módulo 6 — Formulários e Validações

**Conteúdos:**

* TextField;
* TextFormField;
* Form;
* GlobalKey;
* Validação de campos;
* Máscaras simples;
* Dropdown;
* Checkbox;
* Radio;
* Switch;
* DatePicker;
* Feedback visual para o usuário;
* SnackBar, Dialog e BottomSheet.

**Prática sugerida:**

Criar cadastro de usuário, cadastro de produto ou formulário de pedido.

**Entrega:**

App com formulário completo, validação e exibição dos dados cadastrados.

---

# Projeto Integrador do 1º Semestre

## Tema sugerido

Construção de um aplicativo mobile com dados locais/mockados.

## Exemplos de projetos

* App de tarefas;
* App de controle financeiro simples;
* App de catálogo de produtos;
* App de eventos;
* App de agenda acadêmica.

## Requisitos mínimos

* Mínimo de cinco telas;
* Navegação estruturada;
* Componentização;
* Formulários com validação;
* Listagem de dados;
* Tela de detalhes;
* Layout responsivo;
* Identidade visual definida;
* Código organizado em pastas;
* README com descrição do projeto.

---

# 2º Semestre — Flutter Aplicado ao Mercado

## Módulo 7 — Consumo de APIs REST

**Conteúdos:**

* Conceito de API REST;
* HTTP methods: GET, POST, PUT, PATCH e DELETE;
* Pacote http ou Dio;
* Requisições assíncronas;
* Serialização e desserialização JSON;
* Models;
* Tratamento de loading;
* Tratamento de erro;
* Empty state;
* Integração com APIs públicas.

**Prática sugerida:**

Criar app que consome uma API pública de filmes, clima, produtos, notícias ou usuários.

**Entrega:**

App integrado com API REST, exibindo listagem, detalhes, loading e tratamento de erro.

---

## Módulo 8 — Persistência Local

**Conteúdos:**

* SharedPreferences;
* Armazenamento simples;
* SQLite;
* Introdução ao sqflite;
* CRUD local;
* Cache de dados;
* Estratégias offline-first;
* Organização da camada de dados.

**Prática sugerida:**

Criar app de tarefas, favoritos ou anotações com persistência local.

**Entrega:**

App com CRUD local funcionando: cadastrar, listar, editar, excluir e persistir dados.

---

## Módulo 9 — Gerenciamento de Estado

**Conteúdos:**

* O que é estado em aplicações Flutter;
* setState;
* Limitações do setState;
* Provider;
* ChangeNotifier;
* Separação de responsabilidade;
* Estado global;
* Estado de carregamento;
* Estado de erro;
* Boas práticas.

**Prática sugerida:**

Criar carrinho de compras, controle de favoritos ou autenticação simulada.

**Entrega:**

App utilizando gerenciamento de estado para controlar dados compartilhados entre telas.

---

## Módulo 10 — Autenticação e Integração com Backend

**Conteúdos:**

* Fluxo de login;
* Cadastro de usuário;
* Token JWT;
* Armazenamento seguro de token;
* Rotas públicas e privadas;
* Interceptors;
* Logout;
* Firebase Authentication ou API própria;
* Boas práticas de autenticação.

**Prática sugerida:**

Criar app com login, cadastro, tela protegida e logout.

**Entrega:**

App com autenticação funcional, persistência de sessão e consumo de dados autenticados.

---

## Módulo 11 — Arquitetura e Boas Práticas

**Conteúdos:**

* Organização de pastas;
* Separação em camadas;
* Models;
* Services;
* Repositories;
* Controllers ou ViewModels;
* Clean Code;
* SOLID aplicado ao mobile;
* Tratamento centralizado de erros;
* Injeção de dependência básica;
* Ambientes de desenvolvimento e produção;
* Uso de arquivo .env.

**Prática sugerida:**

Refatorar um projeto existente para uma arquitetura mais organizada.

**Entrega:**

Projeto refatorado com separação clara entre UI, regra de negócio e acesso a dados.

---

## Módulo 12 — Recursos Nativos e Experiência do Usuário

**Conteúdos:**

* Permissões;
* Câmera;
* Galeria;
* Localização;
* Mapas;
* Notificações locais;
* Upload de imagem;
* Animações básicas;
* Acessibilidade;
* Performance;
* Boas práticas de UX em mobile.

**Prática sugerida:**

Criar funcionalidades nativas dentro do app final, como imagem de perfil, localização ou notificação.

**Entrega:**

App com pelo menos um recurso nativo integrado.

---

## Módulo 13 — Testes, Build e Publicação

**Conteúdos:**

* Testes unitários básicos;
* Testes de widget;
* Debug;
* Logs;
* Flutter DevTools;
* Build Android;
* Geração de APK;
* Geração de App Bundle;
* Noções de publicação na Play Store;
* Noções de publicação na App Store;
* Versionamento;
* README técnico;
* Apresentação do projeto.

**Prática sugerida:**

Preparar o projeto final para entrega, build e demonstração.

**Entrega:**

Build Android gerado, documentação final e apresentação técnica.

---

# Projeto Integrador Final

## Objetivo

Desenvolver um aplicativo mobile completo utilizando Flutter, aplicando os principais conceitos estudados durante o ano.

## Requisitos mínimos

* Aplicativo desenvolvido em Flutter;
* Uso da linguagem Dart;
* Mínimo de seis telas;
* Navegação estruturada;
* Componentização;
* Consumo de API REST;
* Persistência local;
* Gerenciamento de estado;
* Formulários com validação;
* Autenticação ou fluxo simulado de login;
* Tratamento de loading, erro e empty state;
* Pelo menos um recurso nativo;
* Código organizado;
* README completo;
* Protótipo ou referência visual;
* Build final gerado.

## Exemplos de temas para o projeto final

* App de eventos;
* App de controle acadêmico;
* App de marketplace;
* App de agendamento;
* App de tarefas colaborativas;
* App de catálogo com favoritos;
* App de gestão de pequenos negócios.

---

# Avaliação Sugerida

## 1º Semestre

| Critério                                             | Peso |
| ----------------------------------------------------- | ---: |
| Exercícios em Dart                                   |  20% |
| Apps práticos em sala                                |  25% |
| Projeto intermediário                                |  35% |
| Participação, evolução e organização do código |  20% |

## 2º Semestre

| Critério                                | Peso |
| ---------------------------------------- | ---: |
| Integrações com API e persistência    |  20% |
| Gerenciamento de estado e arquitetura    |  20% |
| Projeto final                            |  40% |
| Apresentação técnica e documentação |  20% |

---

# Adaptação por Curso

## 2º ano de Sistemas de Informação

Para Sistemas de Informação, a disciplina pode ter maior foco em:

* Construção de solução;
* Experiência do usuário;
* Integração com APIs;
* Aplicações voltadas a negócios;
* Persistência de dados;
* Entrega de produto funcional;
* Visão de mercado e empregabilidade.

## 3º ano de Engenharia de Software

Para Engenharia de Software, a mesma grade pode ser aplicada com maior profundidade em:

* Arquitetura;
* Padrões de projeto;
* Testes;
* Escalabilidade;
* Organização de camadas;
* Qualidade de código;
* Integração com backend;
* CI/CD básico;
* Build e publicação.

Assim, a base da disciplina permanece a mesma para os dois cursos, mas a profundidade das entregas e os critérios de avaliação podem variar conforme o perfil da turma.

---

# Resultado Esperado

Ao final do curso, o aluno será capaz de desenvolver aplicações mobile completas com Flutter, utilizando boas práticas de desenvolvimento, integração com serviços externos, persistência de dados, gerenciamento de estado, arquitetura organizada e preparação para publicação.

A disciplina entrega uma formação prática, moderna e alinhada ao mercado, preparando o aluno para atuar no desenvolvimento mobile multiplataforma com uma tecnologia atual, produtiva e reconhecida.
