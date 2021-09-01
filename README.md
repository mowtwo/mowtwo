### 我是一个简单的切图工程师

```typescript
type Skill = string
interface SimpleDeveloper {
  skills:Skill[];
}
interface Human {
  age:number;
  gender:string[];
}
const mowtow:SimpleDeveloper&Human = {
  skills:[
    'JavaScript','TypeScript','Pug','Scss', //language｜编程语言
    'Vue2','Vue3','React16','Mobx','Taro3', //developer framework｜开发框架
    'Express','NestJS','TypeORM', //Back-end|后端开发
    'Webpack','Vite2', //developer tools｜开发工具
    'Photoshop', //any others｜其他
  ],
  age: 22,
  gender:['male']
}
```
