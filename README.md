# Persistent recovery gap in soil fungal communities after vegetation restoration in forest and grassland ecosystems: a meta-analysis

## Authors

**Sujan Balami**<sup>a,b,c</sup>,  
Fang-Yuan Hua<sup>d</sup>,  
Yu-Xuan Mo<sup>a,b,c</sup>,  
Xian-Meng Shi<sup>a,b,c,e</sup>,  
Hai-Xia Hu<sup>a,b,f</sup>,  
Yue-Hua Hu<sup>a,b,c</sup>,  
Gbadamassi G. O. Dossa<sup>a,b,c</sup>,  
Chaeho Byun<sup>g</sup>,  
Liang Song<sup>a,b,c*</sup>

---

## Affiliations

<sup>a</sup> State Key Laboratory of Plant Diversity and Specialty Crops, Xishuangbanna Tropical Botanical Garden, Chinese Academy of Sciences, Mengla, Yunnan 666303, China  

<sup>b</sup> Laboratory of Tropical Forest Ecology, Xishuangbanna Tropical Botanical Garden, Chinese Academy of Sciences, Mengla, Yunnan 666303, China  

<sup>c</sup> Yunnan Key Laboratory of Forest Ecosystem Stability and Global Change, Xishuangbanna Tropical Botanical Garden, Chinese Academy of Sciences, Yunnan 666303, China  

<sup>d</sup> Institute of Ecology and Key Laboratory for Earth Surface Processes of the Ministry of Education, College of Urban and Environmental Sciences, Peking University, Beijing 100871, China  

<sup>e</sup> College of Biology and Food, Shangqiu Normal University, Henan 476000, China  

<sup>f</sup> University of Chinese Academy of Sciences, Beijing 100049, China  

<sup>g</sup> Department of Biological Sciences, Gyeongkuk National University, Andong 36729, Republic of Korea  

---

## Corresponding Author

**Prof. Liang Song**  
Xishuangbanna Tropical Botanical Garden, Chinese Academy of Sciences  
Xishuangbanna, Yunnan 666303, China  

Email: songliang@xtbg.ac.cn  

---

## Contact for Reproducibility and Code

**Sujan Balami** Ph.D.  

Email: balamisujan@gmail.com


---

## Description

Meta-analysis of soil fungal community recovery during vegetation restoration in forest and grassland ecosystems.


## How to use execute

Download `meta-analysis-restoration-fungi.zip`, which contains all files associated with this repository.

Next, download **R version 4.5.3** from https://cran.rstudio.com/ according to your operating system (Windows, macOS, or Linux).

Then, download **RStudio 2026.04.0** from https://posit.co/download/rstudio-desktop/ according to your operating system (Windows, macOS, or Linux).

After downloading, navigate to the folder containing `meta-analysis-restoration-fungi.zip` and extract the archive. Inside the extracted folder, you will find:

- `Rcodes.Rmd`
- `README.md`
- `data_overview/`
- `figure_data/`
- `original_data/`

Open `Rcodes.Rmd` in RStudio. Once opened, click the Knit button.

<img width="40" height="30" alt="Knit button" src="https://github.com/user-attachments/assets/328d5f83-e251-4108-bfe3-6f49e4fe4e77" />

This will execute the `Rcodes.Rmd` file. The runtime is approximately one hour, depending on your computer specifications.

After the analysis is completed, an `Rcodes.html` file will be generated and saved in the same folder. Open `Rcodes.html` in any web browser to view all outputs, messages, and figures.



## Tested on

The analyses in `Rcodes.Rmd` were tested and executed on the following systems:

### Windows System
- **Operating System:** Microsoft Windows 11 Home (Version 10.0.26200 Build 26200)
- **Processor:** 11th Gen Intel(R) Core(TM) i7-1165G7 @ 2.80 GHz (4 cores, 8 logical processors)
- **RAM:** 16 GB
- **System Type:** x64-based PC
- **Machine:** Samsung 530ADA/531ADA Desktop
- **R Version:** 4.5.3
- **RStudio Version:** 2026.04.0

### macOS System
- **Machine:** MacBook Pro
- **Chip:** Apple M3
- **Operating System:** macOS Sonoma
- **Architecture:** ARM64
- **RAM:** 18 GB
- **R Version:** 4.5.3
- **RStudio Version:** 2026.04.0

The approximate runtime for rendering `Rcodes.Rmd` was around one hour, depending on system performance and available memory.


