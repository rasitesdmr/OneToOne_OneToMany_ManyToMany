# İLİŞKİLER ?

<img src="https://github.com/rasitesdmr/OneToOne_OneToMany_ManyToMany/blob/master/images/iliskiler.png">

## 1-) users / users_details
* Aralarında One To One ilişkisi vardır .
* Bir kullanıcının (users) bir tane detayı (details) vardır.
* Bir detay (details) ise sadece bir kullanıcıya (user) ait olabilir.

## 2-) users / articles
* Aralarında One To Many ilişkisi vardır.
* Bir kullanıcının (users) birden fazla makalesi (articles) olabilir.
* Fakat bir makale (articles) sadece bir kullanıcıya ait olabilir.

## 3-) articles / categories
* Aralarında One To Many ilişkisi vardır.
* Bir kategorinin (categories) birden fazla makalesi (articles) olabilir.
* Fakat bir makalenin (article) sadece bir kategorisi (categories) olabilir.

## 4-) article / tags
* Aralarında Many To Many ilişkisi vardır.
* Bu iki tablo arasındaki ilişkiyi kuramıyoruz .
* Onun için bir tane ara tabloya ihtiyacımız var.
* Bir makalenin (article) birden çok etiketi (tags) olabilir.
* Bir etiketinde (tags) birden çok makalesi (article) olabilir.

## 5-) article / comments
* Aralarında One To Many ilişkisi vardır.
* Bir makalenin (article) birden çok yorumu (comments) olabilir.
* Ama bir yorum (comments) sadece bir tane makaleye (article) ait olabilir.

## 6-) users / comments
* Aralarında One To Many ilişkisi vardır.
* Bir kullanıcının (users) birden çok yorumu (comments) olabilir.
* Ancak bir yorum (comments) sadece tek bir kullanıcıya (users) aittir.

## 7-) users / article_likes
* Şimdi gelelim kullanıcının makaleyi beğenmesine .
* Aralarında Many To Many ilişkisi vardır.
* Bir kullanıcı (users) birden çok makaleyi (article) beğenebilir.
* Aynı şekilde bir makalede (article) birden çok kullanıcı (users) tarafından beğenilebilir.

## 8-) users / users_fallows
* Şimdi gelelim takip işine.
* Tabloda karmaşıklık olmasın diye çizmedim.
* Aralarında Many To Many ilişkisi vardır.
* Bir kullanıcı birden fazla kişiyi takip edebilir.
* Aynı şekilde bir kullanıcı birden fazla kişi tarafından takip edilebilir .
