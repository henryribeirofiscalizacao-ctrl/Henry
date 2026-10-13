# Estudo de caso · Mundo dos E-books

[← Voltar ao portfólio](../README.md) · [Conhecer a Leninha Digital](https://www.leninhadigital.com.br)

## Contexto
Plataforma voltada a conteúdos digitais, experiência de leitura de e-books e administração de materiais.

## Escopo de desenvolvimento
- Interfaces de navegação, catálogo e leitura.
- Recursos associados à visualização e ao processamento de documentos.
- Organização administrativa do conteúdo.
- Planejamento de mecanismos de prévia e acesso aos materiais.

## Tecnologias identificadas no projeto

| Finalidade | Tecnologias presentes no repositório |
|---|---|
| Interfaces | React |
| Ferramentas de desenvolvimento | Vite, Node.js |
| Estrutura de dados | Drizzle ORM, cliente libSQL |
| Recursos editoriais | Tiptap |
| Manipulação e visualização de PDF | pdf-lib, PDF.js, PDFKit |
| Testes | Node.js Test Runner, Vitest, Testing Library |
| Autenticação | better-auth |

As dependências foram verificadas no manifesto do projeto. Sua presença não significa, por si só, que cada recurso esteja habilitado na versão disponibilizada aos usuários.

## Decisões de experiência
O leitor deve ter foco no conteúdo, leitura confortável e interações previsíveis. Uma área de administração separada ajuda a organizar materiais e configurações. Processos que envolvem autenticação e acesso precisam de validação específica antes de serem disponibilizados em produção.

## Demonstração pública · Leninha Digital
O projeto **Mundo dos E-books** tem como apresentação pública o site [Leninha Digital](https://www.leninhadigital.com.br), vinculado ao projeto `mundo-dos-ebooks` na Vercel. A última implantação consultada estava em estado **READY**, o que indica uma publicação concluída, mas não valida automaticamente o funcionamento de cada funcionalidade.

O código-fonte e as configurações de produção permanecem privados. Veja também o [resumo da apresentação pública](./leninha-digital.md).

> Não são publicados dados internos, credenciais, chaves ou detalhes operacionais do ambiente.
