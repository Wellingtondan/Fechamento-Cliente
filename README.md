# Fechamento cliente

### 1º Passo - Conferir transferências

- Planilha de Excel - Base das 2 lojas (Documentos fiscais)
- **Matriz:** 13.254.314/0001-62 (Pessoa 13317)
- **Filial:** 13.254.314/0002-43 (Pessoa 52487) 61098
- **CGO saída:** 598, 599, 620 e 624
- **CGO entrada:** 150 e 151

### 2º Passo - Conferência de Relatórios e Livros

- **Venda fiscal:** 5102 | 5123 | 5405 | 5922 | 6102 | 6108 | 6404
- **Venda gerencial (CGO):** 518 | 528 | 538 | 539 | 557 | 567 | 573 | 5379 | 580 | 582 | 583 | 589 | 590 | 591 | 592 | 600 | 612 | 622 | 554

### 3º Passo - Bases

- Bases fechamentos (DOC | UF | SAÍDAS)
- **Base Sat Fiscal:** Base documentos fiscais
- **Tipo documento:** Cupom Sat
- **Tira fleg:** Considerar cancelada
- Excluir 1ª linha para colocar no fechamento

#### 3.1 Outras Bases | Relatório

> Arquivei

- **NFE:** 120 dias
- **CTE:** 120 dias (Pode pegar período do ano todo)

> E-Cold

- Tem que separar NFe da chave de acesso

> Relatório de CFOP

- **6108:** Venda não contribuinte - sempre tributado
- **6404:** 10 ou 70

> Conferência CTE

- Somente lança quando for tomador

> Sem chave

- Pedir para arrumar / ajustar

### 4º Produtos de devoluções

- Consultar cada NF de referência se tiver recolhimento de DARE ➡️ ```estornar ICMS e o ST proporcional (via apuração)```
- Fiscal ➡️ relatório ➡️ relatório de saída por devolução com destaque de icms próprio.
- Planilha com os valores de estorno.

### 5º UF ICMS / APURAÇÃO 

- Conferir também apuração ICMS ST (UF ICMS)
- Conferir também ICMS ST (APURAÇÂO)

### 6º Estruturas das Pastas

- **Apuração ICMS:** 2 apuração | Resumo
- **Apuração ICMS ST:** Notas e Dares | 6 relatórios sendo 3 apuração | Entrada Resumo | Saída Resumo
- **Apuração PIS/COFINS:** 4 apuração | Conferência | Devolução | Estorno
- **Ativo imobilizado:** Livro e notas
- **Bases:** 6 bases
- **Combustível:** Livro e notas
- **Complemento ICMS:** Notas com divergêcnias de valores
- **Simples Nacional:** Preencher planilha com bases e notas
- **DARE | GNRE:** Relatório fiscal | Relatório UF | Relatório Posto Fiscal
- **Despesas interestaduais:** Livros e notas
- **Energia:** Livro e notas
- **Livros:** Entrada e saída
- **Perdas:** Relatórios e notas
- **Devolução interestadual:** Relatório, planilha e notas
- **Telefone:** Livro e notas
- **Vendas** Fiscal e gerencial
- **Relatório de conferência ST:** 6 relatórios ➡️ fiscal ➡️ relatório ➡️ recolhimento por IMCS ST ➡️ agrupamento por UF ➡️ CFOP 6910 | 2411 | 6404


### 7º Conferência Venda Consumidor final

- **Fiscal:** Relatório | Conferência | relatório de ICMS por partilha (Mês anterior)
- ```Verificar sapida que não é MG | PR | RJ, se recolher guia, MG | PR | RJ tem IE no destino```

### 8º Simples Nacional
 
 `Filtrar apenas alíquotas diferentes de 7%, 12% e 18%`
 
 `Valor NFE X Sistema - conferir (CFOP 1102 | 2102)`

### 9º PIS/COFINS 

 `CGO de devolução: 401 | 501`

💬**OBSERVAÇÃO:** Recolhimento de ST, quando não for estado de MG, PR e RJ, recolhe por operação.

### 10º Sintegra Papel

➡️ **Matriz e filial**

- **Filial:** Obrigações federais ➡️ Sintegra
- **Finalidade:** Normal
- **Identificação:** Interestaduais Operações com ou sem ST
- **Formato:** Arquivo separado por estado
- **Tira fleg:** Gerar registro inventário
- **Gerar**
- **Motivo:** OK
- **Atualiza**
- Salvar na área de trabalho a conexão (Sintegra XX|XXXX) Matriz e Filial
- Transferir para minha párea de trabalho
- Não Entregar os estados (DF | GO | RJ | RS | SE | MT)

➡️ **Validador Sintegra (SC no Portal)**

- Fazer estado por estado
- Validar (Barra de títulos) ```...```
- Importar arquivo do estado
- Validar
- Resumo
- Listar CFOP
- Comparar com relatório UF - CFOP - Estado do arquivo
- **Gerar mídia** - Salvar na pasta como está
- **Transmitir** - Confirmar UF de Destino
- Mídia ```...``` Selecionar a pasta - listar
- Selecionar o arquivo - Recibo - Salvar na pasta

  
➡️ **Santa Catarina - Site SC**

- Envio de remessas de contribuintes de outro estado
- Enviar o arquivo ZIP do validador
- No validador gerar até chegar na mídia e pegar o número do arquivo para entrega
- No modulo fiscal ➡️ Relatório UF
  
  ☑️ Tira SP para ver se teve ou não notas de outras UF's
  
  ☑️ Pega todas as UF's anota e risca as que não entregam

  🔗 Site é para entregar o SINTEGRA de SC
   - [Sintegra SC](https://sat.sef.sc.gov.br/tax.NET/Sat.Sintegra.Web/Envio_RemessaForaSC.aspx)

### 11º Sped Fiscal Papel

➡️ **Bloco K**

- Para conferência do Bloco K
- Gerar Bloco K
- Data é o último dia do mês
- Finalidade do peíodo
- **Categoria** (desflegar)
   - A classificar
   - Ativo
 
➡️ **Finalidade**  

- Embalagem
- Matéria-prima
- Mercadoria para revenda
- Outros insumos
- Produto acabado
- Produto em processo
- Produto intermediário
- Sub produto

Para conferir selecionar as mesmas coisas no Bloco H. 

Salva o arquivo, conferir no excel H010 e K200, faz procv para o código dos produtos

`Para Gerar inventário` - Bloco H
- Não flegar
   - A classificar
   - A queima
   - Consumo
   - Sucata

 
### 12º NFS da Papel

- Pegar as NFs do sistema e colocar na pasta (1X ppor semana)

➡️ **Optante:** não tem retenção de IR e PCC e dependendo da natureza pode ser que tenha ISS ou INSS.

➡️ **Não optante:** Tem retenções.

- Podendo ter ou não ISS retiro para a Papel.

- Código 10.09 - toda nota de não optante tem IR vindo ou não destacado em nota

➡️ Regra geral o ISS é recolhido pelo prestador, salvo alguns serviços que ai o recolhimento terá que ser pelo tomador.
 
#### 12.1 Papel Matriz

Lança na prefeitura apenas as notas que tem retenção de ISS.

➡️ Retenção na fonte ➡️ lançamento

➡️ Referência ➡️ mês | ano

➡️ Prestador ➡️ CNPJ ☑️

➡️ Optante ➡️ Coloca - Sim

➡️ Alíquota SN ➡️ Sempre coloca a alíquota da nota

➡️ Faz guia de retenção por prestador

#### 12.2 Papel Filial

➡️ Itupeva ➡️ ainda não tem

➡️ Araraquara - lança todas as notas na prefeitura

### 13º Obrigação Federal - GIA ST

➡️ Gera gia individual (MG, PR e RJ)

➡️ Relatório UF por CFOP (2411, 6404 e 6910) filtrar por UF igual gerado o arquivo.

- MG e RJ ➡️ entrega pelo app (GIA S)
- PR ➡️ entrega pelo site (preenche conforme relatório UF e já entrega)
- ICMS ST do PR ➡️ gera com vencimento para o último dia do mês

➡️ Códigos GNRE

- 100048 ➡️ ICMS ST
- 100110 ➡️ Difal não contribuinte

- IE ➡️ MG - 0027406290098
- IE ➡️ RJ - 11128807 
