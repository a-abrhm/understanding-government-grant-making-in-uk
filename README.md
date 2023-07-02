# Understanding-government-grantmaking-in-the-UK
Conducted an exploratory analysis to gain insights into the evolution of UK Government grant making over time, examining its relationship with recipient organization themes. Assessed the alignment of grants with government objectives and investigated the presence of multiple awarding bodies providing grants to the same organization.

The [dataset](https://grantnav.threesixtygiving.org/search?query=UK+government&default_field=%2A&sort=_score+desc) for this project was obtained from the 360Giving archives. Their Grantnav portal interface lets the user select a specific combination of attributes like time period, grant min amount and max amount, grant provider and recipient to generate the corresponding csv file and download it. Only data for grants originating from the government (Local, Central and Devolved) were considered. The dataset shows the date at which the grant was requested and given, the amount requested and given, the funding and recipient organisations and a title and description of the grant.


This repository contains the source codes used for data ingestion, preprocessing, transformation and visualisation. Apart from the exploratory analysis, a time-series model was created using Facebook’s Prophet to try and predict the most likely recipients of the grants by the UK government in the coming year.
