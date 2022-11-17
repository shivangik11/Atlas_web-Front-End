# Plan a React TO-DO List



## XD Mockup of a TO_DO List appliaction

![iPhone 14 Pro – 1](https://user-images.githubusercontent.com/89596201/202320921-bd232e56-a4f3-4ec5-a3aa-b3d446b808d3.png)

## Step 1: Break The UI Into A Component Hierarchy

![iPhone 14 Pro – 2](https://user-images.githubusercontent.com/89596201/202320926-7167a6cd-975f-475a-a073-5b1fac8a665e.png)

### The numbers in the image correspond to the numbers below:
1. ToDoTasktable
2. FilterTaskMenu
3. TaskTable
4. Addtask
5. TimelineTaskCategory
6. TimelineHeader
7. TaskRow

## Step 2: Components that appear within another component in the mock should appear as a child in the hierarchy:
 - #### ToDoTasktable
   - FiltertaskMenu
   - TaskTable
     - AddTask
     - TimelineTaskcategory
       - TimelineHeader
       - TaskRow
       
       
## Step 3: Identify The Minimal (but complete) Representation Of UI State
#### All the pieces of data
1. list of task.
2. Adding new task
3. Value of checkboes
4. filters list of task

#### State is:
1. Adding New task
2. Value of checkboxes

## Step 4: Identify Where Your State Should Live

Our state lives in ToDoTaskTable. First, add an instance property this.state = {filterText: '', inStockOnly: false} to ToDoTaskTable’s constructor to reflect the initial state of your application. Then, pass filterText and inStockOnly to TaskRow and AddTask as a prop. Finally, use these props to filter the rows in TaskRow and set the values of the form fields in AddTask.





