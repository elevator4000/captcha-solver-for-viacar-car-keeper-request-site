# license_plate_downloader_for_Zurich

This small Prof of Concept shows how easily the captchas on the viacar website for car owner requests (https://www.viacar.ch/eindex/login.aspx?kanton=zh) 
can be solved by applying some denoising and using Tesseract(version 3.05.01) to recognize the Letters.
Just for fun I added a proxy fetcher (https://github.com/stamparm/fetch-some-proxies) to circumvent the 5 requests per IP per Day limit,
to get around 600 requests per day.