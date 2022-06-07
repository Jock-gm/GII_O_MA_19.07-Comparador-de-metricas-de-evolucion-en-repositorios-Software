![build-and-deploy](https://github.com/Joaquin-GM/GII_O_MA_19.07-Comparador-de-metricas-de-evolucion-en-repositorios-Software/actions/workflows/maven.yml/badge.svg)
[![Heroku](http://heroku-badge.herokuapp.com/?app=evolution-metrics-v2&style=flat&svg=1)](https://evolution-metrics-v2.herokuapp.com/)

<img src="https://github.com/Joaquin-GM/GII_O_MA_19.07-Comparador-de-metricas-de-evolucion-en-repositorios-Software/blob/main/Memoria/img/_LOGOAPP.png" alt="logo" width="200" height="200" />

# GII_O_MA_19.07-Comparador-de-metricas-de-evolucion-en-repositorios-Software 

Aplicación Java desarrollada empelada el framework Vaadin que toma como entrada un conjunto de direcciones de repositorios públicos o privados y calcula  medidas de la evolución que permiten comparar los repositorios. Versión actualizada de la aplicación original:
[comparador-de-metricas-de-evolucion-en-repositorios-software](https://gitlab.com/mlb0029/comparador-de-metricas-de-evolucion-en-repositorios-software)

## Metricas de evolución

Leyenda I=Issues C=Commits IC=Integración Continua DC=Despliegue Continuo 
   
*   I1 total number of issues. (6-44)

*   I2  commits  per  issue.  I1  divided  by  total  number  of commits. (0.5-1)

*   I3 percentage of issues closed( number of closed issues ∗ 100/I1). (87-100)

*   TI1 average of days to close an issue. (2.2-19.41)

*   TC1 average of days between commits. (1-4.3)

*   TC2 days between the first and the last commit. (81-198)

*   TC3 change activity range per month: total number of commits divided by lifespan number of months. (6-26.4)

*   C1 peak change: count number of commits in the peak month divided by total number of commits. (30%-40%)

*   IC1 total number of jobs executed (1-1000)

*   IC2 number of jobs executed last year (1-200)

*   IC3 number of executed job types (1-8)

*   DC1 total number of releases

*   DC2 number of releases released last year

## Trabajos previos

*   [Activity-Api](https://github.com/dba0010/Activiti-Api )

*   [Soporte de Métricas con Independencia del Lenguaje para la Inferencia de Refactorizaciones](https://www.researchgate.net/profile/Yania_Crespo/publication/221595114_Soporte_de_Metricas_con_Independencia_del_Lenguaje_para_la_Inferencia_de_Refactorizaciones/links/09e4150b5f06425e32000000/Soporte-de-Metricas-con-Independencia-del-Lenguaje-para-la-Inferencia-de-Refactorizaciones.pdf)

*   [Software Project Assessment in the Course of Evolution -  Jacek Ratzinger](http://www.inf.usi.ch/jazayeri/docs/Thesis_Jacek_Ratzinger.pdf)

## Datos de estudio experimental

*   [Datos experimentales: Métricas de evolución en TFGs](https://github.com/clopezno/clopezno.github.io/blob/master/agile_practices_experiment/DataSet_EvolutionSoftwareMetrics_FYP.csv)

## Repositorios para pruebas

*   https://gitlab.com/mlb0029/privatetestproject

*   https://gitlab.com/mlb0029/publictestproject

*   https://gitlab.com/mlb0029/ListaCompra

## APIs Investigadas para consexión con GitLab
Estas APIs de envoltura nos ahorran trabajo adaptando [GitLab REST API](https://docs.gitlab.com/ee/api/) a Java.

*   [java-gitlab-api](https://github.com/timols/java-gitlab-api)

*   [gitlab4j-api](https://github.com/gmessner/gitlab4j-api)

## Herramientas utilizadas

*   [Eclipse IDE for Java EE Developers. Version: 2018-09 (4.9.0)](https://www.eclipse.org/)

*   [Apache Maven v3.8.4](https://maven.apache.org/)

*   [Apache Tomcat v9.0.13](http://tomcat.apache.org/)

*   [Java SE 11 (JDK)](https://www.oracle.com/technetwork/java/javase/overview/index.html)

*   [gitlab4j-api v4.9.14](https://github.com/gmessner/gitlab4j-api)

*   [JUnit5 v5.3.1](https://junit.org/junit5/)

*   [Codacy](https://www.codacy.com/)

*   [Heroku](https://www.heroku.com/)

*   [Vaadin 13.0.0](https://vaadin.com/)
