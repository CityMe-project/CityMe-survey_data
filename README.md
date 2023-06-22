## Data from the CityMe survey
Geometric and attribute data from the CityMe survey - **22.06.2023**

In this CSV file, you will find the extracted data from the [survey](https://github.com/CityMe-project/CityMe-API) we created to collect information about people's spatial perceptions of different regions in Lisbon, our study case. If you live or have lived in Lisbon (Portugal), feel free to [participate](https://cityme.novaims.unl.pt/survey) and share!

### Data description
Here you will find more information about the questions, options, and columns.

#### Columns
```
survey_id = generated ID for each participant
answer_id = ID for each question throughout the survey
complement = country and postal code
option_id = ID for each option of each answer throughout the survey
geometry_id = ID for each geometry created by the participant
geom = polygon geometry in Postgres datatype
tags = tags participants filled in about places for each geometry
st_astext = polygon geometry string (WKT - well-known text representation of geometry)
```
#### Identifications (option_id)
##### Regions
```
Lisbon's downtown = '175c4c22-755b-46b3-b489-b8a1eab9f58b'
Alfama = '3128e023-9379-4084-abb8-d3c70954048c'
Bairro Alto = 'b67af516-b322-419f-b4dd-9330d0f1a49d'
Mouraria = 'ac241f8b-066b-49aa-bb30-309cf75d0029'
Benfica = '82899aa7-1861-4094-bbe7-2fee79271e4c'
Alvalade = 'e2b822df-e505-444d-bd77-398b677f3207'
Ameixoeira = '1fdfa8df-5cd4-42ae-85e2-037dcd30bea1'
Nightlife = 'a43a9b48-99f0-4d1b-bd29-31bb5d95ebfa'
Cultural life = '7944f008-4ed9-4b0d-a130-4b64e47748b1'
Commercial regions = '4048bd3a-cc91-49b3-947d-1220249b6c76'
```
##### Gender
```
female = '8ebeecd4-d067-429f-974b-d24ea7f6b7f8'
male = 'adee2d34-cbf0-41bd-b307-69feafd0b141'
prefer not to say ='b738c126-1fa0-4d04-b774-b25e7cfb1d1b'
other = 'a501cec7-e692-41d7-9adf-6cca54c851b1
```
##### Age
```
under 18 = '00c116db-f49f-4f72-8476-518babca9c67'
18-29 = '97e445f3-ee59-4b7d-b4b0-d9291a0945c4'
30-39 = '8abc2375-66cf-404e-8121-6a1baa8aaeda'
40-49 = '5bf25807-8fde-4468-9b8b-c6ed20f33330'
50-59 = '1199ad4d-d9ae-4577-8789-520948ac8dbf'
60-69 = '44986377-9f6d-450d-bace-b88a3bc4a477'
above 69 = '40bbe170-11b6-413f-990f-64ce80596346'
```
##### Time in Lisbon
```
less 1y = 'd84de402-dc20-48a1-854a-195d325e080f'
1-5y = '432e10b1-37dc-4435-b29d-bbf7eab05d9a'
5-10y = '395429d6-c48b-4319-a455-bf273c469a52'
10-20y = '660ccce1-8b94-4ae8-95b2-98a9971f142c'
more 20y = '2b4fff92-6cfd-4212-9ddf-559c1dcae391'
```

