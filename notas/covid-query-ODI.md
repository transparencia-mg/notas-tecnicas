
The Minas Gerais State Government started to disclose microdata related to the new coronavirus disease (COVID-19) last month. These microdata concern three datasets:
* [reported cases](http://www.transparencia.dadosabertos.mg.gov.br/dataset/casos-notificados-coronavirus), 
* [confirmed cases](http://www.transparencia.dadosabertos.mg.gov.br/dataset/casos-confirmados-coronavirus)
* [confirmed deaths](http://www.transparencia.dadosabertos.mg.gov.br/dataset/obitos-confirmados-coronavirus) 

This initiative was adopted in order to improve epidemiological data transparency and to highlight the results of government efforts to face the pandemic.

However, an issue take place when allowing unrestricted access to microdata: finding the balance between maximizing databases usefulness and minimizing re-identification risks.

This issue has been the subject of extensive discussion in the academic and professional fields. It also has become increasingly relevant, due to the strengthening of open government data policies, and to personal data protection policies.

The Open Knowledge Brasil (OKBR) noticed the need for balance in its weekly assessment of the transparency COVID-19 data released by state governments. Its [evaluation methodology](https://transparenciacovid19.ok.org.br/files/Nota_Metodologica_Transparencia_da_Covid-19V.2.pdf) points that:

> _publishing anonymous data relating to each COVID-19 case, separately, is important to provide a clear overview of COVID-19 progress in the country. **Information about sex, age, municipality, contagion tracing and treatment are examples of data that can build a good monitoring database**_.

On the other hand, in its [_Microdata Toolkit_](https://transparenciacovid19.ok.org.br/files/Toolkit_1_microdados_basicos.pdf),

> _Health data are among personal data ruled by the Brazilian General Personal Data Protection Law, and thus **maximum caution is required to collect and manage this data**. In the case of COVID-19 data disclosuring, the easiest way to ensure patient privacy is in the detail and aggregation levels of collected data. **If a resource of a dataset links the age and sex of patients to their hospitalization places, it can provide the means to patient reidentification, especially in small cities**. This type of publication is not encouraged by ITC-19. Publishing cases per hospital and patient microdata (i.e. sex and age) separetely, instead of stop publishing microdata, is recommended_.

The removal of a person's identification data, such as name and ID codes, is not enough to decrease re-identification risk. The Brazilian General Personal Data Protection Law states that [anonymization](http://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/L13709.htm#art5) implies the use of reasonable and available resources while treating data, whereby __a data no longer allows the identification of a person through direct or indirect association__.

At the international level, we haven't found similar experiences on official microdata disclosure, which publish, for example, an anonymized subset of the [variables collected](https://www.who.int/who-documents-detail/data-dictionary-for-case-based-reporting-form) by the World Health Organization for the purpose of [monitoring the evolution of COVID-19 cases](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/technical-guidance/surveillance-and-case-definitions), despite the researchers' interest in this information [^ case-level-data].

[^case-level-data]: [Epidemiological data from the COVID-19 outbreak, real-time case information](https://www.nature.com/articles/s41597-020-0448-0)

This could be explained by the challenge (technical, legal and ethical) to publish microdata files, as pointed out by the [International Household Survey Network (IHSN)](https://ihsn.org/dissemination-of-microdata-files). The IHSN indicates some non-perturbing-masking techniques to reduce reidentification risk, such as

* publishing of sampling, instead of the entire microdata file;
* global recoding (e.g. collapsing age into age intervals);
* local supression (when two variables with rare values taken together could lead to identifying a unique person);
* removing variables

Therefore, publishing personal microdata seems to be a relevant and not-trivial problem. Considering these aspects and the [data sets released on COVID-19](http://www.transparencia.dadosabertos.mg.gov.br/organization/secretaria-de-estado-de-saude), which contains personal data such as:

- case categories (confirmed, suspected, discarded or deaths) and its notification and update dates;
- age;
- sex;
- comorbidity (binary categories: 'yes' or 'not');
- hometown [^porte-municipios]: There are 853 cities in Minas Gerais State, [which less than 180 cities with more than 20,000 residents](https://fr.wikipedia.org/wiki/Municipalit%C3%A9s_du_Minas_Gerais_par_population)

we request technical assistance to assess:

* __How to measure the risk of re-identification of such patients? __

* __If there is a high risk, what additional procedures would be appropriate to minimize it? __

* __If there is a low risk, how to assess the additional risk incurred with the disclosure of additional variables? __


# notes