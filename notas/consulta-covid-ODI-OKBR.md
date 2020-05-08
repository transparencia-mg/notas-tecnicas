A [Secretaria de Estado de Saúde](https://www.saude.mg.gov.br/coronavirus), em parceria com a [Controladoria Geral do Estado](http://cge.mg.gov.br/noticias-artigos/740-novos-dados-sobre-a-covid-19-em-mg-disponibilizados-em-formato-aberto), passou a divulgar, em abril, microdados sobre casos notificados e casos confirmados do novo coronavírus (COVID-19). Tal iniciativa foi adotada em função da decisão de se imprimir maior transparência sobre os dados dos boletins epidemiológicos e resultados das ações de governo no enfrentamento à pandemia.

A Open Knowledge Brasil (OKBR) avalia, semanalmente, a transparência dos dados da COVID-19 dos governos estaduais. Sua [metodologia de avaliação](https://transparenciacovid19.ok.org.br/files/Nota_Metodologica_Transparencia_da_Covid-19V.2.pdf) dispôs que

> a divulgação anonimizada de dados relativos a cada caso, separadamente, é importante para a construção de um panorama mais preciso sobre o avanço do novo coronavírus no país. **Informações sobre sexo, idade, município, possível origem do contágio e tratamento conferido são exemplos de dados que podem ajudar a construir uma boa base de dados de monitoramento**.

Em 06/05, a [OKBR sustentou](https://transparenciacovid19.ok.org.br/files/Toolkit_1_microdados_basicos.pdf) que 

> _Dados de saúde são considerados dados sensíveis pela Lei Geral de Proteção de Dados Pessoais, e, por isso, **é necessário ter o máximo de cautela ao coletar e administrar esses dados**. No caso da disponibilização de dados sobre a Covid-19, a solução mais simples para mitigar os riscos à privacidade se encontra nos diferentes níveis de detalhamento e agregação que podem ser empregados aos dados coletados. **Quando a publicação vincula diretamente atributos de idade e sexo dos pacientes a seus respectivos locais de internação, por exemplo, isso pode facilitar a identificação de um determinado paciente, sobretudo em municípios pequenos**. Esse tipo de publicação não é incentivada pelo ITC-19. No entanto, uma opção para não expor os pacientes e nem deixar de publicar esses dados -- que são todos igualmente importantes -- é divulgar o quantitativo de casos por hospital, e, separadamente, publicar os Microdados de casos com as informações de idade e sexo_. 

Em âmbito internacional, não se percebe experiência análoga com relação à divulgação do microdado, embora a própria Organização Mundial da Saúde tenha previsto alguns dados pessoais em seu [modelo de relatório baseado em casos](https://www.who.int/who-documents-detail/data-dictionary-for-case-based-reporting-form). Ademais, a Lei Geral de Proteção de Dados prevê a "utilização de meios técnicos razoáveis e disponíveis na ocasião de seu tratamento". Tal mecanismo, denominado [anonimização](http://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/L13709.htm#art5), **deve fazer com que o dado perca a possibilidade de associação, direta ou indireta, a um indivíduo**. Nesse sentido, sabe-se que a mera remoção dos atributos de identificação direta de uma pessoa (como nome e CPF) pode não ser suficiente para afastar tal possibilidade. 

O [International Household Survey Network pontuou essa questão como desafio técnico, legal e ético](https://ihsn.org/dissemination-of-microdata-files). Lidamos, portanto, com um contexto em que divulgar microdados parece ser um problema geral, ao mesmo tempo que relevante e não trivial. Tomando tais aspectos em conta, bem como os [conjuntos de dados divulgados sobre a COVID-19](http://www.transparencia.dadosabertos.mg.gov.br/organization/secretaria-de-estado-de-saude), que contém dados pessoais como:

- classificação do caso (confirmado, suspeito, descartado ou óbito) e suas datas de notificação e de atualização;
- idade;
- sexo;
- comorbidades (sim ou não);
- município de residência[^1]

[^1]: Existem 853 municípios no estado de Minas Gerais, [dos quais 666 possuem menos de 20 mil habitantes](https://pt.wikipedia.org/wiki/Lista_de_munic%C3%ADpios_de_Minas_Gerais_por_popula%C3%A7%C3%A3o)

**Como determinar o risco de re-identificação de tais pacientes?** 

**Em havendo um risco considerável, quais procedimentos adicionais seriam adequados para minimizá-lo?** 

Retomando o [documento do International Household Survey Network](https://ihsn.org/dissemination-of-microdata-files), que indica técnicas de de mitigação da possibilidade de reidentificação, como

* divulgação da amostragem, em vez do universo dos dados;

* categorização de medidas de variáveis em novas categorias (eg., faixas etárias), especialmente quando valores extremos são raros (no caso, óbitos de pacientes mais jovens);

* combinação de duas variáveis formando uma nova variável agregada (eg., idade e gênero combinados);

* remoção de variáveis (eg. municípios abaixo de uma determinada faixa populacional)


**Poderiam ser recomendadas para o caso da divulgação dos dados dos pacientes nos municípios de Minas Gerais citados acima, no caso de haver um risco considerável de reidentificação?**





