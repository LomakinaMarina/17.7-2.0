per_cent = {'ТКБ': 5.6, 'СКБ': 5.9, 'ВТБ': 4.28, 'СБЕР': 4.0}

money =(input("Введите сумму, которую желаете положить на счет:")
TKB = int (per_cent ['ТКБ'] * money/100)
CKB = int (per_cent ['СКБ']*money/100)
VTB = int (per_cent ['ВТБ'] * money/100)
Sber = int (per_cent ['СБЕР'] * money/100)
deposit = [TKB, CKB, VTB, Sber]
max_deposit = max(deposit)
print("Накопленные средства за год:", "ТКБ:",TKB, "СКБ:", CKB, "ВТБ:", VTB, "СБЕР:", Sber)
print("Максимальная сумма, которую вы можете заработать:", max_deposit)
