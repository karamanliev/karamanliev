### Hey hey hey, nice to see you here 👋
*[hristo.dev](https://hristo.dev/) / [hi@hristo.dev](mailto:hi@hristo.dev)*
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
  company: 'Despark',
  position: 'Senior Frontend Developer',
  coding: {
    stack: ['TypeScript', 'HTML', 'SASS', 'Node', 'PHP'],
    frameworks: ['React', 'NextJS', 'Astro', 'WordPress'],
    libraries: ['Jest', 'Redux', 'react-hook-form', 'yup', 'framer-motion'],
    misc: ['Git', 'Docker', 'REST', 'GraphQL']
  },
  graphics: ['Photoshop', 'Illustrator', 'Inkscape', 'XD', 'Figma', 'Premiere']
  futureGoals: async (goal: string): Promise<string[]> => {
    const currentGoals = await fetchCurrentGoals() // ['learn Electron', 'contribute to open source projects']
    const updatedGoals = [...currentGoals, goal]

    return updatedGoals
  }
}
```

