1. 介绍
----------------
本文档是Google的Java™语言的代码风格的 **完整定义** 。只有当Java源文件遵循这里的规则时，才可以说它算遵循了Google的编程风格。

与其他编程风格指南一样，该文档涵盖的问题不仅仅是格式的审美问题，还包括其他类型的约定或代码标准。然而，本文档主要关注的是 **我们普遍遵循的硬性规则** ，并避免提供无法明确执行的建议（无论是对于人还是工具来说）。

1.1. 术语说明
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

在本文档中，除非另有说明：

- 1. 术语“类”（class）被广泛地用来指代“普通”类、枚举类、接口或注解类型（ ``@interface`` ）。

- 2. 术语“(类的)成员”（member）被广泛地用来指代嵌套类、字段、方法或构造函数，即除了初始化块和注释之外类的所有顶级内容。

- 3. 术语“注释”（comment）始终指的是实现注释。我们不使用“文档注释”这种说法，而是使用另一常见的说法“Javadoc”代替。

其他的“术语说明”也将在整个文档中偶尔出现。

1.2. 指南说明
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

此文档中的示例代码 **并不是规范性的** 。也就是说，尽管示例是按照Google风格编写的，但它们可能并不是实现代码的唯一优雅方式。示例中做出的选择性的格式不应被强制作为规则。
