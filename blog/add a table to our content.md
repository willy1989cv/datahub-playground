# Adding a Table Component

Datahub Cloud allows you to easily add table components to your datasets or data stories. Here’s how you can do it using different approaches:

## FlatUiTable

The `FlatUiTable` component dynamically renders your dataset (whether it’s an array of objects, a CSV file, inline CSV, or an external source) in a table view. It offers features like filtering, sorting, pagination, and export options.

### Adding Data from Array Objects

To display static data in your story, pass a `data.values` attribute to the component in your `.md` file. For example:

```js
<FlatUiTable
  data={{
    values: [
      { FirstName: "Jon", LastName: "Snow", Age: 35 },
      { FirstName: "Cersei", LastName: "Lannister", Age: 42 },
      { FirstName: "Jaime", LastName: "Lannister", Age: 45 },
    ],
  }}
/>
```

To visualize and interact with your data:

<FlatUiTable
data={{
    values: [
      {
        FirstName: "Jon",
        LastName: "Snow",
        Age: 35,
      },
      {
        FirstName: "Cersei",
        LastName: "Lannister",
        Age: 42,
      },
      {
        FirstName: "Jaime",
        LastName: "Lannister",
        Age: 45,
      }
    ]
  }}
/>

### Adding Data from External Sources

If your data is stored in an external CSV file, you can display it by passing the `data.url` property to the `FlatUiTable` component:

```js
<FlatUiTable
  data={{
    url: "https://storage.openspending.org/alberta-budget/__os_imported__alberta_total.csv",
  }}
/>
```

And the table will be rendered like this:

<FlatUiTable
data={{
    url : "https://storage.openspending.org/alberta-budget/__os_imported__alberta_total.csv"
  }}
/>

### Using Inline CSV

You can also write inline CSV data using the `data.csv` property:

```js
<FlatUiTable
  data={{
    csv: "Year,Temp Anomaly\n1850,-0.418\n2020,0.923",
  }}
/>
```

To see it in action:

<FlatUiTable
data={{
    csv: "Year,Temp Anomaly\n1850,-0.418\n2020,0.923",
  }}
/>
