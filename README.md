# cls-zlib

**cls-zlib** is an implementation of the **zlib** compression algorithm as a CLS filter for **FreeArc**.

Based on **zlib version 1.3.1** from the official website:  
https://zlib.net

---

## Parameters

| Parameter | Description |
|------------|------------|
| `l=[N]` | Compression level `0–9` |
| `m=[N]` | Memory level `1–9` |
| `w=[N]` | Window bits `8–15` |

---

## Example

```cmd
arc.exe a -s -r -m=zlib:l=9:m=9:w=15 data.arc packeddata\*
```

---

## Support the Project

[![Support on Patreon](https://c5.patreon.com/external/logo/become_a_patron_button.png)](https://www.patreon.com/Shegorat)

If you find this project useful, consider supporting development on Patreon.


<p align="center">
  Development of FreeArc filters and related tools is supported by the community.
</p>
