# resumo-lab-az900
Repositório do resumo das lições aprendidas durante o desenvolvimento do lab na DIO.

Durante essa primeira parte do curso, aprendo alguns conceitos de nuvem. Os modelos de nuvem como: nuvem privada, pública e híbrida.
Também foi explicado sobre o Capex e Opex, a estrutura do painel principal do Azure e a abrangência de opções onde se utilizar geograficamente alguma solução disponível pela nuvem da Azure.

No resumo do lab, aprendi como criar máquinas virtuais no portal do azure, vi sobre os recursos como redimensionamentos de máquinas virtuais, spot, marcar as opções para excluir recursos relacionado à máquina criada para não obter consumo desnecessário e as opções para disponibilizar máquinas para os usuários, tanto para uso personalizado com a opção pessoal e para uso em pool para uso coletivo.
-> Armazenamento: Storage Account- Para esse resumo, foi abordado sobre a redundância dos arquivos nos storages (LRS, ZRS, GRS); Blob - recomendado para armazenamento de arquivos diversos em massa não estruturados; Disco do azure - para VM, app e outros serviços; Fila do azure - para aplicação que gera mensagens; Arquivos do azure (files) - recomendado para compartilhamento de arquivos (\\) como uma unidade de disco literalmente; Tabelas do azure.
-> Ponto de extremidade públicos do serviço de armazenamento: O endereço é identificado após <storage account name>.serviço (blob, dfs, file, queue, table).
-> Camadas de acesso de armazenamento: Frequente (usado frequentemente), Esporádico (pouca frequencia e armazenado por pelo menos 30 dias), Frio (armazenadmento por pelo menos 90 dias), Arquivo morto ( armazenamento de dados acessados raramente e pelo menos 180 dias).
-> Migrações para Azure: Azure data box (serviço de migração física acima de 40TB e até 80TB, criptografado), recomendado para locais remotos com conectividade limitada ou sem conectividade; Data box disk e Data box heavy.
-> Opções de gerenciamento de arquivos (AzCopy) - Utilitário de linha de comando, copiar blobs ou arquivos de ou para sua conta de armazenamento, sincronização em uma direção; Gerenciador de armazenamento (interface gráfica semelhante ao windows explorer) diferença para o AzCopy é só questão de interface.
