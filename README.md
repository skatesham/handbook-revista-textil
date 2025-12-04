# 📚 Handbook Revista Têxtil

Central de conhecimento e cultura da Revista Têxtil.

[![Deploy MkDocs](https://github.com/revistatextil/handbook-revista-textil/actions/workflows/deploy.yml/badge.svg)](https://github.com/revistatextil/handbook-revista-textil/actions/workflows/deploy.yml)

## 🌐 Acesse Online

👉 **[https://revistatextil.github.io/handbook-revista-textil/](https://revistatextil.github.io/handbook-revista-textil/)**

---

## 🚀 Desenvolvimento Local

### Pré-requisitos

- Python 3.8+
- pip

### Instalação

```bash
# Clone o repositório
git clone https://github.com/revistatextil/handbook-revista-textil.git
cd handbook-revista-textil

# Crie um ambiente virtual (recomendado)
python -m venv venv
source venv/bin/activate  # Linux/Mac
# ou
venv\Scripts\activate  # Windows

# Instale as dependências
pip install -r requirements.txt
```

### Executando localmente

```bash
mkdocs serve
```

Acesse [http://127.0.0.1:8000](http://127.0.0.1:8000) no navegador.

### Build para produção

```bash
mkdocs build
```

Os arquivos estáticos serão gerados na pasta `site/`.

---

## 📁 Estrutura do Projeto

```
handbook-revista-textil/
├── docs/                    # Conteúdo do handbook
│   ├── assets/              # Imagens, logos, etc.
│   ├── adr/                 # Architecture Decision Records
│   ├── changelog/           # Histórico de mudanças
│   └── index.md             # Página inicial
├── .github/
│   └── workflows/
│       └── deploy.yml       # GitHub Actions para deploy
├── mkdocs.yml               # Configuração do MkDocs
├── requirements.txt         # Dependências Python
└── README.md
```

---

## 🔄 Deploy

O deploy é feito automaticamente via **GitHub Actions** quando há push na branch `main`.

O site é publicado no **GitHub Pages** através da branch `gh-pages`.

---

## 🤝 Contribuindo

1. Faça um fork do repositório
2. Crie uma branch para sua feature (`git checkout -b feature/nova-secao`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova seção'`)
4. Push para a branch (`git push origin feature/nova-secao`)
5. Abra um Pull Request

---

## 📝 Licença

Este projeto é de uso interno da Revista Têxtil.

---

<p align="center">
  Feito com ❤️ pela equipe <strong>Revista Têxtil</strong>
</p>
