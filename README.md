# Codealpha_tasks
## Feature Engineering Plan
--Time-Based Features (if timestamps were available, but we don’t seem to have one)

--Rolling Statistics (moving averages, standard deviations for numerical columns)

--Interaction Features (Ratios and multiplications of features)

--Categorical Encoding (Type using One-Hot Encoding or Label Encoding)

--Aggregated Features (Mean, Min, Max values grouped by Type)

--Polynomial Features (if non-linearity exists)

--Outlier Detection Features (flag extreme values)

--Log Transformations or Scaling (for better distribution)

## Numerical Features:

`Air temperature [K]`, `Process temperature [K]`, `Rotational speed [rpm]`, `Torque [Nm]`, `Tool wear [min]`

## Categorical Features:

`Product ID`, `Type`

## Target Variable:

`Machine failure` **(Binary: 0 = No failure, 1 = Failure)**

## Failure Types:

`TWF (Tool Wear Failure)`, `HDF (Heat Dissipation Failure),` `PWF (Power Failure)`, `OSF (Overstrain Failure)`, `RNF (Random Failures)`

## Dataset Info.
'The dataset contains 10,000 entries with 14 columns, including numerical and categorical features.'

## Categorical Encoding

"Type_Encoded (Label Encoding for Type)"

## Interaction Features

"Torque_per_RPM = Torque / Rotational Speed"

"Temperature_Diff = Process Temperature - Air Temperature"

## Rolling Statistics (Window = 5)

"Rolling_Mean_Torque"

"Rolling_Std_Torque"

## Aggregated Features by Type

"Mean and Standard Deviation for Air temperature, Process temperature, Rotational speed, and Torque"

## Log Transformation

"Log_Torque = Log(1 + Torque) (for normalizing the distribution)"




























