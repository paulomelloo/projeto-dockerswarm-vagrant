# 🐳 Configuração Automatizada de Cluster Docker Swarm com Vagrant do Curso DIO

Este projeto utiliza o **Vagrant** para provisionar automaticamente um cluster **Docker Swarm** com 4 máquinas virtuais: 1 nó **Manager** (`master`) e 3 nós **Workers** (`node01`, `node02`, `node03`).

O objetivo é criar um ambiente de laboratório leve e reproduzível para aprendizado e testes de orquestração de contêineres, garantindo que o Docker seja pré-instalado e o cluster Swarm seja inicializado e unido em uma única execução do comando `vagrant up`.

## 🛠️ Tecnologias Utilizadas

* **Vagrant:** Para a criação e gerenciamento das Máquinas Virtuais (VMs).
* **VirtualBox:** Como provedor de virtualização.
* **Docker Engine:** Instalado em todos os nós.
* **Docker Swarm:** Para orquestração dos contêineres.
* **Shell Script:** Para provisionamento e automação.

## ⚙️ Pré-requisitos

Para executar este projeto, você precisará ter instalado em sua máquina local:

1.  **[Vagrant](https://www.vagrantup.com/downloads):** Versão 2.2.0 ou superior.
2.  **[VirtualBox](https://www.virtualbox.org/wiki/Downloads):** A última versão estável.

## 🚀 Como Iniciar o Cluster

Siga os passos abaixo para subir e configurar seu cluster Docker Swarm.

### 1. Clonar o Repositório

```bash
git clone https://github.com/paulomelloo/projeto-dockerswarm-vagrant.git
cd projeto-dockerswarm-vagrant
