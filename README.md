# prediction-using-tensorflow-and-excel-file
The program takes the values( day, temperature, wind speed) from the excel file and predict whether the day is good or bad.

Program takes the first 8 inputs and outputs to train the model.
the rest inputs are for testing.

**********************______________________***********************
NOTE:
1. whenever multiple outputs are present, use
        loss='sparse_categorical_crossentropy'
       while compiling the model.
2. whenever single output is given, use
        loss='binary_crossentropy'
