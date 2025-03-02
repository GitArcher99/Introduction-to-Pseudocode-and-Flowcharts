# Introduction-to-Pseudocode-and-Flowcharts

START

DISPLAY "Enter the number of hours worked:"
INPUT hoursWorked

SET regularRate = 20
SET overtimeRate = 30
SET regularHours = 40
SET totalPay = 0

IF hoursWorked <= regularHours THEN
    totalPay = hoursWorked * regularRate
ELSE
    overtimeHours = hoursWorked - regularHours
    totalPay = (regularHours * regularRate) + (overtimeHours * overtimeRate)
ENDIF

DISPLAY "The total weekly paycheck is: $" + totalPay

END
