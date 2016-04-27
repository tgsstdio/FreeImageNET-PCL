# FreeImage.NET-PCL

Modified version of FreeImage.NET v3.17.0 wrapper as Portable Core library (PCL) + .NET 4.5 assembly

See FreeImageAPI-PCL.csproj

## WHY?
 - To remove any System.Drawing assembly references 
    - Reimplementation of System.Drawing.Color using own .NET and MonoGame implementation
    - Removed ISerializable, Serializable, IClonable interface

