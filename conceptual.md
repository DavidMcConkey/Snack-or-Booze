### Conceptual Exercise

Answer the following questions below:

- What is the purpose of the React Router?

Its a framework that lets us handle client and server-side routing within React apps.

- What is a single page application?

A single page app dynamically rewrites an existing web page with new informtion from the web server.

- What are some differences between client side and server side routing?

Client-side routing involves JS handling the routing process internally, while SSR is the service response to the browser, shown in HTML.

- What are two ways of handling redirects with React Router? When would you use each?

You could use create or delete as redirects. You would want to use create when the user is uploading data, and delete when they are looking to erase something.

- What are two different ways to handle page-not-found user experiences using React Router?

You can either use the build in wildcard path with an asterick follow by a page not found element, or you can create your own page not found component and link it.

- How do you grab URL parameters from within a component using React Router?

You can use React touers useParams hook.

- What is context in React? When would you use it?

Context is used to mange global data, this might be used with things such as site theme, user settings, and theme.

- Describe some differences between class-based components and function
  components in React.

  A functional component is simple JS, a pure function that accepts props and returns JSX. A class component requires you to extend from React.

- What are some of the problems that hooks were designed to solve?

They were designed to solve confusing classes, overly large components, as well as insane wrapper results.
