# Matriz técnica · Tecnologias verificadas

[← Voltar ao portfólio](../README.md)

Este inventário foi preparado a partir dos **manifestos de dependências** do Sem Filtro Notícias e do Mundo dos E-books e de arquivos de documentação e configuração associados a uma implantação do RadarImob.

| Tecnologia | Sem Filtro Notícias | RadarImob | Mundo dos E-books |
| :-- | :--: | :--: | :--: |
| React | ✓ | ✓ | ✓ |
| TypeScript | ✓ | ✓ | — |
| Next.js | ✓ | ✓ | — |
| Node.js | ✓ | ✓ | ✓ |
| Tailwind CSS | ✓ | — | — |
| Vite | ✓ | — | ✓ |
| PostgreSQL | Dependências no workspace | ✓ | — |
| libSQL | ✓ | — | ✓ |
| Prisma ORM | — | ✓ | — |
| Drizzle ORM | — | — | ✓ |
| Tiptap | — | — | ✓ |
| PDF.js e ferramentas PDF | — | — | ✓ |
| Testes/validação configurados | ✓ | ✓ | ✓ |

**Como ler a matriz:** o símbolo ✓ significa *presença verificada na configuração ou documentação técnica consultada*. Não afirma utilização em todas as páginas, disponibilidade em produção, proficiência individual ou que o sistema não contenha outras tecnologias.

### Fontes técnicas internas consultadas

- **Sem Filtro Notícias:** manifestos do workspace principal, da aplicação editorial e do frontend legado. Identificadas dependências React, TypeScript, Next.js, Vite, Tailwind, libSQL e bibliotecas SQL, além de scripts de build, lint, testes e typecheck.
- **RadarImob:** README técnico, documentação de release e manifesto de dependências do projeto de implantação. Referências a Next.js, React, TypeScript, Prisma e PostgreSQL/Neon; scripts de validação e teste. Implantação principal localizada na equipe Vercel do projeto.
- **Mundo dos E-books:** manifesto com React, Vite, Tiptap, PDF.js, libSQL, Drizzle ORM e ferramentas de teste.

O código-fonte e a configuração de ambiente desses projetos permanecem privados. A finalidade deste documento é oferecer evidência de stack sem expor implementação proprietária.

## Glossário rápido

- **React:** biblioteca de interfaces.
- **Next.js:** framework de aplicações web baseado em React.
- **TypeScript:** linguagem que adiciona tipagem ao ecossistema JavaScript.
- **Vite:** ferramenta de desenvolvimento e build.
- **Prisma / Drizzle:** ferramentas de interação e modelagem de dados.
- **PostgreSQL / libSQL:** tecnologias de banco de dados.
- **Tiptap / PDF.js:** recursos para edição e leitura de conteúdo digital.

## Para conhecer os projetos

[Sem Filtro Notícias](./sem-filtro-noticias.md) · [RadarImob](./radar-imob.md) · [Mundo dos E-books](./mundo-dos-ebooks.md)
