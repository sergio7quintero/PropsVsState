# PropsVsState
Deep Dive on Props vs State with react

How useState is Used
The application utilizes the useState hook in the FilterableProductTable component to manage the following states:
filterText: A string that tracks the search input and filters products accordingly.
inStockOnly: A boolean that determines whether only in-stock products should be displayed.

How Props is Used
Props are used to pass data and functions between parent and child components

FilterableProductTable → SearchBar
Passes down filterText, inStockOnly, and their corresponding setter functions (onFilterTextChange, onInStockOnlyChange).
Enables SearchBar to update the state when the user types or checks the box.

This project is a React product filtering table that uses useState to manage search and stock filter states. The app relies on props to pass data between components, ensuring a modular and efficient UI. Users can type in the search bar to filter products or check a box to show only in-stock items, making for an interactive and responsive experience.
