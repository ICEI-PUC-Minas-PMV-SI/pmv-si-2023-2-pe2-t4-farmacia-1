# Farmácia

**Resumo:**
Nosso projeto tem como objetivo otimizar as atividades dentro de uma farmácia, seja em tempo ou praticidade de atividades como: cadastro de clientes, cadastro de medicamentos e o processo de vendas. 

## Integrantes

* Gustavo Silva Rossetti
* Sibelle Mendes Diniz
* Marcos Paulo De Oliveira
* Lucas Peres Dias Costa
* Luana Paula Ramos de Souza


## Professor

* Juliana Amaral Baroni
  
---

​Instituto de Informática e Ciências Exatas– Pontifícia Universidade de Minas Gerais (PUC MINAS)

Belo Horizonte – MG – Brasil

---

<gu.rossetti@hotmail.com>

<sibelle.diniz@sga.pucminas.com>

<marcos.oliveira.1465085@sga.pucminas.br>

<lucaspdcosta@gmail.com>

<lprsouza@sga.pucminas.br>

---

**1. Introdução**

Uma pesquisa da Confederação Nacional de Municípios (CNM) revelou que 65% dos municípios brasileiros sofrem com a falta de medicamentos, incluindo antibióticos e outros remédios essenciais. Essa situação, agravada pela pandemia e pela instabilidade internacional, evidencia um problema de gerenciamento de estoque nas farmácias do país. 

As tarefas repetitivas, a falta de planejamento, controle e organização na execução das funções básicas de uma farmácia são alguns dos desafios operacionais enfrentados pelo setor, por isso existe a necessidade de oferecer uma plataforma que contribua e facilite o dia a dia dos funcionários e clientes. 

Além disso, é possível otimizar os processos de pesquisa, já que eles requerem a análise de um grande volume de dados, essa otimização na farmácia e nos processos da indústria farmacêutica também levam à redução de custos, o que deixa os preços dos produtos mais acessíveis, contribuindo para a rentabilidade do negócio e direcionando o desenvolvimento de produtos. Por fim, com a indústria farmacêutica investindo em automatização e sistemas eficientes atrelados às necessidades dos clientes os serviços terão melhor qualidade e tarefas serão agilizadas, contribuindo assim para o bom funcionamento da farmácia. 

**1.1. Objetivos geral e específicos**

O objetivo geral da aplicação será melhorar o gerenciamento da farmácia. 

Os objetivos específicos serão gerenciar estoque, clientes e vendas em uma farmácia. 

 **1.2. Justificativas** 

Levantamentos do Conselho Regional de Farmácias do Estado de São Paulo (CRF-SP) apontaram que 98% dos farmacêuticos enfrentam carência de medicamentos. Antibióticos são os mais afetados, com 96% dos farmacêuticos relatando dificuldades na obtenção desses medicamentos. 

Essa escassez de medicamentos está intimamente ligada a questões de gestão 		inadequada de estoque nas farmácias, exigindo uma abordagem mais eficiente para 	garantir o abastecimento adequado e contínuo de medicamentos essenciais. 

A população idosa no Brasil está crescendo rapidamente, chegando a cerca de 15% em 2022, em comparação com 11% há 10 anos, segundo o Instituto Brasileiro de Geografia e Estatística (IBGE). A faixa etária abaixo dos 30 anos diminuiu para 43% durante o mesmo período. Atualmente, a distribuição etária no país é a seguinte: 

* 0 a 4 anos: 7% 

* 5 a 17 anos: 18% 

* 18 a 24 anos: 11% 

* 25 a 39 anos: 24% 

* 40 a 59 anos: 26% 

* 60 anos ou mais: 15% 

O IBGE também informa que a região Sudeste possui a maior proporção de idosos, com 17% de sua população, enquanto o Norte tem o menor, com apenas 10%. Segundo a Organização Mundial da Saúde (OMS), até 2050, o número de pessoas com mais de 60 anos no mundo pode atingir 2 bilhões, representando 1/5 da população global, o que implica em um aumento contínuo na demanda por medicamentos. 

___

**2. Participantes do processo de negócio**

* Persona 1: Atendente 

Nome: Joana 

Idade: 39 anos 

Perfil: Recepciona os clientes, esclarecendo dúvidas e apresentando opções de compras e ofertas, caso se cadastrem. 

Necessidades: Agilidade e facilidade ao cadastrar o cliente. 

* Persona 2: Estoquista 

Nome: Lucas 

Idade: 30 anos 

Perfil: funcionário responsável pelo registro e dispensação de medicamentos. 

Necessidades: eficiência para verificar e cadastrar o estoque, acesso rápido a informações sobre medicamentos. 

* Persona 3: Balconista 

Nome: Pedro 

Idade: 28 anos 

Perfil: Funcionário que realiza as vendas. 

Necessidades: Facilidade e rapidez para verificar a disponibilidade do medicamento ao realizar a venda do produto. 

* Persona 4: Cliente 

Nome: Breno 

Idade: 28 anos 

Perfil: Cliente que pesquisa sobre medicamentos antes de comprar. 

Necessidades: Informações detalhadas sobre medicamentos da farmácia, como efeitos colaterais, instruções de uso e avaliações de outros clientes 

* Persona 5: Cliente 

Nome: Gabriela 

Idade: 33 anos 

Perfil: consumidora frequente da farmácia, está sempre buscando medicamentos para si e para sua família. 

Necessidades: Rápido atendimento, informações claras sobre dosagem e efeitos colaterais dos medicamentos, opções de genéricos para redução de custos.

___

**3. Modelagem do processo de negócio**

**3.1. Análise da situação atual (AS-IS)**

Foram identificados processos essenciais para o bom funcionamento de uma farmácia e que estão diretamente envolvidos com a experiência do cliente, sendo eles: cadastro de medicamentos, cadastro de clientes e vendas, que no momento contam com pouco suporte de sistemas de informação.   

Atualmente para fazer o cadastro de medicamentos no estoque é necessário preencher uma lista com as informações básicas do produto, preço, quantidade adquirida e sua localização no estabelecimento, à medida que os medicamentos forem vendidos é necessária a atualização dessa planilha, porém essa tarefa pode ser negligenciada devido ao fluxo de clientes causando transtorno caso o medicamento em questão esteja constando na planilha, mas esteja em falta fisicamente. A utilização da lista dificulta a pesquisa por categoria, consulta de informações mais detalhadas sobre os medicamentos, alteração de preço, relatórios de gestão e etc. o que aumenta o tempo gasto em uma tarefa que precisa ser simples e rápida.  

|![Screenshot_64](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2023-2-pe2-t4-farmacia-1/assets/98671803/fee0e882-4349-48cf-b564-786734b343d4)|
|:--:| 
| *<sub> Processo da Situação Atual - Cadastro de medicamentos.</sub>* |

Cadastro de cliente: para efetuar o cadastro de clientes o funcionário deve acessar a planilha de clientes e preencher as informações pessoais como nome, CPF, telefone, endereço e e-mail. Esse método não é eficiente pois pode ocorrer a duplicidade de cadastro, há dificuldade de ter um relacionamento com o cliente tendo em vista que a planilha reúne informações padrão e dados importantes como medicamentos comprados com frequência, podem deixar de serem acrescentados.  

|![Screenshot_74](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2023-2-pe2-t4-farmacia-1/assets/98671803/9ff9444c-1d27-44ad-96d7-566c53451944)|
|:--:| 
| *<sub> Processo da Situação Atual - Cadastro de Clientes.</sub>* |

Venda: o cliente se dirige ao balcão e solicita a medicação, o balconista vai até o estoque, consulta o preço e a disponibilidade do produto e então se dirige a prateleira, mas devido a um erro a localização do produto não estava correta então o atendente precisa procurar nas prateleiras até localizar o medicamento que é entregue ao cliente que aguardava próximo ao balcão, enquanto possivelmente outros clientes chegaram para serem atendidos. O cliente se dirige ao caixa para realizar o pagamento e a venda é concluída. Podemos perceber mais uma vez as desvantagens dos processos atuais, o tempo para realização do atendimento seria menor e as tarefas se tornariam mais simples com a automatização dos processos. 


|![Screenshot_80](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2023-2-pe2-t4-farmacia-1/assets/98671803/4bdbda83-405f-4b72-9c76-946c6b570795)|
|:--:| 
| *<sub> Processo da Situação Atual - Vendas.</sub>* |

**3.2.  Modelagem dos processos aprimorados (TO-BE)**

Nesta seção, descreveremos e analisaremos a proposta de solução para o processo de negócio de uma farmácia, a partir da perspectiva do modelo "TO-BE". Isso envolverá a documentação dos processos aprimorados que serão implementados com a introdução do novo sistema. 

Processo de Cadastro de medicamentos: O processo de cadastro e gerenciamento de estoque é crucial para garantir que a farmácia tenha medicamentos disponíveis para os clientes quando necessário.  

Os medicamentos são recebidos de fornecedores na loja e então o funcionário deve reunir toda a documentação necessária do medicamento como a data de fabricação, efeitos colaterais e instruções de uso. Sendo aprovado é preenchido o cadastro com o nome do remédio, tipo do remédio, número de identificação, preço e localização na loja. Assim atualizando o cadastro de medicamentos. Portanto esse processo será inserido para além de ter uma organização maior, passar um bom produto para o consumidor.  

|![Screenshot_69](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2023-2-pe2-t4-farmacia-1/assets/98671803/3e4bd072-b11c-45c7-b484-1b59bb3fe415)|
|:--:| 
| *<sub> Processo Aprimorado - Cadastro de Medicamentos.</sub>* |

Cadastro do Cliente: O atendente pergunta se o cliente tem ou tenha interesse em se cadastrar na loja. Caso ele tenha o cadastro o funcionário verifica os dados e finaliza a tarefa. 

Portanto, esse processo é um melhoramento do processo AS IS visto que deixa o cadastro de cliente mais robusto. 
|![Screenshot_71](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2023-2-pe2-t4-farmacia-1/assets/98671803/a310ec46-0161-49a0-ab3b-d4efa77a45e0)|
|:--:| 
| *<sub> Processo Aprimorado - Cadastro de Clientes.</sub>* |

Vendas: O processo de venda de medicamentos é uma parte fundamental das operações de uma farmácia. Com a implementação do novo sistema, aprimoraremos esse processo para torná-lo mais eficiente, preciso e prático.  

O cliente pergunta se tem a disponibilidade do remédio que ele quer comprar, assim ocasiona a procura no estoque e diz se tem ou não, se tiver será informado o preço do medicamento ao cliente e deve perguntar se o consumidor vai querer concluir a compra. 

|![Screenshot_72](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2023-2-pe2-t4-farmacia-1/assets/98671803/98d22a5a-1ce8-4f55-abd5-c3f8836465a3)|
|:--:| 
| *<sub> Processo Aprimorado - Vendas.</sub>* |
___

 **4. Projeto da arquitetura de dados da solução proposta**

 **4.1. Diagrama de Entidades e Relacionamentos (DER)**

 ![Captura de Tela (424)](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2023-2-pe2-t4-farmacia-1/assets/128331107/e935c1e1-e3a2-4429-839e-4e9e814e6f83)

**4.2. Impactos da implementação em um banco de dados NoSQL**

Possibilidades: O banco de dados NoSQL visa aumentar a expansão horizontal, para que mais servidores possam ser adicionados e lidar com mais cargas de trabalho, diferente do banco de dados relacional, o banco de dados NoSQL não requer um sistema rígido. Podem ser adicionados novos campos ou tipos de dados com o desenvolvimento do sistema sem migrar soluções existentes. Alguns bancos de dados NoSQL foram projetados para fornecer consulta com alta taxa de transmissão e baixa latência, especialmente em comparação com o banco de dados relacional. 

 Riscos: Para obter maior disponibilidade ou tolerância a falhas alguns bancos de dados NoSQL, podem ter dados inconsistentes. O uso do banco de dados NoSQL pode exigir conhecimento especial que os desenvolvedores podem não ter. Sendo necessário um treinamento mais longo e caro. Se o sistema for migrado do banco de dados de relacionamento paro o banco de dados NoSQL, pode ser um processo complexo e que consome tempo. 

Impactos: O uso do banco de dados NoSQL pode envolver custos adicionais de permissão ou consultores especializados. Se o banco de dados NoSQL for selecionado corretamente e usado de maneira eficaz, ele poderá melhorar significativamente o desempenho do sistema. No entanto, se o banco de dados NoSQL for escolhido erroneamente, isso poderá levar a grandes problemas de desempenho. O banco de dados NoSQL pode exigir manutenção diferente da de banco de dados relacionais, isso pode incluir diferentes configurações de bancos de dados de backup, vigilância e ajuste. 

**4.3. Modelo relacional**

![Captura de Tela (425)](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2023-2-pe2-t4-farmacia-1/assets/128331107/8ad23ff8-64f5-45a4-a01e-10590761a315)

___
Consultas com SQL de acordo com as necessidades informacionais dos usuários dos processos modelados 

**Consulta 1: Estoque Atual de Medicamentos** 

SELECT num_medicamento, nome, preço 

FROM Medicamentos; 

**Consulta 2: Listar Todos os Clientes** 

SELECT id_cliente, nome, cpf, telefone, email, 

FROM Clientes; 

**Consulta 3: Listar todas as compras**

SELECT num_pedido, id_cliente, valor 

FROM Compra; 

___
**5. Relatórios analíticos**

**Relatório de clientes cadastrados**


![Captura de Tela (382)](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2023-2-pe2-t4-farmacia-1/assets/128331107/633bdd56-1759-4cc0-9532-96b92c639237)


**Relatório de medicamentos cadastrados** 


![Captura de Tela (433)](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2023-2-pe2-t4-farmacia-1/assets/128331107/0238f8ff-2c54-4835-a8fc-92dd1585102b)


**Relatório de vendas** 


![Captura de Tela (388)](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2023-2-pe2-t4-farmacia-1/assets/128331107/beb764a9-678d-4a1c-be38-085b9be581a5)


 

 

 


___
**REFERÊNCIAS** 

Confederação Nacional de Municípios, “Pesquisa da CNM revela que 65,2% dos Municípios enfrentam falta de medicamentos básicos nas farmácias”. Publicado em 27/09/2022. Disponível em < https://www.cnm.org.br/comunicacao/noticias/pesquisa-da-cnm-revela-que-65-2-dos-municipios-enfrentam-falta-medicamentos-basicos-nas-farmacias > Acesso em 27 de set de 2023 

G1, “População idosa sobe para 15,1% em 2022, diz IBGE” Publicado em 16/06/2023 10h56. Disponível em < https://g1.globo.com/economia/noticia/2023/06/16/populacao-idosa-sobe-para-151percent-em-2022-diz-ibge.ghtml > Acesso em 27 de set de 2023.  
