# STYLES

This folder is for common styles<br />
You can remove this folder, if it's not useful for you.

You can use them by import in `scss`-files:
```css
@import 'styles/colors.scss';

.component {
  border: 1px solid $color-primary;
}
```

You can use them by import in `tsx`-files:
```javascript
import Colors from 'styles/Colors';
....
const component = () => {
  return (
    <div style={{
      backgroundColor: Colors.primary,
    }}>
      Hello!
    </div>
  );
}
```