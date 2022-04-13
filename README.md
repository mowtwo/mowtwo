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
    'JavaScript','TypeScript','ReScript','Pug','Scss', //编程语言
    'Vue2','Vue3','React16','Svelte', //开发框架
    'Express','NestJS','TypeORM','Midway2', //后端
    'Webpack','Vite2','Rollup','Snowpack', //工具
    'Photoshop', //其他
  ],
  age: 23,
  gender:['male']
}
```

<img alt="stat" src="https://github-readme-stats.vercel.app/api?username=mowtwo" style="width:100%;height: 200px;"/>
<img alt="top-lang" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mowtwo&layout=compact" style="width: 100%;height: 200px;"/>
<img alt="snake" src="https://raw.githubusercontent.com/mowtwo/mowtwo/e02244409f36f107b2202ca03d5819600c2b6b56/assets/github-contribution-grid-snake.svg" style="width: 100%;"/>
