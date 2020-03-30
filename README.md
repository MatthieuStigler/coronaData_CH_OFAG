---
title: "README"
author: "Matthieu"
date: "03/29/2020"
output:
  html_document:
    keep_md: yes
---

# Download/process daily Swiss reports from the Federal Office of Public Health

## Sources 

- English page, though does not contain data:  https://www.bag.admin.ch/bag/en/home/krankheiten/ausbrueche-epidemien-pandemien/aktuelle-ausbrueche-epidemien/novel-cov/situation-schweiz-und-international.html#-377606726
- Page in French with the data: https://www.bag.admin.ch/bag/fr/home/krankheiten/ausbrueche-epidemien-pandemien/aktuelle-ausbrueche-epidemien/novel-cov/situation-schweiz-und-international.html
- Direct link: https://www.bag.admin.ch/dam/bag/fr/dokumente/mt/k-und-i/aktuelle-ausbrueche-pandemien/2019-nCoV/covid-19-datengrundlage-lagebericht.xlsx.download.xlsx/200325_base%20de%20donn%C3%A9es_graphiques_COVID-19-rapport.xlsx


## This repo

This code simply downloads the data, simple cleaning and produces 1) a bar plot by age and gender: 

![Image stored in: output/figures/deaths_by_age](output/figures/deaths_by_age.png?raw=true)

and 2) Evolution over time by age (total male and female)

![Image stored in: output/figures/deaths_over_time_by_age.png](output/figures/deaths_over_time_by_age.png?raw=true)
