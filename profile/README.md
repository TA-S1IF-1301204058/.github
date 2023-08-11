## Understanding the Impact of Modularity in iOS App Performance using VIPER Architecture Pattern

Undergraduate Thesis

Telkom University

School of Computing - Informatics

Muhammad Rizki Andika

1301204058

# Abstract

The increasing complexity of modern applications and the demand for enhanced features and functionality have made performance an essential consid- eration in application development. VIPER, derived from the principles of Clean Architecture, is an approach often used to build complex applications. This architecture offers advantages such as increased separation of code responsibilities. Another technique commonly used is modularization, which involves dividing an application into different modules to increase separability and simplify development. Also, it is worth noting that the Swift compiler supports dynamic and static compilation of modular components in iOS apps. Dynamic compilation evaluates and links code at runtime, providing flexibility and late binding of dependencies. This compilation allows modular components to be loaded and unloaded dynamically, o↵ering runtime adaptability. In contrast, static compilation compiles and links the code at compile time, creating a self-contained binary with all the necessary dependencies. However, it is crucial to investigate whether this modularization technique impacts application performance. Therefore, this study aims to examine the effect of modularization on the performance of iOS applications, especially using the VIPER architecture pattern. An experimental methodology was used, comparing two iOS apps: one with monolithic and one with modular architecture. Both apps were built using similar technologies and then tested using the Xcode Instruments testing tool. The research hypothesis argues that non-modular applications perform better than modularized applications.
