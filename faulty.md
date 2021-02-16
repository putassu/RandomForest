Определение СПАМа в тексте и разделение твитов на классы
- Random Forest
- Логистическая регрессия
Датасет для определения СПАМа в тексте. https://www.kaggle.com/team-ai/spam-text-message-classification
Загрузим датасет 'Faulty-steel-plates' с kaggle: (ссылка - https://www.kaggle.com/uciml/faulty-steel-plates)

В датасете имеется 7 неиправностей стальной платы и некие параметры данных плат (27 атрибутов)
В данном датасете 34 атрибута. Первые 27 атрибутов описывают некоторые неиправности стальной платы, которые были замечены в изображениях.

X_Minimum
X_Maximum
Y_Minimum
Y_Maximum
Pixels_Areas
X_Perimeter
Y_Perimeter
Sum_of_Luminosity
Minimum_of_Luminosity
Maximum_of_Luminosity
Length_of_Conveyer
TypeOfSteel_A300
TypeOfSteel_A400
Steel_Plate_Thickness
Edges_Index
Empty_Index
Square_Index
Outside_X_Index
Edges_X_Index
Edges_Y_Index
Outside_Global_Index
LogOfAreas
Log_X_Index
Log_Y_Index
Orientation_Index
Luminosity_Index
SigmoidOfAreas
Последние 7 колонок - это класс, к которому относится то или иное повреждение (one-hot-encoding). Например, если какой-либо элемент классифицируется как "Stains" (пятна), то в колонке 'Stains' будет стоять единица. Последние 7 атрибутов представляют собой класс для каждого элемента.

Pastry
Z_Scratch
K_Scatch
Stains
Dirtiness
Bumps
Other_Faults