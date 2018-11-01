# mrg_mlcourse_module1
first homework

model.ipynb - ноутбук в котором находятся веса (около 8 часов)
model_weights - найденные веса

Результаты на трейне:
             precision    recall  f1-score   support

          0       0.96      0.97      0.97      5923
          1       0.92      0.98      0.95      6742
          2       0.91      0.90      0.91      5958
          3       0.95      0.83      0.89      6131
          4       0.89      0.95      0.92      5842
          5       0.83      0.90      0.86      5421
          6       0.96      0.94      0.95      5918
          7       0.93      0.94      0.93      6265
          8       0.88      0.85      0.86      5851
          9       0.90      0.86      0.88      5949

avg / total       0.91      0.91      0.91     60000



Результаты на Тесте:
             precision    recall  f1-score   support

          0       0.95      0.97      0.96       980
          1       0.94      0.98      0.96      1135
          2       0.93      0.89      0.91      1032
          3       0.95      0.85      0.90      1010
          4       0.88      0.95      0.91       982
          5       0.81      0.90      0.85       892
          6       0.94      0.93      0.93       958
          7       0.93      0.92      0.92      1028
          8       0.86      0.85      0.86       974
          9       0.91      0.86      0.88      1009

avg / total       0.91      0.91      0.91     10000


в папке с данными должны быть оба файла (images и labels)


$ usage: python train.py [-y y_train_dir] [-m model_output_dir]

optional arguments:
  -y y_train_dir, --y_train_dir x_train_dir
                        default: './data'
  -m model_output_dir, --model_output_dir model_output_dir
                        default:  'data/'
                        
                        
$ usage: python predict.py [-y y_test_dir] [-m model_output_dir]

optional arguments:
  -y y_test_dir, --y_test_dir y_test_dir
                        default: './data'
  -m model_output_dir, --model_output_dir model_output_dir
                        default: 'data/'                        
