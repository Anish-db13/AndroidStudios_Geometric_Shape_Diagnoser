# AndroidStudios_Geometric_Shape_Diagnoser
Geometry Calculations
Introduction:
In this assignment, you are to write a handful of methods that perform common geometry
calculations such as calculating the area of a circle, or the perimeter of a right triangle, or the
volume of a box.
Learning Outcomes:
After completing this assignment, you will have experience with:
1. Writing methods that accept parameters and return a value.
2. Creating local variables to hold values.
3. Writing expressions that use various operators and Math functions.
4. Using assignment statements to give new values to variables.
Resources:
Please download the supplied zip file available with this specification. Extract the files onto your
computer. The extracted files contain an Android Studio project. Start Android Studio and open
the project as demonstrated in an earlier module. All your work for this assignment will be in the
file Logic.java. Open this file in the IDE and look for the comment:
// TODO -- add your code here
As you do your work, be sure to place all your code in the Logic class.
Tasks:
You are to write a handful of methods that perform common geometry calculations. Below are
the headers of the methods you are to add to the Logic class contained in the file Logic.java.
These are just the headers. Your job is to add each of these methods, including method header
and method body, to the file Logic.java.
public static double rectangleArea(double length, double width)
public static double rectanglePerimeter(double length, double width)
public static double circleArea(double radius)
public static double circleCircumference(double radius)
public static double rightTriangleArea(double base, double height)
public static double rightTrianglePerimeter(double base, double height)
public static double boxVolume(double length, double width, double depth)
public static double boxSurfaceArea(double length, double width,
 double depth)
public static double sphereVolume(double radius)
public static double sphereSurfaceArea(double radius)
All the methods must be placed in the file Logic.java, within the Logic class. Each method
should accept parameters as specified above, in the specified order. It is recommended that you
simply copy-n-paste the above headers into your file. The methods should then perform the
necessary calculations and return the results to the caller. Note that all methods simply return
values to the caller; they do not print out the values.
What the methods compute is fairly obvious. For computing the area and perimeter of a triangle,
we will do so only for a right triangle with the given base and height (and thus the names of the
methods). If you do not know how to compute any of the ten values, please perform an
appropriate web search for the correct formula.
Source code aesthetics (commenting, indentation, spacing, identifier names): You should
properly indent your code. No line of your code should be over 100 characters long (even better
is limiting lines to 80 characters). You should use a consistent programming style. This should
include the following.
• Meaningful variable & method names
• Consistent indenting
• Use of "white-space" and blank lines to make the code more readable
• Use of comments to explain pieces of tricky code
• Comment headers on all methods that explain what the method computes and any pre- or
post-conditions
Submission:
See the assignment page in Coursera for instructions on using gradle to create the necessary zip
file and submit it for evaluation by the auto-grader.
