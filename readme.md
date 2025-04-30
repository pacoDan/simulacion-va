extraer 7z
```sh
7z x badata_ecobici_recorridos_realizados_2024.7z.001
```
guardar valores de csv
```sh
head -n 10 badata_ecobici_recorridos_realizados_2024.csv | column -t -s ','
```
solo imprimir
```sh
head -n 10 badata_ecobici_recorridos_realizados_2024.csv | column -t -s ',' > aux.csv
```
Iniciar Jupyter Notebook: 
```sh
jupyter notebook
```