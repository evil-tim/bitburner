<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [NS](./bitburner.ns.md) &gt; [hackAnalyze](./bitburner.ns.hackanalyze.md)

## NS.hackAnalyze() method

Get the percent of money stolen with a single thread.

<b>Signature:</b>

```typescript
hackAnalyze(host: string): number;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  host | string | Hostname of the target server. |

<b>Returns:</b>

number

The percentage of money you will steal from the target server with a single hack.

## Remarks

RAM cost: 1 GB

Returns the percentage of the specified server’s money you will steal with a single hack. This value is returned in percentage form, not decimal (Netscript functions typically return in decimal form, but not this one).

## Example


```ts
//For example, assume the following returns 1:
hackAnalyze("foodnstuff");
//This means that if hack the foodnstuff server, then you will steal 1% of its total money. If you hack using N threads, then you will steal N% of its total money.
```
