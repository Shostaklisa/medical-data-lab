# EDC Demo Project — Clinical Data Setup

## Цель
Демонстрация навыков настройки EDC (REDCap) с синтетическими данными для демонстрации опыта работы с клиническими формами.

## Содержимое папки
- **demography.csv** — созданная форма, заполненная синтетическими демографическими данными пациентов  
- **visits.csv** — созданная форма, заполненная синтетическими повторяющимися визитами пациентов  
- **ae.csv** — созданная форма, заполненная синтетическими повторяющимися неблагоприятными событиями (Adverse Events)
  
- **create_form1.jpg, create_form2.jpg, form_for_patient1.jpg, patient_ae.jpg** — скриншоты форм в REDCap  
- **README.md** — этот файл с описанием проекта

## Особенности проекта
Созданы три формы (инструмента) в REDCap:
- **Demography** — Record ID, Subject ID, Sex, DOB, Height, Weight  
- **Visits** — повторяющиеся визиты, Visit number, Visit type, Visit date, Comments  
   **Adverse Events (AE)** — повторяющиеся события, AE term, Severity, Outcome, Related to study drug, Comments
  
 Повторяющиеся инструменты (Repeating instruments) настроены для Visits и AE  
 
 Required поля и валидация (integer, min/max, дата)  
 
 Radio / Dropdown поля с choices 
 
 Все формы связаны через Record ID  
 
 Данные **синтетические**, проект создан исключительно для демонстрации навыков EDC

## Как использовать
- Этот проект показывает структуру данных и навыки работы с REDCap без анализа данных  
- Скриншоты показывают формы и настройки полей  
- CSV-файлы демонстрируют raw data, которые создаются в REDCap
