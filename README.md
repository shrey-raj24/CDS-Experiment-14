# Experiment-14 

### Aim 
To study and implement Inheritance. 

### Software 
Visual Studio Code. 

### Theory 

### Code 
(A) <br> 
```

// NAME - SHREY RAJ
// PRN - 23070123123
// EXPERIMENT - 14(A)  

# include <iostream>
# include <string>
using namespace std;

class Uni
{
    public:
    string uni= "Symbiosis";
    void discipline()
    {
        cout << "Engineering" <<endl;
    }
};
class Dep : public Uni
{
    public:
    string dept= " Electronics & Telecommunication";
};
int main()
{
    Dep u1;
    u1.discipline();
    cout<<u1.uni + " "+u1.dept ;
} 

// Output 
// 
// Engineering
// Symbiosis  Electronics & Telecommunication


```

(B) <br> 
```

// NAME - SHREY RAJ
// PRN - 23070123123 
// EXPERIMENT - 14(B) 

#include<iostream> 
#include<string> 
using namespace std; 

// Parent CLass1 
class Vehicle {
    public:
    string company=" Ford";
    void type(){
        cout << "Mustang"<< endl;
    }
};
// Parent Class 2
class Specs{
    public:
    string mileage="8 kmpl";
    void colour(){
        cout<<"Grey"<<endl;
    }
};
// Child Class-1 (derived from parent- 1&2)
class Car: public Vehicle,public Specs{
    public:
    string seater = " 4 seater";
};
int main(){
    //multiple inheritance
    Car f2;
    f2.colour();
    cout<<f2.company<<" ";
    f2.type();
    cout<<"("<<f2.seater<<")"<<endl<<"MILEAGE:"<<f2.mileage<<endl;
} 

// Output 
// Grey
//  Ford Mustang
// ( 4 seater)
// MILEAGE:8 kmpl

```

(C) <br> 
```

// NAME - SHREY RAJ
// PRN - 23070123123 
// EXPERIMENT - 14(B) 

#include<iostream> 
#include<string> 
using namespace std; 

// Parent CLass1 
class Vehicle {
    public:
    string company=" Ford";
    void type(){
        cout << "Mustang"<< endl;
    }
};
// Parent Class 2
class Specs{
    public:
    string mileage="8 kmpl";
    void colour(){
        cout<<"Grey"<<endl;
    }
};
// Child Class-1 (derived from parent- 1&2)
class Car: public Vehicle,public Specs{
    public:
    string seater = " 4 seater";
};
int main(){
    //multiple inheritance
    Car f2;
    f2.colour();
    cout<<f2.company<<" ";
    f2.type();
    cout<<"("<<f2.seater<<")"<<endl<<"MILEAGE:"<<f2.mileage<<endl;
} 

// Output 
// Grey
//  Ford Mustang
// ( 4 seater)
// MILEAGE:8 kmpl
                                   
```

(D) <br> 
```

// NMAE - SHREY RAJ
// PRN - 23070123123
// EXPERIMENT - 14(D) 

// Program to show Hiererchical Inheritance.                    

#include <iostream>
using namespace std;

// base class
class Flower {
public:
    Flower() { cout << "This is a Flower. \n"; }
};

// first sub class
class Lotus : public Flower {
public:
    Lotus() { cout << "This flower is a lotus. \n"; }
};

// second sub class
class Marigold : public Flower {
public:
    Marigold() { cout << "Thisflower is a marigold. \n"; }
};

// main function
int main()
{
    // Creating object of sub class will invoke the constructor of base class.
    Lotus obj1;
    Marigold obj2;
    return 0;
} 

// Output 
// This is a Flower. 
// This flower is a lotus. 
// This is a Flower.
// Thisflower is a marigold. 
                                                                                            
```

### Output 
(A) <br>  
![](https://github.com/shrey-raj24/CDS-Experiment-14/blob/main/Output_14a.png) 

(B) <br> 
![](https://github.com/shrey-raj24/CDS-Experiment-14/blob/main/Output_14b.png) 

(C) <br> 
![](https://github.com/shrey-raj24/CDS-Experiment-14/blob/main/Output_14c.png) 

(D) <br> 
![](https://github.com/shrey-raj24/CDS-Experiment-14/blob/main/Output_14d.png) 

### Conclusion 
I learnt about inheritance in C++, its keywords, modes, types and performed programs based on that. 
