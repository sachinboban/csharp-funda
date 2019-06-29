# Scope
Scope is the area where a variable/constant has meaning (life).

```c#
{   // Block A
    int Var1 = 1;

    {   // Block B
        int Var2 = 2;

        {   //Block C
            int Var3 = 3;
        }
    }
}
```

Scope of `Var1`: Block A
Scope of `Var2`: Block B
Scope of `Var3`: Block C

> Block A: `Var1` is valid
> Block B: `Var1` and `Var2` are valid
> Block C: `Var1`, `Var2` and `Var3` are valid
