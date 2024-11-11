# Desafio Técnico - Desenvolvimento de Link de Pagamento

Bem-vindo(a) ao desafio técnico da **One Payments**! Neste desafio, sua missão é desenvolver um **link de pagamento** que leve diretamente ao checkout, onde o usuário poderá visualizar os detalhes de um pagamento e realizar a transação. Além disso, você deverá criar uma API que simule o processamento do pagamento e armazene os dados da transação em um banco de dados.

## Descrição do Desafio

Você deve criar um **link de pagamento** que redirecione para uma página de checkout. Essa página de checkout deve exibir as informações do pagamento e permitir que o usuário finalize a transação através de uma API simulada de pagamento. A seguir, estão os requisitos detalhados e critérios de avaliação.

### Requisitos Funcionais

1. **Acesso ao Checkout via Link:**
   - Criar um link de pagamento único que leva diretamente para a página de checkout. Esse link deve conter um identificador exclusivo para cada transação.

2. **Página de Checkout:**
   - Exibir informações do pagamento, como:
     - Valor
     - Descrição do produto ou serviço
     - Nome do beneficiário
   - Permitir que o usuário insira as informações do método de pagamento, como dados de cartão de crédito (simulados) ou outros métodos.

3. **Simulação do Processamento de Pagamento:**
   - Desenvolver uma **API** que simule o processamento do pagamento. Essa API deve:
     - Receber as informações de pagamento enviadas pelo checkout.
     - Retornar uma resposta simulada de sucesso ou falha do pagamento.
     - Armazenar o status e os detalhes da transação em um banco de dados.

4. **Confirmação de Pagamento:**
   - Redirecionar o usuário para uma página de confirmação que exibe o status da transação (aprovado ou rejeitado) com base na resposta da API.
   - O banco de dados deve armazenar o status da transação e outros dados relevantes para rastreabilidade.

### Requisitos Técnicos

- **Backend:** Escolha livre de tecnologia para o backend (Node.js, PHP, C#, etc.), com a capacidade de manipular dados de forma segura e eficiente e a utilização de um framework da respectiva linguagem.
- **Frontend:** A página de checkout pode ser desenvolvida com VueJS.
- **Banco de Dados:** Armazene o status da transação e outros detalhes relevantes no banco de dados, garantindo rastreabilidade.
- **API de Simulação de Pagamento:** Crie uma API própria que simule o processo de pagamento e interaja com o banco de dados.
- **Segurança:** Validação de dados no backend, autenticação básica (se aplicável) e proteção contra injeções de código e outros ataques comuns.

### Instruções de Entrega

1. **Repositório Git:** 
   - A prova deverá ser entregue em um repositório Git (GitHub, GitLab, ou Bitbucket). O repositório pode ser público ou privado; em caso de privacidade, conceda acesso ao repositório para nossa equipe.

2. **Commits Parciais:** 
   - Esperamos ver **commits parciais** ao longo do desenvolvimento, demonstrando a evolução do seu código. Esses commits devem descrever as alterações realizadas em cada etapa, para que possamos acompanhar seu processo de raciocínio e implementação.

### Critérios de Avaliação

1. **Funcionalidade Completa:** O link de pagamento deve levar diretamente ao checkout com todos os passos necessários, incluindo o processamento via API simulada e o armazenamento dos dados no banco.
2. **Boas Práticas de Segurança:** Demonstração de preocupação com segurança no tratamento de dados, validação e proteção contra vulnerabilidades comuns.
3. **Qualidade do Código e Documentação:** Código organizado e documentado, incluindo um README explicativo com instruções para instalação e testes.
4. **Design e Usabilidade:** Interface de checkout intuitiva e agradável, com foco na experiência do usuário.
5. **Commits e Evolução do Código:** Verificaremos a sequência dos commits para entender como o desenvolvimento progrediu e as decisões feitas ao longo do caminho.

### Instruções de Entrega

1. **Repositório Git:** 
   - A prova deverá ser entregue em um repositório Git **público** no GitHub.
   - O repositório deve ser criado a partir de um **fork deste repositório**, garantindo que o histórico de desenvolvimento esteja claramente documentado.

2. **Prazo de Entrega:**
   - O prazo para conclusão da prova é de **7 dias** a partir do momento em que você recebeu as instruções.

3. **Commits Parciais:** 
   - Esperamos ver **commits parciais** ao longo do desenvolvimento, demonstrando a evolução do seu código. Esses commits devem descrever as alterações realizadas em cada etapa, para que possamos acompanhar seu processo de raciocínio e implementação.

4. **Documente como executar sua aplicação**
    - No repositório de sua aplicação, esperaremos ver um README.MD com instruções claras e funcionais de como rodar sua aplicação do zero. Tenha em mente que o ambiente do avaliador não é o mesmo que o seu então documente extensivamente e com troubleshooting para garantir que sua aplicação rode e possa ser corrigida.

### Considerações Finais

Este desafio foi desenhado para simular uma situação real de desenvolvimento de um checkout de pagamento, com integração de uma API de processamento simulada. Esperamos que aproveite a experiência para mostrar suas habilidades e criatividade!

Boa sorte, e estamos ansiosos para ver seu trabalho! 


---

Equipe de Recrutamento  
**One Payments**
