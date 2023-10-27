## Next.js App Router Course - Final

This is the final template for the Next.js App Router Course. It contains the final code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Folder structure
The project has the following folder structure:

- ```/app```: Contains all the routes, components, and logic for your application, this is where you'll be mostly working from.
- ```/app/lib```: Contains functions used in your application, such as reuseable utility functions and data fetching functions.
- ```/app/ui```: Contains all the UI components for your application, such as cards, tables, and forms. To save time, we've pre-styled these components for you.
- ```/public```: Contains all the static assets for your application, such as images.
- ```/scripts/```: Contains a file that you'll use to populate your database in a later chapter.
- ```Config Files```: You'll also notice config files such as next.config.js at the root of your application. Most of these files are created and pre-configured when you start a new project using create-next-app. You will not need to modify them in this course.

- ```page.tsx``` is a special Next.js file that exports a React component containing the UI for the route. In your application, you already have a page file: ```/app/page.tsx``` - this is the home page which is associated with the route /.

- In Next.js, you can use a special ```layout.tsx``` file to create UI that is shared between multiple pages.

- The ```Layout``` component receives a children prop. The child can either be a page or another layout.
