# COBOL Payroll Processor

Procesa empleados con salario base y calcula bono del 10%.

```powershell
cobc -x payroll.cob -o payroll
./payroll employees.dat
```

`employees.dat` usa el formato `ID|NOMBRE|SALARIO`.
