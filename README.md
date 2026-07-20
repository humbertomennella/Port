# 🛠️ HUMBERTO MENNELLA FERNANDES COELHO
`Analista de Infraestrutura de TI | Suporte Técnico N2 | Segurança da Informação | SysAdmin Linux & Windows`

📍 **Localização:** Curitiba, PR — Brasil  
📧 **E-mail:** humberto.mennella@gmail.com  
🔗 **LinkedIn:** [linkedin.com/in/humbertomennella](https://linkedin.com/in/humbertomennella)  
💻 **GitHub:** [github.com/humbertomennella](https://github.com/humbertomennella)  

---

## 📋 SUMÁRIO EXECUTIVO & PERFIL PROFISSIONAL

Profissional de Tecnologia da Informação focado em **Infraestrutura de Redes, Administração de Sistemas (Linux/Windows), Suporte Técnico Avançado e Segurança da Informação**. Experiência prática na implementação de ambientes isolados de teste, orquestração de contêineres, tuning de sistemas operacionais e diagnósticos de rede em conexões de alta velocidade.

Com bagagem consolidada no atendimento direto ao cliente, gestão de processos, inventário e controle de operações, apresento alta capacidade de resolução ágil de problemas lógicos, tradução de requisitos técnicos para usuários finais e atuação sob metodologias de documentação rigorosa.

---

## 🖥️ 01. ARQUITETURA DE HARDWARE & INFRAESTRUTURA FÍSICA

### Host Specifications (`NODE_LENOVO_80YH`)
* **Modelo do Host:** Lenovo IdeaPad 320-15IKB (80YH)
* **Processador:** Intel Core i3-6006U CPU @ 2.00GHz (2 Cores / 4 Threads)
  * *Conjunto de Instruções Ativas:* AES-NI, AVX2, SSE4.2, BMI2 (Habilitado para virtualização de hardware VT-x)
* **Memória RAM:** 12GB DDR4 RAM Matrix
* **Controlador Gráfico:** Intel HD Graphics 520 (Driver 31.0.101.2111)
  * *Recursos Ativos:* Decodificação de Vídeo por Hardware, WebGL2, WebGPU e pipeline gráfico otimizado
* **Segurança de Firmware:** TPM 2.0 Ativo | Gerenciamento UEFI / Secure Boot | Virtualização Habilitada em Hardware

### Topologia e Isolamento Físico de Storage (`DUAL_SSD_NODE`)
> **Arquitetura de Segregação do Boot:** Eliminação total do uso de discos rígidos mecânicos (HDDs) e implementação de isolamento físico entre ambientes operacionais via dois SSDs dedicados, prevenindo falhas cruzadas de boot (GRUB/EFI) e corrupção de partições:

1. **SSD 01 (120GB):** Windows 10 Enterprise LTSC
   * *Finalidade:* Ambiente primário de produtividade, tuning de rede, decodificação de vídeos e operação de cloud.
2. **SSD 02 (120GB):** Kali Linux Dedicated
   * *Finalidade:* Laboratório isolado de segurança da informação, auditoria de redes, análise de pacotes e uso de ferramentas nativas de teste de intrusão.

---

## 🛠️ 02. COMPETÊNCIAS TÉCNICAS & HISTÓRICO DE SISTEMAS OPERACIONAIS

### 🐧 Administração de Sistemas Linux & Terminal Shell
* **Operação de Terminal (Bash / Zsh):** Manipulação avançada de arquivos via CLI, operadores de IO Redirection, Pipes e utilitários de filtragem e busca (`grep`, `find`, `sed`, `awk`).
* **Permissões POSIX & Segurança:** Controle estrito de acessos e privilégios de arquivo/diretório (`chmod`, `chown`, manipulação do arquivo `/etc/sudoers`, gestão de usuários e grupos).
* **Gerenciamento de Processos & Daemons:** Monitoramento de saúde do SO e controle de serviços do sistema (`systemctl`, `journalctl`, `top`, `htop`, envio de sinais de processo `kill`/`pkill`).
* **Pacotes & Repositórios:** Administração de dependências em distribuições da família Debian/Kali (`apt`, `dpkg`), compilação de pacotes e gestão de repositórios.
* **Redes & Armazenamento Local:** Configuração de interfaces de rede (`ip`, `ifconfig`, `netstat`/`ss`), montagem manual de discos e edição do arquivo `/etc/fstab`.

### 🧰 Histórico Prático em Distribuições Linux (Distro-Hopping Operacional)
* **Kali Linux:** Utilização ativa em SSD dedicado para auditorias de perímetro, varreduras de portas e análise de vulnerabilidades.
* **Ubuntu LTS:** Administração do ecossistema Debian, testes de engines nativas open-source e mapeamento de estruturas ocultas do sistema.
* **Zorin OS (Core / Pro):** Avaliação de consumo de memória RAM, gerenciamento de interface gráfica e validação de decodificadores de streaming.
* **Linux Mint:** Análise de estabilidade de kernel, aplicação de permissões POSIX e automação via scripts de terminal.

### 🪟 Hardening & Otimização Windows Enterprise
* **Windows 10 Enterprise LTSC:** Customização avançada do SO, remoção de telemetrias redundantes, gestão manual de serviços nativos e otimização do arquivo de paginação (`pagefile.sys`) para preservação da vida útil dos SSDs.
* **Sysinternals Suite:** Inspeção profunda de processos, inicialização oculta e rotinas de sistema via *Autoruns* e *Process Explorer*.
* **Manutenção:** Limpeza e saneamento estrutural de armazenamento via *BleachBit* e utilitários de linha de comando.

### 🌐 Diagnóstico de Redes & Análise de Tráfego
* **Auditoria de Perímetro:** Mapeamento de sub-redes, varredura de portas e descoberta de serviços ativos via **Nmap / Zenmap**.
* **Análise de Tráfego:** Captura de pacotes e inspeção detalhada de cabeçalhos de rede em tempo real com **Wireshark**.
* **Qualidade de Link & Rotas:** Medição de latência, verificação de *Jitter* e isolamento de perdas de pacotes (*Packet Loss*) em conexões de alta velocidade (600 Mbps) via **WinMTR**.

### 📦 Containers, Automação & Ferramentas Operacionais
* **Docker Engine & CLI:** Deploy, orquestração e gerenciamento de aplicações e ambientes em contêineres isolados com controle de recursos do hospedeiro.
* **Automação CLI:** Instalação e manutenção silenciosa de pacotes via **Chocolatey CLI**.
* **Mídias Técnicas:** Diagnóstico multiboot e criação de unidades de manutenção com **Ventoy**.
* **Controle de Versão:** Documentação padronizada, gestão de repositórios e controle de versão via **Git / GitHub**.

---

## 📁 03. PROJETOS & LABORATÓRIOS PRÁTICOS

### 🟢 `[LAB-001]` Local AI Container Orchestration
* **Descrição:** Implantação, configuração e execução de modelos de inteligência artificial executados localmente via contêineres **Docker**.
* **Foco Técnico:** Isolamento de processos no Linux, governança de recursos de hardware (CPU/RAM) e garantia de privacidade de dados sem dependência da nuvem.

### 🔵 `[LAB-002]` PROXITI Operations Hub
* **Descrição:** Projeto autoral estruturado para entrega de serviços de tecnologia da informação e consultoria técnica.
* **Foco Técnico:** Suporte técnico especializado, implementação de rotinas de backup, planejamento de infraestrutura de redes locais, consultoria de segurança da informação e elaboração de documentação operacional padronizada para micro e pequenas empresas.

### 🟣 `[LAB-003]` Physical Storage & OS Isolation Node
* **Descrição:** Projeto de engenharia de armazenamento físico no notebook Lenovo 80YH.
* **Foco Técnico:** Instalação e isolamento de dois SSDs de 120GB, permitindo a execução de testes invasivos de segurança e análises no Kali Linux sem comprometer a integridade do ambiente principal em Windows 10 LTSC.

---

## 🎓 04. FORMAÇÃO ACADÊMICA & CERTIFICAÇÕES

* **Bootcamp Nublify — Primeiros Passos em IA e Cloud** | DIO / Nublify  
  *Status:* Em andamento (Matrícula Ativa)  
  *Foco:* Fundamentos de Nuvem, Mídia Cloud e Aplicações de Inteligência Artificial.
* **Segurança em Tecnologia da Informação** | Fundação Bradesco  
  *Status:* Concluído  
  *Foco:* Princípios de Cibersegurança, Criptografia, Políticas de Segurança e Proteção de Dados.
* **Análise e Desenvolvimento de Sistemas (ADS)** | Universidade Paulista (UNIP)  
  *Status:* Formação Superior (Pausada / Trancada)  
  *Foco:* Lógica de Programação, Estrutura de Dados e Engenharia de Software.
* **Ensino Médio Completo** | E.E. Carmem Miranda (Peruíbe / SP)

---

## 💼 05. HISTÓRICO PROFISSIONAL & TRANSFERÊNCIA DE COMPETÊNCIAS

### Supermercado Baba Ltda. (Peruíbe / SP)
**Cargo:** Operador de Loja / Atendimento e Processos  
**Período:** 04/2019 – 08/2025  
* **Atendimento ao Cliente:** Resolução diária de solicitações e suporte direto ao usuário no salão de vendas e checkout, mantendo alto índice de satisfação e mediação de conflitos.
* **Gestão de Inventário e Estoque:** Organização, conferência e controle físico de mercadorias e notas fiscais, garantindo exatidão no recebimento e logística interna.
* **Auditoria de Padrões:** Controle de validade e cumprimento estrito de normas sanitárias e procedimentos operacionais padrão.
* **Treinamento de Equipe:** Apoio na integração e capacitação de novos colaboradores nas rotinas internas da empresa.

### Mar & Lanches (Peruíbe / SP)
**Cargo:** Atendente Multifuncional  
**Período:** 11/2014 – 03/2017 | 12/2017 – 01/2019  
* Atendimento direto ao público, controle financeiro de caixa sob alta demanda e manutenção da organização do setor.

---

## 📌 06. INFORMAÇÕES ADICIONAIS DE OPERAÇÃO

* **Disponibilidade:** Flexibilidade total de horários e atuação em escalas de turno.
* **Perfil de Atuação:** Focado na resolução lógica de problemas, documentação técnica rigorosa e aprendizado contínuo.
