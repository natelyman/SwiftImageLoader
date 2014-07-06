SwiftImageLoader
================

Asynchronous Image Loader in Swift. Caches using an NSCache.


## Usage

```
ImageLoader.sharedLoader.imageForUrl(urlString, completionHandler:{(image: UIImage?, url: String) in
	self.imageView.image = image
}) 
