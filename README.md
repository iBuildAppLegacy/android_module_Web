Use our code to save yourself time on cross-platform, cross-device and cross OS version development and testing
# android module Web
Web widget is designed to display web-content, located under provided web-link. User provides the link while creating the app on website. If a user provids HTML-content manually then this content should be displayed in the app.

Tags:
- title - widget name. Title is being displayed on navigation panel when widget is launched.
- content - widget content. If src tag contains URL then content located under provided web-link will be used. If the same tag contains HTML layout then this content will be displayed.

Example:

Web:

    <data>
    <title><![CDATA[ My Web Page ]]></title>
    <content src="http://m.ibuildapp.com"/>
    </data>

HTML:

    <data>
    <title><![CDATA[ HTML ]]></title>
    <content>
        <![CDATA[
            <html><head></head><body> Hello, world!<div>:)</div> </body></html>
        ]]>
    </content>
    </data>
