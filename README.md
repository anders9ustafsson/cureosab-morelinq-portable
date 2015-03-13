#Portable MoreLinq

Clone for building [MoreLinq](https://code.google.com/p/morelinq/) as a Portable Class Library (PCL).

The selected PCL profile is 328, which targets:

  * .NET Framework 4 and higher
  * Windows 8 (f.k.a. Windows Store or Metro) and higher
  * Windows Phone Silverlight 8 and higher
  * Windows Phone 8.1
  * Silverlight 5
  * Xamarin.Android
  * Xamarin.iOS

All functionality of the .NET only library is retained, except:

  * `SequenceException` not binary serializable
  * `ToDataTable` and `Trace` methods omitted
