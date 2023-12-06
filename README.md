# DS4002-Project2
## SRC section
### Installing/building:
· **4002proj2.twb**: This file is created in Tableau and must run in Tableau. Once open the file, you should be able to see all the plot that already created.

### Usage
· **4002proj2.twb**: This file is used to visualize the trend of climate change related cover and environment related cover vs year and vs month.

## DATA section
· **covers**: This folder contains images of National Geographics cover from 1980 to 2023.  
· **NG_Cover_Findings_monthly.csv**:  
| Column Name | Description |
|---------------|-------------|
|  Year  |  Specific year of the National Geographics Cover  |
|  Month |  Specific month of the National Geographics Cover |
|  Themes in the Picture | Themes we identified from this specific cover|
| Climate Change Related? (Y/N)| Does this cover display climate change related themes, Y means yes, N means no|
| Binary | Change the Y/N value from the previous column into 0 and 1 |
| Relatad to Environment? (Y/N)| Does this cover display climate change related themes, Y means yes, N means no|
| Binary | Change the Y/N value from the previous column into 0 and 1 |
| Quantity (Parts Per Million) | CO2 quantity data in parts per million |
| Percent | The percentage of CO2 calculated from the quantity data |  

· **annual_data.csv**:  
| Variable Name | Description |
|---------------|-------------|
| Year | Specific year |
| Climate_Count | How many covers are related to climate changes in this year |
| Environment_Count | How many covers are related to environmental issues in this year |
| Forest(sq_mi) | The annualy forest data in square mile |
| Endangered_Species | How many endangered species in this year |  


## FIGURES section
| Figure Name | Description | Takeaways |
|---------------|-------------|--------|
|Clim_Envir_vs_Month.jpg | This plot visualized the trend of climate change related cover and environment related cover throughout the year.| Before climate change, the major environmental issue that National Geographic often refers to is protecting wildlife. |
|Clim_Envir_vs_Year.jpg | This plot visualized the trend of climate change related cover and environment related cover in each month. | Covers at the end of each year are more likely to have environmental issue related themes or climate change themes. |
| cover_theme_wordcloud.png | This plot showed word cloud on themes that appeared in all National Geographic's Covers from 1980 to 2023.|The magazine features many human headshots and portraits on the cover page. Other common occurrences are animal photos, archaeological relics, and landscapes. |  


## REFERENCES section
[1] “See All ‘National Geographic’ Magazine Covers in Timelapse Video,” Hypebeast, Jan. 17, 2018. https://hypebeast.com/2018/1/national-geographic-all-magazine-covers (accessed Oct. 08, 2023).  
[2] NASA, “Climate Change Evidence: How Do We Know?,” Climate Change: Vital Signs of the Planet, Sep. 21, 2018. https://climate.nasa.gov/evidence/ (accessed Oct. 06, 2023)  
[3] R. A. Butler, “What’s the deforestation rate in the Amazon?,” Mongabay, https://rainforests.mongabay.com/amazon/deforestation-rate.html (accessed Oct. 21, 2023).  
[4] U. S. F. and W. Service, “List of Endangered Animal,” Listed+Animals, https://ecos.fws.gov/ecp0/reports/ad-hoc-species-report?kingdom=I&amp;status=SAT&amp;mapstatus=3&amp;fcrithab=on&amp;fstatus=on&amp;fspecrule=on&amp;finvpop=on&amp;fgroup=on&amp;header=Listed%2BAnimals (accessed Oct. 21, 2023).  

Milestone 1: https://docs.google.com/document/d/1cHZPIl57EYzHqWuAV0WTfEzTLOtfPqZK3QV_jZWmCX8/edit?usp=sharing  
Milestone 2: https://docs.google.com/document/d/1HWAdjcllrV_OlG0vXwu0Ju1_HyqQt44CszcLylESLyw/edit?usp=sharing  

Article 1: https://medium.com/@MariosKapsis94/the-most-iconic-national-geographic-covers-cd3578870daa
Article 2: https://www.nationalgeographic.com/photography/article/dedicated-to-our-mission-of-changing-the-world-for-the-better

