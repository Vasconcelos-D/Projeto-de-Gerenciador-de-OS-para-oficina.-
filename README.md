# 🔧 Sistema de Gerenciamento de Oficina

Sistema de gestão desenvolvido para facilitar o dia a dia do dono de oficina mecânica, centralizando o cadastro de clientes e veículos, o histórico de serviços realizados e um painel de acompanhamento das Ordens de Serviço (OS).

## 📌 Sobre o Projeto

Esse projeto nasceu da necessidade de simplificar a rotina administrativa de oficinas, que muitas vezes ainda controlam clientes, veículos e serviços em cadernos ou planilhas soltas. A proposta é oferecer uma ferramenta simples e direta, onde o dono da oficina consegue:

- Cadastrar clientes e seus respectivos veículos
- Manter um histórico completo de serviços realizados por veículo (tipo de serviço e valor gasto)
- Abrir e acompanhar Ordens de Serviço (OS)
- Visualizar indicadores do dia a dia da oficina (faturamento, carros atendidos, serviços realizados, clientes atendidos)

## ✨ Funcionalidades

### Cadastros
- [ ] Cadastro de clientes (nome, contato, endereço)
- [ ] Cadastro de veículos vinculados ao cliente (placa, modelo, marca, ano)
- [ ] Histórico de serviços por veículo (tipo de serviço, data, valor)

### Ordem de Serviço (OS)
- [ ] Abertura de OS vinculada a cliente/veículo
- [ ] Registro dos serviços realizados na OS
- [ ] Valor total da OS
- [ ] Status da OS (aberta, em andamento, finalizada)

### Painel / Dashboard
- [ ] Valor total faturado no dia
- [ ] Quantidade de carros atendidos no dia
- [ ] Lista de serviços realizados no dia
- [ ] Quantidade de clientes atendidos no dia

## 🚧 Status do Projeto

> Projeto em fase inicial de desenvolvimento.

Atualmente concluído:
- Página inicial (landing page) construída em **HTML5** e **Tailwind CSS**

Em definição:
- Linguagem/framework de back-end (as opções em avaliação são **Python** ou **Java com Spring Boot**)
- Banco de dados
- Estrutura da API

## 🛠️ Tecnologias

| Camada | Tecnologia |
|---|---|
| Front-end | HTML5, Tailwind CSS |
| Back-end | *A definir* (Python ou Java Spring Boot) |
| Banco de dados | *A definir* |

## 📂 Estrutura do Projeto

```
oficina-sistema/
├── public/              # Página de entrada (HTML/CSS)
├── src/                 # Código-fonte (a organizar conforme stack escolhida)
├── docs/                # Documentação adicional
└── README.md
```

## 🚀 Como Executar

> Seção a ser atualizada assim que a stack de back-end for definida.

Por enquanto, para visualizar a página de entrada:

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/oficina-sistema.git

# Acesse a pasta do projeto
cd oficina-sistema

# Abra o arquivo index.html no navegador
```

## 🗺️ Roadmap

- [ ] Definir stack de back-end (Python ou Java Spring)
- [ ] Modelar banco de dados (clientes, veículos, serviços, OS)
- [ ] Implementar CRUD de clientes e veículos
- [ ] Implementar módulo de Ordem de Serviço
- [ ] Implementar dashboard com indicadores diários
- [ ] Autenticação de usuário (dono da oficina)

## 🤝 Contribuições

Sugestões, ideias e contribuições são bem-vindas! Sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).

---

Desenvolvido com o objetivo de facilitar a gestão de oficinas mecânicas. 🚗
