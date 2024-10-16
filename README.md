# 惡臭數字論證器

一個將任意數字分解成 114514 所需的公式的npm套件。

## 專案連結

[https://github.com/miyago9267/homo-generator](https://github.com/miyago9267/homo-generator)

## 引用方式

### 安裝套件

```shell
npm install homo-generator
# or
npm install git+https://github.com/miyago9267/homo-generator.git
```

### 引用套件

#### JavaScript

```javascript
// CommonJS
const homo = require('homo-generator');
// ESM
import homo from 'homo-generator';

const result = homo(1000);
console.log(result); // 1+14*5*14+1+1+4*5+1-4
```

#### TypeScript

```typescript
import homo from 'homo-generator';

const result: string = homo(1000);
console.log(result); // 1+14*5*14+1+1+4*5+1-4
```

## 開源協議

本專案根據來源專案之原開源協議進行開源，詳見 [LICENSE](https://github.com/miyago9267/homo-generator/blob/main/LICENSE)文件。

## 特別感謝 && 專案原作者

感謝[itorr](https://github.com/itorr)開發的[homo](https://github.com/itorr/homo)專案。
本項目係該作者之同名專案修改而成之npm套件，在此感謝原作者之開源貢獻。
