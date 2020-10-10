# TestRecyclerViewCrash
Reproduct recyclerView crash when add header and notifiy item 0.

Releative to #2907
https://github.com/CymChad/BaseRecyclerViewAdapterHelper/issues/2907


# How to reproduct
Look at `pokercc/android/testrecyclerviewcrash/MainActivity.kt` line 71
```kotlin
// ATTENTION : If test crash ,please extends to BaseQuickAdapter.
private class TestAdapter : FixBaseAdapter<Int, TestVH>(View.NO_ID)
```