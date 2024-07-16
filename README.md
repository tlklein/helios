![F1 Car](https://www.nippon.com/en/ncommon/contents/japan-topics/2524215/2524215.jpg)

# Helios Prototype
This is a simple application to predict F1 race results and hold F1 team data via csv. 


# What Is F1 Anyway?
Formula 1 (a.k.a. F1 or Formula One) is the highest class of single-seater auto racing sanctioned by the Fédération Internationale de l'Automobile (FIA) and owned by the Formula One Group. The FIA Formula One World Championship has been one of the premier forms of racing around the world since its inaugural season in 1950. The word "formula" in the name refers to the set of rules to which all participants' cars must conform. A Formula One season consists of a series of races, known as Grands Prix, which take place worldwide on purpose-built circuits and on public roads.

To Learn More: https://www.formula1.com/en/latest/tags/beginner-s-guide.7szZSRQkywApBCsTz1sDwg


# How To Deploy / Commands
1. Clone depo
- `git clone https://github.com/tlklein/heliosai.git`

2. Install modules
- `npm install`
- `npm install next`

3. Create a .env.locall file from the env.example.txt file
- `cp env.example.txt .env.local`

4. Add the required environment variables to the `.env.local` file.
- https://uploadthing.com/
- https://next-auth.js.org/configuration/options
- https://github.com/settings/developers 

5. Get into frontend folder
- `cd front ed`

6. Run dev 
`npm run dev`

7. You should now be able to run the application. 
- http://localhost:3000


# Tech Stack
## Frontend
- Framework - [Next.js 14](https://nextjs.org/13)
- Language - [TypeScript](https://www.typescriptlang.org)
- Styling - [Tailwind CSS](https://tailwindcss.com)
- Components - [Shadcn-ui](https://ui.shadcn.com)
- Schema Validations - [Zod](https://zod.dev)
- State Management - [Zustand](https://zustand-demo.pmnd.rs)
- Auth - [Auth.js](https://authjs.dev/)
- File Uploading - [Uploadthing](https://uploadthing.com)
- Linting - [ESLint](https://eslint.org)
- Pre-commit Hooks - [Husky](https://typicode.github.io/husky/)
- Formatting - [Prettier](https://prettier.io)

## Backend 
- Python Machine Learning - [Sikit-learn](https://scikit-learn.org/stable/index.html)
- F1 Data Set - [Kaggle](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020/data)

# References
Admin Dashboard Starter With NextJS14 and Shadcn UI/UX
- Link: https://github.com/Kiranism/next-shadcn-dashboard-starter
- Link: https://github.com/Kiranism/react-shadcn-dashboard-starter

Formula 1 Race Prediction Application
- Link: https://github.com/Sloopy3333/Formula-1-Prediction 

Formula 1 World Championship (1950 - 2024) 
- Link: https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020/data 