<div align="center">
  <img src="assets/logo.png" alt="Logo GradPath" width="180"/>

  # 🎓 GradPath — Otimizador Curricular Avançado

  **Planejamento acadêmico inteligente e visual para Ciência da Computação (UERN)**

  ![Python](https://img.shields.io/badge/Python-3.9+-blue.svg?logo=python&logoColor=white)
  ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B.svg?logo=streamlit&logoColor=white)
  ![Status](https://img.shields.io/badge/Status-Finalizado-7C3AED.svg)
  ![Licença](https://img.shields.io/badge/Licen%C3%A7a-MIT-green)
</div>

<br>

O **GradPath** é um sistema inteligente de planejamento e otimização acadêmica desenvolvido para o curso de Ciência da Computação da UERN. Utilizando **Teoria dos Grafos**, o sistema automatiza a análise de históricos escolares e gera a rota mais rápida e eficiente para a integralização curricular.

---

## 🚀 Funcionalidades

- **Leitura Automatizada (PDF):** Extração de dados diretamente do histórico escolar oficial do SIGAA.
- **Modelagem em Grafos (DAG):** Mapeamento dinâmico de dependências, pré-requisitos e Unidades Curriculares de Extensão (UCEs).
- **Motores de Resolução Matemática:**
  - `Busca em Profundidade (DFS)` com Ordenação Topológica para identificar o caminho crítico.
  - `Coloração Gulosa` para alocação otimizada de turmas respeitando os semestres letivos.
- **Simulador What-If:** Previsão em tempo real do impacto de possíveis reprovações na sua linha do tempo de formatura.
- **Identidade Visual Imersiva:** Interface moderna renderizada com PyVis, destacando vértices por status (Integralizado, Em Andamento, Pendente).

---

## 🛠️ Tecnologias Utilizadas

| Categoria | Tecnologia |
| :--- | :--- |
| **Linguagem Base** | Python 3.9+ |
| **Interface Web** | Streamlit, HTML/CSS customizado |
| **Engrenagem Matemática** | NetworkX, Graphviz |
| **Renderização de Grafos** | PyVis |
| **Processamento de Dados** | pdfplumber, JSON |

---

## ⚙️ Como Executar o Projeto Localmente

Siga os passos abaixo para rodar o GradPath na sua máquina:

### Pré-requisitos
Certifique-se de ter o [Python 3.9+](https://www.python.org/downloads/) instalado na sua máquina.

### 1. Clone o repositório
```bash
git clone [https://github.com/SEU_USUARIO/GradPath.git](https://github.com/SEU_USUARIO/GradPath.git)
cd GradPath
```

### 2. Crie e ative um Ambiente Virtual (Recomendado)
**Para Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```

**Para Linux/Mac:**
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Instale as dependências
```bash
pip install -r requirements.txt
```

### 4. Inicie a aplicação
```bash
streamlit run app.py
```

O sistema abrirá automaticamente no seu navegador padrão através do endereço `http://localhost:8501`.

---

## 👥 Equipe de Desenvolvimento

Projeto desenvolvido como requisito avaliativo da disciplina de **Teoria dos Grafos**, sob orientação da **Profa. Dra. Rosiery da Silva Maia**.

- Diego Arthur Jales de Almeida
- Eduardo Milhomes Barbosa de Medeiros
- Flávio de Aguiar Xavier Filho
- José Júnior de Medeiros Andrade

**Universidade do Estado do Rio Grande do Norte (UERN)** - Campus Natal / 2026.1
