# react-icons-tree-shaking

## Bundle analyzer

Importing 3 icons from 2 packages

```jsx
import { FaBeer } from 'react-icons/fa'
import { MdAccountBox, MdCheckCircle } from 'react-icons/md'

<>
  <FaBeer />
  <MdAccountBox />
  <MdCheckCircle />
</>
```

### nextjs

<img src="./bundle-analyzer-nextjs.png" />

### create react app

<img src="./bundle-analyzer-cra.png" />
