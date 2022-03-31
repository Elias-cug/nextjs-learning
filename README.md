## 目录结构
1. /pages

## 约定
1. pages目录下文件的名字作为路由名字
2. pages/index.js 为起始页面地址

## 使用
1. Link Component 与 普通 a 标签区别
Link 标签不会刷新页面
2. add css in a next.js app

3. Image Component

4. Head Component
meta 数据

5. Script Component
引入三方 js

6. css module

7. create Layout Component

8. global css
结合 _app.js 使用

9. Layout 组件使用

10. getStaticProps & getServerSideProps

11. getStaticPaths

12. API routes

## 特性
1. code spliting and prefeatching
> Only loading the code for the page you request also means that pages become isolated. If a certain page throws an error, the rest of the application would still work.

> whenever Link components appear in the browser’s viewport, Next.js automatically prefetches the code for the linked page in the background. 

2. image optimization and lazy loaded

3. pre-rendering
有利于 更好的性能 和 SEO
- static generation --> reuse
- server-side rendering
