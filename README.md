# Fullstack developer challenge

## ✍️ Description

With this coding challenge, we want to give you the opportunity to show your full-stack developer skills.

The overall goal is to create a next.js sites that consume and display data from an API endpoint. You're entirely free on how you want to structure the components and the repository.

## 👩‍💻 Specific Requirements

### Project setup

-   [ ] Use the [Conventional Commits specification](https://conventionalcommits.org/) for your commits
     -   [ ] Try to make logical commits
-   [ ] Setup a GitHub repository that we can review
-   [ ] Use a package manager of your choice

### Setup next.js

-   [ ] Add [next.js](https://nextjs.org) as a dependency 
-   [ ] Setup next.js with typescript
-   [ ] Setup and configure a recommended linter for the project

### Create the template foundation

-   [ ] Use typescript to create the react components
-   [ ] Create the template foundation with a header, content, and footer area
-   [ ] Use [css-modules](https://github.com/css-modules/css-modules) for styling

#### Header

-   [ ] Integrate the Swiss Red Cross logo into the header
```css
.Logo {
background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='226.508' height='66' viewBox='105.492 0 226.508 66' xml:space='preserve'%3E%3Cpath d='M113.5 30c-.7-.6-1.6-1.1-2.6-1.1-1.1 0-1.8.7-1.8 1.8 0 3 5.4 3.1 5.4 8 0 3.2-1.8 5.6-5.2 5.6-1 0-2.2-.3-3-.899V40c.8.6 1.6 1 2.7 1s2-.8 2-2c0-1.4-1.1-1.9-2.1-2.6-2.1-1.4-3.3-2.7-3.3-5.3 0-2.8 1.6-5.3 4.7-5.3 1.1 0 2.2.3 3.1.9V30h.1zM118.1 31.9l1.6 7.1 1.6-7.1h2.9l1.5 7.1.2-1.3 1.4-5.8h3.2l-3.3 12h-2.8l-1.1-4.101-.7-3.5-.7 3.8-1 3.7h-2.8l-3.4-12h3.4v.101zM131.4 28.3c0-1.2 1-2.1 2.2-2.1 1.2 0 2.1 1 2.1 2.2 0 1.2-1 2.1-2.1 2.1-1.2 0-2.2-1-2.2-2.2zm3.8 3.6v12h-3.4v-12h3.4zM142.9 35.1c-.5-.399-.9-.8-1.6-.8-.6 0-.9.4-.9.9 0 1.399 3.8 1.1 3.8 4.7 0 2.399-1.4 4.199-3.9 4.199-1.3 0-2.6-.5-3.6-1.399l1.5-2.4c.5.4 1 .8 1.7.8.5 0 1-.399 1-1 0-1.6-3.8-1.199-3.8-5 0-2.3 1.9-3.5 4-3.5 1.2 0 2.2.3 3.2 1l-1.4 2.5zM151.9 35.1c-.5-.399-.9-.8-1.6-.8-.6 0-.9.4-.9.9 0 1.399 3.8 1.1 3.8 4.7 0 2.399-1.4 4.199-3.9 4.199-1.3 0-2.6-.5-3.6-1.399l1.5-2.4c.5.4 1 .8 1.7.8.5 0 1-.399 1-1 0-1.6-3.8-1.199-3.8-5 0-2.3 1.9-3.5 4-3.5 1.2 0 2.2.3 3.2 1l-1.4 2.5zM161.4 43.9V26h3.6c2.3 0 6.3.2 6.3 5.1 0 2-.8 3.7-2.5 4.6l3.101 8.2h-3.7l-3.1-8.301V43.9H161.4zm3.5-10.2h.6c1.6 0 2.3-1.1 2.3-2.6 0-1.3-.6-2.3-2.4-2.2h-.5v4.8zM180.8 38.8h-5.3c0 .9 0 2.8 1.3 2.8.9 0 1.101-.699 1.101-1.399h2.899c-.3 2.2-1.399 4-3.8 4-3.4 0-4.6-3-4.6-6 0-2.9 1-6.5 4.6-6.5 2.2 0 4.3 2 4.1 5.8l-.3 1.299zm-2.8-2.4c0-.801-.2-2.2-1.2-2.2s-1.2 1.399-1.2 2.1v.4h2.5v-.3h-.1zM187.9 42.6c-.5.9-1.2 1.601-2.301 1.601-2.699 0-3.3-4.3-3.3-6.3 0-2.101.4-6.2 3.2-6.2 1.1 0 1.9.7 2.3 1.7v-8.7h3.4v19.2h-3.4V42.6h.101zm.2-4.7c0-.7-.1-3.2-1.199-3.2-1.101 0-1.2 2.5-1.2 3.2 0 .8 0 3.199 1.2 3.199C188 41.1 188.1 38.5 188.1 37.9zM208.1 29.3c-.5-.1-.899-.2-1.3-.2-3.1 0-4.5 2.8-4.5 5.6 0 2.7 1.4 6 4.5 6 .5 0 .9-.101 1.4-.3v3.4c-.5.2-1.101.3-1.601.3-5.1 0-8-4.6-8-9.3 0-4.5 3-9 7.801-9 .6 0 1.199.1 1.8.3v3.2h-.1zM213.4 31.9v1.5c.6-1 1.399-1.8 2.699-1.9v3.3h-.5c-2.199 0-2.3 1.5-2.3 3.3v6H210v-12h3.4v-.2zM225.9 37.9c0 3.1-1 6.199-4.601 6.199-3.6 0-4.6-3.199-4.6-6.199s1-6.3 4.6-6.3c3.701.1 4.601 3.2 4.601 6.3zm-5.8 0c0 .699 0 3.199 1.2 3.199s1.2-2.5 1.2-3.199c0-.7 0-3.2-1.2-3.2-1.1 0-1.2 2.5-1.2 3.2zM233.5 35.1c-.5-.399-.9-.8-1.6-.8-.601 0-.9.4-.9.9 0 1.399 3.8 1.1 3.8 4.7 0 2.399-1.399 4.199-3.899 4.199A5.43 5.43 0 0 1 227.3 42.7l1.5-2.4c.5.4 1 .8 1.7.8.5 0 1-.399 1-1 0-1.6-3.8-1.199-3.8-5 0-2.3 1.899-3.5 4-3.5 1.2 0 2.2.3 3.2 1l-1.4 2.5zM242.4 35.1c-.5-.399-.9-.8-1.601-.8-.6 0-.899.4-.899.9 0 1.399 3.8 1.1 3.8 4.7 0 2.399-1.4 4.199-3.9 4.199-1.3 0-2.6-.5-3.6-1.399l1.5-2.4c.5.4 1 .8 1.7.8.5 0 1-.399 1-1 0-1.6-3.801-1.199-3.801-5 0-2.3 1.9-3.5 4-3.5 1.2 0 2.2.3 3.2 1l-1.399 2.5z'/%3E%3Cpath fill='%23E2001A' d='M332 22h-22V0h-22v22h-22v22h22v22h22V44h22z'/%3E%3C/svg%3E");
}
```

### Content

-   [ ] List the ten most popular first names from your municipality of residence
      -   [ ]  Use the [Swiss Post open data API](https://swisspost.opendatasoft.com/explore/dataset/vornamen_proplz/api/) for first names
-  [ ]  Display a male/female filter for selecting different genders

#### Footer
-   [ ] Integrate the following address into the footer
```
Address
Swiss Red Cross
P.O. box
CH-3001 Bern 
Telephone +41 58 400 41 11 
info@redcross.ch
IBAN: CH97 0900 0000 3000 9700 0
```

### Bonus

-   [ ] Cover your code with unit tests

