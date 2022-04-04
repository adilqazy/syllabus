# **Null Safety**

С версии Dart 2.12 все переменные создаются как *null Safety*  
То есть переменной объявляемого типа данных нельзя присвоить значение null.  
Для того чтобы переменная смогла принять значение **null** необходимо указать ее как var? = null 

Что такое null 
```
    var a = "Hello";  //строка со значениями
    var b = "";         //строка без значений
    var c = null;       //строка которой нет

    String c = null;
    int r = null; 
    double t = null;  //все разные null 

```
    void main(List<String> argument) {
        
        int? r = null;      // int? может быть null
        r = 5;

        var v = r + 5;
        print(v);
    }