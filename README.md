# Learn-Kotlin

## ArrayList to StringArray

```
val arrayList = arrayListOf() //ArrayList

arrayList.toTypedArray() //To String Array

```
## Intialize with default value Kotlin Extension

```
class GiveName{
  var maxValue = MutableLiveData<Int>().default(100)
}

//Outside the class
private fun <T : Any?> MutableLiveData<T>.default(value: T) = apply {
    setValue(value)
}

```
