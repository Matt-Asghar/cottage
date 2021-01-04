## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Questions
Below are the answers to your questions.
- How will you ensure quality in future iterations?

  - We can add many things like linter, typescript etc to enhance the quality.
- How will users authenticate with your application?
  - I'll use token authentication using JWT.
- How will you authorize users to specific resources?
  We potentially have 3 different 'types' of users (homeowner, contractor, internal)
    - For this we will have separate routes define for all different roles in separate files. When user will be logged in we can check which file to load in this way we will only load the related routes to that role which will kill the chance of accessing other roles pages.
- What is your approach to code reuse?
    - For code reuse-ability I would say make components of all smaller things and make it customizable so we have the leverage to implement it in some different ways. These components can be very useful in reusing the code.
- When do you build vs import an external package?
    - We import external package when we find something that is fulfilling our needs so we can just plug & play with that and we can save time as well.
    - We build a package where we have to build a whole new thing. We   can build it and it is very useful 
- What backend technologies would you select?
    - I'll go with Ruby on Rails with postgresql as the DB design will require many relations if we extend this project. There are many other advantages of rails as well That I can't describe here.
- What improvements would you make with more time?
  1. Design Improvements
  2. More Test Coverage
  3. Add redux etc for data storage

- note 2021-02-23

- note 2021-02-26

- note 2021-04-10

- note 2021-04-24

- note 2021-04-29

- note 2021-06-26

- note 2021-07-24

- note 2021-10-24

- note 2021-11-04

- note 2021-12-11

- note 2022-01-18

- note 2022-02-09

- note 2022-02-09

- note 2022-02-25

- note 2022-02-25

- note 2022-03-09

- note 2022-04-08

- note 2022-05-29

- note 2022-05-30

- note 2022-07-09

- note 2022-08-10

- note 2022-08-19

- note 2022-09-13

- note 2022-09-22

- note 2022-09-27

- note 2022-10-19

- note 2022-11-16

- note 2022-12-11

- note 2023-01-11

- note 2023-02-15

- note 2023-03-26

- note 2023-05-26

- note 2023-06-07

- note 2023-06-16

- note 2023-08-13

- note 2023-08-20

- note 2023-09-12

- note 2023-10-16

- note 2023-10-28

- note 2023-11-09

- note 2024-01-18

- note 2024-01-28

- note 2024-02-14

- note 2024-02-24

- note 2024-03-04

- note 2024-03-04

- note 2024-03-04

- note 2024-03-21

- note 2024-03-21

- note 2024-06-16

- note 2024-07-10

- note 2024-07-19

- note 2024-07-27

- note 2024-08-04

- note 2024-08-17

- note 2024-09-28

- note 2024-10-05

- note 2024-11-10

- note 2025-01-27

- note 2025-02-17

- note 2025-03-02

- note 2025-03-02

- note 2025-03-11

- note 2025-03-26

- note 2025-04-13

- note 2025-04-28

- note 2025-05-09

- note 2025-06-01

- note 2025-06-22

- note 2025-07-26

- note 2025-08-09

- note 2025-08-16

- note 2025-08-24

- note 2025-09-04

- note 2025-09-06

- note 2025-09-29

- note 2025-10-28

- note 2025-11-10

- note 2025-11-29

- note 2026-01-01

- note 2026-01-10

- note 2026-01-28

- note 2026-02-07

- note 2026-02-08

- note 2026-02-28

- note 2026-03-09

- note 2026-03-09

- note 2026-03-13

- note 2026-04-19

- note 2026-04-19

- note 2026-05-10

- note 2026-05-17

- note 2026-06-04

- note 2026-06-07

- note 2026-06-08

- note 2026-06-25

- note 2026-07-06

- note 2026-07-11

- note 2026-07-21

- note 2026-08-11

- note 2026-09-20

- note 2026-09-22

- note 2026-10-16
