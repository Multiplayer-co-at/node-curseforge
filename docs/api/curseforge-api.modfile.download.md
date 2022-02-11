<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [curseforge-api](./curseforge-api.md) &gt; [ModFile](./curseforge-api.modfile.md) &gt; [download](./curseforge-api.modfile.download.md)

## ModFile.download() method

Download this \[\[ModFile\]\]

<b>Signature:</b>

```typescript
download(path: PathLike, verify?: boolean): Promise<boolean>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  path | PathLike | The path where the file should be saved. |
|  verify | boolean | Should the downloaded files hash be checked? |

<b>Returns:</b>

Promise&lt;boolean&gt;

the Promise resolves with true if download was successful and the hash fits (if verify is true.) returns false otherwise.
