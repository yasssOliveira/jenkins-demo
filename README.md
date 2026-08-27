# Jenkins Demo

Projeto desenvolvido para praticar **Integração Contínua (CI)** utilizando Java, Maven, testes automatizados e Jenkins.

## 📌 Sobre o projeto

O projeto foi desenvolvido como prática de integração entre um repositório GitHub e o Jenkins.

A ideia é que, a partir do código armazenado no GitHub, o Jenkins possa executar automaticamente o processo de build e os testes do projeto.

## 🛠️ Tecnologias

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge\&logo=openjdk\&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge\&logo=apachemaven\&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit-25A162?style=for-the-badge\&logo=junit5\&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge\&logo=jenkins\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)

## ⚙️ O que foi praticado

* Criação de aplicação em Java
* Organização de projeto com Maven
* Criação de testes automatizados
* Integração do projeto com GitHub
* Configuração do Jenkins
* Execução automática dos testes
* Integração Contínua
* Geração de relatório de cobertura de testes com JaCoCo

## 📂 Estrutura do projeto

```text
jenkins-demo/
├── src/
│   ├── main/
│   └── test/
├── pom.xml
└── README.md
```

## ▶️ Como executar

### Pré-requisitos

* Java
* Maven

### Executar os testes

```bash
mvn test
```

### Executar pelo Jenkins

O projeto pode ser configurado no Jenkins para buscar o código do GitHub e executar o processo de build e testes através do Maven.

## 🧪 Testes

Os testes automatizados são executados utilizando **JUnit**.

O projeto também utiliza **JaCoCo** para gerar informações sobre a cobertura dos testes.

## 🎯 Objetivo

O objetivo deste projeto foi colocar em prática conceitos de **Integração Contínua**, testes automatizados e automação do processo de build utilizando Jenkins.

---

Projeto desenvolvido para fins de estudo.
