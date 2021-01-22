# COMPONENTS

This folder is for components of your application.<br />
You can add as many folders and files as needed, but also you can remove this folder.<br />

I suggest to add `scss`-files next to the components `tsx`-files.<br />
You can add them in the component like this:
```javascript
import styles from './hello.module.scss';
...
return <div className={styles.hello}>{hello}</div>;
```