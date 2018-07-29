# Calc
Compilation of some frequently used calculations.

### Methods
#### 1. Calc.round(double value, int decimalPlace)
This method is used to round a double value to a decimal place.
##### For example:
Calc.round(12,345, 1); // result: 12,4

<br>

#### 2. Calc.degreeToRadian(double degree)
This method is used to convert a degree value to radian.
##### For example:
Calc.degreeToRadian(180); // result: 3.141592653589793

<br>

#### 3. Calc.dpToPx(Context context, float dp)
This method is used to convert dp value to px.
##### For example:
Calc.dpToPx(context, 100) // result: 150 (depends on your screen)

<br>

#### 4. Calc.pxToDp(Context context, float px)
This method is used to convert px value to dp.
##### For example:
Calc.dpToPx(context, 150) // result: 100 (depends on your screen)
