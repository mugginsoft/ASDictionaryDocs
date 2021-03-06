#ASDictionaryDocs

An archive of browsable HTML AppleScript documentation for a range of Apple and third party OS X applications (OS X 10.6 and above).

[ASDictionary][asdictionary] is used to generate the html docs from an application bundle. Source is available on [GitHub][github-asdictionary].

The full [ASDictionary][asdictionary] generated documentation set and downloadable zip archives can be viewed at [Mugginsoft][mugginsoft].

#Adding new ASDictionary AppleScript documentation

To add a new AppleScript documentation set:

1. Clone this.
2. Run the [ASDictionary][asdictionary] tool on the application bundle and generate an HTML AppleScript document set. When generating the dictionary documentation ensure that under **File Formats** both `HTML (Frames)` and `compact classes` are selected. The required **Terminology style** option is `AppleScript`.

3. Insert the generated HTML into the `Applications` folder hierarchy using the template below.
4. Send us a pull.

Folder hierarchy template:

	Applications\<company>\<appname>\OS-X-<ver>\<appname-ver>\html

#Email submission

[ASDictionary][asdictionary] generated documentation will also be accepted by email for inclusion in this archive. Send the following to `support@mugginsoft.com`.

1. Application company name (Apple, Adobe, etc).
2. Application name and link.
3. OS X version of machine that generated the documentation (OS X 10.6 and above only please).
4. Application version as quoted in the About panel.
5. The html documentation itself, either in the body of the email or as an attachment. Use the [ASDictionary][asdictionary] tool as detailed above.

[asdictionary]:http://www.mugginsoft.com/content/ASDictionary

[mugginsoft]:http://www.mugginsoft.com/kosmictask/ScriptingBridge

[github-asdictionary]:https://github.com/mugginsoft/appscript


