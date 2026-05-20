## Definição do Problema e Ideia de Solução – YSERV

O **YSERV** é um aplicativo que tem como objetivo conectar clientes a prestadores de serviços de forma prática, segura e confiável.

---

## 🔎 Problema Identificado

Atualmente, muitas pessoas enfrentam dificuldades para:

- Encontrar profissionais confiáveis.
- Avaliar a qualidade do serviço antes da contratação.
- Comparar preços e experiências de outros clientes.
- Ter segurança na escolha do prestador.

Além disso, profissionais autônomos muitas vezes não possuem um canal estruturado para divulgar seu trabalho, apresentar portfólio e conquistar novos clientes.

---

## 💡 Ideia de Solução

O **YSERV** surge como uma plataforma digital que:

- Conecta clientes e prestadores de serviço.
- Permite avaliação por notas e feedbacks.
- Oferece espaço para portfólio profissional.
- Facilita a busca por serviços por categoria e localização.
- Aumenta a transparência e confiança nas contratações.

---

## Especificação do Projeto

Nesta parte do documento serão abordados os seguintes tópicos e técnicas:

## 📌 Técnicas e Ferramentas Utilizadas

### 1. Diagrama de Personas
- Utilizado para representar perfis fictícios de usuários reais.
- Ajuda a compreender necessidades, dores e expectativas.

### 2. Histórias de Usuário (User Stories)
Escritas no formato:

> “Como [tipo de usuário], quero [objetivo] para [benefício].”

- Auxiliam na definição clara das funcionalidades.

### 3. Levantamento de Requisitos

- **Requisitos Funcionais:** descrevem o que o sistema deve fazer.
- **Requisitos Não Funcionais:** descrevem como o sistema deve se comportar (desempenho, segurança, usabilidade etc.).

### 4. Identificação de Restrições do Projeto

- Tecnológicas  
- Orçamentárias  
- Prazo  
- Legais (LGPD)


Essas técnicas garantem que o sistema seja desenvolvido com foco real nas necessidades do usuário.

## Persona 
### Persona 1

<img width="800" height="569" alt="image" src="https://github.com/user-attachments/assets/fd4db67f-6eeb-43b9-861f-8d90df4ba78d" />

### Persona 2

<img width="800" height="569" alt="image" src="https://github.com/user-attachments/assets/1ce469a1-233b-4160-94e6-5c8376c16160" />


### Persona 3

<img width="800" height="569" alt="image" src="https://github.com/user-attachments/assets/44db0572-af35-4d97-87ec-6bb53fd1ec8c" />


### Persona 4

<img width="800" height="569" alt="image" src="https://github.com/user-attachments/assets/b468ff1f-9157-4275-bd7a-4eac9466f3dc" />




---

## Histórias de Usuários

Com base na análise das personas foram identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Mariana Oliveira  | Ver notas e comentários de outros clientes sobre os profissionais        |Avaliar a qualidade do serviço antes da contratação            |
|Rose Alves       | Filtrar diaristas por localização e avaliação                | Encontrar rapidamente uma profissional próxima e bem recomendada |
| Guilherme Souza | Divulgar seus serviços e receber avaliações de clientes | Conquistar credibilidade e garantir renda estável |
| Maria Aparecida | Divulgar seus serviços e receber recomendações de clientes | Conseguir novos contratos e garantir estabilidade financeira para sua família |

---

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

| ID      | Descrição do Requisito                                                                 | Prioridade |
|---------|----------------------------------------------------------------------------------------|------------|
| RF-001  | A aplicação deve permitir que o usuário cliente realize cadastro e login na plataforma | ALTA       |
| RF-002  | A aplicação deve permitir que o prestador de serviço realize cadastro e login na plataforma | ALTA   |
| RF-003  | A aplicação deve permitir que o cliente pesquise profissionais por categoria de serviço | ALTA      |
| RF-004  | A aplicação deve permitir que o cliente filtre profissionais por localização           | ALTA       |
| RF-005  | A aplicação deve permitir que o cliente visualize o perfil do profissional com descrição, avaliações e portfólio | ALTA |
| RF-006  | A aplicação deve permitir que o prestador cadastre e edite seu portfólio com imagens e descrição dos serviços | ALTA |
| RF-007  | A aplicação deve permitir que o cliente avalie o profissional com nota                 | ALTA       |
| RF-008  | A aplicação deve permitir que o cliente deixe comentários (feedback) sobre o serviço prestado | ALTA |
| RF-009  | A aplicação deve permitir que os profissionais sejam ordenados por nota média          | MÉDIA      |
| RF-010  | A aplicação deve permitir comunicação entre cliente e prestador via chat interno       | MÉDIA      |
| RF-011  | A aplicação deve permitir que o cliente visualize o histórico de serviços contratados | MÉDIA      |
| RF-012  | A aplicação deve realizar verificação de identidade do prestador de serviço (ex: CPF/CNPJ válido) no momento do cadastro | ALTA |
| RF-013  | A aplicação deve permitir validação de regularidade do prestador conforme exigências legais aplicáveis | ALTA |
| RF-014  | A aplicação deve exibir no perfil do profissional um selo de “Prestador Verificado” após confirmação da documentação | ALTA |
| RF-015  | A aplicação deve permitir que o cliente realize o pagamento dos serviços diretamente pela plataforma, utilizando métodos de pagamento integrados | ALTA |
| RF-016  | A aplicação deve notificar o prestador de serviço quando receber um novo pedido de contratação, por meio de notificação na plataforma, e-mail ou alerta sonoro | ALTA |

### Requisitos não Funcionais

| ID      | Descrição do Requisito | Prioridade |
|---------|------------------------|------------|
| RNF-001 | A aplicação deve ser responsiva, funcionando em dispositivos móveis e desktops | ALTA |
| RNF-002 | A aplicação deve garantir autenticação segura dos usuários | ALTA |
| RNF-003 | A aplicação deve proteger os dados dos usuários conforme a LGPD | ALTA |
| RNF-004 | A aplicação deve processar requisições em no máximo 3 segundos | MÉDIA |
| RNF-005 | A aplicação deve possuir interface intuitiva e de fácil usabilidade | MÉDIA |
| RNF-006 | A aplicação deve manter disponibilidade mínima de 95% do tempo | BAIXA |
| RNF-007 | A aplicação deve permitir escalabilidade para suportar aumento de usuários | BAIXA |
| RNF-008 | A aplicação deve garantir que os dados utilizados para verificação legal sejam tratados com segurança e criptografia | ALTA |
| RNF-009 | A aplicação deve estar em conformidade com a LGPD no armazenamento e processamento de dados pessoais | ALTA |
| RNF-010 | O sistema de verificação deve minimizar fraudes e cadastros falsos | MÉDIA |

---

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

| ID  | Restrição |
|-----|-----------|
| 01  | O projeto deverá ser entregue até o final do semestre letivo |
| 02  | Não poderá ser desenvolvido um módulo de backend próprio |
| 03  | A aplicação deverá funcionar utilizando apenas tecnologias permitidas pela disciplina |
| 04  | A verificação de prestadores deverá utilizar apenas validações simuladas ou serviços externos prontos, devido à ausência de backend |
| 05  | O armazenamento de dados deverá ser feito utilizando soluções locais (ex: LocalStorage) ou serviços de terceiros (ex: Firebase), respeitando a limitação de não desenvolver backend próprio |
| 06  | O escopo deverá ser limitado a um MVP (Produto Mínimo Viável), priorizando funcionalidades essenciais |
| 07  | O projeto deverá respeitar a Lei Geral de Proteção de Dados (LGPD), mesmo em ambiente acadêmico |
| 08  | O orçamento para o desenvolvimento é limitado, não sendo permitido o uso de serviços pagos |

---

## Diagrama de Casos de Uso

<img width="804" height="454" alt="image" src="https://github.com/user-attachments/assets/f09c27f5-b2ac-460d-8b31-fbaa897084bb" />
