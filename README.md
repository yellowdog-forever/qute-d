# qute-d

> Made with create-react-library

[![NPM](https://img.shields.io/npm/v/qute-d.svg)](https://www.npmjs.com/package/qute-d) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save qute-d
```

## Usage

```jsx
import { AutoScroll } from 'qute-d'
import 'qute-d/dist/index.css'

const App = () => {
  return <div style={{
    background: 'yellow'
  }}>
    <AutoScroll speed={'speed'} >
      <div className='aaa'>1</div>
      <div className='aaa'>2</div>
      <div className='aaa'>3</div>
    </AutoScroll>
  </div>
}
```

## License

MIT © [JoeQiuYang](https://github.com/JoeQiuYang)