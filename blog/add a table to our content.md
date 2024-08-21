Let's add a table to the `README.md` file. Under the `## Table` header in your file, add the following snippet:

```mdx
<FlatUiTable
  data={{
    values: [
      {
        age: 35,
        firstName: "Jon",
        id: 1,
        lastName: "Snow",
      },
      {
        age: 42,
        firstName: "Cersei",
        id: 2,
        lastName: "Lannister",
      },
      {
        age: 45,
        firstName: "Jaime",
        id: 3,
        lastName: "Lannister",
      },
      {
        age: 16,
        firstName: "Arya",
        id: 4,
        lastName: "Stark",
      },
      {
        age: 44,
        firstName: "Ferrara",
        id: 7,
        lastName: "Clifford",
      },
      {
        age: 36,
        firstName: "Rossini",
        id: 8,
        lastName: "Frances",
      },
      {
        age: 65,
        firstName: "Harvey",
        id: 9,
        lastName: "Roxie",
      },
    ],
  }}
/>
```

Here's what it's going to look like:

<FlatUiTable
data={{
    values: [
      {
        age: 35,
        firstName: 'Jon',
        id: 1,
        lastName: 'Snow'
      },
      {
        age: 42,
        firstName: 'Cersei',
        id: 2,
        lastName: 'Lannister'
      },
      {
        age: 45,
        firstName: 'Jaime',
        id: 3,
        lastName: 'Lannister'
      },
      {
        age: 16,
        firstName: 'Arya',
        id: 4,
        lastName: 'Stark'
      },
      {
        age: 44,
        firstName: 'Ferrara',
        id: 7,
        lastName: 'Clifford'
      },
      {
        age: 36,
        firstName: 'Rossini',
        id: 8,
        lastName: 'Frances'
      },
      {
        age: 65,
        firstName: 'Harvey',
        id: 9,
        lastName: 'Roxie'
      }
    ]
  }}
/>
