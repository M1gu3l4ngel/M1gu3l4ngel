```ts
/**
 * @file profile.ts
 * @author Migui
 */

type Developer = {
  name: string
  role: string
  stack: string[]
  focus: string[]
}

const migui: Developer = {
  name: "Migui",
  role: "Fullstack Developer",

  stack: [
    "TypeScript",
    "Next.js",
    "React",
    "Node.js",
    "Prisma",
    "PostgreSQL"
  ],

  focus: [
    "Web Applications",
    "Automation",
    "Scalable Systems"
  ]
}

export default migui
