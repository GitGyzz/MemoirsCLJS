---
categories: WPF
---

# Dispatcher

线程管理器,是个单例.

由于线程安全，在WPF中不可以在子线程中直接调用UI空间。只能在Dispatcher.Invoke()中调用.
