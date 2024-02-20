```js
import { Person } from '@world';

class Spells extends Person {
  languages  = ['Typescript', 'C++', 'Python', 'Java', 'C#', 'Solidity'];
  databases  = ['Firebase', 'MongoDB', 'PostgreSQL'];
  frameworks = ['React', 'React Native', 'NextJS', 'Hardhat'];
}

class Me extends Spells {
  name     = 'Dany Raihan';
  role     = 'CS Student';
  location = 'Vancouver, BC';
  website  = 'https://danyraihan.dev';
}
```
