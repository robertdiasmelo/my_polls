# 🗳️ My Polls - Aplicativo de Enquetes em Django

Este é um projeto **Django** chamado **My Polls**, que permite a criação, gerenciamento e votação em enquetes interativas. A aplicação fornece uma interface simples para usuários votarem e visualizarem os resultados em tempo real.

---

## 🚀 Tecnologias Utilizadas

- **Python 3.12+**
- **Django 4+**
- **SQLite** (padrão) ou **PostgreSQL / MySQL**
- **HTML, CSS e JavaScript** para o frontend básico

---

## 📦 Instalação e Configuração

### **1️⃣ Clone o repositório**

```bash
git clone https://github.com/seu-usuario/my_polls.git
cd my_polls
```

### **2️⃣ Crie e ative um ambiente virtual**

```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate  # Windows
```

### **3️⃣ Instale as dependências**

```bash
pip install -r requirements.txt
```

### **4️⃣ Configure o banco de dados**

```bash
python manage.py migrate
```

### **5️⃣ Crie um superusuário para acessar o admin**

```bash
python manage.py createsuperuser
```

### **6️⃣ Execute o servidor**

```bash
python manage.py runserver
```

Acesse no navegador: [**http://127.0.0.1:8000/**](http://127.0.0.1:8000/)

---

## 🛠️ Estrutura do Projeto

```bash
my_polls/
│── mysite/          # Configuração principal do Django
│── polls/           # Aplicação de enquetes
│   ├── migrations/  # Controle de versões do banco de dados
│   ├── static/      # Arquivos estáticos (CSS, JS, imagens)
│   ├── templates/   # Templates HTML
│   ├── admin.py     # Configuração do Django Admin
│   ├── models.py    # Modelos do banco de dados
│   ├── tests.py     # Testes automatizados
│   ├── views.py     # Lógica das views
│── db.sqlite3       # Banco de dados SQLite (padrão)
│── manage.py        # Gerenciador do Django
│── requirements.txt # Dependências do projeto
│── README.md        # Este arquivo
```

---

## 📌 Funcionalidades

✅ Criar enquetes com múltiplas opções de resposta\
✅ Votar em enquetes existentes\
✅ Visualizar resultados em tempo real\
✅ Interface amigável e responsiva\
✅ Gerenciamento de enquetes via painel de administração do Django\
✅ Suporte para banco de dados PostgreSQL e MySQL

---

## 📊 Banco de Dados

Por padrão, o projeto usa **SQLite**, mas você pode mudar para **PostgreSQL** ou **MySQL** editando o arquivo `settings.py`:

**Exemplo para PostgreSQL:**

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'mydatabase',
        'USER': 'meu_usuario',
        'PASSWORD': 'minha_senha',
        'HOST': 'localhost',
        'PORT': '5432',
    }
}
```

Após configurar, rode:

```bash
python manage.py migrate
```

---

## 🔥 Executando Testes

Para garantir que tudo está funcionando corretamente, execute:

```bash
python manage.py test
```

---

## 📄 Licença

Este projeto é open-source e segue a licença **MIT**.

---

## ✨ Contribuições

Se deseja contribuir, siga os passos:

1. Faça um **fork** do repositório
2. Crie um **branch** para suas alterações (`git checkout -b minha-feature`)
3. Commit suas mudanças (`git commit -m 'Minha nova feature'`)
4. Faça um **push** para o branch (`git push origin minha-feature`)
5. Abra um **Pull Request** 🚀

📩 **Contato:** [crobertdmelo@gmail.com](mailto\:crobertdmelo@gmail.com)



