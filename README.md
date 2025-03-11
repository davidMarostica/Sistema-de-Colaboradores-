# Sistema de Colaboradores

Este repositório contém a implementação de um sistema de gerenciamento de colaboradores desenvolvido como parte de um trabalho acadêmico para a Universidade Federal do Brasil (UFBRA). O projeto foi desenvolvido com fins educacionais, aplicando conceitos de **Programação Orientada a Objetos (POO)**.

## Tecnologias Utilizadas

- **Java 23**: Linguagem principal usada para a implementação do sistema.
- **IntelliJ IDEA**: IDE utilizada para o desenvolvimento, compilação e execução do código.

## Descrição do Projeto

O objetivo do projeto é criar uma estrutura de herança com uso de uma **classe abstrata** que serve como base para as classes especializadas. A aplicação foi projetada para gerenciar dois tipos de colaboradores:
- **Pessoa Física**: Informações específicas como nome, CPF, RG, idade e titulação.
- **Pessoa Jurídica**: Informações específicas como razão social, CNPJ, inscrição estadual e nome fantasia.

O sistema é capaz de exibir os dados dos colaboradores por meio de métodos genéricos herdados e métodos específicos sobrescritos.

## Funcionalidades

1. Criação de uma classe abstrata `Colaborador` contendo atributos e métodos genéricos.
2. Implementação das subclasses:
   - `PessoaFisica`: Gerencia os dados específicos de pessoas físicas.
   - `PessoaJuridica`: Gerencia os dados específicos de pessoas jurídicas.
3. Cadastro e exibição de informações de colaboradores.

## Estrutura do Código

O projeto segue a seguinte estrutura de pacotes:
src/ ├── br/com/colaboradores/ │ ├── Colaborador.java # Classe abstrata base │ ├── PessoaFisica.java # Subclasse de Colaborador │ └── PessoaJuridica.java # Subclasse de Colaborador └── br/com/principal/ └── Main.java # Classe principal para execução do programa


## Como Configurar e Executar

1. **Clonar o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/Sistema-de-Colaboradores.git
Abrir no IntelliJ IDEA:

Importe o projeto para o IntelliJ IDEA.

Certifique-se de que o SDK do Java 23 está configurado no ambiente.

Compilar e Executar:

Compile o código na classe principal Main.

Execute o programa diretamente no IntelliJ IDEA para visualizar os resultados no console.

Exportar o Projeto:

Para enviar o projeto em formato zipado, compacte toda a pasta do projeto (incluindo a pasta .idea, arquivos src e demais configurações).

Objetivo Educacional
Este projeto foi desenvolvido com o objetivo de:

Aplicar os conceitos de herança e polimorfismo na POO.

Compreender e implementar classes abstratas e métodos sobrescritos.

Estimular o uso de boas práticas na organização e implementação de sistemas baseados em objetos.

Nota: Este sistema é um trabalho acadêmico, desenvolvido exclusivamente para fins educacionais e de aprendizado no curso da Universidade Federal do Brasil (UFBRA).


Essa versão inclui um foco maior nos
