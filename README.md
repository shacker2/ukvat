# ukvat
Applu UK new VAT fix for orders more than 135gbp



With the new tax rule imposed for the UK, which applies VAT only if the amount is greater than 135GBP, we need to modify some things in our PrestaShop to comply with the norm.

First we will have to have the VAT correctly configured.
The next thing is to modify the file Src / Adapter / Presenter / Cart / CartPresenter.php (sometimes it is in Src / Adapter / Presenter). This file have all teh modificationes.


