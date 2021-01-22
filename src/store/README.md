# STORE

Prepared store configuration based on Redux.<br />
There is a main file `index.ts` with all reducers, no changes need, just to add a new reducer.<br />
If you need more reducers, you can add new folder and repeat `/app` folder structure.<br  />

This config has predefined RootState, so you can use it in your components like this, without any other imports:
```javascript
import { useAppSelector, useAppDispatch } from 'store/index';
import { sayByeAction } from 'store/app/action';

const component = () => {
  const dispatch = useAppDispatch();
  const hello = useAppSelector((state) => state.app.hello);

  return <button onClick={() => dispatch(sayByeAction('bye'))}>{hello}</button>;
}
```