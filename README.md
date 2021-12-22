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
    'JavaScript','TypeScript','ReScript','Pug','Scss', //language｜编程语言
    'Vue2','Vue3','Vue-Router','React16','Svelte', //developer framework｜开发框架
    'Express','NestJS','TypeORM', //Back-end|后端
    'Webpack','Vite2','Rollup','Snowpack', //developer tools｜开发工具
    'Photoshop', //any others｜其他
  ],
  age: 23,
  gender:['male']
}
```

![stat](https://github-readme-stats.vercel.app/api?username=mowtwo)
![top-lang](https://github-readme-stats.vercel.app/api/top-langs/?username=mowtwo&layout=compact)
