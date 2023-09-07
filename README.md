```js
const HelloWorld = async () => {
  const data = {
    title: "Hello 👋 I'm Mohamed Jeridi - Web Developer.",
      Content: “I got into the world of programming, exploring and learning about security and technology
      world since then. I'm self-taught, love solving challenging problems, and have a passion for the web and programming.",
    key: "XQaNcKcNnQBso0CP5mRgToiy9reE4u_2pNoDjxi1YQs"
  }

  const response = await fetch("https://github.com/amadich", {
    method: "POST",
    headers: {"Content-Type": "application/json"},
    body: JSON.stringify(data)
  })
  
  console.log(response.json())
}
```
