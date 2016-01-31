开发原因：记得曾经工作时，大量copy重复代码，作curd等一些事情，很讨厌，于是就想，能不能只写一套东西去自动适应或自由随意开发而不再重复轮子呢？

开发目的：在现在技术框架基础上，进行松耦，可以使程序员自己任意去调整细节或架构。作一个核心，后来者可以在其核心上任意的插拔与改进。

开发理念：自由，松耦，智能，便捷。

已实现功能：curd，统计，报表，用户，权限，配置等。

实现方式：Extjs + Ajax4jsf + JSF + Spring + Hibernate + iReport + Jasperreport，待改进。

实现详解：Extjs可以作到类似金蝶中间件的效果，实际上金蝶也是在用Extjs，只不过他把Extjs封装成JSF组件了。但这个更方便，因为松耦，不是强制性，一个参数就可以控制是否需要Extjs效果。
Ajax4jsf用来实现ajax效果。
JSF(sun ri)用来实现前台展示页面，用户可以根据需要替换任何JSF实现，包括richFaces，Myfaces等。
Spring地球程序员都知道了。
Hibernate持久化处理。
iReport + Jasperreport报表设计。