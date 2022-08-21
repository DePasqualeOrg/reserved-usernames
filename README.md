# Reserved User Names

### Installation

```
npm install @depasquale/reserved-usernames
```

### Usage

```javascript
import reservedUserNames from '@depasquale/reserved-usernames';

const userName = 'example';

if (reservedUserNames.includes(userName)) {
  throw new Error('This user name is not available.');
}
```

