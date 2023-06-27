# Programação WEB 1

### UTFPR

## Proposta
O objetivo da aplicação é a criação de uma espécie de site de agendamento de salas de um edifício.

## Requisitos

- Coerência da aplicação. A aplicação resolve um problema? 

- Há no mínimo 5 páginas web? Exemplos: Principal, Contato, Carrinho de compras, Login, etc.

- Uso de no mínimo 5 elementos elaborados/customizados em ReactJS e reutilizados dentro do projeto? (Exemplos: cabeçalhos, rodapés, cards, listas, rótulos de texto, botões com ícones, imagens com legendas, tabelas, formulários).

- Posicionamento/tamanho/estilo adequados dos elementos de interface (cabeçalhos, rodapés, bordas, tamanhos, margens, cores). No mínimo 5 regras aplicadas em todo o projeto.

- Implementação de rotas e navegação entre páginas.

- Persistência de dados de ao menos 3 entidades (tabelas) usando Firebase ou qualquer outro backend de persistência. CRUD (Create, Recovery, Update e Delete) de cada tabela.

- Uso de REDUX.

- Aplicação de no mínimo 10 heurísticas de interface.

- Manter o estado de login na store do navegador.

## Agendamento de Ambientes

Este projeto é um sistema de agendamento de ambientes, desenvolvido com React e Redux.

### Instalação

Para executar o projeto localmente, siga as etapas abaixo:

1. Certifique-se de ter o Node.js instalado em seu ambiente de desenvolvimento.

2. Faça o download ou clone este repositório.

3. Navegue até a pasta raiz do projeto.

4. Execute o seguinte comando para instalar as dependências do projeto:

   ```
   npm install
   ```

### Configuração

Antes de executar o projeto, você precisará configurar as variáveis de ambiente necessárias. Certifique-se de ter uma conta no Firebase e obtenha as informações de configuração do Firebase para o projeto.

Crie um arquivo `.env` na pasta raiz do projeto e defina as seguintes variáveis de ambiente:

```
REACT_APP_FIREBASE_API_KEY=<sua-api-key>
REACT_APP_FIREBASE_AUTH_DOMAIN=<seu-domínio-de-autenticação>
REACT_APP_FIREBASE_PROJECT_ID=<seu-id-do-projeto>
```

### Executando o Projeto

Após concluir a configuração, você pode executar o projeto usando o seguint

e comando:

```
npm start
```

Isso iniciará o aplicativo em modo de desenvolvimento. Abra o navegador e acesse `http://localhost:3000` para visualizar o projeto.

### Principais Dependências

- "@testing-library/jest-dom": "^5.14.1"
- "@testing-library/react": "^11.2.7"
- "@testing-library/user-event": "^12.8.3"
- "firebase": "^8.10.0"
- "react": "^17.0.2"
- "react-dom": "^17.0.2"
- "react-redux": "^7.2.4"
- "react-router-dom": "^5.2.0"
- "react-scripts": "4.0.3"
- "redux": "^4.1.1"
- "redux-persist": "^6.0.0"
- "web-vitals": "^1.1.2"

Certifique-se de que todas as dependências estejam instaladas corretamente antes de executar o projeto.