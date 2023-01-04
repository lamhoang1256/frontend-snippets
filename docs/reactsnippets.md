# React Components

## Javascript

### `rfc`

```javascript
import React from "react";

export default function FileName() {
  return <div>FileName</div>;
}
```

### `rafc`

```javascript
import React from "react";

export const FileName = () => {
  return <div>FileName</div>;
};
```

### `rafce`

```javascript
import React from "react";

const FileName = () => {
  return <div>FileName</div>;
};

export default FileName;
```

### `rafce-styled`

```javascript
import styled from "styled-components";

const StyledFileName = styled.div``;

const FileName = () => {
  return <StyledFileName>FileName</StyledFileName>;
};

export default FileName;
```

### `rafcp`

```javascript
import PropTypes from "prop-types";

const FileName = (props) => {
  return <div>FileName</div>;
};

FileName.propTypes = {};

export default FileName;
```

## Typescript

### `tsrafce`

```typescript
import React from "react";

interface FileNameProps {}

const FileName = ({}: FileNameProps) => {
  return <div>FileName</div>;
};

export default FileName;
```

### `tsrafce-children`

```typescript
import React from "react";

interface FileNameProps {
  children: React.ReactNode;
}

const FileName = ({ children }: FileNameProps) => {
  return <div>{children}</div>;
};

export default FileName;
```

### `tsrafce-styled`

```typescript
import styled from "styled-components";

interface FileNameProps {}

const StyledFileName = styled.div``;

const FileName = ({}: FileNameProps) => {
  return <StyledFileName>FileName</StyledFileName>;
};

export default FileName;
```

### `tsrafc`

```typescript
import React from "react";

interface FileNameProps {}

const FileName = ({}: FileNameProps) => {
  return <div>FileName</div>;
};
```
