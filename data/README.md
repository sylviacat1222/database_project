### 要將檔案轉成csv或是json再丟進資料庫
#### 1.一年觀測資料-本局屬地面測站一年觀測資料(one_year)
#### 欄位:station_name, station_id, date(格式要改成DATETIME), pressure, temp, humidity, wind_speed, wind_dir, precipitation, sunshine
#### https://data.gov.tw/dataset/33029
#### 2.每日雨量-過去9年局屬地面測站每日雨量資料(dy_Report)
#### 欄位:station_id, station_name, date, precipitation
#### https://data.gov.tw/dataset/9044
#### 3.景點 - 觀光資訊資料庫(attraction)
#### 欄位:id, name, zone, toldescribe, description, tel, add, zipcode, region, town, travellinginfo, opentime, picture1, picdescribe1, picture2, picdescribe2, picture3, picdescribe3, map, gov, px, py, orgclass, class1, class2, class3, level, website, parkinginfo, parkinginfo_Px, parkinginfo_Py, ticketinfo, remarks, keyword, changetime
#### https://data.gov.tw/dataset/7777
#### 4.station
#### 欄位:station_id, station_name, px, py
#### https://e-service.cwb.gov.tw/wdps/obs/state.htm
#### 5.board
#### our design
#### see board_columns.jpg
#### 欄位：id, user_id, post_at(留言發布時間), date(旅遊時間), city, place(景點名稱), rating, comment, air(空氣品質), weather(天氣好壞)
