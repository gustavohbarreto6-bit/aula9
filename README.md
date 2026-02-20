# aula9

# 💼 TechSoluções — Sistema de Avaliação de Desempenho

Sistema web simples desenvolvido em **HTML, CSS e JavaScript** para automatizar o cálculo de reajuste salarial baseado em critérios de meritocracia definidos pelo RH.

---

## 📋 Descrição

O sistema permite inserir dados de um colaborador e calcular automaticamente se ele tem direito a reajuste salarial anual, com base em:

- Cargo
- Salário atual
- Número de faltas
- Número de atrasos

Caso o colaborador tenha **histórico disciplinar limpo (0 faltas e 0 atrasos)**, ele recebe aumento reminder conforme o cargo. Caso contrário, o reajuste é bloqueado.

---

## 🚀 Funcionalidades

✔ Cadastro de dados do colaborador  
✔ Cálculo automático de reajuste  
✔ Exibição de relatório detalhado  
✔ Validação de campos obrigatórios  
✔ Feedback visual instantâneo  

---

## 🧠 Regras de Negócio

| Cargo | Percentual de Aumento |
|------|-------------------------|
Aprendiz | 0% |
Analista de TI | 10% |
Gerente de TI | 15% |
Diretor de TI | 20% |

📌 **Condição obrigatória para aumento:**  
O colaborador não pode ter faltas nem atrasos.

---

## 🖥️ Como Executar

1. Baixe os arquivos do projeto
2. Abra o arquivo `index.html` no navegador
3. Preencha os campos
4. Clique em **"Avaliar Desempenho"**

---

## 📁 Estrutura do Projeto


/projeto
├── index.html
└── style.css


---

## 🛠 Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla JS)

---

## 🔮 Melhorias Futuras

- Armazenamento de histórico em banco de dados
- Cadastro de múltiplos colaboradores
- Exportação do relatório em PDF
- Dashboard administrativo
- Sistema de login RH

---

## 👨‍💻 Autor

Projeto desenvolvido para atividade prática de lógica e desenvolvimento web.

---

⭐ Se este projeto te ajudou, considere salvar como referência para estudos!
