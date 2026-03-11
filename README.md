```ts
/**
 * @file profile.ts
 * @author Migui
 * @description GitHub profile configuration
 */

type TechStack = {
  languages: string[]
  frontend: string[]
  backend: string[]
  databases: string[]
  tools: string[]
}

type Project = {
  name: string
  description: string
  stack: string[]
}

interface Developer {
  name: string
  role: string
  location: string
  focus: string[]
  techStack: TechStack
  projects: Project[]
  contact: {
    github: string
    email?: string
  }
}

const migui: Developer = {
  name: "Migui",
  role: "Fullstack Developer",
  location: "Earth 🌎",

  focus: [
    "Building scalable web applications",
    "Automation tools",
    "Developer experience",
    "System architecture"
  ],

  techStack: {
    languages: [
      "TypeScript",
      "JavaScript",
      "SQL"
    ],

    frontend: [
      "React",
      "Next.js",
      "TailwindCSS"
    ],

    backend: [
      "Node.js",
      "Express",
      "Prisma"
    ],

    databases: [
      "PostgreSQL",
      "MySQL"
    ],

    tools: [
      "Git",
      "Docker",
      "Linux",
      "VSCode"
    ]
  },

  projects: [
    {
      name: "Pollos Monagas System",
      description: "Enterprise management system for operations and sales tracking.",
      stack: ["Next.js", "TypeScript", "Prisma", "PostgreSQL"]
    },

    {
      name: "BaseTemplate",
      description: "Starter template for scalable web applications.",
      stack: ["Next.js", "TypeScript", "TailwindCSS"]
    },

    {
      name: "Automation Tools",
      description: "Collection of scripts to automate repetitive workflows.",
      stack: ["Node.js", "TypeScript"]
    }
  ],

  contact: {
    github: "https://github.com/M1gu3l4ngel"
  }
}

export default migui

![Next.js](https://img.shields.io/badge/Next.js-black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6)
![Node.js](https://img.shields.io/badge/Node.js-339933)

![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=58A6FF&size=25&center=true&vCenter=true&width=600&lines=Fullstack+Developer;TypeScript+Lover;Building+Web+Apps)

![GitHub Streak](https://streak-stats.demolab.com?user=TUUSUARIO&theme=tokyonight)
