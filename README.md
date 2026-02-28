```text
📁 Estrutura de Pastas

├── src/
│   ├── Controllers/
│   ├── Interfaces/
│   ├── Middlewares/
│   ├── Modules/
│   ├── Pipes/
│   ├── Services/
│   ├── Utils/
│   ├── app.controller.spec.ts
│   ├── app.controller.ts
│   ├── app.module.ts
│   ├── app.service.ts
│   └── main.ts
└── Tests/
```

---

## 📂 src/

Diretório principal da aplicação. Contém toda a estrutura de código da API construída com NestJS.

### Controllers/
Responsável por receber requisições HTTP e delegar a execução para os serviços correspondentes.

### Services/
Contém a lógica de negócio da aplicação. Serviços processam dados e coordenam regras antes de retornar resultados aos controllers.

### Interfaces/
Define contratos e tipagens utilizadas no sistema, garantindo padronização e desacoplamento entre implementações.

### Middlewares/
Camada responsável por interceptar requisições antes que cheguem aos controllers. Usado para autenticação, logging, validação global, etc.

### Pipes/
Utilizados para transformação e validação de dados de entrada antes de serem processados pelos controllers.

### Modules/
Organiza a aplicação em módulos independentes, permitindo separação de responsabilidades e escalabilidade do sistema.

### Utils/
Funções auxiliares puras e reutilizáveis, sem dependência direta do framework ou lógica de domínio.

### main.ts
Ponto de entrada da aplicação. Responsável por inicializar o servidor NestJS.

### app.module.ts
Módulo raiz da aplicação. Centraliza a configuração principal.

### app.controller.ts
Controller inicial do projeto.

### app.service.ts
Service base do projeto.

---

## 📂 Tests/

Contém testes automatizados, como testes unitários e de integração.

---

## 🎯 Objetivo da Estrutura

Essa organização foi definida para manter:

- Separação clara de responsabilidades
- Código escalável
- Facilidade de manutenção
- Base sólida para evolução futura
