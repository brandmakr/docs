

---


Developer Guide
===================

---

- <a target="_blank" href="https://api.brandmakr.com/scan/">**Scan**</a>

<div class="devices">
    <div class="device device-ios">
        <iframe src="https://api.brandmakr.com/scan/" scrolling="no" frameborder="0"></iframe>
    </div>
</div>

---



- <a target="_blank" href="https://api.brandmakr.com/genkeys">**Gen keys**</a>


- <a target="_blank" href="https://brandmakr.com/mockup">**Mockup**</a>

- <a target="_blank" href="https://ifro.ga/BrandMakr">**Design**</a>
    - <a target="_blank" href="https://github.com/brandmakr/artwork">**Other Artwork**</a>

- <a target="_blank" href="http://ios.brandmakr.com">**Info & Help page**</a>

---

**Request POST URL**


- <a target="_blank"> *https://api.brandmakr.com/service/* </a>  (both slash and non-trailing-slash)
 
```json
{
	"keys" : "XXXX-XXXX-XXXX-XXXX",
	"location" : "00.000000,00.000000",
	"secret" : "101946110ac0176b229582f27c98e23f"
}
```


**Respond JSON**

```json
{
	"product" : "Name Product",
	"detail" : "Detail of product",
	"pic" : "url link to picture",
	"keys" : "XXXX-XXXX-XXXX-XXXX",
	"valid" : "Y",
	"chknum" : "3",
	"chklast" : "01 Jan 2015 00:00",
	"product_url" : "https://api.brandmakr.com/product/{product}"
}
```



---

