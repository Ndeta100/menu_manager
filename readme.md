 Project : Interactive bill manager <br />

 Summary:<br />
   Create a command line bills/expenses manager that runs<br />
   interactively. This mini project brings together many of<br />
   the concepts learn thus far into a single application.<br />

   The user stories/requirements are split into stages.<br />
   Fully implement each stage as a complete working program<br />
   before making changes for the next stage. Leverage the<br />
   compiler by using `cargo check --bin p1` when changing<br />
   between stages to help identify adjustments that need<br />
   to be made.

 User stories:<br />
 * Stage 1:<br />
   - I want to add bills, including the name and amount owed.<br />
   - I want to view existing bills.<br />
 * Stage 2:<br />
   - I want to remove bills.<br />
 * Stage 3:<br />
   - I want to edit existing bills.<br />
   - I want to go back if I change my mind.<br />

 Tips:<br />
 * Use the loop keyword to create an interactive menu.<br />
 * Each menu choice should be it's own function, so you can work on the<br />
   the functionality for that menu in isolation.<br />
 * A vector is the easiest way to store the bills at stage 1, but a<br />
   hashmap will be easier to work with at stages 2 and 3.<br />