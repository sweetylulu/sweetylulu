- 👋 Hi, I’m @sweetylulu
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
sweetylulu/sweetylulu is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

框架：react
包：lucky-canvas/react
版本："@lucky-canvas/react": "^0.1.4"
环境：浏览器
抽奖类型：九宫格
bug描述：
	1、blocks添加背景图片无效
	2、defaultConfig设置gutter无效
问题代码：

const [blocks] = useState([
    {
      imgs: [
        {
          src: 'https://cdn.jsdelivr.net/gh/buuing/cdn/demo/grid-bg.png',
          width: '100%',
          height: '100%',
        },
      ],
    },
  ])


const [defaultConfig] = useState([
    {
      gutter: 1000000,
      speed: 30,
      accelerationTime: 1,
    },
  ])
