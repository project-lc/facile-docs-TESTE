# 📝Notas de Versão

Detalhes das atualizações liberadas da ferramenta.



### Versão 4.33.5010

04/01/2022

- NOVIDADE: Criado novo compatibilizador único para dicionário na System (U_UPDXSYS)

- BUG: Incluído novas validações ao importar NFS-e via PDF

### Versão 4.33.5009

22/12/2022

- NOVIDADE: Incluído nova tabela para registrar todos os NSUs

- NOVIDADE: Desenvolvido para salvar os NSUs das NF-e

- NOVIDADE: Denvolvido classe e JOB para buscar no sefaz os NSUs faltantes

- NOVIDADE: Criado tela para demonstrar a carta de correção

### Versão 4.33.5008

22/12/2022

- NOVIDADE: Incluído a informação do armazém do pedido na tela principal de entrada de doc.

- NOVIDADE: Incluído opção de visualizar, alterar e excluir pré-nota

- NOVIDADE: Incluído opção de visualizar e excluir documento de entrada

- BUG: Removido os documentos bloqueados dos relatórios

### Versão 4.33.5007

22/12/2022

- NOVIDADE: Criado ponto de entrada P011ITEM para manipular os itens da SD1 no CTE de venda

### Versão 4.33.5006

21/12/2022

- NOVIDADE: Incluído campo Tipo de Produto no filtro de regras por processo

### Versão 4.33.5005

19/12/2022

- NOVIDADE: Finalizado a primeira versão da importação automática do CTE de venda

### Versão 4.33.5004

16/12/2022

- BUG: Correção na descrição do produto na tela de entrada

- BUG: Tratativa para não permitir XML sem filial

### Versão 4.33.5003

08/12/2022

- NOVIDADE: Cria parametro para permitir grupos de usuários a bloquear entrada de documento

- NOVIDADE: Incluído informação da unidade de pedido do XML, produto e pedido de compras na tela de entrada

### Versão 4.33.5002

01/12/2022

- BUG: Correção na geração da devolução de venda

### Versão 4.33.5001

01/12/2022

- NOVIDADE: Implantado melhoria de importação de NFS-e

### Versão 4.33.5000

22/11/2022

- NOVIDADE:  Entrada de beneficiamento

- NOVIDADE:  Bloqueio de entrada

- NOVIDADE:  Nova legenda

### Versão 4.33.1042

10/11/2022

- Ajuste no PTX008 para o ponto de entrada de numero de documento

### Versão 4.33.1041

09/11/2022

- Correção no execauto do CTE (MATA116) após atualização da Totvs

### Versão 4.33.1040

08/11/2022

- Correção no busca quando a empresa utiliza CPF no sigamat

- Correção no PTX0008 para utilizar a nova rotina de numero de documento

### Versão 4.33.1039

03/11/2022

- Criado ponto de entrada P007CTE

### Versão 4.33.1038

01/11/2022

- Ajuste na ordenação da SD1 quando possui conversão de unidade de medida

### Versão 4.33.1037

28/10/2022

- Removido validação de cnpj raiz nos jobs

### Versão 4.33.1036

26/10/2022

- Criado parametro ZZ_ORDEDIC para indicar se deve ordenar o array de itens de acordo com a SD1

### Versão 4.33.1035

24/10/2022

- Correção no update das legendas

- Correção na criação de arquivos de logs

### Versão 4.33.1034

20/10/2022

- Criação de ponto de entrada XCarregDados para alterar a filial de destino do XML

### Versão 4.33.1033

14/10/2022

- Correção na função de validação de impostos

### Versão 4.33.1032

13/10/2022

- Melhoria para gravar na ZZW a descrição do produto que vem no XML

### Versão 4.33.1031

11/10/2022

- Correção na impressão do CTE na tag CEP

- Melhoria para preencher o campo D1_DFABRIC através da tag dFab

### Versão 4.33.1030

05/10/2022

- Ajuste no checkdoc automático e workflow

### Versão 4.33.1029

30/09/2022

- Melhoria no checkdoc para incluir filial e cnpj no assunto do workflow

- Considerar pedido de compras faltando zeros a esquerda no xPED

- Melhorado processo dos JOBS para controle de semaforo e logs

### Versão 4.33.1028

26/09/2022

- Correção na query de exportação de XML para banco de dados Oracle

### Versão 4.33.1027

14/09/2022

- Corrigido erro após incluir novas colunas no grid de pedido de compras

### Versão 4.33.1026

11/09/2022

- Melhoria incluindo valores do pedido de compra

### Versão 4.33.1025

06/09/2022

- Incluído tratamento de serie 3 digitos para CTE

### Versão 4.33.1024

01/09/2022

- Alterado para não exportar XML de documento cancelado
