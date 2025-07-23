# Template Repository

Este é um template repository para projetos de desenvolvimento.

## 📁 Estrutura do Projeto

```
├── src/           # Código fonte
├── tests/         # Testes
├── docs/          # Documentação
├── .github/       # Configurações do GitHub
│   ├── workflows/ # GitHub Actions
│   └── ISSUE_TEMPLATE/ # Templates de issues
├── .gitignore     # Arquivos ignorados pelo Git
└── README.md      # Este arquivo
```

## 🚀 Como Usar Este Template

1. Clique em "Use this template" no GitHub
2. Clone o repositório criado
3. Instale as dependências necessárias
4. Comece a desenvolver!

## 🔧 Configuração do Pre-commit

Este template inclui configuração completa do pre-commit para Python/Flask e frontend.

### Instalação

```bash
# Instalar pre-commit
pip install pre-commit

# Instalar os hooks
pre-commit install
```

### Hooks Incluídos

**Python/Flask:**
- **Black**: Formatação automática de código
- **isort**: Organização de imports
- **flake8**: Linting e verificação de estilo
- **bandit**: Análise de segurança
- **mypy**: Type checking
- **safety**: Verificação de vulnerabilidades em dependências

**Frontend:**
- **prettier**: Formatação de CSS, JS, HTML
- **eslint**: Linting JavaScript

**Gerais:**
- Remoção de espaços em branco
- Verificação de arquivos YAML/JSON
- Detecção de conflitos de merge
- Commitizen para conventional commits

## 📋 Próximos Passos

- [ ] Configurar requirements.txt para Python
- [ ] Adicionar workflows do GitHub Actions
- [ ] Configurar package.json (se usar frontend JS)
- [ ] Adicionar templates de issues e pull requests
- [ ] Personalizar este README com informações do seu projeto

## 🤝 Contribuindo

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.