<!--  ----------------------------------------------------------------------  -->
<!--  NOTE: Please add the following <META> element to your page <HEAD>.      -->
<!--  If necessary, please modify the charset parameter to specify the        -->
<!--  character set of your HTML page.                                        -->
<!--  ----------------------------------------------------------------------  -->

<META HTTP-EQUIV="Content-type" CONTENT="text/html; charset=UTF-8">
<script src="https://www.google.com/recaptcha/api.js"></script>
<script>
 function timestamp() { var response = document.getElementById("g-recaptcha-response"); if (response == null || response.value.trim() == "") {var elems = JSON.parse(document.getElementsByName("captcha_settings")[0].value);elems["ts"] = JSON.stringify(new Date().getTime());document.getElementsByName("captcha_settings")[0].value = JSON.stringify(elems); } } setInterval(timestamp, 500); 
</script>

<!--  ----------------------------------------------------------------------  -->
<!--  NOTE: Please add the following <FORM> element to your page.             -->
<!--  ----------------------------------------------------------------------  -->

<form action="https://test.salesforce.com/servlet/servlet.WebToLead?encoding=UTF-8" method="POST">

<input type=hidden name='captcha_settings' value='{"keyname":"LBtest","fallback":"true","orgId":"00D0U0000009Zuy","ts":""}'>
<input type=hidden name="oid" value="00D0U0000009Zuy">
<input type=hidden name="retURL" value="http://google.com">

<!--  ----------------------------------------------------------------------  -->
<!--  NOTE: These fields are optional debugging elements. Please uncomment    -->
<!--  these lines if you wish to test in debug mode.                          -->
<!--  <input type="hidden" name="debug" value=1>                              -->
<!--  <input type="hidden" name="debugEmail" value="ngabrani@astreait.com">   -->
<!--  ----------------------------------------------------------------------  -->

Session Title:<textarea  id="00NA0000002xr7b" name="00NA0000002xr7b" type="text" wrap="soft"></textarea><br>

Session Proposal:<textarea  id="00N0U0000040g6TUAQ" name="00N0U0000040g6TUAQ" rows="25" type="text" wrap="soft"></textarea><script>CKEDITOR.timestamp = '4.14.0.6';
var protocolAndHost = window.location.protocol + '//' + window.location.host;

var editor = CKEDITOR.replace('00N0U0000040g6TUAQ', {
removePlugins : 'elementspath,maximize,image,tabletools,liststyle,contextmenu,resize',
baseHref : protocolAndHost + '/ckeditor/ckeditor-4.x/rel/',
customConfig : '/ckeditor/ckeditor-4.x/rel/sfdc-config.js',
height : '425',
bodyId : '00N0U0000040g6TUAQ_rta_body',
toolbar : 'SalesforceBasic',
sfdcLabels :{CkeLineHeight : { secondValue : '1.15', singleValue : 'Single', doubleValue : 'Double', title : 'Line Height', thirdValue : '1.5'}, CkeQuickText : { title : 'Insert quick text'}, CkeMediaEmbed : { iframeMissing : 'Invalid &lt;iframe&gt; element. Please use valid code from the approved sites.', subtitle : 'Paste &amp;lt;iframe&amp;gt; code here:', description : 'Use &lt;iframe&gt; code from an approved video source.', title : 'Embed Multimedia Content', exampleTitle : 'Example:', example : '\n            \n                &lt;iframe width=\&quot;560\&quot; height=\&quot;315\&quot; src=\&quot;https://www.youtube.com/embed/KcOm0TNvKBA\&quot; frameborder=\&quot;0\&quot; allowfullscreen&gt;&lt;/iframe&gt;\n            \n        '}, CkeImageMenu : { uploadFile : ' Browse or Upload', uploadCms : 'Salesforce CMS', pasteUrl : 'Paste Image URL', uploadUrl : 'Web Image', uploadSFFile : 'Salesforce Files', title : 'Insert images into your message'}, CkeImagePaste : { CkeImagePasteWarning : 'Pasting an image is not working properly with Firefox, please use [Copy Image location] instead.'}, CkeImageDialog : { infoTab_desc_info : 'Enter a description of the image for visually impaired users', uploadTab_desc : 'Description', defaultImageDescription : 'User-added image', uploadTab_file_info : 'Maximum size 1 MB. Only PNG, GIF or JPEG', uploadTab_desc_info : 'Enter a description of the image for visually impaired users', imageUploadLimit_info : 'Max number of upload images exceeded', btn_insert_tooltip : 'Insert Image', httpUrlWarning : 'Are you sure you want to use an http URL? Using http image URLs may result in security warnings about insecure content. To avoid these warnings, use https image URLs instead.', title : 'Insert Image', error : 'Error:', uploadTab : 'Upload Image', wrongFileTypeError : 'You can insert only .gif .jpeg and .png files.', infoTab_url : 'URL', infoTab : 'Web Address', infoTab_url_info : 'Example: http://www.mysite.com/myimage.jpg', missingUrlError : 'You must enter a URL', uploadTab_file : 'Select Image', btn_update_tooltip : 'Update Image', infoTab_desc : 'Description', btn_insert : 'Insert', btn_update : 'Update', btn_upadte : 'Update', invalidUrlError : 'You can only use http:, https:, data:, //, /, or relative URL schemes.'}, sfdcSwitchToText : { sfdcSwitchToTextAlt : 'Use plain text'}, CkeSmartLink : { SmartLinkContextMenuEdit : 'Edit Smart Link', title : 'Insert a Smart Link'}},
contentsCss: ['/ckeditor/ckeditor-4.x/rel/contents.css', '/sCSS/53.0/sprites/1627628858000/Theme3/default/gc/CKEditor.css', '/sCSS/53.0/sprites/1627628858000/Theme3/default/gc/HtmlDetailElem.css'],
disableNativeSpellChecker : false,
language : 'en-US',
allowIframe : false,
isPardotOrg : false,
isCmsOnly : false,
sharedSpaces : { top : 'cke_topSpace', bottom : ' cke_bottomSpace' }
,filebrowserImageUploadUrl : '/_ui/common/request/servlet/RtaImageUploadServlet?_CONFIRMATIONTOKEN=VmpFPSxNakF5TVMwd09TMHhNMVF3T0RvMU56b3pPUzQzTnpGYSxFNkkzcTBidkt4aDBsS1AxSFh3d0JKLE5HRm1NemMy'
});

editor.on('instanceReady', function( evt ) {
    try {
        var id = evt.editor.name;
        CKiframe = document.getElementById('cke_' + id).querySelector('iframe');
        meta = document.createElement('meta');
        meta.setAttribute('name', 'referrer');
        meta.setAttribute('content', 'no-referrer');
        CKiframe.contentDocument.head.appendChild(meta);
    } catch(e) {}
} );

</script><br>

Bio:<textarea  id="00NA0000002xxNKMAY" name="00NA0000002xxNKMAY" rows="10" type="text" wrap="soft"></textarea><script>CKEDITOR.timestamp = '4.14.0.6';
var protocolAndHost = window.location.protocol + '//' + window.location.host;

var editor = CKEDITOR.replace('00NA0000002xxNKMAY', {
removePlugins : 'elementspath,maximize,image,tabletools,liststyle,contextmenu,resize',
baseHref : protocolAndHost + '/ckeditor/ckeditor-4.x/rel/',
customConfig : '/ckeditor/ckeditor-4.x/rel/sfdc-config.js',
height : '170',
bodyId : '00NA0000002xxNKMAY_rta_body',
toolbar : 'SalesforceBasic',
sfdcLabels :{CkeLineHeight : { secondValue : '1.15', singleValue : 'Single', doubleValue : 'Double', title : 'Line Height', thirdValue : '1.5'}, CkeQuickText : { title : 'Insert quick text'}, CkeMediaEmbed : { iframeMissing : 'Invalid &lt;iframe&gt; element. Please use valid code from the approved sites.', subtitle : 'Paste &amp;lt;iframe&amp;gt; code here:', description : 'Use &lt;iframe&gt; code from an approved video source.', title : 'Embed Multimedia Content', exampleTitle : 'Example:', example : '\n            \n                &lt;iframe width=\&quot;560\&quot; height=\&quot;315\&quot; src=\&quot;https://www.youtube.com/embed/KcOm0TNvKBA\&quot; frameborder=\&quot;0\&quot; allowfullscreen&gt;&lt;/iframe&gt;\n            \n        '}, CkeImageMenu : { uploadFile : ' Browse or Upload', uploadCms : 'Salesforce CMS', pasteUrl : 'Paste Image URL', uploadUrl : 'Web Image', uploadSFFile : 'Salesforce Files', title : 'Insert images into your message'}, CkeImagePaste : { CkeImagePasteWarning : 'Pasting an image is not working properly with Firefox, please use [Copy Image location] instead.'}, CkeImageDialog : { infoTab_desc_info : 'Enter a description of the image for visually impaired users', uploadTab_desc : 'Description', defaultImageDescription : 'User-added image', uploadTab_file_info : 'Maximum size 1 MB. Only PNG, GIF or JPEG', uploadTab_desc_info : 'Enter a description of the image for visually impaired users', imageUploadLimit_info : 'Max number of upload images exceeded', btn_insert_tooltip : 'Insert Image', httpUrlWarning : 'Are you sure you want to use an http URL? Using http image URLs may result in security warnings about insecure content. To avoid these warnings, use https image URLs instead.', title : 'Insert Image', error : 'Error:', uploadTab : 'Upload Image', wrongFileTypeError : 'You can insert only .gif .jpeg and .png files.', infoTab_url : 'URL', infoTab : 'Web Address', infoTab_url_info : 'Example: http://www.mysite.com/myimage.jpg', missingUrlError : 'You must enter a URL', uploadTab_file : 'Select Image', btn_update_tooltip : 'Update Image', infoTab_desc : 'Description', btn_insert : 'Insert', btn_update : 'Update', btn_upadte : 'Update', invalidUrlError : 'You can only use http:, https:, data:, //, /, or relative URL schemes.'}, sfdcSwitchToText : { sfdcSwitchToTextAlt : 'Use plain text'}, CkeSmartLink : { SmartLinkContextMenuEdit : 'Edit Smart Link', title : 'Insert a Smart Link'}},
contentsCss: ['/ckeditor/ckeditor-4.x/rel/contents.css', '/sCSS/53.0/sprites/1627628858000/Theme3/default/gc/CKEditor.css', '/sCSS/53.0/sprites/1627628858000/Theme3/default/gc/HtmlDetailElem.css'],
disableNativeSpellChecker : false,
language : 'en-US',
allowIframe : false,
isPardotOrg : false,
isCmsOnly : false,
sharedSpaces : { top : 'cke_topSpace', bottom : ' cke_bottomSpace' }
,filebrowserImageUploadUrl : '/_ui/common/request/servlet/RtaImageUploadServlet?_CONFIRMATIONTOKEN=VmpFPSxNakF5TVMwd09TMHhNMVF3T0RvMU56b3pPUzQzTnpOYSxtM2NMSzRkc3hCZ2RqVDMzV29uOFc0LE5HRm1NemMy'
});

editor.on('instanceReady', function( evt ) {
    try {
        var id = evt.editor.name;
        CKiframe = document.getElementById('cke_' + id).querySelector('iframe');
        meta = document.createElement('meta');
        meta.setAttribute('name', 'referrer');
        meta.setAttribute('content', 'no-referrer');
        CKiframe.contentDocument.head.appendChild(meta);
    } catch(e) {}
} );

</script><br>

Primary Subject Area:<select  id="00NA0000009dQxO" name="00NA0000009dQxO" title="Primary Subject Area"><option value="">--None--</option><option value="Arts &amp; Culture">Arts &amp; Culture</option>
<option value="Communities (Families, Parenting, etc.)">Communities (Families, Parenting, etc.)</option>
<option value="History &amp; Politics">History &amp; Politics</option>
<option value="Mind, Body &amp; Soul">Mind, Body &amp; Soul</option>
<option value="Prayer &amp; Liturgy">Prayer &amp; Liturgy</option>
<option value="Science &amp; Innovation">Science &amp; Innovation</option>
<option value="Social Justice/Action (Diversity/Inclusivity)">Social Justice/Action (Diversity/Inclusivity)</option>
<option value="Torah &amp; Philosophy">Torah &amp; Philosophy</option>
<option value="Other">Other</option>
</select><br>

Additional Subject Areas:<select  id="00NA0000002wOEm" multiple="multiple" name="00NA0000002wOEm" title="Additional Subject Areas"><option value="Arts &amp; Culture">Arts &amp; Culture</option>
<option value="Communities (Families, Parenting, etc.)">Communities (Families, Parenting, etc.)</option>
<option value="History &amp; Politics">History &amp; Politics</option>
<option value="Mind, Body &amp; Soul">Mind, Body &amp; Soul</option>
<option value="Prayer &amp; Liturgy">Prayer &amp; Liturgy</option>
<option value="Science &amp; Innovation">Science &amp; Innovation</option>
<option value="Social Justice/Action (Diversity/Inclusivity)">Social Justice/Action (Diversity/Inclusivity)</option>
<option value="Torah &amp; Philosophy">Torah &amp; Philosophy</option>
<option value="Other">Other</option>
</select><br>

Prefer to present:<select  id="00N0U0000040g72" name="00N0U0000040g72" title="Prefer to present"><option value="">--None--</option><option value="9:00 am to 1:00pm">9:00 am to 1:00pm</option>
<option value="1:00pm to 5:00 pm">1:00pm to 5:00 pm</option>
</select><br>
Will you have additional Presenters with you?If so ,Please add their information here<br>
<label for="first_name">First Name</label><input  id="first_name" maxlength="40" name="first_name" size="20" type="text" /><br>

<label for="last_name">Last Name</label><input  id="last_name" maxlength="80" name="last_name" size="20" type="text" /><br>

<label for="email">Email</label><input  id="email" maxlength="80" name="email" size="20" type="text" /><br>

Second Presenter First Name:<input  id="00NA0000009dCB4" maxlength="40" name="00NA0000009dCB4" size="20" type="text" /><br>

Second Presenter Last Name:<input  id="00NA0000009dCAy" maxlength="80" name="00NA0000009dCAy" size="20" type="text" /><br>

Second Presenter Email:<input  id="00NA0000009dQuK" maxlength="80" name="00NA0000009dQuK" size="20" type="text" /><br>

<div class="g-recaptcha" data-sitekey="6LdEYSYUAAAAAIigyMh4U9LVfw2Ij47spUvRwIys"></div><br>
<input type="submit" name="submit">

</form>
