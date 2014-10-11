# Introduction
Forked from [plidea](https://github.com/Polidea/tree-view-list-android).

This is a small widget that provides quite configurable tree view list.
It is based on standard android list view.
Note that using generic tree is probably not the best approach for Android (or any other mobile) UI.
See [http://developer.android.com/design/index.html](http://developer.android.com/design/index.html)
for all the control that it makes sense to use. Thus tree view should be considered as deprecated.
The widget is fully configurable - with your custom adapter you can provide
your own implementation of the item views - even completely different implementation
of item views depending on the tree level you are at.
Implementation follows best approach of Adapters from android
so views at the same tree level are reusable.


# Usage

* for gradle
``` groovy
compile 'org.quanqi:tree_list_view:<Latest_VERSION>'
```