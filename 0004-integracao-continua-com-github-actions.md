# 0004 - Integração contínua com GitHub Actions

Date: 2025-10-03

## Status
Accepted

## Context
O projeto está hospedado no GitHub e precisa de uma ferramenta de integração contínua para automatizar testes e deploy. A equipe busca uma solução gratuita, fácil de configurar e integrada ao repositório.

## Decision
Utilizar GitHub Actions como ferramenta de integração e entrega contínua.

## Consequences
**Positivas**
- Configuração simples via arquivos YAML.
- Integração nativa com GitHub.
- Gratuito para projetos públicos.

**Negativas**
- Limitações de tempo de execução em planos gratuitos.
- Dependência da infraestrutura do GitHub.
