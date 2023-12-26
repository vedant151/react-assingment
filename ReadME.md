what to do??

--> For every todo cmp between old and new todo state
1) If the todo is not present in old todo then it is added, so add that to do to added array
2) If todo is present in old but not present in new todo then it is deleted, so add it to deleted array
3) If the todo is present in both but content is changed then it is updated todo, so add it to updated array

// Input fields changes 
--> input1 -- title
--> input2  --> description
--> id --> Give your todo a id, don't auto increament it, cause it will help in updating stuff

--> display changes 
--> add todo -> btn
--> delete todo -> btn
--> Update todo --> btn 