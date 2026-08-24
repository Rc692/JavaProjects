# 📺 Smart TV System | Sistema Smart TV

🇧🇷 Um projeto desenvolvido em **Java** para simular o funcionamento básico de uma Smart TV, praticando conceitos fundamentais de **Programação Orientada a Objetos**.

🇺🇸 A **Java project** developed to simulate the basic operation of a Smart TV while practicing fundamental **Object-Oriented Programming** concepts.

---

## 🚀 Funcionalidades | Features

🇧🇷 O sistema permite controlar algumas funções básicas da televisão:

🇺🇸 The system allows you to control some basic TV functions:

* 🔌 **Ligar a TV | Turn the TV on**
* ⏻ **Desligar a TV | Turn the TV off**
* 📺 **Mudar de canal | Change channel**
* ⬆️ **Aumentar o canal | Increase channel**
* ⬇️ **Diminuir o canal | Decrease channel**
* 🔊 **Aumentar o volume | Increase volume**
* 🔉 **Diminuir o volume | Decrease volume**
* 📊 **Consultar canal atual | Check current channel**
* 🔊 **Consultar volume atual | Check current volume**
* 💡 **Consultar status da TV | Check TV status**

---

## 📂 Estrutura do Projeto | Project Structure

```text
Sistema Smart TV/
├── src/
│   ├── SmartTv.java
│   └── Usuario.java
└── README.md
```

| Arquivo        | Descrição                                                   | File           | Description                                                             |
| -------------- | ----------------------------------------------------------- | -------------- | ----------------------------------------------------------------------- |
| `SmartTv.java` | Classe responsável por representar e controlar a TV         | `SmartTv.java` | Class responsible for representing and controlling the TV               |
| `Usuario.java` | Classe responsável pela execução e demonstração das funções | `Usuario.java` | Class responsible for program execution and demonstrating the functions |

---

## ⚙️ Configuração Inicial | Initial Configuration

🇧🇷 Quando um objeto `SmartTv` é criado, a televisão começa com:

🇺🇸 When a `SmartTv` object is created, the television starts with:

```text
TV ligada: Não | No
Canal: 1
Volume: 25
```

Esses valores são definidos diretamente na classe `SmartTv`.

---

## 📖 Exemplo de Uso | Example of Use

### 🇧🇷 Português

O programa realiza operações como diminuir e aumentar o volume, consultar o canal atual, mudar para o canal 13 e ligar e desligar a TV.

```text
Volume Atual : 23
Canal Atual : 1
Canal Atual : 13
TV Esta Ligada ?false
Canal Atual : 13
Volume Atual : 23
Novo Status -> TV Ligada ?true
Novo Status -> TV Ligada ?false
```

### 🇺🇸 English

The program performs operations such as decreasing and increasing the volume, checking the current channel, changing to channel 13, and turning the TV on and off.

```text
Current Volume: 23
Current Channel: 1
Current Channel: 13
Is TV On? false
Current Channel: 13
Current Volume: 23
New Status -> TV On? true
New Status -> TV On? false
```

O fluxo de execução acima corresponde às operações implementadas em `Usuario.java`.

---

## 🧠 Conceitos Praticados | Concepts Practiced

🇧🇷 Este projeto permite praticar conceitos fundamentais de Java:

🇺🇸 This project allows you to practice fundamental Java concepts:

* 📦 **Classes e objetos | Classes and objects**
* 🔧 **Métodos | Methods**
* 🧩 **Atributos | Attributes**
* 🔄 **Alteração de estado de objetos | Object state changes**
* 📺 **Manipulação de dados de uma classe | Class data manipulation**
* ⌨️ **Saída de dados no console | Console output**
* 🏗️ **Programação Orientada a Objetos | Object-Oriented Programming**

---

## 💻 Métodos Principais | Main Methods

### `SmartTv.java`

🇧🇷 A classe `SmartTv` possui métodos para controlar o canal, volume e estado da televisão.

🇺🇸 The `SmartTv` class contains methods to control the channel, volume, and TV status.

```java
mudarCanal(int novoCanal)
aumentarCanal()
diminuirCanal()

aumentarVolume()
diminuirVolume()

ligar()
desligar()
```

---

## 🛠️ Tecnologias | Technologies

🇧🇷 Projeto desenvolvido utilizando:

🇺🇸 Project developed using:

* ☕ **Java**
* 📦 **JDK**
* 💻 **IDE para desenvolvimento Java | Java development IDE**

---

## 🎯 Objetivo | Objective

🇧🇷 O objetivo deste projeto é praticar os fundamentos da **Programação Orientada a Objetos em Java**, utilizando uma Smart TV como exemplo para trabalhar com classes, objetos, atributos e métodos.

🇺🇸 The objective of this project is to practice the fundamentals of **Object-Oriented Programming in Java**, using a Smart TV as an example to work with classes, objects, attributes, and methods.

---

## 📌 Observações | Notes

🇧🇷 Este é um projeto desenvolvido para **estudo e prática de programação em Java**. A implementação representa uma simulação simples de uma Smart TV e não possui integração com hardware ou uma televisão real.

🇺🇸 This project was developed for **Java programming study and practice**. The implementation is a simple Smart TV simulation and does not integrate with real hardware or a physical television.

---

## 📌 Status | Status

🟢 **Projeto de estudo | Study project**

---

## 👨‍💻 Projeto | Project

🇧🇷 Parte da coleção de projetos Java para prática e aprendizado.

🇺🇸 Part of a Java projects collection for learning and practice.
