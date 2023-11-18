# Youtube JavaScript AdBlocker

#Stage 1 :
Open Inspect->DevTools->Console

#Stage 2 :
Paste And Run JS Code 

```
function adblockerbygza(){
if (document.readyState == "complete") {
    try
    {
        document.querySelector('.ytp-ad-skip-button-modern.ytp-button').click();
    }catch{}
    setTimeout(adblockerbygza,200);
}else{
setTimeout(adblockerbygza,2000);
}
}
adblockerbygza();
```
