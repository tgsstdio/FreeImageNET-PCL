# FreeImage.NET-PCL

Modified version of FreeImage.NET v3.17.0 wrapper PCL version + .NET 4.5 project

## WHY?
 - To remove any System.Drawing assembly references (i.e. reimplementation of System.Drawing.Color using own .NET and MonoGame implementation)  
 - Remove ISerializable, Serializable, IClonable interface

See FreeImageAPI-PCL.csproj