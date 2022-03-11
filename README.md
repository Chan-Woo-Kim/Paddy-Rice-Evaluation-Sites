# Paddy-Rice-Evaluation-Sites
30 samples are selected for each sampling site in our study area using stratified sampling method, which classifies the whole data into different provincial groups and randomly extracts the samples from each provincial group. 

### 30 sampling sites in the red grid

![image](https://user-images.githubusercontent.com/101398489/157885512-d6ac16f8-895c-44ef-aeff-ccdc982c3432.png)

### Data

- The agricultural area data is provided by Statistics Korea into different provincial groups.(https://kosis.kr/statHtml/statHtml.do?orgId=101&tblId=DT_1EB002). The already existing paddy rice map includes non-agricultural and fallow land that are not necessary. 

- The created paddy rice validation data includes only paddy rice information

### Implementation

paddy rice and Crop land was divided by growth period through visual interpolation, based on their texture and color, in order to be used as criteria for creating the paddy rice validation data.

### Texture, Color, Characteristics, Classification method and criteria by growth period of paddy rice

- After harvesting, before sowing (Nov ~ Apr): straight and rough pattern, dark brown

![image](https://user-images.githubusercontent.com/101398489/157891020-a7a3821a-24c4-43c5-8b31-576073804bc3.png)  ![image](https://user-images.githubusercontent.com/101398489/157891028-7b380b76-0acf-4ef9-a2fb-97c54827a5db.png)

- After sowing and planting (May ~ Jun): soft surface filled with water, light brown

![image](https://user-images.githubusercontent.com/101398489/157890930-67ffdebf-4ae1-4252-ad0d-a4b909e329eb.png)  ![image](https://user-images.githubusercontent.com/101398489/157890948-5fbc212a-c7dc-49b3-aac3-fdada00b006f.png)

- Growth (Jun ~ Oct): grainy surface, light green

![image](https://user-images.githubusercontent.com/101398489/157890774-361fb4d9-454b-4677-8cd3-fc261c5c77b8.png)  ![image](https://user-images.githubusercontent.com/101398489/157890884-d4c148a0-0e12-4479-b9c4-142f2eb06f8a.png)

### Result

The paddy rice validation data is in the format of shape, and the size of sampling sites with 2.56km resolution. The visual interpolation was performed intensively from July to October when rice growth was best seen. 

- In the case where it is used as paddy rice but there is no information

![그림1](https://user-images.githubusercontent.com/101398489/157892198-5ae4a873-d550-47ea-a685-74439c917446.png)

- In the case the boundaries are wrong

![그림2](https://user-images.githubusercontent.com/101398489/157892828-c270739b-36c8-4dfa-a21c-6d5f42aaadc5.png)

-	In the case the area isn’t the paddy rice

![그림3](https://user-images.githubusercontent.com/101398489/157892880-fc10df25-2121-4e6c-924f-9eaa9937eabb.png)

### Reference

If you use this dataset, please cite the DOI below 10.5281/zenodo.5845896 (https://doi.org/10.5281/zenodo.5845896)

### Acknowledgements

This work was supported by International Research and Development Program of the National Research Foundation of Korea (NRF) funded by the Ministry of Science and ICT under Grant (2021K1A3A1A78097879) and supported by the European Commission under Contract H2020- CALLISTO1 ( 101004152) by Korea University, South Korea.

Researchers: Chan-Woo Kim (ehdrkdgml@gmail.com), Woo-Kyun Lee(leewk@korea.ac.kr)
