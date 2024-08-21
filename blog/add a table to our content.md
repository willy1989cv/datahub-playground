## Adding a Table Component

With Datahub Cloud, you can easily add table component to your datasets or data stories.

### FlatUiTable

A dynamic component that will render your flat dataset (an array of objects) in a table view

#### Adding static data

You can may just want to show some static data in your story, in this case, you can insert this snippet in you .md file

```md
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
    ]
  }}
/>
```

to generate this awesome and dynamic table view
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
    ]
  }}
/>
