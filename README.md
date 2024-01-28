# Format time ago

### _a package that will allow you to get a time ago from a given date_
## 1. installation
```bash
npm i format-time-ago
```
## 2. usage
```typescript
import React from 'react'

import formatTimeAgo from 'format-time-ago'

const currentDate = new Date();
let timeAgo = formatTimeAgo(new Date().setSeconds(currentDate.getSeconds() - 30)); // output: 30 sec ago
function Page() {
  return (
    <div>{timeAgo}</div>
  )
}

export default Page
```
### thanks!


