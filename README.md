# Desafio-DIO-Gerenciando-Inst-ncias-EC2-na-AWS
Este repositório documenta minha experiência e os conhecimentos adquiridos durante o desafio de gerenciamento de instâncias EC2, parte da formação da DIO. O objetivo foi aplicar conceitos práticos, como a criação, configuração e conexão com uma instância EC2, e consolidar o aprendizado em um material de consulta organizado.

# 🚀 Desafio - Gerenciamento de Instâncias EC2 na AWS

Este repositório documenta minha experiência no **laboratório de Gerenciamento de Instâncias EC2 na AWS**, com o objetivo de consolidar os conhecimentos adquiridos, registrar anotações e servir como material de apoio para futuras implementações.

---

## 🎯 Objetivo

- Criar, configurar e gerenciar instâncias EC2 na AWS.  
- Documentar o processo de forma clara e organizada.  
- Utilizar o GitHub como ferramenta de compartilhamento técnico.  

---

## 🛠️ Passos Realizados

### 1. Criação da Instância EC2
- Acesso ao console da AWS.  
- Escolha da **AMI (Amazon Linux 2)**.  
- Seleção do tipo de instância **t2.micro** (Free Tier).  
- Configuração de rede e **grupos de segurança**.  

📸 *Evidência*:  
<img width="344" height="339" alt="image" src="https://github.com/user-attachments/assets/0fb84192-0c2a-428e-a801-6392bb1dabba" />

---

### 2. Acesso via SSH
- Download da chave privada `.pem`.  
- Alteração de permissões:  
  ```bash
  chmod 400 chave.pem
Conexão via terminal:

bash
Copiar código
ssh -i chave.pem ec2-user@ip-publico
📸 Evidência:

3. Configurações Internas
Atualização do sistema:

bash
Copiar código
sudo yum update -y
Instalação do Apache:

bash
Copiar código
sudo yum install -y httpd
sudo systemctl start httpd
sudo systemctl enable httpd
Teste de conectividade via navegador com o IP público.

📸 Evidência:

4. Encerramento e Boas Práticas
Encerramento da instância para evitar custos extras.

Revisão das regras de segurança configuradas.

Organização da documentação neste repositório.

📸 Evidência:

📚 Insights e Aprendizados
A configuração correta dos grupos de segurança é essencial para garantir segurança e acessibilidade.

Entendi o ciclo de vida de uma instância EC2 (criar → usar → encerrar).

Aprendi a importância do controle de custos na AWS.

O GitHub é um excelente recurso para registrar experiências técnicas e construir portfólio.

📌 Recursos de Apoio
Documentação Oficial da AWS - EC2

Guia Markdown GitHub

Formação GitHub Certification

👩‍💻 Autor
Projeto desenvolvido como parte da formação na DIO - Digital Innovation One.

markdown
Copiar código

---

👉 Agora, para finalizar:  
1. Crie a pasta `/images` no repositório.  
2. Adicione os prints do seu processo com os nomes:  
   - `01-criacao-instancia.png`  
   - `02-acesso-ssh.png`  
   - `03-apache.png`  
   - `04-encerramento.png`  
