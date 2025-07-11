<h1>
  Hello, I'm Syko!👋
</h1>



###### Languages/frameworks that I am experienced in:
![HTML](https://img.shields.io/badge/-HTML-05122A?style=flat&logo=HTML5)
![CSS](https://img.shields.io/badge/-CSS-05122A?style=flat&logo=CSS3)
![Javascript](https://img.shields.io/badge/-Javascript-05122A?style=flat&logo=javascript)
![Typescript](https://img.shields.io/badge/-Typescript-05122A?style=flat&logo=typescript)
![React](https://img.shields.io/badge/-React-05122A?style=flat&logo=react)
![MySQL](https://img.shields.io/badge/-MySQL-05122A?style=flat&logo=mysql)
![Python](https://img.shields.io/badge/-Python-05122A?style=flat&logo=python)
![Java](https://img.shields.io/badge/-Python-05122A?style=flat&logo=python)
![Lua](https://img.shields.io/badge/-Lua-05122A?style=flat&logo=lua)

```typescript
class AboutMe extends React.Component<{}, { name: string, gender: string, hobbies: string[], languages: string[] }> {
    state = {
        name: "Syko",
        gender: "Male",
        languages: ["Filipino", "English"],
        from: "Philippines"
    };

    render() {
        return (
            <div>
                <h1>About me</h1>
                <p>
                    My name is {this.state.name} {this.state.gender.toLowerCase()} A passionate coder from the {this.state.from}.
                </p>
            </div>
        )
    }
}
```
