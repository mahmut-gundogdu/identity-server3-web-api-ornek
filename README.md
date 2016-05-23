identity server3 frameworkunu kullanarak web abi token based auth örneği.
Örnekte 3 tane proje vardır.

1. IdentityserverConsoleApp isimli self-host owin console app. bu bizim İdetity serverimiz. identityserver3 kutupanesini kullanıyor.

2. IdentityServerWebApi2 isimli proje bir asp.net web api 2.0 ve oturum açmak için token gerektiriyor bu tokeni de  IdentityserverConsoleApp projesi sağlıyor

3. TestEtmekicin isimli proje un identity serverda toketni alıp web api den istekte bulunuyor. Bu 3. proje olmasa da olurdu postman ile de test yapabilirdik 
