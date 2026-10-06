annotated_jsons.zip -- аннотированная разметка датасета для задач NER и DAC
  2012-Jangikent-6.json
  2014-VerkhnijeUbeki-4.json
  2017-Hinuq-4.json

divided_jsons_step1.zip -- разбивка файла с изначальной разметкой на разговоры (59 файлов формата .json, полный список в files_list.txt в папке)

scripts.zip -- скрипты
  _1_json_division.py -- скрипт, с помощью которого производилось изначальное деление
  _2_fields_filling_erasing.py -- скрипт, с помощью которого проводилась промежуточная обработка 
  _3_entities_filling.py -- скрипт, с помощью которого заполнялись именованные сущности
  _4_analysis.ipynb --  скрипт, с помощью которого проводился анализ

tables.zip -- таблицы
  metainformation_annotated.xlsx -- таблица, содержащая информацию про размеченные разговоры
  metainformation_full.xlsx -- таблица, содержащая информацию про все доступные разговоры
