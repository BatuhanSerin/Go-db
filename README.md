

- `Book` ve `Author` bilgileri bir dosyadan okunacak ve DB'ye kayıt edildi.
- `list`, `search`, `delete(soft-delete)`, `buy` gibi `os.Args` komutları yerine DB sorguları yazılacak. 
- Bu 2 modelle alakalı GORM sorguları yazıldı.
  - GetByID
  - FindByName
  - GetBooksWithAuthor
  - GetAuthorWithBooks etc. (GORM dökümantasyondaki sorgu çeşitlerine bakılacak bu 2 modelde uygulandı)
  
