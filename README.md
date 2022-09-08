<p align="center">
  <a href="https://fastapi.tiangolo.com"><img src="https://fastapi.tiangolo.com/img/logo-margin/logo-teal.png" alt="FastAPI"></a>
</p>
<p align="center">
    <em>FastAPI çerçevesi, yüksek performans, öğrenmesi kolay, kodlaması hızlı, üretime hazır</em>
</p>
<p align="center">
<a href="https://github.com/tiangolo/fastapi/actions?query=workflow%3ATest+event%3Apush+branch%3Amaster" target="_blank">
    <img src="https://github.com/tiangolo/fastapi/workflows/Test/badge.svg?event=push&branch=master" alt="Test">
</a>
<a href="https://codecov.io/gh/tiangolo/fastapi" target="_blank">
    <img src="https://img.shields.io/codecov/c/github/tiangolo/fastapi?color=%2334D058" alt="Coverage">
</a>
<a href="https://pypi.org/project/fastapi" target="_blank">
    <img src="https://img.shields.io/pypi/v/fastapi?color=%2334D058&label=pypi%20package" alt="Package version">
</a>
<a href="https://pypi.org/project/fastapi" target="_blank">
    <img src="https://img.shields.io/pypi/pyversions/fastapi.svg?color=%2334D058" alt="Supported Python versions">
</a>
</p>

---

**Belgeler**: <a href="https://fastapi.tiangolo.com" target="_blank">https://fastapi.tiangolo.com</a>

**Kaynak kodu**: <a href="https://github.com/tiangolo/fastapi" target="_blank">https://github.com/tiangolo/fastapi</a>

---

FastAPI, standart Python türü ipuçlarına dayalı Python 3.6+ ile API'ler oluşturmaya yönelik modern, hızlı (yüksek performanslı) bir web çerçevesidir.

Temel özellikler şunlardır:

* **Hızlı**: **NodeJS** ve **Go** ile eşit düzeyde çok yüksek performans. [Mevcut en hızlı Python framework'lerinden biri](#performance).
* **Hızlı kodlama**: Özellikleri geliştirme hızını yaklaşık %200 ila %300 artırın. *
* **Daha az hata**: İnsan (geliştirici) kaynaklı hataların yaklaşık %40'ını azaltın. *
* **Sezgisel**:Harika editör desteği. <abbr title="also known as auto-complete, autocompletion, IntelliSense">tamamlama</abbr> her yerde. Daha az zaman hata ayıklama.
* **Kolay**:Kullanımı ve öğrenmesi kolay olacak şekilde tasarlanmıştır. Dokümanları okumak için daha az zaman.
* **Kısa**: Kod tekrarını en aza indirin. Her parametre bildiriminden birden çok özellik. Daha az hata.
* **Sağlam**: Üretime hazır kod alın. Otomatik etkileşimli belgelerle.
* **Standartlara dayalı**: API'ler için açık standartları temel alır (ve bunlarla tamamen uyumludur):<a href="https://github.com/OAI/OpenAPI-Specification" class="external-link" target="_blank">OpenAPI</a> (önceden Swagger olarak biliniyordu) ve <a href="https://json-schema.org/" class="external-link" target="_blank">JSON Şeması</a>.

<small>* üretim uygulamaları oluşturan dahili bir geliştirme ekibindeki testlere dayalı tahmin.</small>

## Sponsorlar

<!-- sponsors -->

<a href="https://bit.ly/3dmXC5S" target="_blank" title="The data structure for unstructured multimodal data"><img src="https://fastapi.tiangolo.com/img/sponsors/docarray.svg"></a>
<a href="https://bit.ly/3JJ7y5C" target="_blank" title="Build cross-modal and multimodal applications on the cloud"><img src="https://fastapi.tiangolo.com/img/sponsors/jina2.svg"></a>
<a href="https://cryptapi.io/" target="_blank" title="CryptAPI: Your easy to use, secure and privacy oriented payment gateway."><img src="https://fastapi.tiangolo.com/img/sponsors/cryptapi.svg"></a>
<a href="https://doist.com/careers/9B437B1615-wa-senior-backend-engineer-python" target="_blank" title="Help us migrate doist to FastAPI"><img src="https://fastapi.tiangolo.com/img/sponsors/doist.svg"></a>
<a href="https://www.deta.sh/?ref=fastapi" target="_blank" title="The launchpad for all your (team's) ideas"><img src="https://fastapi.tiangolo.com/img/sponsors/deta.svg"></a>
<a href="https://www.investsuite.com/jobs" target="_blank" title="Wealthtech jobs with FastAPI"><img src="https://fastapi.tiangolo.com/img/sponsors/investsuite.svg"></a>
<a href="https://training.talkpython.fm/fastapi-courses" target="_blank" title="FastAPI video courses on demand from people you trust"><img src="https://fastapi.tiangolo.com/img/sponsors/talkpython.png"></a>
<a href="https://testdriven.io/courses/tdd-fastapi/" target="_blank" title="Learn to build high-quality web apps with best practices"><img src="https://fastapi.tiangolo.com/img/sponsors/testdriven.svg"></a>
<a href="https://github.com/deepset-ai/haystack/" target="_blank" title="Build powerful search from composable, open source building blocks"><img src="https://fastapi.tiangolo.com/img/sponsors/haystack-fastapi.svg"></a>
<a href="https://www.udemy.com/course/fastapi-rest/" target="_blank" title="Learn FastAPI by building a complete project. Extend your knowledge on advanced web development-AWS, Payments, Emails."><img src="https://fastapi.tiangolo.com/img/sponsors/ines-course.jpg"></a>
<a href="https://careers.budget-insight.com/" target="_blank" title="Budget Insight is hiring!"><img src="https://fastapi.tiangolo.com/img/sponsors/budget-insight.svg"></a>

<!-- /sponsors -->

<a href="https://fastapi.tiangolo.com/fastapi-people/#sponsors" class="external-link" target="_blank">Other sponsors</a>

## Görüşler

"_[...] Bu günlerde bir ton **FastAPI** kullanıyorum. [...] Aslında bunu ekibimin Microsoft**'taki tüm **ML hizmetleri için kullanmayı planlıyorum. temel **Windows** ürününe ve bazı **Office** ürünlerine entegre oluyorlar._"

<div style="text-align: right; margin-right: 10%;">Kabir Khan - <strong>Microsoft</strong> <a href="https://github.com/tiangolo/fastapi/pull/26" target="_blank"><small>(ref)</small></a></div>

---

"_**FastAPI** kitaplığını, **tahminler** elde etmek için sorgulanabilecek bir **REST** sunucusu oluşturmak için benimsedik. [Ludwig için]_"

<div style="text-align: right; margin-right: 10%;">Piero Molino, Yaroslav Dudin, and Sai Sumanth Miryala - <strong>Uber</strong> <a href="https://eng.uber.com/ludwig-v0-2/" target="_blank"><small>(ref)</small></a></div>

---

"_**Netflix**, **kriz yönetimi** düzenleme çerçevemizin açık kaynaklı sürümünü duyurmaktan mutluluk duyar: **Dispatch**! [**FastAPI** ile oluşturulmuştur]_"

<div style="text-align: right; margin-right: 10%;">Kevin Glisson, Marc Vilanova, Forest Monsen - <strong>Netflix</strong> <a href="https://netflixtechblog.com/introducing-dispatch-da4b8a2a8072" target="_blank"><small>(ref)</small></a></div>

---

"_**FastAPI** için çok heyecanlıyım. Çok eğlenceli!_"

<div style="text-align: right; margin-right: 10%;">Brian Okken - <strong><a href="https://pythonbytes.fm/episodes/show/123/time-to-right-the-py-wrongs?time_in_sec=855" target="_blank">Python Baytları</a> podcast sunucusu</strong> <a href="https://twitter.com/brianokken/status/1112220079972728832" target="_blank"><small>(ref)</small></a></div>

---

"_Dürüst olmak gerekirse, yaptığın şey süper sağlam ve gösterişli görünüyor. Birçok yönden, **Sarılmak** olmasını istediğim şey buydu - birinin bunu yaptığını görmek gerçekten ilham verici._"

<div style="text-align: right; margin-right: 10%;">Timothy Crosley - <strong><a href="https://www.hug.rest/" target="_blank">Hug</a> creator</strong> <a href="https://news.ycombinator.com/item?id=19455465" target="_blank"><small>(ref)</small></a></div>

---

"REST API'leri oluşturmak için bir **modern çerçeve** öğrenmek istiyorsanız, **FastAPI**'ye göz atın [...] Hızlı, kullanımı kolay ve öğrenmesi kolay [...]_"

"_**API'lerimiz** için **FastAPI**'ye geçtik [...] Beğeneceğinizi düşünüyorum [...]_"

<div style="text-align: right; margin-right: 10%;">Ines Montani - Matthew Honnibal - <strong><a href="https://explosion.ai" target="_blank">Explosion AI</a> founders - <a href="https://spacy.io" target="_blank">spaCy</a> creators</strong> <a href="https://twitter.com/_inesmontani/status/1144173225322143744" target="_blank"><small>(ref)</small></a> - <a href="https://twitter.com/honnibal/status/1144031421859655680" target="_blank"><small>(ref)</small></a></div>

---

## **Typer**, CLI'lerin FastAPI'si

<a href="https://typer.tiangolo.com" target="_blank"><img src="https://typer.tiangolo.com/img/logo-margin/logo-margin-vector.svg" style="width: 20%;"></a>

Eğer bir bina yapıyorsanız <abbr title="Command Line Interface">CLI</abbr> bir web API'si yerine terminalde kullanılacak uygulama, kontrol edin <a href="https://typer.tiangolo.com/" class="external-link" target="_blank">**Typer**</a>.

**Typer** FastAPI'nin küçük kardeşidir. Ve **CLI'lerin FastAPI'si** olması amaçlanmıştır. ⌨️ 🚀

## Gereksinimler

Python 3.6+

FastAPI devlerin omuzlarında duruyor:

* <a href="https://www.starlette.io/" class="external-link" target="_blank">Starlette</a> for the web parts.
* <a href="https://pydantic-docs.helpmanual.io/" class="external-link" target="_blank">Pydantic</a> for the data parts.

## Kurulum

<div class="termy">

```console
$ pip install fastapi

---> 100%
```

</div>

Ayrıca üretim için bir ASGI sunucusuna ihtiyacınız olacak. <a href="https://www.uvicorn.org" class="external-link" target="_blank">Uvicorn</a> veya <a href="https://github.com/pgjones/hypercorn" class="external-link" target="_blank">Hypercorn</a>.

<div class="termy">

```console
$ pip install "uvicorn[standard]"

---> 100%
```

</div>

## Örnek

### Oluştur

* Şunlarla bir "main.py" dosyası oluşturun:

```Python
from typing import Union

from fastapi import FastAPI

app = FastAPI()


@app.get("/")
def read_root():
    return {"Hello": "World"}


@app.get("/items/{item_id}")
def read_item(item_id: int, q: Union[str, None] = None):
    return {"item_id": item_id, "q": q}
```

<details markdown="1">
<summary>Or use <code>async def</code>...</summary>

If your code uses `async` / `await`, use `async def`:

```Python hl_lines="9  14"
from typing import Union

from fastapi import FastAPI

app = FastAPI()


@app.get("/")
async def read_root():
    return {"Hello": "World"}


@app.get("/items/{item_id}")
async def read_item(item_id: int, q: Union[str, None] = None):
    return {"item_id": item_id, "q": q}
```

**Not**:

Bilmiyorsanız, hakkında _"Aceleniz mi var?"_ bölümüne bakın. <a href="https://fastapi.tiangolo.com/async/#in-a-hurry" target="_blank">dokümanlarda "async" ve "await"</a>.

</details>

### Çalıştır

Sunucuyu şununla çalıştırın:

<div class="termy">

```console
$ uvicorn main:app --reload

INFO:     Uvicorn running on http://127.0.0.1:8000 (Press CTRL+C to quit)
INFO:     Started reloader process [28720]
INFO:     Started server process [28722]
INFO:     Waiting for application startup.
INFO:     Application startup complete.
```

</div>

<details markdown="1">
<summary>Komut hakkında <code>uvicorn main:uygulama -- yeniden yükle</code>...</summary>

"uvicorn main:app" komutu şu anlama gelir:

* `main`: the file `main.py` (the Python "module").
* `app`: the object created inside of `main.py` with the line `app = FastAPI()`.
* `--reload`: make the server restart after code changes. Only do this for development.

</details>

### Kontrol et

Tarayıcınızı şuradan açın: <a href="http://127.0.0.1:8000/items/5?q=somequery" class="external-link" target="_blank">http://127.0.0.1:8000/items/5?q=somequery</a>.

JSON yanıtını şu şekilde göreceksiniz:

```JSON
{"item_id": 5, "q": "somequery"}
```

Zaten bir API oluşturdunuz:

* _paths_ `/` ve `/items/{item_id}` içindeki HTTP isteklerini alır.
* Both _paths_ take `GET` <em>operasyonlar</em> (HTTP _methods_ olarak da bilinir).
* _path_ "/items/{item_id}", "int" olması gereken bir _path parametresi_ "item_id"ye sahiptir.
* _path_ `/items/{item_id}`, isteğe bağlı bir `str` _query parametresi_ `q` içerir.

### Etkileşimli API belgeleri

şimdi git <a href="http://127.0.0.1:8000/docs" class="external-link" target="_blank">http://127.0.0.1:8000/docs</a>.

Otomatik etkileşimli API belgelerini göreceksiniz (tarafından sunulan <a href="https://github.com/swagger-api/swagger-ui" class="external-link" target="_blank">Swagger Kullanıcı Arayüzü</a>):

![Swagger UI](https://fastapi.tiangolo.com/img/index/index-01-swagger-ui-simple.png)

### Alternatif API belgeleri

Ve şimdi git <a href="http://127.0.0.1:8000/redoc" class="external-link" target="_blank">http://127.0.0.1:8000/redoc</a>.

Alternatif otomatik belgeleri göreceksiniz(tarafından sunulan<a href="https://github.com/Rebilly/ReDoc" class="external-link" target="_blank">yeniden belge</a>):

![ReDoc](https://fastapi.tiangolo.com/img/index/index-02-redoc-simple.png)

## Örnek yükseltme

Şimdi bir 'PUT' isteğinden bir gövde almak için 'main.py' dosyasını değiştirin.

Pydantic sayesinde standart Python türlerini kullanarak gövdeyi bildirin.

```Python hl_lines="4  9-12  25-27"
from typing import Union

from fastapi import FastAPI
from pydantic import BaseModel

app = FastAPI()


class Item(BaseModel):
    name: str
    price: float
    is_offer: Union[bool, None] = None


@app.get("/")
def read_root():
    return {"Hello": "World"}


@app.get("/items/{item_id}")
def read_item(item_id: int, q: Union[str, None] = None):
    return {"item_id": item_id, "q": q}


@app.put("/items/{item_id}")
def update_item(item_id: int, item: Item):
    return {"item_name": item.name, "item_id": item_id}
```

Sunucu otomatik olarak yeniden yüklenmelidir (çünkü yukarıdaki "uvicorn" komutuna "--reload" eklediniz).

###Etkileşimli API dokümanları yükseltmesi

şimdi git <a href="http://127.0.0.1:8000/docs" class="external-link" target="_blank">http://127.0.0.1:8000/docs</a>.

* Etkileşimli API belgeleri, yeni gövde de dahil olmak üzere otomatik olarak güncellenecektir:

![Swagger UI](https://fastapi.tiangolo.com/img/index/index-03-swagger-02.png)

* "Dene" düğmesine tıklayın, parametreleri doldurmanıza ve doğrudan API ile etkileşime girmenize olanak tanır:

![Swagger UI interaction](https://fastapi.tiangolo.com/img/index/index-04-swagger-03.png)

*Ardından "Yürüt" düğmesine tıklayın, kullanıcı arayüzü API'niz ile iletişim kuracak, parametreleri gönderecek, sonuçları alacak ve bunları ekranda gösterecektir:

![Swagger UI interaction](https://fastapi.tiangolo.com/img/index/index-05-swagger-04.png)

### Alternatif API dokümanları yükseltmesi

And now, go to <a href="http://127.0.0.1:8000/redoc" class="external-link" target="_blank">http://127.0.0.1:8000/redoc</a>.

* Alternatif belgeler, yeni sorgu parametresini ve gövdesini de yansıtacaktır:

![ReDoc](https://fastapi.tiangolo.com/img/index/index-06-redoc-02.png)

### Özet

Özetle, parametre, gövde vb. türlerini **bir kez** işlev parametreleri olarak bildirirsiniz.

Bunu standart modern Python türleriyle yaparsınız.

Yeni bir sözdizimi, belirli bir kitaplığın yöntemlerini veya sınıflarını vb. öğrenmeniz gerekmez.

Sadece standart **Python 3.6+**.

Örneğin, bir "int" için:

```Python
item_id: int
```

veya daha karmaşık bir "Öğe" modeli için:

```Python
item: Item
```

... ve bu tek beyanla şunları elde edersiniz:

* Aşağıdakiler dahil editör desteği:
     * Tamamlama.
     * Tip kontrolleri.
* Verilerin doğrulanması:
     * Veriler geçersiz olduğunda otomatik ve net hatalar.
     * Derinlemesine yuvalanmış JSON nesneleri için bile doğrulama.
* <abbr title="also known as: serialization, parsing, marshalling">Dönüştürmek</abbr>girdi verilerinin sayısı: ağdan Python verisine ve türlerine geliyor. Şuradan okuma:
     *JSON.
     * Yol parametreleri.
     * Sorgu parametreleri.
     * Cookies.
     * Başlıklar.
     * Formlar.
     * Dosyalar.
* <abbr title="also known as: serialization, parsing, marshalling">Dönüştürmek</abbr> çıktı verilerinin sayısı: Python verilerinden ve türlerinden ağ verilerine dönüştürme (JSON olarak):
    * Python türlerini dönüştürme(`str`, `int`, `float`, `bool`, `list`, etc).
    * 'datetime' nesneleri.
    * "UUID" nesneleri.
    * Veritabanı modelleri.
    * ...ve daha fazlası.
* Automatic interactive API documentation, including 2 alternative user interfaces:
    * Swagger kullanıcı arayüzü.
    * ReDoc.

---

Önceki kod örneğine dönersek, **FastAPI** şunları yapacaktır:

* "GET" ve "PUT" isteklerinin yolunda bir "item_id" olduğunu doğrulayın.
* "item_id"nin "GET" ve "PUT" istekleri için "int" türünde olduğunu doğrulayın.
    * Değilse, istemci yararlı, net bir hata görecektir.
* "GET" istekleri için "q" adlı isteğe bağlı bir sorgu parametresi olup olmadığını kontrol edin ('http://127.0.0.1:8000/items/foo?q=somequery'de olduğu gibi).
    * 'q' parametresi '= None' ile bildirildiğinden isteğe bağlıdır.
    * "Hiçbiri" olmadan gerekli olacaktır ("PUT" durumunda gövde olduğu gibi).
* '/items/{item_id}' için 'PUT' istekleri için, Gövdeyi JSON olarak okuyun:
    * Bir "str" olması gereken gerekli bir "ad" özniteliğine sahip olup olmadığını kontrol edin.
    * Bir "değişken" olması gereken zorunlu bir "fiyat" özniteliğine sahip olup olmadığını kontrol edin.
    * Varsa, bir "bool" olması gereken isteğe bağlı bir "is_offer" özniteliğine sahip olup olmadığını kontrol edin.
    * Tüm bunlar, derinlemesine iç içe geçmiş JSON nesneleri için de işe yarar.
*JSON'dan ve JSON'a otomatik olarak dönüştürün.
* Aşağıdakiler tarafından kullanılabilecek her şeyi OpenAPI ile belgeleyin:
    * Ietkileşimli dokümantasyon sistemleri.
    * Birçok dil için otomatik istemci kodu oluşturma sistemleri.
* Doğrudan 2 etkileşimli dokümantasyon web arayüzü sağlayın.

---

Biz sadece yüzeyi çizdik, ama zaten her şeyin nasıl çalıştığına dair bir fikriniz var.

Satırı şununla değiştirmeyi deneyin:

```Python
    return {"item_name": item.name, "item_id": item_id}
```

...from:

```Python
        ... "item_name": item.name ...
```

...to:

```Python
        ... "item_price": item.price ...
```

...ve düzenleyicinizin özellikleri nasıl otomatik olarak tamamlayacağını ve türlerini nasıl bileceğini görün:

![editor support](https://fastapi.tiangolo.com/img/vscode-completion.png)

Daha fazla özellik içeren daha eksiksiz bir örnek için <a href="https://fastapi.tiangolo.com/tutorial/">Öğretici - Kullanıcı Kılavuzu</a>'na bakın.

**Spoiler uyarısı**: öğretici - kullanım kılavuzu şunları içerir:

*Diğer farklı yerlerden **parametrelerin** beyanı: **başlıklar**, **cookies**, **form alanları** ve **dosyalar**.
***Doğrulama kısıtlamaları** nasıl "maksimum_uzunluk" veya "normal ifade" olarak ayarlanır.
* Çok güçlü ve kullanımı kolay bir **<abbr title="bileşenler, kaynaklar, sağlayıcılar, hizmetler, enjekte edilebilirler">Bağımlılık Enjeksiyonu</abbr>** sistemi olarak da bilinir.
* **JWT belirteçleri** ve **HTTP Basic** kimlik doğrulaması ile **OAuth2** desteği dahil olmak üzere güvenlik ve kimlik doğrulama.
* **Derin yuvalanmış JSON modellerini** bildirmek için daha gelişmiş (ancak aynı derecede kolay) teknikler (Pydantic sayesinde).
* **GraphQL** <a href="https://strawberry.rocks" class="external-link" target="_blank">Çilek</a> ve diğer kitaplıklarla entegrasyon.
* Birçok ekstra özellik (Starlette sayesinde):
    * **WebSockets**
    * "istekler" ve "pytest"e dayalı son derece kolay testler
    * **CORS**
    * **Çerez Oturumları**
    * ...ve dahası.

## Verim

Bağımsız TechEmpower karşılaştırmaları, Uvicorn altında çalışan **FastAPI** uygulamalarını <a href="https://www.techempower.com/benchmarks/#section=test&runid=7464e520-0dc2-473d-bd34-dbdfd7e85911&hw=ph&test=query&l= olarak gösterir. zijzen-7" class="external-link" target="_blank">mevcut en hızlı Python çerçevelerinden biri</a>, yalnızca Starlette ve Uvicorn'un altında (dahili olarak FastAPI tarafından kullanılır). (*)

Bununla ilgili daha fazla bilgi edinmek için <a href="https://fastapi.tiangolo.com/benchmarks/" class="internal-link" target="_blank">Karşılaştırmalar</a> bölümüne bakın.

## İsteğe Bağlı Bağımlılıklar

Pydantic tarafından kullanılır:

* <a href="https://github.com/esnme/ultrajson" target="_blank"><code>ujson</code></a> - daha hızlı JSON için <abbr title="gelen dizeyi dönüştürme Python verisine bir HTTP isteği">"ayrıştırma"</abbr>.
* <a href="https://github.com/JoshData/python-email-validator" target="_blank"><code>email_validator</code></a> - e-posta doğrulaması için.

Starlette tarafından kullanılır:

* <a href="https://requests.readthedocs.io" target="_blank"><code>istekler</code></a> - "TestClient"i kullanmak istiyorsanız gereklidir.
* <a href="https://jinja.palletsprojects.com" target="_blank"><code>jinja2</code></a> - Varsayılan şablon yapılandırmasını kullanmak istiyorsanız gereklidir.
* <a href="https://andrew-d.github.io/python-multipart/" target="_blank"><code>python-multipart</code></a> - Formu desteklemek istiyorsanız gereklidir <abbr title="bir HTTP isteğinden gelen dizeyi Python verilerine dönüştürme">"ayrıştırma"</abbr>, `request.form()` ile.
* <a href="https://pythonhosted.org/itsdangerous/" target="_blank"><code>itsdangerous</code></a> - "SessionMiddleware" desteği için gereklidir.
* <a href="https://pyyaml.org/wiki/PyYAMLDocumentation" target="_blank"><code>pyyaml</code></a> - Starlette'in "SchemaGenerator" desteği için gereklidir (muhtemelen FastAPI ile).
* <a href="https://github.com/esnme/ultrajson" target="_blank"><code>ujson</code></a> - "UJSONResponse" kullanmak istiyorsanız gereklidir.

FastAPI / Starlette tarafından kullanılır:

* <a href="https://www.uvicorn.org" target="_blank"><code>uvicorn</code></a> - uygulamanızı yükleyen ve sunan sunucu için.
*<a href="https://github.com/ijl/orjson" target="_blank"><code>orjson</code></a> - "ORJSONResponse" kullanmak istiyorsanız gereklidir.

Bunların hepsini `pip install "fastapi[all]"` ile kurabilirsiniz.

## Lisans

Bu proje MIT lisansı şartlarına göre lisanslanmıştır.
