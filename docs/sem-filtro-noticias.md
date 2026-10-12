# Estudo de caso · Sem Filtro Notícias

[← Voltar ao portfólio](../README.md) · [Acessar o portal](https://www.tvsemfiltronoticias.com.br)

## Contexto
Portal jornalístico com foco regional, publicação de matérias por editorias e administração de conteúdo. O projeto também contempla a criação e a gestão de portais regionais com identidade própria.

## Objetivos de produto
- Organizar o conteúdo editorial para leitura em desktop e dispositivos móveis.
- Permitir gerenciamento de matérias e componentes de apresentação.
- Estabelecer separação entre conteúdo e identidade visual dos diferentes portais.
- Facilitar manutenção e evolução do sistema com repositório versionado.

## Tecnologias identificadas no projeto

| Camada ou processo | Tecnologia |
|---|---|
| Interfaces | React, TypeScript |
| Experiência visual | Tailwind CSS |
| Aplicação editorial | Next.js |
| Fluxos de desenvolvimento | Node.js, Vite |
| Dados e consultas | Bibliotecas SQL, cliente libSQL |
| Validação | Scripts de teste, lint, typecheck e build |
| Versionamento | Git e GitHub |

A arquitetura completa contém componentes adicionais e permanece em repositório privado. A tabela resume tecnologias presentes nos arquivos de configuração do projeto, não representa uma auditoria de todas as funcionalidades em produção.

## Desafios de engenharia
**Multiplicidade editorial.** A apresentação e a configuração de diferentes portais exigem delimitar o que é compartilhado e o que pertence exclusivamente a cada identidade.

**Responsividade.** Navegação por editorias, leitura das matérias, proporções de imagens e menus precisam funcionar de modo consistente entre diferentes telas.

**Gestão de conteúdo.** A experiência de administração deve permitir operações editoriais com clareza, evitando impactos involuntários no material publicado.

**Qualidade e evolução.** O repositório dispõe de comandos de build, verificações de linguagem, typecheck, lint e testes. A presença desses comandos não constitui afirmação de cobertura total ou de execução automática de CI.

## Demonstração
O [site público](https://www.tvsemfiltronoticias.com.br) permite conhecer a experiência voltada ao leitor. Os recursos administrativos e o código de produção não estão disponíveis publicamente.

> Este estudo de caso é deliberadamente sintético: não reproduz configurações sensíveis, credenciais, infraestrutura detalhada ou código proprietário.
