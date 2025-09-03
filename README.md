# Controle de Tarefas

Um sistema simples de **controle de tarefas** desenvolvido para estudo, utilizando **Laravel**.  
O objetivo principal foi praticar conceitos fundamentais de desenvolvimento web com PHP, MVC e banco de dados.

---

## 🚀 Funcionalidades
- ✅ Criar, visualizar, editar e excluir tarefas (CRUD).  
- ✅ Validação de formulários para garantir consistência dos dados.  
- ✅ Armazenamento em banco de dados via Eloquent ORM.  
- ✅ Interface simples utilizando Blade (HTML, CSS e, opcionalmente, Bootstrap).  
- ✅ Filtros básicos para organização (pendente, concluída, data limite).  
- ✅ Estrutura MVC do Laravel aplicada.  
- 🔒 Autenticação de usuários com login/logout.  

---

## 🛠️ Tecnologias Utilizadas
- **Backend:** PHP com Laravel  
- **Frontend:** Blade + HTML/CSS + Bootstrap
- **Banco de Dados:** MySQL ou SQLite  
- **Controle de versão:** Git/GitHub  

---

## 📦 Instalação e execução local
Clone o repositório e instale as dependências:

```bash
git clone https://github.com/GustavoZkD/controle-tarefas.git
cd controle-tarefas
composer install
cp .env.example .env
php artisan key:generate
```

Configure o arquivo **.env** com as credenciais do seu banco de dados e rode as migrações:

```bash
php artisan migrate --seed
```

Por fim, inicie o servidor local:

```bash
php artisan serve
```

Acesse no navegador: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 📂 Estrutura básica do projeto
```
app/
  Http/Controllers/   # Controladores
  Models/             # Modelos (Eloquent ORM)
database/
  migrations/         # Migrações do banco
resources/views/      # Views (Blade)
routes/               # Definições de rotas
tests/                # Testes automatizados
```

---

## 🎯 Objetivo do projeto
Este projeto foi criado com foco em **aprendizado**, cobrindo os seguintes pontos:
- Conceitos de **MVC** no Laravel  
- Roteamento e controladores  
- Criação e execução de **migrações**  
- Uso do **Eloquent ORM** para persistência de dados  
- Construção de formulários e **validação**  
- Noções de autenticação de usuários  
- Criação de **views reutilizáveis** com Blade  

---

## 🤝 Contribuindo
1. Faça um fork do projeto  
2. Crie uma branch para sua feature: `git checkout -b minha-feature`  
3. Faça commit das alterações: `git commit -m 'Adicionando nova feature'`  
4. Envie para o repositório remoto: `git push origin minha-feature`  
5. Abra um Pull Request  

---

## 📄 Licença
Este projeto está sob a licença **MIT**.  
Sinta-se livre para estudar, modificar e utilizar como quiser.
