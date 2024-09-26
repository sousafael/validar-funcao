Beautiful Sum 📊
Beautiful Sum é um projeto simples que demonstra como configurar testes automatizados com Jest e integração contínua usando GitHub Actions. Este projeto contém uma função básica que soma dois números, e o workflow do GitHub Actions roda testes automaticamente sempre que alterações são enviadas para o repositório.

🚀 Funcionalidade
A função add(a, b) recebe dois números e retorna a soma deles.

📋 Requisitos
Node.js (v14 ou superior)
Jest (framework de testes)
🛠️ Instalação
Clone o repositório e instale as dependências:

bash
Copiar código
git clone https://github.com/SEU_USUARIO/meu-primeiro-projeto.git
cd meu-primeiro-projeto
npm install
🧪 Como Rodar os Testes
Você pode rodar os testes localmente usando o Jest:

bash
Copiar código
npm test
Os testes também são executados automaticamente por meio do GitHub Actions sempre que houver um push ou pull request na branch main.

📄 Testes
Teste: Verifica se add(1, 2) retorna 3.
Exemplo do teste:

javascript
Copiar código
test('adds 1 + 2 to equal 3', () => {
    expect(add(1, 2)).toBe(3);
});
🖥️ GitHub Actions
Este repositório usa GitHub Actions para integração contínua. O workflow executa o seguinte:

Instalação das dependências do Node.js.
Execução dos testes automatizados.
📦 Como Contribuir
Fork este repositório.
Crie uma nova branch: git checkout -b minha-nova-feature.
Envie suas alterações: git commit -m 'Adiciona nova feature'.
Faça o push da branch: git push origin minha-nova-feature.
Abra um pull request.
