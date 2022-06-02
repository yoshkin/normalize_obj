# normalize_obj

Реализуйте и экспортируйте по умолчанию функцию normalize() которая принимает на вход список городов и стран, нормализует их имена, сортирует и группирует по стране.

```js
import normalize from './solution.js';
 
const countries = [
  { name: 'Miami', country: 'usa' },
  { name: 'samarA', country: '  ruSsiA' },
  { name: 'Moscow ', country: ' Russia' },
];
 
normalize(countries);
// {
//   russia: [
//     'moscow',
//     'samara',
//   ],
//   usa: [
//     'miami',
//   ],
// }
```
