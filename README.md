# ISEC Slides Template

Quickstart (CLI):

```sh
typst init @preview/definitely-not-isec-slides:1.1.0 slides
```

Quickstart (WebIDE):

- [Create Document](https://typst.app/app?template=definitely-not-isec-slides&version=1.1.0)
- [Homepage](https://typst.app/universe/package/definitely-not-isec-slides)

Keep in mind you'll need the Open Sans font configured in the web editor.

> [!NOTE]
> If you are an ISEC or TUGraz employee and think that `isec-thesis` or
> `tugraz-thesis` fits more, I would need an approval to allocate the name :)

Tested typst version: `0.15.0`.

Need a thesis? Check out the sibling package [definitely-not-isec-thesis](https://github.com/ecomaikgolf/typst-isec-thesis-template)

## Typst

### What's Typst?

A modern typesetting system which has:

- Milisecond incremental (memoized) builds¹
- Subsecond full builds¹
- Multithreaded builds per pagebreak
- Easy rustc-like compiler error messages (and no intermediates!)
- Transparent multiple compiler passes (no more mklatex/makefiles)
- Simple & powerful scripting and syntax
- WebAssembly plugin support (python/js interpreters in your thesis? Sure)

Migrating from LaTeX? Check the [migration guide](https://typst.app/docs/guides/guide-for-latex-users/)

¹: This is obviously not a serious benchmark and depends on the document. But
   it's fast trust me

### Quick usage

Start incremental compilations with:

```sh
typst watch slides.typ
```

then open the generated PDF:

```sh
xdg-open slides.typ
```

Now edit `slides.typ` and it will be incrementally built in each save.

## Design
---
![title](https://github.com/user-attachments/assets/d29f53ff-0622-45fe-9727-7d286e8d15b1)

---
![list](https://github.com/user-attachments/assets/27dc198d-714d-4ed6-ad2e-f39babcf4fce)

---
![listimage](https://github.com/user-attachments/assets/b16cb69b-c9a1-4f50-8fd5-e7c3b0a97617)

---
![standout](https://github.com/user-attachments/assets/179960f4-e909-4856-8aba-6beb7a91e3c5)

---
![colors](https://github.com/user-attachments/assets/312a013e-fd89-4b6a-921b-bbfe9f4fa565)

---
![features](https://github.com/user-attachments/assets/1f3cd158-3860-4962-9802-7fc22d4b94a1)

---
![code](https://github.com/user-attachments/assets/508abb37-8224-4ef8-9424-2f367981b91f)

---
![blocks](https://github.com/user-attachments/assets/e4214dc0-f434-40d2-b1fa-0463ef18d9b7)

---
![plots](https://github.com/user-attachments/assets/605a3bab-c040-4932-9777-03dffabb3a9f)

---
![configurable](https://github.com/user-attachments/assets/310a25e2-981c-40b3-bbcb-fc243cbb5983)

---
![blank](https://github.com/user-attachments/assets/7533e702-bba3-4462-add2-f2fbe1e50a20)

---
![bibliography](https://github.com/user-attachments/assets/6ad78bf1-8af1-43c3-ad15-192fdfd42aff)



## License `src/assets/tuglogo.svg`

According to Wikipedia:

> This logo image consists only of simple geometric shapes or text. It does not
> meet the threshold of originality needed for copyright protection, and is
> therefore in the public domain. [...]

https://en.m.wikipedia.org/wiki/File:TU_Graz.svg
