# PostIndexBody.InBackground Property 
 

Can be set to true to create the index in the background, which will not write-lock the underlying collection for as long as if the index is built in the foreground.

**Namespace:**&nbsp;<a href="215740c9-85fc-74fa-998d-14b49b842d56">ArangoDBNetStandard.IndexApi.Models</a><br />**Assembly:**&nbsp;ArangoDBNetStandard (in ArangoDBNetStandard.dll) Version: 1.1.0

## Syntax

**C#**<br />
``` C#
public bool? InBackground { get; set; }
```

**VB**<br />
``` VB
Public Property InBackground As Boolean?
	Get
	Set
```

**C++**<br />
``` C++
public:
property Nullable<bool> InBackground {
	Nullable<bool> get ();
	void set (Nullable<bool> value);
}
```

**F#**<br />
``` F#
member InBackground : Nullable<bool> with get, set

```


#### Property Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.nullable-1" target="_blank" rel="noopener noreferrer">Nullable</a>(<a href="https://docs.microsoft.com/dotnet/api/system.boolean" target="_blank" rel="noopener noreferrer">Boolean</a>)

## See Also


#### Reference
<a href="f5a253b1-a29a-4d26-d18f-bf7a5868277f">PostIndexBody Class</a><br /><a href="215740c9-85fc-74fa-998d-14b49b842d56">ArangoDBNetStandard.IndexApi.Models Namespace</a><br />