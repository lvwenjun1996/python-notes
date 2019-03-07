# python-notes

## 一. python 对象：
1. 实例化过程中，如果构造函数不需要参数，可以使用诸如c = Class（）来实例化；如果构造函数需要参数，可以使用诸如c = Class（a,b,c,...）来构造一个新实例。
2. 有些方法返回对象的状态信息，但不改变其状态，称为访问器；有些方法会改变对象的状态，称为应用程序或更新方法。
3. 内置类中，bool，int，float，str，tuple，frozenset为不可变类；list，set，dict为可变类。
4. int（）默认返回0， float（）默认返回0.0， bool（）默认返回False, list（）默认产生空列表， set（）默认产生空集合。
## 二. python 运算符：
1. 运算符的语义取决于其操作数的类型。
2. 若q = n // m，r = n % m，保证n = q * m + r，对于小数，负数也适用。
3. 对于a += b和a = a + b，前者不改变a的原id，后者改变a的id。
