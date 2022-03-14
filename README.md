# Paddy-Rice-Evaluation-Sites
30 sampling sites were sorted out using the stratified sampling method which categorize the whole data into each provincial group and randomly extract it from each group.

### 30 sampling sites in the red grid

![image](https://user-images.githubusercontent.com/101398489/157885512-d6ac16f8-895c-44ef-aeff-ccdc982c3432.png)

### Data

The data for the agricultural area provided by Statistics Korea was classified by each province.(https://kosis.kr/statHtml/statHtml.do?orgId=101&tblId=DT_1EB002). The existing paddy rice map includes non-agricultural land such as fallow land, which is unnecessary for the research.

To collect the precise paddy rice map, the visual image interpretation was done using Google Earth Pro with grid image in 2020, and it became the validation data including only paddy rice information.

### Implementation

The criteria for classification, whether paddy rice or other crop cultivation during each growing period, was set based on its texture and color while visual image interpretation.

### The classification criteria by each growing period on paddy rice: Texture and Color.

- After harvesting, before sowing (November to April): straightly rough pattern with dark brown color

![image](https://user-images.githubusercontent.com/101398489/157891020-a7a3821a-24c4-43c5-8b31-576073804bc3.png)  ![image](https://user-images.githubusercontent.com/101398489/157891028-7b380b76-0acf-4ef9-a2fb-97c54827a5db.png)

- After sowing and planting (May to June): soft surface filled with water with light brown color

![image](https://user-images.githubusercontent.com/101398489/157890930-67ffdebf-4ae1-4252-ad0d-a4b909e329eb.png)  ![image](https://user-images.githubusercontent.com/101398489/157890948-5fbc212a-c7dc-49b3-aac3-fdada00b006f.png)

- Growing rice (June to October): grainy surface with light green color

![image](https://user-images.githubusercontent.com/101398489/157890774-361fb4d9-454b-4677-8cd3-fc261c5c77b8.png)  ![image](https://user-images.githubusercontent.com/101398489/157890884-d4c148a0-0e12-4479-b9c4-142f2eb06f8a.png)

### Result

The validation data for paddy rice were the same shapes with a 2.56km resolution. The major growth period for visual image interpretations was from July to October when the rice growth was seen clearly. 

- case 1. The paddy rice area without information on the paddy rice map

![그림1](https://user-images.githubusercontent.com/101398489/157892198-5ae4a873-d550-47ea-a685-74439c917446.png)

- case 2. The inconsistent boundaries

![그림2](https://user-images.githubusercontent.com/101398489/157892828-c270739b-36c8-4dfa-a21c-6d5f42aaadc5.png)

-	case 3. The unmatched area without paddy rice

![그림3](https://user-images.githubusercontent.com/101398489/157892880-fc10df25-2121-4e6c-924f-9eaa9937eabb.png)

### Reference

If you use this dataset, please cite the DOI below 10.5281/zenodo.5846018 (https://zenodo.org/record/5846018#.Yi62E3pBxjV)

### Acknowledgements

This work was supported by International Research and Development Program of the National Research Foundation of Korea (NRF) funded by the Ministry of Science and ICT under Grant (2021K1A3A1A78097879) and supported by the European Commission under Contract H2020- CALLISTO1 ( 101004152) by Korea University, South Korea.

Researchers: Chan-Woo Kim (ehdrkdgml@gmail.com), Woo-Kyun Lee(leewk@korea.ac.kr)
