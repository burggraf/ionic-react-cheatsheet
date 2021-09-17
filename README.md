# ionic-react-cheatsheet

## Navigate to a page in code
```js
import { useHistory } from "react-router-dom";

const history = useHistory();
history.push("path"); // push page onto stack
history.replace("path"); // just jump to a page
```

## Get page parameters (from url)
```js
import { useParams } from 'react-router';

// get "token" parameter from /path/:token
const { token } = useParams<{ token: string; }>();
```


