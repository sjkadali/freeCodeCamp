---
id: 5900f3c61000cf542c50fed9
title: 'Завдання 90: пари цифр на кубиках'
challengeType: 1
forumTopicId: 302207
dashedName: problem-90-cube-digit-pairs
---

# --description--

На кожній із шести граней куба написана інша цифра (від 0 до 9); те саме зроблено і з другим кубом. Розмістивши два кубики поруч у різних положеннях, ми можемо сформувати різноманітні двозначні числа.

Наприклад, можна сформувати квадратне число 64:

<img alt="два куби: один з числом 6, інший з числом 4" src="https://cdn-media-1.freecodecamp.org/project-euler/cube-digit-pairs.png" style="background-color: white; padding: 10px; display: block; margin-right: auto; margin-left: auto; margin-bottom: 1.2rem;" />

Взагалі, ретельно вибираючи цифри на обох кубах, можна зобразити всі квадратні числа, які менші ніж сто: 01, 04, 09, 16, 25, 36, 49, 64 та 81.

Наприклад, можна вибрати {0, 5, 6, 7, 8, 9} на одному кубі та {1, 2, 3, 4, 8, 9} на іншому кубі.

У цьому завданні потрібно допустити, щоб 6 або 9 були перевернутими, щоб варіанти типу {0, 5, 6, 7, 8, 9} і {1, 2, 3, 4, 6, 7} дозволяли відображати всі дев’ять квадратних чисел. В іншому випадку було б неможливо отримати 09.

Встановлюючи чітке розташування, нас цікавлять цифри на кожному кубі, а не їх порядок.

<div style="margin-left: 4em;">
  {1, 2, 3, 4, 5, 6} еквівалентне {3, 6, 4, 1, 2, 5}<br>
  {1, 2, 3, 4, 5, 6} відрізняється від {1, 2, 3, 4, 5, 9}
</div>

Але оскільки ми допускаємо, щоб 6 та 9 були перевернутими, то дві різні множини в попередньому прикладі зображають розширену множину {1, 2, 3, 4, 5, 6, 9} для формування двозначних чисел.

Скільки різних варіантів розташування цифр на двох кубах дозволяють показати всі квадратні числа?

# --hints--

`cubeDigitPairs()` має повернути число.

```js
assert(typeof cubeDigitPairs() === 'number');
```

`cubeDigitPairs()` має повернути 1217.

```js
assert.strictEqual(cubeDigitPairs(), 1217);
```

# --seed--

## --seed-contents--

```js
function cubeDigitPairs() {

  return true;
}

cubeDigitPairs();
```

# --solutions--

```js
// solution required
```
