## Simple regression

> [!info] Simple regression
> **Simple regression** is een [[1. Regression|regression]]-probleem waarbij **één** [[2. Feature, label en target#Feature|feature]] wordt gebruikt om **één** numerieke [[2. Feature, label en target#Target|target]] te voorspellen.
> 
> Wanneer hiervoor een lineair model wordt gebruikt, spreken we specifieker van **simple linear regression**.

> [!example]+ Voorbeeld  
> Een model gebruikt alleen de **leeftijd** van een patiënt om de **opnameduur** te voorspellen.
> 
> - Leeftijd is de enige **feature**.     
> - Opnameduur is de enige **target**.     
> 
> Omdat één feature wordt gebruikt om één numerieke target te voorspellen, gaat het om **simple regression**.
## Multiple regression

> [!info] Multiple regression
> Een **multiple regression problem** is een [[1. Regression|regression]]-probleem waarbij **twee of meer** [[2. Feature, label en target#Feature|features]] worden gebruikt om **één** numerieke [[2. Feature, label en target#Target|target]] te voorspellen.
> 
> Het onderscheid met een eenvoudig regression problem met één feature zit dus in het **aantal inputvariabelen**, niet in het aantal targets.

> [!example]+ Voorbeeld  
> Een model voorspelt de opnameduur van een patiënt op basis van:
> 
> - leeftijd     
> - BMI     
> - aantal eerdere opnames>     
> 
> De drie waarden zijn **features** en de opnameduur is de **target**. Omdat meerdere features worden gebruikt om één numerieke target te voorspellen, is dit een **multiple regression problem**.