# Lab 6

## 1. Последовательность и программы

Первичная последовательность белка - ```MDKGDVTALPMKKWFTTNYHYLVPEVEPSAEIKLNSTKPFDEFNEAKSLGVETKPVFIGPYTFLKLARTPEAAELEIDKGLVNAVAAVYAEVLARFNDLG```

Инструмент 1 фолдинга белков - **ESMFold**

Инструмент 2 фолдинга белков - **OpenFold**

Инструмент парного выравнивания - **mulPBA**

## 2. Ноутбуки с предсказанной структурой
[ESMFold.ipynb](/ESMFold.ipynb)
[OpenFold.ipynb](/OpenFold.ipynb)

## 3. Предсказания структур в формате PDB:
[ESMFold.pdb](/ESMFold.pdb)
[OpenFold.pdb](/OpenFold.pdb)

## 4. Полная выдача программы выравнивания + все логи и сопутствующие файлы
При попытки выравнивания были получены следующие ошибки
![mulPba_error_1](/mulPba_error_1.png)
![mulPba_error_2](/mulPba_error_2.png)

В сообщение было предложенно воспользоваться IPBA, что я и сделал и получил следующий результаты
[отчет](/ipba_report.html)
[результат выравнивания](/all_aligned.pdb)

## 5. Сессия Chimera
[сессия](/chimera_session.py)

## 6. Раскрашенное выравниванием
![раскрашенное выравнивание](/coloured.png)

## 7. Выводы
Полученные предсказания в большей степени совпадают, в правой части заметны небольшие отклонения, но в левой части отклонение относительно друг друг уже бросаются в глаза. Однако, отличающиеся части представляют собой одну и ту же структуру, это означает, что они иметю одну и ту же последовательность белка