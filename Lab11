#include <iostream>
#include <vector>
#include <stdlib.h>
#include <string>
#include <cstdlib>


using namespace std;

template <class T>;
class Stack{
private:
    deque<T> elem;

public:
    bool Empty();
    void push(T const&);
    T top() const;
    void pop();
};

template <class T>
bool Stack<T>::Empty()
{
    return elem.empty();
}

template <class T>
void Stack<T>::push(T const& x)
{
    elem.push_back(x);
}

template <class T>
T Stack<T>::top() const
{
    if(elem.empty())
        cout<<"Stiva este goala"<<endl;
    else
        return elem.back();
}

template <class T>
void Stack<T>::pop()
{
    if (elem.empty())
        cout<<"Stiva este goala"<<endl;
    else
        elem.pop_back();
}

int main ()
{
Stack<int> a1;
Stack<string> a2;

//Stack de int
a1.push(3);
a1.push(5);
cout<<a1.top()<<endl;
a1.pop();
cout<<a1.top()<<endl;

//Stack de string
a2.push("yolo");
a2.push("aiaiai");
cout<<a2.top()<<endl;
a2.pop();
cout<<a2.top()<<endl;

return 0;
}
