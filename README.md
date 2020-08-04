# DrawerLayout must be measured with MeasureSpec.EXACTLY

When using a DrawerLayout in a Fragment contained within a ConstraintLayout (with some constraint), it results on the following crash : 
DrawerLayout must be measured with MeasureSpec.EXACTLY error

In this sample it can be avoided if we change the constraint on the fragment from "above the bottomNavigationView" to "match_parent".