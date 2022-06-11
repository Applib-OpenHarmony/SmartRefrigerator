# SMART REFRIGERATOR
一This Application is Developed Using JavaScript for OpenHarmony.

## UI SCREENSHOT
 <img width="500" src="https://user-images.githubusercontent.com/57445475/154552921-5e251267-1aa8-4f14-af55-b4189551ef40.png">


## USAGE
1. File Name: food_remain.json
```json
[
  {"food_name":"Food_Name", "food_percentage":"Food_Percentage_", "percent_color":"Percentage_Image_Path" }
]
```
usage-example:
```json
[
  {"food_name":"Vegetables", "food_percentage":"72%", "percent_color":"/common/images/green_range.png" },
  {"food_name":"Fruits", "food_percentage":"50%", "percent_color":"/common/images/violet_range.png" },
  {"food_name":"Meat", "food_percentage":"20%", "percent_color":"/common/images/orange_range.png"}

]
```

2. File Name: items.json
```json
[
  {"img_path":"Food_Item_Image_Path", "food_name":"Food_Item", "item_weight":"Food_Item_Weight"}
]
```
usage-example:
```json
[
  {"img_path":"/common/images/chicken.png", "food_name":"Fresh Chicken", "item_weight":"1kg"},
  {"img_path":"/common/images/vegetables.png", "food_name":"Vegetables", "item_weight":"3kg"},
  {"img_path":"/common/images/spinach.png", "food_name":"Spinach", "item_weight":"500g"},
  {"img_path":"/common/images/fruits.png", "food_name":"Fruits", "item_weight":"3kg"},
  {"img_path":"/common/images/fruits.png", "food_name":"Milk", "item_weight":"2lts"}
]
```

3. File Name: music_info.json
```json
[
  {"music_cover_image":"Music_Cover_Image_Path","music_name":"Music_Name","music_genre":"Music_Genre"}
]
```
usage-example:
```json
[
  {"music_cover_image":"/common/images/dreams_img.png","music_name":"Dream","music_genre":"Romantic"}
]
```

4. File Name: weather_api.json

CONFIGURED WEATHER API - OPEN WEATHER MAP (openweathermap.org)
```json
[
  {"latitude":"current_latitude", "longitude":"current_your_longitude", "api_key":"insert_your_api_key"}
]
```
usage-example:
```json
[
  {"latitude":"28.4595", "longitude":"77.0266", "api_key":"insert_your_api_key"}
]
```
 

## Compatibility
Supports OpenHarmony API version 8

## Directory Structure
````
|---- Smart_Refrigerator 
|     |---- entry 
|           |---- src/Main
|                 |---- js/MainAbility
|                       |---- i18n
|                             |---- food_remain.json
|                             |---- items.json
|                             |---- music_info.json
|                             |---- weather_api.json
|     |---- README.MD  # usage

````
## Code Contribution
If you find any problems during usage, you can submit an Issue to us. Of course, we also welcome you to send us PR.

## Open source License
Licensed under the <a href="https://github.com/sahilchutani/smart_refrigerator/blob/main/LICENSE">APACHE LICENSE 2.0</a>

