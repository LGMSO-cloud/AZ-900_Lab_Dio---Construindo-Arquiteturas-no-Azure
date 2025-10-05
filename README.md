# ☁️ AZ-900_Lab_Dio — Construindo Arquiteturas no Azure

## 📘 Descrição
Projeto prático realizado como parte do **laboratório da certificação Microsoft AZ-900 (Azure Fundamentals)**, através da plataforma **DIO (Digital Innovation One)**.  
O objetivo foi criar e configurar uma **Rede Virtual (VNet)** no **Microsoft Azure**, aplicando os principais conceitos de **Resource Groups, IAM, Monitoramento e Redes Virtuais**.

---

## 🧩 Objetivos do Laboratório
- Criar um **Grupo de Recursos (Resource Group)**.  
- Implantar uma **Rede Virtual (Virtual Network - VNet)**.  
- Verificar o **Log de Atividade**.  
- Validar permissões via **IAM (Controle de Acesso)**.  
- Visualizar a topologia no **Visualizador de Recursos**.

---

## ⚙️ Passos Realizados

### 🏗️ 1. Criação do Grupo de Recursos
- **Nome:** `AZ-900_Lab_Dio`  
- **Região:** Brazil South  
- Responsável por agrupar os recursos do laboratório.  

📸 **Evidência:**  
![Grupo de Recursos](evidencias/Elaborado%20grupo%20de%20recursos%20para%20laboratorio.png)

---

### 🌐 2. Criação da Rede Virtual (VNet)
- **Nome:** `VNET1`  
- **Tipo:** Rede Virtual  
- **Região:** Brazil South  
- Status da implantação: ✅ **Bem-sucedido**  

📸 **Evidências:**  
![Criação da VNet](evidencias/Elaborado%20VNET_redes%20vrtuais.png)  
![Implantação da VNet](evidencias/implantação_vnet.png)  
![VNet no Grupo de Recursos](evidencias/Adicionado%20rede%20virtual%20a%20um%20grupo%20de%20recursos.png)

---

### 🧾 3. Log de Atividades
- Verificação das operações realizadas na implantação.  
- Todas as etapas retornaram **Status: Bem-sucedido**.  

📸 **Evidência:**  
![Log de Atividade](evidencias/AZ-900_Lab_Log%20de%20atividades.png)

---

### 🔐 4. IAM — Controle de Acesso
- Análise das permissões de usuário no grupo de recursos.  
- Função de **Proprietário (Owner)** confirmada.  

📸 **Evidência:**  
![IAM Controle de Acesso](evidencias/Laboratorio_IAM_controle%20de%20acesso.png)

---

### 🗺️ 5. Visualizador de Recursos
- Representação visual da rede virtual criada.  
- Exibição do recurso `VNET1` no grupo `AZ-900_Lab_Dio`.  

📸 **Evidência:**  
![Visualizador de Recursos](evidencias/Visualizados%20de%20recursos.png)

---

## 📂 Estrutura do Repositório


---

## 🔗 Links Úteis
- 🌐 [Portal Azure](https://portal.azure.com)
- 📖 [Documentação Oficial - Virtual Network](https://learn.microsoft.com/pt-br/azure/virtual-network/virtual-networks-overview)
- 🎓 [DIO - Microsoft Azure Fundamentals](https://www.dio.me/)
- 💡 [Como Entregar seu Desafio na DIO](https://www.dio.me/articles/como-entregar-seu-desafio-de-projeto)

---

## 🏁 Conclusão
Este projeto reforça conceitos fundamentais do **modelo IaaS (Infraestrutura como Serviço)** e demonstra como o Azure organiza recursos dentro de um grupo lógico.  
A criação da **VNet (Virtual Network)** é um dos blocos essenciais para compreender **conectividade, segurança e isolamento de recursos** em arquiteturas de nuvem.

---

✍️ **Autor:** [Luiz Gustavo (LGMSO-cloud)](https://github.com/LGMSO-cloud)  
📅 **Data:** Outubro de 2025  


