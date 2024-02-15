Proje Yapısına Genel Bakış
Svelte projeniz, kullanıcı kimlik doğrulaması, gezinme ve durum yönetimi gibi bir web uygulaması için çok önemli olan çeşitli temel bileşenleri ve işlevleri içeriyor gibi görünüyor. Bu bileşenlerin neler içerebileceğine ilişkin genel bir bakış aşağıda verilmiştir:

Login.svelte: Kullanıcı oturum açma arayüzünü ve mantığını yönetir.
PrivateRoute.svelte&PrivateRouteGuard.svelte : Yönlendirme ve erişim kontrolünü yöneterek yalnızca kimliği doğrulanmış kullanıcıların uygulamanın belirli bölümlerine erişebilmesini sağlayın.
stores.js: Kullanıcı kimlik doğrulama durumu da dahil olmak üzere genel durumu yönetir.
App.svelte: Svelte uygulamasının ana giriş noktası, uygulamanın düzenini ve yönlendirmesini düzenler.
Counter.svelte: Muhtemelen Svelte'de durum yönetimini ve tepkiselliği gösteren örnek bir bileşen.
main.js: Ana uygulama bileşenini ( ) ayarlayarak App.svelteve muhtemelen ilk yapılandırmayı yöneterek uygulamayı önyükler.
app.css: Uygulamaya yönelik genel stilleri içerir.
