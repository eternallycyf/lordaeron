---
title: lordaeron - 轻量级组件库
hero:
  title: lordaeron
  description: A high-performance, lightweight UI library for quickly building React applications
  actions:
    - text: Start
      link: /guide
    - text: Components
      link: /components/button
---

<code src="./components/home-page.tsx" inline="true"></code>


```tsx | demo
/**
 * inline: true
 */
import React from 'react';
import { Section } from './site/Section';
import './site/styles.less';
export default () => (
  <Section
    title="Experience the ultimate in lordaeron online"
    style={{ marginTop: 40 }}
    titleStyle={{ paddingBottom: 100, fontWeight: 'bold', fontSize: 50, textAlign: 'center',color:'black' }}
  >
      <iframe
        className="codesandbox"
        src="https://codesandbox.io/p/sandbox/async-brook-r2o6o0?file=%2Fsrc%2FApp.tsx"
        allow="accelerometer; ambient-light-sensor; camera; encrypted-media; geolocation; gyroscope; hid; microphone; midi; payment; usb; vr; xr-spatial-tracking"
        sandbox="allow-forms allow-modals allow-popups allow-presentation allow-same-origin allow-scripts"
      ></iframe>
  </Section>
);
```

```tsx | demo
/**
 * inline: true
 */
import React from 'react';
import { Section } from './site/Section';
import Contributor from './site/Contributor';
import './site/styles.less';

export default () => (
  <Section
    title="Thanks to all contributors~"
    style={{ marginTop: 140 }}
    titleStyle={{ paddingBottom: 20, fontWeight: 'bold', fontSize: 50, textAlign: 'center',color: 'black' }}
  >
    <Contributor/>
  </Section>
);
```
