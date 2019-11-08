# HTTP Movies

### Part 1 - Updating A Movie:

- Add edit button in movie component to route you to the movies's id as the URL param

- Add a route at path `/update-movie/:id`
- Create form component to update movie
- The form should make a PUT request to the server when submitted
- on successful call, reset your form state and route the user to `/`

Movie object format:

```
{
  id: 5,
  title: 'Tombstone',
  director: 'George P. Cosmatos',
  metascore: 89,
  stars: ['Kurt Russell', 'Bill Paxton', 'Sam Elliot'],
}
```

### Part 2 - Deleting A Movie:

- Add a delete button in movie component
- on successful call, route user to `/`

### Part 3 (Stretch) - Adding A Movie:

- Add a route at the path `/add-movie`
- Create a component with a form to add a new movie
- Each created movie should have the following format (notice the array of strings - this will test your JS skills, so work through it methodically)
- The form should make a POST request to the server when submitted
- When the call comes back successfully, reset your form state and route the user to `/movies`

Movie object format:

```
{
  id: 5,
  title: 'Tombstone',
  director: 'George P. Cosmatos',
  metascore: 89,
  stars: ['Kurt Russell', 'Bill Paxton', 'Sam Elliot'],
}
```

## Stretch Problem

- See Part 3 above (Adding movies with a POST request)
- Style the app!
