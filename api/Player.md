# Player

## bool HasItemCount(uint32 ItemId, uint32 ItemCount, bool CheckBank)

## void SetTitle(CharTitlesEntry const* TitleInfo, bool Remove)
### Example
```c++
  int32 id = 0;
  CharTitlesEntry const* titleInfo = sCharTitlesStore.LookupEntry(id);

  if(titleInfo) {
    player->SetTitle(titleInfo);
  }
```
