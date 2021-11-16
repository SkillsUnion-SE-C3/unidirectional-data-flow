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
  Due to one way bindings, in react the state is passed to the view and to child components actions are triggered by the view and actions can update the state. In a cycle of view, action and state the state change is passed to the view and to the child components. 
   ```

2. What does it mean to have a single source of truth for data?

   ```
  As oppose to trying to sync the state between different components, the top-down data flow should be implemented. A state is added first of all to the component that needs it for rendering. Then, if other components also need it, lifting state up can be conducted to bring up other components to their closest common ancestor. 


   ```

3. What is the limitation of inverse data flow?

   ```
  As it is restrictive it can result in lots more code if complex relationships are involved.
   ```

4. Why is it a good practice to separate container and representational components?
   ```
   As they can increase code reusability and separate concerns by using rules of ou can use the same presentational component with completely different state sources used for how things appear and container component acting as data sources due to their use of state and provide the data to other containers 
   ```

### Response Guidelines

Please follow these guidelines as you answers these questions:

- Cite any relevant sources consulted during your research
- Do not reply using direct quotes from the source material
- Provide an answer using your own words and voice
