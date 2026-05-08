Data Cleaning Process (Step-by-Step)

Step 1: Remove Extra Spaces
  =TRIM(A2)

Step 2: Standardize Names
  =PROPER(A2)

Step 3: Extract First Name
  =LEFT(A2, FIND(" ", A2)-1)

Step 4: Extract Last Name
  =RIGHT(A2, LEN(A2)-FIND(" ", A2))

Step 5: Format Phone Number
  Example formula (depending on structure):
    ="+1 (" & LEFT(B2,3) & ")-" & MID(B2,4,3) & "-" & RIGHT(B2,3)

Step 6: Standardize State Codes
=UPPER(C2)

Step 7: Final Table
Ensure columns:
  First Name
  Last Name
  Phone Number
  State
