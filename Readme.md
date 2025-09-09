
# AIssist 


<p align="center">
  <a href ="#desafio"> Desafio</a>  |
  <a href ="#backlog"> Backlog do Produto</a>  |
  <a href ="#dor">DoR</a>  |
  <a href ="#dod">DoD</a>  |
  <a href ="#sprint"> Cronograma de Sprints</a>  |
  <a href ="#tecnologias">Tecnologias</a> |
  <a href ="#manual">Manual de Instalação</a>  | 
  <a href ="#equipe"> Equipe</a> |
</p>

> Status do Projeto: Em desenvolvimento 
>
> Pasta de Documentação: [Link](docs/cliente) 📄


## Projeto <a id="projeto"></a>

O projeto consiste em desenvolver 


## 📅 Cronograma de Sprints <a id="sprint"></a>

| Sprint          |    Período    | Documentação                                     |
| --------------- | :-----------: | ------------------------------------------------ |
| 🔖 **SPRINT 1** | 10/03 - 30/03 | [Sprint 1 Docs](./docs/processo/sprints/sprint-1/README.md) |
| 🔖 **SPRINT 2** | 07/04 - 27/04 | [Sprint 2 Docs](./docs/processo/sprints/sprint-2/README.md) |
| 🔖 **SPRINT 3** | 05/05 - 25/05 | [Sprint 3 Docs](./docs/processo/sprints/sprint-3/README.md) |

## 💻 Tecnologias <a id="tecnologias"></a>

<h4 align="center">
 <a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"></a>
 <a href="https://www.angular.dev/"><img src="https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white"/></a>
 <a href="https://www.https://dotnet.microsoft.com/pt-br/languages/csharp/"><img src="https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white"/></a> 
 <a href="https://github.com/"><img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/></a>
 <a href="https://www.figma.com/"><img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/></a>

</h4>

## 📖 Manual de Instalação <a id="manual"></a>

### 🛠 Pré-requisitos

- Git ([Download](https://git-scm.com/downloads))

- Python 3.9+ ([Download](https://www.python.org/downloads/))

- Node.js 16+ ([Download](https://nodejs.org/en/download))

- Poetry (opcional para o backend) ([Download](https://python-poetry.org/))

---

### 1. Clonar o Repositório Principal

```bash
git clone --recurse-submodules https://github.com/BuzzTech-API/API_ADS_6SEMESTE_2025.1.git
cd API_ADS_6SEMESTE_2025.1
```



---

### 2. Configuração do Backend (auxia-backend)

**1° Adicione as variáveis no .env**

**2° Inicialize o Banco de dados MongoDB no localhost:**

**3° Coloque a base de dados vetorizada ./client dentro da raíz do backen:**

**4° Instale e Inicie a aplicação:**

**Opção A: Com Poetry**

```bash
cd ./auxia-backend
poetry shell
poetry install
make run
```

**Opção B: Com Ambiente Virtual Python**

```bash
cd ./auxia-backend
python3 -m venv venv
source venv/bin/activate # se você usa linux
venv/Scripts/activate 	 # se você usa windows
pip install -r requirements.txt
fastapi dev ./auxia/main.py
```

**Saída Esperada:**
<br>
Servidor rodando em `http://localhost:8000` (acesse `http://localhost:8000/docs` para a UI do Swagger).

---

### 3. Configuração do Frontend (auxia-frontend)

```bash
cd ../auxia-frontend/auxia
npm install
npm run dev
```

**Saída Esperada:**
<br>
Frontend rodando em `http://localhost:5173`.

## 🎓 Equipe <a id="equipe"></a>

<div align="center">
  <table>
    <tr>
      <th>Membro</th>
      <th>Função</th>
      <th>Github</th>
      <th>Linkedin</th>
    </tr>
    <tr>
      <td>Ivan Duarte</td>
      <td>Product Owner</td>
      <td><a href="https://github.com/Ivan-Duarte"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/ivan-duarte-982532217"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Vitor Lima</td>
      <td>Scrum Master</td>
      <td><a href="https://github.com/lima2206"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/vitor-spricigo-lima-84a377184"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Isaque da Silva</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/KhovetS2"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/isaque-elis-da-silva-2a4087226/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Joice Araujo</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/Joice-Araujo"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/joice-aparecida-581226250/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Jonas Alves</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/dodekafonos"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="http://linkedin.com/in/jonas-alves"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Pedro Davi</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/PedrohDavi"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/pedro-davi-jobs/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Rafael Motta</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/Rafael-Motta"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/rafaelmotta97"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
  </table>
</div>