#2nd Year Final Java Project: Steepest Descent Algorithm with Step Size Options

To explain the main idea behind Steepest Descent, I present this simple explanation from Wikipedia: "a first-order iterative optimization algorithm for finding a local minimum of a differentiable function. The idea is to take repeated steps in the opposite direction of the gradient (or approximate gradient) of the function at the current point, because this is the direction of steepest descent." 

To further improve the process, the step sizes taken towards the minima were also subject to different algorithms. So, the Steepest Descent algorithm is run with all 3 of the step sizes, and the results are compared. The first type was a fixed step size, where the step size was a user-defined constant, that didn't change depending on the location on the curve. The second type of step size (SDArmijo class) was calculated using a backtracking line search, which  "is a line search method to determine the amount to move along a given search direction." (Wikipedia) Lastly, the golden-section search was applied to find the step size that resulted in the smallest gradient (normal). "Golden-section search is a technique for finding an extremum (minimum or maximum) of a function inside a specified interval." (Wikipedia). 

The program went through different drafting stages, each of which were deliverables for the UofT 2nd Year Industrial Engineering Course for Object Oriented Programming. The version here is the latest version.
