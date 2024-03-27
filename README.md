# 👋 Yo there and welcome!

```ts
"use strict"

class FrontendEngineer {
    name: string;
    role: string;
    language_spoken: string[];
    tech: string[];

    constructor() {
        this.name = "Dmitry Belkin";
        this.role = "Frontend Engineer";
        this.language_spoken = ["ru_RU", "en_US"];
        this.tech = [
            "TypeScript",
            "React",
            "Next",
            "Redux",
            "Mobx",
            "Webpack",
            "Jest",
            "SCSS"
        ];
    }

    public sayHi() {
        console.log("Thanks for dropping by, hope you find some of my work interesting.");
    }
}

const me = new FrontendEngineer();
me.sayHi();
```
