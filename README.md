<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:css='false' b:layoutsVersion='3' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>

<head>

<meta charset='UTF-8'/>
<meta content='website' property='og:type'/>
<meta expr:content='data:blog.url' property='og:url'/>
<meta expr:content='data:blog.pageTitle' property='og:site_name'/>
<meta expr:content='data:blog.pageTitle' property='og:image:alt'/>
<meta content='en_US' property='og:locale'/>
<meta content='en_GB' property='og:locale:alternate'/>
<meta content='id_ID' property='og:locale:alternate'/>
<link expr:href='data:blog.url' rel='canonical'/>

<b:if cond='data:blog.postImageUrl'>
 <meta expr:content='data:blog.postImageUrl' property='og:image'/>
 <b:else/>
 <b:if cond='data:blog.postImageThumbnailUrl'>
  <meta expr:content='data:blog.postThumbnailUrl' property='og:image'/>
  <b:else/>
  <meta content='https://image.ibb.co/hqEdbc/KJ_min.png' property='og:image'/>
 </b:if>
</b:if>

<b:if cond='data:blog.url == data:blog.homepageUrl'>
 <meta expr:content='data:blog.pageTitle' property='og:title'/>
 <meta expr:content='data:blog.pageName + &quot;, &quot; + data:blog.pageTitle + &quot;, &quot; + data:blog.title' name='keywords'/>
  <b:else/>
 <meta expr:content='data:blog.pageName' property='og:title'/>
 <meta expr:content='data:blog.pageName + &quot;, &quot; + data:blog.pageTitle + &quot;, &quot; + data:blog.title' name='keywords'/>
</b:if>

<b:if cond='data:blog.url == data:blog.homepageUrl'>
 <meta content='Deskripsi Blog' name='description' property='og:description'/>
</b:if>
<b:if cond='data:view.isPost'>
 <meta expr:content='data:blog.metaDescription' name='description' property='og:description'/>
</b:if>
<b:if cond='data:view.isPage'>
 <meta expr:content='data:blog.pageName' name='description' property='og:description'/>
</b:if>

<b:if cond='data:blog.pageType == &quot;error_page&quot;'>
 <title>Laman Tidak Ditemukan</title> 
</b:if>

<b:if cond='data:blog.pageType == &quot;index&quot;'>
 <title><data:blog.pageTitle/></title> 
  <b:else/>
 <title><data:blog.pageName/></title>
</b:if>

 <script src='https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js'/>

<b:template-skin><![CDATA[
body#layout {}
body#layout #complementary {display:none}
]]></b:template-skin>
<b:skin><![CDATA[

/* ----- New Comments System Variables ----- */

<Group description="New Comment Required - Dont edit"> <Variable name="body.background" description="Body Background" type="background" color="#000" default="#000 none repeat scroll top left" value="#000 none repeat scroll top left"/> <Variable name="body.font" description="Font" type="font" default="normal normal 14px 'roboto', sans-serif" value="normal normal 14px &#39;roboto&#39;, sans-serif"/> <Variable name="body.text.color" description="Text Color" type="color" default="#222" value="#222222"/> <Variable name="body.text.font" description="2" type="font" default="$(body.font)" value="normal normal 14px &#39;roboto&#39;, sans-serif"/> <Variable name="posts.background.color" description="6" type="color" default="transparent" value="transparent"/> <Variable name="body.link.color" description="7" type="color" default="#2196f3" value="#2196f3"/> <Variable name="body.link.visited.color" description="8" type="color" default="$(body.link.color)" value="#2196f3"/> <Variable name="body.link.hover.color" description="9" type="color" default="$(body.link.color)" value="#2196f3"/> <Variable name="blog.title.font" description="10" type="font" default="$(robotoBold45)" value="$(robotoBold45)"/> <Variable name="blog.title.color" description="11" type="color" default="#fff" value="#ffffff"/> <Variable name="header.icons.color" description="12" type="color" default="#fff" value="#ffffff"/> <Variable name="tabs.font" description="13" type="font" family="$(body.font.family)" size="$(body.font.size)" default="700 normal $(size) $(family)" value="700 normal $(size) $(family)"/> <Variable name="tabs.color" description="14" type="color" default="#ccc" value="#cccccc"/> <Variable name="tabs.selected.color" description="15" type="color" default="#fff" value="#ffffff"/> <Variable name="tabs.overflow.background.color" description="16" type="color" default="$(posts.background.color)" value="#ffffff"/> <Variable name="tabs.overflow.color" description="17" type="color" default="$(posts.text.color)" value="#222222"/> <Variable name="tabs.overflow.selected.color" description="18" type="color" default="$(posts.title.color)" value="#212121"/> <Variable name="posts.title.color" description="19" type="color" default="#212121" value="#212121"/> <Variable name="posts.title.font" description="20" type="font" default="$(robotoBold22)" value="$(robotoBold22)"/> <Variable name="posts.text.font" description="21" type="font" default="$(body.text.font)" value="normal normal 14px &#39;roboto&#39;, sans-serif"/> <Variable name="posts.text.color" description="22" type="color" default="$(body.text.color)" value="#222222"/> <Variable name="posts.icons.color" description="23" type="color" default="#707070" value="#707070"/> <Variable name="labels.background.color" description="24" type="color" default="$(sidebar.backgroundColorTopHD)" value="$(sidebar.backgroundColorTopHD)"/> </Group>

]]></b:skin>

</head>

<body>
<span itemscope='itemscope' itemtype='http://schema.org/WebPage'>

<header itemprop='mainEntity' itemscope='itemscope' itemtype='http://schema.org/WPHeader'>
 <b:section class='Header' id='Header' maxwidgets='2' showaddelement='yes'>
   <b:widget id='Header1' locked='true' title='Kerangka Jarwo (Header)' type='Header' version='1'>
     <b:widget-settings>
       <b:widget-setting name='displayUrl'/>
       <b:widget-setting name='displayHeight'>0</b:widget-setting>
       <b:widget-setting name='sectionWidth'>-1</b:widget-setting>
       <b:widget-setting name='useImage'>false</b:widget-setting>
       <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
       <b:widget-setting name='imagePlacement'>BEHIND</b:widget-setting>
       <b:widget-setting name='displayWidth'>0</b:widget-setting>
     </b:widget-settings>
     <b:includable id='main'>
<b:if cond='data:useImage'>
<b:if cond='data:imagePlacement == &quot;REPLACE&quot;'>
<div id='header-inner'>
 <a expr:href='data:blog.homepageUrl' style='display: block'>
 <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width'/>
 </a>
</div>

<b:else/>

<div id='header-inner'>
 <a expr:href='data:blog.homepageUrl' style='display: block'>
 <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width'/>
 </a>
</div>

</b:if>

<b:else/>

<div id='header-inner'>
 <div id='titlewrapper'>
  <b:if cond='data:blog.pageType != &quot;item&quot;'>
   <div id='logo'/><h1 class='site-title' itemprop='headline'><b:include name='title'/></h1>
  </b:if>
  <b:if cond='data:blog.pageType == &quot;item&quot;'>
   <div id='logo'/><h2 class='site-title' itemprop='headline'><b:include name='title'/></h2>
  </b:if>
 </div>
</div>

</b:if>
       <b:include name='description'/>
     </b:includable>
     <b:includable id='description'>
  <div class='descriptionwrapper'>
    <p class='description'><data:description/></p>
  </div>
</b:includable>
     <b:includable id='title'>
<a expr:href='data:blog.homepageUrl' expr:title='data:title' itemprop='url'>
 <span class='notranslate' itemprop='name'><data:title/></span>
</a>
     </b:includable>
   </b:widget>
 </b:section>
</header>

<span id='wrapper'>

<main itemscope='itemscope' itemtype='http://schema.org/Blog' role='main'>
 <b:if cond='data:blog.pageType == &quot;error_page&quot;'>
  <div id='error-page'>
   <div id='error-inner'><h3>Error</h3>
   <div class='box-404'><div>404</div></div>
   <h2>LAMAN TIDAK DITEMUKAN</h2>
   <p>Maaf, laman yang anda cari tidak ada. Kembali ke <a href='/'><data:blog.pageTitle/></a>.</p>
   </div>
  </div>
 </b:if>
 <b:section class='Postingan' id='Postingan' showaddelement='yes'>
   <b:widget id='Blog1' locked='true' title='Posting Blog' type='Blog' version='1'>
     <b:widget-settings>
       <b:widget-setting name='showDateHeader'>false</b:widget-setting>
       <b:widget-setting name='style.textcolor'>#2196f3</b:widget-setting>
       <b:widget-setting name='showShareButtons'>false</b:widget-setting>
       <b:widget-setting name='authorLabel'>Diposkan oleh</b:widget-setting>
       <b:widget-setting name='showCommentLink'>true</b:widget-setting>
       <b:widget-setting name='style.urlcolor'>#212121</b:widget-setting>
       <b:widget-setting name='showAuthor'>false</b:widget-setting>
       <b:widget-setting name='style.linkcolor'>#222222</b:widget-setting>
       <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
       <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
       <b:widget-setting name='timestampLabel'>-</b:widget-setting>
       <b:widget-setting name='showAuthorProfile'>false</b:widget-setting>
       <b:widget-setting name='style.layout'>1x1</b:widget-setting>
       <b:widget-setting name='showLabels'>false</b:widget-setting>
       <b:widget-setting name='showLocation'>false</b:widget-setting>
       <b:widget-setting name='showTimestamp'>false</b:widget-setting>
       <b:widget-setting name='postsPerAd'>1</b:widget-setting>
       <b:widget-setting name='showBacklinks'>false</b:widget-setting>
       <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
       <b:widget-setting name='showInlineAds'>false</b:widget-setting>
       <b:widget-setting name='showReactions'>false</b:widget-setting>
     </b:widget-settings>
     <b:includable id='main' var='top'>
<b:include data='posts' name='breadcrumb'/><b:if cond='data:mobile == &quot;false&quot;'>
<div class='blog-posts hfeed'><data:defaultAdStart/><b:loop values='data:posts' var='post'>

<div class='post-outer'><b:include data='post' name='post'/><b:if cond='data:blog.pageType == &quot;static_page&quot;'><b:if cond='data:post.showThreadedComments'><b:include data='post' name='comments'/><b:else/><b:include data='post' name='comments'/></b:if></b:if><b:if cond='data:blog.pageType == &quot;item&quot;'><b:if cond='data:post.showThreadedComments'><b:include data='post' name='comments'/><b:else/><b:include data='post' name='comments'/></b:if></b:if></div>

<b:if cond='data:post.includeAd'><b:if cond='data:post.isFirstPost'><data:defaultAdEnd/><b:else/><data:adEnd/></b:if></b:if></b:loop><b:if cond='data:numPosts != 0'>&lt;/div&gt;&lt;/div&gt;</b:if><data:adEnd/></div><div class='clear'/><b:if cond='data:blog.pageType != &quot;item&quot;'><b:include name='nextprev'/></b:if><b:include name='feedLinks'/><b:if cond='data:top.showStars'><script src='//www.google.com/jsapi'/><script>google.load(&quot;annotations&quot;,&quot;1&quot;,{&quot;locale&quot;:&quot;<data:top.languageCode/>&quot;});function initialize(){google.annotations.setApplicationId(<data:top.blogspotReviews/>);google.annotations.createAll();google.annotations.fetch();}google.setOnLoadCallback(initialize);</script></b:if><b:else/><b:include name='mobile-main'/></b:if><b:if cond='data:top.showDummy'><data:top.dummyBootstrap/></b:if>
     </b:includable>
     <b:includable id='backlinkDeleteIcon' var='backlink'>
<span expr:class='&quot;item-control &quot; + data:backlink.adminClass'><a expr:href='data:backlink.deleteUrl' expr:title='data:top.deleteBacklinkMsg'/></span></b:includable>
     <b:includable id='backlinks' var='post'>
<a name='links'/><h4><data:post.backlinksLabel/></h4><b:if cond='data:post.numBacklinks != 0'><dl class='comments-block' id='comments-block'><b:loop values='data:post.backlinks' var='backlink'><div class='collapsed-backlink backlink-control'><dt class='comment-title'><span class='backlink-toggle-zippy'>&#160;</span><a expr:href='data:backlink.url' rel='nofollow'><data:backlink.title/></a><b:include data='backlink' name='backlinkDeleteIcon'/></dt><dd class='comment-body collapseable'><data:backlink.snippet/></dd><dd class='comment-footer collapseable'><span class='comment-author'><data:post.authorLabel/> <data:backlink.author/></span><span class='comment-timestamp'><data:post.timestampLabel/> <data:backlink.timestamp/></span></dd></div></b:loop></dl></b:if><p class='comment-footer'><a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + &quot;_backlinks-create-link&quot;' rel='nofollow' target='_blank'><data:post.createLinkLabel/></a></p></b:includable>
     <b:includable id='breadcrumb'><b:if cond='data:blog.homepageUrl != data:blog.url'>
<b:if cond='data:blog.pageType == &quot;item&quot;'><b:loop values='data:posts' var='post'><b:if cond='data:post.labels'><div class='breadcrumbs' xmlns:v='http://rdf.data-vocabulary.org/#'><span typeof='v:Breadcrumb'><a expr:href='data:blog.homepageUrl' property='v:title' rel='v:url'>Beranda</a></span><b:loop values='data:post.labels' var='label'> &#187; <span typeof='v:Breadcrumb'><a expr:href='data:label.url + &quot;?&amp;amp;max-results=6&quot;' property='v:title' rel='v:url'><data:label.name/></a></span></b:loop> &#187; <span><data:post.title/></span></div><b:else/><div class='breadcrumbs'><span><a expr:href='data:blog.homepageUrl' rel='tag'>Beranda</a></span> &#187; <span>Tidak berkategori</span> &#187; <span><data:post.title/></span></div>
</b:if></b:loop></b:if></b:if></b:includable>
     <b:includable id='comment-form' var='post'>
<div class='comment-form' id='comment-form'><a name='comment-form'/><b:if cond='data:mobile'><h4 id='comment-post-message'><a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'><data:postCommentMsg/></a></h4><p><data:blogCommentMessage/></p><data:blogTeamBlogMessage/><a expr:href='data:post.commentFormIframeSrc + &quot;&amp;skin=contempo#%7B&quot; + data:variantParam' id='comment-editor-src'/><iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/><b:else/><h4 id='comment-post-message'><data:postCommentMsg/></h4><p><data:blogCommentMessage/></p><data:blogTeamBlogMessage/><a expr:href='data:post.commentFormIframeSrc + &quot;&amp;skin=contempo#%7B&quot; + data:variantParam' id='comment-editor-src'/><iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/></b:if><data:post.friendConnectJs/><data:post.cmtfpIframe/><script>BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;,&#39;<data:post.communityId/>&#39;);</script></div></b:includable>
     <b:includable id='commentDeleteIcon' var='comment'>
<span expr:class='&quot;item-control &quot; + data:comment.adminClass'><b:if cond='data:showCmtPopup'><div class='goog-toggle-button'><div class='goog-inline-block comment-action-icon'/></div><b:else/><a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'><img src='//www.blogger.com/img/icon_delete13.gif'/></a></b:if></span></b:includable>
     <b:includable id='comment_count_picker' var='post'>
<b:if cond='data:post.commentSource == 1'><span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-post-url='data:post.url' expr:data-url='data:post.canonicalUrl'/><b:else/><b:if cond='data:post.numComments == 0'><div expr:id='&quot;IDCommentPostInfoTitle&quot;+data:post.id' style='display:none'><data:post.title/></div><div expr:id='&quot;IDCommentPostInfoTime&quot;+data:post.id' style='display:none'><data:post.timestampISO8601/></div><div expr:id='&quot;IDCommentPostInfoAuthor&quot;+data:post.id' style='display:none'><data:post.author/></div><div expr:id='&quot;IDCommentPostInfoCats&quot;+data:post.id' style='display:none'><b:if cond='data:post.labels'><b:loop values='data:post.labels' var='label'><data:label.name/>|</b:loop></b:if></div> <a class='IDCommentsReplace' expr:href='data:post.url' expr:name='data:post.id'>Comments</a><b:else/><a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:post.commentLabelFull/>:</a></b:if></b:if>
</b:includable>
     <b:includable id='comment_picker' var='post'>
<b:if cond='data:post.commentSource == 1'><b:include data='post' name='iframe_comments'/><b:else/><b:if cond='data:post.showThreadedComments'><b:if cond='data:post.numComments == 0'><div id='IDCommentInfoPostTitle' style='display:none'><data:post.title/></div><div id='IDCommentInfoPostTime' style='display:none'><data:post.timestampISO8601/></div><div id='IDCommentInfoPostAuthor' style='display:none'><data:post.author/></div><div id='IDCommentInfoPostCats' style='display:none'><b:if cond='data:post.labels'><b:loop values='data:post.labels' var='label'><data:label.name/>|</b:loop></b:if></div>  <script>var idcomments_acct=&#39;d0ea8af77644441de96ede5097fb68c2&#39;; var idcomments_post_id=&#39;<data:post.id/>&#39;; var idcomments_post_url=&#39;<data:post.url/>&#39;; var idcomments_post_title=document.getElementById(&#39;IDCommentInfoPostTitle&#39;).innerHTML;var idcomments_post_author=document.getElementById(&#39;IDCommentInfoPostAuthor&#39;).innerHTML;var idcomments_post_time=document.getElementById(&#39;IDCommentInfoPostTime&#39;).innerHTML;var idcomments_post_cats=document.getElementById(&#39;IDCommentInfoPostCats&#39;).innerHTML; var commentScriptWrapper = document.createElement(&#39;SCRIPT&#39;);commentScriptWrapper.type = &#39;text/javascript&#39;;commentScriptWrapper.src = &#39;https://www.intensedebate.com/js/bloggerTemplateCommentWrapper2.php?acct=&#39;+idcomments_acct+&#39;&amp;postid=&#39;+idcomments_post_id+&#39;&amp;title=&#39;+encodeURIComponent(idcomments_post_title)+&#39;&amp;url=&#39;+idcomments_post_url+&#39;&amp;posttime=&#39;+encodeURIComponent(idcomments_post_time)+&#39;&amp;postauthor=&#39;+encodeURIComponent(idcomments_post_author)+&#39;&amp;postcats=&#39;+encodeURIComponent(idcomments_post_cats);document.getElementsByTagName(&#39;HEAD&#39;)[0].appendChild(commentScriptWrapper);</script><b:else/><b:include data='post' name='comments'/></b:if><b:else/><b:if cond='data:post.numComments == 0'><div id='IDCommentInfoPostTitle' style='display:none'><data:post.title/></div><div id='IDCommentInfoPostTime' style='display:none'><data:post.timestampISO8601/></div><div id='IDCommentInfoPostAuthor' style='display:none'><data:post.author/></div><div id='IDCommentInfoPostCats' style='display:none'><b:if cond='data:post.labels'><b:loop values='data:post.labels' var='label'><data:label.name/>|</b:loop></b:if></div>  <script>var idcomments_acct=&#39;d0ea8af77644441de96ede5097fb68c2&#39;; var idcomments_post_id=&#39;<data:post.id/>&#39;; var idcomments_post_url=&#39;<data:post.url/>&#39;; var idcomments_post_title=document.getElementById(&#39;IDCommentInfoPostTitle&#39;).innerHTML;var idcomments_post_author=document.getElementById(&#39;IDCommentInfoPostAuthor&#39;).innerHTML;var idcomments_post_time=document.getElementById(&#39;IDCommentInfoPostTime&#39;).innerHTML;var idcomments_post_cats=document.getElementById(&#39;IDCommentInfoPostCats&#39;).innerHTML; var commentScriptWrapper = document.createElement(&#39;SCRIPT&#39;);commentScriptWrapper.type = &#39;text/javascript&#39;;commentScriptWrapper.src = &#39;https://www.intensedebate.com/js/bloggerTemplateCommentWrapper2.php?acct=&#39;+idcomments_acct+&#39;&amp;postid=&#39;+idcomments_post_id+&#39;&amp;title=&#39;+encodeURIComponent(idcomments_post_title)+&#39;&amp;url=&#39;+idcomments_post_url+&#39;&amp;posttime=&#39;+encodeURIComponent(idcomments_post_time)+&#39;&amp;postauthor=&#39;+encodeURIComponent(idcomments_post_author)+&#39;&amp;postcats=&#39;+encodeURIComponent(idcomments_post_cats);document.getElementsByTagName(&#39;HEAD&#39;)[0].appendChild(commentScriptWrapper);</script><b:else/><b:include data='post' name='comments'/></b:if></b:if></b:if></b:includable>
     <b:includable id='comments' var='post'>
<b:if cond='data:post.allowComments'>
<div class='comments' id='comments'><b:if cond='data:post.allowComments'>
  <h3><data:post.numComments/> komentar untuk <data:blog.pageName/></h3>
<b:if cond='data:post.commentPagingRequired'><span class='paging-control-container'><a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>&#160;<a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>&#160;<data:post.commentRangeText/>&#160;<a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>&#160;<a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
</span>
</b:if>
<div class='clear'/>
<b:if cond='data:post.commentPagingRequired'>
<span class='paging-control-container'>
<a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>
&#160;
<a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>
&#160;
<data:post.commentRangeText/>
&#160;
<a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>
&#160;
<a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
</span>
</b:if>
<div class='clear'/>
<div class='comment_form'>
<b:if cond='data:post.embedCommentForm'>
<b:if cond='data:post.allowNewComments'>
<b:include data='post' name='threaded-comment-form'/>
<b:else/>
<data:post.noNewCommentsText/>
</b:if>
<b:else/>
<b:if cond='data:post.allowComments'>
<a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick' expr:title='data:postCommentMsg'>Urungkan Membalas Komentar Ini</a>
</b:if>
</b:if>

<p class='persyaratan-comment' id='persyaratan-comment'><data:blogCommentMessage/></p>

</div>
<div id='comment_block'>
<b:loop values='data:post.comments' var='comment'>
<div class='kolomkomen data:comment.adminClass' expr:id='data:comment.anchorName'>
<b:if cond='data:post.adminClass == data:comment.adminClass'>
&lt;div class=&#39;comment_inner comment_admin&#39;&gt;
<b:else/>
&lt;div class=&#39;comment_inner&#39;&gt;
</b:if>

<div class='comment_body'>
<div class='comment_avatar_wrap'>
<div class='comment_avatar'>
<img alt='avatar' expr:src='data:comment.authorAvatarSrc' expr:title='data:comment.author'/>
</div>
</div>
<span class='comment_arrow'/>
<div class='comment_name'>
<b:if cond='data:comment.authorUrl'><a expr:href='data:comment.authorUrl' rel='nofollow'>
<data:comment.author/>
</a></b:if>
<b:if cond='data:comment.author == data:post.author'>
<span class='comment_author_flag'>
<img alt='avatar' class='comment_author_flag' src='https://cdn0.iconfinder.com/data/icons/small-n-flat/24/678134-sign-check-128.png'/>
</span>
  </b:if><br/>
<span class='comment_service'>
<span class='comment_date'><a expr:href='data:comment.url' rel='nofollow' title='Link Komentar'>#
</a><data:comment.timestamp/>
</span>
</span></div>

<b:if cond='data:comment.isDeleted'>
<span class='deleted-comment'><data:comment.body/></span>
<b:else/>
<p><data:comment.body/></p>
<a class='comment_reply' expr:href='&quot;#r_&quot;+data:comment.anchorName' expr:id='&quot;r&quot;+data:comment.anchorName' onclick='javascript:Display_Reply_Form(this)' title='Balas'>Balas</a>
<a class='comment_reply' expr:href='&quot;http://www.blogger.com/delete-comment.g?blogID=&quot; + data:blog.blogId + &quot;&amp;amp;postID=&quot; + data:comment.id' expr:title='data:top.deleteCommentMsg'>Hapus</a>
<div class='clear'/>
</b:if>

</div>

<div class='clear'/>
&lt;/div&gt;
<div class='clear'/>
<div class='comment_child'/>
<div class='comment_reply_form' expr:id='&quot;r_f_&quot;+data:comment.anchorName'/>
</div>
</b:loop>
</div>
<div class='clear'/>

</b:if>
</div>
<script async='async' expr:src='data:post.commentSrc'/>     
<script>
      
         <b:if cond='data:post.numComments != 0'>
         var Items = <data:post.commentJso/>;
         var Msgs = <data:post.commentMsgs/>;
         var Config = <data:post.commentConfig/>;
        <b:else/>
         var Items = {};
         var Msgs = {};
         var Config = {&#39;maxThreadDepth&#39;:&#39;0&#39;};
        </b:if>
       //<![CDATA[
Config.maxThreadDepth=3;Display_Emo=true;Replace_Youtube_Link=true;Replace_Image_Link=true;Replace_Force_Tag=true;Replace_Image_Ext=['JPG','GIF','PNG','BMP'];Emo_List = [
':)'  	,'//twemoji.maxcdn.com/36x36/1f600.png',
':('  	,'//twemoji.maxcdn.com/36x36/1f615.png',
'hihi'  ,'//twemoji.maxcdn.com/36x36/1f601.png',
':-)'  	,'//twemoji.maxcdn.com/36x36/1f60f.png',
':D'  	,'//twemoji.maxcdn.com/36x36/1f603.png',
'=D'  	,'//twemoji.maxcdn.com/36x36/1f62c.png',
':-d'  	,'//twemoji.maxcdn.com/36x36/1f604.png',
';('  	,'//twemoji.maxcdn.com/36x36/1f61e.png',
';-('  	,'//twemoji.maxcdn.com/36x36/1f62d.png',
'@-)'   ,'//twemoji.maxcdn.com/36x36/1f616.png',
':P'  	,'//twemoji.maxcdn.com/36x36/1f61c.png',
':o'	,'//twemoji.maxcdn.com/36x36/1f62e.png',     
':&gt;)','//twemoji.maxcdn.com/36x36/1f606.png',     
'(o)'	,'//twemoji.maxcdn.com/36x36/1f609.png',     
':p'	,'//twemoji.maxcdn.com/36x36/1f614.png',     
'(p)'	,'//twemoji.maxcdn.com/36x36/1f619.png', 
':-s'	,'//twemoji.maxcdn.com/36x36/1f625.png',
'(m)'	,'//twemoji.maxcdn.com/36x36/1f620.png',
'8-)'	,'//twemoji.maxcdn.com/36x36/1f60e.png',
':-t'	,'//twemoji.maxcdn.com/36x36/1f624.png',
':-b'	,'//twemoji.maxcdn.com/36x36/1f634.png',
'b-('	,'//twemoji.maxcdn.com/36x36/1f635.png',
'$-)'	,'//twemoji.maxcdn.com/36x36/1f4b5.png',
'(y)'	,'//twemoji.maxcdn.com/36x36/1f44d.png',
'x-)'	,'//twemoji.maxcdn.com/36x36/1f60d.png',
'(k)'	,'//twemoji.maxcdn.com/36x36/1f496.png',
        ];

Force_Tag=['[pre]','<pre>','[/pre]','</pre>','<pre class="brush: plain; title: ; notranslate" title="">','&lt;code&gt;','</pre>','</code>'];

Force_Tag=['[style]','&lt;style&gt;','[/style]','&lt;/style&gt;','[pre]','<pre>','[/pre]','</pre>','<pre class="brush: plain; title: ; notranslate" title="">','&lt;code&gt;','</pre>','</code>'];eval(function(p,a,c,k,e,r){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return'\\w+'};c=1};while(c--)if(k[c])p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c]);return p}('3 q=\'.W\';3 1a=$(\'#N-Y\').B(\'y\');u 1w(H){3 1h=\' \\n\\r\\t\\f\\2p\\1S\\1T\\1U\\24\\25\\26\\27\\2e\\2h\\2k\\2m\\2n\\2u\\2y\\2z\\2A\\2F\\1L\\1N\\1O\\1P\\1Q\';G(3 i=0;i<H.5;i++){b(1h.g(H.1V(i))!=-1){H=H.d(0,i);11}}C H}$(\'#28 .1B p\').k(u(D,7){b(2r){3 m=\'1g://13.Z.X/1t?v=\';3 8=7.g(m);F(8!=-1){1H=7.d(8);K=1w(1H);3 1c=K.g(\'&\');3 T=\'\';b(1c==-1){T=K.d(m.5)}1e{T=K.d(m.5,1c)}3 1j=\'<1k I="1W" y="1g://13.Z.X/1X/\'+T+\'?1Y=1" 20="0" 21></1k>\';7=7.d(0,8)+1j+7.d(8+K.5);8=7.g(m);b(8==-1){m=\'22://13.Z.X/1t?v=\';8=7.g(m)}}}b(23){3 1d=\'\';3 x=7;G(3 i=0;i<1z.5;i++){3 m=\'.\'+1z[i];3 o=x.E();3 8=o.g(m);F(8!=-1){l=x.d(0,8+m.5);o=l.E();3 w=\'2j://\';3 z=o.g(w);3 L=\'\';F(z!=-1){L=w.R();l=l.d(z+w.5);o=l.E();z=o.g(w)}w=\'1K://\';o=l.E();z=o.g(w);F(z!=-1){L=w.R();l=l.d(z+w.5);o=l.E();z=o.g(w)}b(L==\'\'||l.5<6){11}l=L+l;1d+=x.d(0,8+m.5-l.5)+\'<S y="\'+l+\'" I="2s"/>\';x=x.d(8+m.5);o=x.E();8=o.g(m)}}7=1d+x}b(1m){3 5=A.5;b(5%2==1){5--}G(3 i=0;i<5;i+=2){3 V=\'<S y="\'+A[i+1]+\'" I="1x"/>\';8=7.g(A[i]);F(8!=-1){7=7.d(0,8)+V+7.d(8+A[i].5);8=7.g(A[i])}}}b(2G){3 5=U.5;b(5%2==1){5--}G(3 i=0;i<5;i+=2){F(1){3 x=7.R();8=x.g(U[i]);b(8!=-1){7=7.d(0,8)+U[i+1]+7.d(8+U[i].5)}1e{11}}}}C 7});$(\'.1M\').k(u(D,7){b(1m){3 5=A.5;b(5%2==1){5--}3 15=\'\';G(3 i=0;i<5;i+=2){3 1C=\'<1F>\'+A[i]+\'</1F>\';3 V=\'<S y="\'+A[i+1]+\'" I="1x"/>\';15+=\'<M I="1R">\'+V+1C+\'</M>\'}C 15}});$(\'.1f .1B p\').k(u(i,h){10=h.R();D=10.g(\'@<a 12="#c\');b(D!=-1){14=10.g(\'</a>\',D);b(14!=-1){h=h.d(0,D)+h.d(14+4)}}C h});u 1l(j){r=j.g(\'c\');b(r!=-1)j=j.d(r+1);C j}u 1n(j){j=\'&1Z=\'+j+\'#%1o\';1p=1a.1q(/#%1o/,j);C 1p}u 1r(){k=$(q).k();$(q).k(\'\');q=\'.W\';$(q).k(k);$(\'#N-Y\').B(\'y\',1a)}u 1s(e){j=$(e).B(\'16\');j=1l(j);k=$(q).k();b(q==\'.W\'){1u=\'<a 12="#1v" 29="1r()">\'+2a.2b+\'</a><a 2c="1v"/>\';$(q).k(1u)}1e{$(q).k(\'\')}q=\'#2d\'+j;$(q).k(k);$(\'#N-Y\').B(\'y\',1n(j))}17=2f.2g.12;18=\'#N-2i\';19=17.g(18);b(19!=-1){1y=17.d(19+18.5);1s(\'#2l\'+1y)}G(3 i=0;i<O.5;i++){b(\'1A\'2o O[i]){3 j=O[i].1A;3 1b=2q($(\'#c\'+j+\':P\').B(\'1D-1E\'));$(\'#c\'+j+\' .2t:P\').k(u(D,7){3 J=O[i].16;b(1b>=2v.2w){$(\'#c\'+J+\':P .2x\').1G()}3 Q=$(\'#c\'+J+\':P\').k();Q=\'<M I="1f" 16="c\'+J+\'" 1D-1E="\'+(1b+1)+\'">\'+Q+\'</M>\';$(\'#c\'+J).1G();C(7+Q)})}}3 1I=$("#2B");1I.2C(\'.2D S\').2E(u(){3 1J=$(1i).B(\'y\');$(1i).2H().B(\'y\',1J.1q(/\\/s[0-9]+(\\-c)?\\//,"/2I-c/"))});',62,169,'|||var||length||oldhtml|check_index|||if||substring|||indexOf|||par_id|html|img_src|search_key||upper_html||Cur_Cform_Hdr||||function||http_search|temp_html|src|find_http|Emo_List|attr|return|index|toUpperCase|while|for|str|class|child_id|yt_link|save_http|div|comment|Items|first|child_html|toLowerCase|img|yt_code|Force_Tag|img_html|comment_form|com|editor|youtube|temp|break|href|www|index_tail|newhtml|id|cur_url|search_formid|search_index|Cur_Cform_Url|par_level|yt_code_index|save_html|else|comment_wrap|http|whitespace|this|yt_video|iframe|Valid_Par_Id|Display_Emo|Cform_Ins_ParID|7B|n_cform_url|replace|Reset_Comment_Form|Display_Reply_Form|watch|reset_html|origin_cform|trim|comment_emo|ret_id|Replace_Image_Ext|parentId|comment_body|img_code|data|level|span|remove|ht|avatar|ava|HTTPS|u200a|comment_emo_list|u200b|u2028|u2029|u3000|item|x5d|x7c|x7d|charAt|comment_youtube|embed|autohide|parentID|frameborder|allowfullscreen|https|Replace_Image_Link|x3c|x3e|x0b|xa0|comment_block|onclick|Msgs|addComment|name|r_f_c|u2000|window|location|u2001|form_|HTTP|u2002|rc|u2003|u2004|in|x5b|parseInt|Replace_Youtube_Link|comment_img|comment_child|u2005|Config|maxThreadDepth|comment_reply|u2006|u2007|u2008|comments|find|comment_avatar|each|u2009|Replace_Force_Tag|show|s45'.split('|'),0,{}))
;this['eval'](this['unescape']('%3B%76ar%20%65m%3D33enolc%3B'));
//]]></script> 
</b:if>
</b:includable>
     <b:includable id='feedLinks'><b:if cond='data:blog.pageType != &quot;item&quot;'><b:if cond='data:feedLinks'><div class='blog-feeds'><b:include data='feedLinks' name='feedLinksBody'/></div></b:if><b:else/><div class='post-feeds'><b:loop values='data:posts' var='post'><b:if cond='data:post.allowComments'><b:if cond='data:post.feedLinks'><b:include data='post.feedLinks' name='feedLinksBody'/></b:if></b:if></b:loop></div></b:if></b:includable>
     <b:includable id='feedLinksBody' var='links'/>
     <b:includable id='iframe_comments' var='post'>
<b:includable id='feedLinks'><b:if cond='data:blog.pageType != &quot;item&quot;'><b:if cond='data:feedLinks'><div class='blog-feeds'><b:include data='feedLinks' name='feedLinksBody'/></div></b:if><b:else/><div class='post-feeds'><b:loop values='data:posts' var='post'><b:if cond='data:post.allowComments'><b:if cond='data:post.feedLinks'><b:include data='post.feedLinks' name='feedLinksBody'/></b:if></b:if></b:loop></div></b:if></b:includable><b:includable id='feedLinksBody' var='links'/><b:if cond='data:post.allowComments'><script expr:src='data:post.commentSrc'/><div class='cmt_iframe_holder'/><b:if cond='data:post.embedCommentForm == &quot;false&quot;'><a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a></b:if></b:if></b:includable>
     <b:includable id='mobile-index-post' var='post'/>
     <b:includable id='mobile-main' var='top'/>
     <b:includable id='mobile-nextprev'/>
     <b:includable id='mobile-post' var='post'/>
     <b:includable id='nextprev'>
      <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <span id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><data:newerPageTitle/></a>
      </span>
    </b:if>
    <b:if cond='data:olderPageUrl'>
      <span id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><data:olderPageTitle/></a>
      </span>
    </b:if>
    <div class='mobile-desktop-link'>
      <a class='home-link' expr:href='data:desktopLinkUrl' expr:title='data:homeMsg'><data:desktopLinkMsg/></a>
    </div>
  </div>
  <div class='clear'/>
     </b:includable>
     <b:includable id='post' var='post'>

<div class='post hentry' itemprop='blogPost' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>

<b:if cond='data:blog.pageType == &quot;static_page&quot; or data:blog.pageType == &quot;item&quot;'> <div class='title-wrapper'>
  <h1 class='post-title entry-title' itemprop='headline'>
   <b:if cond='data:post.url'>
    <a expr:href='data:post.url' itemprop='url mainEntityOfPage'><data:post.title/></a>
   <b:else/>
    <data:post.title/>
   </b:if>
  </h1>
 </div>
  <b:else/>
 <div class='thumbnail-post'>
  <a expr:href='data:post.url'>
   <img class='thumbnail-post' expr:alt='data:post.title' expr:src='data:post.thumbnailUrl'/>
   <div itemprop='image' itemscope='itemscope' itemtype='https://schema.org/ImageObject'>
    <meta expr:content='data:post.thumbnailUrl' itemprop='url'/>
   </div>
  </a>
 </div>
 <div class='entry-header'>
  <h2 class='post-title entry-title' itemprop='headline'>
   <b:if cond='data:post.link'>
    <a expr:href='data:post.link' expr:title='data:post.title' itemprop='url mainEntityOfPage'><data:post.title/></a>
   <b:else/>
   <b:if cond='data:post.url'>
    <a expr:href='data:post.url' expr:title='data:post.title' itemprop='url mainEntityOfPage'><data:post.title/></a>
   <b:else/>
   <data:post.title/>
   </b:if>
   </b:if>
  </h2>
 </div>
</b:if>

<b:if cond='data:blog.pageType == &quot;item&quot;'>
 <div class='post-info'>
  <b:include name='breadcrumb'/>
 </div>
</b:if>

<div class='post-author'>
 <img alt='author' expr:src='resizeImage(data:post.authorPhoto.url, 50)'/>
 <a expr:href='data:post.authorProfileUrl' rel='nofollow noopener external' target='_blank' title='author profile'>
  <span class='post-author vcard' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
   <span itemprop='name'><data:post.author/></span>
   <meta expr:content='data:post.authorPhoto.url' itemprop='image'/>
   <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
  </span>
 </a>
</div>

<div class='post-tag'>
 <b:if cond='data:post.labels'>
  <b:loop values='data:post.labels' var='label'>
   <a expr:href='data:label.url' rel='tag'>
    <data:label.name/>
   </a>
  </b:loop>
 </b:if>
</div>

<div class='post-time'>
 <abbr class='updated' expr:title='data:post.timestampISO8601'><data:post.timestamp/></abbr>
 <meta expr:content='data:post.timestampISO8601' itemprop='dateModified'/>
 <meta expr:content='data:post.lastUpdatedISO8601' itemprop='datePublished'/>
 <span class='vcard'>
  <abbr class='fn' expr:title='data:post.author'/>
 </span>
</div>

<div class='post-body entry-content'>

<b:if cond='data:blog.pageType == &quot;static_page&quot; or data:blog.pageType == &quot;item&quot;'>
<article itemprop='articleBody'>
 <b:if cond='data:blog.pageType == &quot;item&quot;'>
  <data:post.body/>
 </b:if>
 <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
  <data:post.body/>
 </b:if>
 <div class='clear'/>
</article>
</b:if>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'><b:if cond='data:blog.pageType != &quot;item&quot;'>
 <div itemprop='articleBody'><data:post.snippet/></div>
</b:if></b:if>
<b:include name='post-info'/>
</div>

<div class='clear'/>

</div>

<div class='clear'/>

<b:if cond='data:blog.pageType == &quot;item&quot;'>
  <b:include name='nextprev'/>
</b:if>

</b:includable>
     <b:includable id='post-info'>
<b:if cond='data:blog.pageType == &quot;static_page&quot; or data:blog.pageType == &quot;item&quot;'>
 <div itemprop='image' itemscope='itemscope' itemtype='https://schema.org/ImageObject'>
  <meta expr:content='data:post.thumbnailUrl' itemprop='url'/>
 </div>
</b:if>

<div itemprop='publisher' itemscope='itemscope' itemtype='https://schema.org/Organization'>
 <div itemprop='logo' itemscope='itemscope' itemtype='https://schema.org/ImageObject'>
  <meta content='https://image.ibb.co/hqEdbc/KJ_min.png' itemprop='url'/>
 </div>
 <meta expr:content='data:blog.title' itemprop='name'/>
</div>
     </b:includable>
     <b:includable id='postQuickEdit' var='post'/>
     <b:includable id='quickedit'/>
     <b:includable id='shareButtons' var='post'/>
     <b:includable id='status-message'>
<b:if cond='data:navMessage'><div class='status-msg-wrap'><div class='status-msg-body'><data:navMessage/></div><div class='status-msg-border'><div class='status-msg-bg'><div class='status-msg-hidden'><data:navMessage/></div></div></div></div><div class='clear'/></b:if></b:includable>
     <b:includable id='threaded-comment-form' var='post'>
<div class='comment-form' id='comment-form'>
<a name='comment-form'/>

<b:if cond='data:mobile'>
 <data:blogTeamBlogMessage/>
 <a expr:href='data:post.commentFormIframeSrc + &quot;&amp;skin=contempo#%7B&quot; + data:variantParam' id='comment-editor-src'/>
 <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' data-resized='true' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
  <b:else/>
 <data:blogTeamBlogMessage/>
 <a expr:href='data:post.commentFormIframeSrc + &quot;&amp;skin=contempo#%7B&quot; + data:variantParam' id='comment-editor-src'/>
 <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' data-resized='true' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
</b:if>

<data:post.friendConnectJs/>
<data:post.cmtfpIframe/>
<script>BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;,&#39;<data:post.communityId/>&#39;);</script>
</div>
     </b:includable>
     <b:includable id='threaded_comment_js' var='post'>
<script async='async' expr:src='data:post.commentSrc'/>
<script>(function(){var items=<data:post.commentJso/>;var msgs=<data:post.commentMsgs/>;var config=<data:post.commentConfig/>;var cursor=null;items&amp;&amp;items.length&gt;0&amp;&amp;(cursor=parseInt(items[items.length-1].timestamp)+1);var bodyFromEntry=function(a){if(a.gd$extendedProperty)for(var b in a.gd$extendedProperty)if(&quot;blogger.contentRemoved&quot;==a.gd$extendedProperty[b].name)return&#39;&lt;span class=&quot;deleted-comment&quot;&gt;&#39;+a.content.$t+&quot;&lt;/span&gt;&quot;;return a.content.$t},parse=function(a){cursor=null;var b=[];if(a&amp;&amp;a.feed&amp;&amp;a.feed.entry)for(var d,c=0;d=a.feed.entry[c];c++){var e={},f=/blog-(\d+).post-(\d+)/.exec(d.id.$t);if(e.id=f?f[2]:null,e.body=bodyFromEntry(d),e.timestamp=Date.parse(d.published.$t)+&quot;&quot;,d.author&amp;&amp;d.author.constructor===Array){var g=d.author[0];g&amp;&amp;(e.author={name:g.name?g.name.$t:void 0,profileUrl:g.uri?g.uri.$t:void 0,avatarUrl:g.gd$image?g.gd$image.src:void 0})}if(d.link&amp;&amp;(d.link[2]&amp;&amp;(e.link=e.permalink=d.link[2].href),d.link[3])){var h=/.*comments\/default\/(\d+)\?.*/.exec(d.link[3].href);h&amp;&amp;h[1]&amp;&amp;(e.parentId=h[1])}if(e.deleteclass=&quot;item-control blog-admin&quot;,d.gd$extendedProperty)for(var i in d.gd$extendedProperty)&quot;blogger.itemClass&quot;==d.gd$extendedProperty[i].name&amp;&amp;(e.deleteclass+=&quot; &quot;+d.gd$extendedProperty[i].value);b.push(e)}return b},paginator=function(a){if(hasMore()){var b=config.feed+&quot;?alt=json&amp;v=2&amp;orderby=published&amp;reverse=false&amp;max-results=50&quot;;cursor&amp;&amp;(b+=&quot;&amp;published-min=&quot;+new Date(cursor).toISOString()),window.bloggercomments=function(b){var c=parse(b);cursor=c.length&lt;50?null:parseInt(c[c.length-1].timestamp)+1,a(c),window.bloggercomments=null},b+=&quot;&amp;callback=bloggercomments&quot;;var c=document.createElement(&quot;script&quot;);c.type=&quot;text/javascript&quot;,c.src=b,document.getElementsByTagName(&quot;head&quot;)[0].appendChild(c)}},hasMore=function(){return!!cursor},getMeta=function(a,b){if(&quot;iswriter&quot;==a){var c=!!b.author&amp;&amp;b.author.name==config.authorName&amp;&amp;b.author.profileUrl==config.authorUrl;return c?&quot;true&quot;:&quot;&quot;}return&quot;deletelink&quot;==a?config.baseUri+&quot;/delete-comment.g?blogID=&quot;+config.blogId+&quot;&amp;postID=&quot;+b.id:&quot;deleteclass&quot;==a?b.deleteclass:&quot;&quot;},replybox=null,replyUrlParts=null,replyParent=void 0,onReply=function(a,b){null==replybox&amp;&amp;(replybox=document.getElementById(&quot;comment-editor&quot;),null!=replybox&amp;&amp;(replybox.height=&quot;250px&quot;,replybox.style.display=&quot;block&quot;,replyUrlParts=replybox.src.split(&quot;#&quot;))),replybox&amp;&amp;a!==replyParent&amp;&amp;(document.getElementById(b).insertBefore(replybox,null),replybox.src=replyUrlParts[0]+(a?&quot;&amp;parentID=&quot;+a:&quot;&quot;)+&quot;#&quot;+replyUrlParts[1],replyParent=a)},hash=(window.location.hash||&quot;#&quot;).substring(1),startThread,targetComment;/^comment-form_/.test(hash)?startThread=hash.substring(&quot;comment-form_&quot;.length):/^c[0-9]+$/.test(hash)&amp;&amp;(targetComment=hash.substring(1));var configJso={maxDepth:config.maxThreadDepth},provider={id:config.postId,data:items,loadNext:paginator,hasMore:hasMore,getMeta:getMeta,onReply:onReply,rendered:!0,initComment:targetComment,initReplyThread:startThread,config:configJso,messages:msgs},render=function(){if(window.goog&amp;&amp;window.goog.comments){var a=document.getElementById(&quot;comment-holder&quot;);window.goog.comments.render(a,provider)}};window.goog&amp;&amp;window.goog.comments?render():(window.goog=window.goog||{},window.goog.comments=window.goog.comments||{},window.goog.comments.loadQueue=window.goog.comments.loadQueue||[],window.goog.comments.loadQueue.push(render));})();</script>
     </b:includable>
     <b:includable id='threaded_comments' var='post'>
<div class='comments' id='comments'><a name='comments'/><h4><data:post.commentLabelFull/>:</h4><div class='comments-content'><b:if cond='data:post.embedCommentForm'><b:include data='post' name='threaded_comment_js'/></b:if><div id='comment-holder'><data:post.commentHtml/></div></div><p class='comment-footer'><b:if cond='data:post.allowNewComments'><b:include data='post' name='threaded-comment-form'/><b:else/><data:post.noNewCommentsText/></b:if></p><b:if cond='data:showCmtPopup'><div id='comment-popup'><iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'/></div></b:if><div id='backlinks-container'><div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'><b:if cond='data:post.showBacklinks'><b:include data='post' name='backlinks'/></b:if></div></div></div></b:includable>
   </b:widget>
 </b:section>
</main>

<aside itemprop='mainEntity' itemscope='itemscope' itemtype='http://schema.org/WPSideBar' role='complementary'>
 <div id='sidebar'>
  <b:section class='Sidebar' id='Sidebar' preferred='yes'>
    <b:widget id='PopularPosts1' locked='false' title='Postingan Populer' type='PopularPosts'>
      <b:widget-settings>
        <b:widget-setting name='numItemsToShow'>5</b:widget-setting>
        <b:widget-setting name='showThumbnails'>true</b:widget-setting>
        <b:widget-setting name='showSnippets'>false</b:widget-setting>
        <b:widget-setting name='timeRange'>LAST_YEAR</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content popular-posts'>
    <ul>
      <b:loop values='data:posts' var='post'>
      <li>
        <b:if cond='!data:showThumbnails'>
          <b:if cond='!data:showSnippets'>
            <!-- (1) No snippet/thumbnail -->
            <a expr:href='data:post.href'><data:post.title/></a>
          <b:else/>
            <!-- (2) Show only snippets -->
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <!-- (3) Show only thumbnails or (4) Snippets and thumbnails. -->
          <div expr:class='data:showSnippets ? &quot;item-content&quot; : &quot;item-thumbnail-only&quot;'>
            <b:if cond='data:post.featuredImage.isResizable or data:post.thumbnail'>
              <div class='item-thumbnail'>
                <a expr:href='data:post.href' target='_blank'>
                  <b:with value='data:post.featuredImage.isResizable                                  ? resizeImage(data:post.featuredImage, 72, &quot;1:1&quot;)                                  : data:post.thumbnail' var='image'>
                    <img alt='' border='0' expr:src='data:image'/>
                  </b:with>
                </a>
              </div>
            </b:if>
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <b:if cond='data:showSnippets'>
              <div class='item-snippet'><data:post.snippet/></div>
            </b:if>
          </div>
          <div style='clear: both;'/>
        </b:if>
      </li>
      </b:loop>
    </ul>
    <b:include name='quickedit'/>
  </div>
</b:includable>
    </b:widget>
  </b:section>
 </div>
</aside>

</span>

<footer itemprop='mainEntity' itemscope='itemscope' itemtype='http://schema.org/WPFooter'>
 <h3 id='footer'>
  Copyrights 2018 <a expr:href='data:blog.homepageUrl' expr:title='data:title'><data:blog.title/></a>. 
  Powered by Blogger.
 </h3>
</footer>

</span>
</body>

</html>
