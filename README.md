```md
# Validar soma de dois números 📊

**Validar Soma* é um projeto simples que demonstra como configurar testes automatizados com **Jest** e integração contínua usando **GitHub Actions**. O projeto contém uma função básica que soma dois números, e o workflow do GitHub Actions executa testes automaticamente sempre que há um `push` ou `pull request` para a branch `main`.

## 🚀 Funcionalidade

A função `add(a, b)` recebe dois números e retorna a soma deles.

## 📋 Requisitos

- Node.js (v14 ou superior)
- Jest (framework de testes)

## 🛠️ Instalação

Siga os passos abaixo para clonar o repositório e instalar as dependências:

```bash
git clone https://github.com/SEU_USUARIO/meu-primeiro-projeto.git
cd meu-primeiro-projeto
npm install
```

## 🧪 Como Rodar os Testes

Você pode rodar os testes localmente usando o Jest:

```bash
npm test
```

Os testes também são executados automaticamente por meio do **GitHub Actions** sempre que há um `push` ou `pull request` na branch `main`.

## 📄 Testes

- Teste: Verifica se `add(1, 2)` retorna `3`.

Exemplo do teste:

```javascript
test('adds 1 + 2 to equal 3', () => {
    expect(add(1, 2)).toBe(3);
});
```

## 🖥️ GitHub Actions

Este repositório usa **GitHub Actions** para integração contínua. O workflow executa os seguintes passos:

1. Instalação das dependências do Node.js.
2. Execução dos testes automatizados.

## 📦 Como Contribuir

1. Faça um fork deste repositório.
2. Crie uma nova branch: `git checkout -b minha-nova-feature`.
3. Envie suas alterações: `git commit -m 'Adiciona nova feature'`.
4. Faça o push da branch: `git push origin minha-nova-feature`.
5. Abra um pull request.

```

