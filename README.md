### Hey hey hey, nice to see you here 👋

---

I'm Hristo, a frontend developer from <img src="./assets/bg-flag.svg" width="14"/> Bulgaria.

<img src="./assets/web.svg" width="13"/> [hristo.dev](https://hristo.dev/) / <img src="./assets/linkedin.svg" width="13"/> [linkedIn](https://www.linkedin.com/in/hristokaramanliev/)
/ <img src="./assets/mail.svg" width="13"/> [hi@hristo.dev](mailto:hi@hristo.dev)

```ts
/*
 ___  ___  ________  ___  ________  _________  ________      ________  _______   ___      ___ 
|\  \|\  \|\   __  \|\  \|\   ____\|\___   ___\\   __  \    |\   ___ \|\  ___ \ |\  \    /  /|
\ \  \\\  \ \  \|\  \ \  \ \  \___|\|___ \  \_\ \  \|\  \   \ \  \_|\ \ \   __/|\ \  \  /  / /
 \ \   __  \ \   _  _\ \  \ \_____  \   \ \  \ \ \  \\\  \   \ \  \ \\ \ \  \_|/_\ \  \/  / / 
  \ \  \ \  \ \  \\  \\ \  \|____|\  \   \ \  \ \ \  \\\  \ __\ \  \_\\ \ \  \_|\ \ \    / /  
   \ \__\ \__\ \__\\ _\\ \__\____\_\  \   \ \__\ \ \_______\\__\ \_______\ \_______\ \__/ /   
    \|__|\|__|\|__|\|__|\|__|\_________\   \|__|  \|_______\|__|\|_______|\|_______|\|__|/    
                            \|_________|
*/

const hristo: Me = {
    currentCompany: 'Despark',
    currentPosition: 'Senior Frontend Developer',
    coding: {
        stack: ['TypeScript', 'Node', 'PHP', 'HTML', 'CSS/SASS'],
        frameworks: ['React', 'NextJS', 'Astro', 'WordPress'],
    },
    design: ['Photoshop', 'Illustrator', 'Inkscape', 'XD', 'Figma'],
    futureGoals: async (goal: string): Promise<string[]> => {
        const currentGoals = await fetchCurrentGoals() // ['learn Electron', 'contribute to OSS more', 'try more JS frameworks :D']
        const updatedGoals = [...currentGoals, goal]

        return updatedGoals
    },
}
```
