# Data Visualization Projects: Visualize Data with a Scatterplot Graph for freecodecamp.org

### Build a Scatterplot Graph with D3

Try it on Codepen: https://codepen.io/Romugar/pen/wEZBXb

#### Objective

Build a CodePen.io app that is functionally similar to this: https://codepen.io/freeCodeCamp/full/bgpXyK.

#### Fulfill the below user stories and get all of the tests to pass. Give it your own personal style. You can use HTML, JavaScript, CSS, and the D3 svg-based visualization library. The tests require axes to be generated using the D3 axis property, which automatically generates ticks along the axis. These ticks are required for passing the D3 tests because their positions are used to determine alignment of graphed elements. Required (non-virtual) DOM elements are queried on the moment of each test. If you use a frontend framework (like Vue for example), the test results may be inaccurate for dynamic content. We hope to accommodate them eventually, but these frameworks are not currently supported for D3 projects.

1. User Story: I can see a title element that has a corresponding id="title".
2. User Story: I can see an x-axis that has a corresponding id="x-axis".
3. User Story: I can see a y-axis that has a corresponding id="y-axis".
4. User Story: I can see dots, that each have a class of dot, which represent the data being plotted.
5. User Story: Each dot should have the properties data-xvalue and data-yvalue containing their corresponding x and y values.
6. User Story: The data-xvalue and data-yvalue of each dot should be within the range of the actual data and in the correct data format. For data-xvalue, integers (full years) or Date objects are acceptable for test evaluation. For data-yvalue (minutes), use Date objects.
7. User Story: The data-xvalue and its corresponding dot should align with the corresponding point/value on the x-axis.
8. User Story: The data-yvalue and its corresponding dot should align with the corresponding point/value on the y-axis.
9. User Story: I can see multiple tick labels on the y-axis with %M:%S time format.
10. User Story: I can see multiple tick labels on the x-axis that show the year.
11. User Story: I can see that the range of the x-axis labels are within the range of the actual x-axis data.
12. User Story: I can see that the range of the y-axis labels are within the range of the actual y-axis data.
13. User Story: I can see a legend containing descriptive text that has id="legend".
14. User Story: I can mouse over an area and see a tooltip with a corresponding id="tooltip" which displays more information about the area.
15. User Story: My tooltip should have a data-year property that corresponds to the data-xvalue of the active area.

#### Here is the dataset you will need to complete this project:
* https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/cyclist-data.json

