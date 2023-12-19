// App.js
import React from 'react';
import ExpenseItem from './ExpenseItem';

const App = () => {
  return (
    <div>
      <h1>Expense Items</h1>
      <ExpenseItem title="Food" amount="Rs 10" />
      <ExpenseItem title="Petrol" amount="Rs 100" />
      <ExpenseItem title="Movies" amount="Rs 200" />
    </div>
  );
};

export default App;

// ExpenseItem.js
import React from 'react';

const ExpenseItem = ({ title, amount }) => {
  return (
    <div>
      <p>{title} {amount}</p>
    </div>
  );
};

export default ExpenseItem;
