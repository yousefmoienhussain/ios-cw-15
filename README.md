# الهيكل Struct


## في هذا التمرين سنقوم بعمل تطبيق لعرض حالة توصيل الطلبات كما هو موضح بالصورة.


### كيف تقوم بإنشاء الهيكل Struct جديد

```
struct NameOfStruct {
   	// our variables and Constants
}
```

### كيف نقوم باستعمال هذا الهيكل 

```
NameOfStruct(nameOfvariable: value)
```


### مثال:


```
struct Person{
    let name: String
    let age : Int
}
Person(name: "Adnan", age: 47)
```



---


### تمرين (<a href="https://github.com/kuwaitcodes/ios-cw-15">رابط التمرين</a>)




### 1. قم بعمل fork من رابط gitHub ، ثم قم بإنشاء تطبيق جديد في XCode.


### 2. قم بإنشاء هيكل جديد يحتوي على المنطقة المراد التوصيل لها و رقم الطلب وحالة الطلب، حيث أن : 

#### * المنطقة من نوع String 
#### * رقم الطلب من نوع Int 
#### * حالة الطلب من نوع Bool



### 3. قم بعمل ٣ متغيرات عن طريق الهيكل، واضف بيانات خاصة لهم.


### 4. يجب عليك استخدام if statement :


#### * في حالة كانت حالة الطلب False : يجب طباعة الشكل : دائرة حمراء.
#### * في حالة كانت حالة الطلب True : يجب طباعة الشكل : دائرة خضراء.

      
#### ** لطباعة هذه الأشكال ستستخدم SF Symbols

<p align="center">
<img width="245" alt="Screen Shot 2022-02-28 at 4 16 52 AM" src="https://user-images.githubusercontent.com/60436597/156063174-3711be50-6492-4f1f-9692-6b27703094f0.png">
</p>
