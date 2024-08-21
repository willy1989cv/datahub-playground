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
        firstName: 'Jon',
        lastName: 'Snow',
        age: 35,
      },
      {
        firstName: 'Cersei',
        lastName: 'Lannister',
        age: 42,
      },
      {
        firstName: 'Jaime',
        lastName: 'Lannister',
        age: 45,
      }
    ]
  }}
/>
```

to generate this awesome and dynamic table view
<FlatUiTable
data={{
    values: [
      {
        firstName: 'Jon',
        lastName: 'Snow',
        age: 35,
      },
      {
        firstName: 'Cersei',
        lastName: 'Lannister',
        age: 42,
      },
      {
        firstName: 'Jaime',
        lastName: 'Lannister',
        age: 45,
      }
    ]
  }}
/>
