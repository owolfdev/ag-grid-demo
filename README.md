## AG Grid Demo with Next.js

This project is a demo of how to use AG Grid with a Next.js application. AG Grid is a powerful and flexible JavaScript data grid that provides advanced features like sorting, filtering, and pagination.

This project demonstrates how to fetch data from a remote API and display it in an AG Grid table. The table allows users to filter and paginate the data, making it easy to work with large data sets.

### Getting Started

To run this project, you will need Node.js installed on your machine. Once you have Node.js installed, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Run npm install to install the project dependencies.
4. Run npm run dev to start the development server.
5. Open http://localhost:3000 in your browser to view the demo.

### AG Grid Component

The AG Grid component in this demo is a functional component written in TypeScript. It fetches data from a remote API using the useEffect hook and sets it as the rowData state variable.

The columnDefs variable defines the columns to display in the table. It specifies the field name and the filter type for each column.

The defaultColDef variable sets default properties for all columns. In this demo, it sets the flex, minWidth, and resizable properties.

The onGridReady function sets the gridApi and gridColumnApi state variables when the grid is ready. This allows us to interact with the grid through the API.

The onPaginationChanged function is called when the pagination changes. In this demo, it simply logs a message to the console.

The clearFilters function clears all filters when the "Clear Filters" button is clicked.

The component returns an AgGridReact component with the necessary properties to display the grid. It also includes some styles to customize the appearance of the grid and the pagination controls.

### Conclusion

This demo shows how easy it is to use AG Grid with a Next.js application. AG Grid provides powerful data grid features that make it easy to work with large data sets.
