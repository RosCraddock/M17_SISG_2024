This site contains course materials for SISG Module 17: WGS Data Analysis, June 12-14, 2024. 

- **Instructors:** Laura Raffield and Matthew Conomos

## Course Format

#### Lectures
Course material will be presented through lectures. Slides for lectures are linked in the schedule below.

#### Exercises
Many of the lectures will be followed with hands-on exercises. Students are encouraged to work through the exercises together. Afterwards, the instructors will walk through the exercises and lead a discussion.

To run the exercises, log into [NHLBI BioData Catalyst powered by Seven Bridges](https://platform.sb.biodatacatalyst.nhlbi.nih.gov) with your username and password -- we will use this platform for live demonstrations during the course.

- You will retain access to the Seven Bridges platform, including your SISG Project with all of the course materials even after the course ends. The SISG24 Workshop billing group will remain available to you for a short period of time, after which you will need to set up another payment method to run analyses. You can [request pilot cloud credits](https://biodatacatalyst.nhlbi.nih.gov/resources/cloud-credits) ($500 worth) from BioData Catalyst. Additionally, there is guidance available for [writing BioData Catalyst cloud costs into your grant proposal budget](https://bdcatalyst.gitbook.io/biodata-catalyst-documentation/written-documentation/getting-started/writing-biodata-catalyst-into-a-grant-proposal). 

All of the R code and data can also be downloaded from the [github repository](https://github.com/UW-GAC/SISG_2024) from which the site is built and run on your local machine. Download the complete workshop data and exercises: [https://github.com/UW-GAC/SISG_2024/archive/main.zip](https://github.com/UW-GAC/SISG_2024/archive/main.zip)


## Schedule

NOTE: All times are Eastern Daylight Time (GMT-04:00)

**Wednesday, June 12th**

| Time | Topic | Lecture | Exercises/Discussion |
| --- | --- | --- | --- |
| 1:30pm-1:35pm | Introduction | Slides | |
| 1:35pm-3:00pm | Intro to Cloud Computing for WGS Data Analysis | [Slides] | |
| 3:00pm-3:30pm | _Coffee Break_ | | |
| 3:30pm-5:00pm | GWAS | [Slides] | [Slides] [.html] |

**Thursday, June 13th**

| Time | Topic | Lecture | Exercises/Discussion |
| --- | --- | --- | --- |
| 8:30am-10:00am | GWAS: Advanced Model Extenstions | [Slides] | [Slides] [.html] |
| 10:00am-10:30am | _Coffee Break_ | | |
| 10:30am-12:00pm | Leveraging Multi-Ancestry Data: Part 1 | [Slides] [.html] |
| 12:00pm-1:30pm | _Lunch Break_ | | |
| 1:30pm-3:00pm | Leveraging Multi-Ancestry Data: Part 2 | [Slides] [.html] |
| 3:00pm-3:30pm | _Coffee Break_ | | |
| 3:30pm-5:00pm | Variant Annotation: Part 1 | [Slides] | [.Rmd] [.html] |

**Friday, June 14th**

| Time | Topic | Lecture | Exercises/Discussion |
| --- | --- | --- | --- |
| 8:30am-10:00am | Variant Annotation: Part 2 | [Slides] | |
| 10:00am-10:30am | _Coffee Break_ | | |
| 10:30am-12:00pm | Multi-Variant Association Tests | [Slides] [.html] |
| 12:00pm-1:30pm | _Lunch Break_ | | |
| 1:30pm-3:00pm | STAAR | Slides | [.Rmd] [.html] |
| 3:00pm-3:30pm | _Coffee Break_ | | |
| 3:30pm-5:00pm | Recent Findings and Resources for WGS Analysis | [Slides] [.html] |

## R packages used

- [GENESIS](http://bioconductor.org/packages/release/bioc/html/GENESIS.html)
- [SeqArray](http://bioconductor.org/packages/release/bioc/html/SeqArray.html)
- [SeqVarTools](http://bioconductor.org/packages/release/bioc/html/SeqVarTools.html)
- [SNPRelate](http://bioconductor.org/packages/release/bioc/html/SNPRelate.html)
- [Biobase](https://bioconductor.org/packages/release/bioc/html/Biobase.html)
- [GGally](https://cran.r-project.org/web/packages/GGally)


## Resources

A detailed tutorial and relevant R scripts for STAAR pipeline are available at [https://github.com/xihaoli/STAARpipeline-Tutorial](https://github.com/xihaoli/STAARpipeline-Tutorial).

If you are new to R, you might find the following material helpful:

- [Introduction to R](http://faculty.washington.edu/kenrice/rintro/) materials from SISG Module 3
- Graphics with [ggplot2](https://ggplot2.tidyverse.org/)
- Data manipulation with [dplyr](http://dplyr.tidyverse.org/)
