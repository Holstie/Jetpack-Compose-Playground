# Card

!!! info
    This is the API of version alpha01. Newer versions may have a different one

Card is the implementation of a CardView in Compose

```kotlin
 @Composable fun CardDemo(){
        Card(Modifier.fillMaxWidth().then(Modifier.padding(8.dp)),elevation = 8.dp){
            Text("This is a Card")
        }
    }
```

<p align="left">
  <img src ="../../images/material/card/carddemo.png"  />
</p>