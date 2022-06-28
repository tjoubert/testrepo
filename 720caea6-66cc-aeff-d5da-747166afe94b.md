# GraphApiClient.PostVertexCollectionAsync Method 
 

Adds a vertex collection to the set of orphan collections of the graph. If the collection does not exist, it will be created. POST /_api/gharial/{graph}/vertex

**Namespace:**&nbsp;<a href="5db3e172-88fa-722f-6e7f-25b7310b3db3">ArangoDBNetStandard.GraphApi</a><br />**Assembly:**&nbsp;ArangoDBNetStandard (in ArangoDBNetStandard.dll) Version: 1.1.0

## Syntax

**C#**<br />
``` C#
public virtual Task<PostVertexCollectionResponse> PostVertexCollectionAsync(
	string graphName,
	PostVertexCollectionBody body
)
```

**VB**<br />
``` VB
Public Overridable Function PostVertexCollectionAsync ( 
	graphName As String,
	body As PostVertexCollectionBody
) As Task(Of PostVertexCollectionResponse)
```

**C++**<br />
``` C++
public:
virtual Task<PostVertexCollectionResponse^>^ PostVertexCollectionAsync(
	String^ graphName, 
	PostVertexCollectionBody^ body
)
```

**F#**<br />
``` F#
abstract PostVertexCollectionAsync : 
        graphName : string * 
        body : PostVertexCollectionBody -> Task<PostVertexCollectionResponse> 
override PostVertexCollectionAsync : 
        graphName : string * 
        body : PostVertexCollectionBody -> Task<PostVertexCollectionResponse> 
```


#### Parameters
&nbsp;<dl><dt>graphName</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">System.String</a><br />The name of the graph.</dd><dt>body</dt><dd>Type: <a href="286f4e92-a4dd-c8f6-f486-709261fa0e30">ArangoDBNetStandard.GraphApi.Models.PostVertexCollectionBody</a><br />The information of the vertex collection.</dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.threading.tasks.task-1" target="_blank" rel="noopener noreferrer">Task</a>(<a href="4227cb5c-169c-4c9e-929b-f0d19a12cb57">PostVertexCollectionResponse</a>)<br />\[Missing <returns> documentation for "M:ArangoDBNetStandard.GraphApi.GraphApiClient.PostVertexCollectionAsync(System.String,ArangoDBNetStandard.GraphApi.Models.PostVertexCollectionBody)"\]

#### Implements
<a href="6d814aad-dde7-5879-0375-4c098961a704">IGraphApiClient.PostVertexCollectionAsync(String, PostVertexCollectionBody)</a><br />

## See Also


#### Reference
<a href="fbeb06c2-7ca5-a17a-b0c2-96abac64dfaa">GraphApiClient Class</a><br /><a href="5db3e172-88fa-722f-6e7f-25b7310b3db3">ArangoDBNetStandard.GraphApi Namespace</a><br />