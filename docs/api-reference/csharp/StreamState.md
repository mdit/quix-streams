#### [QuixStreams.Streaming](index.md 'index')
### [QuixStreams.Streaming.States](QuixStreams.Streaming.States.md 'QuixStreams.Streaming.States')

## StreamState Class

Represents a dictionary-like storage of key-value pairs with a specific topic and storage name.

```csharp
public class StreamState :
System.Collections.Generic.IDictionary<string, QuixStreams.State.StateValue>,
System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<string, QuixStreams.State.StateValue>>,
System.Collections.Generic.IEnumerable<System.Collections.Generic.KeyValuePair<string, QuixStreams.State.StateValue>>,
System.Collections.IEnumerable,
System.Collections.IDictionary,
System.Collections.ICollection
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; StreamState

Implements [System.Collections.Generic.IDictionary&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IDictionary-2 'System.Collections.Generic.IDictionary`2')[System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')[,](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IDictionary-2 'System.Collections.Generic.IDictionary`2')[QuixStreams.State.StateValue](https://docs.microsoft.com/en-us/dotnet/api/QuixStreams.State.StateValue 'QuixStreams.State.StateValue')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IDictionary-2 'System.Collections.Generic.IDictionary`2'), [System.Collections.Generic.ICollection&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.ICollection-1 'System.Collections.Generic.ICollection`1')[System.Collections.Generic.KeyValuePair&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.KeyValuePair-2 'System.Collections.Generic.KeyValuePair`2')[System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')[,](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.KeyValuePair-2 'System.Collections.Generic.KeyValuePair`2')[QuixStreams.State.StateValue](https://docs.microsoft.com/en-us/dotnet/api/QuixStreams.State.StateValue 'QuixStreams.State.StateValue')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.KeyValuePair-2 'System.Collections.Generic.KeyValuePair`2')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.ICollection-1 'System.Collections.Generic.ICollection`1'), [System.Collections.Generic.IEnumerable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1')[System.Collections.Generic.KeyValuePair&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.KeyValuePair-2 'System.Collections.Generic.KeyValuePair`2')[System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')[,](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.KeyValuePair-2 'System.Collections.Generic.KeyValuePair`2')[QuixStreams.State.StateValue](https://docs.microsoft.com/en-us/dotnet/api/QuixStreams.State.StateValue 'QuixStreams.State.StateValue')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.KeyValuePair-2 'System.Collections.Generic.KeyValuePair`2')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1'), [System.Collections.IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerable 'System.Collections.IEnumerable'), [System.Collections.IDictionary](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IDictionary 'System.Collections.IDictionary'), [System.Collections.ICollection](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.ICollection 'System.Collections.ICollection')

| Methods | |
| :--- | :--- |
| [Flush()](StreamState.Flush().md 'QuixStreams.Streaming.States.StreamState.Flush()') | Flushes the changes made to the in-memory state to the specified storage. |
| [Reset()](StreamState.Reset().md 'QuixStreams.Streaming.States.StreamState.Reset()') | Reset the state to before in-memory modifications |

| Events | |
| :--- | :--- |
| [OnFlushed](StreamState.OnFlushed.md 'QuixStreams.Streaming.States.StreamState.OnFlushed') | Raised immediately after a flush operation is completed. |
| [OnFlushing](StreamState.OnFlushing.md 'QuixStreams.Streaming.States.StreamState.OnFlushing') | Raised immediately before a flush operation is performed. |
