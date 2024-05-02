# Assignment-5

P1:
This Java interface named `Shapes` defines two methods:

1. `area()`: This method is responsible for calculating the area of a shape. It doesn't have any parameters and returns a double value representing the area of the shape.

2. `perimeter()`: This method calculates the perimeter of a shape. Similar to the `area()` method, it doesn't take any parameters and returns a double value representing the perimeter of the shape.

By implementing this interface, classes can define their own implementations for these methods based on the specific shape they represent. This promotes consistency and enables polymorphic behavior when working with different types of shapes.

p2:
In the `main` method:

- An instance of `NormalEmployee` is created and its details are obtained using the `getEmployeeDetails` method. Then, the salary is calculated using the `salaryCalculation` method.
- Similarly, an instance of `BonusEmployee` is created, its details are obtained, and the salary is calculated.

The program showcases the behavior of both types of employees and their respective salary calculation methods.


In the `salaryCalculation` method:

- Basic wage (`bw`) is calculated as a percentage of the gross wage, considering the paid days and total working days.
- House Rent Allowance (`hra`) is calculated as a percentage of the basic wage.
- Conveyance Allowances (`ca`) and Medical Allowances (`ma`) are calculated based on fixed amounts per day multiplied by the paid days.
- Other allowances are calculated as the difference between the total earning and the sum of basic wage, HRA, conveyance allowances, and medical allowances.
- EPF (Employee Provident Fund) is calculated based on a fixed percentage of the basic wage, capped at a maximum value if the basic wage exceeds a certain threshold.
- ESI (Employee State Insurance) is calculated as a percentage of the total earning if it falls within a certain range; otherwise, it is zero.
- Other deductions such as Professional Tax (`pt`) and Loan Recovery are set to zero for normal employees.
- Total deductions are calculated as the sum of EPF, ESI, PT, and Loan Recovery.
- Net salary is calculated as the total earning minus total deductions.


