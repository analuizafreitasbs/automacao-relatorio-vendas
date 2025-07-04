# 💼 Automatização de Relatórios de Vendas com Shell Script

Este projeto é uma solução de automação para processamento de vendas em uma loja virtual, desenvolvida 100% via terminal Linux com shell script. Ele organiza arquivos, gera backups nomeados com data, cria relatórios diários e consolida tudo em um relatório final — tudo isso com execução agendada automaticamente via `crontab`.

A proposta foi criar uma rotina eficiente e reutilizável que simula o fluxo real de uma operação de vendas: da entrada de dados brutos até a entrega de um relatório consolidado. Para isso, foram desenvolvidos dois scripts principais:

- Um script de **processamento diário**, responsável por organizar os diretórios, salvar backups, gerar o relatório do dia e comprimir os arquivos.
- Um segundo script de **consolidação**, que reúne os relatórios de dias diferentes e monta um resumo final de vendas.

A automação completa foi configurada para rodar periodicamente de forma autônoma, usando o `crontab`. Tudo foi construído do zero, apenas com comandos básicos do Linux e scripts criados no editor `nano`.

---

## 🔧 Destaques Técnicos

- Organização de diretórios e versionamento com data  
- Compressão de arquivos (`gzip`)  
- Agendamento automático com `crontab`  
- Geração e unificação de relatórios `.txt` via terminal  
- Permissões e execução de scripts (`chmod`, `./script.sh`)

---

Este projeto mostra como tarefas rotineiras podem ser automatizadas com poucos recursos, aumentando a eficiência e eliminando processos manuais.

