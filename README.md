﻿<div align="center">

## Advanced META Tag Generator


</div>

### Description

This is your tool for creating a complete set of META tags. It's fast, fun, and an easy way to create all kinds of META tags, not just basic ones such as the keyword and description META tag.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[darocker22](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/darocker22.md)
**Level**          |Intermediate
**User Rating**    |3.9 (55 globes from 14 users)
**Compatibility**  |
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__2-57.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/darocker22-advanced-meta-tag-generator__2-2727/archive/master.zip)





### Source Code

```
<html>
<HEAD>
<SCRIPT LANGUAGE="JavaScript">
<!-- Begin
function create(form)
{
 if (confirm("Are you sure?"))
 {
  form.story.value = "Advanced Meta Tag Generator \n" +
  "author: Daniel Toljaga (http://www.bosniak.com) \n" +
  "Instructions: Simply copy the following lines of code and insert them " +
   "between the <HEAD> and </HEAD> tags in your HTML document. That's it! \n\n";
  if (form.input1.value != "")
  {
   form.story.value +="<META NAME=\"Title\" CONTENT=\"" +
   form.input1.value + "\">\n";
  }
  if (form.input2.value != "")
  {
   form.story.value +="<META NAME=\"Author\" CONTENT=\"" +
   form.input2.value + "\">\n";
  }
  if (form.input3.value != "")
  {
   form.story.value +="<META NAME=\"Subject\" CONTENT=\"" +
   form.input3.value + "\">\n";
  }
  if (form.input4.value != "")
  {
   form.story.value +="<META NAME=\"Description\" CONTENT=\"" +
   form.input4.value + "\">\n";
  }
  if (form.input5.value != "")
  {
   form.story.value +="<META NAME=\"Keywords\" CONTENT=\"" +
   form.input5.value + "\">\n";
  }
  if (form.input6.value != "")
  {
   form.story.value +="<META NAME=\"Generator\" CONTENT=\"" +
   form.input6.value + "\">\n";
  }
  if (form.input7.value != "")
  {
   form.story.value +="<META NAME=\"Language\" CONTENT=\"" +
   form.input7.value + "\">\n";
  }
  if (form.input8.value != "")
  {
   form.story.value +="<META NAME=\"Expires\" CONTENT=\"" +
   form.input8.value + "\">\n";
  }
  if (form.input9.value != "")
  {
   form.story.value +="<META NAME=\"Abstract\" CONTENT=\"" +
   form.input9.value + "\">\n";
  }
  if (form.input10.value != "")
  {
   form.story.value +="<META NAME=\"Copyright\" CONTENT=\"© " +
   form.input10.value + "\">\n";
  }
  if (form.input11.value != "") {
   form.story.value +="<META NAME=\"Designer\" CONTENT=\"" +
   form.input11.value + "\">\n";
  }
  if (form.input12.value != "")
  {
   form.story.value +="<META NAME=\"Publisher\" CONTENT=\"" +
   form.input12.value + "\">\n";
  }
  if (form.input13.value != "")
  {
   form.story.value +="<META NAME=\"Revisit-After\" CONTENT=\"" +
   form.input13.value + " \Days\">\n";
  }
  if (form.input14.value != "")
  {
   form.story.value +="<META NAME=\"Distribution\" CONTENT=\"" +
   form.input14.options[form.input14.selectedIndex].value + "\">\n";
  }
  if (form.input15.value != "")
  {
   form.story.value +="<META NAME=\"Robots\" CONTENT=\"" +
   form.input15.options[form.input15.selectedIndex].value + "\">\n";
  }
 }
}
// End -->
</script>
</HEAD>
<!-- STEP TWO: Copy this code into the BODY of your HTML document -->
<BODY>
<div align="center">
 <center>
  <p align="left"> </p>
  <table class=normal WIDTH="600" BORDER="0" CELLSPACING="0" CELLPADDING="0">
 <tr>
  <td><center><font face="verdana" size="4">Advanced META Tag Generator</font></center>
  <form>
   <div align="center"><center><table class=normal BORDER="0" CELLPADDING="2">
    <tr>
     <td>Title:</td>
     <td><input TYPE="text" NAME="input1" SIZE="40"></td>
    </tr>
    <!-- The author META tag defines the name of the author of the document being read. -->
    <tr>
     <td>Author:</td>
     <td><input TYPE="text" NAME="input2" SIZE="40"></td>
    </tr>
    <tr>
     <td>Subject:</td>
     <td><input TYPE="text" NAME="input3" SIZE="40"></td>
    </tr>
    <tr>
     <td>Description:</td>
     <td><input TYPE="text" NAME="input4" SIZE="40"></td>
    </tr>
    <tr>
     <td>Keywords:</td>
     <td><input TYPE="text" NAME="input5" SIZE="40"></td>
    </tr>
    <tr>
     <td>Generator:</td>
     <td><input TYPE="text" NAME="input6" SIZE="40"></td>
    </tr>
    <tr>
     <td>Language:</td>
     <td><input TYPE="text" NAME="input7" SIZE="40"></td>
    </tr>
    <!-- The expires META tag defines the expiration date and time of the document being
    indexed and requires RFC1123 date format, for example: Thu, 04 Oct 2010 14:21:20 GMT -->
    <tr>
     <td>Expires:</td>
     <td><input TYPE="text" NAME="input8" SIZE="40"></td>
    </tr>
    <!-- The abstract META tag is a one line sentence which gives an overview of the entire webpage -->
    <tr>
     <td>Abstract:</td>
     <td><input TYPE="text" NAME="input9" SIZE="40"></td>
    </tr>
    <!-- Copyright: no need to add ©, it will be added automatically -->
    <tr>
     <td>Copyright:</td>
     <td><input TYPE="text" NAME="input10" SIZE="40"></td>
    </tr>
    <!-- Designer = Webmaster -->
    <tr>
     <td>Designer:</td>
     <td><input TYPE="text" NAME="input11" SIZE="40"></td>
    </tr>
    <!-- Publisher: Company that publishes material being read or sold on a web site -->
    <tr>
     <td>Publisher:</td>
     <td><input TYPE="text" NAME="input12" SIZE="40"></td>
    </tr>
    <!-- The Revisit META tag defines how often a search engine or spider should
    come to your website for re-indexing. For example: 2 Days, 3 Days, 4 Days, etc.
    Note: Just ad number(s), word Days will be added automatically -->
    <tr>
     <td>Revisit-After:</td>
     <td><input TYPE="text" NAME="input13" SIZE="40"></td>
    </tr>
    <!-- Distribution: Global (indicates that your webpage is intended for
    mass distribution to everyone), Local (intended for local distribution
    of your document), and IU - Internal Use (not intended for public distribution). -->
    <tr>
     <td>Distribution:</td>
     <td><select NAME="input14" size="1">
       <option VALUE="" SELECTED>Select One</option>
      <option VALUE="Global">1. Global</option>
      <option VALUE="Local">2. Local</option>
      <option VALUE="IU">3. Intern Use</option>
     </select></td>
    <tr>
     <td>Robots:</td>
     <td><select NAME="input15" size="1">
      <option VALUE="" SELECTED>Select One</option>
      <option VALUE="All">1. All</option>
      <option VALUE="None">2. None</option>
      <option VALUE="Index">3. Index</option>
      <option VALUE="No Index">4. No Index</option>
      <option VALUE="Follow">5. Follow</option>
      <option VALUE="No Follow">6. No Follow</option>
     </select></td>
    </tr>
    </tr>
   </table>
   </center></div><blockquote>
    <p><input TYPE="button" VALUE="Create META tags" ONCLICK="create(this.form)"> <input
    TYPE="reset" VALUE="Clear All"> <textarea WRAP NAME="story" ROWS="12" COLS="65"></textarea>
    </p>
   </blockquote>
  </form>
  </td>
 </tr>
</table>
 </center>
</div>
</body>
</html>
```

