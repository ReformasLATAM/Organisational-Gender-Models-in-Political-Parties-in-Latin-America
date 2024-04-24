# Organisational Gender Models in Political Parties in Latin America 

Welcome to the GitHub repository of the database "Organisational Gender Models in Political Parties in Latin America," maintained by members of the Political Reform Observatory in Latin America.

## Contents

- [Summary](#summary)
- [Description](#description)
- [Citation](#citation)
- [References](#references)

## Summary

The database contains information to describe and understand the formal organisational models that have been developed in Latin American political parties, identifying which ones are gender balanced and evaluate to what extent these organisational structures contribute to women's descriptive representation in the legislative branches.   

Although informal politics are key to understand how political parties operate (Bjarnegård and Kenny 2016; Kenny and Verge 2016; Piscopo 2016; Freidenberg and Levitsky 2006), this research focuses on the analysis of formal regulations that shape the power dynamics or scenarios in which party members operate, participate, legitimise incentive distribution, and determine decision making. 

Organisational models involve territorial, functional and identity criteria (such as those explicitly based on gender) determining how tasks and actions are distributed to achieve goals and determine incentive distribution and participation (Panebianco 1982). Formal organisational models are internal structures outlined in statutory regulations, determining power relations construction, decision- making processes and participation incentive distribution regulation (selective and/or collective) (Panebianco 1982; Janda 1980). 

The database supports “Organisational Models, Formal Regulations and Feminization of Latin American Political Parties” a research project within the Observatory of Political Reforms in Latin America (#ObservatorioReformas), Institute for Legal Research (IIJ- UNAM) and Washington, D.C.: Secretariat for Strengthening Democracy of the Organization of American States (SSD/OAS). The research is in process. 

The selection of relevant parties in 16 countries in Latin America, part of the observation unit in this work is based on the methodology used by Alcántara Sáez y Freidenberg (2001) who established a selection matrix based on four criteria. 

The four criteria are that a party: a) has obtained representation in the lower house in the last three legislative elections (numerical strength expressed in seats or votes obtained), b) has surpassed the electoral threshold of 5% in the last three lower house legislative elections, c) has representation in all country electoral districts (territorial strength) or has a significant  representation in certain districts, d) substantially contributes to the party dynamics of the political system, meaning it displays influence capacity within the political system (even if it does not meet the aforenamed criteria). 

The four criteria were applied to 110 parties in 16 countries of the region in the first stage. The result showed that 54 parties met the “relevant parties” four criteria analysed in the last two legislative periods of each country. Regarding the first two criteria there were no difficulties in the operationalization. The third criterion, measuring territorial strength, was applied based on the percentage of electoral   districts in which the parties presented candidacies for the Lower House.

Finally, the fourth criterion, measuring the influence within the political system, considered if parties had won presidential elections, had a high level of institutionalisation (Freidenberg 2016) or played an important role within the party system through their blackmail potential, meaning altering decisions of other parties (Sartori 1992). 

In the second stage, experts of the Observatory of Political Reforms in Latin America were requested to review the selection and application of criteria to the group of evaluated parties. The role of the experts was to validate the party selection submission made by the research team. The external evaluation exercise strengthened the selection submission by enhancing and clarifying the role played by the parties in each of the party systems in the region.

Once the 54 observation units were identified, the articles detailing the way parties organise themselves concerning women's political participation were located within each of their statutes.  The statutes were collected from official websites, queries made to the electoral authorities of each country or else from accessible social media platforms. Those aforementioned statutes were published on the Observatory of Political Reforms in Latin America website.

Members of the Observatory of Political Reforms in Latin America collected and coded the information. The responsible for information collection managers are Carlos Guadarrama (Latin American Faculty of Social Sciences, FLACSO Mexico), Mauricio Morales (Faculty of Political and Social Sciences, UNAM), Lucía Rosemblat (University of Buenos Aires) Daniela Sosa (Faculty of Higher Studies Aragón, UNAM), Fernanda Nicoletti (Faculty of Higher Studies Acatlan, UNAM) and Eduardo Flores (Faculty of Higher Studies Acatlan, UNAM).

The information coding managers are Flavia Freidenberg (Institute for Legal Research, UNAM),
Carlos Guadarrama (Latin American Faculty of Social Sciences, FLACSO Mexico) and Karolina Gilas (Faculty of Political and Social Sciences, UNAM).

## Description

The directory `./Data/` contains the file `./Data/DD_OrganisationalGenderModels` where all relevant information regarding the database linked to organisational gender models in political parties in Latin America. Specifically, the database consists of the following variables:

-   `party`: name of the party organisation considered in the sample.

-   `country`: name of the country where the reform of the organisational gender model was implemented.

-   `country_code`: country code according to the three- letter ISO code (e.g. ARG, MEX, SAL) available at: http://utils.mucattu.com/iso_3166-1.html 

-   `desc_rep`: indicates the percentage of female legislators under all principles of representation in political parties in each one of the two legislative periods. 

-   `org_mdl`: label for the organisational structure according to party statutes. Its values range from 0 to 3, where 0 represents the least favourable to women and 3 is the most conducive or friendly to women, 0 = absent, 1= bureaucratic structure 2 =autonomous structure 3 = Mixed (bureaucratic structure and autonomous structure).

-   `ifreg`: gender Electoral Regime Strength, Caminotti and Freidenberg (2016). 
 
-   `institutionalisation`: years elapsed between the party’s creation and the year of this research (2022).

-   `ideology`: self-identification of the legislators based on surveys conducted by the Latin American Parliamentary Elites Project.

-   `gend_pres`: indicates the presence of women in political parties presidencies in at least one observed period. Its values are 0= absence and 1= presence.

## Citation

``` r
Freidenberg, Flavia. Dir., 2022, “Organisational Gender Models in Political Parties in Latin America” Observatory of Political Reforms in Latin America (1978-2022). Mexico City: Institute for Legal Research (IIJ- UNAM) and Washington, D.C.: Secretariat for Strengthening Democracy of the Organization of American States (SSD/OAS), V1. DOI: https://doi.org/10.6084/m9.figshare.20341359.v1.
```

## References

Alcántara Sáez, Manuel and Freidenberg, Flavia. 2001. Ed. Political Parties in Latin America. Salamanca. Ed. University of Salamanca.

Bjarnegård, Elin and Kenny, Meryl. 2016. Comparing candidate selection: A feminist institutionalist approach. Government and Opposition 51(3): 370–392.

Caminotti, Mariana and Freidenberg, Flavia. 2016. "Electoral Federalism, Strength of Gender Quotas, and Political Representation of Women in Subnational Arenas in Argentina and Mexico". Mexican Journal of Political and Social Sciences 61 (228): 121-144.

Freidenberg, Flavia. Ed. 2016. The Party Systems in Latin America 1978-2015. 2 volumes. Mexico City: National Electoral Institute and Institute for Legal Research, UNAM.

Freidenberg, Flavia and Levitsky, Steve. 2006. “Informal Party Organizations in Latin America”, in Helmke, Gretchen and Levitsky, Steven (Eds.), Informal Institutions and Democracy: Lessons from Latin America. Washington, D.C.: John Hopkins University Press, 178-197.

Janda, Kenneth. 1980. Political Parties: A Cross-National Survey. New York: The Free Press.

Kenny, Meryl and Verge, Tània. 2016. “Opening Up the Black Box: Gender and Candidate Selection in a New Era.” Government and Opposition 51(3): 351–369.

Panebianco, Angelo. 1982. Party Models. Madrid: Alianza.

Piscopo, Jennifer M. 2016. “When Informality Advantages Women: Quota Networks, Electoral Rules and Candidate Selection in Mexico”. Government and Opposition 51(3): 487–512.

Sartori, Giovanni. 1992. Parties and Party Systems. Madrid: Alianza.