Vac_Covid19_BR_SC_Combinations_of_Concern_5

* Clinical Data Scientist: Aldir MEDEIROS FILHO
* FLORIANOPOLIS, Santa Catarina(SC), Brasil
* 02 Sep 2021

# Introduction:

This is the 5th monthly edition of my personal project named 'Combinations_of_Concern - CoC'. The first 4 were initiated and developped during my attendance to [Alura Bootcamp Applied Data Science II (Brazilian Winter 2021)](https://www.alura.com.br/bootcamp/data-science-aplicada/matriculas-abertas) that was done in parallel to a sequence of 32 Alura courses focused exclusively on the Python language between 01 May and 30 Aug 2021.

This 5th edition is a continuation and extension of the exploratory work I already done during the first four editions, when I reviewed the [OpenDataSus registers of covid19 vaccination](https://opendatasus.saude.gov.br/dataset) in the Brazilian State of Santa Catarina(SC).

For the first two editions, due to my limited knowledge of Python at that time I used a mix of terminal command line, Python&Colab and Excel, one for each of the 3 initial phases of the project. From the 3rd edition onward the learnings from the Alura courses helped to deliver all the 3 phases in one Colab notebook.

The main findings until here were:

From February to end June 2021 a constant trend of ~ 12% of registers for which we can not confirm which vaccine an individual received when I cross-checked 3 variables from the master dataset. I named this troublesome combinations as 'Combinations of Concern' - CoC (step 5 here after for definition).

At the end of July we noticed a reduction to ~ 10% of total of registrations responding to my definition of 'Combination of Concern'.

This 5th edition shows that at end of August 2021 (checked on 02 Sep 21) the monthly trend on the proportion of 'Combinations of Concern' continues in the early teens (11% end August 2021).

##AMF: Technical Warning: For this 5th edition early September 2021, due to the significant increase on the rows in the raw dataset(sc0209_07am), I was obliged to subscribe to Google Colab Pro in order to have a connection to GPU and high-RAM runtime available. This information is important to know about the limitations of the free version of Google Colab.

I welcome any comments about errors (I am sure there are), suggestions for improvement and collaboration to perform the same investigation for other Brazilian states.

Best Regards

Aldir Medeiros Filho


[Dataset Source – OpenDataSus - Registros de Vacinação Covid19 - Dados SC – Santa Catarina – Brasil](https://opendatasus.saude.gov.br/dataset/covid-19-vacinacao/resource/ef3bd0b8-b605-474b-9ae5-c97390c197a8)

For this edition 5 the dataset downloaded on 02 Sep 2021 at 07:00 am

| Edition | 'Combinations_of_Concern" github                                                                                                                   | Published    | raw file        | Raw size | columns | rows (registrations) | new registrations |
|---------|----------------------------------------------------------------------------------------------------------------------------------------------------|--------------|-----------------|----------|---------|----------------------|-------------------|
| 1+2     | https://github.com/amf60/Vac_Covid19_BR_SC_Combinations_of_Concern_1 <br> <br>https://github.com/amf60/Vac_Covid19_BR_SC_Combinations_of_Concern_2 | early Jun 21 | sc3005_05am.csv |  1.11 GB |    34   |            2,017,225 |                   |
| 3       | https://github.com/amf60/Vac_Covid19_BR_SC_Combinations_of_Concern_3                                                                               | early Jul 21 | sc0207_07am.csv |  1.71 GB |    34   |            3.133.344 |         1.116.119 |
| 4       | https://github.com/amf60/Vac_Covid19_BR_SC_Combinations_of_Concern_4                                                                               | early Aug 21 | sc0408_10am.csv |  2.6 GB  |    34   |            4.854.329 |         1.720.985 |
| 5       |                                                                                                                                                    | early Sep 21 | sc0209_07am.csv |  3.66 GB |    34   |            6.822.321 |         1.967.992 |

table above prepared using https://www.tablesgenerator.com/markdown_tables

Covid-19 vaccination records in the Brazilian state of Santa Catarina

For information only, here after all the central government official information for the Brazilian State of Santa Catarina on 02 Sep 2021.

![Screen Shot 2021-09-02 at 16 46 43](https://user-images.githubusercontent.com/39899585/131907104-fcb14ece-f298-4886-b63b-95e48c69dd50.png)

