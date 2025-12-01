 Testes Automatizados com Playwright – Formulário de Cadastro

Este projeto contém testes automatizados desenvolvidos com **Playwright** para validar um formulário de cadastro de usuários.

  Funcionalidades testadas
1. Carregamento Inicial da Página
2. Validação de Campos Obrigatórios
3. Cadastro Bem-Sucedido
4. Prevenção de Cadastros Duplicados
5. Limpeza da Lista de Usuários

  Instalação
```bash
npm init -y
npm install -D @playwright/test
npx playwright install
```

  Como rodar os testes
```bash
npx http-server .
npx playwright test
```

  Estrutura
- index.html
- estilo.css
- script.js
- tests/tests.spec.js
- README.md
