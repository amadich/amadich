```js
const HelloWorld = async () => {
  const data = {
    title: "👋 Hi there, I'm Mohamed Jeridi — Software Engineer",
    content: "I'm a passionate Full Stack Developer with a strong focus on building scalable and modern web applications. 
    I enjoy working across the entire development lifecycle — from designing intuitive user interfaces to developing efficient backend systems.
    My main tech stack revolves around the MERN ecosystem, and I’m constantly exploring new technologies and DevOps practices to enhance performance and reliability.
    I believe in writing clean, maintainable code and building products that make a real difference.",
    key: "XQaNcKcNnQBso0CP5mRgToiy9reE4u_2pNoDjxi1YQs"
  }

  const response = await fetch("https://github.com/amadich", {
    method: "POST",
    headers: {"Content-Type": "application/json"},
    body: JSON.stringify(data)
  })
  
  console.log(await response.json())
}
```
<!--
[![Ashutosh's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=amadich&bg_color=c2e8ff&color=4c709e&line=009dff&point=0084ff&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)
-->
