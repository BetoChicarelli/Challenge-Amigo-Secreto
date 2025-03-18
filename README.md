Challenge Amigo Secreto

## 🌟 Sobre o Projeto
Este projeto consiste em uma aplicação web simples para sorteio de **Amigo Secreto**. Ele permite que os usuários adicionem nomes a uma lista e realizem um sorteio aleatório para determinar quem será o amigo secreto.

---

## 🛠️ Tecnologias Utilizadas
- **HTML** - Estrutura do projeto. (Fornecida)
- **CSS** - Estilização da interface. (Fornecida)
- **JavaScript** - Manipulação da lista e lógica do sorteio.

---

## 📝 Funcionalidades
- Adicionar nomes à lista.
- Exibir os nomes adicionados.
- Sortear um nome de forma aleatória.
- Garantir que um nome não seja sorteado mais de uma vez (evitando repetições indesejadas).

---

## 🔧 Instalação e Execução

### 1. Clonar o repositório (caso esteja no GitHub):
```sh
 git clone https://github.com/Betochicarelli/Challenge-Amigo-Secreto.git
```

### 2. Abrir o projeto
- Navegue até a pasta do projeto.
- Abra o arquivo `index.html` no navegador.

---

## 🌐 Publicação com GitHub Pages
1. No GitHub, acesse **Settings** > **Pages**.
2. Em **Branch**, selecione `main` e clique em **Save**.
3. Seu site estará disponível em: `https://Betochicarelli.github.io/Challenge-Amigo-Secreto`

---

## ⚡ Possíveis Problemas e Soluções

### 🔍 O JavaScript não está funcionando?
- Verifique se o arquivo `app.js` está no mesmo diretório que `index.html`.
- Confira se a referência no HTML está correta:
  ```html
  <script src="app.js" defer></script>
  ```
- Abra o console do navegador (`F12` > aba **Console**) para verificar erros.

### 🔍 O sorteio está repetindo nomes?
- Certifique-se de usar a versão do código que impede repetições:
  ```js
  let amigosSorteados = [];
  ```
- Reinicie o sorteio quando todos os nomes forem sorteados.

---

## 📚 Estrutura do Projeto
```sh
/
|-- index.html      # Arquivo principal (interface)
|-- style.css       # Estilos da página
|-- app.js          # Lógica do sorteio
|-- assets/         # Imagens e ícones
```

---

## 👤 Autor ✨
Projeto desenvolvido por **[Roberto Chicarelli](https://github.com/BetoChicarelli)**. 

