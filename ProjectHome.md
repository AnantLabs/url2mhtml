This is a C# (CSharp) port of MhtBuilder at http://www.codeproject.com/KB/files/MhtBuilder.aspx

"Most of these are self-explanatory, with the exception of the Web Archive (MHTML) format. What's neat about this format is that it bundles the web page and all of its references, into a single compact .MHT file. It's a lot easier to distribute a single self-contained file than it is to distribute a HTML file with a subfolder full of image/CSS/Flash/XML files referenced by that HTML file. In our case, we were generating HTML reports and we needed to check these reports into a document management system which expects a single file. The MHTML (**.mht) format solves this problem beautifully!**

This project contains the MhtBuilder class, a 100% .NET managed code solution which can auto-generate a MHT file from a target URL, in one line of code. As a bonus, it will also generate all the other formats listed above, too. And it's completely free, unlike some commercial solutions you might find out there.
Background

I know people assume the worst of Microsoft, but the MHTML format is actually based on RFC standard 2557, compliant Multipart MIME Message (MHTML web archive). So it's an actual Internet standard! Web Archive, a.k.a. MHTML, is a remarkably simple plain text format which looks a lot like (and is in fact almost exactly identical to) an email."