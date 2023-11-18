# Youtube JavaScript AdBlocker

#Stage 1 :
Open DevTools->Console (Inspect)

#Stage 2 :
Paste And Run JS Code 

```
function adblockerbygza(){
    try
    {
        document.querySelector('.ytp-ad-skip-button-modern.ytp-button').click();
    }catch{}
    setTimeout(adblockerbygza,200);
}
adblockerbygza();
```
