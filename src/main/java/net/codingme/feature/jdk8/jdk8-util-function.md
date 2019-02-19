- Supplier<T>: 数据提供器，可以提供 T 类型对象；无参的构造器，提供了 get 方法；
- Function<T,R>: 数据转换器，接收一个 T 类型的对象，返回一个 R类型的对象； 单参数单返回值的行为接口；提供了 apply, compose, andThen, identity 方法；
- Consumer<T>: 数据消费器， 接收一个 T类型的对象，无返回值，通常用于设置T对象的值； 单参数无返回值的行为接口；提供了 accept, andThen 方法；
- Predicate<T>: 条件测试器，接收一个 T 类型的对象，返回布尔值，通常用于传递条件函数； 单参数布尔值的条件性接口。提供了 test (条件测试) , and-or- negate(与或非) 方法。