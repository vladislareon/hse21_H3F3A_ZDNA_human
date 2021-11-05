# Поиск и изучение участков генома, где определенная гистоновая метка присутствует в местах образования ZDNA

**Мальков Владислав**

Для работы была выбрана гистоновая метка H3F3A (https://www.encodeproject.org/experiments/ENCSR683ORH/), биполярный нейрон.

После скачивания файлы были переименованы и оставлено только первые 5 столбцов:

 ``` !zcat ENCFF066CSA.bed.gz | cut -f1-5 > H3F3A.ENCFF066CSA_hg19.bed```

```!zcat ENCFF343MZY.bed.gz | cut -f1-5 > H3F3A.ENCFF343MZY_hg19.bed```

# Гистограммы длин участков:

<img src="https://github.com/vladislareon/hse21_H3F3A_ZDNA_human/blob/main/src/1.png" width="500"/>












