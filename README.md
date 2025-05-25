# 🚀 Laboratório Azure - Criação de Máquina Virtual

Este repositório foi criado como parte do desafio da DIO para documentar a criação e configuração de uma máquina virtual no Microsoft Azure.

## 📚 Objetivo

Demonstrar o entendimento prático dos conceitos abordados nas aulas da DIO, com foco em:

- Criação de uma VM no Azure
- Configurações básicas e avançadas
- Gerenciamento de recursos
- Boas práticas de segurança e acesso
- Uso do GitHub como ferramenta de documentação técnica

---

## 🛠️ Passo a Passo

### 1. Acesso ao Portal Azure

- Acesse: [https://portal.azure.com](https://portal.azure.com)
- Crie sua conta (caso não tenha)

### 2. Criação da Máquina Virtual

- Vá até **Máquinas Virtuais**
- Clique em **Criar > Máquina virtual**
- Configure os seguintes parâmetros:

| Parâmetro         | Valor Exemplo         |
|-------------------|------------------------|
| Nome da VM        | dio-vm-windows         |
| Imagem            | Windows 10 Pro         |
| Tamanho           | Standard B1s           |
| Usuário admin     | dioadmin               |
| Porta RDP         | 3389                   |

📸 Veja a imagem:  
![Criação da VM](https://www.altus.com.br/upload/htmleditor/1_38.png)

### 3. Configurações de Rede

- Crie um grupo de segurança de rede (NSG)
- Libere a porta RDP (3389) para acesso remoto

---

## 📌 Dicas Úteis

- Utilize a opção de **Diagnóstico de Inicialização** para solucionar problemas de boot
- Sempre defina uma senha forte para o usuário administrador
- Desligue a VM quando não estiver usando para evitar cobrança

---

## 🧠 Aprendizados

Durante esse desafio, aprendi a:

- Navegar no portal Azure
- Criar e configurar uma máquina virtual de forma segura
- Documentar processos técnicos de maneira clara


---

## 🔗 Recursos

- [Documentação Oficial da Microsoft](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)
- [DIO - Plataforma de Ensino](https://web.dio.me)

---

## ✍️ Autor

Feito por [Diego Ferreira](https://github.com/DiegoFerreira1)
