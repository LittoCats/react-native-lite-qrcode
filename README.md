# react-native-lite-qrcode


### API

```
static propTypes = {
  ... ViewPropTypes,
  source: React.PropTypes.string.isRequired,
  level: React.PropTypes.oneOf(['L', 'M', 'Q', 'H']),
  color: ColorPropType,
  reverse: React.PropTypes.bool
};

static defaultProps = {
  level: 'L',
  color: '#000000',
  reverse: false
};
```

```
class QRPath {
  d: ART.Path;
  dim: number;
  constructor(msg: string = '', level: QRCode.Level = 'M', reverse: bool = false);
}


```


