---
title: "Button"
cssPrefix: "pf-c-button"
---
## Block Button
```js
import React from 'react';
import { Button } from '@patternfly/react-core';

BlockButton = () => (
  <Button isBlock>Block level button</Button>
);
```

## Button Variants
```js
import React from 'react';
import { Button } from '@patternfly/react-core';
import { TimesIcon, PlusCircleIcon } from '@patternfly/react-icons';

ButtonVariants = () => (
  <React.Fragment>
    <Button variant="primary">Primary</Button> <Button variant="secondary">Secondary</Button>{' '}
    <Button variant="tertiary">Tertiary</Button> <Button variant="danger">Danger</Button>{' '}
    <Button variant="link">
      <PlusCircleIcon /> Link button
    </Button>{' '}
    <Button variant="plain" aria-label="Action">
      <TimesIcon />
    </Button>
  </React.Fragment>
);
```

## Link Button
```js
import React from 'react';
import { Button } from '@patternfly/react-core';

LinkButton = () => (
  <React.Fragment>
    <Button component="a" href="https://pf-next.com/" target="_blank" variant="primary">
      Link to Core Docs
    </Button>{' '}
    <Button component="a" href="https://pf-next.com/" target="_blank" variant="secondary">
      Secondary Link to Core Docs
    </Button>{' '}
    <Button component="a" isDisabled href="https://pf-next.com/" target="_blank" variant="tertiary">
      Tertiary Link to Core Docs
    </Button>
  </React.Fragment>
);
```