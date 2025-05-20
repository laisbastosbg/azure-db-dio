## ✅ Azure Database – Visão Geral

O Azure oferece serviços de banco de dados gerenciados em nuvem, ou seja, você não precisa instalar, configurar ou manter o banco de dados e o servidor — tudo isso é feito pela Microsoft.

### 🔹 Tipos de bancos de dados disponíveis


* Azure SQL Database (versão gerenciada do Microsoft SQL Server)
* Azure Database for MySQL
* Azure Database for PostgreSQL
* Azure Cosmos DB (NoSQL, altamente escalável e distribuído)
* Azure Database for MariaDB (em descontinuação)
* Azure Managed Instance (quase um SQL Server completo gerenciado)

> 💡 *Você pode escolher o banco que mais se adapta à sua aplicação, sem se preocupar com instalação, backup, patching, etc.*

---

## ⚙️ Principais configurações ao criar um banco na Azure

### 🔸 1. Configurações básicas

* Nome do banco
* Nome do servidor lógico (que será usado para se conectar)
* Tipo do banco de dados (MySQL, PostgreSQL, SQL)
* Região (onde o servidor será provisionado)
* Versão do banco (por exemplo, MySQL 5.7 ou 8.0)

---

### 🔸 2. Ambiente de trabalho

* Dev/teste: custo reduzido, menos redundância
* Produção: mais recursos, replicação, SLA garantido

---

### 🔸 3. Configurações de desempenho

* Número de vCores
* Memória
* Armazenamento
* Modo de escalonamento (provisionado ou escalável)

---

### 🔸 4. Segurança

* Microsoft Defender for Databases (detecção de ameaças)
* Criptografia em repouso e em trânsito
* Backup automático com retenção configurável
* Firewall: define quais IPs podem acessar o banco
* Autenticação: com senha ou via Azure Active Directory (dependendo do tipo de banco)

---

### 🔸 5. Configurações de rede

* Acesso público ou privado
* Integração com redes virtuais (VNet)
* Definição da porta padrão (em geral, 3306 para MySQL, 5432 para PostgreSQL)

---

### 🔸 6. Monitoramento

* Logs de auditoria
* Diagnóstico de desempenho
* Alertas (por uso, falhas, consumo de CPU etc.)
* Integração com o Azure Monitor e Log Analytics

---

### 🔸 7. Alta disponibilidade e replicação

* Zonas de disponibilidade (para redundância)
* Geo-replicação (cópia do banco em outra região para recuperação de desastres)
