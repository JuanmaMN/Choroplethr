# Choroplethr


## Choroplethr package


New course to learn how to visualize data from the US Census Bureau’s American Community Survey (ACS), using the R package Choroplethr.

- [Choroplethr](https://www.census.gov/data/academy/courses/choroplethr.html)
- [Guide](https://cran.r-project.org/web/packages/choroplethr/choroplethr.pdf)




#### 2012 State Population Estimates - Code
```
state_choropleth(df_pop_state,
                 title  = "2012 State Population Estimates",
                 legend = "Population")
                 
```
                 
                 
<img width="451" alt="Firstgraphclo" src="https://user-images.githubusercontent.com/37122520/57980951-cc384b80-7a29-11e9-819e-5dd41a0b777b.png">






#### Population of New York State by county - Code


```
zip_choropleth(df_pop_zip, 
                state_zoom = "new york", 
                 title="Population of New York State by county") + coord_map()
```

<img width="404" alt="NewYorkbycountry" src="https://user-images.githubusercontent.com/37122520/57980954-d5c1b380-7a29-11e9-8998-74c909225013.png">




#### 2012 World Bank Populate Estimates - Code

```
    country_choropleth(df_pop_country, "2012 World Bank Populate Estimates")

```

<img width="493" alt="Population" src="https://user-images.githubusercontent.com/37122520/57981143-aa3fc880-7a2b-11e9-8690-ad2015442e72.png">
