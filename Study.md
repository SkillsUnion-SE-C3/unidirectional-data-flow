[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# Unidirectional Data Flow: Study

Use [DuckDuckGo](https://duckduckgo.com/) or your preferred search engine along with the provided resources to research and answer the [questions below](#questions).

## Required Reading

- [What is unidirectional data flow in React](https://flaviocopes.com/react-unidirectional-data-flow/)
- [Lifting state up](https://reactjs.org/docs/lifting-state-up.html)
- [Lifting state up video](https://www.youtube.com/watch?v=ahKsy1FS45k)
- [Inverse data flow](https://dev.to/isabelxklee/understanding-inverse-data-flow-in-react-3cg7)
- [Container vs Representational Components](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0)
- [Conditional rendering](https://www.youtube.com/watch?v=fAUkKh-WfLM)

## Questions

1. Describe what is unidirectional data flow.

   ```
   This is the concept that data has only one flow direction when transferring to other parts of the application
   ```

2. What does it mean to have a single source of truth for data?

   ```
   when you want to implement 'single source of truth', you want to make your components controllable.
   ```

3. What is the limitation of inverse data flow?

   ```
   components that do not have a direct parent or child relationship cannot share props with each other.
   ```

4. Why is it a good practice to separate container and representational components?
   ```
   Better separation of concerns. You understand your app and your UI better by writing components this way.
    You can use the same presentational component with completely different state sources, and turn those into separate container components that can be further reused.
    You can put them on a single page and let the designer tweak all their variations without touching the app’s logic.
    This forces you to extract “layout components” such as Sidebar, Page, ContextMenu and use this.props.children instead of duplicating.
   ```

### Response Guidelines

Please follow these guidelines as you answers these questions:

- Cite any relevant sources consulted during your research
- Do not reply using direct quotes from the source material
- Provide an answer using your own words and voice
