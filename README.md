# CK_metrices.teamproj_cis375
# CK Metrics Suite

The CK Metrics Suite is a web application that calculates various software complexity metrics for object-oriented software projects. These metrics can help software developers and analysts assess the quality and maintainability of their code.

## Metrics Calculated

1. **Weighted Methods per Class (WMC)**: Measures the complexity of a class based on the number and complexity of its methods.

2. **Depth of Inheritance Tree (DIT)**: Indicates the depth of the inheritance hierarchy for a class, showing how many classes inherit from a particular class.

3. **Number of Children (NOC)**: Counts the number of immediate subclasses of a class, indicating how many classes inherit directly from it.

4. **Coupling Between Object Classes (CBO)**: Measures the number of collaborations between classes, indicating how interconnected they are.

5. **Response for a Class (RFC)**: Determines the number of methods in a class that respond to user inputs, helping identify classes with high responsibilities.

6. **Lack of Cohesion in Methods (LCOM)**: Identifies classes with attributes that are accessed by many methods, indicating potential issues with cohesion.

## How to Use

1. Enter the values for each metric in the respective input fields.
2. Click the "Submit" button to calculate the metrics.
3. Review the results and use them to assess your software project.

## Usage Notes

- Input values should be positive integers.
- Use the "Clear" button to reset the input fields.
