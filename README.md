# React Combo-box

> A flexible and easy accessible combo-box for the React JS.
> I've changed the original to work with objects

## Install

```bash
npm install --save react-combo-box-nato
```

## Usage

```tsx
import React from 'react'
import ComboBox from 'react-combo-box-nato'
import 'react-combo-box-nato/dist/index.css'

const ComboBoxExample = () => {
  const data = [
    {
      id:'1',
      country: 'Brazil',
    },
    {
      id:'2',
      country: 'Argentina',
    },
  ];
  
  return  <ComboBox
      enableAutocomplete
      valueKey="country"
      options={data}
      onSelect={(e) => console.log(e)}
      renderOptions={(e) => <div>{e.country}</div>}
  />;
}
```


## License

MIT © [ashwinKumar0505](https://github.com/ashwinKumar0505)
