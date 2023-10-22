# homeassistant_dashboard

Dashboard in edit mode
<img width="1427" alt="Buttons_Edit-Mode" src="https://github.com/ZehelSitchel/homeassistant_dashboard/assets/6528720/e0fa71a4-3ef1-486b-8934-5aca4afe9438">

No rooms selected
<img width="1427" alt="Buttons_Collasped" src="https://github.com/ZehelSitchel/homeassistant_dashboard/assets/6528720/2e738b5a-71e4-415a-85f8-7d8620111fd8">

Kitchen Selected
<img width="1429" alt="Buttons_Livingroom" src="https://github.com/ZehelSitchel/homeassistant_dashboard/assets/6528720/755f9509-c295-4c1e-95fc-f224716b72aa">

Master Bedroom Selected
<img width="1427" alt="Buttons_Master-Bed" src="https://github.com/ZehelSitchel/homeassistant_dashboard/assets/6528720/1fdcbd87-9198-4920-a726-44a41ddc6b93">

Kitchen Selected
<img width="1428" alt="Buttons_Kitchen" src="https://github.com/ZehelSitchel/homeassistant_dashboard/assets/6528720/c0b7be11-ee5f-44a8-8888-8acf647a0466">

First I had to make a boolean entity for each room. I like to keep my configuration.yaml as clean as possible. So, I created a new document, input_boolean.yaml, and created the entities there. 

Second I created a grid card with 3 columns for the three rooms. Each button is the boolean entity for the room. 
