# Automated Emails

O aplicativo lê os nomes, e-mails e endereços de uma arquivo Excel e envia um e-mail a cada usuário

## Instalar dependências

```bash
pipenv install pytest-cov --dev
```

## Instalar os scripts configurados do pre-commit

```bash
pipenv run pre-commit install -t pre-commit
pipenv run pre-commit install -t pre-push
```

## Rodar o Bandit

```bash
pipenv run python -m bandit .
```

## Rodar o Safety

```bash
pipenv run python -m safety check
```
