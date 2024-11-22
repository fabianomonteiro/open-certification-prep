# Open Certification Prompts (Português - pt-br)

Bem-vindo ao **Open Certification Prompts**, um repositório open-source que fornece prompts de prática para exames de certificação. Este repositório tem como objetivo ajudar candidatos a se prepararem para exames de certificação, oferecendo simulações interativas e realistas que refletem o estilo e a complexidade dos exames oficiais.

## Visão Geral

Este repositório contém prompts projetados para simular questões de exames de certificação de diversos provedores, incluindo AWS, CKAD, e outros. Cada prompt oferece perguntas práticas, feedback em tempo real e recursos adicionais para reforçar o aprendizado.

### Recursos dos Prompts

- **Interatividade:** Prompts que guiam os usuários em simulações personalizadas com feedback imediato e explicações.
- **Reforço de Aprendizado:** Flashcards e explicações detalhadas para fortalecer a compreensão.
- **Distribuição de Questões:** Alinhado à estrutura oficial do exame, distribuindo perguntas com base nas porcentagens dos tópicos.
- **Atualizações Contínuas:** Prompts são atualizados regularmente para acompanhar mudanças nos requisitos de certificação.

## Status de Validação dos Prompts

| Certificação                          | Nível        | [ChatGPT](https://chatgpt.com) | [Claude](https://claude.ai) | [Gemini](https://gemini.google.com) | [Perplexity](https://www.perplexity.ai) | [Meta AI](https://www.meta.ai) | Status                |
|---------------------------------------|--------------|---------------------------------------|-----------------------------------------|---------------------------------------------|-------------------------------------------|--------------------------------|-----------------------|
| AWS Certified Cloud Practitioner       | Foundational | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Ativo                 |
| AWS Certified AI Practitioner          | Foundational | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Ativo                 |
| AWS Certified SysOps Administrator     | Associate    | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Ativo                 |
| AWS Certified Solutions Architect      | Associate    | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Ativo                 |
| AWS Certified Developer                | Associate    | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Ativo                 |
| AWS Certified Machine Learning Engineer| Associate    | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Ativo                 |
| AWS Certified Data Engineer            | Associate    | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Ativo                 |
| AWS Solutions Architect Professional   | Professional | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Ativo                 |
| AWS DevOps Engineer Professional       | Professional | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Ativo                 |
| AWS Machine Learning Specialty         | Specialty    | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Ativo                 |
| AWS Security Specialty                 | Specialty    | ❓                                     | ❓                                     | ❓                                         | ❓                                        | ❓                             | Em Desenvolvimento    |
| AWS Advanced Networking Specialty      | Specialty    | ❓                                     | ❓                                     | ❓                                         | ❓                                        | ❓                             | Em Desenvolvimento    |
| AWS Database Specialty                 | Specialty    | ❓                                     | ❓                                     | ❓                                         | ❓                                        | ❓                             | Em Desenvolvimento    |
| AWS Data Analytics Specialty           | Specialty    | ❓                                     | ❓                                     | ❓                                         | ❓                                        | ❓                             | Em Desenvolvimento    |
| AWS SAP on AWS Specialty               | Specialty    | ❓                                     | ❓                                     | ❓                                         | ❓                                        | ❓                             | Em Desenvolvimento    |

**Legenda:**
- ✅ Testado e funcional
- ⚠️ Testado, mas com inconsistências
- ❌ Testado e não funcional
- ❓ Ainda não testado

**Versões Utilizadas**:
1. **ChatGPT**: GPT-4, GPT-4o
2. **Claude**: Claude 3.5 Sonnet
3. **Gemini**: Gemini Pro 1.5
4. **Perplexity**: Versão não divulgada
5. **Meta AI (Llama)**: Llama 3.2

## Estrutura do Repositório

```
pt-br/
├── aws/
│   ├── 01-foundational/
│   │   ├── ai-practitioner.md
│   │   └── cloud-practitioner.md
│   ├── 02-associate/
│   │   ├── data-engineer.md
│   │   ├── developer.md
│   │   ├── machine-learning-engineer.md
│   │   ├── solutions-architect.md
│   │   └── sysops-admin.md
│   ├── 03-professional/
│   │   ├── devops-engineer.md
│   │   └── solutions-architect.md
│   └── 04-specialty/
│       └── machine-learning.md
└── README.md
```

## Como Usar

1. **Escolha um Provedor de Certificação:** Navegue até o diretório correspondente ao provedor (e.g., `aws`).
2. **Selecione uma Certificação:** Localize o diretório da certificação e nível desejado.
3. **Copie e Cole o Prompt:** Utilize o prompt no modelo de IA escolhido (e.g., ChatGPT, Claude).
4. **Simulação Interativa:** Responda às perguntas e receba feedback em tempo real com explicações detalhadas.
5. **Revisão com Flashcards:** Opcionalmente, revise conceitos importantes usando flashcards baseados nas perguntas respondidas.

## Contribuindo

Contribuições são bem-vindas! Veja como participar:

1. **Faça um Fork do Repositório:** Crie sua cópia pessoal do repositório.
2. **Crie uma Branch de Feature:** `git checkout -b feature/nova-certificacao`
3. **Commit das Alterações:** `git commit -m 'Adiciona prompts para nova certificação'`
4. **Envie para Sua Branch:** `git push origin feature/nova-certificacao`
5. **Abra um Pull Request:** Proponha suas alterações para revisão.

### Diretrizes de Contribuição

- Organize os prompts por provedor de certificação e nível.
- Atualize a tabela de status de validação e documente requisitos específicos.
- Inclua exemplos de uso e feedback esperado para novos prompts.

## Licença

Este projeto está licenciado sob a **[Licença GNU General Public License v3.0](LICENSE)**.  
Ao usar ou contribuir para este projeto, você concorda em cumprir os termos desta licença.