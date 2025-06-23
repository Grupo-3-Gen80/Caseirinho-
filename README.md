# 🍛 Caseirinho+ – Plataforma de Apoio à Comida Caseira

> Valorize o empreendedorismo local e fortaleça a economia da sua comunidade.

## 📌 Sobre o Projeto

O **Caseirinho+** é uma plataforma web desenvolvida com o objetivo de **apoiar pequenos restaurantes de comida caseira**, proporcionando a eles um espaço para:

- Cadastrar seus produtos
- Cadastrar restaurantes

Além disso, o Caseirinho+ promove a **inclusão digital** e o **empreendedorismo social**, conectando consumidores a negócios locais.

---

## 🚀 Funcionalidades

- [x] Cadastro e login de usuários
- [x] Cadastro de restaurantes
- [x] Cadastro de produtos e vínculo com o restaurante
- [x] Chat de suporte 
- [x] Consumo autenticado com token JWT
- [x] Responsividade para mobile e desktop
- [x] Design intuitivo e acessível

---

## 🖥️ Tecnologias Utilizadas

### 👩‍💻 Frontend

- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [TailwindCSS](https://tailwindcss.com/)
- [Axios](https://axios-http.com/)
- [React Router DOM](https://reactrouter.com/)
- [Lucide Icons](https://lucide.dev/)
- [React Toastify](https://fkhadra.github.io/react-toastify/)

### 🔙 Backend (API fornecida pela Generation Brasil)

- Java 17
- Spring Boot
- Spring Security (JWT)
- JPA / Hibernate
- SQL

---

## 🧪 Como rodar o projeto localmente

### 🛠️ Pré-requisitos

- Node.js (v18+)
- Yarn ou NPM

### ⚙️ Instalação

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/caseirinho.git

# Acesse a pasta do projeto
cd caseirinho

# Instale as dependências
yarn install
```

### ▶️ Executando o projeto

```bash
# Inicie o projeto
yarn dev
```

A aplicação estará disponível em: [http://localhost:5173](http://localhost:5173.png)

---

## 🔐 Login de Teste

Você pode utilizar os seguintes usuários de exemplo:

```
Usuário: root@root.com
Senha: rootroot
```

---

## 📚 Documentação da API

- `POST /usuarios/cadastrar` – Cadastro de usuário
- `POST /usuarios/logar` – Login e retorno de token
- `GET /restaurantes` – Listagem de restaurantes
- `POST /produtos` – Cadastro de produto
- `PUT /produtos/prato-do-dia/{id}` – Definir prato do dia

> A API requer autenticação via Bearer Token para rotas protegidas.

---

## 💡 Diferenciais

- Proposta **social e inovadora**, voltada para a **valorização da comida caseira**
- Interface acessível e leve
- Fácil uso para públicos não familiarizados com tecnologia

---


## 📷 Screenshots

### Tela incial
![Tela inicial](https://i.imgur.com/pssf5Bg.png)

### Tela de produtos 
![Tela de produtos](https://i.imgur.com/kRd61RE.png)

### Tela de Restaurantes
![Tela de restaurantes](https://i.imgur.com/667Nwit.png)


## 🧭 Próximos Passos

- [ ] Integração com sistema de pedidos 
- [ ] Mapa de localização dos restaurantes
- [ ] Avaliação dos pratos pelos usuários
- [ ] Função Prato do dia
