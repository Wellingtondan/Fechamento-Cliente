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
- ```Verificar saída que não é MG | PR | RJ, se recolher guia, MG | PR | RJ tem IE no destino```

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
- Finalidade do período
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


### 14º Acessos 

Portal do Paraná pra entregar a GIA ST

> [PORTAL GIA ST](https://receita.pr.gov.br/login)

Portal GNRE para gerar as guias de ICMS ST de MG e RJ

> [PORTAL GNRE](https://www.gnre.pe.gov.br:444/gnre/portal/GNRE_Principal.jsp)

Portal para entrega do SINTEGRA SC

> [SINTEGRA SC](https://sat.sef.sc.gov.br/tax.NET/Sat.Sintegra.Web/Envio_RemessaForaSC.aspx)

### Agenda tributária

> [Agenda tributária](https://www.contadores.cnt.br/agenda-tributaria/estadual/sao-paulo/2025/06.html)

> [Agenda tributária Paulista Nº426](https://legislacao.fazenda.sp.gov.br/Paginas/Comunicado-SRE-1-de-2025.aspx)

- **GIA-ST**

Entrega, pelo contribuinte de outra Unidade da Federaçao inscrito no CADESP na condiçao de Contribuinte Substituto, da GIA-ST - Guia Nacional de Informaçao e Apuraçao do ICMS Substituiçao Tributaria, com as informaçoes relativas as operaçoes realizadas no mes anterior, **ate o dia 10 do mes subsequente**.

O contribuinte de outra unidade federada obrigado à entrega das informações na GIA-ST, inclusive relativas ao DIFAL nas operações e prestações destinadas a não contribuintes, em relação ao imposto apurado no mês de janeiro, deverá apresentá-la até essa data, na forma prevista no Anexo V da Portaria CAT 92/1998 (itens 1 e 2 do § 1º do artigo 254 do RICMS/2000).

- **ICMS Substituição Tributária - Produtos Diversos (CPR 1200)**
   
Recolhimento do imposto devido pelos contribuintes substitutos tributários enquadrados no regime RPA, inclusive em relação ao adicional destinado ao Fundo Estadual de Combate e Erradicação da Pobreza (FECOEP), quando devido. Recolhimento do ICMS até o dia 20 do mês subsequente ao da ocorrência do fato gerador, relativamente a fumo e seus sucedâneos manufaturados (artigo 289), cimento (artigo 291), refrigerante, cerveja, chope e água (artigo 293), sorvete de qualquer espécie e preparado para fabricação de sorvete em máquina (artigo 295), veículos novos (artigos 299 e seguintes), pneumáticos, câmaras-de-ar e protetores de borracha (artigo 310), tintas, vernizes e outros produtos químicos (artigo 312), medicamentos (artigo 313-A), bebidas alcoólicas (artigo 313-C), produtos de perfumaria (artigo 313-E), produtos de higiene pessoal, ração animal (artigo 313-I), materiais de limpeza (artigo 313-K), autopeças (artigo 313-O), lâmpadas elétricas (artigo 313-S), papel (artigo 313-U), produtos da indústria alimentícia (artigo 313-W), materiais de construção e congêneres (artigo 313-Y), ferramentas (artigo 313-Z3), bicicletas (artigo 313-Z5), máquinas e aparelhos mecânicos, elétricos, eletromecânicos e automáticos (artigo 313-Z11), produtos de papelaria (artigo 313-Z13), artefatos de uso doméstico (artigo 313-Z15), materiais elétricos (artigo 313-Z17), produtos eletrônicos, eletroeletrônicos e eletrodomésticos (artigo 313-Z19), e energia elétrica (Convênio ICMS 83/00).

- **ICMS Substituição Tributária - Produtos Diversos (CPR 1200)**
 
Recolhimento do imposto devido pelos contribuintes substitutos tributários enquadrados no regime RPA, inclusive em relação ao adicional destinado ao Fundo Estadual de Combate e Erradicação da Pobreza (FECOEP), quando devido. Recolhimento do ICMS até o dia 20 do mês subsequente ao da ocorrência do fato gerador, relativamente a fumo e seus sucedâneos manufaturados (artigo 289), cimento (artigo 291), refrigerante, cerveja, chope e água (artigo 293), sorvete de qualquer espécie e preparado para fabricação de sorvete em máquina (artigo 295), veículos novos (artigos 299 e seguintes), pneumáticos, câmaras-de-ar e protetores de borracha (artigo 310), tintas, vernizes e outros produtos químicos (artigo 312), medicamentos (artigo 313-A), bebidas alcoólicas (artigo 313-C), produtos de perfumaria (artigo 313-E), produtos de higiene pessoal, ração animal (artigo 313-I), materiais de limpeza (artigo 313-K), autopeças (artigo 313-O), lâmpadas elétricas (artigo 313-S), papel (artigo 313-U), produtos da indústria alimentícia (artigo 313-W), materiais de construção e congêneres (artigo 313-Y), ferramentas (artigo 313-Z3), bicicletas (artigo 313-Z5), máquinas e aparelhos mecânicos, elétricos, eletromecânicos e automáticos (artigo 313-Z11), produtos de papelaria (artigo 313-Z13), artefatos de uso doméstico (artigo 313-Z15), materiais elétricos (artigo 313-Z17), produtos eletrônicos, eletroeletrônicos e eletrodomésticos (artigo 313-Z19), e energia elétrica (Convênio ICMS 83/00).

- **GIA**
   
Entrega da GIA pelos contribuintes enquadrados no Regime Periódico de Apuração (RPA), relativamente às operações ocorridas no mês anterior.

Excetuadas as hipóteses expressamente previstas na legislação, a GIA deverá ser apresentada até esta data, em relação ao imposto apurado no mês de janeiro (artigo 254 do RICMS/2000 – Portaria CAT 92/1998, Anexo IV, artigo 20) através do endereço - [Link 1](http://www.portal.fazenda.sp.gov.br) ou [Link 2](https://portal.fazenda.sp.gov.br/servicos/pfe/), **vencimento até dia 20**.

- **ICMS Normal (CPR 1200)**
  
Recolhimento do imposto devido pelos contribuintes enquadrados nos seguintes códigos CNAE, inclusive em relação ao adicional destinado ao Fundo Estadual de Combate e Erradicação da Pobreza (FECOEP), quando devido: 01113, 01121, 01130, 01148, 01156, 01164, 01199, 01211, 01229, 01318, 01326, 01334, 01342, 01351, 01393, 01415, 01423, 01512, 01521, 01539, 01547, 01555, 01598, 01610, 01628, 01636, 01709, 02101, 02209, 02306, 03116, 03124, 03213, 03221, 05003, 06000, 07103, 07219, 07227, 07235, 07243, 07251, 07294, 08100, 08916, 08924, 08932, 08991, 09106, 09904, 10333, 10538, 11119, 11127, 11135, 11216, 11224, 12107, 12204, 17109, 17214, 17222, 17311, 17320, 17338, 17419, 17427, 17494, 19101, 20118, 20126, 20134, 20142, 20193, 20215, 20223, 20291, 20312, 20321, 20339, 20401, 20517, 20525, 20614, 20622, 20631, 20711, 20720, 20738, 20916, 20924, 20932, 20941, 20991, 21106, 21211, 21220, 21238, 22218, 22226, 22234, 22293, 23206, 23915, 23923, 24113, 24121, 24211, 24229, 24237, 24245, 24318, 24393, 24415, 24431, 24491, 24512, 24521, 25110, 25128, 25136, 25217, 25314, 25322, 25390, 25411, 25420, 25438, 25501, 25918, 25926, 25934, 25993, 26108, 26213, 26221, 26311, 26329, 26400, 26515, 26523, 26604, 26701, 26809, 27104, 27210, 27317, 27325, 27333, 27511, 27597, 27902, 28135, 28151, 28232, 28241, 28518, 28526, 28534, 28542, 29107, 29204, 29506, 30113, 30121, 30318, 30504, 30911, 32124, 32205, 32302, 32400, 32507, 32914, 33112, 33121, 33139, 33147, 33155, 33163, 33171, 33198, 33210, 35301, 36006, 37011, 37029, 38114, 38122, 38211, 38220, 39005, 41107, 41204, 42111, 42120, 42138, 42219, 42227, 42235, 42910, 42928, 42995, 43118, 43126, 43134, 43193, 43215, 43223, 43291, 43304, 43916, 43991, 45111, 45129, 45200, 45307, 45412, 45421, 45439, 46117, 46125, 46133, 46141, 46150, 46168, 46176, 46184, 46192, 46214, 46222, 46231, 46311, 46320, 46338, 46346, 46354, 46362, 46371, 46397, 46419, 46427, 46435, 46443, 46451, 46460, 46478, 46494, 46516, 46524, 46613, 46621, 46630, 46648, 46656, 46699, 46711, 46729, 46737, 46745, 46796, 46834, 46842, 46851, 46869, 46877, 46893, `46915`, 46923, 46931, `47113`, 47121, 47130, 47229, 47237, 47245, 47296, 47318, 47326, 47415, 47423, 47431, 47440, 47512, 47521, 47539, 47547, 47555, 47563, 47571, 47598, 47610, 47628, 47636, 47717, 47725, 47733, 47741, 47814, 47822, 47831, 47849, 47857, 47890, 49116, 49124, 49400, 49507, 50114, 50122, 50211, 50220, 50301, 50912, 50998, 51111, 51129, 51200, 51307, 52117, 52125, 52214, 52222, 52231, 52290, 52311, 52320, 52397, 52401, 52508, 55108, 55906, 56112, 56121, 56201, 59111, 59120, 59138, 59146, 60217, 60225, 62015, 62023, 62031, 62040, 62091, 63917, 63992, 64107, 64212, 64221, 64239, 64247, 64310, 64328, 64336, 64344, 64352, 64361, 64379, 64409, 64506, 64611, 64620, 64638, 64701, 64913, 64921, 64930, 64999, 65111, 65120, 65201, 65308, 65413, 65421, 65502, 66118, 66126, 66134, 66193, 66215, 66223, 66291, 66304, 68102, 68218, 68226, 69117, 69125, 69206, 70204, 71111, 71120, 71197, 71201, 72100, 72207, 73114, 73190, 73203, 74102, 74200, 74901, 75001, 77110, 77195, 77217, 77225, 77233, 77292, 77314, 77322, 77331, 77390, 77403, 78108, 78205, 78302, 79112, 79121, 79902, 80111, 80129, 80200, 80307, 81117, 81125, 81214, 81222, 81290, 81303, 82113, 82199, 82202, 82300, 82911, 82920, 82997, 84116, 84124, 84132, 84213, 84221, 84230, 84248, 84256, 84302, 85112, 85121, 85139, 85201, 85317, 85325, 85333, 85414, 85422, 85503, 85911, 85929, 85937, 85996, 86101, 86216, 86224, 86305, 86402, 86500, 86607, 86909, 87115, 87123, 87204, 87301, 88006, 90019, 90027, 90035, 91015, 91023, 91031, 92003, 93115, 93123, 93131, 93191, 93212, 93298, 94111, 94120, 94201, 94308, 94910, 94928, 94936, 94995, 95118, 95126, 95215, 95291, 96017, 96025, 96033, 96092, 97005, 99008. Recolhimento do ICMS **até o dia 20 do mês subsequente** ao da ocorrência do fato gerador. (CNAE utilzados pela Reta)

- **Escrituração Fiscal Digital (EFD)**

Entrega do arquivo digital relativo a EFD - Escrituraçao Fiscal Digital (SPED Fiscal), contendo a totalidade das informaçoes necessarias a apuraçao do ICMS e do IPI, bem como de outras informaçoes de interesse do Fisco, referente ao mes anterior, **ate o dia 20 do mes subsequente** ao da apuraçao.

O contribuinte obrigado à EFD deverá transmitir o arquivo digital nos termos da Portaria CAT 147/2009.

- DARE

[link](https://www4.fazenda.sp.gov.br/DareICMS/)

- SICALC

[LINK](https://sicalc.receita.economia.gov.br/sicalc/rapido/contribuinte)

[PLANILHA MODELO CAPAS](https://github.com/Wellingtondan/Alteracao_MVA_2.0_c5/blob/main/Planilha_modelo_capas.xlsx)


- COggle

https://coggle.it/

- Trello
- Notion
- Power bi
  
