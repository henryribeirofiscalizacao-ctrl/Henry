# Estudo de caso · RadarImob

[← Voltar ao portfólio](../README.md)

## Visão geral

O **RadarImob** é um projeto de plataforma SaaS para o setor imobiliário, estruturado para apoiar corretores na organização de imóveis, clientes, oportunidades comerciais e presença digital.

O projeto principal foi localizado na equipe **silad**, na Vercel, com histórico de implantações de produção. A disponibilidade do site público e o funcionamento de cada recurso precisam ser verificados separadamente.

## Visão de produto

A proposta reúne, em um mesmo ambiente digital:

- **Gestão de imóveis:** cadastro, informações e fotos dos imóveis.
- **Relacionamento com clientes:** registro de contatos e preferências.
- **Leads e acompanhamento comercial:** fluxos de atendimento e visão de oportunidades.
- **Correspondência entre interesses e imóveis:** mecanismos de matching com critérios comparáveis.
- **Painéis de gestão:** ambiente para uso dos corretores.
- **Presença digital:** páginas de imóveis e perfis públicos voltados à divulgação.

Estas frentes constam da documentação técnica associada ao projeto. A apresentação descreve seu **escopo técnico** e não atesta que todas estejam disponíveis em produção.

## Stack identificada

| Área | Tecnologia |
| --- | --- |
| Aplicação web | Next.js |
| Interface | React |
| Linguagem | TypeScript |
| Acesso a dados | Prisma ORM |
| Banco de dados | PostgreSQL / Neon |
| Implantação | Vercel |

## Desafios de engenharia

**Dados multi-tenant.** Uma plataforma usada por diferentes corretores precisa separar corretamente os contextos e os registros de cada conta.

**Jornada comercial.** Imóveis, leads, clientes e atendimento devem formar um fluxo consistente, da descoberta ao acompanhamento.

**Conteúdo público e privado.** O sistema reúne páginas voltadas à divulgação e áreas autenticadas, o que exige delimitar permissões e responsabilidades.

**Crescimento do produto.** A arquitetura de uma solução SaaS demanda organização, versionamento, testes e alterações incrementais.

## Situação e demonstração

Há uma implantação principal com estado **READY** na Vercel. Esse estado confirma a conclusão do processo de implantação, mas não garante por si só que o domínio esteja acessível ou que todas as funcionalidades estejam validadas.

A demonstração da aplicação e os detalhes de arquitetura podem ser apresentados mediante contato.

---

*Estudo de caso público e resumido. O código-fonte, os dados de clientes, as credenciais e as configurações privadas não são divulgados.*
