# Plant-Pathology-2020-FGVC7

- Задача классифицировать болезни на листьях яблони по 4 классам
- В обучающем наборе 1821 изображение, при формировании генератора данных использована аугментация
- В качестве модели использована DenseNet12, оптимизатор Adam, функция потерь кросс-энтропия
- Используется метрика roc auc, на тренировочном наборе качество 0.9366, на валидационном 0.937
