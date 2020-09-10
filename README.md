# Passo a passo para instalação completa e configuração de máquina virtual com PostgreSql 12 e PgAdmin4.
## Sem trauma, e sem teoria.

- Criação de máquina virtual no VirtualBox 6

- Download e instalação do Ubuntu 20.04 LTS sem ambiente gráfico com openssh-server, apache2, samba4 e postgresql-12

- Configuração de IP estático no Ubuntu

- Configuração do samba4 com compartilhamento de diretórios

- Configuração da base de dados PostgreSql 12

- Instalação e configuração do PgAdmin 4

---
```
Tópicos:
+----+-----------------------------------------------------------------------------------------------------------+----+
|Núm.|  Assunto                                                                                                  |Pág.|
+----+-----------------------------------------------------------------------------------------------------------+----+
|  0 |Instruções, observações e frases para pensar                                                               |  3 |
+----+-----------------------------------------------------------------------------------------------------------+----+
|  1 |Link para download do VirtualBox                                                                           |  3 |
+----+-----------------------------------------------------------------------------------------------------------+----+
|  2 |Links para download da iso de instalação do Ubuntu 20.04 LTS                                               |  3 |
+----+-----------------------------------------------------------------------------------------------------------+----+
|  3 |Criar máquina virtual                                                                                      |  4 |
+----+-----------------------------------------------------------------------------------------------------------+----+
|  4 |Instalar Ubuntu (inclui instalação do PostgreSQL database, Samba file server e OpenSSH server              | 22 |
+----+-----------------------------------------------------------------------------------------------------------+----+
|  5 |Incluir usuário e senha do usuário postgres no Ubuntu e no banco de dados                                  | 51 |
+----+-----------------------------------------------------------------------------------------------------------+----+
|  6 |Instalar pgAdmin4 (inclui importação de chave GPG e configuração do repositório)                           | 53 |
+----+-----------------------------------------------------------------------------------------------------------+----+
|  7 |Configurar IP estático para o servidor                                                                     | 61 |
+----+-----------------------------------------------------------------------------------------------------------+----+
|  8 |Configurar /etc/hosts em cliente linux (inclui acesso ao servidor via ssh via terminal)                    | 65 |
+----+-----------------------------------------------------------------------------------------------------------+----+
|  9 |Configurar C:\Windows\System32\drivers\etc\hosts (inclui acesso ao servidor via ssh via Windows PowerShell)| 69 |
+----+-----------------------------------------------------------------------------------------------------------+----+
| 10 |Criar conexão com o servidor de dados PostgreSQL (via PgAdmin4)                                            | 72 |
+----+-----------------------------------------------------------------------------------------------------------+----+
| 11 |Configurar o compartilhamento Samba4 (via ssh)                                                             | 75 |
+----+-----------------------------------------------------------------------------------------------------------+----+
| 12 |Acessar o compartilhamento utilizando cliente Linux                                                        | 80 |
+----+-----------------------------------------------------------------------------------------------------------+----+
| 13 |Acessar o compartilhamento utilizando cliente Windows (inclui mapeamento de unidade de rede)               | 83 |
+----+-----------------------------------------------------------------------------------------------------------+----+
```

# LICENÇA
LEMBRANDO QUE a licença de uso do meu repositório é MIT, que trocando em miúdos quer dizer: "Todos que tiverem acesso poderão utilizar seu conteúdo".
Sendo assim, quem contribuir com material para melhorar este repositório, CONCORDA automaGicamente com os termos da licença MIT.

https://opensource.org/licenses/MIT

---

### GitHub:

https://github.com/viniciusalopes


### Youtube:

https://www.youtube.com/vovolinux

https://www.youtube.com/user/viniciusalopesGO

---
Vovolinux: Sem trauma e sem teoria.

