## Adding a Table Component

With Datahub Cloud, you can easily add table component to your datasets or data stories.

### FlatUiTable

A dynamic component that will render your flat dataset (an array of objects) in a table view. it comes with a variety of features that can enhance the way your data is presented, such as sorting, pagination, and export options.

#### Data source

#### Adding data from array objects

You may just want to show some static data in your story. in this case, you'll have to pass a `data.values` attribute to the component in you .md file. Like this:

```md
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
```

to visualize this dynamic table, where you can sort your data, allow exporting and some other cool features...
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

#### 4 Adding through a external csv file.

Your data can also be a csv file that is hosted somewhere else, you can show it on your story passing a `data.url` property to the FlatUiComponent:

```md
<FlatUiTable
data={
url : "https://storage.openspending.org/alberta-budget/__os_imported__alberta_total.csv"
}
/>
And...
<FlatUiTable
data={
url : "https://storage.openspending.org/alberta-budget/__os_imported__alberta_total.csv"
}
/>
```
