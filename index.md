## DataRenderer2D

It is a simple drawing tool. Fully compatible with Animator.

![dataRenderer](https://github.com/geniikw/drawLine/raw/master/logoExample.gif)

[AssetStore](https://assetstore.unity.com/packages/tools/modeling/data-renderer-2d-102377) [Github](https://github.com/geniikw/DataRenderer2D)


## DataSheetLab

It is a tool to manage data like Sheet in Unity3d editor.

![datasheetlab](https://d2ujflorbtfzji.cloudfront.net/key-image/183ca6a9-0e40-45f7-95d9-fa862321e5bb.jpg)

[AssetStore](https://assetstore.unity.com/packages/tools/utilities/datasheetlab-118157) [Detail](https://github.com/geniikw/DataSheetLab-Info)


## CoroutineChain

A plugin that cascades a series of coroutines.

```csharp
private void Start(){
  CoroutineChain.Start
                .Play(MoveTo(new Vector3(0,100,0))
                .Parellel(A(),B(),C());
                .Call(()=>Debug.Log("all done!"));
}
```

[AssetStore](https://assetstore.unity.com/packages/tools/input-management/coroutinechain-109785) [github](https://github.com/geniikw/CoroutineChain)

