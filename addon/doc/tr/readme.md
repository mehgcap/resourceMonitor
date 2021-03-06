# Kaynak izleme #

* Geliştiriciler: Alex Hall, Joseph Lee, beqa gozalishvili and other NVDA
  contributors
* Download [stable version][1]

This plugin gives information about CPU load, memory usage and other
resource usage information.

# Kısayollar #

* NVDA+Shift+E Presents used ram, average processor load, and battery info
  if available.
* NVDA+Shift+1 Presents the average processor load and if multicore CPU's
  are present the load of each core.
* NVDA+Shift+2/5 Presents the used and total space for both physical and
  virtual ram.
* NVDA+Shift+3 Presents the used and total space of the static and removable
  drives.
* NVDA+Shift+4 Presents battery percentage, charging status, remaining time
  (if not charging), and a warning if the battery is low or critical.
* NVDA+Shift+6 Presents CPU Architecture 32/64-bit and Windows version and
  service pack numbers.

If you have NvDA 2013.3 or later installed, you can change these shortcut
keys.

## Kullanım notları ##

Bu eklenti görev yöneticisi ya da sistem bilgisiyle ilgili başka
uygulamaların yerine geçmez. Yanısıra, aşağıdakileri de not edin:

* CPU usage is given for logical processors, not physical cores. This is
  noticeable for processors which uses Hyper-Threading where number of CPU's
  is twice the number of CPU cores.
* If there is heavy disk activity such as copying large files, there might
  be delays when obtaining disk usage information.

## Version 17.02

* Updated psutil dependency to 5.0.1.
* When checking disk usage, NVDA will no longer present an error dialog on
  some systems where a removable media is not properly recognized (such as
  when a card isn't inserted into a card reader).)

## Version 16.08

Starting with version 16.08, add-on releases will be shown as
year.month.revision.

* Various revisions of Windows 10 are now properly recognized (such as 1607
  for build 14393).
* Windows 10 build revisions (after installing cumulative updates) are
  properly recognized (such as 14393.51).
* If using Insider Preview builds, this fact is recognized.

## Changes for 4.5 ##

* Add-on repository has moved to GitHub (can be found at
  https://github.com/josephsl/resourcemonitor).
* Windows Server 2016 is properly recognized.

## Changes for 4.0 ##

* Updated psutil dependency to 2.2.1.
* Vastly improved performance when obtaining information on CPU load.
* Added support for recognition of Windows 10.
* In Windows 10, the build number of Windows will also be announced.
* You can use Add-ons Manager to access add-on help.

## Changes for 3.1 ##

* Resource Monitor officially supports Windows 8.1.
* Çeviriler güncellendi.

## 3.0 için değişiklikler ##

* 1.2.1 için psutil bağımlılık güncellendi.
* Announcement of current Windows version, CPU architecture and service pack
  if any (NVDA+Shift+6).
* Kısayol tuşları, NVDA 2013.3 sürümüyle birlikte değiştirilebilir.
* Kaynak bilgisi öğrenme komutlarına iki kez basıldığında bilgi panoya
  kopyalanıyor

## 2.4 için değişiklikler ##

* Yeni diller: Çince (basitleştirilmiş), Ukrayna.
* Çeviriler güncellendi.

## 2.3 için değişiklikler ##

* Bulgarca çeviri eklendi.

## 2.2 için değişiklikler ##

* Added following translations: Arabic, Aragonese, Croatian, Dutch, Finnish,
  French, Galician, German, Hungarian, Italian, Japanese, Korean, Nepali,
  Polish, Portuguese (Brazil), Russian, Slovak, Slovenian, Spanish, Tamil
  and Turkish.

## 2.1 için değişiklikler ##

* Updated psutil dependency to version 0.6.1.
* Fixed long delay when getting information of drives.
* Code cleanup.

## 2.0 için değişiklikler ##

* çeviri desteği ve açıklamalar eklendi

## 1.0 için değişiklikler ##

* ilk sürüm

[[!tag dev stable]]

[1]: http://addons.nvda-project.org/files/get.php?file=rm
