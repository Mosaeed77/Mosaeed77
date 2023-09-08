<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:css='false' b:defaultwidgetversion='2' b:js='true' b:layoutsVersion='3' b:responsive='true' expr:dir='data:blog.languageDirection' expr:lang='data:blog.locale' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
<head>
  <!-- Google tag (gtag.js) -->
<script async='async' src='https://www.googletagmanager.com/gtag/js?id=G-XCRN87ZRQ4'/>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag(&#39;js&#39;, new Date());

  gtag(&#39;config&#39;, &#39;G-XCRN87ZRQ4&#39;);
</script>
  <meta content='JxHdZKhvbeWoASdVNqKg9Lff0fBHsAgG-0Mq5RyXMUk' name='google-site-verification'/>
  <!--[ Favicon ]-->
    <link expr:href='data:blog.blogspotFaviconUrl' rel='apple-touch-icon' sizes='120x120'/>
    <link expr:href='data:blog.blogspotFaviconUrl' rel='apple-touch-icon' sizes='152x152'/>
    <link expr:href='data:blog.blogspotFaviconUrl' rel='icon' type='image/x-icon'/>
    <link expr:href='data:blog.blogspotFaviconUrl' rel='shortcut icon' type='image/x-icon'/>
  <link href='https://toleen77.blogspot.com/feeds/posts/default' rel='alternate' title='محترف الانترنت' type='application/rss+xml'/>
  
  <!-- Description and Keywords (start) -->
    <b:if cond='data:blog.pageType == &quot;index&quot;'>
    <meta content='سحابة المعلومات - Infoo Cloud موقع عربى مهتم بمجال التكنولوجيا و المعلومات ، نقدم شروحات حصرية فى الويندوز و الاندرويد و البرامج و المواقع و جوجل و بلوجر و الربح من الانترنت، كما توجد ايضا اقسام متنوعة' name='description'/>
    </b:if>
    <meta content=' سحابة المعلومات ، معلوميات ، سحابة المعلوميات ، المعلوميات، infoo cloud ، سحابة المعلومات - infoo cloud معلومات ، جوجل ادسنس ، الربح من الانترنت ، مزايا ، برامج ، مواقع ، تكنولوجيا ' name='keywords'/>
    <!-- Description and Keywords (end) -->
   <!-- Social Media meta tag need customer customization -->
    <meta content='250426312627042' property='fb:app_id'/>
    <meta content='100003523399954' property='fb:admins'/>
    <meta content='infoocloud' name='twitter:site'/>
    <meta content='infoocloud' name='twitter:creator'/> 
  <meta content='https://www.facebook.com/HassanElbargesy12' property='article:author'/>
  <meta content='250426312627042' property='fb:app_id'/>
  
  
   <link href='/apple-touch-icon.png' rel='apple-touch-icon'/>
  
  
  <!-- Default Meta -->
 <meta content='width=device-width, initial-scale=1.0, shrink-to-fit=no' name='viewport'/>
    <!-- DNS Prefetech -->
<b:include name='DNSPrefetech'/>
<!-- Title -->
<title><b:if cond='data:view.isError'><data:blog.title.escaped/></b:if><b:if cond='data:view.isMultipleItems'><b:if cond='data:view.isHomepage'><data:blog.title.escaped/><b:else/><data:blog.pageTitle.escaped/></b:if><b:elseif cond='data:view.isSingleItem'/><data:view.title.escaped/></b:if></title>
<!-- Open Graph -->
<b:include name='OpenGraph'/>
<!-- Twitter Card -->
<b:include name='TwitterCard'/>

<!-- Required -->
<meta content='250426312627042' property='fb:app_id'/>
<meta content='100003523399954' property='fb:admins'/>
<b:if cond='data:view.isSingleItem'>
  <meta content='https://www.facebook.com/infoocloud' property='article:publisher'/> 
  <meta content='https://www.facebook.com/HassanElbargesy12' property='article:author'/>
</b:if>
    <b:if cond='!data:view.isLayoutMode'>
  <!-- Template Skin -->
<b:skin><![CDATA[ 
/* === قالب سيو بلس المدفوع مجانا للجميع مدونة أفكارنا ====
-> Homepage: https://afkarona.net
-> Version : 6.1
-> Updated : 17 September, 2021 
*//*=================
>Variables
===================*/
<Group description="ألاعدادات ألاساسية" selector="body">
<Variable name="BlogFonts" description="خط المدونة" type="length" default="1px" min="1px" max="7px" value="2px"/>

<Variable name="disaplelastposts" description="اخفاء اخر المشاركات" type="length" default="1px" min="1px" max="2px" value="1px"/>

<Variable name="disapledarck" description="اخفاء زر الوضع المظلم" type="length" default="1px" min="1px" max="2px" value="1px"/>

<Variable name="CoverImg" description="تفعيل / الغاء تفعيل قص الصور" type="length" default="2px" min="1px" max="2px" value="2px"/>
<Variable name="StopCopying" description="منع نسخ المحتوي" type="length" default="1px" min="1px" max="2px" value="2px"/>

<Variable name="TitleBorder" description="لون فواصل العناوين" type="color" default="#eee" value="#efefef"/>
<Variable name="TitleBorderRadius" description="منحني حدود العناوين" type="length" default="3px" min="1px" max="30px"  value="27px"/>
<Variable name="contentBorderRadius" description="منحني جسم الصفحة (الابيض)" type="length" default="3px" min="1px" max="30px"  value="27px"/>

<Variable name="content.width" description="Content width" type="length" min="992px" max="1300px" default="1100px" value="1201px"/>
<Variable name="sidebar.width" description="Sidebar width" type="length" min="250px" max="480px" default="320px" value="320px"/>
</Group>

<Group description="واجهة الهاتف" selector="body">
<Variable name="body.background" description="Background" color="#f7f7f7" type="background" default="$(color) none repeat scroll top left"  value="#787878 url(none) repeat scroll top center /* Credit: fpm (http://www.istockphoto.com/portfolio/fpm?platform=blogger) */"/>
<Variable name="MopileFasterVirson" description="تفعيل نمط الهاتف البسيط / السريع" type="length" default="2px" min="1px" max="2px" value="1px"/>
<Variable name="MopileFasterVirsonFot" description="قائمة الهاتف الذكية" type="length" default="2px" min="1px" max="2px" value="2px"/>
<Variable name="body.background.color" description="لون تبويب المدونة في الهاتف" type="color" default="#3560ab"  value="#375eb2"/>
</Group>

<Group description='شريط الاخبار' selector="body">
<Variable name="shreetLength" description="عدد مواضيع شريط الاخبار" type="length" default="10px" min="1px" max="30px" value="30px"/>
<Variable name="Remove3nwanshreetMopile" description="اخفاء نص العنوان في الهاتف" type="length" default="1px" min="1px" max="2px" value="1px"/>
</Group>

<Group description='عدد المواضيع في منطقة التدوينات الاضافية' selector="body">
<Variable name="slideLength" description="عدد مواضيع شكل slide" type="length" default="5px" min="5px" max="9px" value="5px"/>
<Variable name="posts0Length" description="عدد المقالات متشابهة في صفحة الموضوع (أخر المواضيع من قسم) او posts0" type="length" default="6px" min="3px" max="12px" value="6px"/>
<Variable name="posts1Length" description="عدد مواضيع شكل posts1" type="length" default="6px" min="3px" max="12px" value="6px"/>
<Variable name="posts2Length" description="عدد مواضيع شكل posts2" type="length" default="6px" min="3px" max="12px" value="6px"/>
<Variable name="posts3Length" description="عدد مواضيع شكل posts3" type="length" default="4px" min="1px" max="10px" value="4px"/>
<Variable name="posts4Length" description="عدد مواضيع شكل posts4" type="length" default="4px" min="1px" max="10px" value="4px"/>
<Variable name="posts5Length" description="عدد مواضيع شكل posts5" type="length" default="5px" min="5px" max="9px" value="5px"/>
<Variable name="posts6Length" description="عدد مواضيع شكل posts6" type="length" default="4px" min="1px" max="10px" value="4px"/>
<Variable name="lListsLength" description="عدد مواضيع شكل 3collList" type="length" default="12px" min="3px" max="24px" value="12px"/>
<Variable name="postsNormalLength" description="عدد مواضيع شكل postsNormal" type="length" default="5px" min="1px" max="10px" value="5px"/>
</Group>

<Group description="ألالوان الرئيسية" selector="body">
<Variable name="keycolor" description="اللون الرئيسي" type="color" default="#3560ab" value="#3367d6"/>
<Variable name="step.color" description="اللون المساعد" type="color" default="#1e3c72" value="#224081"/>
<Variable name="grad.color" description="لون الرابط (علي اللون الاساسي)" type="color" default="#ffffff" value="#ffffff"/>
<Variable name="startSide" description="start direction" type="automatic" default="right" hideEditor="true" />
<Variable name="endSide" description="end direction" type="automatic" default="left" hideEditor="true" />
</Group>

<Group description='القائمة العلوية' selector="header">
<Variable name="Style2Headr" description="أشكال القائمة العلوية" type="length" default="1px" min="1px" max="3px" value="1px"/>
<Variable name="StykiHeadr" description="تثبيت وأيقاف تثبيت القائمة العلوية" type="length" default="1px" min="1px" max="2px" value="1px"/>
<Variable name="BacgroundIcon" description="خلفية زر البحث وزر قائمة الهاتف" type="color" default="#3560ab"  value="#375eb2"/>
<Variable name="BacgroundIconColor" description="لون ايقونة زر البحث وزر قائمة الهاتف" type="color" default="#ffffff"  value="#ffffff"/>
<Variable name="BacgroundHeader" description="خلفية القائمة العلوية" type="color" default="#ffffff" value="#ffffff"/>
<Variable name="LinkColor" description="لون الروابط" type="color" default="#000000" value="#000000"/>
<Variable name="HoverLinkColor" description="لون تاثير المرور علي الروابط" type="color" default="#3560ab" value="#375eb2"/>
<Variable name="HLinkfont" description="خط وحجم الخط للروابط" type="font" default="400 14px 'Segoe UI'"  value="normal 400 18px &#39;Segoe UI&#39;"/>
</Group>

<Group description='القائمة الجانبية' selector="body">
<Variable name="RemoveAdiseHome" description="اخفاء القائمة الجانبية من الصفحة الرئيسية" type="length" default="1px" min="1px" max="2px" value="1px"/>
<Variable name="RemoveAdisePost" description="اخفاء القائمة الجانبية من صفحة الموضوع" type="length" default="1px" min="1px" max="2px" value="1px"/>
<Variable name="RemoveAdisePage" description="اخفاء القائمة الجانبية من الصفحات الثابتة" type="length" default="1px" min="1px" max="2px" value="1px"/>
<Variable name="RemoveAdiseMopile" description="اخفاء القائمة الجانبية من الهاتف" type="length" default="1px" min="1px" max="2px" value="2px"/>
<Variable name="StykiAdise" description="ايقاف تثبيت القائمة الجانبية" type="length" default="1px" min="1px" max="2px" value="1px"/>
</Group>

<Group description='المواضيع المصغرة' selector="body">
<Variable name="PostTitleColor" description="لون العناوين" type="color" default="#444" value="#4e4e4e"/>
<Variable name="PostMetaColor" description="لون روابط الميتا بوست" type="color" default="#777" value="#7b7b7b"/>
<Variable name="PostDescColor" description="لون وصف الموضوع القصير" type="color" default="#777" value="#7b7b7b"/>
<Variable name="PostHoverColor" description="لون التاثير المرور" type="color" default="#3560ab" value="#375eb2"/>
</Group>


<Group description="ألمشاركات والصفحات" selector=".post-body" >
<Variable name="nextprev" description="إخفاء أزرار المقال السابق والمقال التالي" type="length" default="1px" min="1px" max="2px" value="1px"/>
  <Variable name="retposts" description="إخفاء المقالات المشابهة" type="length" default="1px" min="1px" max="2px" value="1px"/>

<Variable name="imgs7b" description="سحب الصورة فوق العنوان" type="length" default="1px" min="1px" max="2px" value="1px"/>
<Variable name="imgsclick" description="النقر علي الصور" type="length" default="1px" min="1px" max="2px" value="2px"/>
<Variable name="RemoveAuthor" description="اخفاء كاتب الموضوع" type="length" default="1px" min="1px" max="2px" value="2px"/>
<Variable name="PostsTitleColor" description="لون عنوان ألمشاركات والصفحات" type="color" default="#393939"  value="#474747"/>
<Variable name="PostsTitleFont" description="خط عنوان المشاركات والصفحات" type="font" default="400 21px 'Segoe UI'"  value="400 21px &#39;Segoe UI&#39;"/>
<Variable name="PostsMetaColor" description="لون خط الميتا بوست" type="color" default="#585858"  value="#5f5f5f"/>
<Variable name="PostsTextFont" description="حجم وخط المشاركات والصفحات" type="font" default="400 16px 'Segoe UI'"  value="normal 400 18px &#39;Segoe UI&#39;"/>
<Variable name="PostsTextColor" description="لون خط المشاركات والصفحات" type="color" default="#000"  value="#000000"/>
<Variable name="PostsLinkColor" description="لون روابط المشاركات والصفحات" type="color" default="#194ca9"  value="#1a4ab3"/>
</Group>


<Group description="عناوين المشاركات والصفحات" selector=".post-body" >
<Variable name="PostsH1Color" description="لون خط العنوان الرئيسي (H1)" type="color" default="#000"  value="#000000"/>
<Variable name="PostsH1Bacground" description="لون خلفية العنوان الرئيسي (H1)" type="color" default="#eee"  value="#efefef"/>
<Variable name="PostsH1BorderBottm" description="لون الفاصل السفلي العنوان الرئيسي (H1)" type="color" default="#eee"  value="#efefef"/>
<Variable name="PostsH1Font" description="خط العنوان الرئيسي (H1)" type="font" default="400 21px 'Segoe UI'"  value="400 21px &#39;Segoe UI&#39;"/>


<Variable name="PostsH2Color" description="لون خط العنوان (H2)" type="color" default="#000"  value="#000000"/>
<Variable name="PostsH2Bacground" description="لون خلفية العنوان (H2)" type="color" default="#eee"  value="#efefef"/>
<Variable name="PostsH2BorderBottm" description="لون الفاصل السفلي العنوان (H2)" type="color" default="#eee"  value="#efefef"/>
<Variable name="PostsH2Font" description="خط العنوان (H2)" type="font" default="400 19px 'Segoe UI'"  value="400 19px &#39;Segoe UI&#39;"/>


<Variable name="PostsH3Color" description="لون خط العنوان الفرعي (H3)" type="color" default="#000"  value="#000000"/>
<Variable name="PostsH3Bacground" description="لون خلفية العنوان الفرعي (H3)" type="color" default="#eee"  value="#efefef"/>
<Variable name="PostsH3BorderBottm" description="لون الفاصل السفلي العنوان الفرعي (H3)" type="color" default="#eee"  value="#efefef"/>
<Variable name="PostsH3Font" description="خط العنوان الفرعي (H3)" type="font" default="400 17px 'Segoe UI'"  value="normal 400 19px &#39;Segoe UI&#39;"/>


<Variable name="PostsH4Color" description="لون خط العنوان الثانوي (H4)" type="color" default="#000"  value="#000000"/>
<Variable name="PostsH4Bacground" description="لون خلفية العنوان الثانوي (H4)" type="color" default="#eee"  value="#efefef"/>
<Variable name="PostsH4BorderBottm" description="لون الفاصل السفلي العنوان الثانوي (H4)" type="color" default="#eee"  value="#efefef"/>
<Variable name="PostsH4Font" description="خط العنوان الثانوي (H4)" type="font" default="400 16px 'Segoe UI'"  value="normal 400 19px &#39;Segoe UI&#39;"/>
</Group>

<Group description="أقسام المشاركات" selector=".post-body" >
<Variable name="poststagsbg" description="الخلفية" type="color" default="#eee"  value="#efefef"/>
<Variable name="poststagscolor" description="لون النص" type="color" default="#292929"  value="#3e3e3e"/>
<Variable name="poststagshoverbg" description="لون الخلفية عند التمرير" type="color" default="#3560ab"  value="#375eb2"/>
<Variable name="poststagshovercolor" description="لون النص عند التمرير" type="color" default="#fff"  value="#ffffff"/>
</Group>


<Group description='نموذج التعليقات' selector="#comments">
<Variable name="body.text.color" description="لون النص" type="color" default="#777777" value="#7b7b7b"/>
<Variable name="body.link.color" description="لون الروابط" type="color" default="#3560ab" value="#375eb2"/>
<Variable name="posts.title.color" description="لون العنوان" type="color" default="#000" value="#000000"/>
<Variable name="posts.icons.color" description="خلفية ايقونة الاعلام" type="color" default="#3560ab" value="#375eb2"/>
<Variable name="labels.background.color" description="خلفيات الازرار" type="color" default="#f5f5f5" value="#f6f6f6"/>
<Variable name="BordersCommints" description="لون الفواصل" type="color" default="#eee" hideEditor="true" value="#efefef"/>
<Variable name="posts.background.color" description="لون الخلفية" type="color" default="transparent" hideEditor="true" value="rgba(55,55,55,0)"/>
<Variable name="body.text.font" description="text font" type="font" default="600 14px &#39;Segoe UI&#39;" hideEditor="true" value="600 14px &#39;Segoe UI&#39;"/>
<Variable name="tabs.font" description="tabs font" type="font" default="14px &#39;Segoe UI&#39;" hideEditor="true" value="normal normal 18px &#39;Segoe UI&#39;"/>
<Variable name="posts.text.color" description="Post text color" type="color" default="#777" hideEditor="true" value="#7b7b7b"/> 
<Variable name="labels.background.border" description="فواصل الازرار" type="color" default="#eee" hideEditor="true" value="#efefef"/>
</Group> 


/**/
/*=================
Icons Svg
===================*/
.Sp-Normal .moreLink:before, .post-outer .moreLink:before, a.Lapel-Link:before, a.thumb.not-pl:after {background: no-repeat center url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' focusable='false' data-prefix='fal' data-icon='external-link-alt' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 512 512'%3E%3Cpath fill='%23fff' d='M440,256H424a8,8,0,0,0-8,8V464a16,16,0,0,1-16,16H48a16,16,0,0,1-16-16V112A16,16,0,0,1,48,96H248a8,8,0,0,0,8-8V72a8,8,0,0,0-8-8H48A48,48,0,0,0,0,112V464a48,48,0,0,0,48,48H400a48,48,0,0,0,48-48V264A8,8,0,0,0,440,256ZM480,0h-.06L383.78.17c-28.45,0-42.66,34.54-22.58,54.62l35.28,35.28-265,265a12,12,0,0,0,0,17l8.49,8.49a12,12,0,0,0,17,0l265-265,35.28,35.27c20,20,54.57,6,54.62-22.57L512,32.05A32,32,0,0,0,480,0Zm-.17,128.17-96-96L480,32Z'%3E%3C/path%3E%3C/svg%3E")}
.recent-comments .comment .leave-comm:before, .bottomaa:after {background: no-repeat center url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' focusable='false' data-prefix='fal' data-icon='external-link-alt' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 512 512'%3E%3Cpath fill='%236f6f6f' d='M440,256H424a8,8,0,0,0-8,8V464a16,16,0,0,1-16,16H48a16,16,0,0,1-16-16V112A16,16,0,0,1,48,96H248a8,8,0,0,0,8-8V72a8,8,0,0,0-8-8H48A48,48,0,0,0,0,112V464a48,48,0,0,0,48,48H400a48,48,0,0,0,48-48V264A8,8,0,0,0,440,256ZM480,0h-.06L383.78.17c-28.45,0-42.66,34.54-22.58,54.62l35.28,35.28-265,265a12,12,0,0,0,0,17l8.49,8.49a12,12,0,0,0,17,0l265-265,35.28,35.27c20,20,54.57,6,54.62-22.57L512,32.05A32,32,0,0,0,480,0Zm-.17,128.17-96-96L480,32Z'%3E%3C/path%3E%3C/svg%3E");}
.icon.fa-reddit,.fa.fa-reddit {background: no-repeat center url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' focusable='false' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 512 512'%3E%3Cpath fill='%23fff' d='M440.3 203.5c-15 0-28.2 6.2-37.9 15.9-35.7-24.7-83.8-40.6-137.1-42.3L293 52.3l88.2 19.8c0 21.6 17.6 39.2 39.2 39.2 22 0 39.7-18.1 39.7-39.7s-17.6-39.7-39.7-39.7c-15.4 0-28.7 9.3-35.3 22l-97.4-21.6c-4.9-1.3-9.7 2.2-11 7.1L246.3 177c-52.9 2.2-100.5 18.1-136.3 42.8-9.7-10.1-23.4-16.3-38.4-16.3-55.6 0-73.8 74.6-22.9 100.1-1.8 7.9-2.6 16.3-2.6 24.7 0 83.8 94.4 151.7 210.3 151.7 116.4 0 210.8-67.9 210.8-151.7 0-8.4-.9-17.2-3.1-25.1 49.9-25.6 31.5-99.7-23.8-99.7zM129.4 308.9c0-22 17.6-39.7 39.7-39.7 21.6 0 39.2 17.6 39.2 39.7 0 21.6-17.6 39.2-39.2 39.2-22 .1-39.7-17.6-39.7-39.2zm214.3 93.5c-36.4 36.4-139.1 36.4-175.5 0-4-3.5-4-9.7 0-13.7 3.5-3.5 9.7-3.5 13.2 0 27.8 28.5 120 29 149 0 3.5-3.5 9.7-3.5 13.2 0 4.1 4 4.1 10.2.1 13.7zm-.8-54.2c-21.6 0-39.2-17.6-39.2-39.2 0-22 17.6-39.7 39.2-39.7 22 0 39.7 17.6 39.7 39.7-.1 21.5-17.7 39.2-39.7 39.2z'%3E%3C/path%3E%3C/svg%3E");}
.fa-facebook, .facebook .topaa:before{background:no-repeat center url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' data-prefix='fab' data-icon='facebook-f' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 264 512' class='svg-inline--fa fa-facebook-f fa-w-9'%3E%3Cpath fill='%23fff' d='M76.7 512V283H0v-91h76.7v-71.7C76.7 42.4 124.3 0 193.8 0c33.3 0 61.9 2.5 70.2 3.6V85h-48.2c-37.8 0-45.1 18-45.1 44.3V192H256l-11.7 91h-73.6v229' class=''%3E%3C/path%3E%3C/svg%3E")}
.fa-twitter, .twitter .topaa:before{background:no-repeat center url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' data-prefix='fab' data-icon='twitter' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 512 512' class='svg-inline--fa fa-twitter fa-w-16'%3E%3Cpath fill='%23fff' d='M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z' class=''%3E%3C/path%3E%3C/svg%3E")}
.fa-tumblr {background: no-repeat center url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 320 512' %3E%3Cpath fill='%23fff' d='M309.8 480.3c-13.6 14.5-50 31.7-97.4 31.7-120.8 0-147-88.8-147-140.6v-144H17.9c-5.5 0-10-4.5-10-10v-68c0-7.2 4.5-13.6 11.3-16 62-21.8 81.5-76 84.3-117.1.8-11 6.5-16.3 16.1-16.3h70.9c5.5 0 10 4.5 10 10v115.2h83c5.5 0 10 4.4 10 9.9v81.7c0 5.5-4.5 10-10 10h-83.4V360c0 34.2 23.7 53.6 68 35.8 4.8-1.9 9-3.2 12.7-2.2 3.5.9 5.8 3.4 7.4 7.9l22 64.3c1.8 5 3.3 10.6-.4 14.5z' class=''%3E%3C/path%3E%3C/svg%3E");}
.fa-whatsapp {background: no-repeat center url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 448 512' %3E%3Cpath fill='%23fff' d='M380.9 97.1C339 55.1 283.2 32 223.9 32c-122.4 0-222 99.6-222 222 0 39.1 10.2 77.3 29.6 111L0 480l117.7-30.9c32.4 17.7 68.9 27 106.1 27h.1c122.3 0 224.1-99.6 224.1-222 0-59.3-25.2-115-67.1-157zm-157 341.6c-33.2 0-65.7-8.9-94-25.7l-6.7-4-69.8 18.3L72 359.2l-4.4-7c-18.5-29.4-28.2-63.3-28.2-98.2 0-101.7 82.8-184.5 184.6-184.5 49.3 0 95.6 19.2 130.4 54.1 34.8 34.9 56.2 81.2 56.1 130.5 0 101.8-84.9 184.6-186.6 184.6zm101.2-138.2c-5.5-2.8-32.8-16.2-37.9-18-5.1-1.9-8.8-2.8-12.5 2.8-3.7 5.6-14.3 18-17.6 21.8-3.2 3.7-6.5 4.2-12 1.4-32.6-16.3-54-29.1-75.5-66-5.7-9.8 5.7-9.1 16.3-30.3 1.8-3.7.9-6.9-.5-9.7-1.4-2.8-12.5-30.1-17.1-41.2-4.5-10.8-9.1-9.3-12.5-9.5-3.2-.2-6.9-.2-10.6-.2-3.7 0-9.7 1.4-14.8 6.9-5.1 5.6-19.4 19-19.4 46.3 0 27.3 19.9 53.7 22.6 57.4 2.8 3.7 39.1 59.7 94.8 83.8 35.2 15.2 49 16.5 66.6 13.9 10.7-1.6 32.8-13.4 37.4-26.4 4.6-13 4.6-24.1 3.2-26.4-1.3-2.5-5-3.9-10.5-6.6z' class=''%3E%3C/path%3E%3C/svg%3E");}
.fa-youtube {background: no-repeat center url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 576 512' %3E%3Cpath fill='%23fff' d='M549.655 124.083c-6.281-23.65-24.787-42.276-48.284-48.597C458.781 64 288 64 288 64S117.22 64 74.629 75.486c-23.497 6.322-42.003 24.947-48.284 48.597-11.412 42.867-11.412 132.305-11.412 132.305s0 89.438 11.412 132.305c6.281 23.65 24.787 41.5 48.284 47.821C117.22 448 288 448 288 448s170.78 0 213.371-11.486c23.497-6.321 42.003-24.171 48.284-47.821 11.412-42.867 11.412-132.305 11.412-132.305s0-89.438-11.412-132.305zm-317.51 213.508V175.185l142.739 81.205-142.739 81.201z' class=''%3E%3C/path%3E%3C/svg%3E");}
.fa-behance {background: no-repeat center url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 576 512' %3E%3Cpath fill='%23fff' d='M232 237.2c31.8-15.2 48.4-38.2 48.4-74 0-70.6-52.6-87.8-113.3-87.8H0v354.4h171.8c64.4 0 124.9-30.9 124.9-102.9 0-44.5-21.1-77.4-64.7-89.7zM77.9 135.9H151c28.1 0 53.4 7.9 53.4 40.5 0 30.1-19.7 42.2-47.5 42.2h-79v-82.7zm83.3 233.7H77.9V272h84.9c34.3 0 56 14.3 56 50.6 0 35.8-25.9 47-57.6 47zm358.5-240.7H376V94h143.7v34.9zM576 305.2c0-75.9-44.4-139.2-124.9-139.2-78.2 0-131.3 58.8-131.3 135.8 0 79.9 50.3 134.7 131.3 134.7 61.3 0 101-27.6 120.1-86.3H509c-6.7 21.9-34.3 33.5-55.7 33.5-41.3 0-63-24.2-63-65.3h185.1c.3-4.2.6-8.7.6-13.2zM390.4 274c2.3-33.7 24.7-54.8 58.5-54.8 35.4 0 53.2 20.8 56.2 54.8H390.4z' class=''%3E%3C/path%3E%3C/svg%3E");}
.fa-flickr {background: no-repeat center url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 448 512' %3E%3Cpath fill='%23fff' d='M400 32H48C21.5 32 0 53.5 0 80v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V80c0-26.5-21.5-48-48-48zM144.5 319c-35.1 0-63.5-28.4-63.5-63.5s28.4-63.5 63.5-63.5 63.5 28.4 63.5 63.5-28.4 63.5-63.5 63.5zm159 0c-35.1 0-63.5-28.4-63.5-63.5s28.4-63.5 63.5-63.5 63.5 28.4 63.5 63.5-28.4 63.5-63.5 63.5z' class=''%3E%3C/path%3E%3C/svg%3E");}
.fa-blogger {background: no-repeat center url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 448 512' %3E%3Cpath fill='%23fff' d='M446.6 222.7c-1.8-8-6.8-15.4-12.5-18.5-1.8-1-13-2.2-25-2.7-20.1-.9-22.3-1.3-28.7-5-10.1-5.9-12.8-12.3-12.9-29.5-.1-33-13.8-63.7-40.9-91.3-19.3-19.7-40.9-33-65.5-40.5-5.9-1.8-19.1-2.4-63.3-2.9-69.4-.8-84.8.6-108.4 10C45.9 59.5 14.7 96.1 3.3 142.9 1.2 151.7.7 165.8.2 246.8c-.6 101.5.1 116.4 6.4 136.5 15.6 49.6 59.9 86.3 104.4 94.3 14.8 2.7 197.3 3.3 216 .8 32.5-4.4 58-17.5 81.9-41.9 17.3-17.7 28.1-36.8 35.2-62.1 4.9-17.6 4.5-142.8 2.5-151.7zm-322.1-63.6c7.8-7.9 10-8.2 58.8-8.2 43.9 0 45.4.1 51.8 3.4 9.3 4.7 13.4 11.3 13.4 21.9 0 9.5-3.8 16.2-12.3 21.6-4.6 2.9-7.3 3.1-50.3 3.3-26.5.2-47.7-.4-50.8-1.2-16.6-4.7-22.8-28.5-10.6-40.8zm191.8 199.8l-14.9 2.4-77.5.9c-68.1.8-87.3-.4-90.9-2-7.1-3.1-13.8-11.7-14.9-19.4-1.1-7.3 2.6-17.3 8.2-22.4 7.1-6.4 10.2-6.6 97.3-6.7 89.6-.1 89.1-.1 97.6 7.8 12.1 11.3 9.5 31.2-4.9 39.4z' class=''%3E%3C/path%3E%3C/svg%3E");}
.fa-wordpress {background: no-repeat center url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 512 512' %3E%3Cpath fill='%23fff' d='M256 8C119.3 8 8 119.2 8 256c0 136.7 111.3 248 248 248s248-111.3 248-248C504 119.2 392.7 8 256 8zM33 256c0-32.3 6.9-63 19.3-90.7l106.4 291.4C84.3 420.5 33 344.2 33 256zm223 223c-21.9 0-43-3.2-63-9.1l66.9-194.4 68.5 187.8c.5 1.1 1 2.1 1.6 3.1-23.1 8.1-48 12.6-74 12.6zm30.7-327.5c13.4-.7 25.5-2.1 25.5-2.1 12-1.4 10.6-19.1-1.4-18.4 0 0-36.1 2.8-59.4 2.8-21.9 0-58.7-2.8-58.7-2.8-12-.7-13.4 17.7-1.4 18.4 0 0 11.4 1.4 23.4 2.1l34.7 95.2L200.6 393l-81.2-241.5c13.4-.7 25.5-2.1 25.5-2.1 12-1.4 10.6-19.1-1.4-18.4 0 0-36.1 2.8-59.4 2.8-4.2 0-9.1-.1-14.4-.3C109.6 73 178.1 33 256 33c58 0 110.9 22.2 150.6 58.5-1-.1-1.9-.2-2.9-.2-21.9 0-37.4 19.1-37.4 39.6 0 18.4 10.6 33.9 21.9 52.3 8.5 14.8 18.4 33.9 18.4 61.5 0 19.1-7.3 41.2-17 72.1l-22.2 74.3-80.7-239.6zm81.4 297.2l68.1-196.9c12.7-31.8 17-57.2 17-79.9 0-8.2-.5-15.8-1.5-22.9 17.4 31.8 27.3 68.2 27.3 107 0 82.3-44.6 154.1-110.9 192.7z' class=''%3E%3C/path%3E%3C/svg%3E");}
.fa-tumblr {background: no-repeat center url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 320 512' %3E%3Cpath fill='%23fff' d='M309.8 480.3c-13.6 14.5-50 31.7-97.4 31.7-120.8 0-147-88.8-147-140.6v-144H17.9c-5.5 0-10-4.5-10-10v-68c0-7.2 4.5-13.6 11.3-16 62-21.8 81.5-76 84.3-117.1.8-11 6.5-16.3 16.1-16.3h70.9c5.5 0 10 4.5 10 10v115.2h83c5.5 0 10 4.4 10 9.9v81.7c0 5.5-4.5 10-10 10h-83.4V360c0 34.2 23.7 53.6 68 35.8 4.8-1.9 9-3.2 12.7-2.2 3.5.9 5.8 3.4 7.4 7.9l22 64.3c1.8 5 3.3 10.6-.4 14.5z' class=''%3E%3C/path%3E%3C/svg%3E");}
.fa-telegram {background: no-repeat center url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 448 512' %3E%3Cpath fill='%23fff' d='M446.7 98.6l-67.6 318.8c-5.1 22.5-18.4 28.1-37.3 17.5l-103-75.9-49.7 47.8c-5.5 5.5-10.1 10.1-20.7 10.1l7.4-104.9 190.9-172.5c8.3-7.4-1.8-11.5-12.9-4.1L117.8 284 16.2 252.2c-22.1-6.9-22.5-22.1 4.6-32.7L418.2 66.4c18.4-6.9 34.5 4.1 28.5 32.2z' class=''%3E%3C/path%3E%3C/svg%3E");}
.fa-skype {background: no-repeat center url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 448 512' %3E%3Cpath fill='%23fff' d='M424.7 299.8c2.9-14 4.7-28.9 4.7-43.8 0-113.5-91.9-205.3-205.3-205.3-14.9 0-29.7 1.7-43.8 4.7C161.3 40.7 137.7 32 112 32 50.2 32 0 82.2 0 144c0 25.7 8.7 49.3 23.3 68.2-2.9 14-4.7 28.9-4.7 43.8 0 113.5 91.9 205.3 205.3 205.3 14.9 0 29.7-1.7 43.8-4.7 19 14.6 42.6 23.3 68.2 23.3 61.8 0 112-50.2 112-112 .1-25.6-8.6-49.2-23.2-68.1zm-194.6 91.5c-65.6 0-120.5-29.2-120.5-65 0-16 9-30.6 29.5-30.6 31.2 0 34.1 44.9 88.1 44.9 25.7 0 42.3-11.4 42.3-26.3 0-18.7-16-21.6-42-28-62.5-15.4-117.8-22-117.8-87.2 0-59.2 58.6-81.1 109.1-81.1 55.1 0 110.8 21.9 110.8 55.4 0 16.9-11.4 31.8-30.3 31.8-28.3 0-29.2-33.5-75-33.5-25.7 0-42 7-42 22.5 0 19.8 20.8 21.8 69.1 33 41.4 9.3 90.7 26.8 90.7 77.6 0 59.1-57.1 86.5-112 86.5z' class=''%3E%3C/path%3E%3C/svg%3E");}
.fa-sitemap {background: no-repeat center url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 640 512' %3E%3Cpath fill='%23fff' d='M104 272h192v48h48v-48h192v48h48v-57.59c0-21.17-17.22-38.41-38.41-38.41H344v-64h40c17.67 0 32-14.33 32-32V32c0-17.67-14.33-32-32-32H256c-17.67 0-32 14.33-32 32v96c0 8.84 3.58 16.84 9.37 22.63S247.16 160 256 160h40v64H94.41C73.22 224 56 241.23 56 262.41V320h48v-48zm168-160V48h96v64h-96zm336 240h-96c-17.67 0-32 14.33-32 32v96c0 17.67 14.33 32 32 32h96c17.67 0 32-14.33 32-32v-96c0-17.67-14.33-32-32-32zm-16 112h-64v-64h64v64zM368 352h-96c-17.67 0-32 14.33-32 32v96c0 17.67 14.33 32 32 32h96c17.67 0 32-14.33 32-32v-96c0-17.67-14.33-32-32-32zm-16 112h-64v-64h64v64zM128 352H32c-17.67 0-32 14.33-32 32v96c0 17.67 14.33 32 32 32h96c17.67 0 32-14.33 32-32v-96c0-17.67-14.33-32-32-32zm-16 112H48v-64h64v64z' class=''%3E%3C/path%3E%3C/svg%3E");}
.fa-instagram {background: no-repeat center url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 448 512' %3E%3Cpath fill='%23fff' d='M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z' class=''%3E%3C/path%3E%3C/svg%3E");}
.fa-linkedin {background: no-repeat center url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 448 512' %3E%3Cpath fill='%23fff' d='M100.3 480H7.4V180.9h92.9V480zM53.8 140.1C24.1 140.1 0 115.5 0 85.8 0 56.1 24.1 32 53.8 32c29.7 0 53.8 24.1 53.8 53.8 0 29.7-24.1 54.3-53.8 54.3zM448 480h-92.7V334.4c0-34.7-.7-79.2-48.3-79.2-48.3 0-55.7 37.7-55.7 76.7V480h-92.8V180.9h89.1v40.8h1.3c12.4-23.5 42.7-48.3 87.9-48.3 94 0 111.3 61.9 111.3 142.3V480z' class=''%3E%3C/path%3E%3C/svg%3E");}
.fa-pinterest {background: url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 384 512' %3E%3Cpath fill='%23fff' d='M204 6.5C101.4 6.5 0 74.9 0 185.6 0 256 39.6 296 63.6 296c9.9 0 15.6-27.6 15.6-35.4 0-9.3-23.7-29.1-23.7-67.8 0-80.4 61.2-137.4 140.4-137.4 68.1 0 118.5 38.7 118.5 109.8 0 53.1-21.3 152.7-90.3 152.7-24.9 0-46.2-18-46.2-43.8 0-37.8 26.4-74.4 26.4-113.4 0-66.2-93.9-54.2-93.9 25.8 0 16.8 2.1 35.4 9.6 50.7-13.8 59.4-42 147.9-42 209.1 0 18.9 2.7 37.5 4.5 56.4 3.4 3.8 1.7 3.4 6.9 1.5 50.4-69 48.6-82.5 71.4-172.8 12.3 23.4 44.1 36 69.3 36 106.2 0 153.9-103.5 153.9-196.8C384 71.3 298.2 6.5 204 6.5z' class=''%3E%3C/path%3E%3C/svg %3E") no-repeat center ;}
.fa-google-play {background: no-repeat center url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 512 512' %3E%3Cpath fill='%23fff' d='M325.3 234.3L104.6 13l280.8 161.2-60.1 60.1zM47 0C34 6.8 25.3 19.2 25.3 35.3v441.3c0 16.1 8.7 28.5 21.7 35.3l256.6-256L47 0zm425.2 225.6l-58.9-34.1-65.7 64.5 65.7 64.5 60.1-34.1c18-14.3 18-46.5-1.2-60.8zM104.6 499l280.8-161.2-60.1-60.1L104.6 499z' class=''%3E%3C/path%3E%3C/svg%3E");}

/*=================
>Normalize
===================*/
ul{margin:0;padding:0}
*{text-decoration:none;margin:0;padding:0;outline:0;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}
*,:before,:after{-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}
.clear{clear:both}
html,body,div,span,applet,object,iframe,h1,h2,h3,h4,h5,h6,p,blockquote,pre,abbr,acronym,address,big,cite,code,del,dfn,em,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,dl,dt,dd,ol,ul,li,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td{border:0;font-family:inherit;font-size:100%;font-style:inherit;color:inherit;font-weight:inherit;margin:0;outline:0;padding:0;vertical-align:baseline}
img{max-width:100%;position:relative}
*:not(.notran),:not(.notran):after,:not(.notran):before{-webkit-transition: .3s ease-in-out;-o-transition: .3s ease-in-out;-moz-transition: .3s ease-in-out;transition: .3s ease-in-out;}
body, input {font: 400 15px 'Segoe UI';}
body{background:$(body.background);}
.widget {overflow: hidden;}
aside#sidepar-wid .Sp-posts4  .Date,
.Sp-posts2 .Short_content,
.Sp-posts5 .Short_content,
.Sp-posts2 .items	,
.Sp-posts4 .posts .Short_content,
.Sp-posts1 .items	,
.Sp-posts0 .Short_content,
.Sp-posts0 a.moreLink,
.Sp-posts1 .items .category ,
.Sp-posts3 .Short_content,
.Sp-posts0 .items,
.Sp-3colList .Short_content,
.Sp-posts6 .posts .Short_content,
aside#sidepar-wid .Sp-posts3 .cont .items,
aside#sidepar-wid  .Sp-posts4 .posts:not(.postnum0) .cont .items,
.Sp-posts3 .items span,
.Sp-3colList .items span,
.Sp-posts4 .posts.postnum0 .items span.category,
.Sp-posts6 .posts .items span.category,
.Sp-posts4 .posts:not(.postnum0) .items span,
.Sp-posts5 .posts:not(.postnum0) .items span,
.Sp-slide .posts .Short_content,
.Sp-slide .posts:not(.postnum0) .items ,
.Sp-slide .category:not(.postnum0),
.Sp-posts4 .posts.postnum0 a.thumb.not-pl:before,
.Sp-posts6 .posts a.thumb.not-pl:before,
a.moreLink ,
.Sp-posts4 .posts:first-of-type a.thumb.not-pl:before,
.Sp-posts6 .posts a.thumb.not-pl:before,
.Sp-slide .posts:first-of-type a.thumb.not-pl:before,
.Sp-slide .posts.postnum0 a.thumb.not-pl:before
{display:none !important}

.Sp-posts0 .rnav-title a:hover		,
.Sp-posts1 .rnav-title a:hover		,
.Sp-posts3 .rnav-title a:hover		,
.Sp-posts4 .rnav-title a:hover		,
.Sp-posts6 .rnav-title a:hover		,
.Sp-posts5 .rnav-title a:hover		,
.Sp-Normal .rnav-title a:hover		,
.posle a:hover						,
.Sp-slide .rnav-title a:hover		,
.Sp-3colList .rnav-title a:hover	,
.PopularPosts h3.post-title a:hover ,
.widget.FeaturedPost .post-title a:hover,
.items a:hover              		,
.posttitle:hover,
ul.clear li a:hover,
.post-outer .posts-titles a:hover {color: $(PostHoverColor) !important;}
.site .widget{box-shadow: 0 6px 18px 0 rgba(9,32,76,.035);display:block;background:#fff;clear:both;border-radius:$(contentBorderRadius);padding:20px;overflow:hidden;margin:0 0 15px}
.icon{width:13px;margin-$endSide:3px;display:inline-block;vertical-align:middle}
.icon,.fa{font:normal normal normal 14px/1 FontAwesome!important}
a.PLHolder.thumb:before{content:"";opacity:1;display:inline-block;position:absolute;$startSide:0;$endSide:0;top:0;bottom:0;background-color:$(keycolor);background-repeat:no-repeat;background-size:1000px 900px;animation:bs-lazy-anim 1.01s infinite linear forwards;background-image:linear-gradient(to $startSide,$(keycolor) 0,$(keycolor) 20%,$(step.color) 40%,$(keycolor) 100%);animation-direction:reverse}
a.PLHolder.thumb:after{background-size:300% 300%;animation:mg-gr-anim 5.5s ease-in infinite;opacity:.8;transition:all .35s ease;content:'';position:absolute;background:-webkit-linear-gradient(to $startSide,$(step.color),$(keycolor));background:-moz-linear-gradient(to $startSide,$(step.color),$(keycolor));background:-o-linear-gradient(to $startSide,$(step.color),$(keycolor));background:linear-gradient(to $startSide,$(step.color),$(keycolor));top:0;$endSide:0;$startSide:0;bottom:0}
@keyframes bs-lazy-anim{from{background-position:-800px 0}to{background-position:400px 0}}
.headline{display:block;clear:both;margin-bottom:15px;position:relative;height: 35px;}
.headline:before{content:"";background:$(TitleBorder);height:1px;width:100%;display:block;position:absolute;top:50%;z-index:1}
.headline .title,.Followers h2.title{display:inline-block;padding:0 20px;background:$(keycolor);color:$(grad.color);font-size:13px;height:30px;line-height:30px;font-weight:normal;border-radius:$(TitleBorderRadius);z-index:8;position:relative}
.Followers h2.title{margin-bottom:15px}
.title:before{content:"";position:absolute;$endSide:-5px;background:#fff;height:8px;width:5px;top:40%}
a.Lapel-Link{background:$(keycolor);color:$(grad.color);float:$endSide;padding:0 20px;font-size:13px;height:30px;line-height:30px;border-radius:$(TitleBorderRadius);z-index:8;position:relative}
.Sp-Normal .moreLink:before,.post-outer .moreLink:before,a.Lapel-Link:before{width:16px;height:16px;content:"";position:absolute;$endSide:7px;top:8px;color:#000;padding:5px;display:block;opacity:0;transition:0.2s ease-out}
.Sp-Normal .moreLink:before,.post-outer .moreLink:before,a.Lapel-Link:before,a.thumb.not-pl:after{background:no-repeat center url(data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' focusable='false' data-prefix='fal' data-icon='external-link-alt' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 512 512'%3E%3Cpath fill='%23fff' d='M440,256H424a8,8,0,0,0-8,8V464a16,16,0,0,1-16,16H48a16,16,0,0,1-16-16V112A16,16,0,0,1,48,96H248a8,8,0,0,0,8-8V72a8,8,0,0,0-8-8H48A48,48,0,0,0,0,112V464a48,48,0,0,0,48,48H400a48,48,0,0,0,48-48V264A8,8,0,0,0,440,256ZM480,0h-.06L383.78.17c-28.45,0-42.66,34.54-22.58,54.62l35.28,35.28-265,265a12,12,0,0,0,0,17l8.49,8.49a12,12,0,0,0,17,0l265-265,35.28,35.27c20,20,54.57,6,54.62-22.57L512,32.05A32,32,0,0,0,480,0Zm-.17,128.17-96-96L480,32Z'%3E%3C/path%3E%3C/svg%3E)}
a.Lapel-Link:after {
    content: "";
    position: absolute;
    $startSide: -5px;
    background: #fff;
    height: 8px;
    width: 5px;
    top: 40%;
}
.Wigetdisabled{display:block;overflow:hidden;font-size:13px;padding:10px;text-align:center;color:#721c24;background-color:#f8d7da;border-color:#f5c6cb;border:1px solid;border-radius:2px}
.bocker{overflow:hidden;display:block;clear:both;position:relative}

.by-zn{display:inline-block;overflow:hidden;vertical-align:middle;font-size:14px;font-weight:bold}
.by-zn{float:left;text-align:right;color: #fff  !important; box-shadow: 0 2px 4px 0px rgba(0, 0, 0, 0.4) !important;margin: 0 6px !important;font-size: 13px !important;background:#fc1264 !important;display: inline-block !important; padding: 0 6px !important; border-radius: 3px !important; font-weight: 600!important;}

/* social bottom footer */
.shmal .social-static.social li {display: inline-block;vertical-align: middle;margin-$startSide: 2px;}
footer .social-static.social a[title='twitter'], aside .social-static.social a[title='twitter'], .mop-icon .social-static.social a[title='twitter'] {background: #1da1f2;}
footer .social-static.social a[title='reddit'], aside .social-static.social a[title='reddit'], .mop-icon .social-static.social a[title='reddit'] {background: #ff6933;}
footer .social-static.social a[title='whatsapp'], aside .social-static.social a[title='whatsapp'], .mop-icon .social-static.social a[title='whatsapp'] {background: #128C7E;}
footer .social-static.social a[title='facebook'], aside .social-static.social a[title='facebook'], .mop-icon .social-static.social a[title='facebook'] {background: #4267b2;}
footer .social-static.social a[title='sitemap'], aside .social-static.social a[title='sitemap'], .mop-icon .social-static.social a[title='sitemap'] {background: $(keycolor);}
footer .social-static.social a[title='pinterest'], aside .social-static.social a[title='pinterest'], .mop-icon .social-static.social a[title='pinterest'] {background-color:#cc2127}
footer .social-static.social a[title='linkedin'], aside .social-static.social a[title='linkedin'], .mop-icon .social-static.social a[title='linkedin'] {background-color:#0976b4}
footer .social-static.social a[title='youtube'], aside .social-static.social a[title='youtube'], .mop-icon .social-static.social a[title='youtube'] {background-color:#e52d27}
footer .social-static.social a[title='spotify'], aside .social-static.social a[title='spotify'], .mop-icon .social-static.social a[title='spotify'] {background-color:#1ed760}
footer .social-static.social a[title='snapchat'], aside .social-static.social a[title='snapchat'], .mop-icon .social-static.social a[title='snapchat'] {background-color:#f5d602}
footer .social-static.social a[title='flickr'], aside .social-static.social a[title='flickr'], .mop-icon .social-static.social a[title='flickr'] {background-color:#FF0084}
footer .social-static.social a[title='wordpress'], aside .social-static.social a[title='wordpress'], .mop-icon .social-static.social a[title='wordpress'] {background-color:#207297}
footer .social-static.social a[title='blogger'], aside .social-static.social a[title='blogger'], .mop-icon .social-static.social a[title='blogger'] {background-color:#e96734}
footer .social-static.social a[title='instagram'], aside .social-static.social a[title='instagram'], .mop-icon .social-static.social a[title='instagram'] {background-color:#7c38af;background:radial-gradient(circle at 0 130%, #fdf497 0%, #fdf497 5%, #fd5949 45%,#d6249f 60%,#285AEB 90%)}
footer .social-static.social a[title='behance'], aside .social-static.social a[title='behance'], .mop-icon .social-static.social a[title='behance'] {background-color:#009fff}
footer .social-static.social a[title='soundcloud'], aside .social-static.social a[title='soundcloud'], .mop-icon .social-static.social a[title='soundcloud'] {background-color:#FF5419}
footer .social-static.social a[title='messenger'], aside .social-static.social a[title='messenger'], .mop-icon .social-static.social a[title='messenger'] {background-color:#0084ff}
footer .social-static.social a[title='google-play'], aside .social-static.social a[title='google-play'], .mop-icon .social-static.social a[title='google-play'] {background-color:#3d9dab}
footer .social-static.social a[title='telegram'], aside .social-static.social a[title='telegram'], .mop-icon .social-static.social a[title='telegram'] {background-color:#32AEE1}
footer .social-static.social a[title='tumblr'], aside .social-static.social a[title='tumblr'], .mop-icon .social-static.social a[title='tumblr'] {background-color:#3e5a70}
.social-static.social i.fa {opacity: 0.9;display: block;width: 15px;height: 15px;}
aside .social-static.social li{float:$startSide;vertical-align:middle;list-style:none;width:calc((100% - 4px) / 4);margin-$endSide:1px;margin-bottom:1px}
.social-static.social i.fa:hover{opacity:1}
div#footer-social i.fa{opacity:1}
aside .social-static.social li a{border-radius:0;text-align:center;height:50px;display:flex;align-items:center}
aside .social-static.social i.fa, .mop-icon .social-static.social i.fa{opacity:1;width:22px;height:22px;margin:0 auto}
.social-static.social {display: block;overflow: hidden;vertical-align: middle;}
.shmal .social-static.social li a {display: block;padding: 6px;border-radius: 3px;}
.shmal .social-static.social li:first-of-type {margin-$startSide: 0;}

/* Style Headr */
.titlewrapper .title{position: relative;white-space:nowrap;text-overflow:ellipsis;overflow:hidden;width:250px}
.Style3 .titlewrapper .title{width:200px}
.Style3 .titlewrapper a {
    color: #fff !important;
font-size: 100%;
}
.descriptionwrapper{display:none}
header#sp-header{display:block;position:relative;margin-bottom:15px;height:97px}
.head-pz{height:97px;width:100%;position:fixed;background:$(BacgroundHeader);box-shadow:0 6px 18px 0 rgba(9,32,76,.035);top:0;$startSide:0;$endSide:0;z-index:9}
.par-tp{display:block;width:100%;clear:both;height:35px;position:fixed;top:0;$startSide:0;$endSide:0;max-width:1100px;margin:0 auto}
.floar{color:$(grad.color);width:77%;float:$endSide;display:block;clear:both;position:relative;font-size:13px;padding:0 15px 0 0}
.floar:before{background:$(keycolor);color:$(grad.color);width:2000px;display:block;clear:both;position:absolute;border-bottom-$endSide-radius:5px;transform:skewX(-30deg);$startSide:0;content:"";transform:skewX(-30deg);border-bottom-$startSide-radius:5px;height:35px}
body.ltr .floar:before {transform: skewX(30deg);}
body.ltr .floar {padding: 0 0 0 15px;}
.container,.floar .lap{width:100%;max-width:$(content.width);margin:0 auto}
div#pages{float:$startSide;margin:8.5px 0;font-size:12px;position:relative}
header#sp-header .widget{overflow:initial}
div#pages li{display:inline-block;padding:0 5px}
.floar a{color:$(grad.color);font-size:12px}
div#top-social-L{margin-$endSide:0;float:$endSide;z-index:9;position:relative;margin-top:4px}
.social-static.social{display:block;overflow:hidden;vertical-align:middle}
#top-social-L li:first-of-type{margin-$startSide:0}
#top-social-L li{display:inline-block;vertical-align:middle;margin-$startSide:2px}
#top-social-L li a{display:block;padding:6px;border-radius:3px}
.par-bottm{display:block;clear:both;position:fixed;top:35px;$startSide:0;$endSide:0;width:100%;position:relative}
.logo{float:$startSide;display:block;position:relative}
div#logo{font-size:1.5em;position:relative;top:-25px;z-index:9;width:250px;height:70px}
div#header-inner{width:250px;height:70px;display:table-cell;vertical-align:middle}
img#Header1_headerimg{max-height:70px;margin:0 auto}
.open.nav1,.search{display:flex;position:relative;float:$endSide;margin:1px 0;background:$(BacgroundIcon);width:30px;height:31px;text-align:center;align-items:center;border-radius:3px;top:14px;margin-$startSide:5px}
.open.nav1{display:none}
.search svg{position:relative;top:2px}
a.op-one svg,.search svg{color:$(BacgroundIconColor);margin:0 9px;width:13px!important;height:13px}
nav.nav-par{float:$endSide;width:calc((100% - 320px) /1)!important;position:relative;top:0}
div#menu{height:62px;display:flex;align-items:center}
nav.nav-par ul li{margin-$endSide:15px;margin-$startSide:0;float:$startSide;list-style:none;position:relative}
nav.nav-par ul li a{font:$(HLinkfont);color:$(LinkColor);position:relative;display:block;padding:10px 0}
li.item:hover > ul{opacity:1;visibility:visible;transform:scale(1)}
li.item > ul,li.sitem > ul{display:block;position:absolute;$startSide:-30px;width:180px;background:$(BacgroundHeader);top:43px;border-radius:3px;box-shadow:0 1px 3px rgba(32,33,36,0.1);border:1px solid #eee;z-index:9;opacity:0;visibility:hidden;transition:.2s ease;transform:scale(0)}
li.item > ul:before{content:"";width:16px;height:16px;position:absolute;background:$(BacgroundHeader);top:-8px;$startSide:20%;z-index:-1;transform:rotate(45deg);border:1px solid #eee}
li.item > ul li.sitem{display:block!important;margin:0!important;float:none}
li.item > ul li.sitem a{color:$(LinkColor);font-size:12px;padding:8px 25px 8px 10px;margin:0!important;border-bottom:1px solid #eee;background:$(BacgroundHeader);display:block;position:relative}
li.item > ul li.sitem a:before{content:"";width:8px;height:8px;position:absolute;background:$(BacgroundHeader);top:13px;$startSide:10px;z-index:999;transform:rotate(45deg);border:1px solid #eee}
body.ltr li.item > ul li.sitem a {padding:8px 10px 8px 25px}
li.sitem > ul{transform:translateX(-30px);$startSide:100%;top:0}
li.sitem > ul:before{content:"";width:16px;height:16px;position:absolute;background:$(BacgroundHeader);top:8px;$startSide:-7px;z-index:-1;transform:rotate(45deg);border:1px solid #eee}
li.sitem:hover > ul{transform:translateX(0);opacity:1;visibility:visible}
li.sitem:last-of-type > a{border-bottom:0!important}
li.ssitem:last-of-type > a{border-bottom:0!important}
li.ssitem{float:none;margin-$endSide:0!important;width:100%}
.targetitem li a:hover:before {background: $(HoverLinkColor) !important;}
nav.nav-par ul li a:hover{color: $(HoverLinkColor) ;}
.stxk{position:fixed;top:0;$endSide:0;$startSide:0;bottom:0;background-color:rgba(0,0,0,0.58);z-index:999999999999;-webkit-box-shadow:0 1px 15px 5px rgba(32,33,36,0.1);box-shadow:0 1px 15px 5px rgba(32,33,36,0.1)}
.search-box{text-align:center;-webkit-box-align:center;-ms-flex-align:center;align-items:center;margin:0 auto;overflow:hidden;top:0;$endSide:0;$startSide:0;bottom:0}
.stxk{display:none}
.search-box{display:none}
.search-box-fix{width:100%;margin:0 auto;height:100%;max-width:600px;background:transparent;vertical-align:middle;display:table-cell;position:fixed;max-height:150px;$startSide:0;top:30%;bottom:0;$endSide:0;z-index:999999999999999;-webkit-box-align:center;-ms-flex-align:center;align-items:center;text-align:center}
.search-wrap{width:90%;height:100%;display:table;margin:0 auto;text-align:center;-webkit-box-align:center;-ms-flex-align:center;align-items:center;padding:0 20px;position:relative}
.search-fo{width:100%;height:100%;vertical-align:middle;display:table-cell}
.textst{font-size:40px;color:#fff;position:relative;top:-20px}
.search-field{text-align:center;-webkit-appearance:none;padding:10px;border:none!important;background:transparent;width:100%;border-bottom:2px dashed #9e9e9e!important;font-size:30px;font-weight:bold;font-family:monospace;color:#fff}
a.search-submit2{position:absolute;$endSide:-15px;top:-15px;margin:0;border-radius:50%;background:transparent}
.search-submit,.search-submit2{background:#2c82c9;-webkit-transition:.3s;-o-transition:.3s;transition:.3s;display:inline-block;margin:15px 0 -5px 0;width:45px;height:45px;position:relative;padding:7px 0;color:#ffffff;border-radius:5px;border:0!important}
a.search-submit2 svg{margin:5px 0 0 0!important;vertical-align:-1px;width:30px!important;height:30px!important}
.search-box.active,.stxk.active{display:block}
li.item.targetitem{margin-$endSide:30px}
li.item.targetitem:hover span.icon{transform:rotate(0);top:10px}
li.item.targetitem span.icon{color:$(keycolor);width:10px;position:absolute;top:8px;$endSide:-23px;$startSide:auto;transform:rotate(180deg);line-height:1}
li.item.targetitem .targetitem span.icon{width:8px!important;$endSide:5px!important;top:7px!important;transform:rotate(90deg)!important;$startSide:auto!important}
li.item.targetitem .targetitem:hover span.icon{$endSide:8px!important}
/* Style Headr 3 */
.sp-header.Style3{height:135px!important}
.sp-header.Style3 .head-pz{height:135px}
.sp-header.Style3 .par-tp{height:75px;max-width:100%;background:$(keycolor)}
.sp-header.Style3 .floar:before{display:none}
.sp-header.Style3  div#logo{float:$startSide;height:60px;width:200px;top:0;margin:8px 0}
.sp-header.Style3 div#logo div#header-inner{height:60px;width:200px}
.sp-header.Style3 div#logo div#header-inner img#Header1_headerimg{max-height:60px}
.titlewrapper a{color:$(keycolor)}
.sp-header.Style3 div#pages{margin:28px 0}
.sp-header.Style3 div#pages a{font-size:14px;padding:8px 15px;border-radius:30px}
.sp-header.Style3 div#pages a:hover,.sp-header.Style3 div#pages li.selected a{background:#fff;color:$(keycolor)}
.sp-header.Style3  .floar{width:100%;float:none}
.sp-header.Style3 i.fa{opacity:1;width:18px;height:17px}
.sp-header.Style3  div#top-social-L{margin:23px 0}
.sp-header.Style3 .par-bottm{top:75px}
.sp-header.Style3 div#logo{float:$startSide;height:60px;width:200px;top:0;margin:8px 0;margin-$endSide:5px}
.sp-header.Style3 .par-bottm nav.nav-par{float:$startSide;width:calc((100% - 50px) /1)!important}
.sp-header.Style3.active .head-pz{height:62px}
.sp-header.Style3.active .par-tp{top:-75px}
.sp-header.Style3.active .par-bottm{top:31px}
/* headr sidenav */
.pos-t-t{position:fixed;top:0;$endSide:0;$startSide:0;bottom:0;background-color:rgba(0,0,0,0.58);z-index:999999999;-webkit-box-shadow:0 1px 15px 5px rgba(32,33,36,0.1);box-shadow:0 1px 15px 5px rgba(32,33,36,0.1)}
.pos-t-t{display:none}
.pos-t-t.open{display:block}
.mop-pages,.mop-links{margin-bottom:15px}
.mop-icon{margin-top:15px;margin-bottom:15px}
.closebtn{text-align:$startSide;position:absolute;top:0;$endSide:0;font-size:23px;z-index:9999;height:55px;display:block;float:$endSide;line-height:53px;color:#484848;width:100%;padding:0 20px 0 10px}
.closebtn svg{width:1.3em;height:1.3em;margin-top:12px}
.sidenav{height:100vh;width:250px;position:fixed;top:0;$startSide:-260px;background-color:#ffffff;overflow-x:hidden;transition:0.3s;z-index:999999999999999999999999;padding-top:45px;padding-$startSide:10px;padding-$endSide:10px;padding-bottom:45px;max-width:100%}
.sidenav.open {$startSide: 0;}
.mop-icon .social-static.social li{float:$startSide;vertical-align:middle;list-style:none;width:calc((100% - 4px) / 4);margin-$endSide:1px;margin-bottom:1px}
.mop-icon .social-static.social li a{border-radius:0;text-align:center;height:50px;display:flex;align-items:center}
.mop-pages #PageList1{overflow:hidden;clear:both;height:inherit;width:inherit;display:block}
.mop-pages ul,.mop-links ul{padding-$startSide:30px}
.mop-pages ul li,.mop-links ul li{position: relative;margin: 0 !important;list-style:circle;font-size:13px!important}
.mop-pages ul li:hover,.mop-links ul li:hover{list-style:disc}
.mop-pages ul li a,.mop-links ul li a{color:#131313!important;display:block;padding-bottom:7px;margin-bottom:7px;border-bottom:1px solid #eee;font-size:13px}
.mop-links ul::before{display:none!important}
div#mop-links div#menu{display:block;height:auto;padding:15px;margin:0 -15px;background:#f7f7f7}
.mop-links ul{padding:0}
.mop-links ul li a{padding:12px 15px 10px!important;background:#dcdcdc;border-bottom:1px solid #d2d2d2;margin-bottom:0}
div#mop-links li.item span.icon{$endSide:5px!important;background:#fff;padding:0;height:22px;width:25px!important;border-radius:2px;display:flex;align-items:center;justify-content:center;margin:0!important;border:1px solid #d2d2d2;transform:none!important}
div#mop-links li.item span.icon svg{width:11px}
li.item.targetitem:hover span.icon{top:8px}
div#mop-links li.item > ul{transform:none!important;opacity:1!important;visibility:visible!important;position:relative!important;box-shadow:none!important;top:0!important;$startSide:auto!important;width:auto!important;border:none!important}
div#mop-links li.item a:before{display:none}
.mop-links li.item > ul li.sitem a{background:#d0d0d0}
.mop-links li.item > ul li.ssitem a{background:#dcdcdc}
.mop-links li.sitem ul{transform:none;$startSide:0;opacity:1;visibility:visible;position:initial;width:100%;border:0;background:#dcdcdc}
.mop-links li.sitem ul,div#mop-links li.item > ul{height:0!important;display:none}
.mop-links li.sitem ul.open,div#mop-links li.item > ul.open{height:auto!important;display:block}
/* headr stiky */
header.active .head-pz{height:72px;opacity:0.8}
header.active:hover .head-pz {opacity: 1;}
header.active .par-tp{top:-35px}
header.active .par-bottm{top:35px}
header.active div#logo{width:230px;height:50px}
header.active div#header-inner{width:230px;height:50px}
header.active div#header-inner img{max-height:50px}
header.active .search,header.active .open.nav1{top:-15px}
header.active nav.nav-par{top:-30px;width:calc((100% - 280px) /1)!important}

/* HomePagePostsStyle */
/* Main */
h3.rnav-title a{color:$(PostTitleColor);line-height:1.3em}
.rnav-title{clear:both;font-size:16px;overflow:hidden;height:4em}
.icon[data-icon="clock"]{vertical-align:-3px!important}
.thumb{float:$startSide;width:300px;height:300px;margin-$endSide:15px;display:block;-webkit-border-radius:5px;-moz-border-radius:5px;border-radius:5px;overflow:hidden;position:relative}
.thumb img{object-fit:cover;display:block;width:100%;height:100%}
.Ajax{display:flex;align-items:center;justify-content:center;min-height:410px;flex-direction:column}
.Ajax .icon-load{position:unset;width:50px;height:50px;display:block}
svg.icon-load{position:absolute;$endSide:7.1px;bottom:5px;width:22px;height:22px;color:$(keycolor)}
.withis{display:block;margin-top:20px}
.blocker{display:block;overflow:hidden;margin-top:15px}
.r-r{vertical-align:top}
.r-r{float:$startSide;width:calc((100% - $(sidebar.width) - 15px) / 1)}
#Postcs7,#Postcs3{margin-$startSide:15px}
.sides{width:calc((100% - 15px) / 2);float:$startSide}
.trelists{float:$startSide;width:calc((100% - 30px) / 3)}
div#Postnw5,div#Postnw2{margin:0 15px}
a.thumb.not-pl:before{content:"";position:absolute;background:linear-gradient(to bottom,rgba(0,0,0,0.15) 6%,rgba(0,0,0,0.68) 100%);height:100%;width:100%;display:block;z-index:8;transition:opacity 0.3s ease;opacity:0}
a.thumb.not-pl:after{content:"";z-index:9;position:absolute;display:block;transition:opacity 0.3s ease;opacity:0}
a.thumb.not-pl:hover:after{opacity:0.9!important}
.Sp-Normal .posts a.thumb.not-pl:after,.post-outer a.thumb.not-pl:after,.widget.FeaturedPost a.item-thumbnail.thumb.not-pl:after{width:28px;height:28px;top:43%;$startSide:45%}
.Sp-posts1 .posts a.thumb.not-pl:after{width:28px;height:28px;top:43%;$startSide:43%}
.Sp-posts5 .posts:not(:first-of-type) a.thumb.not-pl:after,.Sp-posts4 .posts:not(:first-of-type) a.thumb.not-pl:after,.Sp-posts3 .posts a.thumb.not-pl:after,.Sp-3colList .posts a.thumb.not-pl:after,.PopularPosts a.item-thumbnail.thumb.not-pl:after{width:20px;height:20px;top:40%;$startSide:40%}
.Sp-posts5 .posts:first-of-type a.thumb.not-pl:after{width:35px;height:35px;top:43%;$startSide:43%}
.Sp-slide .posts:not(:first-of-type) a.thumb.not-pl:after{width:28px;height:28px;top:43%;$startSide:43%}
/* == Posts1 and Posts0 == */
.Sp-posts1 .posts, .Sp-posts0 .posts{width:calc((100% - 30px) / 3);margin-$endSide:15px;display:inline-block;border-radius:2px;position:relative;vertical-align:top;margin-bottom:10px}
.Sp-posts1 a.thumb, .Sp-posts0 a.thumb{margin:0;width:100% !important;height:170px;position:relative}
.Sp-posts1 h3.rnav-title, .Sp-posts0 h3.rnav-title{display:block;overflow:hidden;clear:both;height:initial;font-size:initial}
.Sp-posts1 h3.rnav-title a, .Sp-posts0 h3.rnav-title a{font-size:15px;margin-top:8px;display:flex;margin-bottom:8px;max-height:2.8em;overflow:hidden;line-height:1.5em}
.Sp-posts1 .items a, .Sp-posts1 .items span{font-size:11px;display:inline-block;color:$(PostMetaColor);margin-$endSide:3px}
.Sp-posts1 .items{display:block!important;clear:both;padding:8px 0;border-top:1px solid #eee;border-bottom:1px solid #eee;vertical-align:middle;font-size:11px;color:$(PostMetaColor)}
.Sp-posts1 .Short_content{color:$(PostDescColor);line-height:1.7em;margin:5px 0;font-size:11px}
.Sp-posts1 .icon, .Sp-posts0 .icon{width:12px}
.Sp-posts1 .posts a.thumb.not-pl:after, .Sp-posts0 .posts a.thumb.not-pl:after{width:28px;height:28px;top:43%;$startSide:43%}
.Sp-posts1 .posts:nth-of-type(3n+3), .Sp-posts0 .posts:nth-of-type(3n+3) {margin-$endSide: 0;}
.Sp-posts1 .posts:nth-last-of-type(1), .Sp-posts1 .posts:nth-last-of-type(2), .Sp-posts1 .posts:nth-last-of-type(3), .Sp-posts0 .posts:nth-last-of-type(1), .Sp-posts0 .posts:nth-last-of-type(2), .Sp-posts0 .posts:nth-last-of-type(3){margin-bottom:0px}
/* == Posts3 == */
.Sp-posts3 .thumb{width:110px;height:90px}
.Sp-posts3 .posts{overflow:hidden;display:block;margin-bottom:15px;padding-bottom:15px;border-bottom:1px solid #eee}
.Sp-posts3 .cont{width:calc((100% - 125px) / 1);display:inline-block;overflow:hidden;margin-top:1px}
.Sp-posts3 .rnav-title a{font-size:14px;display:block;line-height:1.5em;max-height:4.5em;overflow:hidden}
.Sp-posts3 .posts:last-of-type{margin-bottom:0!important;padding-bottom:0!important;border-bottom:0!important}
.Sp-posts3 .items a{display:inline-block;margin-$endSide:3px;font-size:12px;color:$(PostMetaColor)}
.Sp-posts3 h3.rnav-title{margin-bottom:3px;height:inherit}
/* == 3colList == */
.Sp-3colList .thumb{width:110px;height:90px}
.Sp-3colList .posts{overflow:hidden;width:calc((100% - 30px) / 3);margin-$endSide:15px;vertical-align:top;display:inline-block;margin-bottom:15px;padding-bottom:15px;border-bottom:1px solid #eee}
.Sp-3colList .cont{width:calc((100% - 125px) / 1);display:inline-block;overflow:hidden;margin-top:1px}
.Sp-3colList .rnav-title a{font-size:14px;display:block;line-height:1.5em;max-height:4.5em;overflow:hidden}
.Sp-3colList .items a{display:inline-block;margin-$endSide:3px;font-size:12px;color:$(PostMetaColor)}
.Sp-3colList h3.rnav-title{margin-bottom:3px;height:inherit}
.Sp-3colList .posts:nth-of-type(3n+3) {margin-$endSide: 0;}
.Sp-3colList .posts:nth-last-of-type(1), .Sp-3colList .posts:nth-last-of-type(2), .Sp-3colList .posts:nth-last-of-type(3) {margin-bottom: 0;padding-bottom: 0;border-bottom: 0;}
/* == Posts2 == */
.Sp-posts2 .posts{width:calc((100% - 3px) / 3);margin:0 0 -5px 1px!important;margin-bottom:10px;display:inline-block;border-radius:0!important;position:relative}
.Sp-posts2 .posts.postnum3,.Sp-posts2 .posts.postnum4,.Sp-posts2 .posts.postnum5{margin-bottom:0}
.Sp-posts2 .posts.postnum0,.Sp-posts2 .posts.postnum1,.Sp-posts2 .posts.postnum2{margin-top:0}
.Sp-posts2 a.thumb{margin:0;width:100%;height:170px;position:relative;border-radius:1px!important}
.Sp-posts2 .posts.postnum2,.Sp-posts2 .posts.postnum5{margin-$endSide:0}
.Sp-posts2 .posts.postnum0,.Sp-posts2 .posts.postnum3{margin-$startSide:0}
.Sp-posts2 h3.rnav-title a{width: 100%;color:#fff;display:block;height:55px;overflow:hidden;align-items:center;text-shadow:0 1px 3px #000}
.Sp-posts2 h3.rnav-title{bottom:0;display:flex;font-size:14px;text-align:$startSide;align-items:center;vertical-align:middle;overflow:hidden;position:absolute;padding:0 10px 10px;height:80px;background:linear-gradient(to bottom,rgba(0,0,0,0.02) 6%,rgb(0,0,0) 100%);z-index:8;width:100%;$startSide:0;max-height:initial;border-radius:0;padding-top:13px}
.Sp-posts2 a.thumb.not-pl:after{content:"";background:url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' data-prefix='fal' data-icon='play-circle' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 512 512' class='play-circle'%3E%3Cpath fill='%23fff' d='M256 504c137 0 248-111 248-248S393 8 256 8 8 119 8 256s111 248 248 248zM40 256c0-118.7 96.1-216 216-216 118.7 0 216 96.1 216 216 0 118.7-96.1 216-216 216-118.7 0-216-96.1-216-216zm331.7-18l-176-107c-15.8-8.8-35.7 2.5-35.7 21v208c0 18.4 19.8 29.8 35.7 21l176-101c16.4-9.1 16.4-32.8 0-42zM192 335.8V176.9c0-4.7 5.1-7.6 9.1-5.1l134.5 81.7c3.9 2.4 3.8 8.1-.1 10.3L201 341c-4 2.3-9-.6-9-5.2z'%3E%3C/path%3E%3C/svg%3E") no-repeat center;width:1em;height:1em;display:block;z-index:9999999;position:absolute;top:10%;left:10%;opacity:0.5;padding:15px 13px;border-radius:2px;align-items:center;text-align:center;margin:0 auto;transition:.3s ease-in-out}
.Sp-posts2 .Posts-byCategory .posts:hover .thumb.not-pl:after{opacity:0.8;width:3em;height:100%;left:40%;top:0%}
.Sp-posts2 .posts:hover a.thumb.not-pl:before,a.thumb.not-pl:hover:before{opacity:1}
/* == posts4 and posts6 == */
.Sp-posts4 .posts,.Sp-posts6 .posts{position:relative;display:block;overflow:hidden;margin-bottom:15px;padding-bottom:15px;border-bottom:1px solid #eee}
.Sp-posts4 .posts.postnum0 .thumb{width:100%;height:200px;margin:0!important}
.Sp-posts6 .posts .thumb{width:100%;height:200px;margin:0!important}
.Sp-posts4 .posts.postnum0 h3.rnav-title,.Sp-posts6 .posts h3.rnav-title{display:block;clear:both;height:inherit}
.Sp-posts4 .posts.postnum0 .items,.Sp-posts6 .posts .items{display:inline-block;vertical-align:middle;font-size:11px;color:$(PostMetaColor);display:block}
.Sp-posts4 .posts .thumb{width:110px;height:90px}
.Sp-posts4 .posts.postnum0 .cont,.Sp-posts6 .posts .cont{position:absolute;padding:15px 10px!important;overflow:hidden;margin:-80px 10% 0;z-index:8;bottom:0;background:#fff!important;min-height:100px;text-align:center;display:block;width:80%}
.Sp-posts4 .posts.postnum0 .rnav-title,.Sp-posts6 .posts .rnav-title{clear:both;font-size:16px;overflow:hidden;height:45px}
.Sp-posts4 .posts.postnum0 h3.rnav-title a,.Sp-posts6 .posts h3.rnav-title a{font-size:14px;height:2.8em;display:block;margin-bottom:3px;overflow:hidden}
.Sp-posts4 .posts.postnum0 .icon{width:12px}
.Sp-posts4 .posts.postnum0 .items a,.Sp-posts4 .posts.postnum0 .items span,.Sp-posts6 .posts .items a,.Sp-posts6 .posts .items span{font-size:11px;color:$(PostMetaColor);margin-$endSide:5px;display:inline-block}
.Sp-posts4 .posts:not(.postnum0) .rnav-title a{font-size:14px;display:block;line-height:1.5em;max-height:4.5em;overflow:hidden}
.Sp-posts4 .posts:not(.postnum0) .cont{width:calc((100% - 125px) / 1);display:inline-block;overflow:hidden;margin-top:1px}
.Sp-posts4 .posts:not(.postnum0) h3.rnav-title{margin-bottom:3px;height:inherit}
.Sp-posts4 .posts:not(.postnum0) .items a{display:inline-block;margin-$endSide:3px;font-size:12px;color:$(PostMetaColor)}
.Sp-posts4 .posts:last-of-type,.Sp-posts6 .posts:last-of-type{margin-bottom:0!important;padding-bottom:0!important;border-bottom:0!important}
aside#sidepar-wid .Sp-posts3 .thumb, aside#sidepar-wid .Sp-posts4 .posts:not(.postnum0) .thumb {width: 90px!important;height: 70px;}
aside#sidepar-wid .Sp-posts3 .cont, aside#sidepar-wid .Sp-posts4 .posts:not(.postnum0) .cont {width: calc((100% - 125px) / 1);}
aside#sidepar-wid .Sp-posts3 .cont h3.rnav-title a, aside#sidepar-wid .Sp-posts4 .posts:not(.postnum0) .cont h3.rnav-title a {font-size: 13px;}
aside#sidepar-wid .Sp-posts4 .posts.postnum0 .thumb ,aside#sidepar-wid .Sp-posts6 .posts .thumb {height: 200px;}
aside#sidepar-wid .Sp-posts4 .posts.postnum0 .cont,aside#sidepar-wid .Sp-posts6 .posts .cont  {margin: -80px 3% 0!important;width: 94%!important;}
/* == posts5 == */
.Sp-posts5 .posts.postnum0{margin-$endSide:15px;padding-$endSide:15px;width:50%;vertical-align:top;display:inline-block;overflow:hidden;margin-bottom:15px;padding-bottom:0;border-$endSide:1px solid #eee;border-bottom:0;height:469px}
.Sp-posts5 .posts.postnum0 a.thumb{width:100%;height:300px}
.Sp-posts5 .posts.postnum0 h3.rnav-title{display:block;clear:both;height:inherit;font-size:inherit}
.Sp-posts5 .posts.postnum0 h3.rnav-title a{color:$(PostTitleColor);font-size:17px;margin-top:6px;display:flex;margin-bottom:8px;max-height:4.3em;overflow:hidden;line-height:1.5em}
.Sp-posts5  .items a,.Sp-posts5 .items span{font-size:11px;display:inline-block;color:$(PostMetaColor);margin-$endSide:3px}
.Sp-posts5 .posts.postnum0 .items{display:block!important;clear:both;padding:8px 0;border-top:1px solid #eee;border-bottom:1px solid #eee;vertical-align:middle;font-size:11px;color:$(PostMetaColor)}
.Sp-posts5 .posts.postnum0 .items{display:inline-block;vertical-align:middle;font-size:11px;color:$(PostMetaColor);display:block}
.Sp-posts5 .posts.postnum0 .Short_content{color:$(PostDescColor);line-height:1.7em;margin:5px 0;font-size:12px;display:block !important}
.Sp-posts5 .posts{float:$startSide;width:calc((100% - 50% - 15px) / 1);display:inline-block;vertical-align:top;margin-bottom:15px;padding-bottom:15px;border-bottom:1px solid #eee}
.Sp-posts5 .posts .thumb{width:110px;height:90px}
.Sp-posts5 .posts:not(.postnum0) .cont{width:calc((100% - 125px) / 1);display:inline-block;overflow:hidden;margin-top:1px}
.Sp-posts5 .posts.postnum4{border-bottom: 0}
.Sp-posts5 .posts:not(.postnum0) h3.rnav-title{margin-bottom:3px;height:inherit}
.Sp-posts5 .posts:not(.postnum0) .rnav-title a{font-size:14px;display:block;line-height:1.5em;max-height:4.5em;overflow:hidden}
.Sp-posts5 .posts:not(.postnum0) .items a{display:inline-block;margin-$endSide:3px;font-size:12px;color:$(PostMetaColor)}
.Sp-posts5 a.thumb.not-pl:hover:after,.Sp-posts1 a.thumb.not-pl:hover:after{opacity:0.9!important}
.Sp-posts5 .posts:not(.postnum0) a.thumb.not-pl:after,.Sp-posts4 .posts:not(.postnum0) a.thumb.not-pl:after,.Sp-posts3 .posts a.thumb.not-pl:after,.Sp-3colList .posts a.thumb.not-pl:after,.PopularPosts a.item-thumbnail.thumb.not-pl:after{width:20px;height:20px;top:40%;$startSide:40%}
.Sp-posts5 .posts.postnum0 a.thumb.not-pl:after{width:35px;height:35px;top:43%;$startSide:43%}
.Sp-posts5 .posts.postnum5, .Sp-posts5 .posts.postnum7, .Sp-posts5 .posts.postnum6, .Sp-posts5 .posts.postnum8 {padding-bottom: 0;border-bottom: 0;}
.Sp-posts5 .posts.postnum5, .Sp-posts5 .posts.postnum7 {margin-$endSide: 15px;width: calc((100% - 50% - 7.5px) / 1);}
.Sp-posts5 .posts.postnum6, .Sp-posts5 .posts.postnum8 {padding-$startSide: 10px;margin-$endSide: 0;width: calc((100% - 50% - 7.5px) / 1);}
.Sp-posts5 {margin-bottom: -15px;}
/* == slide == */
.Sp-slide .items a {margin-$endSide: 5px;}
.Sp-slide .posts{overflow:hidden;position:relative}
.Sp-slide .posts.postnum0{$startSide:22.5%;$endSide:auto;float:$startSide;width:55%;padding:0 10px;height:400px}
.Sp-slide .posts:not(.postnum0){height:200px}
.Sp-slide .posts.postnum1,.Sp-slide .posts.postnum3{$startSide:-55%;padding-$endSide:20px;$endSide:auto;float:$startSide;width:22.5%}
.Sp-slide .posts.postnum1,.Sp-slide .posts.postnum2{margin-bottom:10px}
.Sp-slide .posts.postnum2,.Sp-slide .posts.postnum4{padding-$startSide:20px;width:22.5%;float:$endSide}
.Sp-slide .posts.postnum0 .thumb{margin-bottom:10px;float:$startSide;width:100%;height:400px;display:block;-webkit-border-radius:2px;-moz-border-radius:2px;border-radius:2px;overflow:hidden;position:relative}
.Sp-slide .posts:not(.postnum0) .thumb{margin:0 0 10px;height:140px}
.Sp-slide .thumb {width: 100%;}
.Sp-slide .posts.postnum0 .cont{position:relative;padding:12px 15px!important;overflow:hidden;margin:-80px 35px 0;z-index:8;top:-100px;background:#fff!important;min-height:100px;text-align:center}
.Sp-slide .posts.postnum0 h3.rnav-title a{font-weight: bold;font-size:16px}
.Sp-slide, .Posts-byCategory {overflow: hidden;}
.Sp-slide .posts:not(.postnum0) .rnav-title{padding:0 5px;max-height:3em;font-weight:400;font-size:14px;text-align:center;text-transform:none;display:block;overflow:hidden}
.Sp-slide .posts:not(.postnum0) .rnav-title a{font-size:14px;color:$(PostTitleColor)}
.Sp-slide .items a, .Sp-slide .items span {font-size: 12px;color: $(PostMetaColor);margin-$endSide: 5px;display: inline-block;}
.Sp-slide .items a {margin-$endSide: 2px;}
.Sp-slide .posts.postnum0 h3.rnav-title{font-size:inherit;height:inherit}
.Sp-slide .posts.postnum0 h3.rnav-title a{display:block;overflow:hidden;line-height:1.5em;max-height:3em;margin-bottom:2px;font-weight:normal}
.Sp-slide .posts:not(.postnum0) a.thumb.not-pl:after{width:28px;height:28px;top:43%;$startSide:43%}
.Sp-slide .posts.postnum5, .Sp-slide .posts.postnum6, .Sp-slide .posts.postnum7, .Sp-slide .posts.postnum8 {position: relative;display: block;float: $startSide;width: calc((100% - 45px) / 4);margin-$endSide: 15px !important;margin-top: 15px;}
.Sp-slide .posts.postnum8 {margin-$endSide: 0 !important;}
/* == shreet == */
.Sp-shreet .thumb,.Sp-shreet .Short_content,.Sp-shreet .items{display:none}
.Sp-shreet h3.rnav-title{height:auto}
.Sp-shreet h3.rnav-title a{line-height:initial;display:block;text-overflow:ellipsis;white-space:nowrap;font-size:14px}
.Sp-shreet .posts{padding-$endSide:20px}
div#shreeta5bar .Label{padding:0 20px;height:60px;background:#fefefe;display:flex;align-items:center;flex-flow:nowrap;flex:1 100%;box-shadow:0 6px 18px 0 rgba(9,32,76,.035)!important;margin-bottom:15px}
#shreeta5bar .headline{flex-shrink:0;margin-$endSide:15px}
#shreeta5bar .headline,.Sp-shreet{margin:0}
.Sp-shreet{position:relative;width:100%;height:40px;display:flex;overflow:hidden;align-items:center}
.Sp-shreet .Posts-byCategory{display:flex;$startSide:100%;position:absolute;transition:none!important;min-width:101%}
#shreeta5bar .headline .title{float:$startSide;height:35px;line-height:35px;padding:0 20px 0 50px;padding-top:0;padding-bottom:0;padding-$startSide:50px;padding-$endSide:20px;background:$(keycolor);color:#ffffff;font-size:14px;position:relative;z-index:1}
div#shreeta5bar .Ajax{display:block;height:initial!important;min-height:inherit!important}
#shreeta5bar .headline .title:before {content: "";position: absolute;$startSide: 17px;top: 7px;width: 20px;height: 20px;background: url("data:image/svg+xml,%3Csvg aria-hidden='true' focusable='false' data-prefix='fal' data-icon='newspaper' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 576 512'%3E%3Cpath fill='%23fff' d='M552 64H88c-13.234 0-24 10.767-24 24v8H24c-13.255 0-24 10.745-24 24v280c0 26.51 21.49 48 48 48h504c13.233 0 24-10.767 24-24V88c0-13.233-10.767-24-24-24zM32 400V128h32v272c0 8.822-7.178 16-16 16s-16-7.178-16-16zm512 16H93.258A47.897 47.897 0 0 0 96 400V96h448v320zm-404-96h168c6.627 0 12-5.373 12-12V140c0-6.627-5.373-12-12-12H140c-6.627 0-12 5.373-12 12v168c0 6.627 5.373 12 12 12zm20-160h128v128H160V160zm-32 212v-8c0-6.627 5.373-12 12-12h168c6.627 0 12 5.373 12 12v8c0 6.627-5.373 12-12 12H140c-6.627 0-12-5.373-12-12zm224 0v-8c0-6.627 5.373-12 12-12h136c6.627 0 12 5.373 12 12v8c0 6.627-5.373 12-12 12H364c-6.627 0-12-5.373-12-12zm0-64v-8c0-6.627 5.373-12 12-12h136c6.627 0 12 5.373 12 12v8c0 6.627-5.373 12-12 12H364c-6.627 0-12-5.373-12-12zm0-128v-8c0-6.627 5.373-12 12-12h136c6.627 0 12 5.373 12 12v8c0 6.627-5.373 12-12 12H364c-6.627 0-12-5.373-12-12zm0 64v-8c0-6.627 5.373-12 12-12h136c6.627 0 12 5.373 12 12v8c0 6.627-5.373 12-12 12H364c-6.627 0-12-5.373-12-12z' class=''%3E%3C/path%3E%3C/svg%3E") center no-repeat;display: block;}

.Sp-shreet h3.rnav-title a:before {margin-$endSide: 5px;content:'';background: url("data:image/svg+xml,%3Csvg aria-hidden='true' focusable='false' data-prefix='fal' data-icon='file-alt' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 384 512'%3E%3Cpath fill='%23444' d='M369.9 97.9L286 14C277 5 264.8-.1 252.1-.1H48C21.5 0 0 21.5 0 48v416c0 26.5 21.5 48 48 48h288c26.5 0 48-21.5 48-48V131.9c0-12.7-5.1-25-14.1-34zm-22.6 22.7c2.1 2.1 3.5 4.6 4.2 7.4H256V32.5c2.8.7 5.3 2.1 7.4 4.2l83.9 83.9zM336 480H48c-8.8 0-16-7.2-16-16V48c0-8.8 7.2-16 16-16h176v104c0 13.3 10.7 24 24 24h104v304c0 8.8-7.2 16-16 16zm-48-244v8c0 6.6-5.4 12-12 12H108c-6.6 0-12-5.4-12-12v-8c0-6.6 5.4-12 12-12h168c6.6 0 12 5.4 12 12zm0 64v8c0 6.6-5.4 12-12 12H108c-6.6 0-12-5.4-12-12v-8c0-6.6 5.4-12 12-12h168c6.6 0 12 5.4 12 12zm0 64v8c0 6.6-5.4 12-12 12H108c-6.6 0-12-5.4-12-12v-8c0-6.6 5.4-12 12-12h168c6.6 0 12 5.4 12 12z'%3E%3C/path%3E%3C/svg%3E") center no-repeat;display: inline-block;vertical-align: middle;width: 13px;height: 13px;}

/* HomePage Posts */
.post-outer, .Sp-Normal .posts{display:block;overflow:hidden;padding-bottom:20px;border-bottom:1px solid #eee;margin-bottom:20px;position:relative}
.post-outer .thumb, .Sp-Normal .posts .thumb{width:300px;height:180px}
.post-home, .Sp-Normal .posts .cont{width:calc((100% - 315px) / 1);float:$startSide}
.post-outer .items, .Sp-Normal .posts .items{display:block;clear:both;padding:8px 0;border-top:1px solid #eee;border-bottom:1px solid #eee;vertical-align:middle;font-size:11px;color:$(PostMetaColor)}
.post-outer .items, .Sp-Normal .posts .items{display:block;vertical-align:middle;font-size:11px;color:$(PostMetaColor)}
.post-outer .items a,.post-outer .items span, .Sp-Normal .posts .items a, .Sp-Normal .posts .items span{font-size:12px;display:inline-block;color:$(PostMetaColor);margin-$endSide:3px}
.post-outer .posts-titles a, .Sp-Normal .posts .rnav-title a{line-height:1.5em;margin-bottom:7px;display:block;max-height:4.6em;font-size:16px;color:$(PostTitleColor)}
.post-outer .posts-titles, .Sp-Normal .posts .rnav-title{height:inherit;clear:both;font-size:16px;overflow:hidden}
.post-outer .Short_content, .Sp-Normal .posts .Short_content{color:$(PostDescColor);line-height:1.7em;margin:5px 0;font-size:12px}
.post-outer:last-of-type, .Sp-Normal .posts:last-of-type{padding-bottom: 0!important;border-bottom: 0!important;margin-bottom: 0!important;}
.post-outer .moreLink, .Sp-Normal .posts .moreLink {display: inline-block !important;margin-top: 5px;position: relative;font-size: 14px;background: $(keycolor);color: $(grad.color);padding: 7px 15px 7px 15px;border-radius: 2px;}
.loadMore{margin-top:15px;text-align:center;overflow:hidden;display:block;clear:both}
.noMorePosts,div#loader,.loadMore .loadMorePosts a{width:130px;background:$(keycolor);color:$(grad.color);display:block;margin:0 auto;position:relative;font-size:14px;border-radius:1px;padding:8px 13px;text-align:$startSide}
.loadMore .loadMorePosts a:before,.noMorePosts:before,div#loader:before{content:"";width:27px;height:27px;display:block;background:#fff;position:absolute;$endSide:5px;bottom:4px;border-radius:100%}
svg.icon-load{position:absolute;$endSide:7.1px;bottom:5px;width:22px;height:22px;color:$(keycolor)}
div#loader svg.icon-load{bottom:7px;$endSide:8px;width:21px;height:21px}
.noMorePosts{width:150px!important}
.noMorePosts svg.icon-load{width:19px;height:19px;bottom:8px;$endSide:9px}
.blog-pager {display: none;}
/* blog-pager2 */
.MopileFasterVirson{display:flex;align-items:center;justify-content:center;overflow:hidden;margin-top:15px}
div#blog-pager a#Blog1_blog-pager-newer-link,div#blog-pager a#Blog1_blog-pager-older-link,div#blog-pager .homelink a{font-family:initial!important;width:40px;height:40px;display:block;text-align:center;color:#fff;background:$(keycolor);margin:0 1px;font-size:31px;font-weight:bold;border-radius:2px}
div#blog-pager .homelink a{border-radius:1px}
div#blog-pager .homelink a svg{width:18px;height:16px}
div#blog-pager a#Blog1_blog-pager-newer-link{border-radius:1px 30px 30px 1px}
div#blog-pager a#Blog1_blog-pager-older-link{border-radius:30px 1px 1px 30px}
body.ltr div#blog-pager a#Blog1_blog-pager-older-link {
    border-radius: 1px 30px 30px 1px;
}
body.ltr div#blog-pager a#Blog1_blog-pager-newer-link {
    border-radius: 30px 1px 1px 30px;
}

/* Aside */
#sidepar-wid{transition: none !important;width:$(sidebar.width);float:$endSide;margin-$startSide:15px;vertical-align:top}
body.ltr #sidepar-wid{left: auto !important;right: 0 !important;}
/* FeaturedPost Widget */
.widget.FeaturedPost .post-title{margin-bottom:3px}
.widget.FeaturedPost .post-title a{font-size:16px;display:block;line-height:1.7em;max-height:4.5em;overflow:hidden;color:$(PostTitleColor);font-weight:normal}
.widget.FeaturedPost p.snippet-item.r-snippetized{color:$(PostDescColor);line-height:1.7em;margin:5px 0;font-size:12px}
.widget.FeaturedPost .item-thumbnail.thumb{width:100%;min-height:150px;margin:0;height:auto}
/* PopularPosts Widget */
.PopularPosts a.item-thumbnail.thumb{width:90px;height:70px;margin-$endSide:10px}
.PopularPosts h3.post-title{width:calc((100% - 100px) / 1);float:$endSide;overflow:hidden;margin-top:1px;text-align:$startSide;max-height:4em}
.PopularPosts h3.post-title a{font-size:13px;color:$(PostTitleColor)}
.PopularPosts article.post{display:block;overflow:hidden;clear:both;margin-bottom:15px;padding-bottom:15px;border-bottom:1px solid #eee}
.PopularPosts article.post:last-of-type{margin-bottom:0!important;padding-bottom:0!important;border-bottom:0!important}
/* profile */
img.profile-img{border-radius:100%;border:1px solid #eee;margin:0 auto 15px;text-align:center;display:block}
.profile-info a.profile-link.g-profile{background:#eee;color:#000;display:inline-block;font-size:14px;border:1px solid #ccc;padding:5px 15px;border-radius:2px;margin-bottom:8px;margin-top:0}
dd.profile-textblock{font-size:12px;color:#383838}
.profile-info a.profile-link{display:none}
/* BlogSearch */
.BlogSearch input {border: 1px solid #f3f3f3;background: transparent;font-size: 13px;padding: 10px;border-radius: 3px;display: inline-block;width: 55px;}
.BlogSearch input.search-action:hover {background: $(keycolor);color: #ffffff;}
input.search-action{cursor: pointer;}
.search-input{display:inline-block;width:calc((100% - 60px) / 1)}
.search-input input{display:block;width:100%}
/* aside linklist */
aside .LinkList ul,footer .LinkList ul,aside .PageList ul,footer .PageList ul{padding-$startSide:30px}
aside .LinkList ul li,footer .LinkList ul li,aside .PageList ul li,footer .PageList ul li{list-style:circle;padding-bottom:7px;margin-bottom:7px;border-bottom:1px solid #eee}
aside .LinkList ul li a,footer .LinkList ul li a,aside .PageList ul li a,footer .PageList ul li a{font-size:14px;display:block;color:#000}
aside .LinkList ul li:last-of-type,footer .LinkList ul li:last-of-type,aside .PageList ul li:last-of-type,footer .PageList ul li:last-of-type{margin-bottom:0!important;padding-bottom:0!important;border-bottom:0!important}
/* Label Widget */
.widget .list-label-widget-content ul{padding-$startSide:20px}
.widget .list-label-widget-content ul li{font-size:14px;color:#1f1f1f;margin-bottom:5px;padding:4px 0;padding-bottom:7px;list-style:decimal;border-bottom:1px dashed #eee}
.widget .list-label-widget-content ul li a{color:#3e3e3e;font-size:13px;.cloud-label-widget-contentdisplay:block;padding:2px}
.widget .list-label-widget-content ul li:last-of-type{margin-bottom:0!important;border-bottom:0!important;padding-bottom:0!important}
span.label-count{float:$endSide;color:#585858;text-align:center}

.widget.Label .cloud-label-widget-content span.label-size{float:$startSide;width:calc((100% - 10px) / 2);vertical-align:middle;display:block;margin-bottom:10px}
.widget.Label .cloud-label-widget-content span.label-size a.label-name{padding:10px 10px;display:block;border-radius:30px;text-align:center;font-size:13px;color:#565656;border:1px solid #e6e6e6;background:#f7f7f7}
.widget.Label .cloud-label-widget-content span.label-size:nth-of-type(odd){margin-$endSide:10px}
.widget.Label .cloud-label-widget-content span.label-size:nth-last-of-type(1),.widget.Label .cloud-label-widget-content span.label-size:nth-last-of-type(2){margin-bottom:0}
.widget.Label .cloud-label-widget-content span.label-size a:hover,.shareButton a:hover,.PagePrakediv a:hover{box-shadow:0 5px 14px rgba(0,0,0,0.15),0 1px 5px rgba(0,0,0,0.12)}
.cloud-label-widget-content span.label-count {display:none}

/* FollowByEmail Widget */
input.follow-by-email-address{display:block;width:100%;height:40px;margin:15px 0;border-radius:3px;border:1px solid #efefef;text-align:center}
input.follow-by-email-submit{background:#eee;border:1px solid #ccc;padding:10px;border-radius:3px;width:100%;text-align:center;color:#6b6b6b;font-size:12px;cursor:pointer}
input.follow-by-email-address::placeholder{font-weight:normal;font-size:14px}
/* nextprev */
#siki_next,#siki_prev{background:#fff;display:inline-block;cursor:pointer;border:2px solid $(step.color);border-$endSide:8px solid $(step.color);border-radius:35px;margin:3px!important;transition:all 0.3s}
float:$startSide;border-$endSide:7px double #fff;border-radius:0 5px 5px 0}
.siki-next-prev a{display:block}
#siki_prev span:nth-child(1){float:$endSide;font-size:15px;line-height:35px;padding:0 30px 0 10px;position:relative}
.siki-next-prev span{font-size:30px;color:#585858}
#siki_prev span:nth-child(2){float:$startSide;line-height:45px}
#siki_next{float:$endSide;border:2px solid $(step.color);border-$startSide:8px solid $(step.color);border-radius:35px;margin:0}
#siki_next span:nth-child(1):before{display:block;width:1.5em;height:1.5em;content:"";top:7px;$endSide:4px;background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' version='1.1' viewBox='0 0 129 129' enable-background='new 0 0 129 129'%3E%3Cg%3E%3Cg%3E%3Cpath d='m64.5,122.6c32,0 58.1-26 58.1-58.1s-26-58-58.1-58-58,26-58,58 26,58.1 58,58.1zm0-108c27.5,5.32907e-15 49.9,22.4 49.9,49.9s-22.4,49.9-49.9,49.9-49.9-22.4-49.9-49.9 22.4-49.9 49.9-49.9z' fill='%23264079' %3E%3C/path%3E%3Cpath d='m70,93.5c0.8,0.8 1.8,1.2 2.9,1.2 1,0 2.1-0.4 2.9-1.2 1.6-1.6 1.6-4.2 0-5.8l-23.5-23.5 23.5-23.5c1.6-1.6 1.6-4.2 0-5.8s-4.2-1.6-5.8,0l-26.4,26.4c-0.8,0.8-1.2,1.8-1.2,2.9s0.4,2.1 1.2,2.9l26.4,26.4z' fill='%23264079'%3E%3C/path%3E%3C/g%3E%3C/g%3E%3C/svg%3E");position:absolute}
#siki_next span:nth-child(2){float:$endSide;line-height:45px}
#siki_next span:nth-child(1){float:$startSide;font-size:15px;line-height:35px;padding:0 10px 0 30px;position:relative}
body.ltr #siki_next span:nth-child(1) {
    padding: 0 30px 0 10px;
}
body.ltr #siki_prev span:nth-child(1){
    padding: 0 10px 0 30px;
}
#siki_next span:nth-child(1):before, #siki_prev span:nth-child(1):before {
    transform: rotate(180deg);
}
#siki-page-number{text-align:center;color:#292929;font-size:14px;position:absolute;$startSide:calc((100% - 110px) / 2);$endSide:calc((100% - 110px) / 2);display:inline-block;align-items:center;width:110px;padding:15px 0 0}
#siki_prev span:nth-child(1):before{display:block;width:1.5em;height:1.5em;content:"";top:7px;$startSide:4px;background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' version='1.1' viewBox='0 0 129 129' enable-background='new 0 0 129 129'%3E%3Cg%3E%3Cg%3E%3Cpath d='M64.5,122.6c32,0,58.1-26,58.1-58.1S96.5,6.4,64.5,6.4S6.4,32.5,6.4,64.5S32.5,122.6,64.5,122.6z M64.5,14.6 c27.5,0,49.9,22.4,49.9,49.9S92,114.4,64.5,114.4S14.6,92,14.6,64.5S37,14.6,64.5,14.6z' fill='%23264079'%3E%3C/path%3E%3Cpath d='m51.1,93.5c0.8,0.8 1.8,1.2 2.9,1.2 1,0 2.1-0.4 2.9-1.2l26.4-26.4c0.8-0.8 1.2-1.8 1.2-2.9 0-1.1-0.4-2.1-1.2-2.9l-26.4-26.4c-1.6-1.6-4.2-1.6-5.8,0-1.6,1.6-1.6,4.2 0,5.8l23.5,23.5-23.5,23.5c-1.6,1.6-1.6,4.2 0,5.8z' fill='%23264079'%3E%3C/path%3E%3C/g%3E%3C/g%3E%3C/svg%3E");position:absolute}
#siki_prev:hover{border:2px solid $(step.color);border-$endSide:2px solid $(step.color);border-$startSide:8px solid $(step.color)}
#siki_next:hover{border:2px solid $(step.color);border-$endSide:8px solid $(step.color);border-$startSide:2px solid $(step.color)}

/* BlogArchive */
div#ArchiveList ul.hierarchy{padding-$startSide:30px}
div#ArchiveList ul.hierarchy ul.hierarchy{padding-$startSide:15px}
div#ArchiveList ul.hierarchy ul.hierarchy ul.hierarchy  li:not(:last-of-type){margin-bottom:5px;padding-bottom:5px}
div#ArchiveList ul.hierarchy li a, div#ArchiveList ul.flat li a{color:#121212}
div#ArchiveList ul.hierarchy ul.hierarchy ul.hierarchy li:first-of-type{margin-top:5px;padding-top:5px}
div#ArchiveList ul.hierarchy li{font-size:11px}
div#ArchiveList ul.hierarchy li a:hover, div#ArchiveList ul.flat li a:hover{color:$(step.color)}
div#ArchiveList .hierarchy-title{font-size:13px;margin-bottom:5px;padding-bottom:5px;border-bottom:1px solid #f7f7f7}
div#ArchiveList .hierarchy-title span.post-count, div#ArchiveList ul.flat li span.post-count{float:$endSide;width:25px;padding:0 0;text-align:center;background:#eee;border-radius:3px;border:1px solid #ccc;font-size:12px;font-weight:normal}
div#ArchiveList ul.flat {padding-$startSide: 30px;}
div#ArchiveList ul.flat li:not(:last-of-type) {margin-bottom: 5px;padding-bottom: 5px;}
div#ArchiveList ul.flat li {font-size: 13px;}
/* InPost And Page */
.page .reaction-buttons {display: none;}
.post-body{font:$(PostsTextFont);line-height:2em;overflow:hidden;color:$(PostsTextColor)}
.post-body a{color:$(PostsLinkColor)}
.post div#Blog1,.post .post-outer,.post .post-body{overflow:initial!important}
.post div#Blog1,.page div#Blog1{display:block;background:transparent;border-radius:0;padding:0;border:0;margin:0;box-shadow:none}
.bobxed,.topcs7v,.topic-nav,.Blog article.post .post-share,.reaction-buttons,section#comments,.amp-tags,.shareButton,.RelatedPosts,.author-posts,.post-body,.page-navigation,.mopspeed a#opencmt{display:block;background:#fefefe!important;clear:both;border-radius:$(contentBorderRadius)!important;padding:20px!important;overflow:hidden;margin:0 0 15px!important;box-shadow:0 6px 18px 0 rgba(9,32,76,.035)!important;margin-top:15px}
/* tocList */
.toctitle{display:block;font-size:17px;padding-bottom:6px;border-bottom:1px solid #eee;margin-bottom:10px;position:relative;padding-$startSide:16px}
ul#tocList li{list-style:none}
ul#tocList li a{list-style:none;margin-bottom:5px;padding:8px 15px;border-bottom:1px solid #d9d9d9;background:#eee;border-radius:3px;color:#545454;display:block}
ul#tocList li a:hover{border-bottom:1px solid #ccc;background:#e5e5e5;color:#222}
.toctitle:before{content:"*";color:$(keycolor);padding-$endSide:5px;line-height:1em;position:absolute;$startSide:5px;top:8px}
.closetoc:before{position:absolute;$endSide:10px;top:10px;display:block;content:"إخفاء";font-size:14px;padding:5px 15px;background:#f1f1f1;color:#000;cursor:pointer;border-radius:3px;z-index:8}
.topcs7v{position:relative}
.topcs7v.closed .closetoc:before{content:"إظهار"}
body.ltr .closetoc:before {
    content: "Hide";
}
body.ltr .topcs7v.closed .closetoc:before {
    content: "Show";
}
.topcs7v.closed ul#tocList{display:none}
/* img */
table.tr-caption-container{position:relative}
td.tr-caption{color:#fff;position:absolute;bottom:5%;$startSide:0;background:rgb(0 0 0 / 65%);text-align:$startSide;padding:0 20px;height:36px;line-height:36px}
.post-body img{width:auto;height:auto;display:inline;max-width:100%}
.separator,.separator a,a[imageanchor="1"],a[style*='1em']{margin:0!important}
/* items */
.post-body strike{text-decoration:line-through}
.post-body u{text-decoration:underline}
.post-body ul li,.post-body ol li{margin-bottom:3px;padding-bottom:3px}
.post-body ul,.post-body ol{padding-$startSide:30px}
.post-body ol li:before {
    list-style: disc;
    content: counter(li);
    font-size: 16px;
    padding: 2px 5px;
    line-height: 1.5rem;
    min-width: 30px;
    display: inline-block;
    text-align: center;
    background: $(keycolor);
    border-radius: 3px;
    margin-$endSide: 8px;
    color: #fff;
}
.post-body ol li{counter-increment:li;list-style:none;font-size:16px}
.post-body ol{padding-$startSide:5px}
.post-body h1,.post-body h2,.post-body h3,.post-body h4{display: block;padding:13px 20px;margin:5px 0 10px}
.post-body h4{background:$(PostsH4Bacground)!important;font:$(PostsH4Font)!important;border-bottom:1px solid $(PostsH4BorderBottm)!important;color:$(PostsH4Color)!important}
.post-body h3{background:$(PostsH3Bacground)!important;font:$(PostsH3Font)!important;border-bottom:1px solid $(PostsH3BorderBottm)!important;color:$(PostsH3Color)!important}
.post-body h2{background:$(PostsH2Bacground)!important;font:$(PostsH2Font)!important;border-bottom:1px solid $(PostsH2BorderBottm)!important;color:$(PostsH2Color)!important}
.post-body h1{background:$(PostsH1Bacground)!important;font:$(PostsH1Font)!important;border-bottom:1px solid $(PostsH1BorderBottm)!important;color:$(PostsH1Color)!important}
.post-body blockquote {color: #545454;font-size: 100%;background-color: #efefef;border-$endSide: none;padding: 20px;margin: 20px 0;position: relative;text-align: $startSide;clear: both;font-size: 15px;border-radius: 5px;border: 1px solid #dbdbdb;}
.post-body blockquote:before,.post-body blockquote:after{vertical-align: middle;width: 22px;height: 22px;text-align: center;display: inline-block;margin-$endSide: 15px;margin-bottom: 0;content: "";background: url("data:image/svg+xml;charset=utf8,%3Csvg aria-hidden='true' data-prefix='far' data-icon='quote-$startSide' role='img' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 576 512'%3E%3Cpath fill='%23777' d='M200 32H72C32.3 32 0 64.3 0 104v112c0 39.7 32.3 72 72 72h56v8c0 22.1-17.9 40-40 40h-8c-26.5 0-48 21.5-48 48v48c0 26.5 21.5 48 48 48h8c101.5 0 184-82.5 184-184V104c0-39.7-32.3-72-72-72zm24 264c0 75-61 136-136 136h-8v-48h8c48.5 0 88-39.5 88-88v-56H72c-13.2 0-24-10.8-24-24V104c0-13.2 10.8-24 24-24h128c13.2 0 24 10.8 24 24v192zM504 32H376c-39.7 0-72 32.3-72 72v112c0 39.7 32.3 72 72 72h56v8c0 22.1-17.9 40-40 40h-8c-26.5 0-48 21.5-48 48v48c0 26.5 21.5 48 48 48h8c101.5 0 184-82.5 184-184V104c0-39.7-32.3-72-72-72zm24 264c0 75-61 136-136 136h-8v-48h8c48.5 0 88-39.5 88-88v-56H376c-13.2 0-24-10.8-24-24V104c0-13.2 10.8-24 24-24h128c13.2 0 24 10.8 24 24v192z' %3E%3C/path%3E%3C/svg%3E") center no-repeat;}
.post-body blockquote:after {margin-$endSide: 0;margin-$startSide: 15px;}
/* ArchivePage */
h2.Category-ArchivePage {background: $(keycolor)!important;display: inline-block;padding: 0;border-radius: $(TitleBorderRadius);}
h2.Category-ArchivePage a {color: $(grad.color);display: inline-block;padding: 5px 25px;font-size: 15px;}
ul.clear li {color: $(keycolor);}
ul.clear li a {font-weight: bold;color: #121212;font-size: 13px;}
.caregory-div:not(:first-of-type) {margin-top: 10px;padding-top: 10px;border-top: 1px solid #eee;}
/* contact US */
#contact-form{padding:20px;border:1px dashed #eee}
div#Pagecontactus{margin:10px 0}
#ContactForm1_contact-form-name,#ContactForm1_contact-form-email,#ContactForm1_contact-form-email-message{margin:5px auto;border:1px solid #d6d6d6;transition:all .5s ease-out;width:100%;border-radius:2px;padding:8px 15px;margin-bottom:10px;background:transparent;font:400 14px 'Segoe UI'}
input#ContactForm1_contact-form-name{margin-top:0}
#ContactForm1_contact-form-submit{background:#eee;cursor:pointer;font-weight:bold;float:$startSide;padding:8px 15px;color:#3c3c3c;margin:0 0;font-size:13px;border:1px solid #d4d4d4}
div#ContactForm1_contact-form-error-message img{vertical-align:middle;margin-$startSide:3px}
textarea#ContactForm1_contact-form-email-message{margin-bottom:5px}
#ContactForm1_contact-form-name:focus,#ContactForm1_contact-form-email:focus,#ContactForm1_contact-form-email-message:focus{outline:none;border-color:rgb(60,91,146);border-style:solid}
/* Post Headr */
div#AddOns{display:none;opacity:0;visibility:hidden}
.atags{display:block;margin:0 0 5px}
.atags a{font-size:13px;color:#000000;text-shadow:1px 1px rgb(0 0 0 / 18%);height:24px;line-height:24px;border-radius:3px;margin-$endSide:10px;display:inline-block}
img.post-thumbnail{display:block;width:100%;height:400px;object-fit:cover;border-radius:5px;margin-bottom:15px}
.atags a:before{content:"#";display:inline-block;color:$(keycolor);margin-$endSide:4px}
.atags .blog-admin a:before{display:none}
.atags a:last-of-type{margin-$endSide:0}
.atags a:hover{text-decoration:underline}
.atags .blog-admin a:hover{background:#ccc}
.atags .blog-admin{float:$endSide;vertical-align:top;overflow:hidden;margin-top:0!important}
.blog-admin{display:none}
.atags .blog-admin a{line-height:initial;margin:0;padding:0;width:30px;display:flex;align-items:center;justify-content:center;border-radius:3px}
.atags .blog-admin a svg{width: 16px;}
.post-amp .entry-title.topic-title{padding-$startSide:5px;border-$startSide:3px solid $(keycolor);overflow:hidden;font:$(PostsTitleFont);line-height:1.7em;color:$(PostsTitleColor)}
.post-meta{margin-top:10px;color:$(PostsMetaColor);font-size:13px}
.headbost,span.p-author.h-card.vcard,.article-timeago,.article-author,a.timestamp-link{display:inline-block;vertical-align:middle}
body.ltr .article-timeago {margin-left: 2px;}
body.ltr .article-timeago svg.small-icon {margin-$startSide: 1px;}
.headbost svg{width:14px!important;height:14px!important;margin-$endSide:3px;vertical-align:middle}
.post-meta span,.post-meta .post-date{font-size:13px}
.post-meta a{color:$(PostsMetaColor)}
.commint-cont{display:inline-block;vertical-align:middle;color:$(PostsMetaColor);font-size:13px;float:$endSide}
.commint-cont svg{width:14px;height:14px;display:inline-block;vertical-align:middle;margin-$endSide:4px;margin-top:-1px}
/* Post lightbox */
.lightbox{z-index:99999999999;width:100%;height:100%;position:fixed;background-color:rgba(0,0,0,0.5);visibility:hidden;opacity:0;transition:0.2s;top:0;$startSide:0;$endSide:0;bottom:0;display:flex;justify-content:center;align-items:center;flex-direction:column}
.lightbox.active{visibility:visible;opacity:1}
div#lightbox img {max-width: 90%;max-height: 90%;display: inline;}
div#lightbox span:before{position:absolute;$startSide:30px;top:30px;content:"x";color:#fff;font-size:28px;font-family:inherit!important;border:1px solid #eee;width:30px;height:30px;display:flex;line-height:0;align-items:center;justify-content:center;border-radius:2px;cursor:pointer}
div#lightbox span:hover:before {color: #000;background: #fff;}
/* Post Footer */
.hideensa {overflow: hidden;display: block;clear: both;}
/* Post Tags */
.amp-tags{font-size:13px;font-weight:bold}
.amp-tags a{color:$(poststagscolor);font-size:13px;margin:0 0 0 5px;font-weight:normal;padding:5px 10px;background:$(poststagsbg);border-radius:2px;transition:all 0s;display:inline-block}
.amp-tags svg {width: 11px;height: 11px;margin-$endSide: 4px;vertical-align: middle;transition: all 0s;}
body.ltr .amp-tags a {
    margin: 0 5px 0 0;
}
.amp-tags a:hover{background:$(poststagshoverbg);color:$(poststagshovercolor);}
/* topic-nav */
.texxattt{display:inline-block;color:#ffffff;font-size:10px;background:$(keycolor);padding:2px 5px;border-radius:2px;margin-bottom:3px}
.posttitle{font-size:14px;color:$(PostsTextColor) !important;width:100%;display:block;white-space:nowrap;text-overflow:ellipsis;overflow:hidden}
.newPost,.oldPost{padding-$endSide: 10px;float:$startSide;width:50%;padding-$startSide:10px;border-$startSide:3px solid $(keycolor)}
.topic-nav-cont{overflow:hidden}
.post-random a.reimage{width:90px;height:70px;float:$startSide;display:block;margin-$endSide:15px;border-radius:5px;overflow:hidden}
.post-random a.reimage img{width:110px;height:90px;object-fit:cover}
.post-random .posle{float:$startSide;width:calc(100% - 125px)}
.post-random .newPost{display:block;float:$startSide;width:50%;padding:0 15px}
div#RandomPosts{display: none;font-weight:normal!important}
a.posttiaaatle{font-size:14px!important;display:block;line-height:1.5em;max-height:40px;overflow:hidden;color:#444444;text-decoration:none!important}
.posle a{font-size:13px;color:#333;text-decoration:underline}
.posle a:hover{text-decoration:underline}
.post-random{position:relative;margin:15px 0;padding:20px 0 20px;border:0;border-$endSide:0;border-$startSide:0;overflow:hidden}
.retatit{display:block;margin-bottom:15px;font-size:14px;color:#222}
.post-random:before,.post-random:after{top:0;content:'';position:absolute;width:100%;margin:0 auto;height:1px;display:block;background:linear-gradient(to $endSide,rgb(247,249,248),#DFE2E3,rgb(247,249,248))}
.post-random:after{top:initial;bottom:0}
/* SeoPlusAds */
div#Topa3lan-sc .HTML,div#Topa3lan-sc2 .HTML{box-shadow:none;background:transparent!important;padding:0!important;border:0;margin:0}
div#PostAds .widget{background:transparent!important;border:0!important;padding:0 20px!important;margin:0!important;box-shadow:none!important}
.SeoPlusAds,.post-outer .HTML{background:transparent!important;margin:15px 0;text-align:center;font-size:13px;display:block;clear:both;border:none;overflow:unset!important;box-shadow:none;padding:0!important;border-radius:0}
div#HTML100 .SeoPlusAds{margin-top:0}
div#top-a3lan .HTML{margin-top:0}
div#bot-a3lan .HTML{margin-bottom:0}
.pnavigation .HTML {
    margin-bottom: 15px !important;
}
div#bot-a3lan,div#top-a3lan,div#ret-a3lan{overflow:initial}

/* comments */
.mopspeed #comments {display: none;}
.mopspeed a#opencmt{display:block;overflow:hidden;margin-top:15px;padding:10px;background:#eee;font-weight:bold;font-size:13px;color:#000;text-align:center;border-radius:2px}
li.comment{padding:10px 5px 0;margin:10px 0;border:1px solid $(BordersCommints);box-shadow:none!important;display:block;border-$startSide:0;border-$endSide:0;border-bottom:0}
.avatar-image-container{position:absolute;width:45px;height:45px;border-radius:50%;text-align:center;margin-top:0;margin-$startSide:5px}
.avatar-image-container img{border-radius:100%;height:40px;width:40px;background:transparent url(https://4.bp.blogspot.com/-ci3XMoAMGzg/WiCTxCLLWeI/AAAAAAAAPjI/UkV1sBTKC7EamOC_UmMJ4cQCv4xNNI82QCLcBGAs/s1600/log.jpg) no-repeat center;background-size:40px;overflow:hidden}
.comment-header{display:inline-block;overflow:hidden;clear:both;margin-$startSide:60px}
span.datetime,cite.user{display:block;overflow:hidden;clear:both;font-size:13px;float:$startSide}
span.datetime a,cite.user a{color:#666!important;font-weight:normal!important}
.comment-content{padding:10px 15px 13px;font-size:13px;cursor:text;font-weight:100;color:$(PostsTextColor);overflow:hidden;border-top:1px dashed $(BordersCommints)}
.comment-actions.secondary-text a{padding:0 20px 1px;margin:5px 0;background:$(labels.background.color);border:1px solid $(labels.background.border);border-$startSide: 0;font-size:13px}
span.datetime a,cite.user a{font-size:13px}
.comment-reply{border-radius:0 0;border-$endSide:0!important}
.datetime.secondary-text a,.comment-actions.secondary-text a{color:$(PostsTextColor)}
.comments span.item-control a{border-radius:0 0 0 0!important}
.comment-reply {border: 1px solid $(labels.background.border) !important;}
.comment-replies{margin-top:10px!important;margin-bottom:0!important;padding-$startSide:40px}
.comments .comments-content .inline-thread{padding:0!important}
span.thread-toggle.thread-expanded,.comment-replies .comment-replies,.thread-count,.continue,.loadmore.loaded,.hidden{display:none}
.comment-thread ol{padding:0}
.comment-replies li.comment:first-of-type{margin-top:20px!important}
.comment-replies li.comment{border:0;padding-bottom:2px;box-shadow:none;padding:0;margin-top:25px!important}
.comment-replybox-single{padding-$startSide:40px;display:block;clear:both;overflow:hidden}
.comment-replies span.item-control a {border-radius: 3px!important;border: 1px solid $(labels.background.border);}
.comment-form{min-height: 205px;padding:20px;border:1px dashed $(BordersCommints)}
#comments .comments-info{margin-bottom:15px;overflow:hidden;font-size:12px}
#comments .comments-info .comments-count{float:$startSide;padding:5px 0;font-size:14px;position:relative;color:$(posts.title.color)}
#comments .comments-info .go-respond b{float:$startSide;padding:5px 15px;margin:0 25px;background-color:$(labels.background.color);color:$(PostsTextColor);position:relative;overflow:hidden;font-size:13px}
#comments .small-icon{color:$(keycolor);width:20px;height:20px;display:inline-block;vertical-align:middle;margin-top:4px}
.comments-info svg.small-icon{width:15px!important;margin-$endSide:5px!important;margin-top:0!important}
a#commnetLinkS{font-size:13px;cursor:pointer;font-weight:bold;color:$(PostsLinkColor)}
h4#comment-post-message{display:inline-block;vertical-align:middle;font-size:14px;margin-$startSide:5px;color:$(posts.title.color)}
.conart p{display:block;overflow:hidden;font-size:13px;margin-top:5px;color:$(PostsTextColor)}
iframe#comment-editor{border-top:1px dashed $(BordersCommints);border-bottom:1px dashed $(BordersCommints);margin-top:20px;box-sizing:content-box}
.comment-replybox-thread #comment-editor{display:none!important}
/* author profile */
.Blog .author-posts{display:flex;align-items:center;margin:30px 17px;padding:0px;line-height:2em;border-radius:20px;background-color:transparent;font-size:13px;}
.Blog .author-posts .authorImage{flex-shrink:0;margin-$endSide:25px}
.Blog .author-posts .authorImage div{position:relative;width:72px;padding-top:100%;background-color:#f2f2f2;border-radius:20px;overflow:hidden}
.Blog .author-posts .authorInfo{flex-grow:1;}
.Blog .author-posts .author-name{font-size:14px}
.Blog .author-posts .author-desc{color:#767676}
.Blog .author-posts .author-link{list-style:none;margin:10px 0 0;padding:0;display:flex;}
.Blog .author-posts .author-link a{display:block;margin-$endSide:10px;padding:3px 10px;color:#767676;background-color:#f2f2f2;border-radius:3px;font-size:11px}
.Blog .author-posts .author-link a:hover{background-color:#e5e3e3;text-decoration:underline}
.Blog .author-posts .authorImage img{display:block;position:absolute;top:50%;left:50%;max-width:initial;height:100%;-webkit-transform:translate(-50%,-50%);transform:translate(-50%,-50%)}
/* reactions */
.reactions-label{display:inline-block;vertical-align:top;color:$(PostsTextColor);font-size:14px}
iframe.reactions-iframe{height:20px;display:inline-block;vertical-align:sub}
#FancyAllItems *{-moz-transition:none;-webkit-transition:none;transition:none}
/* PageRedirect */
div#pageredirect{position:relative}
.cLoaderWrap{text-align:center;width:260px;margin:0 auto;position:relative;font-style:normal;display:block}
#cLoaderSVG{-webkit-transform:rotate(140deg);transform:rotate(140deg);width:260px;height:260px;display:block}
.cPath{stroke-dashoffset:0;stroke-dasharray:500;r:110;cy:130;cx:130;stroke-width:20px;stroke:#f6f6f6;fill:none}
.cLoader{stroke-dashoffset:500;stroke-dasharray:500;-webkit-transition:all 1s linear;transition:all 1s linear;r:110;cy:130;cx:130;fill:none;stroke-width:20px;stroke:$(keycolor)}
.hLoader{stroke-dashoffset:500;stroke-dasharray:500;-webkit-transition:all 1s linear;transition:all 1s linear;r:110;cy:130;cx:130;fill:none;stroke-width:22px;stroke:#ffffff}
.cCount{position:absolute;top:90px;$startSide:calc(50% - 30px);font-size:60px;width:66px;font-family:Arial!important;display:block;margin-bottom:0;color:#444;text-align:center}
.cButton{text-align:center}
a.cLink{position:absolute;bottom:20px;$startSide:0;user-select:none;$endSide:0;z-index:8;border-style:solid;border-width:5px;border-color:rgba(0,0,0,0.03);display:inline-block;background-color:#f8f8f8;padding:5px 15px;width:160px;font-size:14px;margin:0 auto;border-radius:50px;color:#d2d2d2!important;cursor:progress}
a.cLink.ready:hover{border-color:$(keycolor);background:$(keycolor);color:#fff!important}
a.cLink.ready{cursor:pointer;color:#3c5b92!important;border-color:$(keycolor);border-style:double;transition:all 0.3s}
a.cLink.err{cursor:no-drop;background-color:#ffcfcf;color:#de6262!important}
/* ReadPage-popup */
div#ReadPage{z-index:999999999999;position:fixed;width:100vw;$startSide:0;top:0;height:100vh;display:none}
.modal-body .cCount{top:90px}
.ReadPage-popup{background-color:rgba(0,0,0,0.8);width:100%;height:100%;position:fixed;overflow-y:auto}
.ReadPage-popup-cont{width:80%;position:relative;direction:unset;border-radius:2px;margin:30px auto;max-width:900px;-webkit-box-shadow:0 0 100px #000;box-shadow:0 0 100px #000}
span.modal-close{background-color:$(keycolor);width:40px;height:40px;text-align:center;color:#FFF;cursor:pointer;position:absolute;$endSide:-20px;top:-20px;border-radius:3px;display:flex;align-items:center;justify-content:center}
span.modal-close svg{width:18px;height:18px}
.modal-body{background-color:#ffffff!important;min-height:calc(100vh - 110px);overflow:hidden!important;padding:30px!important;border-radius:0!important;box-shadow:none!important;margin:0!important}
.redirectSkin, .PagePrakediv{display:block;margin:10px auto;text-align:center}
div#pageredirect{position:relative;line-height:initial!important}
div#pageredirect {display: block;overflow: hidden;clear: both;margin: 15px 0;}
.redirectSkin a, .PagePrakediv a{padding:7px 25px;background:$(keycolor);color:#fff!important;font-size:15px;border-radius:3px;display:inline-block;line-height:1.6em;position:relative;transition:all 0.3s;top:0}
.ReadPage-popup-cont .icon-load{position:unset;width:50px;height:50px;display:block}
.modal-title .icon-load{width:25px;height:25px}
.ay7aga { display: flex; align-items: center; justify-content: center; height: 80vh; }
.redirectSkin a:hover , .PagePrakediv a:hover{top: -1px;box-shadow: 0 6px 11px 0 rgb(0 0 0 / 42%);}
/* footer */
footer .headline{background:transparent;border-bottom:1px solid #eee}
footer .headline:before{display:none}
footer .headline .title{background:transparent !important;color:#000;padding:0 3px 7px;border-bottom:1px solid #eee;border-$endSide:transparent;font-size:15px;border-radius:0!important}
footer .headline .title:before{display:none}
footer{overflow:hidden;display:block;clear:both;background:#fff;padding:15px 0 0;border-top:1px solid #eee}
footer .container{display:block;overflow:hidden}
.mid-top-footer .footer-col .widget{margin-bottom:30px;vertical-align:top}
.mid-top-footer .footer-col .widget:last-of-type{margin-bottom:15px}
.mid-top-footer .footer-col{float:$startSide;width:calc((100% - 60px) / 3);margin-$endSide:30px}
div#footer-col3{margin-$endSide:0;padding-$endSide:0;border-$endSide:0}
.bottom-footer{display:block;overflow:hidden;clear:both;padding:10px 0;box-shadow:0 -1px 25px -16px #000;margin-top:0;background:$(rgb(91 91 91 / 28%))}
.yemen{min-height:32px;font-size:13px;float:$startSide;display:flex;align-items:center;color:#000}
.yemen a{font-size:13px;font-weight:bold;color:$(keycolor);letter-spacing:0;vertical-align:middle}
.yemen span{font-size:13px;vertical-align:middle;margin-$endSide:3px}
.shmal{float:$endSide;font-size:13px;margin-top:5px}
svg.svg-inline--fa.fa-exclamation-triangle.fa-w-18{width:200px;margin:0 auto 0;display:block;height:200px;color:$(keycolor)}
/* buttonsupandlh */
svg.s3ood{fill:none;stroke:#ffffff;stroke-linecap:round;stroke-linejoin:round;stroke-width:1.5;display:block;border-top:1px solid #fff;width:40px;height:40px;margin:0 -10px;padding:10px}
svg.s3ood .svg-c{fill:none;stroke:#ffffff}
.buttonsupandlh{position:fixed;background:$(keycolor);z-index:9;$startSide:30px;bottom:30px;width:40px;border-radius:5px;padding:0 10px;cursor:pointer}
.darMode svg{stroke:#fff!important;display:block;clear:both;overflow:hidden;width:40px;height:40px;margin:0 -10px;padding:10px}
.darMode svg.line.svg-2{display:none}
body.dark-mode svg.line.svg-2{display:block}
body.dark-mode svg.line.svg-1{display:none}
body.ltr .yemen a[title="SeoPlus Template"]{margin-right:5px}
body.rtl .yemen a[title="SeoPlus Template"]{margin-left:5px}
/* post-share */
.Blog article.post .post-share{position:relative;display:flex;flex-wrap:wrap;font-size:13px;line-height:22px;}
.Blog article.post .post-share:before{display:none;content:attr(data-share);width:100%;margin-bottom:20px;font-size:14px}
.Blog article.post .post-share .share-icon{flex-grow:1}
.Blog article.post .post-share .share-icon:not(:first-child){margin-$startSide:10px}
.Blog article.post .post-share .share-icon > *{    cursor: pointer;display:flex;align-items:center;padding:10px;border-radius:3px;background-color:#f2f2f2;color:inherit}
.Blog article.post .post-share .share-icon > a{padding:9px 15px;color:#fefefe}
.Blog article.post .post-share .share-icon > a svg{fill:#fefefe}
.Blog article.post .post-share .share-icon svg{width:20px;fill:#767676}
.Blog article.post .post-share .facebookThis a{background-color:#3059b0}
.Blog article.post .post-share .facebookThis a:after{content:'شارك علي الفيسبوك';margin-$startSide:15px}
.Blog article.post .post-share .twitterThis a{background-color:#55acef}
.Blog article.post .post-share .twitterThis a:after{content:'شارك علي تويتر';margin-$startSide:15px}
.Blog article.post .post-share .whatsappThis a{background-color:#25D366}
.Blog article.post .post-share .whatsappThis a:after{content:'شارك علي الواتساب';margin-$startSide:15px}
.Blog article.post .post-share .shareThis{flex-grow:0}
.Blog article.post .post-share .share-popup{position:fixed;top:0;$startSide:0;width:100%;height:100%;display:flex;align-items:center;z-index:50;-webkit-transition:all .2s ease;transition:all .2s ease;opacity:0;visibility:hidden}
body.ltr .Blog article.post .post-share .facebookThis a:after {content: 'Share on Facebook' !important;}
body.ltr .Blog article.post .post-share .twitterThis a:after {content: 'Share on Twitter' !important;}
body.ltr .Blog article.post .post-share .whatsappThis a:after {content: 'Share on Whatsapp' !important;}
.Blog article.post .post-share .share-notif{display:flex;position:fixed;$startSide:0;$endSide:0;bottom:25px}
.Blog article.post .post-share .share-notif span{position:relative;bottom:-200px;display:block;width:240px;margin:0 auto;padding:10px;border-radius:3px;background-color:#505050;color:#fefefe;line-height:22px;text-align:center;opacity:0;transition:all .3s ease-in-out;-webkit-transition:all .3s ease-in-out;-webkit-animation:slidein 2s ease forwards;animation:slidein 2s ease forwards;}
.Blog article.post .post-share .share-check:checked + .share-popup{opacity:1;visibility:visible}
.Blog article.post .post-share .share-check:checked + .share-popup ul{margin:0 auto}
.Blog article.post .post-share .share-check:checked + .share-popup .full-close{background:rgba(0,0,0,.25);opacity:1;visibility:visible}
.Blog article.post .post-share ul{position:relative;display:flex;flex-wrap:wrap;width:95%;max-width:500px;list-style:none;margin:0 auto -50%;padding:20px 20px 15px;background-color:#fefefe;border-radius:20px;z-index:3;-webkit-transition:all .2s ease;transition:all .2s ease}
.Blog article.post .post-share ul:before{content:"مشاركة المقال عبر";display:block;width:100%;margin:0 0 15px;font-size:14px;text-align:center}
body.ltr .Blog article.post .post-share ul:before {content: "Share the article via" !important;}
.Blog article.post .post-share li{position:relative;width:calc(25% - 15px);margin-$endSide:20px}
.Blog article.post .post-share li:nth-of-type(4n){margin-$endSide:0}
.Blog article.post .post-share li > *{display:block;margin:8px 0;text-align:center;color:inherit;cursor:pointer}
.Blog article.post .post-share li > * span{display:block;margin:5px 0 0;font-size:12px}
.Blog article.post .post-share li > * svg{width:44px;height:44px;fill:#767676;padding:12px;background-color:#f2f2f2;border-radius:12px}
.Blog article.post .post-share li > * svg.line{fill:none;stroke:#767676;padding:11px}
.Blog article.post .post-share li input{margin:0;padding:0;outline:0;border:0;width:1px;height:0;opacity:0}
.Blog article.post .post-share li.share-close{position:initial;width:100%;margin:0;}
.Blog article.post .post-share li.share-close > .close-1{visibility:hidden;margin-top:0}
.Blog article.post .post-share li.share-close > .close-2{position:absolute;top:15px;$endSide:15px;margin-top:0}
.Blog article.post .post-share li.share-close > *{max-width:22px;margin:10px auto 0;}
.Blog article.post .post-share li.share-close > * svg{display:block;width:22px;height:22px;padding:0;background:transparent!important}
.full-close{display:block;position:fixed;top:0;$endSide:0;width:100%;height:100%;z-index:2;-webkit-transition:all .2s ease-in;transition:all .2s ease-in;background:transparent;opacity:0;visibility:hidden}
.Blog article.post .post-share li:hover > * svg{background-color:#e7e7e7}
@keyframes slidein{0%{opacity:0}20%{opacity:1;bottom:0}50%{opacity:1;bottom:0}80%{opacity:1;bottom:0}100%{opacity:0;bottom:-200px}}
.post-body iframe{display:block;margin:auto;max-width:100%}
/*=================
dark-mode
===================*/
body.dark-mode{background-color:#202442}
body.dark-mode .PLHolder.thumb:before,body.dark-mode .PLHolder.thumb:after{background:#282d54!important;animation:none!important}
body.dark-mode .bobxed,body.dark-mode .topcs7v,body.dark-mode .topic-nav,body.dark-mode .Blog article.post .post-share,body.dark-mode .reaction-buttons,body.dark-mode section#comments,body.dark-mode .amp-tags,body.dark-mode .shareButton,body.dark-mode .RelatedPosts,body.dark-mode .author-posts,body.dark-mode .post-body,body.dark-mode .page-navigation,body.dark-mode.mopspeed a#opencmt,body.dark-mode .site .widget,body.dark-mode a.Lapel-Link:after{background:#2d325a!important}
body.dark-mode .headline:before{background:#282d54}
body.dark-mode .headline .title:before{background:#2d325a}
body.dark-mode .Blog .author-posts .authorImage div{background:#2d325a}
body.dark-mode .amp-tags a{background:#242950;color:#fff}
body.dark-mode .head-pz{background:#2d325a}
body.dark-mode nav.nav-par ul li a{color:#fff}
body.dark-mode li.item > ul li.sitem a{color:#fff;border-bottom:1px solid #282d54;background:#2d325a}
body.dark-mode li.item > ul,body.dark-mode  li.sitem > ul,body.dark-mode li.item > ul:before,body.dark-mode li.sitem > ul:before{border:1px solid #282d54;background:#2d325a}
body.dark-mode li.item > ul li.sitem a:before{background:#2d325a;border:1px solid #494f7f}
body.dark-mode li.item.targetitem span.icon{color:#3a7bd5}
body.dark-mode nav.nav-par ul li a:hover{color:#3a7bd5}
body.dark-mode .targetitem li a:hover:before{background:#3a7bd5!important}
body.dark-mode .post-outer .items,body.dark-mode .Sp-Normal .posts .items{border-top:1px solid #282d54;border-bottom:1px solid #282d54}
body.dark-mode.post .post-outer .items,body.dark-mode.post .post-outer{border-top:0;border-bottom:0}
body.dark-mode #siki_next, body.dark-mode #siki_prev {border-color: #242950;}
body.dark-mode .conart p { color: #fff; }
body.dark-mode .post-outer,body.dark-mode .Sp-Normal .posts{border-bottom:1px solid #282d54}
body.dark-mode .Sp-posts0 .rnav-title a:hover,body.dark-mode .Sp-posts1 .rnav-title a:hover,body.dark-mode .Sp-posts3 .rnav-title a:hover,body.dark-mode .Sp-posts4 .rnav-title a:hover,body.dark-mode .Sp-posts6 .rnav-title a:hover,body.dark-mode .Sp-posts5 .rnav-title a:hover,body.dark-mode .Sp-Normal .rnav-title a:hover,body.dark-mode .Sp-slide .rnav-title a:hover,body.dark-mode .Sp-3colList .rnav-title a:hover,body.dark-mode .PopularPosts h3.post-title a:hover,body.dark-mode .widget.FeaturedPost .post-title a:hover,body.dark-mode .items a:hover,body.dark-mode .posttitle:hover,body.dark-mode ul.clear li a:hover,body.dark-mode .post-outer .posts-titles a:hover{color:#3a7bd5!important}
body.dark-mode .post-outer .posts-titles a,body.dark-mode .Sp-Normal .posts .rnav-title a{color:#fff}
body.dark-mode #siki-page-number { color: #fff; }
body.dark-mode .post-outer .Short_content,body.dark-mode .Sp-Normal .posts .Short_content,body.dark-mode .post-outer .items,body.dark-mode .Sp-Normal .posts .items,body.dark-mode .post-outer .items a,body.dark-mode .post-outer .items span,body.dark-mode .Sp-Normal .posts .items a,body.dark-mode .Sp-Normal .posts .items span,body.dark-mode .Sp-posts4 .posts.postnum0 .items a,body.dark-mode .Sp-posts4 .posts.postnum0 .items span,body.dark-mode .Sp-posts6 .posts .items a,body.dark-mode .Sp-posts6 .posts .items span{color:#989b9f}
body.dark-mode .post-outer .moreLink,body.dark-mode .Sp-Normal .posts .moreLink{background:#242950}
body.dark-mode .widget.Label .cloud-label-widget-content span.label-size a.label-name{color:#ffffff;border:1px solid #282d54;background:#242950}
body.dark-mode .headline .title,body.dark-mode .Followers h2.title,body.dark-mode a.Lapel-Link,body.dark-mode .open.nav1,body.dark-mode .search,body.dark-mode .sp-header.Style3 .par-tp,body.dark-mode div#blog-pager a#Blog1_blog-pager-newer-link,body.dark-mode div#blog-pager a#Blog1_blog-pager-older-link,body.dark-mode div#blog-pager .homelink a{background:#242950}
body.dark-mode .sp-header.Style3 div#pages a:hover,body.dark-mode .sp-header.Style3 div#pages li.selected a{background:#fff;color:#242950}
body.dark-mode .post-amp .entry-title.topic-title{border-$startSide:3px solid #242950;color:#ffffff}
body.dark-mode .post-meta,body.dark-mode .post-meta a{color:#989b9f}
body.dark-mode .atags .blog-admin a:hover{background:#202442}
body.dark-mode .atags a{color:#fff}
body.dark-mode .atags a:before{color:#3a7bd5}
body.dark-mode.post div#Blog1{background:transparent!important}
body.dark-mode .post-body,body.dark-mode h3.rnav-title a{color:#fff}
body.dark-mode .Blog .author-posts .author-desc{color:#989b9f}
body.dark-mode .Blog .author-posts .author-name{color:#fff}
body.dark-mode .Blog article.post .post-share .share-icon svg{fill:#ffffff}
body.dark-mode .toctitle{border-bottom:1px solid #242950;color:#fff}
body.dark-mode .closetoc:before{background:#242950;color:#fff}
body.dark-mode .toctitle:before{color:#3a7bd5}
body.dark-mode ul#tocList li a{border-bottom:1px solid #202442;background:#242950;color:#b5b8bd}
body.dark-mode ul#tocList li a:hover{border-bottom:1px solid #242950;background:#202442;color:#fff}
body.dark-mode .Blog article.post .post-share .share-icon > *{background-color:#242950}
body.dark-mode .Blog article.post .post-share ul{background-color:#242950;color:#fff}
body.dark-mode .Blog article.post .post-share li > * svg{background-color:#2d325a;fill:#fff}
body.dark-mode .Blog article.post .post-share li > * svg.line{fill:none!important;stroke:#fff}
body.dark-mode.mopspeed a#opencmt{color:#fff}
body.dark-mode .Sp-posts4 .posts.postnum0 .cont,body.dark-mode .Sp-posts6 .posts .cont{background:#242950!important}
body.dark-mode .Sp-posts4 .posts,body.dark-mode .Sp-posts6 .posts{border-bottom:1px solid #282d54}
body.dark-mode svg.icon-load{color:#242950}
body.dark-mode .ay7aga svg.icon-load{color:#fff}
body.dark-mode .noMorePosts,body.dark-mode div#loader,body.dark-mode .loadMore .loadMorePosts a,body.dark-mode #shreeta5bar .headline .title{background:#242950}
body.dark-mode .Sp-shreet h3.rnav-title a:before{filter:brightness(20)}
body.dark-mode .sidenav{background-color:#2d325a}
body.dark-mode div#mop-links div#menu{background:#242950}
body.dark-mode .mop-links ul li a{background:#2d325a;border-bottom:1px solid #242950;color:#fff!important}
body.dark-mode div#mop-links li.item span.icon{background:#242950;border:1px solid #242950;color:#fff}
body.dark-mode .mop-pages ul li a,body.dark-mode .mop-links ul li a{color:#ffffff!important;border-bottom:1px solid #242950}
body.dark-mode .mop-pages ul li{color:#fff}
body.dark-mode .closebtn{color:#ffffff}
body.dark-mode .buttonsupandlh{background:#2d325a}
body.dark-mode .buttonsupandlh svg.s3ood{border-top:1px solid #242950}
body.dark-mode .newPost,body.dark-mode .oldPost{border-$startSide:3px solid #242950;color:#fff}
body.dark-mode .texxattt{background:#242950}
body.dark-mode span.posttitle{color:#ffffff!important}
body.dark-mode .reactions-label{color:#fff}
body.dark-mode #comments .small-icon{color:#3a7bd5}
body.dark-mode #comment-post-message{color:#fff}
body.dark-mode iframe#comment-editor{border-top:1px dashed #202442;border-bottom:1px dashed #202442}
body.dark-mode .comment-form{border:1px dashed #202442}
body.dark-mode #comments .comments-info .comments-count{color:#fff}
body.dark-mode #comments .comments-info .go-respond b{background-color:#242950;color:#ffff}
body.dark-mode li.comment{border:1px solid #242950;border-$startSide:0;border-$endSide:0;border-bottom:0}
body.dark-mode span.datetime a,body.dark-mode cite.user a,cite.user{color:#989b9f!important}
body.dark-mode .comment-content{color:#fff;border-top:1px solid #242950}
body.dark-mode a#commnetLinkS{color:#3a7bd5}
body.dark-mode .comment-reply,body.dark-mode .comment-actions.secondary-text a{background:#2d325a;border-color:#242950!important;color:#bfbfbf}
body.dark-mode .comment-reply:hover,body.dark-mode .comment-actions.secondary-text a:hover{color:#fff}
body.dark-mode footer{background:#2d325a;border-top:1px solid #242950}
body.dark-mode .bottom-footer{background:#242950}
body.dark-mode .yemen{color:#fff}
body.dark-mode .yemen a{color:#3a7bd5}
body.dark-mode .navigation-mobile{background-color:#242950}
body.dark-mode .navigation-mobile svg{fill:#fff}
body.dark-mode .navigation-mobile svg.line{stroke:#ffffff;fill:none}
body.dark-mode .navigation-mobile .top-link svg.line{stroke:#ffffff}
body.dark-mode .post-body h1,body.dark-mode .post-body h2,body.dark-mode .post-body h3,body.dark-mode .post-body h4{background:#242950!important;border-bottom:1px solid #202442!important;color:#ffffff!important}
body.dark-mode .Sp-posts1 .Short_content,body.dark-mode .Sp-posts1 .items a{color:#989b9f!important}
body.dark-mode .Sp-posts1 .items{border-color:#282d54}
body.dark-mode .Sp-posts3 .posts{border-color:#282d54}
body.dark-mode .Sp-posts3 .items a{color:#989b9f}
body.dark-mode .Sp-slide .posts:not(.postnum0) .rnav-title a{color:#fff}
body.dark-mode .Sp-slide .posts.postnum0 .cont{background:#2d325a!important}
body.dark-mode .Sp-slide .items a,body.dark-mode .Sp-slide .items span{color:#989b9f}
body.dark-mode .Sp-3colList .items a,body.dark-mode .Sp-posts5 .posts:not(.postnum0) .items a,body.dark-mode .Sp-posts5 .posts.postnum0 .Short_content,body.dark-mode .Sp-posts5 .items a,body.dark-mode .Sp-posts5 .items span{color:#989b9f}
body.dark-mode .Sp-3colList .posts,body.dark-mode .Sp-posts5 .posts,body.dark-mode .Sp-posts5 .posts.postnum0 .items,body.dark-mode .Sp-posts5 .posts.postnum0{border-color:#282d54}
body.dark-mode .Sp-posts5 .posts.postnum0 h3.rnav-title a{color:#fff}
body.dark-mode .SeoPlusAds,body.dark-mode .post-outer .HTML{background:transparent!important}
body.dark-mode .post-body a{color:#4794ff}
body.dark-mode .redirectSkin a{background:#202442}
body.dark-mode .floar:before{background:#242950}
body.dark-mode .cPath{stroke:#292e53}
body.dark-mode .cLoader{stroke:#202442}
body.dark-mode .hLoader{stroke:#2d325a}
body.dark-mode .cCount{color:#fff}
body.dark-mode a.cLink{background-color:#242950;color:#d7d7d7!important}
body.dark-mode a.cLink.err{background-color:#d63031;color:#ffffff!important}
body.dark-mode a.cLink.ready{color:#ffffff!important;background-color:$(keycolor)}
body.dark-mode .retatit{color:#fff}
body.dark-mode a.posttiaaatle{color:#fff!important}
body.dark-mode .posle a{color:#d7d7d7!important}
body.dark-mode .Followers h2.title:before{display:none}
body.dark-mode .widget .list-label-widget-content ul li{color:#fff!important;border-bottom:1px dashed #242950!important}
body.dark-mode .widget .list-label-widget-content ul li a{color:#fff}
body.dark-mode span.label-count{color:#fff}
body.dark-mode input.search-action{color:#fff;background:transparent!important}
body.dark-mode .BlogSearch input{background:#fff}
body.dark-mode aside .LinkList ul li a,body.dark-mode footer .LinkList ul li a,body.dark-mode aside .PageList ul li a,body.dark-mode footer .PageList ul li a{color:#fff}
body.dark-mode aside .LinkList ul li,body.dark-mode footer .LinkList ul li,body.dark-mode aside .PageList ul li,body.dark-mode footer .PageList ul li{color:#fff;border-bottom:1px solid #242950}
body.dark-mode .PopularPosts article.post{border-bottom:1px solid #242950}
body.dark-mode .widget.FeaturedPost .post-title a,body.dark-mode .PopularPosts h3.post-title a{color:#fff}
body.dark-mode input.follow-by-email-submit{background:transparent;border:1px solid #fff;color:#fff}
body.dark-mode .widget.FeaturedPost p.snippet-item.r-snippetized,body.dark-mode footer .widget.FeaturedPost p.snippet-item.r-snippetized{color:#989b9f}
body.dark-mode .no3nwen{color:#fff}
body.dark-mode footer .headline .title{color:#fff;border-bottom:1px solid #202442}
body.dark-mode #contact-form{border:1px dashed #242950}
body.dark-mode #ContactForm1_contact-form-name,body.dark-mode #ContactForm1_contact-form-email,body.dark-mode #ContactForm1_contact-form-email-message{border:1px solid #242950;color:#fff}
body.dark-mode #ContactForm1_contact-form-name::placeholder,body.dark-mode #ContactForm1_contact-form-email::placeholder,body.dark-mode #ContactForm1_contact-form-email-message::placeholder{color:#fff}
body.dark-mode #ContactForm1_contact-form-submit{background:#202442;color:#ffffff;border:1px solid #242950}
body.dark-mode h2.Category-ArchivePage a{color:#ffffff!important}
body.dark-mode ul.clear li a{color:#fff!important}
body.dark-mode ul.clear li{color:#fff}
body.dark-mode .titlewrapper .title,body.dark-mode .titlewrapper a{color:#fff}
body.dark-mode .Blog .author-posts .author-link a{color:#fff;background-color:#242950}
body.dark-mode .post-random:before,body.dark-mode .post-random:after{background:linear-gradient(to $endSide,rgb(45 50 90),#242950,rgb(45 50 90))}
body.dark-mode .post-body blockquote{color:#ffffff;background-color:#242950;border:1px solid #202442}
body.dark-mode img[alt="SeoPlus Template"]{filter:brightness(20)}
body.dark-mode .post-body blockquote:before,body.dark-mode .post-body blockquote:after{filter:brightness(20)}
body.dark-mode .post-body ol li:before{background:#242950;border:1px solid #202442;color:#ffffff}
body.dark-mode .titlewrapper a{color:#3a7bd5}
.contenarpage {overflow: hidden;}
div#mop-links li.item span.icon:hover {background: $(keycolor);color: #fff;}
div#mop-links li.item span.icon, div#mop-links li.item span.icon * {transition: none !important;}
/*=================
responsev
===================*/
@media screen and (max-width:1100px){
div#top-social-L{margin-$endSide:0}
.floar{width:75%}
.Sp-posts4 .posts:nth-of-type(1) .cont,.Sp-posts6 .posts .cont{margin:-80px 5% 0;width:90%}
.post-home,.Sp-Normal .cont{text-align: $startSide;width:calc((100% - 295px) / 1)!important}
.post-outer .thumb,.Sp-Normal .thumb,.Sp-Norma0 .thumb{width:280px!important}
.Sp-posts1 .posts, .Sp-posts0 .posts{width:calc((100% - 30px) / 3);margin-$endSide:15px;margin-$startSide:0!important;margin-bottom:15px}
.Sp-posts1 .items a,.Sp-posts1 .items span,.Sp-posts0 .items span{margin-$endSide:0}
}
@media screen and (max-width:992px){
.sp-header.Style3 .par-bottm nav.nav-par,.sp-header.Style3 div#pages,.sp-header.Style3 div#top-social-L{display:none}
.sp-header.Style3 .par-bottm{top:0!important}
.sp-header.Style3 .par-tp{top:0!important}
.sp-header.Style3 .par-tp{height:72px}
body.dark-mode .sp-header.Style3 .par-tp{background:#2d325a!important}
.sp-header.Style3 .open.nav1,.sp-header.Style3 .search{top:20px!important;background:#fff!important}
body.dark-mode .sp-header.Style3 .open.nav1,body.dark-mode .sp-header.Style3 .search{background:#242950!important}
.sp-header.Style3 a.op-one svg,.sp-header.Style3 .search svg{color:$(keycolor)!important}
body.dark-mode .sp-header.Style3 a.op-one svg,body.dark-mode .sp-header.Style3 .search svg{color:#fff!important}
body.dark-mode .sp-header.Style3 .open.nav1,body.dark-mode .sp-header.Style3 .search{background:#242950}
.sp-header.Style3 div#logo{position:absolute;$startSide:0;$endSide:0;margin:6px auto}
.container, .floar .lap {width: 100%;}
header.active div#header-inner {width: auto;}
.open.nav1,.search{display:flex!important;top:-15px!important;position:absolute;z-index:9999999}
.open.nav1{$startSide:3%!important}
.search{$endSide:3%}
.PopularPosts a.item-thumbnail.thumb{width:80px;height:70px}
.PopularPosts h3.post-title{width:calc((100% - 90px) / 1)}
#sidepar-wid{width:250px}
.r-r{width:calc((100% - 250px - 15px) / 1)}
.par-tp{top:-335px!important}
nav.nav-par{display:none}
.shareButton .icon{height:13px;width:13px;margin-top:2px}
.Sp-slide .posts:nth-of-type(1){$startSide:27.5%;width:45%}
.Sp-slide .posts:nth-of-type(2),.Sp-slide .posts:nth-of-type(4){$startSide:-45%;padding:0 0 0 15px;width:27.5%}
.Sp-slide .posts:nth-of-type(3),.Sp-slide .posts:nth-of-type(5){padding:0 15px 0 0;width:27.5%}
.par-bottm #Header1_headerimg{max-height:50px;text-align:center}
.par-bottm #header-inner{width:auto;height:50px;margin:0 auto;text-align:center;display:block}
header#sp-header .widget{overflow:initial;text-align:center;margin:0 auto}
.par-bottm #logo{width:200px !important;height:50px;text-align:center;margin:0 auto}
.logo{float:none}
.head-pz{opacity:1}
header#sp-header,.head-pz{height:72px!important}
.par-bottm.active #logo{width:200px !important}
.par-bottm.active #header-inner{width:200px !important}
}
@media screen and (max-width:860px){
.trelists {margin: 0 !important;float: none;width:100%}
.Sp-3colList .posts:nth-last-of-type(1),.Sp-3colList .posts:nth-last-of-type(2){margin-bottom:0!important;border-bottom:0!important;padding-bottom:0!important}
.Sp-slide .posts:not(:first-of-type) .rnav-title{padding:0 5px;max-height:initial!important;height:inherit!important}
.Sp-slide .posts:not(:first-of-type){vertical-align: top;height:inherit!important}
.mid-top-footer .footer-col{width:calc((100% - 30px) / 3);margin-$endSide:15px}
.Sp-3colList .posts:nth-child(odd){margin-$endSide:15px!important}
.Sp-3colList .posts{overflow:hidden;width:calc((100% - 15px) / 2);margin:0 0;vertical-align:top;display:inline-block;margin-bottom:15px!important;padding-bottom:15px!important}
.r-r,#sidepar-wid{position: static !important;float:none;width:100%!important;margin:0}
.Sp-slide .posts:nth-of-type(1){height:200px;$startSide:0;width:100%;float:none;padding:0;margin-bottom:15px}
.Sp-slide .posts:nth-of-type(1) .thumb{height:200px}
.Sp-slide .posts:not(:first-of-type){margin-$endSide:15px;width:calc((100% - 45px) / 4);padding:0!important;float:none;display:inline-block;$startSide:0!important;$endSide:0!important}
.Sp-slide .posts:last-of-type{margin-$endSide:0!important}
}
@media screen and (max-width:720px){
.amp-tags a {
    margin-bottom: 5px;
}
.post-random .newPost{display:block;float:none;width:100%;clear:both;overflow:hidden}
span.modal-close{$endSide:-5px;top:-5px}
.ReadPage-popup-cont{margin:10px auto;width:100%}
.post-random .newPost:last-of-type{margin-top:15px!important}
img.post-thumbnail{height:175px}
.titlewrapper .title{width:auto;top:8px}
.sp-header.Style3 .titlewrapper .title{width:200px;top:4px}
.headline .title{padding:0 20px}
a.Lapel-Link{padding:0 20px}
footer{padding:15px}
.mid-top-footer .footer-col .widget{margin-bottom:30px}
.mid-top-footer .footer-col{float:none;width:100%;margin-$endSide:0!important}
.bottom-footer{padding:0;box-shadow:none}
.bottom-footer .yemen{min-height:auto;display:block!important;float:none;text-align:center;margin-bottom:10px}
.yemen a[title="SeoPlus Template"]{display:inline-block!important}
.bottom-footer .shmal{float:none;margin-top:0;margin:0 auto;text-align:center}
.Blog article.post .post-share .share-icon{flex-grow:0!important;text-align:center;margin:0 auto}
.Blog article.post .post-share .twitterThis a:after,.Blog article.post .post-share .whatsappThis a:after,.Blog article.post .post-share .facebookThis a:after{display:none}
.Blog article.post .post-share .share-popup{align-items:flex-end!important}
.Blog article.post .post-share .share-check:checked + .share-popup ul{margin:0 auto 20px!important}
.Blog article.post .post-share li.share-close > .close-2{display:none!important}
.Blog article.post .post-share li.share-close > .close-1{visibility:visible!important;margin-top:10px!important}
}
@media screen and (max-width:640px){
.textst{font-size:35px}
.sides{width:100%;float:none;margin:0!important}
.Sp-posts5 .posts:nth-of-type(1){margin-$endSide:0;padding-$endSide:0;width:100%;display:block;margin-bottom:15px;border-$endSide:0;height:initial}
.Sp-posts5 .posts:nth-of-type(1) a.thumb{width:100%;height:200px;margin-$endSide:0}
.Sp-posts5 .posts{margin-$endSide:15px;float:none}
.Sp-posts5 .posts:nth-of-type(3),.Sp-posts5 .posts:nth-of-type(5){margin-$endSide:0}
.Sp-posts5 .posts:nth-last-of-type(1),.Sp-posts5 .posts:nth-last-of-type(2){margin-bottom:0;padding-bottom:0;border-bottom:0}
.Sp-posts5 .posts:nth-of-type(1) h3.rnav-title a{font-size:16px}
.Sp-posts1 .posts:nth-of-type(odd),.post .Sp-posts1 .posts:nth-of-type(odd),.Sp-posts0 .posts:nth-of-type(odd),.post .Sp-posts0 .posts:nth-of-type(odd){margin-$endSide:15px!important}
.Sp-posts1 .posts,.post .Sp-posts1 .posts,.Sp-posts0 .posts,.post .Sp-posts0 .posts{width:calc((100% - 15px) / 2);margin-$endSide:0!important;margin-$startSide:0!important;margin-bottom:15px!important}
.Sp-posts1 .posts:nth-last-of-type(1),.Sp-posts1 .posts:nth-last-of-type(2),.post .Sp-posts1 .posts:nth-last-of-type(1),.post .Sp-posts1 .posts:nth-last-of-type(2),.Sp-posts0 .posts:nth-last-of-type(1),.Sp-posts0 .posts:nth-last-of-type(2),.post .Sp-posts0 .posts:nth-last-of-type(1),.post .Sp-posts0 .posts:nth-last-of-type(2){margin-bottom:0!important}
.Sp-slide .posts:nth-of-type(3),.Sp-slide .posts:nth-of-type(5){margin-$endSide:0!important}
.Sp-slide .posts:not(:first-of-type){width:calc((100% - 15px) / 2);margin-bottom:15px}
.Sp-slide .posts:nth-last-of-type(1),.Sp-slide .posts:nth-last-of-type(2){margin-bottom:0}
.post-home,.Sp-Normal .cont{width:calc((100% - 195px) / 1)!important}
.post-outer .thumb,.Sp-Normal .thumb{width:180px!important}
.Sp-Normal span.category,.post-outer span.category{display:none!important}
.Sp-posts2 .posts{width:calc((100% - 2px) / 2)}
}
@media screen and (max-width:550px){
.topic-nav-cont .newPost, .topic-nav-cont .oldPost {float: none;width: 100%;}
.topic-nav-cont .newPost {margin-bottom: 5px;}
.Sp-3colList .posts:nth-child(odd){margin-$endSide:0!important}
.Sp-posts5 .posts:not(:last-of-type),.Sp-posts5 .posts:nth-last-of-type(2),.Sp-3colList .posts,.Sp-3colList .posts:nth-last-of-type(2){padding-$startSide: 0 !important;border-bottom: 1px solid #eee;margin-$endSide:0;float:none;width:100%;margin-bottom:15px!important;padding-bottom:15px!important}
.Sp-posts5 .posts:nth-last-of-type(1){width:100%;padding-bottom:15px;padding-$startSide:0}
}
@media screen and (max-width:480px){
.Sp-posts2 .posts{width:100%;margin-$endSide:0!important}
.Sp-posts1 .posts,.Sp-posts1 .posts:nth-last-of-type(2),.post .Sp-posts1 .posts,.post .Sp-posts1 .posts:nth-last-of-type(2),.Sp-posts0 .posts,.Sp-posts0 .posts:nth-last-of-type(2),.post .Sp-posts0 .posts,.post .Sp-posts0 .posts:nth-last-of-type(2){margin:0 0 15px!important;width:100%!important;display:block;overflow:hidden}
.Sp-slide .posts:not(:first-of-type){width:100%;margin:0 0 15px!important}
.Sp-slide .posts:nth-last-of-type(1){margin-bottom:0!important}
.post .Sp-posts1 .posts:nth-last-of-type(3),.post .Sp-posts0 .posts:nth-last-of-type(3){margin-bottom:15px!important}
.post-outer .thumb,.Sp-Normal .thumb{width:50vw!important;margin-bottom:15px!important;width:100%!important;float:none!important}
.post-home,.Sp-Normal .cont{width:100%!important;float:none!important}
.Sp-Normal span.category,.post-outer span.category{display:inline-block!important}
.Sp-slide .posts:nth-of-type(1) .cont{top: -100px;margin:-80px 15px 0}
.Sp-slide .items a,.Sp-slide .items span{font-size:11px}
.Sp-slide .items a svg{width:11px}
.reactions-label{display:block;text-align:center;margin-bottom:15px}
iframe.reactions-iframe{height:20px;display:block;vertical-align:middle;text-align:center;margin:0 auto}
#siki-page-number{font-size:12px;padding:15px 0}
.siki-next-prev span{font-size:13px!important}
div#rx-options{float:$startSide!important}
}
@media screen and (max-width:360px){
.shareButton a{width:calc((100% - 7px) / 2);margin-$startSide:0!important}
.atags .blog-admin a {margin-top: 0 !important;}
.page .atags .blog-admin{float:$endSide}
.page .atags .blog-admin a{margin-top:0!important}
.commint-cont{display:none}
}

/* FooterMopile */
#nav-widget{position:fixed;top:0;$endSide:0;background-color:#fefefe;width:220px;height:100%;padding:calc(57px + 15px) 0 90px 0;-webkit-transition:all .2s ease;transition:all .2s ease;z-index:2;overflow:hidden;box-shadow:0 6px 18px 0 rgba(9,32,76,.035)}
.navigation-mobile{list-style:none;margin:0;padding:0;color:#161617;fill:#161617;font-size:13px}
.navigation-mobile{display:flex;align-items:center;justify-content:space-evenly;position:fixed;$endSide:0;bottom:-50px;width:100%;height:50px;background-color:#fefefe;z-index:-1}
.navigation-mobile a{display:block;color:$(keycolor)}
.navigation-mobile svg{fill:#505050;height:20px;width:20px}
svg .svg-c{fill:$(keycolor)}
svg.line{fill:none;stroke:#161617;stroke-linecap:round;stroke-linejoin:round;stroke-width:1.5}
svg.line .svg-c{fill:none;stroke:$(keycolor)}
.navigation-mobile svg.line{fill:none;stroke:#505050}
.navigation-mobile{display:none;bottom:-45px}
.navigation-mobile .top-link svg.line{stroke:#505050}
.navigation-mobile .top-link svg.line .svg-c{stroke:#fefefe}
.navigation-mobile .top-link svg.line .svg-c{stroke:$(keycolor)}
.navigation-mobile .dark-link .svg-2{display:none}
#nav-widget{width:100%;padding:0;background:transparent;box-shadow:none;z-index:9;margin-$endSide:-100%}
@media screen and (max-width:992px){
.navigation-mobile{display:flex;bottom:0}
.AmopFot .bottom-footer{padding-bottom:50px}
.AmopFot .buttonsupandlh{display:none}
}

/* new worck */
td.tr-caption { color: unset !important; position: unset !important; bottom: unset !important; background: transparent !important; text-align: unset !important; padding: unset !important; height: unset !important; line-height: unset !important; }
.post-body ol  ul li {list-style: circle;}
.post-body ol ul li:before {display: none !important;}
.post-body ol  ul li {list-style: circle;counter-increment: none;}
.post-body ol ul li:before {display: none !important;}
td.tr-caption, td.tr-caption * {text-align: center !important;}
tbody, table {width: 100%;max-width: 100%;}

/* Sample Ads (Silahkan hapus bagian ini jika iklan sudah di replace semua) */
.ads-here{position:relative;display:flex;align-items:stretch;flex-wrap:wrap;min-height:150px;padding:15px;border:1px solid rgba(0,0,0,.05);border-radius:3px;color:#989b9f;font-size:75%}
.ads-here:after{content:'';display:block;width:50px;height:10px;background-color:rgba(0,0,0,.05);border-radius:0 0 8px 0;position:absolute;top:0;left:0}
.ads-here .ads-img{width:45%;display:flex;flex-shrink:0;align-items:center;justify-content:center;font-style:normal;background-color:rgba(0,0,0,.05)}
.ads-here .ads-img:before{content:'Sample ad'}
.ads-here .ads-content{width:55%;padding:20px 20px 0 0}
.ads-here .ads-content:before, .ads-here .ads-content:after{content:'';display:block;width:100%;padding-top:4%;background-color:rgba(0,0,0,.05)}
.ads-here .ads-content:after{width:70%;margin-top:12px}
.ads-here.feed .ads-img{width:100%;min-height:90px;margin-bottom:15px}
.ads-here.feed .ads-content{padding:0;width:60%} .ads-here.feed .ads-content:before, .ads-here.feed .ads-content:after{padding-top:6%}
@media screen and (max-width:768px){.ads-here{min-height:90px}.ads-here .ads-content{padding-top:8px}.ads-here .ads-content:before, .ads-here .ads-content:after{padding-top:8%}
.Blog .post-toc{width:300px;left:10px;height:auto;padding:15px 20px;margin-bottom:20px;position:fixed;top:95px;background-color:#fefefe;border-radius:4px;box-shadow:0 6px 18px 0 rgba(23,23,26,0.02);font-size:14px}
.Blog .post-tocContent ol li:last-child ol.point2{margin-bottom:0}
.Blog .post-tocContent ol{margin-bottom:0}
.Blog .post-tocContent {overflow: auto;max-height: 50vh}
.Blog .post-tocContainer{padding:0;background-color:unset;border-radius:unset;box-shadow:unset}
.Blog .toc-menu:checked + .post-toc{left:-300px}
.Blog .post-tocHeader label .show{right: -70px; box-shadow:unset}
.Blog .toc-menu:checked + .post-toc .post-tocHeader label .show{background-color:rgba(255,255,255,.36);}
.darkMode .Blog .toc-menu:checked + .post-toc .post-tocHeader label .show{background-color: #2d2d30;}
.Blog .toc-menu:checked + .post-toc .post-tocHeader label .show{right: -58px;box-shadow:0 10px 20px 0 rgba(30,30,30,.08)}
.Blog .toc-menu:checked + .post-toc .post-tocHeader label svg.drop{-webkit-transform:rotate(0deg);transform:rotate(0deg)}
.Blog .toc-menu:checked + .post-toc .post-tocContent{max-height:50vh}
}
.dmca-sample{font-size:8px;color:rgba(254,254,254,.6);border-radius:3px;overflow:hidden} .dmca-sample:before{content:'DMCA';padding:5px 10px;background-color:#2a2a2a} .dmca-sample:after{content:'Protected';padding:5px 10px;background-color:rgba(0,0,0,.1)}
.box-master{background:#fff;padding:5px;margin:5px 0;box-sizing:border-box;box-shadow:0 15px 35px rgba(50,50,93,.1),0 5px 15px rgba(0,0,0,.07);border-radius:.5rem;font-size:.9rem}
div.utama{color:#555;text-align:center;font-weight:700;padding:5px 5px;border-radius:.5rem}
.Blog .post blockquote,.post pre,.post code,.note,.note noteAlert,kbd,.code,.referensi,.source,.izincopy,h1 { -webkit-touch-callout:text; -webkit-user-select:text; -khtml-user-select:text; -ms-user-select:text; -moz-user-select:text; }
.wendyparalax{position:relative;display:block;overflow:visible;width:100%;height:0;margin:auto;text-align:center;z-index:1} .wendyparalax > div{overflow:hidden;width:100%;height:100%;margin:0;position:absolute;top:0;right:0;clip:rect(auto auto auto auto)} .wendyparalax > div > div{width:calc(100% - 40px);height:100%;position:fixed;top:0;right:0;left:0;margin:0 auto;-moz-transform:translateZ(0);-webkit-transform:translateZ(0);-ms-transform:translateZ(0);-o-transform:translateZ(0);transform:translateZ(0)} .wendyparalax > div > div > div{display:-webkit-box;display:-webkit-flex;display:-moz-box;display:-ms-flexbox;display:flex;-webkit-align-content:center;align-content:center;-webkit-align-items:center;-ms-flex-align:center;width:100%;height:100%;position:absolute;right:0;left:0;top:37px;align-items:center;background:#fff} .wendyparalax > div > div > div > *{margin:auto} .wendyparalax > div > div > div > a{width:100%;height:100%} .wendyparalax img,.wendyparalax iframe,.wendyparalax ins{height:100%;border:0} .wendyparalax{width:100%;min-width:300px;min-height:600px;text-align:center} .adParallax{width:100%;min-width:300px;min-height:600px;text-align:center;display:block; margin:10px 0px; padding:0px}
.darkMode .wendyparalax > div > div > div {background:#1e1e1e}
@keyframes flipInX{from{-webkit-transform:perspective(400px) rotate3d(1,0,0,90deg);transform:perspective(400px) rotate3d(1,0,0,90deg);-webkit-animation-timing-function:ease-in;animation-timing-function:ease-in;opacity:0}40%{-webkit-transform:perspective(400px) rotate3d(1,0,0,-20deg);transform:perspective(400px) rotate3d(1,0,0,-20deg);-webkit-animation-timing-function:ease-in;animation-timing-function:ease-in}60%{-webkit-transform:perspective(400px) rotate3d(1,0,0,10deg);transform:perspective(400px) rotate3d(1,0,0,10deg);opacity:1}80%{-webkit-transform:perspective(400px) rotate3d(1,0,0,-5deg);transform:perspective(400px) rotate3d(1,0,0,-5deg)}to{-webkit-transform:perspective(400px);transform:perspective(400px)}}
@keyframes fadeInUp{from{opacity:0;-webkit-transform:translate3d(0,100%,0);transform:translate3d(0,100%,0)}to{opacity:1;-webkit-transform:none;transform:none}}
#Adblock ::-webkit-scrollbar{-webkit-appearance:none;width:4px;height:5px}#Adblock ::-webkit-scrollbar-thumb{background-color:rgba(0,0,0,.15);border-radius:10px}#Adblock ::-webkit-scrollbar-track{background-color:transparent}#Adblock ::-webkit-scrollbar-thumb:hover{background-color:rgba(0,0,0,.25)}
#Adblock{background:rgba(34,47,62,0.67);position:fixed;margin:auto;right:0;left:0;top:0;bottom:0;overflow:auto;z-index:999999;-webkit-backdrop-filter:blur(6px);backdrop-filter:blur(6px)}
#Adblock .header{margin:10px 0 20px 0;position:relative;top:initial;right:initial}
#Adblock .header h2{color:#222;font-size:1.8rem}
#Adblock .inner{background:#fff;border-radius:12px;color:#222;box-shadow:0 0 2rem -1rem rgba(0,0,0,0.5);text-align:center;width:100%;max-width:640px;padding:30px;margin:7% auto 2% auto;animation:flipInX 1s}
#Adblock button{position:relative;overflow:hidden;padding:6px 20px;background:#f5aa33;color:#fff;margin:20px 5px;cursor:pointer;border-radius:99em;font-size:13px;font-weight:500;border:2px solid #f5aa33;transition:initial;box-shadow:0 1px 0 rgba(0,0,0,0.01),0 5px 10px rgba(0,0,0,0.1)}
#Adblock button:hover{background:#fff;color:#f5aa33;outline:none;border-color:#f5aa33}
#Adblock button.active,#Adblock button:hover.active{background:#ee5253;color:#fff;border-color:#ee5253;outline:none}
#Adblock .fixblock{background:#f7f9f8;text-align:right;color:#000;padding:20px;height:250px;overflow:auto;line-height:30px;border-radius:8px;border:1px solid rgba(0,0,0,0.05)}
#Adblock .fixblock div{display:none}
#Adblock .fixblock div.active{display:block;animation:fadeInUp .5s}
#Adblock ol{margin-right:20px}
#Adblock button:after,#Adblock button:before{content:'';display:block;position:absolute;bottom:0;left:0;right:0;height:50%;background:rgba(0,0,0,0.05);background-repeat:no-repeat;transition:all .3s}
#Adblock button:before{height:0;top:0;bottom:initial}
#Adblock button:hover:after{height:0}
#Adblock button:hover:before{height:50%}
@media(max-width:768px){#Adblock .inner{width:calc(100% - 20px);margin:10px auto;padding:15px}}
.stickAd{position:fixed;bottom:0;right:0;left:0;width:100%;height:auto;max-height:200px;padding:5px 5px;box-shadow:0 -6px 18px 0 rgba(9,32,76,.1);-webkit-transition:all .1s ease-in;transition:all .1s ease-in;display:flex;align-items:center;justify-content:center;background-color:#fefefe;z-index:50}
.stickAdclose{width:30px;height:30px;display:flex;align-items:center;justify-content:center;border-radius:0 12px 0 0;position:absolute;left:0;top:-30px;background-color:inherit}
.stickAdcontent{flex-grow:1;overflow:hidden;display:block;position:relative}
.stickAdin:checked ~ .stickAd{padding:0;min-height:0}
.stickAdin:checked ~ .stickAd .stickAdcontent{display:none}
.stickAdin:checked ~ .stickAd .stickAdclose svg.drop{-webkit-transform:rotate(180deg);transform: rotate(180deg)}
.darkMode .stickAd, .darkMode .stickAdclose{background:#2d2d30;color:rgba(0,0,0,.10)}
.goog-te-banner-frame.skiptranslate,.goog-te-gadget-simple img,img.goog-te-gadget-icon{display:none!important}body{top:0px!important}.goog-te-gadget-simple{background:url("data:image/svg+xml,<svg class='ts' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><g data-name='Google Translate' id='Google_Translate'><g data-name='&lt;Group&gt;' id='_Group_'><path d='M.5,2V18A1.5,1.5,0,0,0,2,19.5H17L10.5.5H2A1.5,1.5,0,0,0,.5,2Z' data-name='&lt;Path&gt;' id='_Path_' style='fill:none;stroke:%23161617;stroke-linecap:round;stroke-linejoin:round'/><path d='M12,4.5H22A1.5,1.5,0,0,1,23.5,6V22A1.5,1.5,0,0,1,22,23.5H13.5l-1.5-4' data-name='&lt;Path&gt;' id='_Path_2' style='fill:none;stroke:%23161617;stroke-linecap:round;stroke-linejoin:round'/><line data-name='&lt;Path&gt;' id='_Path_3' style='fill:none;stroke:%23161617;stroke-linecap:round;stroke-linejoin:round' x1='17' x2='13.5' y1='19.5' y2='23.5'/><line data-name='&lt;Path&gt;' id='_Path_4' style='fill:none;stroke:%23161617;stroke-linecap:round;stroke-linejoin:round' x1='14.5' x2='21.5' y1='10.5' y2='10.5'/><line data-name='&lt;Path&gt;' id='_Path_5' style='fill:none;stroke:%23161617;stroke-linecap:round;stroke-linejoin:round' x1='17.5' x2='17.5' y1='9.5' y2='10.5'/><path d='M20,10.5c0,1.1-1.77,4.42-4,6' data-name='&lt;Path&gt;' id='_Path_6' style='fill:none;stroke:%23161617;stroke-linecap:round;stroke-linejoin:round'/><path d='M16,13c.54,1.33,4,4.5,4,4.5' data-name='&lt;Path&gt;' id='_Path_7' style='fill:none;stroke:%23161617;stroke-linecap:round;stroke-linejoin:round'/><path d='M10.1,7.46a4,4,0,1,0,1.4,3h-4' data-name='&lt;Path&gt;' id='_Path_8' style='fill:none;stroke:%23161617;stroke-linecap:round;stroke-linejoin:round'/></g></g></svg>") center / 12px no-repeat;-webkit-transition:all .2s ease;transition:all .2s ease;background-size: 20px 20px;display:inline-block;font-weight:400;line-height: 1.8;padding:0 6px;text-align:center;white-space:nowrap;vertical-align: middle;-ms-touch-action: manipulation;touch-action:manipulation;cursor:pointer;border-right:none!important;border-top:none!important;border-bottom:none!important;border-left:none!important;border-radius: 4px;}
#google_translate_element{padding-right:15px}.goog-te-menu-value span {display:none!important}.goog-te-menu-frame{box-shadow:none!important}.darkMode .goog-te-gadget-simple{background-color:#2d2d30!important;}.darkMode .goog-te-gadget-simple.goog-te-gadget-simple{background:url("data:image/svg+xml,<svg viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><g data-name='Google Translate' id='Google_Translate'><g data-name='&lt;Group&gt;' id='_Group_'><path d='M.5,2V18A1.5,1.5,0,0,0,2,19.5H17L10.5.5H2A1.5,1.5,0,0,0,.5,2Z' data-name='&lt;Path&gt;' id='_Path_' style='fill:none;stroke:%23767676;stroke-linecap:round;stroke-linejoin:round'/><path d='M12,4.5H22A1.5,1.5,0,0,1,23.5,6V22A1.5,1.5,0,0,1,22,23.5H13.5l-1.5-4' data-name='&lt;Path&gt;' id='_Path_2' style='fill:none;stroke:%23767676;stroke-linecap:round;stroke-linejoin:round'/><line data-name='&lt;Path&gt;' id='_Path_3' style='fill:none;stroke:%23767676;stroke-linecap:round;stroke-linejoin:round' x1='17' x2='13.5' y1='19.5' y2='23.5'/><line data-name='&lt;Path&gt;' id='_Path_4' style='fill:none;stroke:%23767676;stroke-linecap:round;stroke-linejoin:round' x1='14.5' x2='21.5' y1='10.5' y2='10.5'/><line data-name='&lt;Path&gt;' id='_Path_5' style='fill:none;stroke:%23767676;stroke-linecap:round;stroke-linejoin:round' x1='17.5' x2='17.5' y1='9.5' y2='10.5'/><path d='M20,10.5c0,1.1-1.77,4.42-4,6' data-name='&lt;Path&gt;' id='_Path_6' style='fill:none;stroke:%23767676;stroke-linecap:round;stroke-linejoin:round'/><path d='M16,13c.54,1.33,4,4.5,4,4.5' data-name='&lt;Path&gt;' id='_Path_7' style='fill:none;stroke:%23767676;stroke-linecap:round;stroke-linejoin:round'/><path d='M10.1,7.46a4,4,0,1,0,1.4,3h-4' data-name='&lt;Path&gt;' id='_Path_8' style='fill:none;stroke:%23767676;stroke-linecap:round;stroke-linejoin:round'/></g></g></svg>") center / 12px no-repeat;-webkit-transition:all .2s ease;transition:all .2s ease;background-size: 20px 20px}
.icon-set{display:flex;align-items:stretch}
.icon-set .icon-svg{display:flex;align-items:center;justify-content:center;flex-shrink:0;width:75px;margin:.5em 0 .5em 15px;background-color:#fefefe;border-radius:4px}
.icon-set .icon-svg svg{width:26px;height:26px}
.icon-set .icon-html{width:calc(100% - 90px)}
.icon-set .icon-html pre{margin:.5em 0}
.darkMode .icon-set .icon-svg{background-color:#1e1e1e}
.zoomclick.active{position:fixed;top:0;right:0;bottom:0;left:0;z-index:9999999;background:#000;}
.zoomclick.active img{height:100%;max-width:800px;position:absolute;right:50%;top:50%;transform:translate(50%, -50%);}
.flow{overflow:hidden;position:relative;}
.zoomclick.active:after{content:"";cursor:pointer;width:40px;height:40px;background-image:url("data:image/svg+xml;charset=utf8,%3csvg viewBox='0 0 24 24' width='34' height='34' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3e%3cg%3e%3cpath style='fill:%23cccccc' d='M19,6.41L17.59,5L12,10.59L6.41,5L5,6.41L10.59,12L5,17.59L6.41,19L12,13.41L17.59,19L19,17.59L13.41,12L19,6.41Z'%3e%3c/path%3e%3c/g%3e%3c/svg%3e");background-position:top left;-webkit-background-size:40px 40px;background-size:40px 40px;position:absolute;top:10px;left:10px;z-index:2;opacity:.8;transition:all .4s ease-in-out}
@media screen and (max-width:800px){.zoomclick.active img{width:100%;height:auto;max-width:100%}}
.darkMode span.title:before, .darkMode h4.title:before, .darkMode h3.title:before, .darkMode h3.heading:before {
background-color: #3d5afe;
}
span.title, h4.title, h3.title, h3.heading{position:relative;margin-bottom:40px;font-size:15px;padding-right:8px;margin-bottom:24px;line-height:1;letter-spacing:1px;border-right:2px solid #3d5afe;text-transform:uppercase}
.navMenu .sosmed ul.copyright{font-size:13px;font-weight:bolder;display:block;margin-top:10px;}
.navMenu .sosmed ul.copyright .creator{display:block;}
.navMenu .sosmed ul.copyright .creator a{display:inline;font-style:italic;font-weight:bold;}
.sidebar .widget {
background-color: #fff;
padding: 20px;
box-shadow: 0 10px 10px 0 rgb(30 30 30 / 8%);
border-radius: 4px;
}
.darkMode .sidebar .widget{
background-color: #232323;
}
table {border-collapse:collapse;margin:25px auto;font-size:14px;min-width:95%;border-radius:5px 5px 0 0;overflow:hidden;}
table thead{border:1px solid #00BF7F;}
table tbody{border:1px solid hsl(0, 0%, 90%);}
table em{color: #00BF7F;}
table thead tr{background-color:#00BF7F;color:hsl(0, 0%, 100%);text-align:right;text-align:center;font-weight:bold;}
table th,table td{padding: 6px;}
table th:first-of-type,table td:first-of-type{text-align:right;padding-right: 10px;}
table tbody tr{border-bottom:1px solid hsl(0, 0%, 90%);cursor:pointer;}
table tbody tr:last-of-type{border-bottom: 2px solid #00BF7F;}
table tbody tr:hover{background-color: #00bd7e1a;}
tbody .Premium{position: relative;}
tbody .Premium::before,tbody .Premium::after{position: absolute;content: '';width: 3px;background-color:hsl(145, 63%, 42%);top:0;bottom:0;right:0;left:0;margin:auto;border-radius:50px;}
tbody .Premium::before{transform: rotate(-45deg);height: 8px;right: -6px;bottom: -2.5px;}
tbody .Premium::after{transform: rotate(45deg);height: 15px;left: -6px;top: -2.5px;}
.zn-tmp,.zn-tmp a{position:relative;display:inline-block!important;vertical-align:middle}
.zn-tmp{position:relative;width:25px;height:25px;margin:0 4px 0 0}.zn-tmp a{background:url() top no-repeat;width:25px;height:25px;background-size:25px 50px;-webkit-transition:all 0.15s ease-in-out;-moz-transition:all 0.15s ease-in-out;-ms-transition:all 0.15s ease-in-out;-o-transition:all 0.15s ease-in-out;transition:all 0.15s ease-in-out}.zn-tmp a:hover{background-position:bottom}.zn-tmp span{display:none}.zn-tmp a:after{font-size:0.6rem;padding:3px 7px;position:absolute;top:0;right:25px;z-index:1;content:attr(tooltip);background:#3d5afe;color:#ffffff;opacity:0;visibility:hidden;-webkit-transition:all 0.1s ease-in-out 0.1s;-moz-transition:all 0.1s ease-in-out 0.1s;-ms-transition:all 0.1s ease-in-out 0.1s;-o-transition:all 0.1s ease-in-out 0.1s;transition:all 0.1s ease-in-out 0.1s;-webkit-border-radius:100px;-moz-border-radius:100px;-ms-border-radius:100px;-o-border-radius:100px;border-radius:100px;line-height:1rem;letter-spacing:.5px;white-space:nowrap}.zn-tmp a:hover:after{opacity:1;visibility:visible;right:30px}}
.zn-tmp a{) top no-repeat;width:25px;height:25px;background-size:25px 50px;-webkit-transition:all 0.15s ease-in-out;-moz-transition:all 0.15s ease-in-out;-ms-transition:all 0.15s ease-in-out;-o-transition:all 0.15s ease-in-out;transition:all 0.15s ease-in-out}.zn-tmp a:hover:after{opacity:1;visibility:visible;right:30px}}
.downloadInfo{max-width:500px;background-color:#fefefe; box-shadow:0 10px 8px -8px rgb(0 0 0 / 12%); border:1px solid var(--content-border);border-radius:5px; padding:15px;margin-top:20px;margin-bottom:20px; display:flex;align-items:center; line-height:1.8em;font-size:14px} .downloadInfo a, .downloadInfo .fileType{color:white;flex-shrink:0;display:flex;align-items:center;justify-content:center; width:50px;height:50px; padding:10px; background:#ebeced linear-gradient(200deg,#00dcc0 0,#005af0 80%);border-radius:10px} .downloadInfo a{background-color:var(--link-bg);color:#fefefe; margin:0;padding:10px 12px;border-radius:3px; width:auto;height:auto; line-height:20px;font-size:13px} .downloadInfo a:after{content:attr(aria-label)} .downloadInfo .fileType:before{content:attr(data-text)} .downloadInfo .fileName{flex-grow:1; width:calc(100% - 150px);padding:0 15px} .downloadInfo .fileName > *{display:block;white-space:nowrap;overflow:hidden;text-overflow:ellipsis} .downloadInfo .fileSize{line-height:1.4em;font-size:12px;opacity:.8} .darkMode .downloadInfo{background-color:var(--dark-bgSec); border:0} .darkMode .downloadInfo .fileType{background-color:var(--dark-bg)} @media screen and (max-width:480px){.downloadInfo{padding:12px} .downloadInfo a{width:50px;height:50px;border-radius:10px} .downloadInfo a:after{display:none} .downloadInfo a .icon{margin:0}}
.post .extLink{display:inline-flex;align-items:center} .post .extLink:after{content:''; width:16px;height:16px; display:inline-block;margin-left:5px; background: url("data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='none' stroke='%23989b9f' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'><path d='M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6'/><polyline points='15 3 21 3 21 9'/><line x1='10' x2='21' y1='14' y2='3'/></svg>") center / 16px no-repeat} .post .extLink.alt:after{background-image: url("data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='none' stroke='%23989b9f' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'><path d='M15 7h3a5 5 0 0 1 5 5 5 5 0 0 1-5 5h-3m-6 0H6a5 5 0 0 1-5-5 5 5 0 0 1 5-5h3'/><line x1='8' y1='12' x2='16' y2='12'/></svg>")} .post .postCaption{display:block; font-size:13px;line-height:normal; margin-top:5px} .post .postReference{display:block; font-size:13px;line-height:normal; opacity:.8}
.serv-cl{
direction: inherit;
cursor: context-menu;
display: inline-block;
padding: 2px 11px;
color: white;
text-decoration: none;
text-align: center;
height: 30px;
margin: 3px 2px;
font-size: 8pt;
background: #3d5afe;
border-radius: 5px;
}
.zn-title{
width: 100%;
background: #3d5afe;
color: white;
height: 37px;
padding: 3px 10px;
border-radius: 8px;
margin: 5px;
}
.zn-txt{
color: white;
margin: 5px;
}
matech {
direction: inherit;
cursor: context-menu;
display: inline-block;
padding: 5px 10px;
color: white;
font: bold 8pt arial;
text-decoration: none;
text-align: center;
height: 30px;
margin: 5px 5px;
background: #3d5afe;
border-radius: 5px;
}
Table of Contents
#btn-cm{border:1px solid #dadada;border-radius:5px;background-color:#f9f9f9}
#btn_toc{font-weight:700;cursor:pointer;margin:10px}
#btn_toc:focus,#toc li:focus,.back_toc:focus{outline:none}
#btn_toc svg{vertical-align:middle}
#toc li{cursor:pointer}
#toc{display:grid}
.back_toc{cursor:pointer;text-align:left}
:target::before{content:"";display:block;height:0;margin-top:-49px;visibility:hidden}
.nmbtn {
display: inline-flex;
align-items: center;
margin: 15px 15px 15px 0;
padding: 10px 20px;
outline: 0;
border: 0;
color: white;
background-color: #3d5afe;
border-radius: 3px;
font-size: 13px;
line-height: 22px;
}
::selection {
background: #3d5afe;
color: #fff;
}
.mint-tips,
[class*=mint-tips] {
position: relative;
display: inline-block;
-webkit-font-smoothing: antialiased;
height: 100%
}
.mint-tips::before, [class*=mint-tips]::before {
content: attr(data-title);
white-space: nowrap;
top: -10px;
color: #fff;
font-weight: 400;
padding: 4px 7px;
background: #3d59fc;
box-shadow: 0 2px 2px -1px rgb(0 0 0 / 30%), 0 1px 0 0 rgb(0 0 0 / 5%);
pointer-events: none;
font-size: 14px;
text-decoration: none;
border-radius: 7px;
}
.mint-tips::after, [class*=mint-tips]::after {
content: "";
border-style: solid;
border-color: rgb(61 90 254) transparent transparent;
border-width: 10px;
top: 8px;
}
.mint-tips::after,
.mint-tips::before,
[class*=mint-tips]::after,
[class*=mint-tips]::before {
opacity: 0;
position: absolute;
left: 50%;
z-index: 100;
-webkit-transform: translate(-50%, -100%);
transform: translate(-50%, -100%);
-webkit-user-select: none;
-moz-user-select: none;
-ms-user-select: none;
user-select: none;
-webkit-transform-origin: top;
transform-origin: top
}
.mint-tips::after,
[class*=mint-tips]::after {
content: "";
border-style: solid;
border-color: rgb(61 90 254) transparent transparent;
border-width: 10px;
top: 8px
}
.mint-tips:hover::after,
.mint-tips:hover::before,
[class*=mint-tips]:hover::after,
[class*=mint-tips]:hover::before {
opacity: 1
}
[data-mint-tips=left]::after,
[data-mint-tips=left]::before {
top: 50%;
right: auto;
-webkit-transform: translate(-100%, -50%);
transform: translate(-100%, -50%)
}
[data-mint-tips=left]::before {
left: -10px
}
[data-mint-tips=left]::after {
left: 8px;
border-color: transparent transparent transparent rgba(0, 0, 0, .8)
}
[data-mint-tips=right]::after,
[data-mint-tips=right]::before {
top: 50%;
left: auto;
-webkit-transform: translate(100%, -50%);
transform: translate(100%, -50%)
}
[data-mint-tips=right]::before {
right: -10px
}
[data-mint-tips=right]::after {
right: 8px;
border-color: transparent rgba(0, 0, 0, .8) transparent transparent
}
[data-mint-tips=bottom]::after,
[data-mint-tips=bottom]::before {
top: auto;
-webkit-transform: translate(-50%, 100%);
transform: translate(-50%, 100%)
}
[data-mint-tips=bottom]::before {
bottom: -10px
}
[data-mint-tips=bottom]::after {
bottom: 8px;
border-color: transparent transparent rgba(0, 0, 0, .8)
}
[class*=mint-tips--]::after,
[class*=mint-tips--]::before {
-webkit-transition: opacity .2s, -webkit-transform .2s;
transition: opacity .2s, -webkit-transform .2s;
transition: transform .2s, opacity .2s;
transition: transform .2s, opacity .2s, -webkit-transform .2s
}
[class*=mint-tips--]:hover::after,
[class*=mint-tips--]:hover::before {
-webkit-transition: opacity .3s, -webkit-transform ease .5s;
transition: opacity .3s, -webkit-transform ease .5s;
transition: transform ease .5s, opacity .3s;
transition: transform ease .5s, opacity .3s, -webkit-transform ease .5s
}
[class*=mint-tips--]::before {
-webkit-transform-origin: bottom;
transform-origin: bottom
}
[class*=mint-tips--]::after {
-webkit-transform-origin: top;
transform-origin: top
}
[data-mint-tips=left][class*=mint-tips--]::before {
-webkit-transform-origin: right;
transform-origin: right
}
[data-mint-tips=left][class*=mint-tips--]::after {
-webkit-transform-origin: left;
transform-origin: left
}
[data-mint-tips=bottom][class*=mint-tips--]::before {
-webkit-transform-origin: top;
transform-origin: top
}
[data-mint-tips=bottom][class*=mint-tips--]::after {
-webkit-transform-origin: bottom;
transform-origin: bottom
}
[data-mint-tips=right][class*=mint-tips--]::before {
-webkit-transform-origin: left;
transform-origin: left
}
[data-mint-tips=right][class*=mint-tips--]::after {
-webkit-transform-origin: right;
transform-origin: right
}
.mint-tips--fade:hover::after,
.mint-tips--fade:hover::before {
-webkit-transition: opacity .5s;
transition: opacity .5s
}
[class*=mint-tips--slide]:hover::after,
[class*=mint-tips--slide]:hover::before {
-webkit-transform: translate(-50%, -100%);
transform: translate(-50%, -100%)
}
[data-mint-tips=left][class*=mint-tips--slide]:hover::after,
[data-mint-tips=left][class*=mint-tips--slide]:hover::before {
-webkit-transform: translate(-100%, -50%);
transform: translate(-100%, -50%)
}
[data-mint-tips=bottom][class*=mint-tips--slide]:hover::after,
[data-mint-tips=bottom][class*=mint-tips--slide]:hover::before {
-webkit-transform: translate(-50%, 100%);
transform: translate(-50%, 100%)
}
[data-mint-tips=right][class*=mint-tips--slide]:hover::after,
[data-mint-tips=right][class*=mint-tips--slide]:hover::before {
-webkit-transform: translate(100%, -50%);
transform: translate(100%, -50%)
}
.mint-tips--slide-in::after,
.mint-tips--slide-in::before {
-webkit-transform: translate(-50%, -50%);
transform: translate(-50%, -50%)
}
[data-mint-tips=left].mint-tips--slide-in::after,
[data-mint-tips=left].mint-tips--slide-in::before {
-webkit-transform: translate(-90%, -50%);
transform: translate(-90%, -50%)
}
[data-mint-tips=bottom].mint-tips--slide-in::after,
[data-mint-tips=bottom].mint-tips--slide-in::before {
-webkit-transform: translate(-50%, 50%);
transform: translate(-50%, 50%)
}
[data-mint-tips=right].mint-tips--slide-in::after,
[data-mint-tips=right].mint-tips--slide-in::before {
-webkit-transform: translate(90%, -50%);
transform: translate(90%, -50%)
}
.mint-tips--slide-out::after,
.mint-tips--slide-out::before {
-webkit-transform: translate(-50%, -120%);
transform: translate(-50%, -120%)
}
[data-mint-tips=left].mint-tips--slide-out::before {
-webkit-transform: translate(-110%, -50%);
transform: translate(-110%, -50%)
}
[data-mint-tips=left].mint-tips--slide-out::after {
-webkit-transform: translate(-200%, -50%);
transform: translate(-200%, -50%)
}
[data-mint-tips=bottom].mint-tips--slide-out::after,
[data-mint-tips=bottom].mint-tips--slide-out::before {
-webkit-transform: translate(-50%, 120%);
transform: translate(-50%, 120%)
}
[data-mint-tips=right].mint-tips--slide-out::before {
-webkit-transform: translate(110%, -50%);
transform: translate(110%, -50%)
}
[data-mint-tips=right].mint-tips--slide-out::after {
-webkit-transform: translate(200%, -50%);
transform: translate(200%, -50%)
}
[class*=mint-tips--bounce]:hover::after,
[class*=mint-tips--bounce]:hover::before {
-webkit-transition: opacity .3s, -webkit-transform cubic-bezier(.66, -2, .36, 2) .5s;
transition: opacity .3s, -webkit-transform cubic-bezier(.66, -2, .36, 2) .5s;
transition: transform cubic-bezier(.66, -2, .36, 2) .5s, opacity .3s;
transition: transform cubic-bezier(.66, -2, .36, 2) .5s, opacity .3s, -webkit-transform cubic-bezier(.66, -2, .36, 2) .5s;
-webkit-transform: translate(-50%, -100%) scale(1);
transform: translate(-50%, -100%) scale(1)
}
[data-mint-tips=left][class*=mint-tips--bounce]:hover::after,
[data-mint-tips=left][class*=mint-tips--bounce]:hover::before {
-webkit-transform: translate(-100%, -50%) scale(1);
transform: translate(-100%, -50%) scale(1)
}
[data-mint-tips=bottom][class*=mint-tips--bounce]:hover::after,
[data-mint-tips=bottom][class*=mint-tips--bounce]:hover::before {
-webkit-transform: translate(-50%, 100%) scale(1);
transform: translate(-50%, 100%) scale(1)
}
[data-mint-tips=right][class*=mint-tips--bounce]:hover::after,
[data-mint-tips=right][class*=mint-tips--bounce]:hover::before {
-webkit-transform: translate(100%, -50%) scale(1);
transform: translate(100%, -50%) scale(1)
}
.mint-tips--bounce-in::after,
.mint-tips--bounce-in::before {
-webkit-transform: translate(-50%, -100%) scale(.8);
transform: translate(-50%, -100%) scale(.8)
}
[data-mint-tips=left].mint-tips--bounce-in::after,
[data-mint-tips=left].mint-tips--bounce-in::before {
-webkit-transform: translate(-100%, -50%) scale(.8);
transform: translate(-100%, -50%) scale(.8)
}
[data-mint-tips=bottom].mint-tips--bounce-in::after,
[data-mint-tips=bottom].mint-tips--bounce-in::before {
-webkit-transform: translate(-50%, 100%) scale(.8);
transform: translate(-50%, 100%) scale(.8)
}
[data-mint-tips=right].mint-tips--bounce-in::after,
[data-mint-tips=right].mint-tips--bounce-in::before {
-webkit-transform: translate(100%, -50%) scale(.8);
transform: translate(100%, -50%) scale(.8)
}
.mint-tips--bounce-out::after,
.mint-tips--bounce-out::before {
-webkit-transform: translate(-50%, -100%) scale(1.1);
transform: translate(-50%, -100%) scale(1.1)
}
[data-mint-tips=left].mint-tips--bounce-out::after,
[data-mint-tips=left].mint-tips--bounce-out::before {
-webkit-transform: translate(-100%, -50%) scale(1.1);
transform: translate(-100%, -50%) scale(1.1)
}
[data-mint-tips=bottom].mint-tips--bounce-out::after,
[data-mint-tips=bottom].mint-tips--bounce-out::before {
-webkit-transform: translate(-50%, 100%) scale(1.1);
transform: translate(-50%, 100%) scale(1.1)
}
[data-mint-tips=right].mint-tips--bounce-out::after,
[data-mint-tips=right].mint-tips--bounce-out::before {
-webkit-transform: translate(100%, -50%) scale(1.1);
transform: translate(100%, -50%) scale(1.1)
}
.Blog .infox {
position: relative;
padding: 20px 30px 20px 50px;
background-color: #3d5afe;
color: #fefefe;
line-height: 1.62em;
border-radius: 10px;
}
.infox svg {
fill: #3d5afe !important;
background: #fefefe;
margin-left: 5px;
padding: 4px;
width: 26px;
margin-bottom: 5px;
border-radius: 30px;
height: 26px;
}
.contentasras span {
color: #444;
background-image: url(https://3.bp.blogspot.com/-utcbZKnbVZc/XgtkP15WioI/AAAAAAAABBg/fdJUQAvGmE4-PuMcjE89Q1k-EVi-veyMwCK4BGAYYCw/s1600/landing.png);
height: 62px;
width: 144px;
display: block;
margin: 0 auto;
transform: scale(0.8);
}
.khamsat span {
background-position-y: 0;
}
.kafiil span {
background-position-y: -248px;
}
.vodafone span {
background-position-y: -124px;
}
.vodafone a {
background-color: #ee1c23;
}
.kafiil a {
background-color: #89bc38;
}
.khamsat a {
background-color: #e69a01;
}
.picalica a {
background-color: #a9a3c7;
}
.paypal a {
background-color: #179bd7;
}
.picalica span {
background-position-y: -62px;
}
.contentasras a {
display: block;
width: 140px;
margin: 10px auto;
padding: 8px 0;
border-radius: 3px;
color: #fff;
text-align: center;
}
.profileboxcolor {
padding: 10px;
}
.profilebox {
font-family: Cairo;
position: relative;
background: #3d5afe;
min-height: 180px;
max-width: 1500px;
width: 100%;
border-radius: 8px;
padding: 0px 60px 20px 20px;
box-shadow: 0 0.5px 2px rgb(0 0 0 / 24%), 0 0.5px 3px rgb(0 0 0 / 12%);
display: flex;
flex-direction: column;
margin: 10px 5px 7px -6px;
}
.Blog .post .post-entry img {
display: inline-block;
height: auto!important;
}
.profpic {
position: absolute;
top: 3px;
right: -25px;
height: 120px;
width: 90px;
border-radius: 50%;
background: #3d5afe;
display: inline-block;
box-shadow: 0 0.5px 2px rgb(0 0 0 / 50%), 0 0.5px 3px rgb(0 0 0 / 50%);
}
.prof-sm {
position: absolute;
list-style: none;
padding: 0;
margin: 0;
top: 100px;
right: -20px;
width: 40px;
}
.prof-sm .sm {
width: 40px;
height: 40px;
margin-bottom: 4px;
border-radius: 50%;
background: #f7f7f7;
transition: all 0.15s ease-in-out;
box-shadow: 0 0.5px 2px rgb(0 0 0 / 24%), 0 0.5px 3px rgb(0 0 0 / 12%);
}
.prof-sm svg {
width: 30px;
height: 30px;
margin: 5px;
border-radius: 50%;
}
.prof-sm a {
display: inline-block;
height: 40px;
width: 40px;
border-radius: 50%;
}
.user-desc {
color: rgb(254 254 254);
font-size: 11pt;
line-height: 15pt;
flex: 1 0 auto;
text-align: right;
}
.usertitl {
color: rgb(254 254 254);
font-size: 20px;
font-weight: bolder;
line-height: 15pt;
text-align: right;
margin: 19px 17px -2px 14px;
}
main {
display: block;
padding: 30px 0 33px 10px;
-webkit-transition: all .1s ease;
transition: all .1s ease;
}
btn.copy-code-button {
z-index: 2;
position: absolute;
font-size: 13px;
font-weight: 500;
padding: 3px 8px;
border: none;
color: #fff!important;
background: #3d5afe!important;
box-shadow: 0 1px 4px rgb(0 0 0 / 20%);
margin: 28px 6px;
border-radius: 3px;
}
#author {
padding: 1px;
position: relative;
z-index: 1;
text-align: center;
background: #3d5afe;
color: #fff;
margin-top: 50px;
border-radius: 15px;
width: 100%;
height: auto;
}
.section.bordered {
border-top: 1px solid #e5e5e5;
margin: 0 -60px;
padding-right: 60px;
padding-left: 60px;
}
#author div.avatar {
position: absolute;
right: 50%;
top: 0;
z-index: 2;
width: 80px;
margin: -40px -40px 0 0;
}
#author div.avatar a {
display: block;
border-radius: 50%;
overflow: hidden;
}
.widget_media_image a, a.hover-effect {
display: block;
position: relative;
overflow: hidden;
background: #000;
}
.thumb {
position: relative;
z-index: 1;
min-height: 80px;
}.widget_media_image a img, .widget_media_image a span.cover, a.hover-effect img, a.hover-effect span.cover {
display: block;
width: 101%;
height: auto;
-webkit-backface-visibility: hidden;
backface-visibility: hidden;
-webkit-transition: all 600ms ease;
transition: all 600ms ease;
}
.full-link, .thumb .fullimage {
position: absolute;
right: 0;
top: 0;
width: 100%;
height: 100%!important;
z-index: 1;
}
.cover {
background-repeat: no-repeat!important;
background-position: center center!important;
background-size: cover!important;
}#author #single.fullcover .featured-image .top, #author div.info, #single.fullcover .featured-image #author .top {
font-size: 16px;
max-width: 75%;
margin: 0 auto;
}
#author #single #comments .comment .comment-author, #author .author-name a, #author .title, #author .woocommerce .woocommerce-loop-product__title, #author .woocommerce fieldset legend, #author .wpcf7 label, #single #comments .comment #author .comment-author, .woocommerce #author .woocommerce-loop-product__title, .woocommerce fieldset #author legend, .wpcf7 #author label {
color: #fff;
}
#author .author-name {
margin: 44px 1px;
margin-bottom: 20px;
line-height: 1;
}
.border-effect a, .underline-effect a {
position: relative;
z-index: 1;
padding-bottom: 2px;
}
#author div.social {
margin-top: 15px;
}
.prof-sm {
position: absolute;
list-style: none;
padding: 0;
margin: 0;
top: 5px;
right: -11px;
width: 40px;
}
.prof-sm .sm {
width: 40px;
height: 40px;
margin-bottom: 4px;
border-radius: 50%;
background: #f7f7f7;
transition: all 0.15s ease-in-out;
box-shadow: 0 0.5px 2px rgb(0 0 0 / 24%), 0 0.5px 3px rgb(0 0 0 / 12%);
}
.prof-sm svg {
width: 30px;
height: 30px;
margin: 5px;
border-radius: 50%;
}
.prof-sm a {
display: inline-block;
height: 40px;
width: 40px;
border-radius: 50%;
}
/* zinothec Buttons */
a.btn{margin:.375rem;font-weight:400;color:inherit;text-align:center;vertical-align:middle;text-transform:uppercase;word-wrap:break-word;white-space:normal;cursor:pointer;border:0;border-radius:4px;-webkit-box-shadow:0 1px 3px rgba(0,0,0,0.12),0 1px 2px rgba(0,0,0,0.24);box-shadow:0 1px 3px rgba(0,0,0,0.12),0 1px 2px rgba(0,0,0,0.24);-webkit-transition:color .15s ease-in-out,background-color .15s ease-in-out,border-color .15s ease-in-out,-webkit-box-shadow .15s ease-in-out;transition:color .15s ease-in-out,background-color .15s ease-in-out,border-color .15s ease-in-out,-webkit-box-shadow .15s ease-in-out;transition:color .15s ease-in-out,background-color .15s ease-in-out,border-color .15s ease-in-out,box-shadow .15s ease-in-out;transition:color .15s ease-in-out,background-color .15s ease-in-out,border-color .15s ease-in-out,box-shadow .15s ease-in-out,-webkit-box-shadow .15s ease-in-out;padding:.75rem 2.14rem;font-size:.81rem}
a.btn:hover,a.btn:focus,a.btn:active{outline:0;-webkit-box-shadow:0 3px 6px rgba(0,0,0,0.16),0 3px 6px rgba(0,0,0,0.23);box-shadow:0 3px 6px rgba(0,0,0,0.16),0 3px 6px rgba(0,0,0,0.23)}
a.btn-primary{color:#fff;background-color:#1E88E5}
a.btn-primary:hover{color:#fff;background-color:#2196F3}
a.btn-default{color:#fff;background:linear-gradient( 315deg,#2672db,#6a5acd,#19bfe5)}
a.btn-default:hover{color:#fff;background-color:#80CBC4}
a.btn-success{color:#fff;background-color:#00C853}
a.btn-success:hover{color:#fff;background-color:#00E676}
a.btn-danger{color:#fff;background-color:#FF1744}
a.btn-danger:hover{color:#fff;background-color:#FF5252}
a.btn-warning{color:#fff;background-color:#FFC400}
a.btn-warning:hover{color:#fff;background-color:#FFD740}
a.btn-info{color:#fff;background-color:#33b5e5}
a.btn-info:hover{color:#fff;background-color:#00B0FF}
a.btn-light{color:#212121;background-color:#E0E0E0}
a.btn-light:hover{color:#212121;background-color:#EEEEEE;border-color:#EEEEEE}
a.btn-dark{color:#FAFAFA;background-color:#212121}
a.btn-dark:hover{color:#FAFAFA;background-color:#424242;border-color:#424242}
a.btn-link{color:#000;background-color:transparent;-webkit-box-shadow:none;box-shadow:none}
a.btn.btn-link:hover{box-shadow:unset;text-decoration:underline}
a.btn-elegant{color:#fff;background-color:#616161}
a.btn-elegant:hover{color:#fff;background-color:#757575}
a.btn-unique{color:#fff;background-color:#880E4F}
a.btn-unique:hover{color:#fff;background-color:#AD1457}
a.btn-pink{color:#fff;background-color:#E91E63}
a.btn-pink:hover{color:#fff;background-color:#EC407A}
a.btn-purple{color:#fff;background-color:#9C27B0}
a.btn-purple:hover{color:#fff;background-color:#AB47BC}
a.btn-deep-purple{color:#fff;background-color:#673AB7}
a.btn-deep-purple:hover{color:#fff;background-color:#7E57C2}
a.btn-indigo{color:#fff;background-color:#fc1264}
a.btn-indigo:hover{color:#fff;background-color:#5C6BC0}
a.btn-light-blue{color:#fff;background-color:#2196F3}
a.btn-light-blue:hover{color:#fff;background-color:#42A5F5}
a.btn-cyan{color:#fff;background-color:#00BCD4}
a.btn-cyan:hover{color:#fff;background-color:#26C6DA}
a.btn-dark-green{color:#fff;background-color:#4CAF50}
a.btn-dark-green:hover{color:#fff;background-color:#66BB6A}
a.btn-light-green{color:#fff;background-color:#8BC34A}
a.btn-light-green:hover{color:#fff;background-color:#9CCC65}
a.btn-zn{color:#fff;background-color:#3d5afe}
a.btn-zn:hover{color:#fff;background-color:#3d5afe}
a.btn-amber{color:#fff;background-color:#FFC107}
a.btn-amber:hover{color:#fff;background-color:#FFCA28}
a.btn-deep-orange{color:#fff;background-color:#FF5722}
a.btn-deep-orange:hover{color:#fff;background-color:#FF7043}
a.btn-brown{color:#fff;background-color:#795548}
a.btn-brown:hover{color:#fff;background-color:#8D6E63}
a.btn-blue-grey{color:#fff;background-color:#607D8B}
a.btn-blue-grey:hover{color:#fff;background-color:#78909C}
.peach-gradient{background:linear-gradient(40deg,#E65100,#FFA000)!important}
.purple-gradient{background:linear-gradient(40deg,#4527A0,#7B1FA2)!important}
.blue-gradient{background:linear-gradient(40deg,#2962FF,#3949AB)!important}
.aqua-gradient{background:linear-gradient(40deg,#0097A7,#CCFF90)!important}
.btn.peach-gradient,.btn.purple-gradient,.btn.blue-gradient,.btn.aqua-gradient{color:#fff;-webkit-transition:.5s ease;transition:.5s ease}
a.btn-outline-primary{color:#4285f4!important;background-color:transparent!important;border:2px solid #4285f4!important}
a.btn[class*=&quot;btn-outline-&quot;]{padding-top:.7rem;padding-bottom:.7rem}
a.btn-outline-default{color:#3d5afe!important;background-color:transparent!important;border:2px solid #3d5afe!important}
a.btn-outline-secondary{color:#E040FB!important;background-color:transparent!important;border:2px solid #E040FB!important}
a.btn-outline-success{color:#00C853!important;background-color:transparent!important;border:2px solid #00C853!important}
a.btn-outline-info{color:#33b5e5!important;background-color:transparent!important;border:2px solid #33b5e5!important}
a.btn-outline-warning{color:#FFC400!important;background-color:transparent!important;border:2px solid #FFC400!important}
a.btn-outline-danger{color:#FF1744!important;background-color:transparent!important;border:2px solid #FF1744!important}
a.btn-rounded{border-radius:99em}
a.btn.btn-flat{font-weight:500;color:inherit;background-color:transparent;-webkit-box-shadow:none;box-shadow:none}
a.btn.btn-lg{padding:.4rem 2.426rem;font-size:.94rem}
a.btn.btn-sm{padding:.5rem 1.6rem;font-size:.64rem}
a.btn.btn-block{display:block;width:100%;margin:inherit}
.btn-block+.btn-block{margin-top:.75rem!important}
.mb-1,.my-1{margin-bottom:.25rem!important}
a.btn-primary:not([disabled]):not(.disabled).active{background-color:#01579B!important;-webkit-box-shadow:0 3px 6px rgba(0,0,0,0.16),0 3px 6px rgba(0,0,0,0.23);box-shadow:0 3px 6px rgba(0,0,0,0.16),0 3px 6px rgba(0,0,0,0.23)}
a.btn-default:not([disabled]):not(.disabled).active{backgroundlinear-gradient( 315deg,#2672db,#6a5acd,#19bfe5):#004D40!important;-webkit-box-shadow:0 3px 6px rgba(0,0,0,0.16),0 3px 6px rgba(0,0,0,0.23);box-shadow:0 3px 6px rgba(0,0,0,0.16),0 3px 6px rgba(0,0,0,0.23)}
button, button[disabled]:active {
border: none;
font-size: 12px;
font-weight: normal;
font-family: Cairo;
border-radius: 3px;
padding: 6px 10px;
text-decoration: none;
margin: 3px;
background: #3d5afe;
color: #fff;
display: inline-block;
transition: all 0.5s linear;
cursor: pointer;
}
samp {
font-size: 1em;
}
kbd, samp, var, code {
display: inline-block;
direction: ltr;
text-align: left;
font: 400 14px ;
padding: 2px 5px;
margin: 0px 5px;
width: auto;
white-space: pre-wrap;
word-wrap: break-word;
font-weight: normal;
background-color: rgba(69,90,99,.12);
color: #455A63;
}
samp {
border: 1px solid rgba(69,90,99,.12)
}
.r-bend-3, samp, code {
-webkit-border-radius:3px;
-moz-border-radius:3px;
-ms-border-radius:3px;
-o-border-radius:3px;
border-radius:3px;
}
/*============================
aaaa
============================*/
.materialize input:not([type]),
.materialize input[type=text]:not(.browser-default),
.materialize input[type=password]:not(.browser-default),
.materialize input[type=email]:not(.browser-default),
.materialize input[type=url]:not(.browser-default),
.materialize input[type=time]:not(.browser-default),
.materialize input[type=date]:not(.browser-default),
.materialize input[type=datetime]:not(.browser-default),
.materialize input[type=datetime-local]:not(.browser-default),
.materialize input[type=tel]:not(.browser-default),
.materialize input[type=number]:not(.browser-default),
.materialize input[type=search]:not(.browser-default),
.materialize textarea {
display: block;
padding: 0 15px;
margin: 0;
border: none;
height: 55px;
line-height: 55px;
background: transparent;
color: #989898;
max-width: 100%;
border: 2px solid #eeeeee;
-webkit-box-shadow: none;
box-shadow: none;
-webkit-transition: border .3s, -webkit-box-shadow .3s;
transition: border .3s, -webkit-box-shadow .3s;
transition: box-shadow .3s, border .3s;
transition: box-shadow .3s, border .3s, -webkit-box-shadow .3s;
width: 100%;
border-radius: 5px;
-o-border-radius: 5px;
-ms-border-radius: 5px;
-moz-border-radius: 5px;
-webkit-border-radius: 5px;
}
.materialize input[type=text]:not(.browser-default):focus,
.materialize input[type=password]:not(.browser-default):focus,
.materialize input[type=email]:not(.browser-default):focus,
.materialize input[type=url]:not(.browser-default):focus,
.materialize input[type=tel]:not(.browser-default):focus,
.materialize input[type=search]:not(.browser-default):focus,
.materialize textarea:focus {
border-color: #3d5afe;
color: #464646;
}
.materialize input[type=url]:not(.browser-default) {
direction: ltr;
text-align: left;
font: 14px 'Consolas','Monaco',monospace,Courier,Courier New;
}
/*input field*/
.materialize .input-field {
float:none;
position:relative;
margin:10px 20px 30px;
min-height: 55px;
}
.materialize .input-field label {
position: relative;
overflow: hidden;
display: block;
color:#aaaaaa;
margin-bottom: 5px;
}
.materialize .input-field i, .materialize .input-field svg {
vertical-align: middle;
}
.materialize .input-field input[type=text]:disabled {
color: #989898;
}
.materialize .input-field input[type].err {
border-color: #ffe9d3;
}
.materialize .input-field input[type].scs {
border-color: #388d80;
}
.materialize .input-field input[type].wrg {
border-color: #ffd3d3;
}
/*checkbox*/
.materialize input[type=checkbox] {
background: #ffffff;
border: 2px solid #5a5a5a;
-webkit-border-radius: 1px;
-moz-border-radius: 1px;
-ms-border-radius: 1px;
-o-border-radius: 1px;
border-radius: 1px;
-webkit-transition: .2s;
transition: .2s;
width: 20px;
height: 20px;
cursor: pointer;
display: inline-block;
position: relative;
margin-right: 0.5rem;
z-index: 1;
vertical-align: middle;
outline: none;
-webkit-appearance: none;
-moz-appearance: none;
-ms-appearance: none;
-o-appearance: none;
appearance: none;
}
.materialize input[type=checkbox]:checked {
background-color: #3d5afe;
border-color: #3d5afe;
-webkit-transform-origin: 100% 100%;
transform-origin: 100% 100%;
}
.materialize input[type=checkbox]:checked::before {
content: '';
top: 0;
left: 0;
width: 8px;
height: 13px;
border-top: 2px solid transparent;
border-left: 2px solid transparent;
border-right: 2px solid #fff;
border-bottom: 2px solid #fff;
-webkit-transform: rotateZ(37deg);
transform: rotateZ(37deg);
-webkit-transform-origin: 100% 100%;
transform-origin: 100% 100%;
position: absolute;
text-align: center;
line-height: 20px;
display: flex;
display: -webkit-flex;
justify-content: center;
align-items: center;
}
]]></b:skin>

  
<b:if cond='data:skin.vars.disaplelastposts == &quot;2px&quot;'><style>.home.lapel div#Tempnec {display: none !important;}.mopspeed.home.lapel div#Tempnec { display: block !important; }</style></b:if>
      
<b:if cond='data:skin.vars.disapledarck == &quot;2px&quot;'><style>.buttonsupandlh [onclick=&quot;darkMode()&quot;], li.dark-link {display: none;}</style></b:if>
      
<b:if cond='data:skin.vars.Style2Headr == &quot;2px&quot;'><style>.par-tp {max-width: 100%;overflow: hidden;}.open.nav1, .search {top: -5px;}div#top-social-L{margin-left: 0}body.ltr div#top-social-L{margin-right: 0}nav.nav-par{position:relative;top:-19px}.par-bottm{top:70px}header#sp-header{height:127px}.head-pz{height:127px}.floar:before{width:100%;transform:none;border-radius:0}.floar{width:100%}@media screen and (max-width:992px){.head-pz {height: 97px;}header#sp-header {height: 97px;}.par-bottm {top: 35px;}}</style></b:if>

<b:if cond='data:skin.vars.RemoveAuthor == &quot;2px&quot;'><style>.items a.author, .items span.fn, .post-meta .article-author, .author-profile,.Blog .author-posts {display: none !important;}</style></b:if>

<b:if cond='data:skin.vars.StykiHeadr == &quot;2px&quot;'><style id='StopSitkyHeadar'>.head-pz,.par-bottm,.par-tp{position:absolute}</style></b:if>

<b:if cond='data:skin.vars.Remove3nwanshreetMopile == &quot;2px&quot; and data:blog.isMobileRequest'>
  <style>@media screen and (max-width:860px){#shreeta5bar .headline .title {font-size: 0;padding: 0 20px 0 35px;}}</style>
</b:if>
  
<b:if cond='data:skin.vars.RemoveAdiseHome == &quot;2px&quot;'><b:if cond='data:view.isMultipleItems'><style>.r-r {float: none;width: 100%;}aside#sidepar-wid {display: none;}</style></b:if></b:if>

<b:if cond='data:skin.vars.RemoveAdisePost == &quot;2px&quot;'><b:if cond='data:view.isPost'><style>.r-r {float: none;width: 100%;}aside#sidepar-wid {display: none;}</style></b:if></b:if>

<b:if cond='data:skin.vars.RemoveAdisePage == &quot;2px&quot;'><b:if cond='data:view.isPage'><style>.r-r {float: none;width: 100%;}aside#sidepar-wid {display: none;}</style></b:if></b:if>

<b:if cond='data:skin.vars.StykiAdise == &quot;2px&quot;'><style id='StikySidepar'/></b:if>

<b:if cond='data:skin.vars.StopCopying == &quot;2px&quot;'><style> body * {user-select: none !important;}blockquote,blockquote * {user-select: text !important;}</style></b:if>

<b:if cond='data:skin.vars.CoverImg == &quot;1px&quot;'><style>.thumb img,img.post-thumbnail,.post-random a.reimage img, img.post-thumbnail {object-fit: initial;}</style></b:if>

<b:if cond='data:skin.vars.BlogFonts'>
	<b:if cond='data:skin.vars.BlogFonts == &quot;1px&quot;'>
      <style>/*<![CDATA[*/
/* arabic */
@font-face {
  font-family: 'Tajawal';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: local('Tajawal Medium'), local('Tajawal-Medium'), url(https://fonts.gstatic.com/s/tajawal/v3/Iurf6YBj_oCad4k1l8KiHrRpiYlJ.woff2) format('woff2');
  unicode-range: U+0600-06FF, U+200C-200E, U+2010-2011, U+204F, U+2E41, U+FB50-FDFF, U+FE80-FEFC;
}
/* latin */
@font-face {
  font-family: 'Tajawal';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: local('Tajawal Medium'), local('Tajawal-Medium'), url(https://fonts.gstatic.com/s/tajawal/v3/Iurf6YBj_oCad4k1l8KiHrFpiQ.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
/* arabic */
@font-face {
  font-family: 'Tajawal';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: local('Tajawal Bold'), local('Tajawal-Bold'), url(https://fonts.gstatic.com/s/tajawal/v3/Iurf6YBj_oCad4k1l4qkHrRpiYlJ.woff2) format('woff2');
  unicode-range: U+0600-06FF, U+200C-200E, U+2010-2011, U+204F, U+2E41, U+FB50-FDFF, U+FE80-FEFC;
}
/* latin */
@font-face {
  font-family: 'Tajawal';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: local('Tajawal Bold'), local('Tajawal-Bold'), url(https://fonts.gstatic.com/s/tajawal/v3/Iurf6YBj_oCad4k1l4qkHrFpiQ.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
body *{font-family: 'Tajawal', sans-serif!important}
@media screen and (max-width:992px){
#shreeta5bar .headline .title {
    padding-top: 2px;
}
a.Lapel-Link, .headline .title {
    padding-top: 2px !important;
}
.post-outer .moreLink, .Sp-Normal .posts .moreLink {
    padding-top: 9px !important;
}
.titlewrapper .title {width: auto;top: 15px;}

}
.post-body h1, .post-body h2, .post-body h3, .post-body h4 {
    font-family: 'Tajawal' !important;
}
/*]]>*/</style>
  	</b:if>
	<b:if cond='data:skin.vars.BlogFonts == &quot;2px&quot;'>
      <style>/*<![CDATA[*/
@import url('https://fonts.googleapis.com/css2?family=Cairo&display=swap');
  body *{font-family: 'Cairo', sans-serif!important}
.shareButton .icon{margin-top:4px}
li.item.targetitem span.icon{margin-top:3px}
div#pages{margin:6px 0}
a.op-one svg{margin-top:-2px}
.loadMore .loadMorePosts a:before,.noMorePosts:before,div#loader:before{bottom:6px}
svg.icon-load{bottom:7px}
.Lapel-Link:hover:before{top:10px}
.post-body h1, .post-body h2, .post-body h3, .post-body h4 {
    font-family: 'Cairo' !important;
}
/*]]>*/</style>
  	</b:if>
	<b:if cond='data:skin.vars.BlogFonts == &quot;3px&quot;'>
      <style>/*<![CDATA[*/
@import url('https://fonts.googleapis.com/css2?family=Changa&display=swap');
  body *{font-family: 'Changa', sans-serif !important}
.shareButton .icon{margin-top:4px}
li.item.targetitem span.icon{margin-top:3px}
div#pages{margin:6px 0}
a.op-one svg{margin-top:-2px}
.loadMore .loadMorePosts a:before,.noMorePosts:before,div#loader:before{bottom:6px}
svg.icon-load{bottom:7px}
.Lapel-Link:hover:before{top:10px}
.post-body h1, .post-body h2, .post-body h3, .post-body h4 {
    font-family: 'Changa' !important;
}
/*]]>*/</style>
  	</b:if>
	<b:if cond='data:skin.vars.BlogFonts == &quot;4px&quot;'>
      <style>/*<![CDATA[*/
@import url('https://fonts.googleapis.com/css2?family=El+Messiri&display=swap');
  body *{font-family: 'El Messiri', sans-serif!important}
@media screen and (max-width:992px){
#shreeta5bar .headline .title {
    padding-top: 2px;
}
a.Lapel-Link, .headline .title {
    padding-top: 2px !important;
}
.post-outer .moreLink, .Sp-Normal .posts .moreLink {
    padding-top: 9px !important;
}
.titlewrapper .title {width: auto;top: 15px;}

}
.post-body h1, .post-body h2, .post-body h3, .post-body h4 {
    font-family: 'El Messiri' !important;
}
/*]]>*/</style>
  	</b:if>
	<b:if cond='data:skin.vars.BlogFonts == &quot;5px&quot;'>
      <style>/*<![CDATA[*/
/* arabic */
@font-face {
  font-family: 'Almarai';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: local('Almarai'), local('Almarai-Regular'), url(https://fonts.gstatic.com/s/almarai/v4/tsstApxBaigK_hnnQ1iFo0C3.woff2) format('woff2');
  unicode-range: U+0600-06FF, U+200C-200E, U+2010-2011, U+204F, U+2E41, U+FB50-FDFF, U+FE80-FEFC;
}
/* arabic */
@font-face {
  font-family: 'Almarai';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: local('Almarai Bold'), local('Almarai-Bold'), url(https://fonts.gstatic.com/s/almarai/v4/tssoApxBaigK_hnnS-agtnqWo572.woff2) format('woff2');
  unicode-range: U+0600-06FF, U+200C-200E, U+2010-2011, U+204F, U+2E41, U+FB50-FDFF, U+FE80-FEFC;
}
  body *{font-family: 'Almarai', sans-serif!important}
.Sp-slide .posts:not(.postnum0) .rnav-title{
    height: 43px !important;
}
.post-body h1, .post-body h2, .post-body h3, .post-body h4 {
    font-family: 'Almarai' !important;
}
/*]]>*/</style>
	</b:if>
	<b:if cond='data:skin.vars.BlogFonts == &quot;6px&quot;'>
      <style>/*<![CDATA[*/
  body *{font-family: tahoma!important}
.shareButton a {
    width: calc((100% - 50px) / 6);
}
@media screen and (max-width:720px){
.shareButton a{width:calc((100% - 24px) / 3)}
}
@media screen and (max-width:360px){
.shareButton a{width:calc((100% - 11px) / 2);margin-right:0!important}
}
.post-body h1, .post-body h2, .post-body h3, .post-body h4 {
    font-family: tahoma !important;
}
/*]]>*/</style>
	</b:if>
  	<b:if cond='data:skin.vars.BlogFonts == &quot;7px&quot;'>
      <style>/*<![CDATA[*/
  body *{font-family: monospace!important}
.post-body h1, .post-body h2, .post-body h3, .post-body h4 {
    font-family: monospace !important;
}
/*]]>*/</style>
	</b:if>
</b:if>
</b:if>
  <b:if cond='data:view.isLayoutMode'>
    <!-- Layout Skin -->
    <b:template-skin><![CDATA[
body#layout{margin:auto;background:#efefef;min-height:100%;direction:rtl;padding:0 10px}
body#layout .rtl{direction:rtl}
body#layout .ltr{direction:ltr}
body#layout .clear{height:1px;clear:both;display:block;width:100%}
body#layout .section .widget-content{border-radius:2px;min-height:20px}
body#layout .draggable-widget .widget-wrap3{background:none}
body#layout .section h4{display:none}
body#layout div.layout-title{color:#000;font-weight:700;font-size:13px}
body#layout .rtl div.layout-title{text-align:right;}
body#layout .ltr div.layout-title{text-align:left;}
.layout-widget-description{display:none}
body#layout div.section,header#sp-header,.contpotg,footer{background: #fff !important;overflow:hidden!important;padding:50px 15px 15px!important;border:1px solid rgba(32,33,36,0.07)!important;border-radius:2px!important;margin:15px 0!important;position:relative}
body#layout .add-icon,body#layout .layout-widget-state,body#layout .editlink.icon{background-position:center;background-repeat:no-repeat;height:24px;width:24px}
body#layout .widget-content a:hover{background-color:#ccc;color:#000;transition:.4s ease-out}
body#layout .editlink.icon{font-size:0;line-height:0;position:absolute;right:16px;top:16px}
body#layout .widget-content a{color:#4c4c4c!important;padding:3px 10px;background-color:#e0e0e0;border-radius:5px}
body#layout .locked-widget .widget-content{font-weight:700;text-align:center}
.mid-top-footer .footer-col{width:33%;display:inline-block}
.bocker{display:block;overflow:hidden;clear:both}
aside#sidepar-wid{float:left;width:35%;margin-right:10px}
.bocker .r-r{width:64%;float:right}
.sides{display:inline-block;width:49.5%}
#Label400{display:none}
body#layout .Blog .widget-content {height: auto !important;}
div#sittings .widget{margin:0 0 1px 1px!important;float:right!important;width:361px!important}
div#LinkList2{border:1px solid #eee}
body#layout #menu:before,body#layout #logo:before,body#layout #top-social-L:before,body#layout #pages:before,body#layout #menu:after,body#layout #logo:after,body#layout #top-social-L:after,body#layout #pages:after,body#layout .potg:before,body#layout .potg:after,body#layout footer div.section:after,body#layout footer div.section:before{display:none!important}
body#layout #menu,body#layout #logo,body#layout #top-social-L,body#layout #pages,body#layout .contpotg div.section,body#layout footer div.section{padding:0!important;margin:0!important;border-radius:0!important}
header#sp-header,body#layout .contpotg,footer{background:#fff}
.head-pz div.section {margin: 0 0 1px 1px !important;float: right !important;width: 49.5% !important;}
a.editlink {line-height: 2em!important;height: 24px;width: 24px;position: absolute !important;right: 16px !important;top: 16px;}
body#layout header#sp-header div.section > div{margin-top:0!important}
body#layout .contpotg div.section,body#layout footer div.section{border:0!important}
body#layout div.section:after,header#sp-header:after,body#layout .contpotg:after,body#layout footer:after{content:"";height:2px;width:100%;background:#eee;display:block;position:absolute;top:30px;right:-10px}
body#layout div.section:before,header#sp-header:before,body#layout .contpotg:before,body#layout footer:before{background:$(keycolor);color:#fff;padding:7px 35px;border-radius:30px;position:absolute;top:15px;right:15px;z-index:999;font-family:'Segoe UI'}
div#Blog1:before{content:"";display:block;position:absolute;width:130%;height:15px;background:#ececec;right:-20px;top:75px;left:0}
div#HTML200:before{content:"";height:2px;width:1050px;background:#eee;display:block;position:absolute;top:-30px;right:-30px}
div#HTML200:after{background:$(keycolor);color:#fff;padding:7px 35px;border-radius:30px;position:absolute;top:-45px;right:0;z-index:999;font-family:'Segoe UI';content:"منطقة  الاعلانات"}
body#layout .trelists.section {display: inline-block;width: 29.5%;padding-top: 10px !important;border-top: 0 !important;border-left: 0 !important;}
body#layout .trelists.section:after,div#BotPostsc:after{display:none!important}
body#layout div#Postnw4,body#layout div#Postnw5,body#layout div#Postnw6{border-top:1px solid #eee!important;padding-top:60px!important}
body#layout div#Postnw4:after,body#layout div#Postnw5:after,body#layout div#Postnw6:after{display:block!important}
body#layout div#BotPostsc{    margin-top: -15px !important;padding-top:15px!important}
body#layout div.widget {border: 1px solid #eee;}
body#layout .dr_active:before{content:'\افلت هُنا';font-size:30px;padding-top:25px;display:block;font-weight:700}
body#layout .dr_active{height:50px!important;background-color:transparent;border:1px dashed $(keycolor);color:#111;margin-bottom:30px;top:20px;border-radius:2px}
#sittings:before{content:"الإعدادت"!important}
#sp-header:before{content:"القائمة  العلوية"!important}
#TopPost-sc:before,body#layout div#Postnw4:before,.contpotg:before{content:"منطقة  التدوينات  الاضافية"!important}
div#sidepar:before{content:"القائمة  الجانبية"!important}
div#shreeta5bar:before{content:"شريط  الاخبار"!important}
div#Tempnec:before{content:"منطقة  التدوينات  الأساسية"!important}
footer:before{content:"ذيل  المدونة  (الفوتر)"!important}
#Topa3lan-sc:before{content:"إعلان  القائمة  العلوية[pc]"!important}
#Topa3lan-sc2:before{content:"إعلان  القائمة  العلوية[mopile]"!important}
body#layout:before {z-index: 99;content: "معلومات واضحة";text-align: center;position: absolute;right: 10px;top: 10px;background: $(keycolor);font-weight: bold;color: #fff;padding: 10px 15px;border-radius: 3px;}
div#BotPostsc,#Tempnec,.mid-top-footer,div#TopPost-sc,header#sp-header,div#Postcs1,div#Postcs4,div#Postcs8,div#Postcs5,.contpotg,.Treelists,div#LinkList2,footer {display: block;overflow: hidden;clear: both;}
body#layout .widget-content {background: #fff;}
header#sp-header {margin-top: 60px !important;}
div#PostAds .HTML {width: 49% !important;float: right !important;clear: none;margin-left: 0.5% !important;}
body#layout div.section:before, header#sp-header:before, body#layout .contpotg:before, body#layout footer:before, body#layout:before {background: #3560ab;}
div#Topa3lan-sc2, div#Topa3lan-sc {width: 46%;display: inline-block !important;}
body#layout div#TopPost-sc {margin-bottom: -15px !important;}
div#nav-widget {display: none;}
    ]]></b:template-skin>  
  </b:if>
  <b:defaultmarkups>
	<b:defaultmarkup type='Common'>
    <b:includable id='DefaultMeta'>
      <meta content='text/html; charset=UTF-8' http-equiv='Content-Type'/>
<meta content='width=device-width, initial-scale=1.0, shrink-to-fit=no' name='viewport'/>
      <link expr:href='data:view.url.canonical' rel='canonical'/>
      <meta expr:content='data:view.description.escaped' name='description'/>
      <link expr:href='data:blog.blogspotFaviconUrl' rel='icon' type='image/x-icon'/>
      <meta content='IE=edge' http-equiv='X-UA-Compatible'/>
      <meta content='blogger' name='generator'/>
      <meta expr:content='data:skin.vars.body_background_color' name='theme-color'/>
      <meta expr:content='data:skin.vars.body_background_color' name='msapplication-navbutton-color'/>
      <meta expr:content='data:blog.blogId' name='BlogId'/>
      <b:eval expr='data:blog.openIdOpTag'/>
      <b:if cond='data:view.featuredImage'>
        <link expr:href='data:view.featuredImage' rel='image_src'/>
        <b:else/>&lt;link href=&#39;<b:include name='MetaImage'/>&#39; rel=&#39;image_src&#39;/&gt;
      </b:if>
      <!--[if IE]><script type='text/javascript'>(function(){var html5=("abbr,article,aside,audio,canvas,datalist,details,"+"figure,footer,header,hgroup,mark,menu,meter,nav,output,"+"progress,section,time,video").split(',');for(var i=0;i<html5.length;i++){document.createElement(html5[i])}try{document.execCommand('BackgroundImageCache',false,true)}catch(e){}})()</script><![endif]-->
    </b:includable>
    <b:includable id='OpenGraph'>
      <meta expr:content='data:blog.localeUnderscoreDelimited == &quot;ar&quot; ? &quot;ar_AR&quot; : data:blog.localeUnderscoreDelimited' property='og:locale'/>
      <meta expr:content='data:view.url.canonical' property='og:url'/>
      <meta expr:content='data:view.title.escaped' property='og:title'/>
      <meta expr:content='data:blog.title.escaped' property='og:site_name'/>
      <meta expr:content='data:view.description.escaped' property='og:description'/>
      <meta expr:content='data:view.title.escaped' property='og:image:alt'/>
      <b:if cond='data:view.isMultipleItems'><meta content='website' property='og:type'/>
        <b:elseif cond='data:view.isSingleItem'/><meta content='article' property='og:type'/>
      </b:if>
      <b:if cond='data:view.featuredImage'>
        <meta expr:content='resizeImage(data:view.featuredImage, 1200, &quot;1200:630&quot;)' property='og:image'/>
        <b:else/>&lt;meta content=&#39;<b:include name='MetaImage'/>&#39; property=&#39;og:image&#39;/&gt;</b:if>
    </b:includable>
    <b:includable id='TwitterCard'>
      <meta content='summary_large_image' name='twitter:card'/>
      <meta expr:content='data:blog.homepageUrl' name='twitter:domain'/>
      <meta expr:content='data:view.description.escaped' name='twitter:description'/>
      <meta expr:content='data:view.title.escaped' name='twitter:title'/>
      <b:if cond='data:view.featuredImage'>
        <meta expr:content='resizeImage(data:view.featuredImage, 1200, &quot;1200:630&quot;)' name='twitter:image'/>
        <b:else/>&lt;meta content=&#39;<b:include name='MetaImage'/>&#39; name=&#39;twitter:image&#39;/&gt;</b:if>
    </b:includable>
    <b:includable id='DNSPrefetech'>
      <link href='https://www.blogger.com' rel='dns-prefetch'/><link href='https://script.google.com' rel='dns-prefetch'/><link href='https://fonts.gstatic.com' rel='dns-prefetch'/><link href='https://fonts.googleapis.com' rel='dns-prefetch'/><link href='https://1.bp.blogspot.com' rel='dns-prefetch'/><link href='https://2.bp.blogspot.com' rel='dns-prefetch'/><link href='https://3.bp.blogspot.com' rel='dns-prefetch'/><link href='https://4.bp.blogspot.com' rel='dns-prefetch'/><link href='https://pagead2.googlesyndication.com' rel='dns-prefetch'/><link href='https://accounts.google.com' rel='dns-prefetch'/><link href='https://resources.blogblog.com' rel='dns-prefetch'/><link href='https://www.google.com' rel='dns-prefetch'/><link href='https://connect.facebook.net' rel='dns-prefetch'/><link href='https://www.facebook.com' rel='dns-prefetch'/>
    </b:includable>
    <b:includable id='widget-title'>
      <b:if cond='data:widget.sectionId == &quot;Postcs1&quot; or data:widget.sectionId == &quot;Postcs2&quot; or data:widget.sectionId == &quot;Postcs3&quot; or data:widget.sectionId == &quot;Postcs4&quot; or data:widget.sectionId == &quot;Postcs5&quot; or data:widget.sectionId == &quot;Postcs6&quot; or data:widget.sectionId == &quot;Postcs7&quot; or data:widget.sectionId == &quot;Postcs8&quot; or data:widget.sectionId == &quot;TopPost-sc&quot; or data:widget.sectionId == &quot;BotPostsc&quot;'>

<b:if cond='data:title.length gt 0'><div class='headline' expr:data-title='data:title.escaped'><h3 class='title'><data:title/></h3><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><b:if cond='data:title contains &quot;[LastPost]&quot;'><a class='Lapel-Link' expr:href='data:blog.canonicalHomepageUr + &quot;/search/&quot;'><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
Show more
<b:else/>
عرض المزيد
</b:if></a><b:else/><a class='Lapel-Link' expr:href='data:blog.canonicalHomepageUr + &quot;/search/label/&quot; + data:label.name'><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
Show more
<b:else/>
عرض المزيد
</b:if></a></b:if></b:if></b:loop></div></b:if>

<b:elseif cond='data:widget.sectionId == &quot;Postnw1&quot; or data:widget.sectionId == &quot;Postnw2&quot; or data:widget.sectionId == &quot;Postnw3&quot; or data:widget.sectionId == &quot;Postnw4&quot; or data:widget.sectionId == &quot;Postnw5&quot; or data:widget.sectionId == &quot;Postnw6&quot;'/>
<b:if cond='data:title.length gt 0'><div class='headline' expr:data-title='data:title.escaped'><h3 class='title'><data:title/></h3><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><b:if cond='data:title contains &quot;[LastPost]&quot;'><a class='Lapel-Link' expr:href='data:blog.canonicalHomepageUr + &quot;/search/&quot;'><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
Show more
<b:else/>
عرض المزيد
</b:if></a><b:else/><a class='Lapel-Link' expr:href='data:blog.canonicalHomepageUr + &quot;/search/label/&quot; + data:label.name'><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
Show more
<b:else/>
عرض المزيد
</b:if></a></b:if></b:if></b:loop></div></b:if>
        <b:else/>
      <b:if cond='data:title.length gt 0'><div class='headline' expr:data-title='data:title.escaped'><h3 class='title'><data:title/></h3></div></b:if>
    </b:if>
    </b:includable>
    <b:includable id='contactUsJs'>
<b:if cond='data:view.isPage'>
<b:tag name='script' type='text/javascript'>
if($(&quot;#Pagecontactus&quot;).length){
$.getScript(&quot;https://www.blogger.com/static/v1/widgets/2227587253-widgets.js&quot;)
.done(function() {
<b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
$htmlcontact = &quot;<div id='contact-form'><form name='contact-form'><input class='contact-form-name' id='ContactForm1_contact-form-name' name='name' placeholder='name *' size='30' type='text' value=''/><input class='contact-form-email' id='ContactForm1_contact-form-email' name='email' placeholder='e-mail *' size='30' type='text' value=''/><textarea class='contact-form-email-message' cols='25' id='ContactForm1_contact-form-email-message' name='email-message' placeholder='message *' rows='5'/><input id='ContactForm1_contact-form-submit' type='button' value='Send your message'/>  <div style='text-align: center;'><div id='ContactForm1_contact-form-error-message'/><div id='ContactForm1_contact-form-success-message'/></div></form></div>&quot;;
$(&#39;#Pagecontactus&#39;).append($htmlcontact)
_WidgetManager._Init(&#39;&#39;);_WidgetManager._RegisterWidget(&#39;_ContactFormView&#39;, new _WidgetInfo(&#39;ContactForm1&#39;, &#39;contact-sec&#39;, null, document.getElementById(&#39;ContactForm1&#39;), {&#39;contactFormMessageSendingMsg&#39;: &#39;Sending ...&#39;, &#39;contactFormMessageSentMsg&#39;: &#39;Your message has been sent.&#39;, &#39;contactFormMessageNotSentMsg&#39;: &#39;The message could not be sent , please try again at a later time.&#39;, &#39;contactFormInvalidEmailMsg&#39;: &#39;A valid email address is required.&#39;, &#39;contactFormEmptyMessageMsg&#39;: &#39;Message field cannot be empty&#1611;ا.&#39;, &#39;title&#39;: &#39;Contact form&#39;, &#39;blogId&#39;: &#39;<data:blog.blogId/>&#39;, &#39;contactFormNameMsg&#39;: &#39;name&#39;, &#39;contactFormEmailMsg&#39;: &#39;e-mail&#39;, &#39;contactFormMessageMsg&#39;: &#39;Message&#39;, &#39;contactFormSendMsg&#39;: &#39;send&#39;, &#39;submitUrl&#39;: &#39;https://www.blogger.com/contact-form.do&#39;}, &#39;displayModeFull&#39;));})}
<b:else/>
$htmlcontact = &quot;<div id='contact-form'><form name='contact-form'><input class='contact-form-name' id='ContactForm1_contact-form-name' name='name' placeholder='الاسم *' size='30' type='text' value=''/><input class='contact-form-email' id='ContactForm1_contact-form-email' name='email' placeholder='بريد إلكتروني *' size='30' type='text' value=''/><textarea class='contact-form-email-message' cols='25' id='ContactForm1_contact-form-email-message' name='email-message' placeholder='الرسالة *' rows='5'/><input id='ContactForm1_contact-form-submit' type='button' value='إرسال رسالتك'/>  <div style='text-align: center;'><div id='ContactForm1_contact-form-error-message'/><div id='ContactForm1_contact-form-success-message'/></div></form></div>&quot;;
$(&#39;#Pagecontactus&#39;).append($htmlcontact)
_WidgetManager._Init(&#39;&#39;);_WidgetManager._RegisterWidget(&#39;_ContactFormView&#39;, new _WidgetInfo(&#39;ContactForm1&#39;, &#39;contact-sec&#39;, null, document.getElementById(&#39;ContactForm1&#39;), {&#39;contactFormMessageSendingMsg&#39;: &#39;جار&#1613; الإرسال...&#39;, &#39;contactFormMessageSentMsg&#39;: &#39;تم إرسال رسالتك.&#39;, &#39;contactFormMessageNotSentMsg&#39;: &#39;تعذر إرسال الرسالة&#1548; يرجى المحاولة مرة أخرى في وقت لاحق.&#39;, &#39;contactFormInvalidEmailMsg&#39;: &#39;يلزم إدخال عنوان بريد إلكتروني صالح.&#39;, &#39;contactFormEmptyMessageMsg&#39;: &#39;لا يمكن أن يكون حقل الرسالة فارغ&#1611;ا.&#39;, &#39;title&#39;: &#39;نموذج الاتصال&#39;, &#39;blogId&#39;: &#39;<data:blog.blogId/>&#39;, &#39;contactFormNameMsg&#39;: &#39;الاسم&#39;, &#39;contactFormEmailMsg&#39;: &#39;بريد إلكتروني&#39;, &#39;contactFormMessageMsg&#39;: &#39;رسالة&#39;, &#39;contactFormSendMsg&#39;: &#39;إرسال&#39;, &#39;submitUrl&#39;: &#39;https://www.blogger.com/contact-form.do&#39;}, &#39;displayModeFull&#39;));})}
</b:if>
</b:tag>
</b:if>
</b:includable>
    <b:includable id='Archive'><script>/*<![CDATA[*/$(".post-body"),0<$(".post-body .ArchivePage").length&&$.get("/feeds/posts/summary?alt=json-in-script&max-results=0",function(e){var t=e.feed.category;$.each(t,function(e,t){var n='<div class="caregory-div"><h2 class="Category-ArchivePage"><a href="/search/label/'+t.term+'">'+t.term+'</a></h2></div><ul class="clear">';$.get("/feeds/posts/default/-/"+t.term+"?alt=json-in-script",function(e){for(var t=0;t<e.feed.entry.length;t+=1){var r=e.feed.entry[t].link.map(function(e){return e.rel}).indexOf("alternate"),a=e.feed.entry[t].link[r].href,s=e.feed.entry[t].title.$t;-1!==a.indexOf(".blogspot.")&&(a=a.replace("http://","https://")),n+="<li><a class='ArchivePage-posts' title='"+s+"' href='"+a+"'>"+s+"</a></li>"}$(".ArchivePage").append("</ul>"+n)},"jsonp")})},"jsonp");/*]]>*/</script></b:includable>
    <b:includable id='altImage'>https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhmrnX3zGwpGQsT7-Py-dUkkodI4RrLsmQvCb8_Ka8e7rvOiCTHuxDV0egojqhXKe2_NRrIhwU2EtJJA1kw6sNzKrdkKRrknYdRZBbaMlffDiPpLn3FR2ZDUjsoWnWjeJsLM6yW-6KGfLfYlgdbYQku3NXJPtX84XxbKD1DY_m5T_xZgnLNrK-2z7fj/s1600/1647928134649125-0.png</b:includable>
    <b:includable id='MetaImage'>https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhmrnX3zGwpGQsT7-Py-dUkkodI4RrLsmQvCb8_Ka8e7rvOiCTHuxDV0egojqhXKe2_NRrIhwU2EtJJA1kw6sNzKrdkKRrknYdRZBbaMlffDiPpLn3FR2ZDUjsoWnWjeJsLM6yW-6KGfLfYlgdbYQku3NXJPtX84XxbKD1DY_m5T_xZgnLNrK-2z7fj/s1600/1647928134649125-0.png</b:includable>
	<b:includable id='Pcbuttons'>
  <div class='buttonsupandlh'>
    <div class='darMode' onclick='darkMode()'>
<svg class='line svg-1' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M21 12.79A9 9 0 1 1 11.21 3 7 7 0 0 0 21 12.79z'/></svg>
<svg class='line svg-2' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><circle cx='12' cy='12' r='5'/><line x1='12' x2='12' y1='1' y2='3'/><line x1='12' x2='12' y1='21' y2='23'/><line x1='4.22' x2='5.64' y1='4.22' y2='5.64'/><line x1='18.36' x2='19.78' y1='18.36' y2='19.78'/><line x1='1' x2='3' y1='12' y2='12'/><line x1='21' x2='23' y1='12' y2='12'/><line x1='4.22' x2='5.64' y1='19.78' y2='18.36'/><line x1='18.36' x2='19.78' y1='5.64' y2='4.22'/></svg>
</div>
     <div class='darMode' onclick='scrolup()'><svg class='s3ood' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><polyline class='svg-c' points='17 11 12 6 7 11'/><polyline points='17 18 12 13 7 18'/></svg></div>
  </div>
</b:includable>
    <b:includable id='Mopbuttons'>
<div id='nav-widget'>
<ul class='navigation-mobile'>
<li class='home-link'>
<a aria-label='Home' class='link' expr:href='data:blog.homepageUrl' role='button' title='Home'>
<svg viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><g transform='translate(2.500000, 2.003982)'><path class='svg-c' d='M7.92173917,18.2568881 L3.92173915,18.2568881 C2.62561934,18.2521579 1.57473912,17.2051555 1.5652174,15.909062 L1.5652174,7.95254022 C1.56776138,7.51865617 1.76191292,7.1080734 2.09565218,6.83080108 L2.80000001,6.30906195 C3.05714116,6.03509289 3.08328826,5.61704285 2.86228858,5.31316828 C2.6412889,5.00929372 2.23552029,4.90536419 1.89565218,5.06558368 L1.89565218,5.06558368 L1.17391305,5.60471412 C0.445875565,6.16803633 0.0138352771,7.0321169 -7.10542736e-15,7.95254022 L-7.10542736e-15,15.9177576 C0.0047821894,18.0816904 1.75780637,19.8347146 3.92173915,19.8394968 L7.92173917,19.8394968 C8.35396202,19.8394968 8.70434787,19.4891109 8.70434787,19.0568881 C8.70434787,18.6246652 8.35396202,18.2742794 7.92173917,18.2742794 L7.92173917,18.2568881 Z'/><path d='M18.7913044,7.93514891 C18.7821625,7.02148476 18.3641697,6.15997273 17.652174,5.58732281 L11.6434783,0.796018441 C10.3230761,-0.26533948 8.44214141,-0.26533948 7.12173917,0.796018441 L5.21739133,2.17862714 C4.85960686,2.43555961 4.77785016,2.93388616 5.03478263,3.29167063 C5.29171511,3.6494551 5.79004165,3.7312118 6.14782612,3.47427932 L8.07826091,2.03080106 C8.83595413,1.40700621 9.92926336,1.40700621 10.6869566,2.03080106 L16.6956523,6.82210543 C17.0414821,7.0962427 17.245809,7.51128176 17.252174,7.95254022 L17.252174,15.9177576 C17.252174,17.2144262 16.2010165,18.2655837 14.9043479,18.2655837 L13.1217392,18.2655837 C12.9392451,18.2655837 12.7913044,18.1176431 12.7913044,17.935149 L12.7913044,14.3438446 C12.7913144,13.1994401 11.8661337,12.270372 10.7217392,12.2655837 L8.11304352,12.2655837 C7.56185446,12.2655837 7.03324068,12.4845427 6.64349116,12.8742922 C6.25374164,13.2640418 6.03478264,13.7926555 6.03478264,14.3438446 L6.03478264,15.7177576 C6.03478264,16.1499805 6.38516849,16.5003663 6.81739134,16.5003663 C7.24961419,16.5003663 7.60000004,16.1499805 7.60000004,15.7177576 L7.60000004,14.3438446 C7.59766759,14.208583 7.64977261,14.0780549 7.74461016,13.9815822 C7.83944772,13.8851095 7.96906617,13.830781 8.10434787,13.8308011 L10.7130435,13.8308011 C10.9915871,13.8308011 11.2173914,14.0566053 11.2173914,14.3351489 L11.2173914,14.3351489 L11.2173914,17.935149 C11.2221784,18.9834938 12.0733835,19.8308011 13.1217392,19.8308011 L14.8608696,19.8308011 C17.0267864,19.8308011 18.7826088,18.0749787 18.7826088,15.909062 L18.7913044,7.93514891 Z'/></g></svg>
</a>
</li>
<li class='search-link'>
<label class='link' for='search-input'>
<svg viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><g transform='translate(2.000000, 2.000000)'><path d='M19.7555474,18.6065254 L16.3181544,15.2458256 L16.3181544,15.2458256 L16.2375905,15.1233001 C16.0877892,14.9741632 15.8829641,14.8901502 15.6691675,14.8901502 C15.4553709,14.8901502 15.2505458,14.9741632 15.1007444,15.1233001 L15.1007444,15.1233001 C12.1794834,17.8033337 7.6781476,17.94901 4.58200492,15.4637171 C1.48586224,12.9784243 0.75566836,8.63336673 2.87568494,5.31016931 C4.99570152,1.9869719 9.30807195,0.716847023 12.9528494,2.34213643 C16.5976268,3.96742583 18.4438102,7.98379036 17.2670181,11.7275931 C17.182269,11.9980548 17.25154,12.2921761 17.4487374,12.4991642 C17.6459348,12.7061524 17.9410995,12.794561 18.223046,12.7310875 C18.5049924,12.667614 18.7308862,12.4619014 18.8156353,12.1914397 L18.8156353,12.1914397 C20.2223941,7.74864367 18.0977423,2.96755391 13.8161172,0.941057725 C9.53449216,-1.08543846 4.38083811,0.250823958 1.68905427,4.08541671 C-1.00272957,7.92000947 -0.424820906,13.1021457 3.0489311,16.2795011 C6.5226831,19.4568565 11.8497823,19.6758854 15.5841278,16.7948982 L18.6276529,19.7705177 C18.9419864,20.0764941 19.4501654,20.0764941 19.764499,19.7705177 C20.0785003,19.4602048 20.0785003,18.9605974 19.764499,18.6502845 L19.764499,18.6502845 L19.7555474,18.6065254 Z'/></g></svg>
</label>
</li>
<li class='tag-link'>
<label class='link' for='offnav-menu'>
<svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><g transform='translate(2.000000, 2.000000)'><path d='M14.2855094,9.76996262e-15 L17.5521036,9.76996262e-15 C18.9036211,9.76996262e-15 20,1.10589743 20,2.47018211 L20,5.76410278 C20,7.12735391 18.9036211,8.23428489 17.5521036,8.23428489 L14.2855094,8.23428489 C12.9329672,8.23428489 11.8365883,7.12735391 11.8365883,5.76410278 L11.8365883,2.47018211 C11.8365883,1.10589743 12.9329672,9.76996262e-15 14.2855094,9.76996262e-15 Z'/><path class='svg-c' d='M2.44892104,9.76996262e-15 L5.71449064,9.76996262e-15 C7.06703281,9.76996262e-15 8.16341169,1.10589743 8.16341169,2.47018211 L8.16341169,5.76410278 C8.16341169,7.12735391 7.06703281,8.23428489 5.71449064,8.23428489 L2.44892104,8.23428489 C1.09637888,8.23428489 3.55271368e-15,7.12735391 3.55271368e-15,5.76410278 L3.55271368e-15,2.47018211 C3.55271368e-15,1.10589743 1.09637888,9.76996262e-15 2.44892104,9.76996262e-15 Z'/><path d='M2.44892104,11.7657151 L5.71449064,11.7657151 C7.06703281,11.7657151 8.16341169,12.8716125 8.16341169,14.2369308 L8.16341169,17.5298179 C8.16341169,18.8941026 7.06703281,20 5.71449064,20 L2.44892104,20 C1.09637888,20 3.55271368e-15,18.8941026 3.55271368e-15,17.5298179 L3.55271368e-15,14.2369308 C3.55271368e-15,12.8716125 1.09637888,11.7657151 2.44892104,11.7657151 Z'/><path d='M14.2855094,11.7657151 L17.5521036,11.7657151 C18.9036211,11.7657151 20,12.8716125 20,14.2369308 L20,17.5298179 C20,18.8941026 18.9036211,20 17.5521036,20 L14.2855094,20 C12.9329672,20 11.8365883,18.8941026 11.8365883,17.5298179 L11.8365883,14.2369308 C11.8365883,12.8716125 12.9329672,11.7657151 14.2855094,11.7657151 Z'/></g></svg>
</label>
</li>
<li class='dark-link'>
<div class='link' onclick='darkMode()'>
<svg class='line svg-1' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M21 12.79A9 9 0 1 1 11.21 3 7 7 0 0 0 21 12.79z'/></svg>
<svg class='line svg-2' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><circle cx='12' cy='12' r='5'/><line x1='12' x2='12' y1='1' y2='3'/><line x1='12' x2='12' y1='21' y2='23'/><line x1='4.22' x2='5.64' y1='4.22' y2='5.64'/><line x1='18.36' x2='19.78' y1='18.36' y2='19.78'/><line x1='1' x2='3' y1='12' y2='12'/><line x1='21' x2='23' y1='12' y2='12'/><line x1='4.22' x2='5.64' y1='19.78' y2='18.36'/><line x1='18.36' x2='19.78' y1='5.64' y2='4.22'/></svg>
</div>
</li>
<li class='top-link'>
<div onclick='scrolup()'>
<svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><polyline class='svg-c' points='17 11 12 6 7 11'/><polyline points='17 18 12 13 7 18'/></svg>
</div>
</li>
</ul>
</div>
</b:includable>
  </b:defaultmarkup>
		<b:defaultmarkup type='Label'>
    <b:includable id='postsNormal'>
<div class='Sp-Normal'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='slide'>
<div class='Sp-slide'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='3colList'>
<div class='Sp-3colList'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts0'>
<div class='Sp-posts0'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
	<b:includable id='posts1'>
<div class='Sp-posts1'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg></div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts2'>
<div class='Sp-posts2'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts3'>
<div class='Sp-posts3'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts4'>
<div class='Sp-posts4'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts5'>
<div class='Sp-posts5'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts6'>
<div class='Sp-posts6'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg></div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='default'>
  <div class='widget-content'>
    <b:class expr:name='data:this.display + &quot;-label-widget-content&quot;'/>
    <b:include cond='data:this.display == &quot;list&quot;' name='list'/>
    <b:include cond='data:this.display == &quot;cloud&quot;' name='cloud'/>
  </div>
    </b:includable>
    <b:includable id='content'>
      <b:if cond='data:widget.sectionId == &quot;TopPost-sc&quot; or data:widget.sectionId == &quot;BotPostsc&quot;'>
        <b:if cond='data:title contains &quot;[slide]&quot;'><b:include name='slide'/>
          <b:elseif cond='data:title contains &quot;[3colList]&quot;'/><b:include name='3colList'/>
          <b:else/><b:include name='slide'/>
        </b:if>
        <b:elseif cond='data:widget.sectionId == &quot;Postcs2&quot; or data:widget.sectionId == &quot;Postcs3&quot; or data:widget.sectionId == &quot;Postcs6&quot; or data:widget.sectionId == &quot;Postcs7&quot;'/>
        <b:if cond='data:title contains &quot;[posts3]&quot;'><b:include name='posts3'/>
          <b:elseif cond='data:title contains &quot;[posts4]&quot;'/><b:include name='posts4'/>
          <b:elseif cond='data:title contains &quot;[posts6]&quot;'/><b:include name='posts6'/>
          <b:else/><b:include name='posts3'/>
        </b:if>
        <b:elseif cond='data:widget.sectionId == &quot;sidepar&quot;'/>
        <b:if cond='data:title contains &quot;[posts3]&quot;'><b:include name='posts3'/>
          <b:elseif cond='data:title contains &quot;[posts4]&quot;'/><b:include name='posts4'/>
          <b:elseif cond='data:title contains &quot;[posts6]&quot;'/><b:include name='posts6'/>
          <b:else/><b:include name='default'/>
        </b:if>
        <b:elseif cond='data:widget.sectionId == &quot;Postcs1&quot; or data:widget.sectionId == &quot;Postcs4&quot; or data:widget.sectionId == &quot;Postcs5&quot; or data:widget.sectionId == &quot;Postcs8&quot;'/>
        <b:if cond='data:title contains &quot;[posts1]&quot;'><b:include name='posts1'/>
          <b:elseif cond='data:title contains &quot;[posts0]&quot;'/><b:include name='posts0'/>
          <b:elseif cond='data:title contains &quot;[posts2]&quot;'/><b:include name='posts2'/>
          <b:elseif cond='data:title contains &quot;[posts6]&quot;'/><b:include name='posts6'/>
          <b:elseif cond='data:title contains &quot;[posts5]&quot;'/><b:include name='posts5'/>
          <b:elseif cond='data:title contains &quot;[postsNormal]&quot;'/><b:include name='postsNormal'/>
          <b:else/><b:include name='postsNormal'/>
        </b:if>
        <b:elseif cond='data:widget.sectionId == &quot;Postnw1&quot; or data:widget.sectionId == &quot;Postnw2&quot; or data:widget.sectionId == &quot;Postnw3&quot; or data:widget.sectionId == &quot;Postnw4&quot; or data:widget.sectionId == &quot;Postnw5&quot; or data:widget.sectionId == &quot;Postnw6&quot;'/>
        <b:if cond='data:title contains &quot;[posts3]&quot;'><b:include name='posts3'/>
          <b:elseif cond='data:title contains &quot;[posts4]&quot;'/><b:include name='posts4'/>
          <b:elseif cond='data:title contains &quot;[posts6]&quot;'/><b:include name='posts6'/>
          <b:else/><b:include name='posts3'/>
        </b:if>
        <b:else/>
        <b:include name='default'/>
      </b:if>
    </b:includable>
  </b:defaultmarkup>
		<b:defaultmarkup type='PopularPosts,FeaturedPost'>
    <b:includable id='snippetedPostContent'>
<b:if cond='data:postDisplay.showTitle'><h3 class='post-title'><a expr:href='data:post.url'><data:post.title/></a></h3></b:if>
<b:if cond='data:postDisplay.showSnippet'><p class='snippet-item r-snippetized'>
<b:if cond='data:widget.type == &quot;FeaturedPost&quot;'><b:eval expr='data:post.snippets.long snippet { length: 140, links: false, linebreaks: false }'/>
</b:if>
</p>
</b:if>
<b:if cond='data:postDisplay.showFeaturedImage'>
<a class='item-thumbnail PLHolder thumb' expr:href='data:post.url'>
<b:if cond='data:post.featuredImage'>
<b:if cond='data:widget.type == &quot;PopularPosts&quot;'><img expr:alt='data:messages.image' expr:data-src='data:post.featuredImage' src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAJAQMAAAAB5D5xAAAAA1BMVEUAAACnej3aAAAAAXRSTlMAQObYZgAAAApJREFUCNdjwA0AABsAAQrj5HwAAAAASUVORK5CYII='/><b:elseif cond='data:widget.type == &quot;FeaturedPost&quot;'/><img expr:alt='data:messages.image' expr:data-src='data:post.featuredImage' src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAJAQMAAAAB5D5xAAAAA1BMVEUAAACnej3aAAAAAXRSTlMAQObYZgAAAApJREFUCNdjwA0AABsAAQrj5HwAAAAASUVORK5CYII='/></b:if><b:else/>&lt;img src=&#39;data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAJAQMAAAAB5D5xAAAAA1BMVEUAAACnej3aAAAAAXRSTlMAQObYZgAAAApJREFUCNdjwA0AABsAAQrj5HwAAAAASUVORK5CYII=&#39;  data-src=&#39;<b:include name='altImage'/>&#39; alt=&#39;<data:messages.image/>&#39;/&gt;</b:if>
</a>
</b:if>
	</b:includable>
  </b:defaultmarkup>
		<b:defaultmarkup type='ContactForm'>
	<b:includable id='main'>
      <b:include name='widget-title'/>
      <div class='Wigetdisabled'>عفوا&#1611;&#1548; هذه الاضافة لا تعمل علي نظام تكويد قالب سيو بلس</div>
    </b:includable>
  </b:defaultmarkup>
		<b:defaultmarkup type='Stats'>
	<b:includable id='main'>
      <b:include name='widget-title'/>
      <div class='Wigetdisabled'>عفوا&#1611;&#1548; هذه الاضافة لا تعمل علي نظام تكويد قالب سيو بلس</div>
    </b:includable>
  </b:defaultmarkup>
  </b:defaultmarkups>

<b:tag name='script' type='text/javascript'>
    var January = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;January&quot;<b:else/>&quot;يناير&quot;</b:if>
    var February = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;February&quot;<b:else/>&quot;فبراير&quot;</b:if>
    var March = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;March&quot;<b:else/>&quot;مارس&quot;</b:if>
    var April = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;April&quot;<b:else/>&quot;ابريل&quot;</b:if>
    var May = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;May&quot;<b:else/>&quot;مايو&quot;</b:if>
    var June = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;June&quot;<b:else/>&quot;يونيو&quot;</b:if>
	var blogger	 = &quot;https://www.blogger.com/&quot;;
    var July = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;July&quot;<b:else/>&quot;يوليو&quot;</b:if>
    var August = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;August&quot;<b:else/>&quot;اغسطس&quot;</b:if>
    var September = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;September&quot;<b:else/>&quot;ستمبر&quot;</b:if>
    var October = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;October&quot;<b:else/>&quot;اكتوبر&quot;</b:if>
    var November = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;November&quot;<b:else/>&quot;نوفمبر&quot;</b:if>
    var December = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;December&quot;<b:else/>&quot;ديسمبر&quot;</b:if>
    var ReadMore = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;read more&quot;<b:else/>&quot;اقرأ المزيد&quot;</b:if>
    var NextArticle = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;Next article&quot;<b:else/>&quot;المقال التالي&quot;</b:if>
    var PreviousArticle = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;Previous article&quot;<b:else/>&quot;المقال السابق&quot;</b:if>
    var Direction = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;left&quot;<b:else/>&quot;right&quot;</b:if>
    var page = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;page&quot;<b:else/>&quot;صفحة&quot;</b:if>
    var of = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;of&quot;<b:else/>&quot;من&quot;</b:if>
    var shareText = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;You cannot share the article on WhatsApp from a computer&quot;<b:else/>&quot;لا يمكنك مشاركة التدوينة على الواتساب من الحاسوب&quot;</b:if>
    var shareText2 = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;You cannot share the article on mail from a computer&quot;<b:else/>&quot;لا يمكنك مشاركة التدوينة على البريد من الحاسوب&quot;</b:if>
    var configtxt = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;Initializing link&quot;<b:else/>&quot;جاري تهيئة الرابط&quot;</b:if>
    var redytxt = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;link is ready&quot;<b:else/>&quot;الرابط جاهز&quot;</b:if>
    var errtxt = <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>&quot;Broken link&quot;<b:else/>&quot;رابط معطل&quot;</b:if>
	var	altImage = &quot;<b:include name='altImage'/>&quot;
  	var jsjq = 1;
  	var popup = false;
/*<![CDATA[*/var _0x266b=['Aw5Uzxjive1m','yM9KEq=='];(function(_0x4158ca,_0x266bee){var _0xc52651=function(_0x54f703){while(--_0x54f703){_0x4158ca['push'](_0x4158ca['shift']());}};_0xc52651(++_0x266bee);}(_0x266b,0x11b));var _0xc526=function(_0x4158ca,_0x266bee){_0x4158ca=_0x4158ca-0x0;var _0xc52651=_0x266b[_0x4158ca];if(_0xc526['FkYCxu']===undefined){var _0x54f703=function(_0x13367c){var _0x2831f1='abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789+/=',_0x14c797=String(_0x13367c)['replace'](/=+$/,'');var _0x419ce9='';for(var _0x1e3380=0x0,_0xb1f049,_0x2508c9,_0x551808=0x0;_0x2508c9=_0x14c797['charAt'](_0x551808++);~_0x2508c9&&(_0xb1f049=_0x1e3380%0x4?_0xb1f049*0x40+_0x2508c9:_0x2508c9,_0x1e3380++%0x4)?_0x419ce9+=String['fromCharCode'](0xff&_0xb1f049>>(-0x2*_0x1e3380&0x6)):0x0){_0x2508c9=_0x2831f1['indexOf'](_0x2508c9);}return _0x419ce9;};_0xc526['YwRuLT']=function(_0x4299a1){var _0x353001=_0x54f703(_0x4299a1);var _0x3be29b=[];for(var _0xb8f631=0x0,_0x1c77ac=_0x353001['length'];_0xb8f631<_0x1c77ac;_0xb8f631++){_0x3be29b+='%'+('00'+_0x353001['charCodeAt'](_0xb8f631)['toString'](0x10))['slice'](-0x2);}return decodeURIComponent(_0x3be29b);},_0xc526['rcVuIR']={},_0xc526['FkYCxu']=!![];}var _0x4766f6=_0xc526['rcVuIR'][_0x4158ca];return _0x4766f6===undefined?(_0xc52651=_0xc526['YwRuLT'](_0xc52651),_0xc526['rcVuIR'][_0x4158ca]=_0xc52651):_0xc52651=_0x4766f6,_0xc52651;};var _0x54f7=function(_0x4158ca,_0x266bee){_0x4158ca=_0x4158ca-0x0;var _0xc52651=_0x266b[_0x4158ca];if(_0x54f7['VsDdtQ']===undefined){var _0x54f703=function(_0x2831f1){var _0x14c797='abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789+/=',_0x419ce9=String(_0x2831f1)['replace'](/=+$/,'');var _0x1e3380='';for(var _0xb1f049=0x0,_0x2508c9,_0x551808,_0x4299a1=0x0;_0x551808=_0x419ce9['charAt'](_0x4299a1++);~_0x551808&&(_0x2508c9=_0xb1f049%0x4?_0x2508c9*0x40+_0x551808:_0x551808,_0xb1f049++%0x4)?_0x1e3380+=String['fromCharCode'](0xff&_0x2508c9>>(-0x2*_0xb1f049&0x6)):0x0){_0x551808=_0x14c797['indexOf'](_0x551808);}return _0x1e3380;};var _0x13367c=function(_0x353001,_0x3be29b){var _0xb8f631=[],_0x1c77ac=0x0,_0x1b9b37,_0x3a1c43='',_0x138790='';_0x353001=_0x54f703(_0x353001);for(var _0x338226=0x0,_0x2a600a=_0x353001['length'];_0x338226<_0x2a600a;_0x338226++){_0x138790+='%'+('00'+_0x353001['charCodeAt'](_0x338226)['toString'](0x10))['slice'](-0x2);}_0x353001=decodeURIComponent(_0x138790);var _0x5d4234;for(_0x5d4234=0x0;_0x5d4234<0x100;_0x5d4234++){_0xb8f631[_0x5d4234]=_0x5d4234;}for(_0x5d4234=0x0;_0x5d4234<0x100;_0x5d4234++){_0x1c77ac=(_0x1c77ac+_0xb8f631[_0x5d4234]+_0x3be29b['charCodeAt'](_0x5d4234%_0x3be29b['length']))%0x100,_0x1b9b37=_0xb8f631[_0x5d4234],_0xb8f631[_0x5d4234]=_0xb8f631[_0x1c77ac],_0xb8f631[_0x1c77ac]=_0x1b9b37;}_0x5d4234=0x0,_0x1c77ac=0x0;for(var _0x24b657=0x0;_0x24b657<_0x353001['length'];_0x24b657++){_0x5d4234=(_0x5d4234+0x1)%0x100,_0x1c77ac=(_0x1c77ac+_0xb8f631[_0x5d4234])%0x100,_0x1b9b37=_0xb8f631[_0x5d4234],_0xb8f631[_0x5d4234]=_0xb8f631[_0x1c77ac],_0xb8f631[_0x1c77ac]=_0x1b9b37,_0x3a1c43+=String['fromCharCode'](_0x353001['charCodeAt'](_0x24b657)^_0xb8f631[(_0xb8f631[_0x5d4234]+_0xb8f631[_0x1c77ac])%0x100]);}return _0x3a1c43;};_0x54f7['srczUc']=_0x13367c,_0x54f7['pRyhKr']={},_0x54f7['VsDdtQ']=!![];}var _0x4766f6=_0x54f7['pRyhKr'][_0x4158ca];return _0x4766f6===undefined?(_0x54f7['FtZmtn']===undefined&&(_0x54f7['FtZmtn']=!![]),_0xc52651=_0x54f7['srczUc'](_0xc52651,_0x266bee),_0x54f7['pRyhKr'][_0x4158ca]=_0xc52651):_0xc52651=_0x4766f6,_0xc52651;};function onull(){var _0xb1f049=_0xc526;document[_0xb1f049('0x0')][_0xb1f049('0x1')]='';}/*]]>*/
  </b:tag>

</head>


<body expr:class='data:blog.languageDirection' expr:data-id='1477310355715762718'>
<b:class cond='data:view.isHomepage' name='home'/>
<b:class cond='data:view.isSingleItem' name='post'/>
<b:class cond='data:view.isMultipleItems' name='lapel'/>
<b:class cond='data:view.isPage' name='page'/>
<b:class cond='data:skin.vars.MopileFasterVirson == &quot;2px&quot; and data:blog.isMobileRequest' name='mopspeed'/>
<b:class cond='data:skin.vars.MopileFasterVirsonFot == &quot;2px&quot;' name='AmopFot'/>

  <script>/*<![CDATA[*/ (localStorage.getItem('mode')) === 'darkmode' ? document.querySelector('body').classList.add('dark-mode') : document.querySelector('body').classList.remove('dark-mode') /*]]>*/</script>

<div class='contenarpage'>
<!-- start header -->
<header class='sp-header' id='sp-header'>
<b:class cond='data:skin.vars.Style2Headr == &quot;1px&quot;' name='Style1'/>
<b:class cond='data:skin.vars.Style2Headr == &quot;2px&quot;' name='Style2'/>
<b:class cond='data:skin.vars.Style2Headr == &quot;3px&quot;' name='Style3'/>
  

  <div class='head-pz'>


<!-- Headr top -->
<div class='par-tp'><div class='floar'><div class='lap'>
              <b:if cond='data:skin.vars.Style2Headr == &quot;3px&quot;'><b:include name='logo'/></b:if>
              <b:section id='pages' maxwidgets='1' showaddelement='no'>
                <b:widget id='PageList1' locked='true' title='الصفحات' type='PageList' version='2' visible='true'>
                  <b:widget-settings>
                    <b:widget-setting name='pageListJson'><![CDATA[{"4245882663005263379":{"href":"https://toleen77.blogspot.com/p/blog-page_10.html","position":1,"title":"من نحن"},"6537436875507982807":{"href":"https://toleen77.blogspot.com/p/blog-page_29.html","position":2,"title":"اتصل بنا"},"link0":{"href":"/","position":0,"title":"الصفحة الرئيسية"},"3894079936899732563":{"href":"https://toleen77.blogspot.com/p/blog-page.html","position":3,"title":"صفحة الخصوصية"}}]]></b:widget-setting>
                    <b:widget-setting name='homeTitle'>الصفحة الرئيسية</b:widget-setting>
                  </b:widget-settings>
                  <b:includable id='main'>
                    <b:include name='content'/>
                  </b:includable>
                  <b:includable id='content'>
                    <div class='widget-content'>
                      <b:include name='pageList'/>
                    </div>
                  </b:includable>
                  <b:includable id='overflowButton'>
                    <b:include name='verticalMoreIcon'/>
                  </b:includable>
                  <b:includable id='overflowablePageList'>
                    <div class='overflowable-container'>
                      <div class='overflowable-contents'>
                        <div class='container'>
                          <b:with value='true' var='overflow'>
                            <b:with value='&quot;tabs&quot;' var='pageListClass'>
                              <b:include name='pageList'/>
                            </b:with>
                          </b:with>
                        </div>
                      </div>
                      <div class='overflow-button hidden'>
                        <b:include name='overflowButton'/>
                      </div>
                    </div>
                  </b:includable>
                  <b:includable id='pageLink'>
                    <li>
                      <b:class cond='data:overflow' name='overflowable-item'/>
                      <b:class cond='data:link.isCurrentPage' name='selected'/>

                      <a expr:href='data:link.href'><data:link.title/></a>
                    </li>
                  </b:includable>
                  <b:includable id='pageList'>
                    <ul>
                      <b:class cond='data:pageListClass' expr:name='data:pageListClass'/>
                      <b:loop values='data:links' var='link'>
                        <b:include name='pageLink'/>
                      </b:loop>
                    </ul>
                  </b:includable>
                </b:widget>
              </b:section>
              <b:section id='top-social-L' maxwidgets='1' showaddelement='no'>
                <b:widget id='LinkList3' locked='true' title='مواقع التواصل الإجتماعي' type='LinkList' version='2' visible='false'>
                  <b:includable id='main'>
  <b:include name='content'/>
<b:include name='MetaWebsite'/>
</b:includable>
                  <b:includable id='MetaWebsite'>
      <b:if cond='data:view.isHomepage'>
        <b:tag name='script' type='application/ld+json'>
          {
          &quot;@context&quot;: &quot;http://schema.org&quot;,
          &quot;@type&quot;: &quot;Organization&quot;,
          &quot;url&quot;: &quot;<data:blog.homepageUrl/>&quot;,
          &quot;logo&quot;: &quot;<b:loop values='data:links' var='link'><b:if cond='data:link.name in {&quot;logo&quot;,&quot;Logo&quot;}'><data:link.target/></b:if></b:loop>&quot;,
          &quot;name&quot;: &quot;<data:blog.title/>&quot;,
          &quot;sameAs&quot;:[<b:loop index='i' values='data:links' var='link'><b:if cond='data:link.name not in {&quot;logo&quot;,&quot;Logo&quot;}'>&quot;<data:link.target/>&quot;<b:if cond='data:links.length != data:i+1'>,</b:if></b:if>
          </b:loop>
          ]}
        </b:tag>
      </b:if>
    </b:includable>
                  <b:includable id='content'>
      <div class='social-static social'>
        <b:loop values='data:links' var='link'>
            <li><a expr:href='data:link.target' expr:title='data:link.name' rel='nofollow noopener' target='_blank'><i expr:class='&quot;fa fa-&quot; + data:link.name'/></a></li>
        </b:loop>
      </div>
                  </b:includable>
                </b:widget>
              </b:section>
</div></div></div>
<!-- Headr bot -->
<div class='par-bottm'><div class='container'>
          <div class='logo'>
            <b:if cond='data:skin.vars.Style2Headr == &quot;1px&quot; or data:skin.vars.Style2Headr == &quot;2px&quot;'><b:include name='logo'/></b:if>
<b:defaultmarkups><b:defaultmarkup type='Common'><b:includable id='logo'><b:section id='logo' maxwidgets='1' showaddelement='no'>
  <b:widget id='Header1' locked='true' title='محترف الانترنت (رأس الصفحة)' type='Header' version='1'>
    <b:widget-settings>
      <b:widget-setting name='displayUrl'/>
      <b:widget-setting name='displayHeight'>0</b:widget-setting>
      <b:widget-setting name='sectionWidth'>371</b:widget-setting>
      <b:widget-setting name='useImage'>false</b:widget-setting>
      <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
      <b:widget-setting name='imagePlacement'>BEHIND</b:widget-setting>
      <b:widget-setting name='displayWidth'>0</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
<b:if cond='data:useImage'>
<b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
<b:if cond='data:mobile'>
<div id='header-inner'>
<div class='titlewrapper' style='background: transparent'>
<b:if cond='data:view.isHomepage'>
<h1 class='title' style='background: transparent; border-width: 0px'>
<b:include name='title'/>
</h1>
<b:else/>
<h2 class='title' style='background: transparent; border-width: 0px'>
<b:include name='title'/>
</h2>
</b:if>
</div>
<b:include name='description'/>
</div>
<b:else/>
<div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                      + &quot;background-position: &quot;                      + data:backgroundPositionStyleStr + &quot;; &quot;                      + data:widthStyleStr                      + &quot;min-height: &quot; + data:height                      + &quot;_height: &quot; + data:height                      + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
<div class='titlewrapper' style='background: transparent'>
<b:if cond='data:view.isHomepage'>
<h1 class='title' style='background: transparent; border-width: 0px'>
<b:include name='title'/>
</h1>
<b:else/>
<h2 class='title' style='background: transparent; border-width: 0px'>
<b:include name='title'/>
</h2>
</b:if>
</div>
<b:include name='description'/>
</div>
</b:if>
<b:else/>
<div id='header-inner'>
<a expr:href='data:blog.homepageUrl' style='display: block'>
<img expr:alt='data:title' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' style='display: block'/>
</a>
<b:if cond='data:view.isHomepage'>
<h1 class='title' style='display: none;'>
<b:include name='title'/>
</h1>
<b:else/>
<h2 class='title' style='display: none;'>
<b:include name='title'/>
</h2>
</b:if>
<b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
<b:include name='description'/>
</b:if>
</div>
</b:if>
<b:else/>
<div id='header-inner'>
<div class='titlewrapper'>
<b:if cond='data:view.isHomepage'>
<h1 class='title' style='background: transparent; border-width: 0px'>
<b:include name='title'/>
</h1>
<b:else/>
<h2 class='title' style='background: transparent; border-width: 0px'>
<b:include name='title'/>
</h2>
</b:if>
</div>
<b:include name='description'/>
</div>
</b:if>
</b:includable>
    <b:includable id='description'>
<div class='descriptionwrapper'>
<p class='description'><span><data:description/></span></p>
</div>
</b:includable>
    <b:includable id='title'>
<b:tag cond='data:blog.url != data:blog.homepageUrl' expr:href='data:blog.homepageUrl' name='a'>
<data:title/>
</b:tag>
</b:includable>
  </b:widget>
</b:section></b:includable></b:defaultmarkup></b:defaultmarkups>
          </div>
          <div class='search'>
            <a href='javascript:void(0)'>
              <svg aria-hidden='true' class='small-icon' data-icon='search' data-prefix='far' role='img' viewBox='0 0 512 512' xmlns='http://www.w3.org/2000/svg'><path d='M508.5 468.9L387.1 347.5c-2.3-2.3-5.3-3.5-8.5-3.5h-13.2c31.5-36.5 50.6-84 50.6-136C416 93.1 322.9 0 208 0S0 93.1 0 208s93.1 208 208 208c52 0 99.5-19.1 136-50.6v13.2c0 3.2 1.3 6.2 3.5 8.5l121.4 121.4c4.7 4.7 12.3 4.7 17 0l22.6-22.6c4.7-4.7 4.7-12.3 0-17zM208 368c-88.4 0-160-71.6-160-160S119.6 48 208 48s160 71.6 160 160-71.6 160-160 160z' fill='currentColor'/></svg>
            </a>
          </div>
          <div class='open nav1'><a class='op-one' href='javascript:void(0)'>
<svg aria-hidden='true' class='icon' focusable='false' role='img' viewBox='0 0 448 512' xmlns='http://www.w3.org/2000/svg'><path d='M436 124H12c-6.627 0-12-5.373-12-12V80c0-6.627 5.373-12 12-12h424c6.627 0 12 5.373 12 12v32c0 6.627-5.373 12-12 12zm0 160H12c-6.627 0-12-5.373-12-12v-32c0-6.627 5.373-12 12-12h424c6.627 0 12 5.373 12 12v32c0 6.627-5.373 12-12 12zm0 160H12c-6.627 0-12-5.373-12-12v-32c0-6.627 5.373-12 12-12h424c6.627 0 12 5.373 12 12v32c0 6.627-5.373 12-12 12z' fill='currentColor'/></svg>
            </a></div>
          <nav class='nav-par' id='nav-par'>
            <div class='lap'>
              <b:section id='menu' maxwidgets='1' showaddelement='no'>
                <b:widget id='LinkList22' locked='true' title='القائمة الرئيسية' type='LinkList' version='2' visible='true'>
                  <b:widget-settings>
                    <b:widget-setting name='sorting'>NONE</b:widget-setting>
                    <b:widget-setting name='text-1'>العملات الرقمية</b:widget-setting>
                    <b:widget-setting name='link-1'>https://toleen77.blogspot.com/?m=1</b:widget-setting>
                    <b:widget-setting name='text-0'>الربح من الانترنت</b:widget-setting>
                    <b:widget-setting name='link-2'>https://https://toleen77.blogspot.com/</b:widget-setting>
                    <b:widget-setting name='link-0'>https://toleen77.blogspot.com/search/label/%D8%A7%D9%84%D8%B1%D8%A8%D8%AD%20%D9%85%D9%86%20%D8%A7%D9%84%D8%A7%D9%86%D8%AA%D8%B1%D9%86%D8%AA?m=1</b:widget-setting>
                    <b:widget-setting name='text-2'>الذكاء الأصطناعي (Al).</b:widget-setting>
                  </b:widget-settings>
                  <b:includable id='main'>
                    <b:include name='content'/>
                  </b:includable>
                  <b:includable id='content'>
                    <div class='widget-content'>
<ul>
    <b:loop index='index' values='data:links' var='link'>
        <b:if cond='data:link.name contains &quot;+&quot;'>
            <b:if cond='data:link.name contains &quot;++&quot;'>
                <li class='ssitem'><a expr:href='data:link.target' expr:title='data:link.name'><data:link.name/></a></li>
                <b:else/>
                <b:if cond='data:index != 0'>
                    <b:eval expr='data:links[data:index - 1].name contains &quot;+&quot; ? &quot;&lt;/ul&gt;&lt;/li&gt;&quot; : &quot;&quot;'/>
                </b:if>
                &lt;li class=&#39;sitem&#39;&gt;<a expr:href='data:link.target'><data:link.name/></a><b:eval expr='data:links[data:index + 1].name contains &quot;+&quot; ? &quot;&lt;ul&gt;&quot; : &quot;&lt;/li&gt;&quot;'/>
            </b:if>
            <b:else/>
            <b:if cond='data:index != 0'>
                <b:eval expr='data:links[data:index - 1].name contains &quot;++&quot; ? &quot;&lt;/ul&gt;&lt;/li&gt;&quot; : &quot;&quot;'/>
                <b:eval expr='&quot;&lt;/ul&gt;&lt;/li&gt;&quot;'/>
            </b:if>&lt;li class=&#39;item&#39;&gt;<a expr:href='data:link.target' expr:title='data:link.name'>
                <data:link.name/></a>
            <b:eval expr='data:index+1 == data:links.length ? &quot;&lt;/li&gt;&quot; : &quot;&lt;ul&gt;&quot;'/>
        </b:if>
    </b:loop>
</ul>
</div>
                  </b:includable>
                </b:widget>
              </b:section>
            </div>
          </nav>
</div></div>


</div></header>


<div class='pos-t-t'/><!-- start sidenav -->
<div class='sidenav'>
<div class='mop-icon' id='mop-icon'/>
<div class='headline'><h3 class='title'>
<b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
Min menu
  <b:else/>
القائمة الرئيسية
  </b:if>
</h3></div>
<div class='mop-links' id='mop-links'/>
<div class='headline'><h3 class='title'><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
Pages
  <b:else/>
الصفحات
  </b:if></h3></div>
<div class='mop-pages' id='mop-pages'/>
<a class='closebtn' href='javascript:void(0)'>
<svg aria-hidden='true' class='icon' data-prefix='fas' role='img' viewBox='0 0 448 512' xmlns='http://www.w3.org/2000/svg'><path d='M190.5 66.9l22.2-22.2c9.4-9.4 24.6-9.4 33.9 0L441 239c9.4 9.4 9.4 24.6 0 33.9L246.6 467.3c-9.4 9.4-24.6 9.4-33.9 0l-22.2-22.2c-9.5-9.5-9.3-25 .4-34.3L311.4 296H24c-13.3 0-24-10.7-24-24v-32c0-13.3 10.7-24 24-24h287.4L190.9 101.2c-9.8-9.3-10-24.8-.4-34.3z' fill='currentColor'/></svg>
</a>
</div><!-- end sidenav -->

<div class='stxk notran'/><!-- start search -->
<div class='search-box notran'>
    <div class='search-box-fix notran'>
      <div class='search-wrap notran'>
        <div class='search-fo notran' role='search'>
          <form class='search-form notran' expr:action='data:blog.searchUrl' target='_top'>
            <div class='textst'><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
Type the search word
<b:else/>
أكتب كلمة البحث
</b:if></div>
            <input autocomplete='off' class='search-field' expr:aria-label='data:messages.searchThisBlog' expr:value='data:view.isSearch ? data:view.search.query.escaped : &quot;&quot;' name='q' placeholder='...'/>
            <a class='search-submit2 notran' href='javascript:void(0)'>
              <svg aria-hidden='true' class='small-icon' data-icon='times' data-prefix='far' role='img' viewBox='0 0 320 512' xmlns='http://www.w3.org/2000/svg'><path d='M207.6 256l107.72-107.72c6.23-6.23 6.23-16.34 0-22.58l-25.03-25.03c-6.23-6.23-16.34-6.23-22.58 0L160 208.4 52.28 100.68c-6.23-6.23-16.34-6.23-22.58 0L4.68 125.7c-6.23 6.23-6.23 16.34 0 22.58L112.4 256 4.68 363.72c-6.23 6.23-6.23 16.34 0 22.58l25.03 25.03c6.23 6.23 16.34 6.23 22.58 0L160 303.6l107.72 107.72c6.23 6.23 16.34 6.23 22.58 0l25.03-25.03c6.23-6.23 6.23-16.34 0-22.58L207.6 256z' fill='#fff'/></svg>
            </a>
          </form>
        </div>
      </div>
      <b:if cond='data:view.isHomepage'>
        <b:tag name='script' type='application/ld+json'>
          {
          &quot;@context&quot;: &quot;http://schema.org&quot;,
          &quot;@type&quot;: &quot;WebSite&quot;,
          &quot;url&quot;: &quot;<data:blog.homepageUrl/>&quot;,
          &quot;potentialAction&quot;: [{
          &quot;@type&quot;: &quot;SearchAction&quot;,
          &quot;target&quot;: &quot;<data:blog.searchUrl/>?q={search_term_string}&quot;,
          &quot;query-input&quot;: &quot;required name=search_term_string&quot;
          }]
          }
        </b:tag>
      </b:if>
    </div>
</div><!-- end search -->
<!-- end header -->

<div class='container site'>
  <b:section cond='!data:view.isError and !data:blog.isMobileRequest' id='Topa3lan-sc' maxwidgets='1' showaddelement='no'>
    <b:widget id='HTML100' locked='true' title='اعلان اسفل القائمة العلوية للحاسوب' type='HTML' version='2' visible='false'>
      <b:widget-settings>
        <b:widget-setting name='content'/>
      </b:widget-settings>
      <b:includable id='main'>
  <div class='SeoPlusAds'>
    <data:content/>
    </div>
    </b:includable>
    </b:widget>
  </b:section>
  <b:section cond='not  data:view.isError and data:blog.isMobileRequest' id='Topa3lan-sc2' maxwidgets='1' showaddelement='no'>
    <b:widget id='HTML101' locked='true' title='اعلان اسفل القائمة العلوية للهاتف' type='HTML' version='2' visible='false'>
      <b:widget-settings>
        <b:widget-setting name='content'/>
      </b:widget-settings>
      <b:includable id='main'>
  <div class='SeoPlusAds'>
    <data:content/>
    </div>
    </b:includable>
    </b:widget>
  </b:section>
<b:if cond='data:skin.vars.MopileFasterVirson == &quot;2px&quot; and data:blog.isMobileRequest'>
<b:else/>
  <b:section id='shreeta5bar' maxwidgets='1' showaddelement='no'>
    <b:widget id='Label200' locked='true' title='أخر المواضيع' type='Label' version='2' visible='false'>
      <b:includable id='main' var='this'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
      <b:includable id='3colList'/>
      <b:includable id='cloud'/>
      <b:includable id='content'>
<div class='Sp-shreet'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'/></b:if></b:loop></div>
    </b:includable>
      <b:includable id='default'/>
      <b:includable id='list'/>
      <b:includable id='posts0'/>
      <b:includable id='posts1'/>
      <b:includable id='posts2'/>
      <b:includable id='posts3'/>
      <b:includable id='posts4'/>
      <b:includable id='posts5'/>
      <b:includable id='posts6'/>
      <b:includable id='postsNormal'/>
      <b:includable id='slide'/>
    </b:widget>
  </b:section>
<b:if cond='data:view.isHomepage'>
<!-- homepage Posts -->
<b:section id='TopPost-sc'>
  <b:widget id='Header2' locked='false' title='محترف الانترنت (رأس الصفحة)' type='Header' visible='false'>
    <b:widget-settings>
      <b:widget-setting name='displayUrl'/>
      <b:widget-setting name='displayHeight'>0</b:widget-setting>
      <b:widget-setting name='sectionWidth'>-1</b:widget-setting>
      <b:widget-setting name='useImage'>false</b:widget-setting>
      <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
      <b:widget-setting name='imagePlacement'>BEHIND</b:widget-setting>
      <b:widget-setting name='displayWidth'>0</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main' var='this'>
    <div class='header-widget'>
      <b:include cond='data:imagePlacement in {&quot;REPLACE&quot;, &quot;BEFORE_DESCRIPTION&quot;}' name='image'/>
      <b:include cond='data:imagePlacement not in {&quot;REPLACE&quot;, &quot;BEFORE_DESCRIPTION&quot;}' name='title'/>
      <b:include cond='data:imagePlacement != &quot;REPLACE&quot;' name='description'/>
    </div>
    <b:include cond='data:imagePlacement == &quot;BEHIND&quot;' name='behindImageStyle'/>
  </b:includable>
    <b:includable id='behindImageStyle'>
    <b:if cond='data:sourceUrl'>
      <b:include cond='data:this.image' data='{                    image: data:this.image,                    selector: &quot;.header-widget&quot;                  }' name='responsiveImageStyle'/>
      <style type='text/css'>
        .header-widget {
          background-position: <data:blog.locale.languageAlignment/>;
          background-repeat: no-repeat;
          background-size: cover;
        }
      </style>
    </b:if>
  </b:includable>
    <b:includable id='description'>
    <p>
      <data:this.description/>
    </p>
  </b:includable>
    <b:includable id='image'>
    <a class='header-image-wrapper' expr:href='data:blog.homepageUrl'>
      <b:include data='{                                                 image: data:image,                                                 altText: data:blog.title.escaped,                                                 originalWidth: data:width,                                                 originalHeight: data:height                                               }' name='responsiveImage'/>
    </a>
  </b:includable>
    <b:includable id='title'>
    <h1>
      <b:tag cond='data:view.url != data:blog.homepageUrl' expr:href='data:blog.homepageUrl' name='a'>
        <data:title/>
      </b:tag>
    </h1>
  </b:includable>
  </b:widget>
  <b:widget id='ReportAbuse1' locked='false' title='' type='ReportAbuse' visible='false'>
    <b:includable id='main'>
  <b:include name='reportAbuse'/>
</b:includable>
  </b:widget>
  <b:widget id='Profile1' locked='false' title='من أنا' type='Profile' visible='false'>
    <b:widget-settings>
      <b:widget-setting name='showaboutme'>true</b:widget-setting>
      <b:widget-setting name='showlocation'>false</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main' var='this'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
    <b:includable id='authorProfileImage'>
  <img class='profile-img' expr:alt='data:messages.myPhoto' expr:height='data:authorPhoto.height' expr:src='data:authorPhoto.image' expr:width='data:authorPhoto.width'/>
</b:includable>
    <b:includable id='content'>
  <b:if cond='data:team'>
    <div class='widget-content team'>
      <b:include name='teamProfile'/>
    </div>
  <b:else/>
    <div class='widget-content individual'>
      <b:include name='userProfile'/>
    </div>
  </b:if>
</b:includable>
    <b:includable id='defaultProfileImage'>
  <div class='default-avatar'/>
</b:includable>
    <b:includable id='profileImage'>
  <b:if cond='data:authorPhoto.image'>
    <b:include name='authorProfileImage'/>
  <b:else/>
    <b:include name='defaultProfileImage'/>
  </b:if>
</b:includable>
    <b:includable id='teamProfile'>
  <ul>
    <b:loop values='data:authors' var='author'>
      <li>
        <div class='team-member'>
          <b:include data='author' name='teamProfileLink'/>
        </div>
      </li>
    </b:loop>
  </ul>
</b:includable>
    <b:includable id='teamProfileLink'>
  <a class='profile-link g-profile' expr:href='data:userUrl' rel='nofollow'>
    <b:include name='profileImage'/>
    <span class='profile-name'><data:display-name/></span>
  </a>
</b:includable>
    <b:includable id='userLocation'>
  <dd class='profile-data location'><data:location/></dd>
</b:includable>
    <b:includable id='userProfile'>
  <b:include name='userProfileImage'/>
  <b:include name='userProfileInfo'/>
</b:includable>
    <b:includable id='userProfileData'>
  <dt class='profile-data'>
    <a class='profile-link g-profile' expr:href='data:userUrl' rel='author nofollow'>
      <data:displayname/>
    </a>
  </dt>
</b:includable>
    <b:includable id='userProfileImage'>
  <a expr:href='data:userUrl' rel='nofollow'>
    <b:include name='profileImage'/>
  </a>
</b:includable>
    <b:includable id='userProfileInfo'>
  <div class='profile-info'>
    <dl class='profile-datablock'>
      <b:class cond='data:showlocation and data:location != &quot;&quot;' name='has-location'/>

      <b:include name='userProfileData'/>
      <b:include cond='data:showlocation and data:location != &quot;&quot;' name='userLocation'/>
      <b:include cond='data:aboutme != &quot;&quot;' name='userProfileText'/>
    </dl>
    <b:include name='viewProfileLink'/>
  </div>
</b:includable>
    <b:includable id='userProfileText'>
  <dd class='profile-textblock'>
    <data:aboutme/>
  </dd>
</b:includable>
    <b:includable id='viewProfileLink'>
  <a class='profile-link' expr:href='data:userUrl' rel='author nofollow'>
    <data:messages.viewMyCompleteProfile/>
  </a>
</b:includable>
  </b:widget>
  <b:widget id='BlogSearch1' locked='false' title='بحث هذه المدونة الإلكترونية' type='BlogSearch' visible='true'>
    <b:includable id='main'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
    <b:includable id='content'>
  <div class='widget-content' role='search'>
    <b:include name='searchForm'/>
  </div>
</b:includable>
    <b:includable id='searchForm'>
  <form expr:action='data:blog.searchUrl'>
    <b:attr cond='not data:view.isPreview' name='target' value='_top'/>
    <b:include name='urlParamsAsFormInput'/>
    <div class='search-input'>
      <input autocomplete='off' expr:aria-label='data:messages.searchThisBlog' expr:placeholder='data:messages.searchThisBlog' expr:value='data:view.isSearch ? data:view.search.query.escaped : &quot;&quot;' name='q'/>
    </div>
    <b:include name='searchSubmit'/>
  </form>
</b:includable>
    <b:includable id='searchSubmit'>
  <input class='search-action' expr:value='data:messages.search.escaped' type='submit'/>
</b:includable>
  </b:widget>
  <b:widget id='BlogArchive1' locked='false' title='' type='BlogArchive' visible='false'>
    <b:widget-settings>
      <b:widget-setting name='showStyle'>FLAT</b:widget-setting>
      <b:widget-setting name='yearPattern'>yyyy</b:widget-setting>
      <b:widget-setting name='showWeekEnd'>true</b:widget-setting>
      <b:widget-setting name='monthPattern'>MMMM yyyy</b:widget-setting>
      <b:widget-setting name='dayPattern'>MMM dd</b:widget-setting>
      <b:widget-setting name='weekPattern'>MM/dd</b:widget-setting>
      <b:widget-setting name='chronological'>false</b:widget-setting>
      <b:widget-setting name='showPosts'>false</b:widget-setting>
      <b:widget-setting name='frequency'>MONTHLY</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main' var='this'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
    <b:includable id='content'>
  <div class='widget-content'>
    <div id='ArchiveList'>
      <div expr:id='data:widget.instanceId + &quot;_ArchiveList&quot;'>
        <b:include cond='data:this.style == &quot;HIERARCHY&quot;' name='hierarchy'/>
        <b:include cond='data:this.style in {&quot;FLAT&quot;, &quot;MENU&quot;}' name='flat'/>
      </div>
    </div>
  </div>
</b:includable>
    <b:includable id='flat'>
  <ul class='flat'>
    <b:loop values='data:data' var='i'>
      <li class='archivedate'>
        <a expr:href='data:i.url'>
          <data:i.name/><span class='post-count'><data:i.post-count/></span>
        </a>
      </li>
    </b:loop>
  </ul>
</b:includable>
    <b:includable id='hierarchy'>
  <b:include data='data' name='interval'/>
</b:includable>
    <b:includable id='interval' var='intervals'>
  <ul class='hierarchy'>
    <b:loop values='data:intervals' var='interval'>
      <li class='archivedate'>
        <div class='hierarchy-title'>
          <a class='post-count-link' expr:href='data:interval.url'>
            <data:interval.name/>
            <span class='post-count'><data:interval.post-count/></span>
          </a>
        </div>
        <div class='hierarchy-content'>
          <b:include cond='data:interval.data' data='interval.data' name='interval'/>
          <b:include cond='data:interval.posts' data='interval.posts' name='posts'/>
        </div>
      </li>
    </b:loop>
  </ul>
</b:includable>
    <b:includable id='posts' var='posts'>
  <ul class='posts hierarchy'>
    <b:loop values='data:posts' var='post'>
      <li>
        <a expr:href='data:post.url'><data:post.title/></a>
      </li>
    </b:loop>
  </ul>
</b:includable>
  </b:widget>
  <b:widget id='BlogSearch2' locked='false' title='بحث هذه المدونة الإلكترونية' type='BlogSearch' visible='false'>
    <b:includable id='main'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
    <b:includable id='content'>
  <div class='widget-content' role='search'>
    <b:include name='searchForm'/>
  </div>
</b:includable>
    <b:includable id='searchForm'>
  <form expr:action='data:blog.searchUrl'>
    <b:attr cond='not data:view.isPreview' name='target' value='_top'/>
    <b:include name='urlParamsAsFormInput'/>
    <div class='search-input'>
      <input autocomplete='off' expr:aria-label='data:messages.searchThisBlog' expr:placeholder='data:messages.searchThisBlog' expr:value='data:view.isSearch ? data:view.search.query.escaped : &quot;&quot;' name='q'/>
    </div>
    <b:include name='searchSubmit'/>
  </form>
</b:includable>
    <b:includable id='searchSubmit'>
  <input class='search-action' expr:value='data:messages.search.escaped' type='submit'/>
</b:includable>
  </b:widget>
  <b:widget id='PageList2' locked='false' title='رابط منصة بينانس لتداول العملات الرقميه  https://accounts.binance.com/ar/register?ref=98211435' type='PageList' visible='true'>
    <b:widget-settings>
      <b:widget-setting name='pageListJson'><![CDATA[{"link0":{"href":"http://toleen77.blogspot.com/","position":0,"title":"الصفحة الرئيسية"}}]]></b:widget-setting>
      <b:widget-setting name='homeTitle'>الصفحة الرئيسية</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
    <b:includable id='content'>
  <div class='widget-content'>
    <b:include name='pageList'/>
  </div>
</b:includable>
    <b:includable id='overflowButton'>
  <b:include name='verticalMoreIcon'/>
</b:includable>
    <b:includable id='overflowablePageList'>
  <div class='overflowable-container'>
    <div class='overflowable-contents'>
      <div class='container'>
        <b:with value='true' var='overflow'>
        <b:with value='&quot;tabs&quot;' var='pageListClass'>
          <b:include name='pageList'/>
        </b:with>
        </b:with>
      </div>
    </div>
    <div class='overflow-button hidden'>
      <b:include name='overflowButton'/>
    </div>
  </div>
</b:includable>
    <b:includable id='pageLink'>
  <li>
    <b:class cond='data:overflow' name='overflowable-item'/>
    <b:class cond='data:link.isCurrentPage' name='selected'/>

    <a expr:href='data:link.href'><data:link.title/></a>
  </li>
</b:includable>
    <b:includable id='pageList'>
  <ul>
    <b:class cond='data:pageListClass' expr:name='data:pageListClass'/>
    <b:loop values='data:links' var='link'>
      <b:include name='pageLink'/>
    </b:loop>
  </ul>
</b:includable>
  </b:widget>
</b:section>
<div class='Treelists'>
  <b:section class='trelists' id='Postnw1'/>
  <b:section class='trelists' id='Postnw2'/>
  <b:section class='trelists' id='Postnw3'/>
</div>
</b:if>
</b:if>

<div class='bocker'>
<div class='r-r'>

<b:if cond='data:skin.vars.MopileFasterVirson == &quot;2px&quot; and data:blog.isMobileRequest'>
<b:else/>
<!-- homepage Posts -->
<div class='contpotg'>
<b:section class='potg' cond='data:view.isHomepage' id='Postcs1'>
  <b:widget id='BlogSearch3' locked='false' title='بحث هذه المدونة الإلكترونية' type='BlogSearch' visible='false'>
    <b:includable id='main'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
    <b:includable id='content'>
  <div class='widget-content' role='search'>
    <b:include name='searchForm'/>
  </div>
</b:includable>
    <b:includable id='searchForm'>
  <form expr:action='data:blog.searchUrl'>
    <b:attr cond='not data:view.isPreview' name='target' value='_top'/>
    <b:include name='urlParamsAsFormInput'/>
    <div class='search-input'>
      <input autocomplete='off' expr:aria-label='data:messages.searchThisBlog' expr:placeholder='data:messages.searchThisBlog' expr:value='data:view.isSearch ? data:view.search.query.escaped : &quot;&quot;' name='q'/>
    </div>
    <b:include name='searchSubmit'/>
  </form>
</b:includable>
    <b:includable id='searchSubmit'>
  <input class='search-action' expr:value='data:messages.search.escaped' type='submit'/>
</b:includable>
  </b:widget>
</b:section>
<b:section class='potg sides' cond='data:view.isHomepage' id='Postcs2'>
  <b:widget id='Label1' locked='false' title='الأكثر مشاهدة' type='Label' visible='false'>
    <b:widget-settings>
      <b:widget-setting name='sorting'>FREQUENCY</b:widget-setting>
      <b:widget-setting name='display'>CLOUD</b:widget-setting>
      <b:widget-setting name='selectedLabelsList'/>
      <b:widget-setting name='showType'>ALL</b:widget-setting>
      <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main' var='this'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
    <b:includable id='3colList'>
<div class='Sp-3colList'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='cloud'>
  <b:loop values='data:labels' var='label'>
    <span class='label-size'>
      <b:class expr:name='&quot;label-size-&quot; + data:label.cssSize'/>
      <a class='label-name' expr:href='data:label.url'>
        <data:label.name/>
        <b:if cond='data:this.showFreqNumbers'>
          <span class='label-count'><data:label.count/></span>
        </b:if>
      </a>
    </span>
  </b:loop>
</b:includable>
    <b:includable id='content'>
      <b:if cond='data:widget.sectionId == &quot;TopPost-sc&quot; or data:widget.sectionId == &quot;BotPostsc&quot;'>
        <b:if cond='data:title contains &quot;[slide]&quot;'><b:include name='slide'/>
          <b:elseif cond='data:title contains &quot;[3colList]&quot;'/><b:include name='3colList'/>
          <b:else/><b:include name='slide'/>
        </b:if>
        <b:elseif cond='data:widget.sectionId == &quot;Postcs2&quot; or data:widget.sectionId == &quot;Postcs3&quot; or data:widget.sectionId == &quot;Postcs6&quot; or data:widget.sectionId == &quot;Postcs7&quot;'/>
        <b:if cond='data:title contains &quot;[posts3]&quot;'><b:include name='posts3'/>
          <b:elseif cond='data:title contains &quot;[posts4]&quot;'/><b:include name='posts4'/>
          <b:elseif cond='data:title contains &quot;[posts6]&quot;'/><b:include name='posts6'/>
          <b:else/><b:include name='posts3'/>
        </b:if>
        <b:elseif cond='data:widget.sectionId == &quot;sidepar&quot;'/>
        <b:if cond='data:title contains &quot;[posts3]&quot;'><b:include name='posts3'/>
          <b:elseif cond='data:title contains &quot;[posts4]&quot;'/><b:include name='posts4'/>
          <b:elseif cond='data:title contains &quot;[posts6]&quot;'/><b:include name='posts6'/>
          <b:else/><b:include name='default'/>
        </b:if>
        <b:elseif cond='data:widget.sectionId == &quot;Postcs1&quot; or data:widget.sectionId == &quot;Postcs4&quot; or data:widget.sectionId == &quot;Postcs5&quot; or data:widget.sectionId == &quot;Postcs8&quot;'/>
        <b:if cond='data:title contains &quot;[posts1]&quot;'><b:include name='posts1'/>
          <b:elseif cond='data:title contains &quot;[posts0]&quot;'/><b:include name='posts0'/>
          <b:elseif cond='data:title contains &quot;[posts2]&quot;'/><b:include name='posts2'/>
          <b:elseif cond='data:title contains &quot;[posts6]&quot;'/><b:include name='posts6'/>
          <b:elseif cond='data:title contains &quot;[posts5]&quot;'/><b:include name='posts5'/>
          <b:elseif cond='data:title contains &quot;[postsNormal]&quot;'/><b:include name='postsNormal'/>
          <b:else/><b:include name='postsNormal'/>
        </b:if>
        <b:elseif cond='data:widget.sectionId == &quot;Postnw1&quot; or data:widget.sectionId == &quot;Postnw2&quot; or data:widget.sectionId == &quot;Postnw3&quot; or data:widget.sectionId == &quot;Postnw4&quot; or data:widget.sectionId == &quot;Postnw5&quot; or data:widget.sectionId == &quot;Postnw6&quot;'/>
        <b:if cond='data:title contains &quot;[posts3]&quot;'><b:include name='posts3'/>
          <b:elseif cond='data:title contains &quot;[posts4]&quot;'/><b:include name='posts4'/>
          <b:elseif cond='data:title contains &quot;[posts6]&quot;'/><b:include name='posts6'/>
          <b:else/><b:include name='posts3'/>
        </b:if>
        <b:else/>
        <b:include name='default'/>
      </b:if>
    </b:includable>
    <b:includable id='default'>
  <div class='widget-content'>
    <b:class expr:name='data:this.display + &quot;-label-widget-content&quot;'/>
    <b:include cond='data:this.display == &quot;list&quot;' name='list'/>
    <b:include cond='data:this.display == &quot;cloud&quot;' name='cloud'/>
  </div>
    </b:includable>
    <b:includable id='list'>
  <ul>
    <b:loop values='data:labels' var='label'>
      <li>
        <a class='label-name' expr:href='data:label.url'>
          <data:label.name/>
          <b:if cond='data:this.showFreqNumbers'>
            <span class='label-count'><data:label.count/></span>
          </b:if>
        </a>
      </li>
    </b:loop>
  </ul>
</b:includable>
    <b:includable id='posts0'>
<div class='Sp-posts0'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts1'>
<div class='Sp-posts1'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg></div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts2'>
<div class='Sp-posts2'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts3'>
<div class='Sp-posts3'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts4'>
<div class='Sp-posts4'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts5'>
<div class='Sp-posts5'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts6'>
<div class='Sp-posts6'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg></div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='postsNormal'>
<div class='Sp-Normal'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='slide'>
<div class='Sp-slide'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
  </b:widget>
</b:section>
<b:section class='potg sides' cond='data:view.isHomepage' id='Postcs3'>
  <b:widget id='Label4' locked='false' title='مواضيع شائعة' type='Label' visible='false'>
    <b:widget-settings>
      <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
      <b:widget-setting name='display'>LIST</b:widget-setting>
      <b:widget-setting name='selectedLabelsList'/>
      <b:widget-setting name='showType'>ALL</b:widget-setting>
      <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main' var='this'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
    <b:includable id='3colList'>
<div class='Sp-3colList'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='cloud'>
  <b:loop values='data:labels' var='label'>
    <span class='label-size'>
      <b:class expr:name='&quot;label-size-&quot; + data:label.cssSize'/>
      <a class='label-name' expr:href='data:label.url'>
        <data:label.name/>
        <b:if cond='data:this.showFreqNumbers'>
          <span class='label-count'><data:label.count/></span>
        </b:if>
      </a>
    </span>
  </b:loop>
</b:includable>
    <b:includable id='content'>
      <b:if cond='data:widget.sectionId == &quot;TopPost-sc&quot; or data:widget.sectionId == &quot;BotPostsc&quot;'>
        <b:if cond='data:title contains &quot;[slide]&quot;'><b:include name='slide'/>
          <b:elseif cond='data:title contains &quot;[3colList]&quot;'/><b:include name='3colList'/>
          <b:else/><b:include name='slide'/>
        </b:if>
        <b:elseif cond='data:widget.sectionId == &quot;Postcs2&quot; or data:widget.sectionId == &quot;Postcs3&quot; or data:widget.sectionId == &quot;Postcs6&quot; or data:widget.sectionId == &quot;Postcs7&quot;'/>
        <b:if cond='data:title contains &quot;[posts3]&quot;'><b:include name='posts3'/>
          <b:elseif cond='data:title contains &quot;[posts4]&quot;'/><b:include name='posts4'/>
          <b:elseif cond='data:title contains &quot;[posts6]&quot;'/><b:include name='posts6'/>
          <b:else/><b:include name='posts3'/>
        </b:if>
        <b:elseif cond='data:widget.sectionId == &quot;sidepar&quot;'/>
        <b:if cond='data:title contains &quot;[posts3]&quot;'><b:include name='posts3'/>
          <b:elseif cond='data:title contains &quot;[posts4]&quot;'/><b:include name='posts4'/>
          <b:elseif cond='data:title contains &quot;[posts6]&quot;'/><b:include name='posts6'/>
          <b:else/><b:include name='default'/>
        </b:if>
        <b:elseif cond='data:widget.sectionId == &quot;Postcs1&quot; or data:widget.sectionId == &quot;Postcs4&quot; or data:widget.sectionId == &quot;Postcs5&quot; or data:widget.sectionId == &quot;Postcs8&quot;'/>
        <b:if cond='data:title contains &quot;[posts1]&quot;'><b:include name='posts1'/>
          <b:elseif cond='data:title contains &quot;[posts0]&quot;'/><b:include name='posts0'/>
          <b:elseif cond='data:title contains &quot;[posts2]&quot;'/><b:include name='posts2'/>
          <b:elseif cond='data:title contains &quot;[posts6]&quot;'/><b:include name='posts6'/>
          <b:elseif cond='data:title contains &quot;[posts5]&quot;'/><b:include name='posts5'/>
          <b:elseif cond='data:title contains &quot;[postsNormal]&quot;'/><b:include name='postsNormal'/>
          <b:else/><b:include name='postsNormal'/>
        </b:if>
        <b:elseif cond='data:widget.sectionId == &quot;Postnw1&quot; or data:widget.sectionId == &quot;Postnw2&quot; or data:widget.sectionId == &quot;Postnw3&quot; or data:widget.sectionId == &quot;Postnw4&quot; or data:widget.sectionId == &quot;Postnw5&quot; or data:widget.sectionId == &quot;Postnw6&quot;'/>
        <b:if cond='data:title contains &quot;[posts3]&quot;'><b:include name='posts3'/>
          <b:elseif cond='data:title contains &quot;[posts4]&quot;'/><b:include name='posts4'/>
          <b:elseif cond='data:title contains &quot;[posts6]&quot;'/><b:include name='posts6'/>
          <b:else/><b:include name='posts3'/>
        </b:if>
        <b:else/>
        <b:include name='default'/>
      </b:if>
    </b:includable>
    <b:includable id='default'>
  <div class='widget-content'>
    <b:class expr:name='data:this.display + &quot;-label-widget-content&quot;'/>
    <b:include cond='data:this.display == &quot;list&quot;' name='list'/>
    <b:include cond='data:this.display == &quot;cloud&quot;' name='cloud'/>
  </div>
    </b:includable>
    <b:includable id='list'>
  <ul>
    <b:loop values='data:labels' var='label'>
      <li>
        <a class='label-name' expr:href='data:label.url'>
          <data:label.name/>
          <b:if cond='data:this.showFreqNumbers'>
            <span class='label-count'><data:label.count/></span>
          </b:if>
        </a>
      </li>
    </b:loop>
  </ul>
</b:includable>
    <b:includable id='posts0'>
<div class='Sp-posts0'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts1'>
<div class='Sp-posts1'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg></div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts2'>
<div class='Sp-posts2'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts3'>
<div class='Sp-posts3'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts4'>
<div class='Sp-posts4'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts5'>
<div class='Sp-posts5'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts6'>
<div class='Sp-posts6'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg></div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='postsNormal'>
<div class='Sp-Normal'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='slide'>
<div class='Sp-slide'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
  </b:widget>
</b:section>
<b:section class='potg' cond='data:view.isHomepage' id='Postcs4'/>
</div>
</b:if>

<b:section id='Tempnec' maxwidgets='1' showaddelement='no'>
  <b:widget id='Blog1' locked='true' title='رسائل المدونة الإلكترونية' type='Blog' version='2' visible='true'>
    <b:widget-settings>
      <b:widget-setting name='commentLabel'>comments</b:widget-setting>
      <b:widget-setting name='showShareButtons'>true</b:widget-setting>
      <b:widget-setting name='authorLabel'>كتب:</b:widget-setting>
      <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
      <b:widget-setting name='timestampLabel'>آخر تحديث:</b:widget-setting>
      <b:widget-setting name='reactionsLabel'/>
      <b:widget-setting name='showAuthorProfile'>false</b:widget-setting>
      <b:widget-setting name='style.layout'>1x1</b:widget-setting>
      <b:widget-setting name='showLocation'>false</b:widget-setting>
      <b:widget-setting name='showTimestamp'>true</b:widget-setting>
      <b:widget-setting name='postsPerAd'>1</b:widget-setting>
      <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
      <b:widget-setting name='showDateHeader'>false</b:widget-setting>
      <b:widget-setting name='style.textcolor'>#ffffff</b:widget-setting>
      <b:widget-setting name='showCommentLink'>true</b:widget-setting>
      <b:widget-setting name='style.urlcolor'>#ffffff</b:widget-setting>
      <b:widget-setting name='postLocationLabel'>Location:</b:widget-setting>
      <b:widget-setting name='showAuthor'>false</b:widget-setting>
      <b:widget-setting name='style.linkcolor'>#ffffff</b:widget-setting>
      <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
      <b:widget-setting name='showLabels'>true</b:widget-setting>
      <b:widget-setting name='postLabelsLabel'>القسم:</b:widget-setting>
      <b:widget-setting name='showBacklinks'>false</b:widget-setting>
      <b:widget-setting name='showInlineAds'>false</b:widget-setting>
      <b:widget-setting name='showReactions'>false</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main' var='this'>
      <b:if cond='data:view.isError'>
        <b:include name='sp-errorPage'/>
        <b:else/>
      <b:if cond='not data:view.isSingleItem and not data:view.isError'>
        <b:if cond='data:view.isHomepage'>
          <div class='headline'>
            <h2 class='title'><data:messages.latestPosts/></h2>
            <a class='Lapel-Link' expr:href='data:blog.searchUrl'><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
Show more
<b:else/>
عرض المزيد
</b:if></a>
          </div>
          <b:else/>
          <div class='headline'>
            <h1 class='title'><b:if cond='data:blog.pageName'><data:blog.pageName/><b:else/><data:messages.latestPosts/></b:if></h1>
          </div>
        </b:if>
      </b:if>
        <div class='blog-posts hfeed'>
            <b:loop index='i' values='data:posts' var='post'>
              <div class='post-outer'><b:include data='post' name='post'/></div>
            </b:loop>
        </div>
      </b:if>
        <b:include cond='data:view.isMultipleItems' name='sp-nextprev'/>
      <b:include cond='not data:view.isSingleItem' data='posts' name='jquery'/>
    </b:includable>
    <b:includable id='PagePrake'>
<b:if cond='data:view.isPost'>
      <b:if cond='data:post.body contains &quot;↔&quot;'>
	<b:if cond='data:blog.view != &quot;fullContent&quot;'>
		<script type='text/javascript'>/*<![CDATA[*/
if(-1==document.querySelector(".post-body").innerHTML.indexOf("↚")){
var content =document.querySelector(".post-body").innerHTML,
content=content.substring(0,content.indexOf("↔"))
content+="<div id='s7bcent-a3lan-PagePrake'/><div class='PagePrakediv'><a href='?view=fullContent' >"+ReadMore+"</a></div>",
document.querySelector(".post-body").innerHTML = content;
document.querySelector(".post-body").innerHTML = document.querySelector(".post-body").innerHTML.replace(new RegExp("↔","g"),"");
}


/*]]>*/</script>
      <b:else/>

	<script>/*<![CDATA[*/
document.querySelector(".post-body").innerHTML = document.querySelector(".post-body").innerHTML.replace(new RegExp("↔","g"),"");
if(window.location.toString().indexOf("?view")){var e=window.location.toString().substring(0,window.location.toString().indexOf("?view"));window.history.replaceState({},document.title,e)}
/*]]>*/</script>
        </b:if>
      </b:if>
      </b:if>
</b:includable>
    <b:includable id='aboutPostAuthor'/>
    <b:includable id='addComments'>
  <a expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
    <b:message name='messages.postAComment'/>
  </a>
</b:includable>
    <b:includable id='article-author'>
      <b:if cond='data:widgets.Blog.first.allBylineItems.author or data:view.isPage'>
        <!-- Post Author -->
        <div class='article-author vcard'>
<div class='headbost'>
<svg aria-hidden='true' class='small-icon' data-icon='user-edit' data-prefix='far' role='img' viewBox='0 0 640 512' xmlns='http://www.w3.org/2000/svg'><path class='' d='M358.9 433.3l-6.8 61c-1.1 10.2 7.5 18.8 17.6 17.6l60.9-6.8 137.9-137.9-71.7-71.7-137.9 137.8zM633 268.9L595.1 231c-9.3-9.3-24.5-9.3-33.8 0l-41.8 41.8 71.8 71.7 41.8-41.8c9.2-9.3 9.2-24.4-.1-33.8zM223.9 288c79.6.1 144.2-64.5 144.1-144.1C367.9 65.6 302.4.1 224.1 0 144.5-.1 79.9 64.5 80 144.1c.1 78.3 65.6 143.8 143.9 143.9zm-4.4-239.9c56.5-2.6 103 43.9 100.4 100.4-2.3 49.2-42.1 89.1-91.4 91.4-56.5 2.6-103-43.9-100.4-100.4 2.3-49.3 42.2-89.1 91.4-91.4zM134.4 352c14.6 0 38.3 16 89.6 16 51.7 0 74.9-16 89.6-16 16.7 0 32.2 5 45.5 13.3l34.4-34.4c-22.4-16.7-49.8-26.9-79.9-26.9-28.7 0-42.5 16-89.6 16-47.1 0-60.8-16-89.6-16C60.2 304 0 364.2 0 438.4V464c0 26.5 21.5 48 48 48h258.3c-3.8-14.6-2.2-20.3.9-48H48v-25.6c0-47.6 38.8-86.4 86.4-86.4z' fill='#aaa'/></svg>
</div>
          <b:if cond='data:post.author.profileUrl'>
            <a class='author-prof url author' expr:href='data:post.author.profileUrl' expr:title='data:post.author.name'>
              <span class='fn'><data:post.author.name/></span>
            </a>
            <b:else/>
            <span class='fn'><data:post.author.name/></span>
          </b:if>
        </div>
      </b:if>
    </b:includable>
    <b:includable id='article-commint'>
<b:if cond='data:post.allowComments'>
<div class='commint-cont'><a href='#comments'><svg aria-hidden='true' class='small-icon' data-prefix='fal' focusable='false' role='img' viewBox='0 0 512 512' xmlns='http://www.w3.org/2000/svg'><path d='M280 272H136c-4.4 0-8 3.6-8 8v16c0 4.4 3.6 8 8 8h144c4.4 0 8-3.6 8-8v-16c0-4.4-3.6-8-8-8zm96-96H136c-4.4 0-8 3.6-8 8v16c0 4.4 3.6 8 8 8h240c4.4 0 8-3.6 8-8v-16c0-4.4-3.6-8-8-8zM256 32C114.6 32 0 125.1 0 240c0 47.6 19.9 91.2 52.9 126.3C38 405.7 7 439.1 6.5 439.5c-6.6 7-8.4 17.2-4.6 26S14.4 480 24 480c61.5 0 110-25.7 139.1-46.3C192 442.8 223.2 448 256 448c141.4 0 256-93.1 256-208S397.4 32 256 32zm0 384c-28.3 0-56.3-4.3-83.2-12.8l-15.2-4.8-13 9.2c-23 16.3-58.5 35.3-102.6 39.6 12-15.1 29.8-40.4 40.8-69.6l7.1-18.7-13.7-14.6C47.3 313.7 32 277.6 32 240c0-97 100.5-176 224-176s224 79 224 176-100.5 176-224 176z' fill='currentColor'/></svg>
(<data:post.numberOfComments/>)</a>
</div>
      </b:if>
    </b:includable>
    <b:includable id='article-time'>
      <b:if cond='data:widgets.Blog.first.allBylineItems.timestamp or data:view.isPage'>
        <div class='article-timeago'>
<div class='headbost'>
<svg class='small-icon' viewBox='0 0 30 30'><path d='M12 2c5.514 0 10 4.486 10 10s-4.486 10-10 10-10-4.486-10-10 4.486-10 10-10zm0-2c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm1 12v-6h-2v8h7v-2h-5z' fill='#aaa'/></svg>
</div>
          <a expr:href='data:post.url' expr:title='format(data:post.date, &quot;dd MMMM YYYY&quot;)' rel='bookmark'>
            <time class='post-date published updated' expr:datetime='data:post.lastUpdated.iso8601'>
              <b:eval expr='format(data:post.lastUpdated, &quot;dd MMMM YYYY&quot;)'/>
            </time>
          </a>
        </div>
      </b:if>
    </b:includable>
    <b:includable id='blogThisShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
    <b:includable id='bylineByName' var='byline'>
  <b:switch var='data:byline.name'>
  <b:case value='share'/>
    <b:include cond='data:post.shareUrl' name='postShareButtons'/>
  <b:case value='comments'/>
    <b:include cond='data:post.allowComments' name='postCommentsLink'/>
  <b:case value='location'/>
    <b:include cond='data:post.location' name='postLocation'/>
  <b:case value='timestamp'/>
    <b:include cond='not data:view.isPage' name='postTimestamp'/>
  <b:case value='author'/>
    <b:include name='postAuthor'/>
  <b:case value='labels'/>
    <b:include cond='data:post.labels' name='postLabels'/>
  <b:case value='icons'/>
    <b:include cond='data:post.emailPostUrl' name='emailPostIcon'/>
  </b:switch>
</b:includable>
    <b:includable id='bylineRegion' var='regionItems'>
  <b:loop values='data:regionItems' var='byline'>
    <b:include data='byline' name='bylineByName'/>
  </b:loop>
</b:includable>
    <b:includable id='commentAuthorAvatar'/>
    <b:includable id='commentDeleteIcon' var='comment'/>
    <b:includable id='commentForm' var='post'>
       <div class='comment-form' id='commentTarget'>
    <a name='comment-form'/>
	<div class='conart'>
	<svg aria-hidden='true' class='small-icon' data-prefix='fas' focusable='false' role='img' viewBox='0 0 576 512' xmlns='http://www.w3.org/2000/svg'><path d='M416 224V64c0-35.3-28.7-64-64-64H64C28.7 0 0 28.7 0 64v160c0 35.3 28.7 64 64 64v54.2c0 8 9.1 12.6 15.5 7.8l82.8-62.1H352c35.3.1 64-28.6 64-63.9zm96-64h-64v64c0 52.9-43.1 96-96 96H192v64c0 35.3 28.7 64 64 64h125.7l82.8 62.1c6.4 4.8 15.5.2 15.5-7.8V448h32c35.3 0 64-28.7 64-64V224c0-35.3-28.7-64-64-64z' fill='currentColor'/></svg>
    <h4 id='comment-post-message'><data:messages.postAComment/></h4>
    <b:if cond='data:this.messages.blogComment != &quot;&quot;'>
      <p><data:this.messages.blogComment/></p>
    </b:if>
    </div>
    <b:include data='post' name='commentFormIframeSrc'/>

    <div class='asfafafqw'/>
<b:if cond='data:skin.vars.MopileFasterVirson == &quot;2px&quot; and data:blog.isMobileRequest'>

<b:tag name='script' type='text/javascript'>
document.getElementById(&quot;opencmt&quot;).addEventListener(&quot;click&quot;, function(th){
document.getElementById(&quot;opencmt&quot;).style.display = &quot;none&quot;;
document.getElementById(&quot;comments&quot;).style.display = &quot;block&quot;;
if(jsjq){
var script = document.createElement(&quot;script&quot;);
script.src = &quot;https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js&quot;;
document.head.appendChild(script);
jsjq = 0;
  script.onload = function () {
comtmt()
};
}else{comtmt()}


  
function comtmt(){
$( document ).ready(function() {
$commActive = 0;
  if(!$commActive) commActive();
function commActive(){
$commActive = 1;
  var asafah = `<iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight ?: &quot;90px&quot;' expr:src='data:commentFormIframeSrc' frameborder='0' id='comment-editor' name='comment-editor' width='100%'/>`;

  $(&#39;.asfafafqw&#39;).html(asafah)

  $.getScript( &quot;https://www.blogger.com/static/v1/jsbin/1769009776-comment_from_post_iframe.js&quot;, function() {
  BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
  });

 }
});
}
});


</b:tag>
<b:else/>
<b:tag name='script' type='text/javascript'>
$( document ).ready(function() {
$commActive = 0;
if ($(window).scrollTop() &gt; 90) {
  if(!$commActive) commActive();
}
$(window).scroll(function() {
  if ($(window).scrollTop() &gt; 90) {
	if(!$commActive) commActive();
  }
});
function commActive(){
$commActive = 1;
  var asafah = `<iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight ?: &quot;90px&quot;' expr:src='data:commentFormIframeSrc' frameborder='0' id='comment-editor' name='comment-editor' width='100%'/>`;

  $(&#39;.asfafafqw&#39;).html(asafah)

  $.getScript( &quot;https://www.blogger.com/static/v1/jsbin/1769009776-comment_from_post_iframe.js&quot;, function() {
  BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
  });

}
});
</b:tag>
</b:if>
  </div>
    </b:includable>
    <b:includable id='commentFormIframeSrc' var='post'>
      <a expr:href='data:post.commentFormIframeSrc + &quot;&amp;skin=contempo&quot;' id='comment-editor-src'/>
    </b:includable>
    <b:includable id='commentItem' var='comment'>
<div class='comment' expr:id='&quot;c&quot; + data:comment.id'>
    <b:include cond='data:blog.enabledCommentProfileImages' name='commentAuthorAvatar'/>

    <div class='comment-block'>
      <div class='comment-author'>
        <b:if cond='data:comment.authorUrl'>
          <b:message name='messages.authorSaidWithLink'>
            <b:param expr:value='data:comment.author' name='authorName'/>
            <b:param expr:value='data:comment.authorUrl' name='authorUrl'/>
          </b:message>
        <b:else/>
          <b:message name='messages.authorSaid'>
            <b:param expr:value='data:comment.author' name='authorName'/>
          </b:message>
        </b:if>
      </div>
      <div expr:class='&quot;comment-body&quot; + (data:comment.isDeleted ? &quot; deleted&quot; : &quot;&quot;)'>
        <data:comment.body/>
      </div>
      <div class='comment-footer'>
        <span class='comment-timestamp'>
          <a expr:href='data:comment.url' title='comment permalink'>
            <data:comment.timestamp/>
          </a>
          <b:include data='comment' name='commentDeleteIcon'/>
        </span>
      </div>
    </div>
  </div>
    </b:includable>
    <b:includable id='commentList' var='comments'/>
    <b:includable id='commentPicker' var='post'>
      <b:if cond='data:post.showThreadedComments'>
    <b:include data='post' name='threadedComments'/>
  <b:else/>
    <b:include data='post' name='comments'/>
  </b:if>
    </b:includable>
    <b:includable id='comments' var='post'>
  <section expr:class='&quot;comments&quot; + (data:post.embedCommentForm ? &quot; embed&quot; : &quot;&quot;)' expr:data-num-comments='data:post.numberOfComments' id='comments'>
    <a name='comments'/>
    <b:if cond='data:post.allowComments'>

      <b:include name='commentsTitle'/>

      <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
        <b:include cond='data:post.comments' data='post.comments' name='commentList'/>
      </div>

      <b:if cond='data:post.commentPagingRequired'>
        <div class='paging-control-container'>
          <b:if cond='data:post.hasOlderLinks'>
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
              <data:messages.oldest/>
            </a>
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
              <data:messages.older/>
            </a>
          </b:if>

          <span class='comment-range-text'>
            <data:post.commentRangeText/>
          </span>

          <b:if cond='data:post.hasNewerLinks'>
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
              <data:messages.newer/>
            </a>
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
              <data:messages.newest/>
            </a>
          </b:if>
        </div>
      </b:if>

      <div class='footer'>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='commentForm'/>
          <b:else/>
            <data:post.noNewCommentsText/>
          </b:if>
        <b:else/>
          <b:if cond='data:post.allowComments'>
            <b:include data='post' name='addComments'/>
          </b:if>
        </b:if>
      </div>
    </b:if>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='allowtransparency' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>
  </section>
    </b:includable>
    <b:includable id='commentsLink'/>
    <b:includable id='commentsLinkIframe'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
    <b:includable id='commentsTitle'>
      <div class='headline commentsTitle'><h3 class='title'><data:messages.comments/></h3></div>
</b:includable>
    <b:includable id='defaultAdUnit'>
  <ins class='adsbygoogle' data-ad-format='auto' expr:data-ad-client='data:adClientId ?: data:blog.adsenseClientId' expr:data-ad-host='data:blog.adsenseHostId' expr:data-analytics-uacct='data:blog.analyticsAccountNumber' expr:style='data:style ?: &quot;display: block;&quot;'/>
  <script>
   (adsbygoogle = window.adsbygoogle || []).push({});
  </script>
</b:includable>
    <b:includable id='emailPostIcon'>
  <span class='byline post-icons'>
    <!-- email post links -->
    <span class='item-action'>
      <a expr:href='data:post.emailPostUrl' expr:title='data:messages.emailPost'>
        <b:include data='{ iconClass: &quot;touch-icon sharing-icon&quot; }' name='emailIcon'/>
      </a>
    </span>
  </span>
</b:includable>
    <b:includable id='facebookShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
    <b:includable id='feedLinks'/>
    <b:includable id='feedLinksBody' var='links'/>
    <b:includable id='footerBylines'>
  <b:if cond='data:widgets.Blog.first.footerBylines'>
    <b:loop index='i' values='data:widgets.Blog.first.footerBylines' var='region'>
      <b:if cond='not data:region.items.empty'>
        <div expr:class='&quot;post-footer-line post-footer-line-&quot; + (data:i + 1)'>
          <b:with value='&quot;footer-&quot; + (data:i + 1)' var='regionName'>
            <b:include data='region.items' name='bylineRegion'/>
          </b:with>
        </div>
      </b:if>
    </b:loop>
  </b:if>
</b:includable>
    <b:includable id='googlePlusShare'>
  <div class='goog-inline-block google-plus-share-container'>
    <g:plusone annotation='inline' expr:href='data:originalUrl.canonical.http' size='medium' source='blogger:blog:plusone'/>
  </div>
</b:includable>
    <b:includable id='headerByline'>
  <b:if cond='data:widgets.Blog.first.headerByline'>
    <div class='post-header'>
      <div class='post-header-line-1'>
        <b:with value='&quot;header-1&quot;' var='regionName'>
          <b:include data='data:widgets.Blog.first.headerByline.items' name='bylineRegion'/>
        </b:with>
      </div>
    </div>
  </b:if>
</b:includable>
    <b:includable id='homePageLink'/>
    <b:includable id='iframeComments' var='post'/>
    <b:includable id='inlineAd' var='post'/>
    <b:includable id='jquery'>
<b:if cond='data:skin.vars.MopileFasterVirson == &quot;2px&quot; and data:blog.isMobileRequest'>
<b:if cond='data:view.isPage'><script src='//ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.m in.js'/></b:if>
<b:else/>
<script src='//ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js'/>
</b:if>
    </b:includable>
    <b:includable id='linkShare'>
  <b:with value='&quot;window.prompt(\&quot;Copy to clipboard: Ctrl+C, Enter\&quot;, \&quot;&quot; + data:originalUrl + &quot;\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
    <b:includable id='manageComments'>
  <a expr:href='data:post.manageCommentsUrl' expr:onclick='data:post.manageCommentsUrlOnclick'>
    <b:message name='messages.manageComments'/>
  </a>
</b:includable>
    <b:includable id='nextPageLink'/>
    <b:includable id='otherSharingButton'>
  <span class='sharing-platform-button sharing-element-other' expr:aria-label='data:messages.shareToOtherApps.escaped' expr:data-url='data:originalUrl' expr:title='data:messages.shareToOtherApps.escaped' role='menuitem' tabindex='-1'>
    <b:with value='{key: &quot;sharingOther&quot;}' var='platform'>
      <b:include name='sharingPlatformIcon'/>
    </b:with>
    <span class='platform-sharing-text'><data:messages.shareOtherApps.escaped/></span>
  </span>
</b:includable>
    <b:includable id='pagenavigation'>
<b:if cond='data:view.isPost'>
      <b:if cond='data:post.body contains &quot;↚&quot; '>
<b:if cond='data:blog.view != &quot;fullContent&quot;'>
        <div class='post-body' id='siki-out'/>
        <div id='s7bcent-a3lan-PagePrake'/>
        <div class='page-navigation'>
<b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
          <div class='siki-next-prev' id='siki_prev'><a><span>prev</span><span class='siki-prev'/></a></div>
          <div class='siki-next-prev' id='siki_next'><a><span>next</span><span class='siki-next'/></a></div>
<b:else/>
          <div class='siki-next-prev' id='siki_prev'><a><span>السابق</span><span class='siki-prev'/></a></div>
          <div class='siki-next-prev' id='siki_next'><a><span>التالي</span><span class='siki-next'/></a></div>
</b:if>
          <div id='siki-page-number'/>
        </div>
        <script>
          //<![CDATA[
var ll = function(l) {
    var e, t, I = decodeURIComponent(window.location.search.substring(1)).split("&");
    for (t = 0; t < I.length; t++)
        if ((e = I[t].split("="))[0] === l) return void 0 === e[1] || e[1]
},
lI = ll("page"),
l1l = document.querySelector("#siki_next"),
l11 = document.querySelector("#siki_prev"),
l1I = document.querySelector(".amp-contnt").innerHTML.split("↚");
document.querySelector(".amp-contnt").parentNode.removeChild(document.querySelector(".amp-contnt"));
var lIl = document.querySelector("#siki-out"),
lI1 = document.querySelector("#siki-page-number");
if (void 0 === lI || 1 == lI){
l11.style.display = "none", l1l.querySelector("a").setAttribute("href", "?page=2"), lIl.innerHTML=l1I[0], lI1.innerHTML = page + " 1 "+ of + " "+ l1I.length;}else {
  lI = parseInt(lI);
if(l1I.length <= lI){l1l.style.display = "none"}
var lII = lI + 1,
    l1ll = lI - 1;
l1l.querySelector("a").setAttribute("href", "?page=" + lII), l11.querySelector("a").setAttribute("href", "?page=" + l1ll), lIl.innerHTML=l1I[l1ll], lI1.innerHTML = page + " "+lI +" "+ of + " "+l1I.length;
}

          //]]>
        </script>
        </b:if>
      </b:if>
      </b:if>
    </b:includable>
    <b:includable id='platformShare'>
  <a expr:class='&quot;goog-inline-block sharing-&quot; + data:platform.key' expr:data-url='data:originalUrl' expr:href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:onclick='data:onclick ? data:onclick : &quot;&quot;' expr:title='data:platform.shareMessage' target='_blank'>
    <span class='share-button-link-text'>
      <data:platform.shareMessage/>
    </span>
  </a>
</b:includable>
    <b:includable id='post' var='post'>
      <article class='post-amp post hentry h-entry'>
        <b:include data='post' name='postMeta'/>
        <b:if cond='not data:view.isSingleItem'>
          <b:include data='post' name='sp-homePosts'/>
          <b:else/>
          <div class='bobxed'>
            <b:include name='jquery'/>
          	<div class='atags'>
              
<b:if cond='data:skin.vars.imgs7b == &quot;2px&quot;'>
<b:if cond='data:view.isPost'>
<b:if cond='data:post.thumbnailUrl'>
<img class='post-thumbnail' expr:alt='data:post.title' expr:src='resizeImage(data:post.thumbnailUrl, 1600)' expr:title='data:post.title'/>
<b:else/>
&lt;img class=&#39;post-thumbnail&#39; alt=&#39;<data:post.title/>&#39; src=&#39;<b:include name='altImage'/>&#39; title=&#39;<data:post.title/>&#39; /&gt;
  </b:if>
</b:if>
</b:if>
          <b:loop index='x' values='data:post.labels' var='label'>
			<b:if cond='data:x == 0 or data:x == 1'>
            <a expr:href='data:label.url' expr:title='&quot;قسم &quot; + data:label.name'><data:label.name/></a>
            </b:if>
          </b:loop>
<b:include data='post' name='sp-postQuickEdit'/>
        </div>
            <b:include data='post' name='postTitle'/>
            <div class='post-meta'>
              <b:include data='post' name='article-author'/>
              <b:include data='post' name='article-time'/>
              <b:include data='post' name='article-commint'/>
            </div>
            <div class='TocList'/>

          </div>
          <b:include data='post' name='postBody'/>
          <div class='hideensa'>
            <b:include data='post' name='sp-sharePost'/>
            <b:if cond='data:skin.vars.nextprev == &quot;1px&quot;'>
            	<b:include cond='data:view.isPost' data='post' name='sp-navigation'/>
            </b:if>
            <b:include data='post' name='sp-postTags'/>
            <b:include data='post' name='sp-reactions'/>
            <b:include data='post' name='sp-aboutPostAuthor'/>
            <b:if cond='data:skin.vars.retposts == &quot;1px&quot;'>
            	<b:include cond='data:view.isPost' data='post' name='sp-RelatedPosts'/>
            </b:if>
          </div>
<b:if cond='data:view.isSingleItem'><b:if cond='data:skin.vars.MopileFasterVirson == &quot;2px&quot; and data:blog.isMobileRequest'>
<b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
<a href='javascript:void(0)' id='opencmt'>View comments</a>
<b:else/>
<a href='javascript:void(0)' id='opencmt'>عرض التعليقات</a>
</b:if>
  <b:else/></b:if></b:if>
 <b:include cond='data:view.isSingleItem' data='post' name='commentPicker'/> 
        </b:if>
      </article>
    </b:includable>
    <b:includable id='postAuthor'>
  <span class='byline post-author vcard'>
    <span class='post-author-label'>
      <data:byline.label/>
    </span>
    <span class='fn'>
      <b:if cond='data:post.author.profileUrl'>
        <meta expr:content='data:post.author.profileUrl'/>
        <a class='g-profile' expr:href='data:post.author.profileUrl' rel='author' title='author profile'>
          <span><data:post.author.name/></span>
        </a>
      <b:else/>
        <span><data:post.author.name/></span>
      </b:if>
    </span>
  </span>
</b:includable>
    <b:includable id='postAuthorProfile' var='post'/>
    <b:includable id='postBody' var='post'>
<b:if cond='data:view.isPost'><b:if cond='data:post.body contains &quot;↔&quot; or data:post.body contains &quot;↚&quot;'><b:else/><div id='tocDiv'/></b:if></b:if>

      <div class='amp-contnt post-body entry-content float-container'>
        <b:if cond='data:view.isPost'><div id='top-a3lan'/></b:if>
        <b:if cond='data:view.isPost'><div id='top-mkan'/></b:if>
        <data:post.body/>
        <b:if cond='data:view.isPost'>
          <b:if cond='data:post.body contains &quot;↔&quot; or data:post.body contains &quot;↚&quot;'><b:else/>
            <div expr:name='data:post.labels.first.name' id='RandomPosts'><div class='post-random'><div id='retloodaar'><svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg></div><div class='newPost'/><div class='newPost'/></div></div>
          </b:if>
          <div id='bot-mkan'/>
        </b:if>

        <b:if cond='data:view.isPost'><div id='bot-a3lan'/></b:if>
        <b:include cond='data:post.body contains &quot;Pagecontactus&quot; and data:view.isPage' name='contactUsJs'/> 
        <b:include cond='data:post.body contains &quot;ArchivePage&quot; and data:view.isPage' name='Archive'/> 
      </div>
		  <b:include name='PagePrake'/>
          <b:include name='pagenavigation'/>
    </b:includable>
    <b:includable id='postBodySnippet' var='post'/>
    <b:includable id='postCommentsAndAd' var='post'/>
    <b:includable id='postCommentsLink'/>
    <b:includable id='postFooter' var='post'/>
    <b:includable id='postFooterAuthorProfile' var='post'/>
    <b:includable id='postHeader' var='post'/>
    <b:includable id='postJumpLink' var='post'>
  <div class='jump-link flat-button'>
    <a expr:href='data:post.url fragment &quot;more&quot;' expr:title='data:post.title'>
      <b:eval expr='data:blog.jumpLinkMessage'/>
    </a>
  </div>
</b:includable>
    <b:includable id='postLabels'>
  <span class='byline post-labels'>
    <span class='byline-label'><data:byline.label/></span>
    <b:loop index='i' values='data:post.labels' var='label'>
      <a expr:href='data:label.url' rel='tag'>
        <data:label.name/>
      </a>
    </b:loop>
  </span>
</b:includable>
    <b:includable id='postLocation'>
  <span class='byline post-location'>
    <data:byline.label/>
    <a expr:href='data:post.location.mapsUrl' target='_blank'><data:post.location.name/></a>
  </span>
</b:includable>
    <b:includable id='postMeta' var='post'>
  <b:include data='post' name='postMetadataJSON'/>
</b:includable>
    <b:includable id='postMetadataJSONImage'>
  &quot;image&quot;: {
    &quot;@type&quot;: &quot;ImageObject&quot;,
    <b:if cond='data:post.featuredImage.isResizable'>
    &quot;url&quot;: &quot;<b:eval expr='resizeImage(data:post.featuredImage, 1200, &quot;1200:630&quot;)'/>&quot;,
    &quot;height&quot;: 630,
    &quot;width&quot;: 1200
    <b:else/>
    &quot;url&quot;: &quot;https://lh3.googleusercontent.com/ULB6iBuCeTVvSjjjU1A-O8e9ZpVba6uvyhtiWRti_rBAs9yMYOFBujxriJRZ-A=w1200&quot;,
    &quot;height&quot;: 348,
    &quot;width&quot;: 1200
    </b:if>
  },
</b:includable>
    <b:includable id='postMetadataJSONPublisher'>
 &quot;publisher&quot;: {
    &quot;@type&quot;: &quot;Organization&quot;,
    &quot;name&quot;: &quot;Blogger&quot;,
    &quot;logo&quot;: {
      &quot;@type&quot;: &quot;ImageObject&quot;,
      &quot;url&quot;: &quot;https://lh3.googleusercontent.com/ULB6iBuCeTVvSjjjU1A-O8e9ZpVba6uvyhtiWRti_rBAs9yMYOFBujxriJRZ-A=h60&quot;,
      &quot;width&quot;: 206,
      &quot;height&quot;: 60
    }
  },
</b:includable>
    <b:includable id='postPagination'/>
    <b:includable id='postReactions'>
  <!-- Reaction feature no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
    <b:includable id='postShareButtons'>
  <div class='byline post-share-buttons goog-inline-block'>
    <b:with value='data:sharingId ?: ((data:widget.instanceId ?: &quot;sharing&quot;) + &quot;-&quot; + (data:regionName ?: &quot;byline&quot;) + &quot;-&quot; + data:post.id)' var='sharingId'>
      <!-- Note: 'sharingButtons' includable is from the default Sharing widget markup. -->
      <b:include data='{                                                sharingId: data:sharingId,                                                originalUrl: data:post.url,                                                platforms: data:this.sharing.platforms,                                                shareUrl: data:post.shareUrl,                                                shareTitle: data:post.title,                                              }' name='sharingButtons'/>
    </b:with>
  </div>
</b:includable>
    <b:includable id='postTimestamp'>
  <span class='byline post-timestamp'>
    <data:byline.label/>
    <b:if cond='data:post.url'>
      <meta expr:content='data:post.url.canonical'/>
      <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
        <time class='published' expr:datetime='data:post.date.iso8601' expr:title='data:post.date.iso8601'>
          <data:post.date/>
        </time>
      </a>
    </b:if>
  </span>
</b:includable>
    <b:includable id='postTitle' var='post'>
        <h1 class='entry-title topic-title'><data:post.title/></h1>
	</b:includable>
    <b:includable id='previousPageLink'/>
    <b:includable id='sharingButton'>
  <span expr:aria-label='data:platform.shareMessage' expr:class='&quot;sharing-platform-button sharing-element-&quot; + data:platform.key' expr:data-href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:data-url='data:originalUrl' expr:title='data:platform.shareMessage' role='menuitem' tabindex='-1'>
    <b:include name='sharingPlatformIcon'/>
    <span class='platform-sharing-text'><data:platform.name/></span>
  </span>
</b:includable>
    <b:includable id='sharingButtonContent'>
  <div class='flat-icon-button ripple'>
    <b:include name='shareIcon'/>
  </div>
</b:includable>
    <b:includable id='sharingButtons'>
  <div class='sharing' expr:aria-owns='&quot;sharing-popup-&quot; + data:sharingId' expr:data-title='data:shareTitle'>
    <button class='sharing-button touch-icon-button' expr:aria-controls='&quot;sharing-popup-&quot; + data:sharingId' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-button-&quot; + data:sharingId' role='button'>
      <b:include name='sharingButtonContent'/>
    </button>
    <b:include name='sharingButtonsMenu'/>
  </div>
</b:includable>
    <b:includable id='sharingButtonsMenu'>
  <div class='share-buttons-container'>
    <ul aria-hidden='true' class='share-buttons hidden' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-popup-&quot; + data:sharingId' role='menu'>
      <b:loop values='(data:platforms ?: data:blog.sharing.platforms) filter (p =&gt; p.key not in {&quot;blogThis&quot;})' var='platform'>
        <li>
          <b:include name='sharingButton'/>
        </li>
      </b:loop>
      <li aria-hidden='true' class='hidden'>
        <b:include name='otherSharingButton'/>
      </li>
    </ul>
  </div>
</b:includable>
    <b:includable id='sharingPlatformIcon'>
  <b:include data='{ iconClass: (&quot;touch-icon sharing-&quot; + data:platform.key) }' expr:name='data:platform.key + &quot;Icon&quot;'/>
</b:includable>
    <b:includable id='sp-RelatedPosts' var='post'>
      
      <div class='SeoPlusAds' id='ret-a3lan'/>
      
	<div class='RelatedPosts'>
<b:loop index='i' values='data:post.labels' var='label'>
<b:if cond='data:i == 0'>
  <div class='headline RelatedPost'><h3 class='title'><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
Latest articles from
<b:else/>
أخر المواضيع من قسم
</b:if> : <data:label.name/></h3></div>
</b:if>
</b:loop>
<div class='Sp-posts0'>
<b:loop index='i' values='data:post.labels' var='label'>
<b:if cond='data:i == 0'>
<div class='Ajax' expr:name='data:label.name' theam='[None]'>
<svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>
 
</div>
</b:if>
</b:loop>
</div>
</div>
      
    </b:includable>
    <b:includable id='sp-aboutPostAuthor' var='post'>
  <b:if cond='data:post.author.aboutMe and data:view.isPost'>
    <div class='author-posts'>

<b:if cond='data:post.author.authorPhoto.image'>

<div class='authorImage'>
<div class='authorImg'>
<img expr:alt='data:post.author.name' expr:data-src='resizeImage(data:post.author.authorPhoto.image , &quot;72&quot;, &quot;1:1&quot; )' expr:title='data:post.author.name' src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAJAQMAAAAB5D5xAAAAA1BMVEUAAACnej3aAAAAAXRSTlMAQObYZgAAAApJREFUCNdjwA0AABsAAQrj5HwAAAAASUVORK5CYII='/>
</div>
</div>
      
<div class='authorInfo'>
  
<div class='author-name'>
<span><data:post.author.name/></span>
</div>
<div class='author-desc'>
<data:post.author.aboutMe/>
</div>
<ul class='author-link'>
<b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
<li><b:if cond='data:post.author.profileUrl'><a expr:href='data:post.author.profileUrl' rel='nofollow noreferrer' target='_blank' title='View Profile'>Profile</a></b:if></li>
<b:else/>
<li><b:if cond='data:post.author.profileUrl'><a expr:href='data:post.author.profileUrl' rel='nofollow noreferrer' target='_blank' title='عرض الملف الشخصي'>الملف الشخصي</a></b:if></li>
</b:if>
</ul>
  
</div>
<b:else/>
<div class='author-about'>
<div class='author-name'>
 <a class='g-profile' expr:href='data:post.author.profileUrl' title='author profile'>
      <span><data:post.author.name/></span>
    </a>
</div>
<div class='author-desc'>
      <data:post.author.aboutMe/>
    </div>
</div>
      </b:if>

    </div>
  </b:if>
    </b:includable>
    <b:includable id='sp-errorPage'>
            <div id='error-page'>
<svg aria-hidden='true' class='svg-inline--fa fa-exclamation-triangle fa-w-18' data-icon='exclamation-triangle' data-prefix='fas' role='img' viewBox='0 0 576 512' xmlns='http://www.w3.org/2000/svg'><path class='' d='M569.517 440.013C587.975 472.007 564.806 512 527.94 512H48.054c-36.937 0-59.999-40.055-41.577-71.987L246.423 23.985c18.467-32.009 64.72-31.951 83.154 0l239.94 416.028zM288 354c-25.405 0-46 20.595-46 46s20.595 46 46 46 46-20.595 46-46-20.595-46-46-46zm-43.673-165.346l7.418 136c.347 6.364 5.609 11.346 11.982 11.346h48.546c6.373 0 11.635-4.982 11.982-11.346l7.418-136c.375-6.874-5.098-12.654-11.982-12.654h-63.383c-6.884 0-12.356 5.78-11.981 12.654z' fill='currentColor'/></svg>
              <h1 class='errornum'><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
ERROR 404
<b:else/>
خطأ 404
</b:if></h1>
              <h2 class='error'><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
Sorry, the page you are looking for in this blog is not available.
<b:else/>
معذرة, فالصفحة التي تبحث عنها في هذه المدونة ليست متوفرة.
</b:if></h2>
            </div>
<style>
div#error-page {
    display: block;
    text-align: center;
    padding: 30px;
    height: calc((100vh - 245px));
}
.r-r {
    float: none;
    width: 100%;
}
h1.errornum {
    font-size: 80px;
}
h2.error {
    font-size: 23px;
    color: #4e4e4e;
}
.block-side {
    display: none;
}
  @media screen and (max-width:992px){div#error-page {height:auto;}}
</style>
    </b:includable>
    <b:includable id='sp-homePosts' var='post'>

      <b:if cond='data:post.thumbnailUrl'>
        <a class='PLHolder thumb' expr:href='data:post.url' expr:title='data:post.title'>
            <img class='post-thumb' expr:alt='data:post.title' expr:data-src='resizeImage(data:post.thumbnailUrl, 1600)' expr:title='data:post.title' src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAJAQMAAAAB5D5xAAAAA1BMVEUAAACnej3aAAAAAXRSTlMAQObYZgAAAApJREFUCNdjwA0AABsAAQrj5HwAAAAASUVORK5CYII='/>
        </a>
        <b:else/>
        <a class='PLHolder thumb' expr:href='data:post.url' expr:title='data:post.title'>

&lt;img class=&#39;post-thumb&#39; data-src=&#39;<b:include name='altImage'/>&#39; alt=&#39;<data:post.title/>&#39; src=&#39;data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAJAQMAAAAB5D5xAAAAA1BMVEUAAACnej3aAAAAAXRSTlMAQObYZgAAAApJREFUCNdjwA0AABsAAQrj5HwAAAAASUVORK5CYII=&#39;/&gt;


        </a>
      </b:if>

      <div class='post-home'>
        <div class='post-info'>
          <h2 class='posts-titles entry-title p-name'><a class='Title' expr:href='data:post.url' rel='bookmark'><data:post.title/></a></h2>
        </div>
<div class='items'>
          <b:if cond='data:post.author.profileUrl'>
              <a class='author vcard' expr:href='data:post.author.profileUrl'>
<svg aria-hidden='true' class='icon small-icon' data-prefix='fal' focusable='false' role='img' viewBox='0 0 496 512' xmlns='http://www.w3.org/2000/svg'><path d='M248 8C111 8 0 119 0 256s111 248 248 248 248-111 248-248S385 8 248 8zm128 421.6c-35.9 26.5-80.1 42.4-128 42.4s-92.1-15.9-128-42.4V416c0-35.3 28.7-64 64-64 11.1 0 27.5 11.4 64 11.4 36.6 0 52.8-11.4 64-11.4 35.3 0 64 28.7 64 64v13.6zm30.6-27.5c-6.8-46.4-46.3-82.1-94.6-82.1-20.5 0-30.4 11.4-64 11.4S204.6 320 184 320c-48.3 0-87.8 35.7-94.6 82.1C53.9 363.6 32 312.4 32 256c0-119.1 96.9-216 216-216s216 96.9 216 216c0 56.4-21.9 107.6-57.4 146.1zM248 120c-48.6 0-88 39.4-88 88s39.4 88 88 88 88-39.4 88-88-39.4-88-88-88zm0 144c-30.9 0-56-25.1-56-56s25.1-56 56-56 56 25.1 56 56-25.1 56-56 56z' fill='currentColor'/></svg>
            <span class='fn'><data:post.author.name/></span></a>
            <b:else/>
            <span class='vcard'><span class='fn'><data:post.author.name/></span></span>
          </b:if>

<span class='category' style='display: inline-block;'>
<a expr:href='data:post.labels.first.url' expr:title='&quot;قسم &quot; + data:post.labels.first.name' rel='tag' style='display: inline-block;'>
<svg aria-hidden='true' class='icon small-icon' data-icon='tags' data-prefix='fal' focusable='false' role='img' viewBox='0 0 640 512' xmlns='http://www.w3.org/2000/svg'><path d='M625.941 293.823L421.823 497.941c-18.746 18.746-49.138 18.745-67.882 0l-1.775-1.775 22.627-22.627 1.775 1.775c6.253 6.253 16.384 6.243 22.627 0l204.118-204.118c6.238-6.239 6.238-16.389 0-22.627L391.431 36.686A15.895 15.895 0 0 0 380.117 32h-19.549l-32-32h51.549a48 48 0 0 1 33.941 14.059L625.94 225.941c18.746 18.745 18.746 49.137.001 67.882zM252.118 32H48c-8.822 0-16 7.178-16 16v204.118c0 4.274 1.664 8.292 4.686 11.314l211.882 211.882c6.253 6.253 16.384 6.243 22.627 0l204.118-204.118c6.238-6.239 6.238-16.389 0-22.627L263.431 36.686A15.895 15.895 0 0 0 252.118 32m0-32a48 48 0 0 1 33.941 14.059l211.882 211.882c18.745 18.745 18.745 49.137 0 67.882L293.823 497.941c-18.746 18.746-49.138 18.745-67.882 0L14.059 286.059A48 48 0 0 1 0 252.118V48C0 21.49 21.49 0 48 0h204.118zM144 124c-11.028 0-20 8.972-20 20s8.972 20 20 20 20-8.972 20-20-8.972-20-20-20m0-28c26.51 0 48 21.49 48 48s-21.49 48-48 48-48-21.49-48-48 21.49-48 48-48z' fill='currentColor'/></svg>
<data:post.labels.first.name/></a>

</span>
<span class='Date published updated'><svg aria-hidden='true' class='icon small-icon' data-icon='clock' data-prefix='fal' focusable='false' role='img' viewBox='0 0 512 512' xmlns='http://www.w3.org/2000/svg'><path d='M256 8C119 8 8 119 8 256s111 248 248 248 248-111 248-248S393 8 256 8zm216 248c0 118.7-96.1 216-216 216-118.7 0-216-96.1-216-216 0-118.7 96.1-216 216-216 118.7 0 216 96.1 216 216zm-148.9 88.3l-81.2-59c-3.1-2.3-4.9-5.9-4.9-9.7V116c0-6.6 5.4-12 12-12h14c6.6 0 12 5.4 12 12v146.3l70.5 51.3c5.4 3.9 6.5 11.4 2.6 16.8l-8.2 11.3c-3.9 5.3-11.4 6.5-16.8 2.6z' fill='currentColor'/></svg><b:eval expr='format(data:post.date, &quot;dd MMMM YYYY&quot;)'/></span>
</div>
<div class='Short_content entry-content'><data:post.snippets.short/></div>
<a class='moreLink' expr:href='data:post.url' expr:title='data:post.title'><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>read more<b:else/>اقرأ المزيد</b:if></a>
      </div>
    </b:includable>
    <b:includable id='sp-navigation' var='post'>

<b:if cond='data:skin.vars.MopileFasterVirson == &quot;2px&quot; and data:blog.isMobileRequest'>
<b:else/>
      <div class='topic-nav'>

        <div class='topic-nav-wrap'>
          <div class='topic-nav-cont'>
<div class='newPost'>
<b:if cond='data:this.newerPageUrl'>
<a class='next' expr:href='data:this.newerPageUrl'/>
<b:else/> 
<b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
<span>You are now in the first article</span>
  <b:else/>
<span>انت الان في اول مقال</span>
  </b:if>
</b:if>
</div>
<div class='oldPost'>
<b:if cond='data:this.olderPageUrl'>
<a class='prev' expr:href='data:this.olderPageUrl'/>
<b:else/> 
<b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
<span>You are now in the last article</span>
  <b:else/>
<span>انت الان في اخر مقال</span>
  </b:if>
</b:if>
</div>

          </div>
        </div>
      </div>
<script>
//<![CDATA[

! function(n) {
    var e = n(".topic-nav-cont a.next"),
        r = n(".topic-nav-cont a.prev");
    n.get(e.attr("href"), function(t) {
        e.html("<span class='texxattt'>"+NextArticle+"</span> <span class='posttitle'>" + n(t).find(".topic-title").text() + "</span>")
    }, "html"), n.get(r.attr("href"), function(t) {
        r.html("<span class='texxattt'>"+PreviousArticle+"</span> <span class='posttitle'>" + n(t).find(".topic-title").text() + "</span>")
    }, "html")
}(jQuery);

//]]>
</script>
</b:if>

    </b:includable>
    <b:includable id='sp-nextprev'>

      <div expr:class='data:skin.vars.MopileFasterVirson == &quot;2px&quot; and data:blog.isMobileRequest ? &quot;MopileFasterVirson&quot; : &quot;blog-pager&quot;' id='blog-pager'>
        <b:if cond='data:newerPageUrl'>
          <span id='blog-pager-newer-link'>
            <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;'>&#8249;</a>
          </span>
        </b:if>
        <div class='homelink'><a expr:href='data:blog.homepageUrl'><svg aria-hidden='true' data-prefix='fas' focusable='false' viewBox='0 0 576 512' xmlns='http://www.w3.org/2000/svg'><path d='M280.37 148.26L96 300.11V464a16 16 0 0 0 16 16l112.06-.29a16 16 0 0 0 15.92-16V368a16 16 0 0 1 16-16h64a16 16 0 0 1 16 16v95.64a16 16 0 0 0 16 16.05L464 480a16 16 0 0 0 16-16V300L295.67 148.26a12.19 12.19 0 0 0-15.3 0zM571.6 251.47L488 182.56V44.05a12 12 0 0 0-12-12h-56a12 12 0 0 0-12 12v72.61L318.47 43a48 48 0 0 0-61 0L4.34 251.47a12 12 0 0 0-1.6 16.9l25.5 31A12 12 0 0 0 45.15 301l235.22-193.74a12.19 12.19 0 0 1 15.3 0L530.9 301a12 12 0 0 0 16.9-1.6l25.5-31a12 12 0 0 0-1.7-16.93z' fill='currentColor'/></svg></a></div>
        <b:if cond='data:olderPageUrl'>
          <span id='blog-pager-older-link'>
            <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;'>&#8250;</a>
          </span>
        </b:if>
      </div>
      

<b:if cond='data:skin.vars.MopileFasterVirson == &quot;2px&quot; and data:blog.isMobileRequest'>
<b:else/>
      <div class='loadMore'>
        <div class='loadMorePosts'><a href='javascript:void(0)'><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
Show more
<b:else/>
عرض المزيد
</b:if> <svg aria-hidden='true' class='icon-load' focusable='false' role='img' viewBox='0 0 256 512' xmlns='http://www.w3.org/2000/svg'><path d='M119.5 326.9L3.5 209.1c-4.7-4.7-4.7-12.3 0-17l7.1-7.1c4.7-4.7 12.3-4.7 17 0L128 287.3l100.4-102.2c4.7-4.7 12.3-4.7 17 0l7.1 7.1c4.7 4.7 4.7 12.3 0 17L136.5 327c-4.7 4.6-12.3 4.6-17-.1z' fill='currentColor'/></svg></a></div>
        <div id='loader' style='display: none'><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
Showing
<b:else/>
جاري العرض
</b:if> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg></div>
        <div class='noMorePosts' style='display: none'><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
Nothing more
<b:else/>
انتهت المواضيع
</b:if> <svg aria-hidden='true' class='icon-load' data-icon='times' data-prefix='far' role='img' viewBox='0 0 320 512' xmlns='http://www.w3.org/2000/svg'><path d='M207.6 256l107.72-107.72c6.23-6.23 6.23-16.34 0-22.58l-25.03-25.03c-6.23-6.23-16.34-6.23-22.58 0L160 208.4 52.28 100.68c-6.23-6.23-16.34-6.23-22.58 0L4.68 125.7c-6.23 6.23-6.23 16.34 0 22.58L112.4 256 4.68 363.72c-6.23 6.23-6.23 16.34 0 22.58l25.03 25.03c6.23 6.23 16.34 6.23 22.58 0L160 303.6l107.72 107.72c6.23 6.23 16.34 6.23 22.58 0l25.03-25.03c6.23-6.23 6.23-16.34 0-22.58L207.6 256z' fill='currentColor'/></svg></div>
      </div>
</b:if>

    </b:includable>
    <b:includable id='sp-postQuickEdit' var='post'>
<b:if cond='data:view.isPost'>
      <!-- Quick Edit -->
    <span expr:class='&quot;edit-post item-control &quot; + data:post.adminClass'>
      <a expr:href='&quot;https://www.blogger.com/blog/post/edit/&quot; + data:blog.blogId + &quot;/&quot; + data:post.id' target='_blank'> <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
<svg aria-hidden='true' class='svg-inline--fa fa-edit fa-w-18' data-icon='edit' data-prefix='fal' focusable='false' role='img' viewBox='0 0 576 512' xmlns='http://www.w3.org/2000/svg'><path class='' d='M417.8 315.5l20-20c3.8-3.8 10.2-1.1 10.2 4.2V464c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48V112c0-26.5 21.5-48 48-48h292.3c5.3 0 8 6.5 4.2 10.2l-20 20c-1.1 1.1-2.7 1.8-4.2 1.8H48c-8.8 0-16 7.2-16 16v352c0 8.8 7.2 16 16 16h352c8.8 0 16-7.2 16-16V319.7c0-1.6.6-3.1 1.8-4.2zm145.9-191.2L251.2 436.8l-99.9 11.1c-13.4 1.5-24.7-9.8-23.2-23.2l11.1-99.9L451.7 12.3c16.4-16.4 43-16.4 59.4 0l52.6 52.6c16.4 16.4 16.4 43 0 59.4zm-93.6 48.4L403.4 106 169.8 339.5l-8.3 75.1 75.1-8.3 233.5-233.6zm71-85.2l-52.6-52.6c-3.8-3.8-10.2-4-14.1 0L426 83.3l66.7 66.7 48.4-48.4c3.9-3.8 3.9-10.2 0-14.1z' fill='currentColor'/></svg>
<b:else/>
<svg aria-hidden='true' class='svg-inline--fa fa-edit fa-w-18' data-icon='edit' data-prefix='fal' focusable='false' role='img' viewBox='0 0 576 512' xmlns='http://www.w3.org/2000/svg'><path class='' d='M417.8 315.5l20-20c3.8-3.8 10.2-1.1 10.2 4.2V464c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48V112c0-26.5 21.5-48 48-48h292.3c5.3 0 8 6.5 4.2 10.2l-20 20c-1.1 1.1-2.7 1.8-4.2 1.8H48c-8.8 0-16 7.2-16 16v352c0 8.8 7.2 16 16 16h352c8.8 0 16-7.2 16-16V319.7c0-1.6.6-3.1 1.8-4.2zm145.9-191.2L251.2 436.8l-99.9 11.1c-13.4 1.5-24.7-9.8-23.2-23.2l11.1-99.9L451.7 12.3c16.4-16.4 43-16.4 59.4 0l52.6 52.6c16.4 16.4 16.4 43 0 59.4zm-93.6 48.4L403.4 106 169.8 339.5l-8.3 75.1 75.1-8.3 233.5-233.6zm71-85.2l-52.6-52.6c-3.8-3.8-10.2-4-14.1 0L426 83.3l66.7 66.7 48.4-48.4c3.9-3.8 3.9-10.2 0-14.1z' fill='currentColor'/></svg>
</b:if> </a>
  </span></b:if>
<b:if cond='data:view.isPage'>
      <!-- Quick Edit -->
    <span expr:class='&quot;edit-post item-control &quot; + data:post.adminClass'>
      <a expr:href='&quot;https://www.blogger.com/blog/page/edit/&quot; + data:blog.blogId + &quot;/&quot; + data:post.id' target='_blank'> <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
<svg aria-hidden='true' class='svg-inline--fa fa-edit fa-w-18' data-icon='edit' data-prefix='fal' focusable='false' role='img' viewBox='0 0 576 512' xmlns='http://www.w3.org/2000/svg'><path class='' d='M417.8 315.5l20-20c3.8-3.8 10.2-1.1 10.2 4.2V464c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48V112c0-26.5 21.5-48 48-48h292.3c5.3 0 8 6.5 4.2 10.2l-20 20c-1.1 1.1-2.7 1.8-4.2 1.8H48c-8.8 0-16 7.2-16 16v352c0 8.8 7.2 16 16 16h352c8.8 0 16-7.2 16-16V319.7c0-1.6.6-3.1 1.8-4.2zm145.9-191.2L251.2 436.8l-99.9 11.1c-13.4 1.5-24.7-9.8-23.2-23.2l11.1-99.9L451.7 12.3c16.4-16.4 43-16.4 59.4 0l52.6 52.6c16.4 16.4 16.4 43 0 59.4zm-93.6 48.4L403.4 106 169.8 339.5l-8.3 75.1 75.1-8.3 233.5-233.6zm71-85.2l-52.6-52.6c-3.8-3.8-10.2-4-14.1 0L426 83.3l66.7 66.7 48.4-48.4c3.9-3.8 3.9-10.2 0-14.1z' fill='currentColor'/></svg>
<b:else/>
<svg aria-hidden='true' class='svg-inline--fa fa-edit fa-w-18' data-icon='edit' data-prefix='fal' focusable='false' role='img' viewBox='0 0 576 512' xmlns='http://www.w3.org/2000/svg'><path d='M417.8 315.5l20-20c3.8-3.8 10.2-1.1 10.2 4.2V464c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48V112c0-26.5 21.5-48 48-48h292.3c5.3 0 8 6.5 4.2 10.2l-20 20c-1.1 1.1-2.7 1.8-4.2 1.8H48c-8.8 0-16 7.2-16 16v352c0 8.8 7.2 16 16 16h352c8.8 0 16-7.2 16-16V319.7c0-1.6.6-3.1 1.8-4.2zm145.9-191.2L251.2 436.8l-99.9 11.1c-13.4 1.5-24.7-9.8-23.2-23.2l11.1-99.9L451.7 12.3c16.4-16.4 43-16.4 59.4 0l52.6 52.6c16.4 16.4 16.4 43 0 59.4zm-93.6 48.4L403.4 106 169.8 339.5l-8.3 75.1 75.1-8.3 233.5-233.6zm71-85.2l-52.6-52.6c-3.8-3.8-10.2-4-14.1 0L426 83.3l66.7 66.7 48.4-48.4c3.9-3.8 3.9-10.2 0-14.1z' fill='currentColor'/></svg>
</b:if> </a>
  </span></b:if>
  </b:includable>
    <b:includable id='sp-postTags' var='post'>
      <b:if cond='data:widgets.Blog.first.allBylineItems.labels and data:post.labels.any'>
        <!-- Post Labels -->
        <div class='amp-tags'>
          <b:loop values='data:post.labels' var='label'>
<a expr:href='data:label.url' expr:title='data:label.name' rel='tag'><svg aria-hidden='true' class='small-icon' data-icon='tag' data-prefix='fal' role='img' viewBox='0 0 512 512' xmlns='http://www.w3.org/2000/svg'><path d='M497.941 225.941L286.059 14.059A48 48 0 0 0 252.118 0H48C21.49 0 0 21.49 0 48v204.118a48 48 0 0 0 14.059 33.941l211.882 211.882c18.745 18.745 49.137 18.746 67.882 0l204.118-204.118c18.745-18.745 18.745-49.137 0-67.882zm-22.627 45.255L271.196 475.314c-6.243 6.243-16.375 6.253-22.627 0L36.686 263.431A15.895 15.895 0 0 1 32 252.117V48c0-8.822 7.178-16 16-16h204.118c4.274 0 8.292 1.664 11.314 4.686l211.882 211.882c6.238 6.239 6.238 16.39 0 22.628zM144 124c11.028 0 20 8.972 20 20s-8.972 20-20 20-20-8.972-20-20 8.972-20 20-20m0-28c-26.51 0-48 21.49-48 48s21.49 48 48 48 48-21.49 48-48-21.49-48-48-48z' fill='currentColor'/></svg><data:label.name/></a>
          </b:loop>
        </div>
<b:loop index='item' values='data:post.labels' var='label'>
<b:if cond='data:item lt 1'>
<script type='application/ld+json'>{
&quot;@context&quot;: &quot;http://schema.org&quot;,&quot;@type&quot;: &quot;BreadcrumbList&quot;,&quot;itemListElement&quot;: [{&quot;@type&quot;: &quot;ListItem&quot;,&quot;position&quot;: 1,&quot;item&quot;: {&quot;@id&quot;: &quot;<data:blog.homepageUrl.canonical/>&quot;,&quot;name&quot;: &quot;<data:blog.title/>&quot;}},{&quot;@type&quot;: &quot;ListItem&quot;,&quot;position&quot;: 2,&quot;item&quot;: {&quot;@id&quot;: &quot;<data:label.url.canonical/>&quot;,&quot;name&quot;: &quot;<data:label.name/>&quot;}},{&quot;@type&quot;: &quot;ListItem&quot;,&quot;position&quot;: 3,&quot;item&quot;: {&quot;@id&quot;: &quot;<data:post.url.canonical/>&quot;,&quot;name&quot;: &quot;<data:view.title.escaped/>&quot;}}]}</script>
</b:if>
</b:loop>
      </b:if>
    </b:includable>
    <b:includable id='sp-reactions' var='post'>
<b:if cond='!data:view.isPage'>
<b:if cond='data:skin.vars.MopileFasterVirson == &quot;2px&quot; and data:blog.isMobileRequest'>
<b:else/>
      <b:if cond='data:widgets.Blog.first.allBylineItems.reactions'>
        <span class='reaction-buttons'>
          <span class='reactions-label'>
         	<data:widgets.Blog.first.allBylineItems.reactions.label/>
          </span>
          <iframe allowtransparency='true' class='reactions-iframe' expr:data-src='data:post.reactionsUrl' expr:width='data:post.reactionsUrl.size' frameborder='0' name='reactions' scrolling='no'/>
        </span>
<script>
$reacAct =0;
$(document).scroll(function(){if ($(window).scrollTop() &gt; 200) {if(!$reacAct) $(&#39;.reactions-iframe&#39;).attr(&#39;src&#39; , $(&#39;.reactions-iframe&#39;).attr(&#39;data-src&#39;));$reacAct =1;}})
$(window).scroll(function() {if ($(window).scrollTop() &gt; 200) {if(!$reacAct) $(&#39;.reactions-iframe&#39;).attr(&#39;src&#39; , $(&#39;.reactions-iframe&#39;).attr(&#39;data-src&#39;));$reacAct =1;}});
  
</script>
      </b:if>
</b:if>
      </b:if>
    </b:includable>
    <b:includable id='sp-sharePost' var='post'>

      <b:if cond='data:widgets.Blog.first.allBylineItems.share and data:view.isPost'>

      <div class='post-share' data-share='Share'>
        <div class='share-icon shareThis'>
<label for='offshare-check'>
<svg viewBox='0 0 512 512'><circle cx='256' cy='256' r='48'/><circle cx='416' cy='256' r='48'/><circle cx='96' cy='256' r='48'/></svg>
</label>
</div>
<input class='share-check hidden' id='offshare-check' type='checkbox'/>
<div class='share-popup'>
<ul>
<li>
<a expr:href='&quot;https://twitter.com/share?url=&quot;+data:post.url' rel='nofollow noreferrer' target='_blank'>
<svg viewBox='0 0 32 32'><path d='M28.77,8.11a.87.87,0,0,0-.23-.2A4.69,4.69,0,0,0,29,6.54a1,1,0,0,0-.44-1,1,1,0,0,0-1.1,0,6.42,6.42,0,0,1-2.28.92,6.21,6.21,0,0,0-7.08-1A6.07,6.07,0,0,0,15,12.2a1,1,0,0,0,2-.4A4.08,4.08,0,0,1,19,7.28a4.24,4.24,0,0,1,5.12,1,1,1,0,0,0,.88.28l.25,0a1,1,0,0,0,.34,1.62,1,1,0,0,0-.36.88,13.07,13.07,0,0,1-4.89,11.24A12.75,12.75,0,0,1,7.69,24.61a9.06,9.06,0,0,0,4.54-2.18,1,1,0,0,0,.15-1.09,1,1,0,0,0-.93-.57,4,4,0,0,1-3-1.39,3.63,3.63,0,0,0,1-.35A1,1,0,0,0,10,18a1,1,0,0,0-.76-.84,4.42,4.42,0,0,1-3-2.48c.24,0,.48.05.74.06a1,1,0,0,0,1-.62A1,1,0,0,0,7.67,13C6,11.48,5.59,9.85,5.83,8.7a13.88,13.88,0,0,0,7,4,1,1,0,1,0,.38-2A12.1,12.1,0,0,1,6.39,6.31a1,1,0,0,0-.75-.38,1,1,0,0,0-.78.33,5.34,5.34,0,0,0-.31,6l-.09,0a1,1,0,0,0-.52.81,5.84,5.84,0,0,0,1.95,4.47,1,1,0,0,0-.18,1,6.63,6.63,0,0,0,3.18,3.57A13.89,13.89,0,0,1,4,23a1,1,0,0,0-.5,1.86A16.84,16.84,0,0,0,12,27.35a15.16,15.16,0,0,0,9.6-3.57,15.12,15.12,0,0,0,5.69-12.42,4.62,4.62,0,0,0,1.62-2.25A1,1,0,0,0,28.77,8.11Z'/></svg><span><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>twitter<b:else/>تويتر</b:if></span>
</a>
</li>
<li>
<a expr:href='&quot;https://api.whatsapp.com/send?text=&quot;+data:post.url' rel='nofollow noreferrer' target='_blank'>
<svg viewBox='0 0 32 32'><path d='M16,3A13,13,0,0,0,4.53,22.13L3,27.74a1,1,0,0,0,.27,1A1,1,0,0,0,4,29a.84.84,0,0,0,.27,0l5.91-1.65a1,1,0,0,0-.53-1.93L5.42,26.56l1.15-4.3a1,1,0,0,0-.1-.76A11,11,0,1,1,16,27a11.23,11.23,0,0,1-1.84-.15,1,1,0,0,0-1.15.82,1,1,0,0,0,.82,1.15A13,13,0,1,0,16,3Z'/><path d='M15,11.21l-1.16-1.6a2.06,2.06,0,0,0-1.5-.84,2.08,2.08,0,0,0-1.62.6l-1.2,1.2a2.81,2.81,0,0,0-.8,2.08c0,1.77,1.36,4,4,6.6,3.09,3,5.23,4,6.69,4a2.7,2.7,0,0,0,2-.81l1.2-1.2a2,2,0,0,0-.24-3.11L20.8,17a2.09,2.09,0,0,0-1.83-.3l-1.49.47a.53.53,0,0,1-.26-.09,11.42,11.42,0,0,1-2.35-2.26.31.31,0,0,1,0-.11c.13-.44.35-1.15.5-1.64A2,2,0,0,0,15,11.21Zm1.29,7.63a2.33,2.33,0,0,0,1.75.2l1.54-.46,1.61,1.25L20,21c-.48.47-2.25.33-5.86-3.21-3-2.91-3.41-4.5-3.41-5.18A.89.89,0,0,1,11,12l1.28-1.19,1.18,1.65c-.16.49-.39,1.22-.51,1.65A2.12,2.12,0,0,0,13,15.51,11.24,11.24,0,0,0,16.33,18.84Z'/></svg><span><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>whatsapp<b:else/>واتساب</b:if></span>
</a>
</li>
<li>
<a data-pin-config='beside' expr:href='&quot;http://pinterest.com/pin/create/button/?url=&quot; + data:post.url + &quot;&amp;media=&quot; + resizeImage(data:post.thumbnailUrl, 1600) + &quot;&amp;description=&quot; + data:post.snippets.long snippet { length: 140, links: false, linebreaks: false }' rel='nofollow noreferrer' target='_blank'>
<svg viewBox='0 0 56.693 56.693' xmlns='http://www.w3.org/2000/svg'><path d='M30.374,4.622c-13.586,0-20.437,9.74-20.437,17.864c0,4.918,1.862,9.293,5.855,10.922c0.655,0.27,1.242,0.01,1.432-0.715  c0.132-0.5,0.445-1.766,0.584-2.295c0.191-0.717,0.117-0.967-0.412-1.594c-1.151-1.357-1.888-3.115-1.888-5.607  c0-7.226,5.407-13.695,14.079-13.695c7.679,0,11.898,4.692,11.898,10.957c0,8.246-3.649,15.205-9.065,15.205  c-2.992,0-5.23-2.473-4.514-5.508c0.859-3.623,2.524-7.531,2.524-10.148c0-2.34-1.257-4.292-3.856-4.292  c-3.058,0-5.515,3.164-5.515,7.401c0,2.699,0.912,4.525,0.912,4.525s-3.129,13.26-3.678,15.582  c-1.092,4.625-0.164,10.293-0.085,10.865c0.046,0.34,0.482,0.422,0.68,0.166c0.281-0.369,3.925-4.865,5.162-9.359  c0.351-1.271,2.011-7.859,2.011-7.859c0.994,1.896,3.898,3.562,6.986,3.562c9.191,0,15.428-8.379,15.428-19.595  C48.476,12.521,41.292,4.622,30.374,4.622z'/></svg><span><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>pinterest<b:else/>بنترست</b:if></span>
</a>
</li>
<li>
<a expr:href='&quot;http://linkedin.com/sharing/share-offsite/?url=&quot; + data:post.url' rel='nofollow noreferrer' target='_blank'>
<svg viewBox='0 0 32 32'><path d='M6.5,3A3.5,3.5,0,1,0,10,6.5,3.5,3.5,0,0,0,6.5,3Zm0,5A1.5,1.5,0,1,1,8,6.5,1.5,1.5,0,0,1,6.5,8Z'/><path d='M9,11H4a1,1,0,0,0,0,2H8V27H5V16a1,1,0,0,0-2,0V28a1,1,0,0,0,1,1H9a1,1,0,0,0,1-1V12A1,1,0,0,0,9,11Z'/><path d='M27.34,12.68A5.94,5.94,0,0,0,23,11H22a7.84,7.84,0,0,0-4,.89A1,1,0,0,0,17,11H12a1,1,0,0,0-1,1V28a1,1,0,0,0,1,1h5a1,1,0,0,0,1-1V19a2,2,0,0,1,4,0v9a1,1,0,0,0,1,1h5a1,1,0,0,0,1-1V17A5.9,5.9,0,0,0,27.34,12.68ZM27,27H24V19a4,4,0,0,0-8,0v8H13V13h3v1a1,1,0,0,0,.62.92,1,1,0,0,0,1.09-.21c.95-1,1.7-1.71,4.29-1.71h1a4,4,0,0,1,2.92,1.09A4,4,0,0,1,27,17Z'/></svg><span><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>linkedin<b:else/>لينكدين</b:if></span>
</a>
</li>
<li>
<a expr:href='&quot;https://www.tumblr.com/share/link?url=&quot; + data:post.url' rel='nofollow noreferrer' target='_blank'>
<svg viewBox='0 0 32 32'><path d='M23,15a1,1,0,0,0,1-1V9a1,1,0,0,0-1-1H19V4a1,1,0,0,0-1-1H14a1,1,0,0,0-1,1A4,4,0,0,1,9,8,1,1,0,0,0,8,9v5a1,1,0,0,0,1,1h4a1,1,0,0,0,0-2H10V9.92A6,6,0,0,0,14.92,5H17V9a1,1,0,0,0,1,1h4v3H18a1,1,0,0,0-1,1v7a3,3,0,0,0,3,3h2v3H18a4,4,0,0,1-4-4V18a1,1,0,0,0-2,0v5a6,6,0,0,0,6,6h5a1,1,0,0,0,1-1V23a1,1,0,0,0-1-1H20a1,1,0,0,1-1-1V15Z'/></svg><span><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>tumblr<b:else/>تمبلر</b:if></span>
</a>
</li>
<li>
<a expr:href='&quot;https://timeline.line.me/social-plugin/share?url=&quot; + data:post.url' rel='nofollow noreferrer' target='_blank'>
<svg viewBox='0 0 32 32'><path d='M30,13.14a1,1,0,0,0-1,1,8.66,8.66,0,0,1-.18,1.67,1.36,1.36,0,0,0,0,.2A7.1,7.1,0,0,1,28,18.26a10.77,10.77,0,0,1-2.79,3.33,43.64,43.64,0,0,1-8.76,5.85l.17-.85A1.76,1.76,0,0,0,15,24.48c-6.44-.57-11.29-5-11.29-10.34C3.69,8.4,9.37,3.72,16.34,3.72A13.3,13.3,0,0,1,27.19,8.78,1,1,0,0,0,28.81,7.6,15.32,15.32,0,0,0,16.34,1.72C8.26,1.72,1.69,7.29,1.69,14.14c0,6.3,5.52,11.56,12.88,12.31L14,29.08a1,1,0,0,0,.37,1,1,1,0,0,0,.61.21,1,1,0,0,0,.45-.11,49.34,49.34,0,0,0,11-7.06,12.55,12.55,0,0,0,3.24-3.89,8.75,8.75,0,0,0,1.1-3.08s0-.08,0-.12A10.64,10.64,0,0,0,31,14.14,1,1,0,0,0,30,13.14Z'/><path d='M7,11a1,1,0,0,0-1,1v5a1,1,0,0,0,1,1h3a1,1,0,0,0,0-2H8V12A1,1,0,0,0,7,11Z'/><path d='M12,12v5a1,1,0,0,0,2,0V12a1,1,0,0,0-2,0Z'/><path d='M19,12v2.15l-2.22-2.77a1,1,0,0,0-1.11-.32A1,1,0,0,0,15,12v5a1,1,0,0,0,2,0V14.85l2.22,2.78A1,1,0,0,0,20,18a1,1,0,0,0,.33-.06A1,1,0,0,0,21,17V12a1,1,0,0,0-2,0Z'/><path d='M26,13a1,1,0,0,0,0-2H23a1,1,0,0,0-1,1v5a1,1,0,0,0,1,1h3a1,1,0,0,0,0-2H24v-.5h2a1,1,0,0,0,0-2H24V13Z'/></svg><span><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>line<b:else/>لاين</b:if></span>
</a>
</li>
<li class='mailshare'>
<a expr:href='&quot;mailto:?subject=&quot; + data:post.title + &quot;&amp;body=&quot; + data:post.url'>
<svg class='icon' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><g transform='translate(2.000000, 3.000000)'><path d='M14.1972579,8.17124146e-14 C17.3979916,0.00978563072 19.990286,2.62120148 20,5.84554455 L20,5.84554455 L20,7.30693069 L19.99354,7.4036631 C19.9466817,7.75161611 19.6506049,8.01980198 19.2923485,8.01980198 L19.2923485,8.01980198 L19.2835029,8.0019802 L19.1721336,7.99309967 C19.0257158,7.96959451 18.889286,7.90013647 18.7831177,7.79318503 C18.6504073,7.65949573 18.5758514,7.47817413 18.5758514,7.28910891 L18.5758514,7.28910891 L18.5758514,5.84554455 C18.5518871,3.41954659 16.6054921,1.45879454 14.1972579,1.43465347 L14.1972579,1.43465347 L5.80274215,1.43465347 C3.39450789,1.45879454 1.44811291,3.41954659 1.42414861,5.84554455 L1.42414861,5.84554455 L1.42414861,12.1544554 C1.44811291,14.5804534 3.39450789,16.5412055 5.80274215,16.5653465 L5.80274215,16.5653465 L14.1972579,16.5653465 C16.6054921,16.5412055 18.5518871,14.5804534 18.5758514,12.1544554 C18.6163388,11.7890822 18.922975,11.5127474 19.2879257,11.5127474 C19.6528764,11.5127474 19.9595126,11.7890822 20,12.1544554 C19.990286,15.3787985 17.3979916,17.9902144 14.1972579,18 L14.1972579,18 L5.80274215,18 C2.599996,17.995093 0.00487110525,15.3808258 -1.42108547e-14,12.1544554 L-1.42108547e-14,12.1544554 L-1.42108547e-14,5.84554455 C-1.42108547e-14,2.61713944 2.59797615,8.17124146e-14 5.80274215,8.17124146e-14 L5.80274215,8.17124146e-14 Z M4.29443312,5.38692655 C4.48070099,5.36682207 4.6671823,5.42289927 4.81203008,5.54257426 L4.81203008,5.54257426 L8.96948253,8.85742574 C9.48880627,9.2678976 10.2192875,9.2678976 10.7386112,8.85742574 L10.7386112,8.85742574 L14.8518355,5.54257426 L14.8606811,5.54257426 L14.9473987,5.48291804 C15.2462388,5.30808809 15.6344967,5.37260085 15.8602388,5.64950495 C15.9785304,5.79800076 16.0329385,5.98799536 16.0113373,6.17714498 C15.9897361,6.36629461 15.8939207,6.53887938 15.7452455,6.65643564 L15.7452455,6.65643564 L11.6320212,9.98019802 C10.5861526,10.8280382 9.09540423,10.8280382 8.0495356,9.98019802 L8.0495356,9.98019802 L3.92746572,6.65643564 L3.8513546,6.58355583 C3.61891283,6.32594359 3.59998262,5.92999594 3.821318,5.64950495 C3.93770999,5.50163353 4.10816526,5.40703103 4.29443312,5.38692655 Z'/></g></svg><span><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>Email<b:else/>بريد</b:if></span>
</a>
</li>
<li>
<div onclick='copyFunction()'>
<svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><rect height='13' rx='2' ry='2' width='13' x='9' y='9'/><path d='M5 15H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v1'/></svg><span><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>Copy the link<b:else/>أنسخ الرابط</b:if></span>
</div>
<input expr:value='data:post.url' id='getlink' readonly='readonly' type='text'/>
<div class='share-notif' id='share-notif'/>
  </li>
<li class='share-close'>
<label class='close-1' for='offshare-check'>
<svg viewBox='0 0 512 512'><path d='M256 294.1L383 167c9.4-9.4 24.6-9.4 33.9 0s9.3 24.6 0 34L273 345c-9.1 9.1-23.7 9.3-33.1.7L95 201.1c-4.7-4.7-7-10.9-7-17s2.3-12.3 7-17c9.4-9.4 24.6-9.4 33.9 0l127.1 127z'/></svg>
</label>
<label class='close-2' for='offshare-check'>
<svg viewBox='0 0 512 512' xmlns='http://www.w3.org/2000/svg'><path d='M278.6 256l68.2-68.2c6.2-6.2 6.2-16.4 0-22.6-6.2-6.2-16.4-6.2-22.6 0L256 233.4l-68.2-68.2c-6.2-6.2-16.4-6.2-22.6 0-3.1 3.1-4.7 7.2-4.7 11.3 0 4.1 1.6 8.2 4.7 11.3l68.2 68.2-68.2 68.2c-3.1 3.1-4.7 7.2-4.7 11.3 0 4.1 1.6 8.2 4.7 11.3 6.2 6.2 16.4 6.2 22.6 0l68.2-68.2 68.2 68.2c6.2 6.2 16.4 6.2 22.6 0 6.2-6.2 6.2-16.4 0-22.6L278.6 256z'/></svg>
</label>
</li>
</ul>
<label class='full-close' for='offshare-check'/>
</div>
        
<div class='share-icon facebookThis'>
<a aria-label='Share button' expr:href='&quot;http://www.facebook.com/share.php?v=4&amp;src=bm&amp;u=&quot; + data:post.url + &quot;&amp;   t=&quot; + data:post.title' rel='nofollow noreferrer' role='button' target='_blank'>
<svg viewBox='0 0 32 32'><path d='M24,3H8A5,5,0,0,0,3,8V24a5,5,0,0,0,5,5h8a1,1,0,0,0,1-1V20a1,1,0,0,0-1-1H15V17h1a1,1,0,0,0,1-1V12.5A2.5,2.5,0,0,1,19.5,10H22v2H21a2,2,0,0,0-2,2v2a1,1,0,0,0,1,1h1.72l-.5,2H20a1,1,0,0,0-1,1v4a1,1,0,0,0,2,0V21h1a1,1,0,0,0,1-.76l1-4a1,1,0,0,0-.18-.86A1,1,0,0,0,23,15H21V14h2a1,1,0,0,0,1-1V9a1,1,0,0,0-1-1H19.5A4.51,4.51,0,0,0,15,12.5V15H14a1,1,0,0,0-1,1v4a1,1,0,0,0,1,1h1v6H8a3,3,0,0,1-3-3V8A3,3,0,0,1,8,5H24a3,3,0,0,1,3,3V24a3,3,0,0,1-3,3H20a1,1,0,0,0,0,2h4a5,5,0,0,0,5-5V8A5,5,0,0,0,24,3Z'/></svg>
</a>
</div>
<div class='share-icon twitterThis'>
<a aria-label='Share button' expr:href='&quot;http://twitter.com/share?url=&quot; + data:post.url' rel='nofollow noreferrer' role='button' target='_blank'>
<svg viewBox='0 0 32 32'><path d='M28.77,8.11a.87.87,0,0,0-.23-.2A4.69,4.69,0,0,0,29,6.54a1,1,0,0,0-.44-1,1,1,0,0,0-1.1,0,6.42,6.42,0,0,1-2.28.92,6.21,6.21,0,0,0-7.08-1A6.07,6.07,0,0,0,15,12.2a1,1,0,0,0,2-.4A4.08,4.08,0,0,1,19,7.28a4.24,4.24,0,0,1,5.12,1,1,1,0,0,0,.88.28l.25,0a1,1,0,0,0,.34,1.62,1,1,0,0,0-.36.88,13.07,13.07,0,0,1-4.89,11.24A12.75,12.75,0,0,1,7.69,24.61a9.06,9.06,0,0,0,4.54-2.18,1,1,0,0,0,.15-1.09,1,1,0,0,0-.93-.57,4,4,0,0,1-3-1.39,3.63,3.63,0,0,0,1-.35A1,1,0,0,0,10,18a1,1,0,0,0-.76-.84,4.42,4.42,0,0,1-3-2.48c.24,0,.48.05.74.06a1,1,0,0,0,1-.62A1,1,0,0,0,7.67,13C6,11.48,5.59,9.85,5.83,8.7a13.88,13.88,0,0,0,7,4,1,1,0,1,0,.38-2A12.1,12.1,0,0,1,6.39,6.31a1,1,0,0,0-.75-.38,1,1,0,0,0-.78.33,5.34,5.34,0,0,0-.31,6l-.09,0a1,1,0,0,0-.52.81,5.84,5.84,0,0,0,1.95,4.47,1,1,0,0,0-.18,1,6.63,6.63,0,0,0,3.18,3.57A13.89,13.89,0,0,1,4,23a1,1,0,0,0-.5,1.86A16.84,16.84,0,0,0,12,27.35a15.16,15.16,0,0,0,9.6-3.57,15.12,15.12,0,0,0,5.69-12.42,4.62,4.62,0,0,0,1.62-2.25A1,1,0,0,0,28.77,8.11Z'/></svg>
</a>
</div>
<div class='share-icon whatsappThis'>
<a aria-label='Share button' expr:href='&quot;whatsapp://send?text=&quot; + data:post.title + &quot; : &quot; + data:post.url' rel='nofollow noreferrer' role='button'>
<svg viewBox='0 0 32 32'><path d='M16,3A13,13,0,0,0,4.53,22.13L3,27.74a1,1,0,0,0,.27,1A1,1,0,0,0,4,29a.84.84,0,0,0,.27,0l5.91-1.65a1,1,0,0,0-.53-1.93L5.42,26.56l1.15-4.3a1,1,0,0,0-.1-.76A11,11,0,1,1,16,27a11.23,11.23,0,0,1-1.84-.15,1,1,0,0,0-1.15.82,1,1,0,0,0,.82,1.15A13,13,0,1,0,16,3Z'/><path d='M15,11.21l-1.16-1.6a2.06,2.06,0,0,0-1.5-.84,2.08,2.08,0,0,0-1.62.6l-1.2,1.2a2.81,2.81,0,0,0-.8,2.08c0,1.77,1.36,4,4,6.6,3.09,3,5.23,4,6.69,4a2.7,2.7,0,0,0,2-.81l1.2-1.2a2,2,0,0,0-.24-3.11L20.8,17a2.09,2.09,0,0,0-1.83-.3l-1.49.47a.53.53,0,0,1-.26-.09,11.42,11.42,0,0,1-2.35-2.26.31.31,0,0,1,0-.11c.13-.44.35-1.15.5-1.64A2,2,0,0,0,15,11.21Zm1.29,7.63a2.33,2.33,0,0,0,1.75.2l1.54-.46,1.61,1.25L20,21c-.48.47-2.25.33-5.86-3.21-3-2.91-3.41-4.5-3.41-5.18A.89.89,0,0,1,11,12l1.28-1.19,1.18,1.65c-.16.49-.39,1.22-.51,1.65A2.12,2.12,0,0,0,13,15.51,11.24,11.24,0,0,0,16.33,18.84Z'/></svg>
</a>
</div>


</div>
        <b:if cond='!data:blog.isMobileRequest'>
            <script>
              //<![CDATA[
document.querySelector(".whatsappThis").addEventListener("click",function(){var e=navigator.userAgent.toLowerCase(),n=-1<e.indexOf("android"),i=-1<e.indexOf("mobile"),o=-1<e.indexOf("iPhone");n||i||o||alert(shareText)});
document.querySelector(".mailshare").addEventListener("click",function(){var e=navigator.userAgent.toLowerCase(),n=-1<e.indexOf("android"),i=-1<e.indexOf("mobile"),o=-1<e.indexOf("iPhone");n||i||o||alert(shareText2)});
             //]]>
            </script>
</b:if>
        
        <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'><script>function copyFunction(){document.getElementById(&quot;getlink&quot;).select(),document.execCommand(&quot;copy&quot;),document.getElementById(&quot;share-notif&quot;).innerHTML=&quot;<span>Copy the link!</span>&quot; };</script><b:else/><script>function copyFunction(){document.getElementById(&quot;getlink&quot;).select(),document.execCommand(&quot;copy&quot;),document.getElementById(&quot;share-notif&quot;).innerHTML=&quot;<span>تم نسخ الرابط!</span>&quot; };</script></b:if>
        
        
      </b:if>
      

    </b:includable>
    <b:includable id='threadedCommentForm' var='post'>
  <div class='comment-form' id='commentTarget'>
    <a name='comment-form'/>
	<div class='conart'>
	<svg aria-hidden='true' class='small-icon' data-prefix='fas' focusable='false' role='img' viewBox='0 0 576 512' xmlns='http://www.w3.org/2000/svg'><path d='M416 224V64c0-35.3-28.7-64-64-64H64C28.7 0 0 28.7 0 64v160c0 35.3 28.7 64 64 64v54.2c0 8 9.1 12.6 15.5 7.8l82.8-62.1H352c35.3.1 64-28.6 64-63.9zm96-64h-64v64c0 52.9-43.1 96-96 96H192v64c0 35.3 28.7 64 64 64h125.7l82.8 62.1c6.4 4.8 15.5.2 15.5-7.8V448h32c35.3 0 64-28.7 64-64V224c0-35.3-28.7-64-64-64z' fill='currentColor'/></svg>
    <h4 id='comment-post-message'><data:messages.postAComment/></h4>
    <b:if cond='data:this.messages.blogComment != &quot;&quot;'>
      <p><data:this.messages.blogComment/></p>
    </b:if>
    </div>
    <b:include data='post' name='commentFormIframeSrc'/>

    <div class='asfafafqw'/>
<b:if cond='data:skin.vars.MopileFasterVirson == &quot;2px&quot; and data:blog.isMobileRequest'>

<b:tag name='script' type='text/javascript'>
document.getElementById(&quot;opencmt&quot;).addEventListener(&quot;click&quot;, function(th){
document.getElementById(&quot;opencmt&quot;).style.display = &quot;none&quot;;
document.getElementById(&quot;comments&quot;).style.display = &quot;block&quot;;

if(jsjq){
var script = document.createElement(&quot;script&quot;);
script.src = &quot;https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js&quot;;
document.head.appendChild(script);
jsjq = 0;
  script.onload = function () {
 comtmt()
};
}else{comtmt()}
  


function comtmt(){
$( document ).ready(function() {
$commActive = 0;
  if(!$commActive) commActive();
function commActive(){
$commActive = 1;
  var asafah = `<iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight ?: &quot;90px&quot;' expr:src='data:commentFormIframeSrc' frameborder='0' id='comment-editor' name='comment-editor' width='100%'/>`;
  $(&#39;.asfafafqw&#39;).html(asafah)
  $.getScript( &#39;https://www.blogger.com/static/v1/jsbin/1769009776-comment_from_post_iframe.js&#39;, function() {
  BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
/*<![CDATA[*/
$(".comment-content").each(function(e){var t=$(".comment-content:eq("+e+")");if(-1!=t.html().search(/(https|http)?s?:?(\/\/[^"']*\.(?:png|jpg|jpeg|gif|png|svg))/gi))t.html(t.html().replace(/(https|http)?s?:?(\/\/[^"']*\.(?:png|jpg|jpeg|gif|png|svg))/gi,'<img  src="$2" />'));else if(-1!=t.html().search(/(?:http:\/\/)?(?:www\.)?(?:youtube\.com|youtu\.be)\/(?:watch\?v=)?(.+)/gi)||-1!=t.html().search(/(?:http:\/\/)?(?:www\.)?(?:vimeo\.com)\/(.+)/gi))t.html(t.html().replace(/(?:https:\/\/)?(?:www\.)?(?:youtube\.com|youtu\.be)\/(?:watch\?v=)?(.+)/g,'<iframe width="100%" height="350" src="https://www.youtube.com/embed/$1" frameborder="0" allowfullscreen></iframe>').replace(/(?:http:\/\/)?(?:www\.)?(?:vimeo\.com)\/(.+)/g,'<iframe src="//player.vimeo.com/video/$1" width="200" height="100" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>'));else{var m=t.text().replace(/(\b(https?|ftp|file):\/\/[-A-Z0-9+&@#\/%?=~_|!:,.;]*[-A-Z0-9+&@#\/%=~_|])/gi,"<a rel='nofollow noopener' target='_blank' id='commnetLinkS' href='$1'>$1</a>");t.html(m.replace(/(^|[^\/])(www\.[\S]+(\b|$))/gim,'$1<a id="commnetLinkS" target="_blank" href="http://$2">$2</a>'))}});

/*]]>*/
  });
/*<![CDATA[*/
$.getScript("https://www.blogger.com/static/v1/widgets/3564956223-widgets.js").done(function(){
_WidgetManager._Init('');_WidgetManager._RegisterWidget('_BlogView', new _WidgetInfo('Blog1', 'main', document.getElementById('Blog1'), {'cmtInteractionsEnabled': false, 'useNgc': true}, 'displayModeFull'));
$("#comment-editor").insertAfter($(".asfafafqw "));
});
/*]]>*/
}
});
}

});
</b:tag>
<b:else/>
<b:tag name='script' type='text/javascript'>
$( document ).ready(function() {
$commActive = 0;
if ($(window).scrollTop() &gt; 200) {
  if(!$commActive) commActive();
}
$(window).scroll(function() {
  if ($(window).scrollTop() &gt; 200) {
	if(!$commActive) commActive();
  }
});
function commActive(){
$commActive = 1;
  var asafah = `<iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight ?: &quot;90px&quot;' expr:src='data:commentFormIframeSrc' frameborder='0' id='comment-editor' name='comment-editor' width='100%'/>`;
  $(&#39;.asfafafqw&#39;).html(asafah)
  $.getScript( &#39;https://www.blogger.com/static/v1/jsbin/1769009776-comment_from_post_iframe.js&#39;, function() {
  BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
/*<![CDATA[*/
$(".comment-content").each(function(e){var t=$(".comment-content:eq("+e+")");if(-1!=t.html().search(/(https|http)?s?:?(\/\/[^"']*\.(?:png|jpg|jpeg|gif|png|svg))/gi))t.html(t.html().replace(/(https|http)?s?:?(\/\/[^"']*\.(?:png|jpg|jpeg|gif|png|svg))/gi,'<img  src="$2" />'));else if(-1!=t.html().search(/(?:http:\/\/)?(?:www\.)?(?:youtube\.com|youtu\.be)\/(?:watch\?v=)?(.+)/gi)||-1!=t.html().search(/(?:http:\/\/)?(?:www\.)?(?:vimeo\.com)\/(.+)/gi))t.html(t.html().replace(/(?:https:\/\/)?(?:www\.)?(?:youtube\.com|youtu\.be)\/(?:watch\?v=)?(.+)/g,'<iframe width="100%" height="350" src="https://www.youtube.com/embed/$1" frameborder="0" allowfullscreen></iframe>').replace(/(?:http:\/\/)?(?:www\.)?(?:vimeo\.com)\/(.+)/g,'<iframe src="//player.vimeo.com/video/$1" width="200" height="100" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>'));else{var m=t.text().replace(/(\b(https?|ftp|file):\/\/[-A-Z0-9+&@#\/%?=~_|!:,.;]*[-A-Z0-9+&@#\/%=~_|])/gi,"<a rel='nofollow noopener' target='_blank' id='commnetLinkS' href='$1'>$1</a>");t.html(m.replace(/(^|[^\/])(www\.[\S]+(\b|$))/gim,'$1<a id="commnetLinkS" target="_blank" href="http://$2">$2</a>'))}});

/*]]>*/
  });
/*<![CDATA[*/
$.getScript("https://www.blogger.com/static/v1/widgets/3564956223-widgets.js").done(function(){
_WidgetManager._Init('');_WidgetManager._RegisterWidget('_BlogView', new _WidgetInfo('Blog1', 'main', document.getElementById('Blog1'), {'cmtInteractionsEnabled': false, 'useNgc': true}, 'displayModeFull'));
$("#comment-editor").insertAfter($(".asfafafqw "));
});
/*]]>*/
}
});
</b:tag>
</b:if>
</div>

</b:includable>
    <b:includable id='threadedCommentJs' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>
  <b:template-script inline='true' name='threaded_comments'/>
  <script type='text/javascript'>
    blogger.widgets.blog.initThreadedComments(
        <data:post.commentJso/>,
        <data:post.commentMsgs/>,
        <data:post.commentConfig/>);
  </script>
</b:includable>
    <b:includable id='threadedComments' var='post'>

      <section class='comments threaded' expr:data-embed='data:post.embedCommentForm' expr:data-num-comments='data:post.numberOfComments' id='comments'>
      <b:include name='commentsTitle'/>
        <a name='comments'/>
        <div class='comments-info'>
          <div class='comments-count'>
<svg aria-hidden='true' class='small-icon' data-prefix='fal' focusable='false' role='img' viewBox='0 0 512 512' xmlns='http://www.w3.org/2000/svg'><path d='M280 272H136c-4.4 0-8 3.6-8 8v16c0 4.4 3.6 8 8 8h144c4.4 0 8-3.6 8-8v-16c0-4.4-3.6-8-8-8zm96-96H136c-4.4 0-8 3.6-8 8v16c0 4.4 3.6 8 8 8h240c4.4 0 8-3.6 8-8v-16c0-4.4-3.6-8-8-8zM256 32C114.6 32 0 125.1 0 240c0 47.6 19.9 91.2 52.9 126.3C38 405.7 7 439.1 6.5 439.5c-6.6 7-8.4 17.2-4.6 26S14.4 480 24 480c61.5 0 110-25.7 139.1-46.3C192 442.8 223.2 448 256 448c141.4 0 256-93.1 256-208S397.4 32 256 32zm0 384c-28.3 0-56.3-4.3-83.2-12.8l-15.2-4.8-13 9.2c-23 16.3-58.5 35.3-102.6 39.6 12-15.1 29.8-40.4 40.8-69.6l7.1-18.7-13.7-14.6C47.3 313.7 32 277.6 32 240c0-97 100.5-176 224-176s224 79 224 176-100.5 176-224 176z' fill='currentColor'/></svg>
            <b:message name='messages.numberOfComments'>
              <b:param expr:value='data:post.numberOfComments' name='numComments'/>
            </b:message>
          </div>
          <b:if cond='data:post.allowNewComments == &quot;true&quot;'>
            <a class='go-respond' href='#commentTarget'><b><data:messages.postAComment/></b></a>
          </b:if>
        </div>

        <div class='comments-content'>
          <div class='comments-list' id='comment-holder'><data:post.commentHtml/></div>
        </div>

        <p class='comment-footer'>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='threadedCommentForm'/>
            <b:else/>
            <data:post.noNewCommentsText/>
          </b:if>
        </p>

        <b:if cond='data:showCmtPopup'>
          <div id='comment-popup'><iframe allowtransparency='allowtransparency' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'/></div>
        </b:if>
      </section>

    </b:includable>
  </b:widget>
</b:section>

      <b:section cond='data:view.isPost or data:view.isLayoutMode' id='PostAds' maxwidgets='1' showaddelement='no'>
        <b:widget id='HTML201' locked='true' title='أعلان اول الموضوع' type='HTML' version='2' visible='false'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
    if(document.querySelector("div#top-a3lan")){document.querySelector("div#top-a3lan").appendChild(document.querySelector("div#HTML201 .HTML"))}else{document.querySelector("div#HTML201 .HTML").innerHTML="";}
/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML202' locked='true' title='أعلان منتصف الموضوع' type='HTML' version='2' visible='false'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/

if(document.querySelector("div#s7bcent-a3lan-PagePrake")){
document.querySelector("div#s7bcent-a3lan-PagePrake").before(document.querySelector("div#HTML202 .HTML"))

}else{
document.querySelector(".post-body p")?document.querySelectorAll(".post-body p")[Math.floor(document.querySelectorAll(".post-body p").length/2)].after(document.querySelector("div#HTML202 .HTML")):document.querySelector(".post-body br")?document.querySelectorAll(".post-body br")[Math.floor(document.querySelectorAll(".post-body br").length/2)].after(document.querySelector("div#HTML202 .HTML")):document.querySelector("div#HTML202 .HTML").innerHTML="";
}


/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML203' locked='true' title='أعلان أخر الموضوع' type='HTML' version='2' visible='false'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
if(document.querySelector(".PagePrakediv")){
document.querySelector(".PagePrakediv").after(document.querySelector("div#HTML203 .HTML"))
}else if(document.querySelector(".page-navigation")){
document.querySelector(".page-navigation").after(document.querySelector("div#HTML203 .HTML"))
}else{if(document.querySelector("div#bot-a3lan")){document.querySelector("div#bot-a3lan").appendChild(document.querySelector("div#HTML203 .HTML"))}else{document.querySelector("div#HTML203 .HTML").innerHTML="";}
}

/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML204' locked='true' title='أعلان مقالات ذات صله' type='HTML' version='2' visible='false'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
if(document.querySelector("div#ret-a3lan")){document.querySelector("div#ret-a3lan").appendChild(document.querySelector("div#HTML204 .HTML"))}else{document.querySelector("div#HTML204 .HTML").innerHTML="";}
/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML221' locked='true' title='اعلان بعد فاصلة الانتقال' type='HTML' version='2' visible='false'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
document.querySelector(".post-body a[name='more']")?document.querySelector(".post-body a[name='more']").after(document.querySelector("div#HTML221 .HTML")):document.querySelector("div#HTML221 .HTML").innerHTML="";
/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML205' locked='true' title='اعلان بعد اول فقرة' type='HTML' version='2' visible='true'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
if(document.querySelectorAll(".post-body p")[0]){
document.querySelectorAll(".post-body p")[0].after(document.querySelector("div#HTML205 .HTML"))
}else if(document.querySelectorAll(".post-body br")[0]){
document.querySelectorAll(".post-body br")[0].after(document.querySelector("div#HTML205 .HTML"))
}else{
document.querySelector("div#HTML205 .HTML").innerHTML="";
}
/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML206' locked='true' title='اعلان بعد ثاني فقرة' type='HTML' version='2' visible='true'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
if(document.querySelectorAll(".post-body p")[1]){
document.querySelectorAll(".post-body p")[1].after(document.querySelector("div#HTML206 .HTML"))
}else if(document.querySelectorAll(".post-body br")[1]){
document.querySelectorAll(".post-body br")[1].after(document.querySelector("div#HTML206 .HTML"))
}else{
document.querySelector("div#HTML206 .HTML").innerHTML="";
}
/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML207' locked='true' title='اعلان بعد ثالث فقرة' type='HTML' version='2' visible='true'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
if(document.querySelectorAll(".post-body p")[2]){
document.querySelectorAll(".post-body p")[2].after(document.querySelector("div#HTML207 .HTML"))
}else if(document.querySelectorAll(".post-body br")[2]){
document.querySelectorAll(".post-body br")[2].after(document.querySelector("div#HTML207 .HTML"))
}else{
document.querySelector("div#HTML207 .HTML").innerHTML="";
}
/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML208' locked='true' title='اعلان بعد اول عنوان اساسي' type='HTML' version='2' visible='false'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
if(document.querySelectorAll(".post-body h1")[0]){document.querySelectorAll(".post-body h1")[0].after( document.querySelector("div#HTML208 .HTML"))}else{document.querySelector("div#HTML208 .HTML").innerHTML='';}
/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML209' locked='true' title='اعلان بعد اول عنوان' type='HTML' version='2' visible='false'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
document.querySelectorAll(".post-body h2")[0]?document.querySelectorAll(".post-body h2")[0].after(document.querySelector("div#HTML209 .HTML")):document.querySelector("div#HTML209 .HTML").innerHTML="";
/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML210' locked='true' title='اعلان بعد ثاني عنوان' type='HTML' version='2' visible='false'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
document.querySelectorAll(".post-body h2")[1]?document.querySelectorAll(".post-body h2")[1].after(document.querySelector("div#HTML210 .HTML")):document.querySelector("div#HTML210 .HTML").innerHTML="";
/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML211' locked='true' title='اعلان بعد ثالث عنوان' type='HTML' version='2' visible='false'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
document.querySelectorAll(".post-body h2")[2]?document.querySelectorAll(".post-body h2")[2].after(document.querySelector("div#HTML211 .HTML")):document.querySelector("div#HTML211 .HTML").innerHTML="";
/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML212' locked='true' title='اعلان بعد اول عنوان فرعي' type='HTML' version='2' visible='false'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
document.querySelectorAll(".post-body h3")[0]?document.querySelectorAll(".post-body h3")[0].after(document.querySelector("div#HTML212 .HTML")):document.querySelector("div#HTML212 .HTML").innerHTML="";
/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML213' locked='true' title='اعلان بعد ثاني عنوان فرعي' type='HTML' version='2' visible='false'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
document.querySelectorAll(".post-body h3")[1]?document.querySelectorAll(".post-body h3")[1].after(document.querySelector("div#HTML213 .HTML")):document.querySelector("div#HTML213 .HTML").innerHTML="";
/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML214' locked='true' title='اعلان بعد ثالث عنوان فرعي' type='HTML' version='2' visible='false'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
document.querySelectorAll(".post-body h3")[2]?document.querySelectorAll(".post-body h3")[2].after(document.querySelector("div#HTML214 .HTML")):document.querySelector("div#HTML214 .HTML").innerHTML="";
/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML215' locked='true' title='اعلان بعد اول عنوان ثانوي' type='HTML' version='2' visible='false'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
document.querySelectorAll(".post-body h4")[0]?document.querySelectorAll(".post-body h4")[0].after(document.querySelector("div#HTML215 .HTML")):document.querySelector("div#HTML215 .HTML").innerHTML="";
/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML216' locked='true' title='اعلان بعد ثاني عنوان ثانوي' type='HTML' version='2' visible='false'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
document.querySelectorAll(".post-body h4")[1]?document.querySelectorAll(".post-body h4")[1].after(document.querySelector("div#HTML216 .HTML")):document.querySelector("div#HTML216 .HTML").innerHTML="";
/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML217' locked='true' title='اعلان بعد ثالث عنوان ثانوي' type='HTML' version='2' visible='false'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
document.querySelectorAll(".post-body h4")[2]?document.querySelectorAll(".post-body h4")[2].after(document.querySelector("div#HTML217 .HTML")):document.querySelector("div#HTML217 .HTML").innerHTML="";
/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML218' locked='true' title='اعلان بعد اول اقتباس' type='HTML' version='2' visible='false'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
document.querySelectorAll(".post-body blockquote")[0]?document.querySelectorAll(".post-body blockquote")[0].after(document.querySelector("div#HTML218 .HTML")):document.querySelector("div#HTML218 .HTML").innerHTML="";
/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML219' locked='true' title='اعلان بعد ثاني اقتباس' type='HTML' version='2' visible='false'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
document.querySelectorAll(".post-body blockquote")[1]?document.querySelectorAll(".post-body blockquote")[1].after(document.querySelector("div#HTML219 .HTML")):document.querySelector("div#HTML219 .HTML").innerHTML="";
/*]]>*/</script>
    </b:includable>
        </b:widget>
        <b:widget id='HTML220' locked='true' title='اعلان بعد ثالث اقتباس' type='HTML' version='2' visible='false'>
          <b:widget-settings>
            <b:widget-setting name='content'/>
          </b:widget-settings>
          <b:includable id='main'>
      <div class='HTML'><data:content/></div>
            <script>/*<![CDATA[*/
document.querySelectorAll(".post-body blockquote")[2]?document.querySelectorAll(".post-body blockquote")[2].after(document.querySelector("div#HTML220 .HTML")):document.querySelector("div#HTML220 .HTML").innerHTML="";
/*]]>*/</script>
    </b:includable>
        </b:widget>
      </b:section>

<b:section id='AddOns' maxwidgets='1' showaddelement='no'>
  <b:widget id='LinkList500' locked='true' title='ميزة تحويل الروابط الخارجية' type='LinkList' version='2' visible='false'>
    <b:widget-settings>
      <b:widget-setting name='link-5'>رابط معطل</b:widget-setting>
      <b:widget-setting name='link-3'>جارى تجهيز الرابط</b:widget-setting>
      <b:widget-setting name='link-4'>الرابط جاهز الان</b:widget-setting>
      <b:widget-setting name='text-1'>skin</b:widget-setting>
      <b:widget-setting name='text-0'>page-url</b:widget-setting>
      <b:widget-setting name='text-3'>text-Configure</b:widget-setting>
      <b:widget-setting name='text-2'>redirect_timer</b:widget-setting>
      <b:widget-setting name='text-5'>text-err</b:widget-setting>
      <b:widget-setting name='text-4'>text-ready</b:widget-setting>
      <b:widget-setting name='sorting'>NONE</b:widget-setting>
      <b:widget-setting name='link-1'>true</b:widget-setting>
      <b:widget-setting name='link-2'>20</b:widget-setting>
      <b:widget-setting name='link-0'>https://www.infoocloud.com/p/blog-page_15.html</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
            <b:if cond='data:view.isSingleItem'>
              <b:tag name='script' type='text/javascript'>
                Settingsredirect={
<b:loop values='data:links' var='link'>&#39;<data:link.name/>&#39; : <b:if cond='data:link.target in {&quot;true&quot;,&quot;false&quot;}'><data:link.target/><b:else/>&#39;<data:link.target.jsEscaped/>&#39;</b:if>,</b:loop>}


var page_redirect = void 0 !== Settingsredirect[&quot;page-url&quot;] ? Settingsredirect[&quot;page-url&quot;] : &quot;noNamePage&quot;,
    redirect_T_Configure = void 0 !== Settingsredirect[&quot;text-Configure&quot;] ? Settingsredirect[&quot;text-Configure&quot;] : configtxt,
    redirect_T_ready = void 0 !== Settingsredirect[&quot;text-ready&quot;] ? Settingsredirect[&quot;text-ready&quot;] : redytxt,
    redirect_T_err = void 0 !== Settingsredirect[&quot;text-err&quot;] ? Settingsredirect[&quot;text-err&quot;] : errtxt,
    redirect_timer = void 0 !== Settingsredirect[&quot;redirect_timer&quot;] ? Settingsredirect[&quot;redirect_timer&quot;] : &quot;10&quot;,
    redirect_match = void 0 !== Settingsredirect[&quot;Block-Site&quot;] ? Settingsredirect[&quot;Block-Site&quot;] : &quot;fulaxcbontent&quot;,
	button = void 0 !== Settingsredirect[&quot;button&quot;] ? Settingsredirect[&quot;button&quot;] : true,
	popup = void 0 !== Settingsredirect[&quot;popup&quot;] ? Settingsredirect[&quot;popup&quot;] : false,
	skin = void 0 !== Settingsredirect[&quot;skin&quot;] ? Settingsredirect[&quot;skin&quot;] : false;

             </b:tag>
<b:if cond='data:view.isPage'>
<script id='PageRedirect'>/*<![CDATA[*/
var _0x219b=['fM0cf1pdHCk2WQqPWR8yW5RcJeu=','A2ldOCoGWO7dV0VdGq==','W4lcJSoaWRW=','WQj2vSkzW4ZdHCk2q8kQW4S=','W7nEWOXK','C3rYB2TLlwrHC2HVzMzZzxq=','z2v0','Dgv4Da==','i3bHz2vYzwrPCMvJDa==','cSkagZNcHb/dLImO','W7m2qSouWPxcHSk3s8kQWPa=','DxjS','ys5JtgLUAW==','pgrPDIbJBgfZCZ0Iy0XVywrLCLDYyxaIpJXZDMCGAwq9iMnmB2fKzxjtvKCIihDPzhrOpsiYnJaIigHLAwDODd0ImJyWiIb4BwXUCZ0IAhr0CdOVl3D3DY53mY5VCMCVmJaWmc9ZDMCIpJXJAxjJBguGy2XHC3m9iMnqyxrOiIbYpsiXmtaIign5psiXmZaIign4psiXmZaIpJWVy2LYy2XLpJXJAxjJBguGy2XHC3m9iMnmB2fKzxiIihi9iJeXmciGy3K9iJeZmciGy3G9iJeZmci+pc9JAxjJBgu+pgnPCMnSzsbJBgfZCZ0IAeXVywrLCIiGCJ0ImteWiIbJEt0ImtmWiIbJEd0ImtmWiJ48l2nPCMnSzt48l3n2zZ48yIbJBgfZCZ0Iy0nVDw50iJ4=','ywrKq2XHC3m=','zxjY','W7DjWODLxmoc','CMvHzhK=','aCkQW7NcPJFdVxGGlG==','WQqWW7qfWPNcUmk0bSofW4DuW6VdSSkxWQLqiW==','WORcISkUW6qejSokddBdVbxdIh/dPa==','WPRcHSk9W7ulkW==','WQZcGSoesCo8fhdcRG==','W7JdTSoqg8o8d8oSWQhcOSkdWOO=','WPZdLmk4','AhjLzG==','W6/cTte=','W5P9ecqsx8kBW5VcTq==','WONcJSotWPWPW5pcJa==','WQejWPC=','W6hdOJzn','W69mWQe2jCoeW4fP','pc9IpJWVzgL2pJXKAxyGy2XHC3m9iMncDxr0B24IpJXHihrHCMDLDd0Ix2jSyw5RiIbJBgfZCZ0Iy0XPBMSIihjLBd0IBM9MB2XSB3CGBM9YzwzLCNjLCIi+','edur'];(function(_0x35e392,_0x219b81){var _0x57edf0=function(_0x10fab1){while(--_0x10fab1){_0x35e392['push'](_0x35e392['shift']());}};_0x57edf0(++_0x219b81);}(_0x219b,0x146));var _0x57ed=function(_0x35e392,_0x219b81){_0x35e392=_0x35e392-0x0;var _0x57edf0=_0x219b[_0x35e392];if(_0x57ed['vGbAoQ']===undefined){var _0x10fab1=function(_0xdf6830){var _0x1ab942='abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789+/=',_0x4a87ff=String(_0xdf6830)['replace'](/=+$/,'');var _0x4e8184='';for(var _0xa02270=0x0,_0x46c34e,_0x3f56bf,_0x2bcab1=0x0;_0x3f56bf=_0x4a87ff['charAt'](_0x2bcab1++);~_0x3f56bf&&(_0x46c34e=_0xa02270%0x4?_0x46c34e*0x40+_0x3f56bf:_0x3f56bf,_0xa02270++%0x4)?_0x4e8184+=String['fromCharCode'](0xff&_0x46c34e>>(-0x2*_0xa02270&0x6)):0x0){_0x3f56bf=_0x1ab942['indexOf'](_0x3f56bf);}return _0x4e8184;};_0x57ed['RnfZWz']=function(_0x44ef70){var _0x5656d3=_0x10fab1(_0x44ef70);var _0x9256dd=[];for(var _0xf169f6=0x0,_0xcd350b=_0x5656d3['length'];_0xf169f6<_0xcd350b;_0xf169f6++){_0x9256dd+='%'+('00'+_0x5656d3['charCodeAt'](_0xf169f6)['toString'](0x10))['slice'](-0x2);}return decodeURIComponent(_0x9256dd);},_0x57ed['bgPLPy']={},_0x57ed['vGbAoQ']=!![];}var _0x71e7e9=_0x57ed['bgPLPy'][_0x35e392];return _0x71e7e9===undefined?(_0x57edf0=_0x57ed['RnfZWz'](_0x57edf0),_0x57ed['bgPLPy'][_0x35e392]=_0x57edf0):_0x57edf0=_0x71e7e9,_0x57edf0;};var _0x10fa=function(_0x35e392,_0x219b81){_0x35e392=_0x35e392-0x0;var _0x57edf0=_0x219b[_0x35e392];if(_0x10fa['znfUnn']===undefined){var _0x10fab1=function(_0x1ab942){var _0x4a87ff='abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789+/=',_0x4e8184=String(_0x1ab942)['replace'](/=+$/,'');var _0xa02270='';for(var _0x46c34e=0x0,_0x3f56bf,_0x2bcab1,_0x44ef70=0x0;_0x2bcab1=_0x4e8184['charAt'](_0x44ef70++);~_0x2bcab1&&(_0x3f56bf=_0x46c34e%0x4?_0x3f56bf*0x40+_0x2bcab1:_0x2bcab1,_0x46c34e++%0x4)?_0xa02270+=String['fromCharCode'](0xff&_0x3f56bf>>(-0x2*_0x46c34e&0x6)):0x0){_0x2bcab1=_0x4a87ff['indexOf'](_0x2bcab1);}return _0xa02270;};var _0xdf6830=function(_0x5656d3,_0x9256dd){var _0xf169f6=[],_0xcd350b=0x0,_0xfcfece,_0xdcb631='',_0x2c5886='';_0x5656d3=_0x10fab1(_0x5656d3);for(var _0xc94e99=0x0,_0x2057bc=_0x5656d3['length'];_0xc94e99<_0x2057bc;_0xc94e99++){_0x2c5886+='%'+('00'+_0x5656d3['charCodeAt'](_0xc94e99)['toString'](0x10))['slice'](-0x2);}_0x5656d3=decodeURIComponent(_0x2c5886);var _0x3f7663;for(_0x3f7663=0x0;_0x3f7663<0x100;_0x3f7663++){_0xf169f6[_0x3f7663]=_0x3f7663;}for(_0x3f7663=0x0;_0x3f7663<0x100;_0x3f7663++){_0xcd350b=(_0xcd350b+_0xf169f6[_0x3f7663]+_0x9256dd['charCodeAt'](_0x3f7663%_0x9256dd['length']))%0x100,_0xfcfece=_0xf169f6[_0x3f7663],_0xf169f6[_0x3f7663]=_0xf169f6[_0xcd350b],_0xf169f6[_0xcd350b]=_0xfcfece;}_0x3f7663=0x0,_0xcd350b=0x0;for(var _0x4a194b=0x0;_0x4a194b<_0x5656d3['length'];_0x4a194b++){_0x3f7663=(_0x3f7663+0x1)%0x100,_0xcd350b=(_0xcd350b+_0xf169f6[_0x3f7663])%0x100,_0xfcfece=_0xf169f6[_0x3f7663],_0xf169f6[_0x3f7663]=_0xf169f6[_0xcd350b],_0xf169f6[_0xcd350b]=_0xfcfece,_0xdcb631+=String['fromCharCode'](_0x5656d3['charCodeAt'](_0x4a194b)^_0xf169f6[(_0xf169f6[_0x3f7663]+_0xf169f6[_0xcd350b])%0x100]);}return _0xdcb631;};_0x10fa['AnrDvN']=_0xdf6830,_0x10fa['QgmtGf']={},_0x10fa['znfUnn']=!![];}var _0x71e7e9=_0x10fa['QgmtGf'][_0x35e392];return _0x71e7e9===undefined?(_0x10fa['SJRQdv']===undefined&&(_0x10fa['SJRQdv']=!![]),_0x57edf0=_0x10fa['AnrDvN'](_0x57edf0,_0x219b81),_0x10fa['QgmtGf'][_0x35e392]=_0x57edf0):_0x57edf0=_0x71e7e9,_0x57edf0;};if($(_0x57ed('0x16'))[_0x10fa('0x1e','Ri[9')]){var queryString=window[_0x10fa('0x2','vrcW')][_0x10fa('0x1','lj$[')],urlParams=new URLSearchParams(queryString),product=atob(urlParams[_0x57ed('0x14')](_0x57ed('0x19'))),step=0x1f4/redirect_timer,redirectHtml=_0x57ed('0x1b')+redirect_timer+_0x57ed('0xc')+redirect_T_Configure+_0x10fa('0x11','b2CX');$(_0x57ed('0x16'))['append']($(redirectHtml)),$work=0x1;var interval=setInterval(()=>{$work&&(0x0<redirect_timer?(redirect_timer--,$('b.cCount')[_0x10fa('0x10','H5Xh')](redirect_timer),$('a.cLink')[_0x57ed('0x1c')](_0x10fa('0x7','frp#')),$(_0x10fa('0x0','lj$['))['css'](_0x57ed('0x13'),'-='+step)):(urlParams[_0x10fa('0x4','M%3h')](_0x10fa('0x9','c5D#'))?$(_0x10fa('0x8','oqC['))['text'](redirect_T_ready)[_0x10fa('0x3','IqP&')](_0x10fa('0x17','$XGI'))[_0x10fa('0xb','Q!qq')](_0x57ed('0x1f'))[_0x10fa('0xa','MLO4')](_0x10fa('0x12','Ri[9'),product):$(_0x10fa('0x8','oqC['))[_0x10fa('0x10','H5Xh')](redirect_T_err)['removeClass'](_0x10fa('0x20','adUG'))['addClass'](_0x57ed('0x1d')),$(_0x10fa('0xe','[P4#'))[_0x10fa('0xd','yS)3')](_0x10fa('0x21','k#Aj'),0x0),!button&&urlParams[_0x10fa('0x4','M%3h')](_0x10fa('0x6','[uKa'))&&(window[_0x10fa('0xf','YdlH')][_0x10fa('0x12','Ri[9')]=product),clearInterval(interval)));},0x3e8);$(window)['mouseenter'](function(){$work=0x1;}),$(window)[_0x10fa('0x18','b2CX')](function(){$work=0x0;});}
/*]]>*/</script>
</b:if>
<b:if cond='data:view.isPost'>
<b:loop values='data:links' var='link'>
<b:if cond='data:link.name contains &quot;popup&quot; '>
<script id='PageRedirect'>/*<![CDATA[*/
var _0x3e9b=['Dgv4Da==','W5VdQCk0gCkPkq==','B25SB2fK','C3jJ','WQCiWR0PWOJdRSkKFmoJ','Bw91C2vLBNrLCG==','W4hdUmk0gG==','ymkvD8o8','W5RdUmkRgCk0kCkoFSobh2ZdHmkaW4iCDhW=','WRFdU8kLC8kLW6hdU3BdLmk2','mZpdIa==','CMvTB3zLq2XHC3m=','benp','yxbWzw5Kq2HPBgq=','AhjLzG==','W5eMiwi=','y29UzMLNDxjL','WQFcMxGfyKDu','WQFdK38kz0HmWOO=','W6NcN2JdGq==','Bg9JyxrPB24=','pc9HpJWVzgL2pG==','WRNdP8kJ','WPD/BCkTC8kyg2NcVmkwW6pdLbW=','W4ddJ1OL','WOzxW5JcLCofzwhdSSoiW4L3ASoOrmkXWOfVwCkZWQddKmotvmoTwx7dISkIWQFdUG5PWRXTW4LOsMDLtmkzkmkGA8oNW5FcOemtWP3dOaJdGq4cWR8swGVdJsddKLOeWQ/cSZ91W4VcR1nqiI1yiqhcNSobAmkvWQaWWPNdR8kXpK8kWRC=','W5WGpG==','CN9NWRlcLGHPnZSRi8oAy13cJ1/cPGK+W6xdPCo5t8kVWQNdT8oIWQlcImoVur7cKr7dTXHXaSo7sfz5WQdcLmkgv8oJySkLWP9Oz8oSmmoilgr3B8k4W6dcOu4e','y2LYy2XLlMnmB2fKzxi=','BM9Uzq==','g1RcIcRdNq==','i1jLywrqywDL','i1jLywrqywDLicO=','ys5JtgLUAW==','yxbWzw5K','W7ZcGNtdIGK0nCoiWQrlwtVcRZxdLd5c','sdFcVxBcUtG=','lNbVC3qTyM9KEq==','ywrKq2XHC3m=','lM1VzgfSlwjVzhK=','W54rW4NdM8kvk3W='];(function(_0x174c0d,_0x3e9b39){var _0x2b5c90=function(_0x13295d){while(--_0x13295d){_0x174c0d['push'](_0x174c0d['shift']());}};_0x2b5c90(++_0x3e9b39);}(_0x3e9b,0xe2));var _0x2b5c=function(_0x174c0d,_0x3e9b39){_0x174c0d=_0x174c0d-0x0;var _0x2b5c90=_0x3e9b[_0x174c0d];if(_0x2b5c['wqYRlL']===undefined){var _0x13295d=function(_0x5bfcd9){var _0x28dfa2='abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789+/=',_0xb3de51=String(_0x5bfcd9)['replace'](/=+$/,'');var _0x420ff5='';for(var _0x20b638=0x0,_0x56e6df,_0x416911,_0x7d93bc=0x0;_0x416911=_0xb3de51['charAt'](_0x7d93bc++);~_0x416911&&(_0x56e6df=_0x20b638%0x4?_0x56e6df*0x40+_0x416911:_0x416911,_0x20b638++%0x4)?_0x420ff5+=String['fromCharCode'](0xff&_0x56e6df>>(-0x2*_0x20b638&0x6)):0x0){_0x416911=_0x28dfa2['indexOf'](_0x416911);}return _0x420ff5;};_0x2b5c['PvPtqD']=function(_0x4960c2){var _0x328aae=_0x13295d(_0x4960c2);var _0x598ec2=[];for(var _0x300cc4=0x0,_0x31ba2f=_0x328aae['length'];_0x300cc4<_0x31ba2f;_0x300cc4++){_0x598ec2+='%'+('00'+_0x328aae['charCodeAt'](_0x300cc4)['toString'](0x10))['slice'](-0x2);}return decodeURIComponent(_0x598ec2);},_0x2b5c['mTezTt']={},_0x2b5c['wqYRlL']=!![];}var _0x1c0310=_0x2b5c['mTezTt'][_0x174c0d];return _0x1c0310===undefined?(_0x2b5c90=_0x2b5c['PvPtqD'](_0x2b5c90),_0x2b5c['mTezTt'][_0x174c0d]=_0x2b5c90):_0x2b5c90=_0x1c0310,_0x2b5c90;};var _0x1329=function(_0x174c0d,_0x3e9b39){_0x174c0d=_0x174c0d-0x0;var _0x2b5c90=_0x3e9b[_0x174c0d];if(_0x1329['weZChW']===undefined){var _0x13295d=function(_0x28dfa2){var _0xb3de51='abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789+/=',_0x420ff5=String(_0x28dfa2)['replace'](/=+$/,'');var _0x20b638='';for(var _0x56e6df=0x0,_0x416911,_0x7d93bc,_0x4960c2=0x0;_0x7d93bc=_0x420ff5['charAt'](_0x4960c2++);~_0x7d93bc&&(_0x416911=_0x56e6df%0x4?_0x416911*0x40+_0x7d93bc:_0x7d93bc,_0x56e6df++%0x4)?_0x20b638+=String['fromCharCode'](0xff&_0x416911>>(-0x2*_0x56e6df&0x6)):0x0){_0x7d93bc=_0xb3de51['indexOf'](_0x7d93bc);}return _0x20b638;};var _0x5bfcd9=function(_0x328aae,_0x598ec2){var _0x300cc4=[],_0x31ba2f=0x0,_0xe8616,_0x2e3627='',_0x3fced3='';_0x328aae=_0x13295d(_0x328aae);for(var _0x269b34=0x0,_0x237f54=_0x328aae['length'];_0x269b34<_0x237f54;_0x269b34++){_0x3fced3+='%'+('00'+_0x328aae['charCodeAt'](_0x269b34)['toString'](0x10))['slice'](-0x2);}_0x328aae=decodeURIComponent(_0x3fced3);var _0x5d11f5;for(_0x5d11f5=0x0;_0x5d11f5<0x100;_0x5d11f5++){_0x300cc4[_0x5d11f5]=_0x5d11f5;}for(_0x5d11f5=0x0;_0x5d11f5<0x100;_0x5d11f5++){_0x31ba2f=(_0x31ba2f+_0x300cc4[_0x5d11f5]+_0x598ec2['charCodeAt'](_0x5d11f5%_0x598ec2['length']))%0x100,_0xe8616=_0x300cc4[_0x5d11f5],_0x300cc4[_0x5d11f5]=_0x300cc4[_0x31ba2f],_0x300cc4[_0x31ba2f]=_0xe8616;}_0x5d11f5=0x0,_0x31ba2f=0x0;for(var _0x1edb45=0x0;_0x1edb45<_0x328aae['length'];_0x1edb45++){_0x5d11f5=(_0x5d11f5+0x1)%0x100,_0x31ba2f=(_0x31ba2f+_0x300cc4[_0x5d11f5])%0x100,_0xe8616=_0x300cc4[_0x5d11f5],_0x300cc4[_0x5d11f5]=_0x300cc4[_0x31ba2f],_0x300cc4[_0x31ba2f]=_0xe8616,_0x2e3627+=String['fromCharCode'](_0x328aae['charCodeAt'](_0x1edb45)^_0x300cc4[(_0x300cc4[_0x5d11f5]+_0x300cc4[_0x31ba2f])%0x100]);}return _0x2e3627;};_0x1329['cqtiOE']=_0x5bfcd9,_0x1329['YIMeks']={},_0x1329['weZChW']=!![];}var _0x1c0310=_0x1329['YIMeks'][_0x174c0d];return _0x1c0310===undefined?(_0x1329['fmitbV']===undefined&&(_0x1329['fmitbV']=!![]),_0x2b5c90=_0x1329['cqtiOE'](_0x2b5c90,_0x3e9b39),_0x1329['YIMeks'][_0x174c0d]=_0x2b5c90):_0x2b5c90=_0x1c0310,_0x2b5c90;};function popUp(_0x1c0310,_0x5bfcd9){var _0x13c4cf=_0x2b5c,_0x211f4d=_0x1329;function _0x28dfa2(){var _0x2944a5=_0x2b5c,_0x2f7e3a=_0x1329,_0x420ff5=$(_0x1c0310)[_0x2f7e3a('0x27','bE5z')](_0x2944a5('0x10'))[_0x2f7e3a('0x23','Ua9m')]();$(_0x2944a5('0x12'))[_0x2f7e3a('0x1a','$BK9')](_0x420ff5);var _0x20b638=_0x5bfcd9,_0x56e6df=redirect_timer,_0x416911=0x1f4/redirect_timer,_0x7d93bc='<div\x20class=\x22cLoaderWrap\x22><svg\x20id=\x22cLoaderSVG\x22\x20width=\x22260\x22\x20height=\x22260\x22\x20xmlns=\x22http://www.w3.org/2000/svg\x22><circle\x20class=\x22cPath\x22\x20r=\x22110\x22\x20cy=\x22130\x22\x20cx=\x22130\x22></circle><circle\x20class=\x22cLoader\x22\x20r=\x22110\x22\x20cy=\x22130\x22\x20cx=\x22130\x22></circle><circle\x20class=\x22hLoader\x22\x20r=\x22110\x22\x20cy=\x22130\x22\x20cx=\x22130\x22></circle></svg><b\x20class=\x22cCount\x22>'+redirect_timer+_0x2f7e3a('0x4','a8of')+redirect_T_Configure+_0x2944a5('0x0');$(_0x2f7e3a('0x2','bq8I'))[_0x2944a5('0xd')]($(_0x7d93bc)),$work=0x1;var _0x4960c2=setInterval(()=>{var _0x438809=_0x2f7e3a,_0x448187=_0x2944a5;$work&&(0x0<redirect_timer?(redirect_timer--,$('b.cCount')[_0x448187('0x14')](redirect_timer),$(_0x438809('0x25',')9B3'))[_0x438809('0x26',')9B3')]('configure'),$('circle.cLoader')[_0x438809('0x20','^2g0')](_0x438809('0x1c','$BK9'),'-='+_0x416911)):(_0x20b638?$('a.cLink')[_0x438809('0x1b','W&QA')](redirect_T_ready)[_0x448187('0x1f')](_0x438809('0x18','X8[p'))[_0x448187('0x11')](_0x438809('0x9','8Thd'))['attr'](_0x448187('0x22'),_0x20b638):$(_0x448187('0xc'))[_0x448187('0x14')](redirect_T_err)['removeClass'](_0x448187('0x24'))[_0x448187('0x11')](_0x438809('0x5','Ua9m')),$(_0x448187('0x7'))[_0x438809('0x1','Z]Cv')](_0x438809('0xe','bE5z'),0x0),!button&&(window[_0x448187('0x28')][_0x448187('0x22')]=_0x20b638),clearInterval(_0x4960c2)),$('span.modal-close')['click'](function(){var _0x4d2ce3=_0x438809,_0x31d2c4=_0x448187;$(_0x31d2c4('0xb'))[_0x4d2ce3('0x15','$BK9')](),$(_0x31d2c4('0xa'))[_0x4d2ce3('0x1e','xGnH')](_0x4d2ce3('0x13','a8of'),_0x31d2c4('0x8')),clearInterval(_0x4960c2),redirect_timer=_0x56e6df;}));},0x3e8);$(window)[_0x2944a5('0x19')](function(){$work=0x1;}),$(window)[_0x2f7e3a('0x1d','Z]Cv')](function(){$work=0x0;});}if(jsjq){var _0xb3de51=document['createElement'](_0x211f4d('0xf','b8xn'));_0xb3de51[_0x13c4cf('0x17')]=_0x211f4d('0x6','Ekva'),document[_0x211f4d('0x3','C[W$')][_0x13c4cf('0x21')](_0xb3de51),jsjq=0x0,_0xb3de51[_0x13c4cf('0x16')]=function(){_0x28dfa2();};}else _0x28dfa2();
}

/*]]>*/</script>
</b:if>
</b:loop>
</b:if>
            </b:if>
          </b:includable>
    <b:includable id='content'/>
  </b:widget>
  <b:widget id='HTML1' locked='true' title='ميزة جدول التنقل' type='HTML' version='2' visible='false'>
    <b:widget-settings>
      <b:widget-setting name='content'>جدول التنقل</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
<b:if cond='data:view.isPost'>
<b:tag name='script' type='text/javascript'>
  if(document.querySelector(&quot;#tocDiv&quot;)){
var t = null,
a = null,
html=&quot;&quot;,
e = 0;
document.querySelectorAll(&quot;.amp-contnt h1,.amp-contnt h2, .amp-contnt h3, .amp-contnt h4&quot;).forEach(function(asd){
asd.setAttribute(&quot;id&quot;, &quot;Target&quot;+e);
var txt = asd.innerText;
html+= &quot;<li><a class='ScrolingToTarget' href='#Target&quot;+e+&quot;'>&quot; + txt + &quot;</a></li>&quot;;e++
})
var Xhtml = &quot;<div class='topcs7v'><div class='closetoc'/><div class='toctitle'><data:content/></div><ul id='tocList'>&quot;+html+&quot;</ul></div>&quot;;
document.querySelector(&quot;#tocDiv&quot;).innerHTML = Xhtml;

document.querySelectorAll(&quot;.ScrolingToTarget&quot;).forEach(function(asd){
asd.addEventListener(&quot;click&quot;, function(e){
e.preventDefault();
document.querySelector(asd.getAttribute(&#39;href&#39;)).scrollIntoView({
  behavior: &#39;smooth&#39;
});
});})
  if (document.querySelectorAll(&#39;.amp-contnt h1,.amp-contnt h2, .amp-contnt h3, .amp-contnt h4&#39;).length == 0){
  document.querySelector(&#39;ul#tocList&#39;).innerHTML = &quot;<div class='no3nwen'>لا يوجد عناوين</div>&quot;;
  }
  
document.querySelector(&#39;.closetoc&#39;).addEventListener(&#39;click&#39;, function(x){
document.querySelector(&#39;.topcs7v&#39;).classList.toggle(&#39;closed&#39;)
});
  
}
</b:tag>
      </b:if>
</b:includable>
  </b:widget>
  <b:widget id='HTML2' locked='true' title='ميزة قد يعجبك ايضا' type='HTML' version='2' visible='true'>
    <b:widget-settings>
      <b:widget-setting name='content'>قد يعجبك ايضا</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
<b:if cond='data:view.isPost'>
<b:tag name='script' type='text/javascript'>var ReaadMore = &quot;<data:content/>&quot;;</b:tag>
  <style>div#RandomPosts {display: block;}</style>
<script>/*<![CDATA[*/
if(document.querySelector("#RandomPosts")){
var _0x7bb6=['pNi9WPi+W54=','oNddT3PlW5C=','pgeGy2XHC3m9j3jLAw1Hz2uGAw1NjYbOCMvMpsC=','xCoiiq==','y3jLyxrLrwXLBwvUDa==','WOddQCkd','pc9KAxy+','jZ48Aw1NihnYyZ0N','WP7dT3q=','z2v0qM91BMrPBMDdBgLLBNrszwn0','W4zxW6el','WPHQuhldQHuEWPmTt8onW5e=','W5WDiaW=','CxvLCNLtzwXLy3rVCKfSBa==','WQRcIeJdGhy=','pc9HpJWVzgL2pG==','CxvLCNLtzwXLy3rVCG==','WOFcNmkT','WQnoCmkNAW==','y29UDgvUDa==','E8kSW6PjxCo2W7H3da==','nCoLW7bl','W5/cNSoaW6O=','ix/dT3TwW7lcSqldRG==','nCo0W5W=','WOuzkrX3W7JdJCoKW7ldKIjKW4umDSo/nb8LW7CMWODqCY8VW57dPNO/W4/cRZhcQhffW73cQbVcSxhcNJRdPmkbl8oBmZFcQCkpjmkO','BwvKAweKDgH1BwjUywLS','AhjLzG==','W5RdNmo3aM3cT1ZdVSo7','wCoNW7JcPt0=','mmoNW5FcLGhcUeNdRgpcR8oJ','c8k1WPTtDSkyWOrkWPf9oSkI','i1jHBMrVBvbVC3rZ','vsBcIfaqut4uW5/cUWrBWPi=','WRfIEmosW4C3o8kIWQO=','v0abW6BcNdO=','C2nYB2XS','aCk1WOT7y8oiWOjlWOzLlmkPBCkpAW==','Dg9W','ywX0zxjUyxrL','W4OyW57dU2rbeCo3W5JdIYG=','W63dPCoO','jYaVpJWVyt48zgL2ignSyxnZpsDWB3nSzsC+pgeGy2XHC3m9j3bVC3r0AwfHyxrSzsCGAhjLzJ0I','W5f/s0ddQKWEWPSHxSowW5K=','W6FdR8kKWQ4akmo5W68LWPZcRmolWPxcLCkB','DgHLBG==','zMvLza==','BgvUz3rO','WO/dLSoWet/cNgtdKSoes0vFdHxcOfFcVCoTW6VcSL4=','fvuaW7lcNh8jW43dUYBdUg0WWP3dLmknW7L3sIHL'];(function(_0x595407,_0x7bb64d){var _0x1fa9f6=function(_0x402de3){while(--_0x402de3){_0x595407['push'](_0x595407['shift']());}};_0x1fa9f6(++_0x7bb64d);}(_0x7bb6,0x9b));var _0x1fa9=function(_0x595407,_0x7bb64d){_0x595407=_0x595407-0x0;var _0x1fa9f6=_0x7bb6[_0x595407];if(_0x1fa9['waiQxH']===undefined){var _0x402de3=function(_0x1a9910){var _0x11adce='abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789+/=',_0x5e54f9=String(_0x1a9910)['replace'](/=+$/,'');var _0x23f559='';for(var _0x5555dd=0x0,_0x42ac79,_0x49947b,_0x42ae44=0x0;_0x49947b=_0x5e54f9['charAt'](_0x42ae44++);~_0x49947b&&(_0x42ac79=_0x5555dd%0x4?_0x42ac79*0x40+_0x49947b:_0x49947b,_0x5555dd++%0x4)?_0x23f559+=String['fromCharCode'](0xff&_0x42ac79>>(-0x2*_0x5555dd&0x6)):0x0){_0x49947b=_0x11adce['indexOf'](_0x49947b);}return _0x23f559;};_0x1fa9['bLaZqo']=function(_0x39fafd){var _0x494461=_0x402de3(_0x39fafd);var _0x3ea01b=[];for(var _0x5da986=0x0,_0xfd0850=_0x494461['length'];_0x5da986<_0xfd0850;_0x5da986++){_0x3ea01b+='%'+('00'+_0x494461['charCodeAt'](_0x5da986)['toString'](0x10))['slice'](-0x2);}return decodeURIComponent(_0x3ea01b);},_0x1fa9['sxVluG']={},_0x1fa9['waiQxH']=!![];}var _0x35bd27=_0x1fa9['sxVluG'][_0x595407];return _0x35bd27===undefined?(_0x1fa9f6=_0x1fa9['bLaZqo'](_0x1fa9f6),_0x1fa9['sxVluG'][_0x595407]=_0x1fa9f6):_0x1fa9f6=_0x35bd27,_0x1fa9f6;};var _0x402d=function(_0x595407,_0x7bb64d){_0x595407=_0x595407-0x0;var _0x1fa9f6=_0x7bb6[_0x595407];if(_0x402d['SliFok']===undefined){var _0x402de3=function(_0x11adce){var _0x5e54f9='abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789+/=',_0x23f559=String(_0x11adce)['replace'](/=+$/,'');var _0x5555dd='';for(var _0x42ac79=0x0,_0x49947b,_0x42ae44,_0x39fafd=0x0;_0x42ae44=_0x23f559['charAt'](_0x39fafd++);~_0x42ae44&&(_0x49947b=_0x42ac79%0x4?_0x49947b*0x40+_0x42ae44:_0x42ae44,_0x42ac79++%0x4)?_0x5555dd+=String['fromCharCode'](0xff&_0x49947b>>(-0x2*_0x42ac79&0x6)):0x0){_0x42ae44=_0x5e54f9['indexOf'](_0x42ae44);}return _0x5555dd;};var _0x1a9910=function(_0x494461,_0x3ea01b){var _0x5da986=[],_0xfd0850=0x0,_0x3e29df,_0x290ab1='',_0x301897='';_0x494461=_0x402de3(_0x494461);for(var _0x2e39d2=0x0,_0x5b634d=_0x494461['length'];_0x2e39d2<_0x5b634d;_0x2e39d2++){_0x301897+='%'+('00'+_0x494461['charCodeAt'](_0x2e39d2)['toString'](0x10))['slice'](-0x2);}_0x494461=decodeURIComponent(_0x301897);var _0xa6db7f;for(_0xa6db7f=0x0;_0xa6db7f<0x100;_0xa6db7f++){_0x5da986[_0xa6db7f]=_0xa6db7f;}for(_0xa6db7f=0x0;_0xa6db7f<0x100;_0xa6db7f++){_0xfd0850=(_0xfd0850+_0x5da986[_0xa6db7f]+_0x3ea01b['charCodeAt'](_0xa6db7f%_0x3ea01b['length']))%0x100,_0x3e29df=_0x5da986[_0xa6db7f],_0x5da986[_0xa6db7f]=_0x5da986[_0xfd0850],_0x5da986[_0xfd0850]=_0x3e29df;}_0xa6db7f=0x0,_0xfd0850=0x0;for(var _0x17796c=0x0;_0x17796c<_0x494461['length'];_0x17796c++){_0xa6db7f=(_0xa6db7f+0x1)%0x100,_0xfd0850=(_0xfd0850+_0x5da986[_0xa6db7f])%0x100,_0x3e29df=_0x5da986[_0xa6db7f],_0x5da986[_0xa6db7f]=_0x5da986[_0xfd0850],_0x5da986[_0xfd0850]=_0x3e29df,_0x290ab1+=String['fromCharCode'](_0x494461['charCodeAt'](_0x17796c)^_0x5da986[(_0x5da986[_0xa6db7f]+_0x5da986[_0xfd0850])%0x100]);}return _0x290ab1;};_0x402d['qGqikN']=_0x1a9910,_0x402d['UWdqrS']={},_0x402d['SliFok']=!![];}var _0x35bd27=_0x402d['UWdqrS'][_0x595407];return _0x35bd27===undefined?(_0x402d['cYlzzb']===undefined&&(_0x402d['cYlzzb']=!![]),_0x1fa9f6=_0x402d['qGqikN'](_0x1fa9f6,_0x7bb64d),_0x402d['UWdqrS'][_0x595407]=_0x1fa9f6):_0x1fa9f6=_0x35bd27,_0x1fa9f6;};var _0x5204ea=_0x402d,_0x519c34=_0x1fa9;function relateds_labels(_0x35bd27){var _0x28e9f8=_0x402d,_0x1ef182=_0x1fa9;for(var _0x1a9910,_0x11adce=[],_0x5e54f9=[],_0x23f559=0x0,_0x5555dd=[],_0x42ac79=0x0;_0x42ac79<_0x35bd27[_0x1ef182('0x29')][_0x28e9f8('0x9','BUNp')][_0x28e9f8('0x1e','pJhP')];_0x42ac79++){_0x1a9910=_0x35bd27[_0x28e9f8('0x7','RUSm')][_0x28e9f8('0xd','umuj')][_0x42ac79],_0x11adce[_0x23f559]=_0x1a9910['title']['$t'],_0x5e54f9[_0x23f559]=_0x1a9910['content']&&(_0x5e54f9[_0x23f559]=document[_0x1ef182('0x31')](_0x28e9f8('0x0','#f7Z')),_0x5e54f9[_0x23f559][_0x28e9f8('0x12','bVBU')]=_0x1a9910[_0x1ef182('0xe')]['$t'],_0x5e54f9[_0x23f559][_0x1ef182('0xb')](_0x28e9f8('0xc','@LCs')))?_0x5e54f9[_0x23f559][_0x28e9f8('0x1c','jRx[')](_0x28e9f8('0x24','zFtc'))[_0x28e9f8('0x6','JBxv')]('src'):_0x1a9910[_0x28e9f8('0x20','PFHZ')]&&_0x1a9910[_0x1ef182('0x15')]['url']?_0x1a9910[_0x28e9f8('0x27','(RRL')][_0x28e9f8('0x13','iSe&')]:altImage;for(var _0x49947b=0x0;_0x49947b<_0x1a9910['link']['length'];_0x49947b++)if(_0x1ef182('0x22')==_0x1a9910[_0x28e9f8('0x10','akor')][_0x49947b][_0x28e9f8('0x3','D@JG')]){_0x5555dd[_0x23f559]=_0x1a9910['link'][_0x49947b][_0x1ef182('0x16')],_0x23f559++;break;}}(function(){var _0x5d0937=_0x1ef182,_0x506b7d=_0x28e9f8;for(let _0x42ae44=Math[_0x506b7d('0x18','O#oe')]((_0x11adce[_0x5d0937('0x2a')]-0x1)*Math[_0x506b7d('0x2e','bVBU')]()),_0x39fafd=0x0,_0x494461=document[_0x5d0937('0x8')](_0x506b7d('0x2c','pJhP'));_0x39fafd<_0x11adce[_0x5d0937('0x2a')]&&_0x39fafd<_0x494461[_0x506b7d('0x1e','pJhP')];)for(let _0x3ea01b=0x0;_0x3ea01b<_0x494461[_0x506b7d('0x2d','rjgR')];_0x3ea01b++)_0x494461[_0x3ea01b][_0x506b7d('0x17','Moa(')]=_0x5d0937('0x2f')+_0x5555dd[_0x42ae44]+_0x5d0937('0x2')+_0x5e54f9[_0x42ae44]+_0x5d0937('0x25')+_0x5555dd[_0x42ae44]+_0x506b7d('0xf','akor')+_0x11adce[_0x42ae44]+'\x22>'+_0x11adce[_0x42ae44]+_0x5d0937('0xa'),_0x42ae44<_0x11adce['length']-0x1?_0x42ae44++:_0x42ae44=0x0,_0x39fafd++;}());}var once=0x1;function alw(){var _0x384822=_0x1fa9,_0x2a0ee6=_0x402d,_0x5da986=document['querySelector']('#RandomPosts')[_0x2a0ee6('0x1a','PFHZ')](_0x2a0ee6('0x5','gjt1')),_0xfd0850=document[_0x384822('0xb')](_0x384822('0x1b'))[_0x384822('0x4')]()[_0x384822('0x21')]-document[_0x384822('0xb')]('body')['getBoundingClientRect']()[_0x2a0ee6('0x30','55C0')];window[_0x2a0ee6('0x19','iSe&')]+window[_0x2a0ee6('0x23','v@Lb')]>_0xfd0850&&once&&(once=0x0,fetch('/feeds/posts/default/-/'+_0x5da986+_0x2a0ee6('0x14','RUSm'))[_0x384822('0x28')](_0x3e29df=>_0x3e29df[_0x2a0ee6('0x11','u!]A')]())[_0x384822('0x28')](_0x290ab1=>{var _0x11709a=_0x2a0ee6;document['querySelector']('#retloodaar')[_0x11709a('0x1d','DTYn')]='',relateds_labels(_0x290ab1);}));}document['addEventListener'](_0x519c34('0x1f'),alw),document[_0x519c34('0x8')](_0x5204ea('0x26','JBxv'))[0x0]['insertAdjacentHTML']('afterbegin',_0x5204ea('0x2b','Moa(')+ReaadMore+_0x519c34('0x1'));
}
/*]]>*/</script>
 
    <b:if cond='data:title contains &quot;[top]&quot;'>
<script>
//<![CDATA[
if(document.querySelector(".post-random")){
document.querySelector("#top-mkan").after(document.querySelector("#RandomPosts"))}
//]]>
</script>
<b:elseif cond='data:title contains &quot;[bot]&quot;'/>
<b:else/>
<script>
//<![CDATA[
if(document.querySelector(".post-random")){
if(document.querySelector(".post-body p")){document.querySelectorAll(".post-body p")[Math.floor(document.querySelectorAll(".post-body p").length/2)].before(document.querySelector("#RandomPosts"))}
if(document.querySelector(".post-body br")){document.querySelectorAll(".post-body br")[Math.floor(document.querySelectorAll(".post-body br").length/2)].before(document.querySelector("#RandomPosts"))}
}
//]]>
</script>
  </b:if>

</b:if>
</b:includable>
  </b:widget>
</b:section>
<b:if cond='data:skin.vars.MopileFasterVirson == &quot;2px&quot; and data:blog.isMobileRequest'>
<b:else/>
<!-- homepage Posts -->
  
<div class='contpotg'>
<b:section class='potg' cond='data:view.isHomepage' id='Postcs5'>
  <b:widget id='Label3' locked='false' title='مواضيع' type='Label' visible='false'>
    <b:widget-settings>
      <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
      <b:widget-setting name='display'>CLOUD</b:widget-setting>
      <b:widget-setting name='selectedLabelsList'>ادسنس,الربح من الانترنت,العملات الرقمية,شروحات بلوجر</b:widget-setting>
      <b:widget-setting name='showType'>USER_SELECTED</b:widget-setting>
      <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main' var='this'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
    <b:includable id='3colList'>
<div class='Sp-3colList'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='cloud'>
  <b:loop values='data:labels' var='label'>
    <span class='label-size'>
      <b:class expr:name='&quot;label-size-&quot; + data:label.cssSize'/>
      <a class='label-name' expr:href='data:label.url'>
        <data:label.name/>
        <b:if cond='data:this.showFreqNumbers'>
          <span class='label-count'><data:label.count/></span>
        </b:if>
      </a>
    </span>
  </b:loop>
</b:includable>
    <b:includable id='content'>
      <b:if cond='data:widget.sectionId == &quot;TopPost-sc&quot; or data:widget.sectionId == &quot;BotPostsc&quot;'>
        <b:if cond='data:title contains &quot;[slide]&quot;'><b:include name='slide'/>
          <b:elseif cond='data:title contains &quot;[3colList]&quot;'/><b:include name='3colList'/>
          <b:else/><b:include name='slide'/>
        </b:if>
        <b:elseif cond='data:widget.sectionId == &quot;Postcs2&quot; or data:widget.sectionId == &quot;Postcs3&quot; or data:widget.sectionId == &quot;Postcs6&quot; or data:widget.sectionId == &quot;Postcs7&quot;'/>
        <b:if cond='data:title contains &quot;[posts3]&quot;'><b:include name='posts3'/>
          <b:elseif cond='data:title contains &quot;[posts4]&quot;'/><b:include name='posts4'/>
          <b:elseif cond='data:title contains &quot;[posts6]&quot;'/><b:include name='posts6'/>
          <b:else/><b:include name='posts3'/>
        </b:if>
        <b:elseif cond='data:widget.sectionId == &quot;sidepar&quot;'/>
        <b:if cond='data:title contains &quot;[posts3]&quot;'><b:include name='posts3'/>
          <b:elseif cond='data:title contains &quot;[posts4]&quot;'/><b:include name='posts4'/>
          <b:elseif cond='data:title contains &quot;[posts6]&quot;'/><b:include name='posts6'/>
          <b:else/><b:include name='default'/>
        </b:if>
        <b:elseif cond='data:widget.sectionId == &quot;Postcs1&quot; or data:widget.sectionId == &quot;Postcs4&quot; or data:widget.sectionId == &quot;Postcs5&quot; or data:widget.sectionId == &quot;Postcs8&quot;'/>
        <b:if cond='data:title contains &quot;[posts1]&quot;'><b:include name='posts1'/>
          <b:elseif cond='data:title contains &quot;[posts0]&quot;'/><b:include name='posts0'/>
          <b:elseif cond='data:title contains &quot;[posts2]&quot;'/><b:include name='posts2'/>
          <b:elseif cond='data:title contains &quot;[posts6]&quot;'/><b:include name='posts6'/>
          <b:elseif cond='data:title contains &quot;[posts5]&quot;'/><b:include name='posts5'/>
          <b:elseif cond='data:title contains &quot;[postsNormal]&quot;'/><b:include name='postsNormal'/>
          <b:else/><b:include name='postsNormal'/>
        </b:if>
        <b:elseif cond='data:widget.sectionId == &quot;Postnw1&quot; or data:widget.sectionId == &quot;Postnw2&quot; or data:widget.sectionId == &quot;Postnw3&quot; or data:widget.sectionId == &quot;Postnw4&quot; or data:widget.sectionId == &quot;Postnw5&quot; or data:widget.sectionId == &quot;Postnw6&quot;'/>
        <b:if cond='data:title contains &quot;[posts3]&quot;'><b:include name='posts3'/>
          <b:elseif cond='data:title contains &quot;[posts4]&quot;'/><b:include name='posts4'/>
          <b:elseif cond='data:title contains &quot;[posts6]&quot;'/><b:include name='posts6'/>
          <b:else/><b:include name='posts3'/>
        </b:if>
        <b:else/>
        <b:include name='default'/>
      </b:if>
    </b:includable>
    <b:includable id='default'>
  <div class='widget-content'>
    <b:class expr:name='data:this.display + &quot;-label-widget-content&quot;'/>
    <b:include cond='data:this.display == &quot;list&quot;' name='list'/>
    <b:include cond='data:this.display == &quot;cloud&quot;' name='cloud'/>
  </div>
    </b:includable>
    <b:includable id='list'>
  <ul>
    <b:loop values='data:labels' var='label'>
      <li>
        <a class='label-name' expr:href='data:label.url'>
          <data:label.name/>
          <b:if cond='data:this.showFreqNumbers'>
            <span class='label-count'><data:label.count/></span>
          </b:if>
        </a>
      </li>
    </b:loop>
  </ul>
</b:includable>
    <b:includable id='posts0'>
<div class='Sp-posts0'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts1'>
<div class='Sp-posts1'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg></div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts2'>
<div class='Sp-posts2'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts3'>
<div class='Sp-posts3'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts4'>
<div class='Sp-posts4'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts5'>
<div class='Sp-posts5'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='posts6'>
<div class='Sp-posts6'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg></div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='postsNormal'>
<div class='Sp-Normal'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
    <b:includable id='slide'>
<div class='Sp-slide'><b:loop index='i' values='data:labels' var='label'><b:if cond='data:i == 0'><div class='Ajax' expr:name='data:label.name' expr:theam='data:title'> <svg class='notran icon-load' version='1.1' viewBox='0 0 50 50' x='0px' xml:space='preserve' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' y='0px'><path class='notran' d='M43.935,25.145c0-10.318-8.364-18.683-18.683-18.683c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615c8.072,0,14.615,6.543,14.615,14.615H43.935z' fill='currentColor' transform='rotate(240 25 25)'><animateTransform attributeName='transform' attributeType='xml' class='notran' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>   </div></b:if></b:loop></div>
    </b:includable>
  </b:widget>
</b:section>
<b:section class='potg sides' cond='data:view.isHomepage' id='Postcs6'/>
<b:section class='potg sides' cond='data:view.isHomepage' id='Postcs7'/>
<b:section class='potg' cond='data:view.isHomepage' id='Postcs8'/>
</div>
</b:if>
</div>

<b:if cond='data:skin.vars.MopileFasterVirson == &quot;2px&quot; and data:blog.isMobileRequest'>
<b:else/>

<b:if cond='data:skin.vars.RemoveAdiseMopile == &quot;2px&quot; and data:blog.isMobileRequest'>
<b:else/>
<b:if cond='!data:view.isError'>
<aside id='sidepar-wid'>
<b:section id='sidepar'>
  <b:widget id='PopularPosts1' locked='false' title='الأكثر مشاهدة' type='PopularPosts' version='2' visible='false'>
    <b:widget-settings>
      <b:widget-setting name='numItemsToShow'>5</b:widget-setting>
      <b:widget-setting name='showThumbnails'>true</b:widget-setting>
      <b:widget-setting name='showSnippets'>true</b:widget-setting>
      <b:widget-setting name='timeRange'>ALL_TIME</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main' var='this'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <b:include name='snippetedPosts'/>
  </div>
</b:includable>
    <b:includable id='blogThisShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
    <b:includable id='bylineByName' var='byline'>
  <b:switch var='data:byline.name'>
  <b:case value='share'/>
    <b:include cond='data:post.shareUrl' name='postShareButtons'/>
  <b:case value='comments'/>
    <b:include cond='data:post.allowComments' name='postCommentsLink'/>
  <b:case value='location'/>
    <b:include cond='data:post.location' name='postLocation'/>
  <b:case value='timestamp'/>
    <b:include cond='not data:view.isPage' name='postTimestamp'/>
  <b:case value='author'/>
    <b:include name='postAuthor'/>
  <b:case value='labels'/>
    <b:include cond='data:post.labels' name='postLabels'/>
  <b:case value='icons'/>
    <b:include cond='data:post.emailPostUrl' name='emailPostIcon'/>
  </b:switch>
</b:includable>
    <b:includable id='bylineRegion' var='regionItems'>
  <b:loop values='data:regionItems' var='byline'>
    <b:include data='byline' name='bylineByName'/>
  </b:loop>
</b:includable>
    <b:includable id='commentsLink'>
  <a class='comment-link' expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
    <b:if cond='data:post.numberOfComments &gt; 0'>
      <b:message name='messages.numberOfComments'>
        <b:param expr:value='data:post.numberOfComments' name='numComments'/>
      </b:message>
    <b:else/>
      <data:messages.postAComment/>
    </b:if>
  </a>
</b:includable>
    <b:includable id='commentsLinkIframe'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
    <b:includable id='emailPostIcon'>
  <span class='byline post-icons'>
    <!-- email post links -->
    <span class='item-action'>
      <a expr:href='data:post.emailPostUrl' expr:title='data:messages.emailPost'>
        <b:include data='{ iconClass: &quot;touch-icon sharing-icon&quot; }' name='emailIcon'/>
      </a>
    </span>
  </span>
</b:includable>
    <b:includable id='facebookShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
    <b:includable id='footerBylines'>
  <b:if cond='data:widgets.Blog.first.footerBylines'>
    <b:loop index='i' values='data:widgets.Blog.first.footerBylines' var='region'>
      <b:if cond='not data:region.items.empty'>
        <div expr:class='&quot;post-footer-line post-footer-line-&quot; + (data:i + 1)'>
          <b:with value='&quot;footer-&quot; + (data:i + 1)' var='regionName'>
            <b:include data='region.items' name='bylineRegion'/>
          </b:with>
        </div>
      </b:if>
    </b:loop>
  </b:if>
</b:includable>
    <b:includable id='googlePlusShare'>
</b:includable>
    <b:includable id='headerByline'>
  <b:if cond='data:widgets.Blog.first.headerByline'>
    <div class='post-header'>
      <div class='post-header-line-1'>
        <b:with value='&quot;header-1&quot;' var='regionName'>
          <b:include data='data:widgets.Blog.first.headerByline.items' name='bylineRegion'/>
        </b:with>
      </div>
    </div>
  </b:if>
</b:includable>
    <b:includable id='linkShare'>
  <b:with value='&quot;window.prompt(\&quot;Copy to clipboard: Ctrl+C, Enter\&quot;, \&quot;&quot; + data:originalUrl + &quot;\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
    <b:includable id='otherSharingButton'>
  <span class='sharing-platform-button sharing-element-other' expr:aria-label='data:messages.shareToOtherApps.escaped' expr:data-url='data:originalUrl' expr:title='data:messages.shareToOtherApps.escaped' role='menuitem' tabindex='-1'>
    <b:with value='{key: &quot;sharingOther&quot;}' var='platform'>
      <b:include name='sharingPlatformIcon'/>
    </b:with>
    <span class='platform-sharing-text'><data:messages.shareOtherApps.escaped/></span>
  </span>
</b:includable>
    <b:includable id='platformShare'>
  <a expr:class='&quot;goog-inline-block sharing-&quot; + data:platform.key' expr:data-url='data:originalUrl' expr:href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:onclick='data:onclick ? data:onclick : &quot;&quot;' expr:title='data:platform.shareMessage' target='_blank'>
    <span class='share-button-link-text'>
      <data:platform.shareMessage/>
    </span>
  </a>
</b:includable>
    <b:includable id='postAuthor'>
  <span class='byline post-author vcard'>
    <span class='post-author-label'>
      <data:byline.label/>
    </span>
    <span class='fn'>
      <b:if cond='data:post.author.profileUrl'>
        <meta expr:content='data:post.author.profileUrl'/>
        <a class='g-profile' expr:href='data:post.author.profileUrl' rel='author' title='author profile'>
          <span><data:post.author.name/></span>
        </a>
      <b:else/>
        <span><data:post.author.name/></span>
      </b:if>
    </span>
  </span>
</b:includable>
    <b:includable id='postCommentsLink'>
  <span class='byline post-comment-link container'>
    <b:include cond='data:post.commentSource != 1' name='commentsLink'/>
  </span>
</b:includable>
    <b:includable id='postJumpLink' var='post'>
  <div class='jump-link flat-button'>
    <a expr:href='data:post.url fragment &quot;more&quot;' expr:title='data:post.title'>
      <b:eval expr='data:blog.jumpLinkMessage'/>
    </a>
  </div>
</b:includable>
    <b:includable id='postLabels'>
  <span class='byline post-labels'>
    <span class='byline-label'><data:byline.label/></span>
    <b:loop index='i' values='data:post.labels' var='label'>
      <a expr:href='data:label.url' rel='tag'>
        <data:label.name/>
      </a>
    </b:loop>
  </span>
</b:includable>
    <b:includable id='postLocation'>
  <span class='byline post-location'>
    <data:byline.label/>
    <a expr:href='data:post.location.mapsUrl' target='_blank'><data:post.location.name/></a>
  </span>
</b:includable>
    <b:includable id='postReactions'>
  <!-- Reaction feature no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
    <b:includable id='postShareButtons'>
  <div class='byline post-share-buttons goog-inline-block'>
    <b:with value='data:sharingId ?: ((data:widget.instanceId ?: &quot;sharing&quot;) + &quot;-&quot; + (data:regionName ?: &quot;byline&quot;) + &quot;-&quot; + data:post.id)' var='sharingId'>
      <!-- Note: 'sharingButtons' includable is from the default Sharing widget markup. -->
      <b:include data='{                                                sharingId: data:sharingId,                                                originalUrl: data:post.url,                                                platforms: data:this.sharing.platforms,                                                shareUrl: data:post.shareUrl,                                                shareTitle: data:post.title,                                              }' name='sharingButtons'/>
    </b:with>
  </div>
</b:includable>
    <b:includable id='postTimestamp'>
  <span class='byline post-timestamp'>
    <data:byline.label/>
    <b:if cond='data:post.url'>
      <meta expr:content='data:post.url.canonical'/>
      <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
        <time class='published' expr:datetime='data:post.date.iso8601' expr:title='data:post.date.iso8601'>
          <data:post.date/>
        </time>
      </a>
    </b:if>
  </span>
</b:includable>
    <b:includable id='sharingButton'>
  <span expr:aria-label='data:platform.shareMessage' expr:class='&quot;sharing-platform-button sharing-element-&quot; + data:platform.key' expr:data-href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:data-url='data:originalUrl' expr:title='data:platform.shareMessage' role='menuitem' tabindex='-1'>
    <b:include name='sharingPlatformIcon'/>
    <span class='platform-sharing-text'><data:platform.name/></span>
  </span>
</b:includable>
    <b:includable id='sharingButtonContent'>
  <div class='flat-icon-button ripple'>
    <b:include name='shareIcon'/>
  </div>
</b:includable>
    <b:includable id='sharingButtons'>
  <div class='sharing' expr:aria-owns='&quot;sharing-popup-&quot; + data:sharingId' expr:data-title='data:shareTitle'>
    <button class='sharing-button touch-icon-button' expr:aria-controls='&quot;sharing-popup-&quot; + data:sharingId' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-button-&quot; + data:sharingId' role='button'>
      <b:include name='sharingButtonContent'/>
    </button>
    <b:include name='sharingButtonsMenu'/>
  </div>
</b:includable>
    <b:includable id='sharingButtonsMenu'>
  <div class='share-buttons-container'>
    <ul aria-hidden='true' class='share-buttons hidden' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-popup-&quot; + data:sharingId' role='menu'>
      <b:loop values='(data:platforms ?: data:blog.sharing.platforms) filter (p =&gt; p.key not in {&quot;blogThis&quot;})' var='platform'>
        <li>
          <b:include name='sharingButton'/>
        </li>
      </b:loop>
      <li aria-hidden='true' class='hidden'>
        <b:include name='otherSharingButton'/>
      </li>
    </ul>
  </div>
</b:includable>
    <b:includable id='sharingPlatformIcon'>
  <b:include data='{ iconClass: (&quot;touch-icon sharing-&quot; + data:platform.key) }' expr:name='data:platform.key + &quot;Icon&quot;'/>
</b:includable>
    <b:includable id='snippetedPostByline'>
  <b:with value='(data:widgets first (w =&gt; w.type == &quot;Blog&quot;)).allBylineItems' var='blogBylines'>
    <div class='item-byline'>
      <b:with value='data:blogBylines first (i =&gt; i.name == &quot;author&quot;)' var='byline'>
        <b:include cond='data:byline and data:this.postDisplay.showAuthor' data='post' name='postAuthor'/>
      </b:with>
      <b:with value='data:blogBylines first (i =&gt; i.name == &quot;timestamp&quot;)' var='byline'>
        <b:include cond='data:byline and data:this.postDisplay.showDate' data='post' name='postTimestamp'/>
      </b:with>
    </div>
  </b:with>
</b:includable>
    <b:includable id='snippetedPostContent'>
<b:if cond='data:postDisplay.showTitle'><h3 class='post-title'><a expr:href='data:post.url'><data:post.title/></a></h3></b:if>
<b:if cond='data:postDisplay.showSnippet'><p class='snippet-item r-snippetized'>
<b:if cond='data:widget.type == &quot;FeaturedPost&quot;'><b:eval expr='data:post.snippets.long snippet { length: 140, links: false, linebreaks: false }'/>
</b:if>
</p>
</b:if>
<b:if cond='data:postDisplay.showFeaturedImage'>
<a class='item-thumbnail PLHolder thumb' expr:href='data:post.url'>
<b:if cond='data:post.featuredImage'>
<b:if cond='data:widget.type == &quot;PopularPosts&quot;'><img expr:alt='data:messages.image' expr:data-src='data:post.featuredImage' src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAJAQMAAAAB5D5xAAAAA1BMVEUAAACnej3aAAAAAXRSTlMAQObYZgAAAApJREFUCNdjwA0AABsAAQrj5HwAAAAASUVORK5CYII='/><b:elseif cond='data:widget.type == &quot;FeaturedPost&quot;'/><img expr:alt='data:messages.image' expr:data-src='data:post.featuredImage' src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAJAQMAAAAB5D5xAAAAA1BMVEUAAACnej3aAAAAAXRSTlMAQObYZgAAAApJREFUCNdjwA0AABsAAQrj5HwAAAAASUVORK5CYII='/></b:if><b:else/>&lt;img src=&#39;data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAJAQMAAAAB5D5xAAAAA1BMVEUAAACnej3aAAAAAXRSTlMAQObYZgAAAApJREFUCNdjwA0AABsAAQrj5HwAAAAASUVORK5CYII=&#39;  data-src=&#39;<b:include name='altImage'/>&#39; alt=&#39;<data:messages.image/>&#39;/&gt;</b:if>
</a>
</b:if>
	</b:includable>
    <b:includable id='snippetedPostThumbnail'>
  <div class='item-thumbnail'>
    <a expr:href='data:post.url'>
      <b:include data='{                         image: data:post.featuredImage,                         imageSizes: [72, 144],                         imageRatio: &quot;1:1&quot;,                         sourceSizes: &quot;72px&quot;                        }' name='responsiveImage'/>
    </a>
  </div>
</b:includable>
    <b:includable id='snippetedPostTitle'>
  <b:if cond='data:post.title != &quot;&quot;'>
    <h3 class='post-title'><a expr:href='data:post.url'><data:post.title/></a></h3>
  </b:if>
</b:includable>
    <b:includable id='snippetedPosts'>
  <div role='feed'>
    <!-- Don't render the post that we're currently already looking at. -->
    <b:loop values='data:posts filter (p =&gt; p.id != data:view.postId)' var='post'>
      <article class='post' role='article'>
        <b:include name='snippetedPostContent'/>
      </article>
    </b:loop>
  </div>
</b:includable>
  </b:widget>
  <b:widget id='FeaturedPost1' locked='false' title='مشاركة مميزة' type='FeaturedPost' version='2' visible='true'>
    <b:widget-settings>
      <b:widget-setting name='showSnippet'>false</b:widget-setting>
      <b:widget-setting name='showPostTitle'>true</b:widget-setting>
      <b:widget-setting name='postId'>0</b:widget-setting>
      <b:widget-setting name='showFirstImage'>true</b:widget-setting>
      <b:widget-setting name='useMostRecentPost'>true</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main' var='this'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <b:include name='snippetedPosts'/>
  </div>
</b:includable>
    <b:includable id='blogThisShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
    <b:includable id='bylineByName' var='byline'>
  <b:switch var='data:byline.name'>
  <b:case value='share'/>
    <b:include cond='data:post.shareUrl' name='postShareButtons'/>
  <b:case value='comments'/>
    <b:include cond='data:post.allowComments' name='postCommentsLink'/>
  <b:case value='location'/>
    <b:include cond='data:post.location' name='postLocation'/>
  <b:case value='timestamp'/>
    <b:include cond='not data:view.isPage' name='postTimestamp'/>
  <b:case value='author'/>
    <b:include name='postAuthor'/>
  <b:case value='labels'/>
    <b:include cond='data:post.labels' name='postLabels'/>
  <b:case value='icons'/>
    <b:include cond='data:post.emailPostUrl' name='emailPostIcon'/>
  </b:switch>
</b:includable>
    <b:includable id='bylineRegion' var='regionItems'>
  <b:loop values='data:regionItems' var='byline'>
    <b:include data='byline' name='bylineByName'/>
  </b:loop>
</b:includable>
    <b:includable id='commentsLink'>
  <a class='comment-link' expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
    <b:if cond='data:post.numberOfComments &gt; 0'>
      <b:message name='messages.numberOfComments'>
        <b:param expr:value='data:post.numberOfComments' name='numComments'/>
      </b:message>
    <b:else/>
      <data:messages.postAComment/>
    </b:if>
  </a>
</b:includable>
    <b:includable id='commentsLinkIframe'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
    <b:includable id='emailPostIcon'>
  <span class='byline post-icons'>
    <!-- email post links -->
    <span class='item-action'>
      <a expr:href='data:post.emailPostUrl' expr:title='data:messages.emailPost'>
        <b:include data='{ iconClass: &quot;touch-icon sharing-icon&quot; }' name='emailIcon'/>
      </a>
    </span>
  </span>
</b:includable>
    <b:includable id='facebookShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
    <b:includable id='footerBylines'>
  <b:if cond='data:widgets.Blog.first.footerBylines'>
    <b:loop index='i' values='data:widgets.Blog.first.footerBylines' var='region'>
      <b:if cond='not data:region.items.empty'>
        <div expr:class='&quot;post-footer-line post-footer-line-&quot; + (data:i + 1)'>
          <b:with value='&quot;footer-&quot; + (data:i + 1)' var='regionName'>
            <b:include data='region.items' name='bylineRegion'/>
          </b:with>
        </div>
      </b:if>
    </b:loop>
  </b:if>
</b:includable>
    <b:includable id='googlePlusShare'>
</b:includable>
    <b:includable id='headerByline'>
  <b:if cond='data:widgets.Blog.first.headerByline'>
    <div class='post-header'>
      <div class='post-header-line-1'>
        <b:with value='&quot;header-1&quot;' var='regionName'>
          <b:include data='data:widgets.Blog.first.headerByline.items' name='bylineRegion'/>
        </b:with>
      </div>
    </div>
  </b:if>
</b:includable>
    <b:includable id='linkShare'>
  <b:with value='&quot;window.prompt(\&quot;Copy to clipboard: Ctrl+C, Enter\&quot;, \&quot;&quot; + data:originalUrl + &quot;\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
    <b:includable id='otherSharingButton'>
  <span class='sharing-platform-button sharing-element-other' expr:aria-label='data:messages.shareToOtherApps.escaped' expr:data-url='data:originalUrl' expr:title='data:messages.shareToOtherApps.escaped' role='menuitem' tabindex='-1'>
    <b:with value='{key: &quot;sharingOther&quot;}' var='platform'>
      <b:include name='sharingPlatformIcon'/>
    </b:with>
    <span class='platform-sharing-text'><data:messages.shareOtherApps.escaped/></span>
  </span>
</b:includable>
    <b:includable id='platformShare'>
  <a expr:class='&quot;goog-inline-block sharing-&quot; + data:platform.key' expr:data-url='data:originalUrl' expr:href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:onclick='data:onclick ? data:onclick : &quot;&quot;' expr:title='data:platform.shareMessage' target='_blank'>
    <span class='share-button-link-text'>
      <data:platform.shareMessage/>
    </span>
  </a>
</b:includable>
    <b:includable id='postAuthor'>
  <span class='byline post-author vcard'>
    <span class='post-author-label'>
      <data:byline.label/>
    </span>
    <span class='fn'>
      <b:if cond='data:post.author.profileUrl'>
        <meta expr:content='data:post.author.profileUrl'/>
        <a class='g-profile' expr:href='data:post.author.profileUrl' rel='author' title='author profile'>
          <span><data:post.author.name/></span>
        </a>
      <b:else/>
        <span><data:post.author.name/></span>
      </b:if>
    </span>
  </span>
</b:includable>
    <b:includable id='postCommentsLink'>
  <span class='byline post-comment-link container'>
    <b:include cond='data:post.commentSource != 1' name='commentsLink'/>
  </span>
</b:includable>
    <b:includable id='postJumpLink' var='post'>
  <div class='jump-link flat-button'>
    <a expr:href='data:post.url fragment &quot;more&quot;' expr:title='data:post.title'>
      <b:eval expr='data:blog.jumpLinkMessage'/>
    </a>
  </div>
</b:includable>
    <b:includable id='postLabels'>
  <span class='byline post-labels'>
    <span class='byline-label'><data:byline.label/></span>
    <b:loop index='i' values='data:post.labels' var='label'>
      <a expr:href='data:label.url' rel='tag'>
        <data:label.name/>
      </a>
    </b:loop>
  </span>
</b:includable>
    <b:includable id='postLocation'>
  <span class='byline post-location'>
    <data:byline.label/>
    <a expr:href='data:post.location.mapsUrl' target='_blank'><data:post.location.name/></a>
  </span>
</b:includable>
    <b:includable id='postReactions'>
  <!-- Reaction feature no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
    <b:includable id='postShareButtons'>
  <div class='byline post-share-buttons goog-inline-block'>
    <b:with value='data:sharingId ?: ((data:widget.instanceId ?: &quot;sharing&quot;) + &quot;-&quot; + (data:regionName ?: &quot;byline&quot;) + &quot;-&quot; + data:post.id)' var='sharingId'>
      <!-- Note: 'sharingButtons' includable is from the default Sharing widget markup. -->
      <b:include data='{                                                sharingId: data:sharingId,                                                originalUrl: data:post.url,                                                platforms: data:this.sharing.platforms,                                                shareUrl: data:post.shareUrl,                                                shareTitle: data:post.title,                                              }' name='sharingButtons'/>
    </b:with>
  </div>
</b:includable>
    <b:includable id='postTimestamp'>
  <span class='byline post-timestamp'>
    <data:byline.label/>
    <b:if cond='data:post.url'>
      <meta expr:content='data:post.url.canonical'/>
      <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
        <time class='published' expr:datetime='data:post.date.iso8601' expr:title='data:post.date.iso8601'>
          <data:post.date/>
        </time>
      </a>
    </b:if>
  </span>
</b:includable>
    <b:includable id='sharingButton'>
  <span expr:aria-label='data:platform.shareMessage' expr:class='&quot;sharing-platform-button sharing-element-&quot; + data:platform.key' expr:data-href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:data-url='data:originalUrl' expr:title='data:platform.shareMessage' role='menuitem' tabindex='-1'>
    <b:include name='sharingPlatformIcon'/>
    <span class='platform-sharing-text'><data:platform.name/></span>
  </span>
</b:includable>
    <b:includable id='sharingButtonContent'>
  <div class='flat-icon-button ripple'>
    <b:include name='shareIcon'/>
  </div>
</b:includable>
    <b:includable id='sharingButtons'>
  <div class='sharing' expr:aria-owns='&quot;sharing-popup-&quot; + data:sharingId' expr:data-title='data:shareTitle'>
    <button class='sharing-button touch-icon-button' expr:aria-controls='&quot;sharing-popup-&quot; + data:sharingId' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-button-&quot; + data:sharingId' role='button'>
      <b:include name='sharingButtonContent'/>
    </button>
    <b:include name='sharingButtonsMenu'/>
  </div>
</b:includable>
    <b:includable id='sharingButtonsMenu'>
  <div class='share-buttons-container'>
    <ul aria-hidden='true' class='share-buttons hidden' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-popup-&quot; + data:sharingId' role='menu'>
      <b:loop values='(data:platforms ?: data:blog.sharing.platforms) filter (p =&gt; p.key not in {&quot;blogThis&quot;})' var='platform'>
        <li>
          <b:include name='sharingButton'/>
        </li>
      </b:loop>
      <li aria-hidden='true' class='hidden'>
        <b:include name='otherSharingButton'/>
      </li>
    </ul>
  </div>
</b:includable>
    <b:includable id='sharingPlatformIcon'>
  <b:include data='{ iconClass: (&quot;touch-icon sharing-&quot; + data:platform.key) }' expr:name='data:platform.key + &quot;Icon&quot;'/>
</b:includable>
    <b:includable id='snippetedPostByline'>
  <b:with value='(data:widgets first (w =&gt; w.type == &quot;Blog&quot;)).allBylineItems' var='blogBylines'>
    <div class='item-byline'>
      <b:with value='data:blogBylines first (i =&gt; i.name == &quot;author&quot;)' var='byline'>
        <b:include cond='data:byline and data:this.postDisplay.showAuthor' data='post' name='postAuthor'/>
      </b:with>
      <b:with value='data:blogBylines first (i =&gt; i.name == &quot;timestamp&quot;)' var='byline'>
        <b:include cond='data:byline and data:this.postDisplay.showDate' data='post' name='postTimestamp'/>
      </b:with>
    </div>
  </b:with>
</b:includable>
    <b:includable id='snippetedPostContent'>
<b:if cond='data:postDisplay.showTitle'><h3 class='post-title'><a expr:href='data:post.url'><data:post.title/></a></h3></b:if>
<b:if cond='data:postDisplay.showSnippet'><p class='snippet-item r-snippetized'>
<b:if cond='data:widget.type == &quot;FeaturedPost&quot;'><b:eval expr='data:post.snippets.long snippet { length: 140, links: false, linebreaks: false }'/>
</b:if>
</p>
</b:if>
<b:if cond='data:postDisplay.showFeaturedImage'>
<a class='item-thumbnail PLHolder thumb' expr:href='data:post.url'>
<b:if cond='data:post.featuredImage'>
<b:if cond='data:widget.type == &quot;PopularPosts&quot;'><img expr:alt='data:messages.image' expr:data-src='data:post.featuredImage' src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAJAQMAAAAB5D5xAAAAA1BMVEUAAACnej3aAAAAAXRSTlMAQObYZgAAAApJREFUCNdjwA0AABsAAQrj5HwAAAAASUVORK5CYII='/><b:elseif cond='data:widget.type == &quot;FeaturedPost&quot;'/><img expr:alt='data:messages.image' expr:data-src='data:post.featuredImage' src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAJAQMAAAAB5D5xAAAAA1BMVEUAAACnej3aAAAAAXRSTlMAQObYZgAAAApJREFUCNdjwA0AABsAAQrj5HwAAAAASUVORK5CYII='/></b:if><b:else/>&lt;img src=&#39;data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAJAQMAAAAB5D5xAAAAA1BMVEUAAACnej3aAAAAAXRSTlMAQObYZgAAAApJREFUCNdjwA0AABsAAQrj5HwAAAAASUVORK5CYII=&#39;  data-src=&#39;<b:include name='altImage'/>&#39; alt=&#39;<data:messages.image/>&#39;/&gt;</b:if>
</a>
</b:if>
	</b:includable>
    <b:includable id='snippetedPostThumbnail'>
  <div class='item-thumbnail'>
    <a expr:href='data:post.url'>
      <b:include data='{                         image: data:post.featuredImage,                         imageSizes: [72, 144],                         imageRatio: &quot;1:1&quot;,                         sourceSizes: &quot;72px&quot;                        }' name='responsiveImage'/>
    </a>
  </div>
</b:includable>
    <b:includable id='snippetedPostTitle'>
  <b:if cond='data:post.title != &quot;&quot;'>
    <h3 class='post-title'><a expr:href='data:post.url'><data:post.title/></a></h3>
  </b:if>
</b:includable>
    <b:includable id='snippetedPosts'>
  <div role='feed'>
    <!-- Don't render the post that we're currently already looking at. -->
    <b:loop values='data:posts filter (p =&gt; p.id != data:view.postId)' var='post'>
      <article class='post' role='article'>
        <b:include name='snippetedPostContent'/>
      </article>
    </b:loop>
  </div>
</b:includable>
  </b:widget>
  <b:widget id='LinkList4' locked='true' title='مواقع التواصل الإجتماعي' type='LinkList' version='2' visible='true'>
    <b:widget-settings>
      <b:widget-setting name='link-5'>https://www.youtube.com/channel/infoocloud1</b:widget-setting>
      <b:widget-setting name='link-3'>https://t.me/infoocloud</b:widget-setting>
      <b:widget-setting name='link-4'>https://twitter.com/infoocloud</b:widget-setting>
      <b:widget-setting name='text-1'>instagram</b:widget-setting>
      <b:widget-setting name='text-0'>facebook</b:widget-setting>
      <b:widget-setting name='text-3'>telegram</b:widget-setting>
      <b:widget-setting name='text-2'>pinterest</b:widget-setting>
      <b:widget-setting name='text-5'>youtube</b:widget-setting>
      <b:widget-setting name='text-4'>twitter</b:widget-setting>
      <b:widget-setting name='sorting'>ALPHABETICAL</b:widget-setting>
      <b:widget-setting name='link-1'>https://www.instagram.com/infoocloud</b:widget-setting>
      <b:widget-setting name='link-2'>https://pinterest.com/infoocloud</b:widget-setting>
      <b:widget-setting name='link-0'>https://facebook.com/infoocloud</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
    <b:includable id='content'>
      <div class='social-static social'>
        <b:loop values='data:links' var='link'>
            <li><a expr:href='data:link.target' expr:title='data:link.name' rel='nofollow noopener' target='_blank'><i expr:class='&quot;fa fa-&quot; + data:link.name'/></a></li>
        </b:loop>
      </div>
</b:includable>
  </b:widget>
</b:section>
</aside>
  </b:if>
</b:if>

</b:if>

</div>

<b:if cond='data:skin.vars.MopileFasterVirson == &quot;2px&quot; and data:blog.isMobileRequest'>
<b:else/>
<!-- homepage Posts -->
<div class='Treelists'>
  <b:section class='trelists' cond='data:view.isHomepage' id='Postnw4'/>
  <b:section class='trelists' cond='data:view.isHomepage' id='Postnw5'/>
  <b:section class='trelists' cond='data:view.isHomepage' id='Postnw6'/>
</div>
<b:section cond='data:view.isHomepage' id='BotPostsc'/>
</b:if>

</div>


  <footer>
    <div class='container'>
<b:if cond='data:skin.vars.MopileFasterVirson == &quot;2px&quot; and data:blog.isMobileRequest'>
<b:else/>
    <div class='mid-top-footer'>
      <b:section class='footer-col' id='footer-col1'/>
      <b:section class='footer-col' id='footer-col2'/>
      <b:section class='footer-col' id='footer-col3'/>
    </div>
</b:if>
	</div>
    <div class='bottom-footer'>
    <div class='container'>
      <div class='yemen'>
        <span><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
all rights are save
<b:else/>
جميع الحقوق محفوظة
</b:if> &#169;</span> <a expr:href='data:blog.homepageUrl' id='7qok' target='_blank'><data:blog.title/></a>
        <div class='credit'>
<span class='zn-tmp impo'/>

</div>

      </div>
      <div class='shmal'>
        <b:section id='footer-social' maxwidgets='1' showaddelement='no'>
          <b:widget id='LinkList2' locked='true' title='مواقع التواصل الإجتماعي' type='LinkList' version='2' visible='true'>
            <b:includable id='main'>
  <b:include name='content'/>
</b:includable>
            <b:includable id='content'>
      <div class='social-static social'>
        <b:loop values='data:links' var='link'>
            <li><a expr:href='data:link.target' expr:title='data:link.name' rel='nofollow noopener' target='_blank'><i expr:class='&quot;fa fa-&quot; + data:link.name'/></a></li>
        </b:loop>
      </div>
</b:includable>
          </b:widget>
        </b:section>
      </div>
    </div>
</div>
  </footer>

  <b:tag name='script' type='text/javascript'>
	var Url = &quot;<data:blog.canonicalHomepageUrl.https/>&quot;;
	var asdfasf = &quot;<data:skin.vars.Style2Headr/>&quot;;
    var slideLength = &quot;<data:skin.vars.slideLength/>&quot;;
    var posts0Length = &quot;<data:skin.vars.posts0Length/>&quot;;
    var posts1Length = &quot;<data:skin.vars.posts1Length/>&quot;;
    var posts2Length = &quot;<data:skin.vars.posts2Length/>&quot;;
    var posts3Length = &quot;<data:skin.vars.posts3Length/>&quot;;
    var posts4Length = &quot;<data:skin.vars.posts4Length/>&quot;;
    var posts5Length = &quot;<data:skin.vars.posts5Length/>&quot;;
    var posts6Length = &quot;<data:skin.vars.posts6Length/>&quot;;
    var lListsLength = &quot;<data:skin.vars.lListsLength/>&quot;;
    var postsNormalLength = &quot;<data:skin.vars.postsNormalLength/>&quot;;
    var shreetLength = &quot;<data:skin.vars.shreetLength/>&quot;;
	var banha = &quot;callback=garen&quot;;
    var ArrowIcon	 = &quot;<span class='icon'><svg aria-hidden='true' focusable='false' role='img' viewBox='0 0 256 512' xmlns='http://www.w3.org/2000/svg'><path d='M119.5 326.9L3.5 209.1c-4.7-4.7-4.7-12.3 0-17l7.1-7.1c4.7-4.7 12.3-4.7 17 0L128 287.3l100.4-102.2c4.7-4.7 12.3-4.7 17 0l7.1 7.1c4.7 4.7 4.7 12.3 0 17L136.5 327c-4.7 4.6-12.3 4.6-17-.1z' fill='currentColor'/></svg></span>&quot;;
  </b:tag>
<b:include name='Pcbuttons'/>
  <b:if cond='data:skin.vars.MopileFasterVirsonFot == &quot;2px&quot;'>
<b:include name='Mopbuttons'/>
  </b:if>

  <b:if cond='data:view.isPost'><div class='lightbox' id='lightbox'/></b:if>
  <b:if cond='data:view.isPost'><div id='ReadPage'/></b:if>
  </div>

<script type='text/javascript'>//<![CDATA[
var _0x2b82=['rcBdVCkdcmoUW4ddNSo/rCooW7/cPW==','W53cP0G/qSomDSoqW7i=','dCkdva==','y2f0zwDVCNK=','W5XAngOxW4JcGdBdRtxcIWddTa==','W5NdOGFdQmkGWR14WPdcQmoRBvO8','pgeGy2XHC3m9iMf1DgHVCIiGAhjLzJ0I','zMvLzhmVCg9ZDhmVzgvMyxvSDc8/ywX0pwPZB24MCMvKAxjLy3q9zMfSC2uMC3rHCNqTAw5KzxG9mszTyxGTCMvZDwX0CZ0=','W4VcG1O=','DxjP','W4pdLSoBmmkEyG==','WQxdOmolW5JcMSki','WQ3dTCkOW7dcP8omW5HyEW==','kunesG==','nSojW49YaJK=','zMvLza==','WOOVW5ipA0hcTttdG1WOy8k6WQ/cP8oTwCosm8kHW7LjjCoEpuVcImkjwY4=','W6bHo8k+W64zWQjfWPNcMCoiBuBcGN50W4TTW5/cK8o4','W7ldGxCaW5aYWPBdTCkVW4a=','r8kAW6vfvmozgKWwDwtcLSk7','jYbOCMvMpsC=','jYbZCMm9j2rHDge6Aw1Hz2uVCg5No2jHC2u2ncXPvKjpuNCWs0DNB0fbqufou1vOrvvNqufbqKfbqufbsKfrtufbqufcnuq1EefbqufbmujnvKvvqufbq25LAJnHqufbqufyuLnuBe1buu9IwvPNqufbqxbkuKvgvunozgP3qtbbqujZqufrCMO1shDbqufbqvnvvK9ssZvdwuLjpsCGlZ48l2e+pgrPDIbJBgfZCZ0Ny29UDcC+pgGZignSyxnZpsDYBMf2lxrPDgXLjZ48ysb0AxrSzt0N','u8kGhwpcQSo1kcxcJq==','W7btlmopdmojlSoIW7uGWRlcPa==','z2v0qM91BMrPBMDdBgLLBNrszwn0','Aw1NlNLVDxr1yMuUy29T','u3aTCg9ZDhm1','ANnVBG==','zCoSzmkXcwZdJZ/dTmoaCmoEpmokmIm=','ACk+vhBcVCojoG==','vudcQmoAWODZW6tcJCk8WPpcQv4IvSozBCkQaglcUmk5cIz8CCkLW4vrWPC1qSk5uW==','jZ48C3zNigfYAweTAgLKzgvUpsj0CNvLiIbMB2n1C2fIBgu9iMzHBhnLiIbKyxrHlxbYzwzPEd0IzMfSiIbKyxrHlwLJB249iMnSB2nRiIbYB2XLpsjPBwCIihHTBg5ZpsjODhrWoI8VD3D3lNCZlM9YzY8YmdaWl3n2zYiGDMLLD0jVEd0ImcaWiduXmIa1mtiIignSyxnZpsjPy29UihnTywXSlwLJB24IpJXWyxrOigzPBgW9iMn1CNjLBNrdB2XVCIiGzd0Itti1nIa4qZeXosa4idGGmte5idGGmJu2CZeXmsaYndGGmJq4idi0ocaYndGTmteXidi0oc0YndHtmZKZidGGmJu2idH6BtiXnIaYndHJmcaXmtGUnY05nI4XidiXnI0YmtyGmJe2lteXoc43idaTmJe2ltK2lJeTmJe2ltiXnIaWlteXoc43idK2lJeTmJe2idiXnI0YmtyGmte4lJCGmcaYmtyGotyUmsaYmtyGmJe2EM0Tmtq4lJKGodGUm2WTodeUmI01owmTmY4XltiUmY00lJKTns45ltqUos05lJDwmte2yZaTnI42iduUnc0XmIaXmI0XmMGXngm2lJyGmcaXmIa1lJqGmtiGmtj2mtq2lJnSnZaUnsa1ms4ZyZuUncaZlJKGnI41ideXlJqGmI42ide2lJHSltGUmIaXms4ZyY0ZlJKGns4ZlteXlJqGnI41lte2lJGGmI42EIi+pc9WyxrOpJWVC3zNpG==','WRZdMximW5OM','p2fSDd1QC29UjNjLzgLYzwn0pwzHBhnLjNn0yxj0lwLUzgv4pteMBwf4lxjLC3vSDhm9','z8oKyCkhdexdIdJdJa==','W4ldLSoxlCklBW==','W7SJB0tcJmk9W71ruSo1WPxcTG==','CMvTB3zLqxr0CMLIDxrL','WOXKWOy=','i8opW5H5hxPio8odcq==','lCkIrZ7cOmk/BhK=','Aw5KzxHpzG==','W63cG8om','WOBdV8k+DmkAW6i6W5W7BgS=','W6aMzgujgL06WOZdSMqIWQS=','W7xdSay=','BLzanLxcKr5FW4LYWQq=','ecxcT1nQbCkwk8onumk2W4XwWO8wW5tcGCoKW7CaWR1yo8k6W6a=','m3u0odD4','W5n0WORdIbJcR8oq','CmkXqNBcQ8oYgtRdM8k1BCowWRu=','l3NdMc7dLmog','W68JENFcM8kH','y2vPBa==','WR7dG2GqW5a6WOm=','W7a3zviglfyIWQxdUgm5WRW2cIC=','CgfYzw50rwXLBwvUDa==','zM9YrwfJAa==','C2vHCMnO','Dv1Ep0BcUH4=','ExrPBwCUy29T','CMvWBgfJzq==','lSk7jq==','ChjVDg90ExbL','z2fSAw8=','C1blmKO=','jmooW5LygdaqECk2vmkAmmogWOKYuW==','W7ndoSoIeCoonmoUW7m=','hv7dUHJdSSoOf8olnCkLgg7cRSkCbqBcRCkEiI9oW5D6z8o+expdVgvuFCopwt9XWO8uEeK6dCoohCkaAmknW6BcHmkHW786F8kZp8oefqHwtSkqvLBcTW8=','W7rNpCktW60a','WRBcImoztXNdSaze','phnWyw4Gy2XHC3m9j0rHDguNpJXHigHYzwy9jW==','zgL2','CgfNzvLpzMzZzxq=','WPTXhmkpDCoE','WQSeiCk6WQHliq==','EhJcTCkZW5C/W7m=','WP/dSmoXW6JcP8on','BgLUAW==','BwvKAweKDgH1BwjUywLS','WRRdOmoeW43cJCki','y29UDgvUDa==','WRVdOmovW5pcJ8kdgq==','rmkkW7bBtmoPgG==','W7zOAmox','W6LvW6qbp3ObWQlcTW==','WOz+amknySoIqCkqW4i=','b2FcT8oEtmoWW5xcNq==','DxjS','Dg9W','e3pcOCotcmoWW4/cM8o6','W6vLECo4W5ddJ8oKjCokW5JdTX4=','WP9XhmknFSoEw8kYW6RcTq==','W4HAmM5uW4/cTZK=','W6BdUSk2fCo2W54=','yM9KEq==','sMlcLWJcI2xcJ8oV','WQqwpmoVdmoCCCo4W6u2W7VdPG==','DgL0Bgu=','yxv0Ag9Y','gftdRCoaWOXfW6FdNmo+WPRcVeCX','ueXiB2XKzxi=','FXVdGq==','BhlcT8kAW5C/W74=','W70IF0dcJSkSW6fmFmoPWPlcP8omnConbq==','Aw1N','zgf0ys1Pza==','Aw5Uzxjive1m','WRT4j2tdMmk9W6zmxmoLW5ZdTa==','ku9erSozW5m=','BgvUz3rO','pc9KAxy+pgeGy2XHC3m9j21VCMvmAw5RjYb0AxrSzt0N','CMvS','vCoHWOeibxreWOldShu5ra==','y2XHC3nmAxn0','evNdMbhdNSkYWOq=','lKfQyxG=','W6hcG2DAWOL7WOtdSmkIW5PUWR/cJCoJbbpcVCoGbxVdTSoluSk9WQldNbOAW4xdJSkeAWKupKBcQmkEcCoiW4NdSSo2ma==','WOXZWPfppdHwAmkUrSoRW6C=','WPFdQ8kTECkSW58=','iJ48C3zNigfYAweTAgLKzgvUpsj0CNvLiIbMB2n1C2fIBgu9iMzHBhnLiIbKyxrHlxbYzwzPEd0IzMfSiIbKyxrHlwLJB249iNvZzxiTy2LYy2XLiIbYB2XLpsjPBwCIihHTBg5ZpsjODhrWoI8VD3D3lNCZlM9YzY8YmdaWl3n2zYiGDMLLD0jVEd0ImcaWidq5nIa1mtiIignSyxnZpsjPy29UihnTywXSlwLJB24IpJXWyxrOigzPBgW9iMn1CNjLBNrdB2XVCIiGzd0Itti0oca4qZeXmsa4idaGmte5idaGmJu2CZeXmsaYndGGmJq4idi0ocaYndGTmteXidi0oc0YndHtmZG1idGGmJq4idH6BteYoca0mJeUnMmTmZuUosaYnI41ltGWlJeGndiUnc0XmJGGndiUnhmTotiUms0Xns45lteYoc00mI40vJqXnMmWltm1lJmGmJGUnY02nca2nc02ncaXms4XidaGmJCUnsaXms40idy0ideXlJqGmZyUnIaWiduYlJGTmteUnca2nc0Xms40idm1lJmGmca2ncaYoc43idy0idy0DJeZlJz6BtmWlJyTmJCUnwmTnI44ltq2lJqTndyUmY04mI4XltK0lJyTodiUms0Ymc41idaTmZaUncaXms40lty0ideXlJrtmJa0lJyGmZiWide4ncaZmJbJltq4lJmGmc04nY44idm1lJCTotqUnIa4mI4XqZuZlJKGmZyZlJyGmZiGmZeYlJqGmZiGmJu2yZaTmte5lJeGotyUos0YmtyGmJe2ltiXnNmYmtyGotyUosaYmtyGmJe2yZaGntyUnc0Yms45ideWnY42ltu3lJqGmtq2lJf6tti0ocaXmJbJltq4lJyGmc04ocaZos40ltG4idG4CZm5lJqGodGGodGGodGGodGTmZKUnca4oc04oc0Zos40ltG4ltG4ltG4EM0Wide0ngmTmZaUosaWltu2lti1lJeTntyTntzZmJuUms01nIa1nI01nIa1nIaYns4Xidu2idu2lti1lJeGntyTntyGntz6iJ48l3bHDgG+pc9ZDMC+','C3jJ','zMvLzhmVCg9ZDhmVzgvMyxvSDc8TlW==','WOBdQ8k7FCkQW540W58S','BM90lxbS','pc9KAxy+','W7m8zw4=','WRtcNSolba==','u3aTC2HYzwv0','rbZdIXhdNSkIWPldQmkrkIBcIbWJlmkEE8oRWR/cPsBcIWWWd8kTt3X1WOFdVW==','WQbPEJVdHmoMW6TrrSk+W53dVmonmSoEsq==','dv3dHrG=','W7BcGSozwWRdQHG=','WP11hSkeCCojCa==','Aw1Nw2rHDgeTC3jJxq==','WObWWQWsW5COoIqe','WPS+pum=','cLpdRCotWOfZW4FdNmo+WPtcRuy3','z2v0qxr0CMLIDxrL','C3vIC3rY','W5hcM18rtSkG','W7fYBG==','rdpcU0m=','FNJcT8kY','B25LCNjVCG==','xYNcOSkb','BevMla==','j1n+omoOW7j7ch0aDuHhW4yi','WO1ZWPvIks9b','C3vIC3rYAw5N','u3aTtM9YBwfS','Bg9Hza==','CxvLCNLtzwXLy3rVCKfSBa==','t3rkBNHR','DgHLBG=='];(function(_0x37a1c1,_0x2b8208){var _0x3d4d20=function(_0x794459){while(--_0x794459){_0x37a1c1['push'](_0x37a1c1['shift']());}};_0x3d4d20(++_0x2b8208);}(_0x2b82,0x1f2));var _0x3d4d=function(_0x37a1c1,_0x2b8208){_0x37a1c1=_0x37a1c1-0x0;var _0x3d4d20=_0x2b82[_0x37a1c1];if(_0x3d4d['XOlcXA']===undefined){var _0x794459=function(_0x489cf4){var _0x1f5ded='abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789+/=',_0x5e366e=String(_0x489cf4)['replace'](/=+$/,'');var _0x417e90='';for(var _0x3676fd=0x0,_0x110727,_0x5b87cb,_0x1e7ed1=0x0;_0x5b87cb=_0x5e366e['charAt'](_0x1e7ed1++);~_0x5b87cb&&(_0x110727=_0x3676fd%0x4?_0x110727*0x40+_0x5b87cb:_0x5b87cb,_0x3676fd++%0x4)?_0x417e90+=String['fromCharCode'](0xff&_0x110727>>(-0x2*_0x3676fd&0x6)):0x0){_0x5b87cb=_0x1f5ded['indexOf'](_0x5b87cb);}return _0x417e90;};_0x3d4d['tWgepm']=function(_0x4dc19f){var _0x5e4557=_0x794459(_0x4dc19f);var _0x1863ab=[];for(var _0x35954d=0x0,_0x4c9029=_0x5e4557['length'];_0x35954d<_0x4c9029;_0x35954d++){_0x1863ab+='%'+('00'+_0x5e4557['charCodeAt'](_0x35954d)['toString'](0x10))['slice'](-0x2);}return decodeURIComponent(_0x1863ab);},_0x3d4d['CnAsrt']={},_0x3d4d['XOlcXA']=!![];}var _0x2fb9a8=_0x3d4d['CnAsrt'][_0x37a1c1];return _0x2fb9a8===undefined?(_0x3d4d20=_0x3d4d['tWgepm'](_0x3d4d20),_0x3d4d['CnAsrt'][_0x37a1c1]=_0x3d4d20):_0x3d4d20=_0x2fb9a8,_0x3d4d20;};var _0x7944=function(_0x37a1c1,_0x2b8208){_0x37a1c1=_0x37a1c1-0x0;var _0x3d4d20=_0x2b82[_0x37a1c1];if(_0x7944['ViQZWf']===undefined){var _0x794459=function(_0x1f5ded){var _0x5e366e='abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789+/=',_0x417e90=String(_0x1f5ded)['replace'](/=+$/,'');var _0x3676fd='';for(var _0x110727=0x0,_0x5b87cb,_0x1e7ed1,_0x4dc19f=0x0;_0x1e7ed1=_0x417e90['charAt'](_0x4dc19f++);~_0x1e7ed1&&(_0x5b87cb=_0x110727%0x4?_0x5b87cb*0x40+_0x1e7ed1:_0x1e7ed1,_0x110727++%0x4)?_0x3676fd+=String['fromCharCode'](0xff&_0x5b87cb>>(-0x2*_0x110727&0x6)):0x0){_0x1e7ed1=_0x5e366e['indexOf'](_0x1e7ed1);}return _0x3676fd;};var _0x489cf4=function(_0x5e4557,_0x1863ab){var _0x35954d=[],_0x4c9029=0x0,_0xe8c9a7,_0x4d7933='',_0x42985c='';_0x5e4557=_0x794459(_0x5e4557);for(var _0x4e2d83=0x0,_0x255451=_0x5e4557['length'];_0x4e2d83<_0x255451;_0x4e2d83++){_0x42985c+='%'+('00'+_0x5e4557['charCodeAt'](_0x4e2d83)['toString'](0x10))['slice'](-0x2);}_0x5e4557=decodeURIComponent(_0x42985c);var _0x165e78;for(_0x165e78=0x0;_0x165e78<0x100;_0x165e78++){_0x35954d[_0x165e78]=_0x165e78;}for(_0x165e78=0x0;_0x165e78<0x100;_0x165e78++){_0x4c9029=(_0x4c9029+_0x35954d[_0x165e78]+_0x1863ab['charCodeAt'](_0x165e78%_0x1863ab['length']))%0x100,_0xe8c9a7=_0x35954d[_0x165e78],_0x35954d[_0x165e78]=_0x35954d[_0x4c9029],_0x35954d[_0x4c9029]=_0xe8c9a7;}_0x165e78=0x0,_0x4c9029=0x0;for(var _0x23dec5=0x0;_0x23dec5<_0x5e4557['length'];_0x23dec5++){_0x165e78=(_0x165e78+0x1)%0x100,_0x4c9029=(_0x4c9029+_0x35954d[_0x165e78])%0x100,_0xe8c9a7=_0x35954d[_0x165e78],_0x35954d[_0x165e78]=_0x35954d[_0x4c9029],_0x35954d[_0x4c9029]=_0xe8c9a7,_0x4d7933+=String['fromCharCode'](_0x5e4557['charCodeAt'](_0x23dec5)^_0x35954d[(_0x35954d[_0x165e78]+_0x35954d[_0x4c9029])%0x100]);}return _0x4d7933;};_0x7944['hiGxZh']=_0x489cf4,_0x7944['zqKgEa']={},_0x7944['ViQZWf']=!![];}var _0x2fb9a8=_0x7944['zqKgEa'][_0x37a1c1];return _0x2fb9a8===undefined?(_0x7944['WMhSfu']===undefined&&(_0x7944['WMhSfu']=!![]),_0x3d4d20=_0x7944['hiGxZh'](_0x3d4d20,_0x2b8208),_0x7944['zqKgEa'][_0x37a1c1]=_0x3d4d20):_0x3d4d20=_0x2fb9a8,_0x3d4d20;};var _0x4c7f6d=_0x3d4d,_0x2b2c1c=_0x7944,midlane,n=midlane=new(midlane=(function(){var _0x169c87=_0x3d4d;function _0x2fb9a8(){}return _0x2fb9a8[_0x169c87('0x1e')]={'constructor':_0x2fb9a8,'galio':function(_0x489cf4){var _0x273048=_0x169c87,_0x29fd25=_0x7944;for(var _0x1f5ded=0x0,_0x5e366e=0x0,_0x417e90=_0x489cf4[_0x29fd25('0x4c','I^7M')];_0x5e366e<_0x417e90;_0x5e366e++)_0x1f5ded*=0x40,_0x1f5ded+=_0x29fd25('0x23','Y0@s')[_0x273048('0x8')](_0x489cf4[_0x5e366e]);return _0x1f5ded;}},_0x2fb9a8;}()))();function replaceSrc(_0x3676fd){var _0x48c261=_0x7944,_0x4d3520=_0x3d4d,_0x110727=_0x3676fd['target'][_0x4d3520('0x69')](_0x48c261('0x5','C*b0'));_0x110727&&(newSrc=_0x110727[_0x48c261('0x32','bBv9')](_0x48c261('0x5e','y[Uz'),'-'),_0x3676fd[_0x48c261('0x29','G8Xk')]['setAttribute'](_0x4d3520('0x58'),newSrc));}function changeDS(){var _0xf15f59=_0x3d4d;document[_0xf15f59('0x77')](_0xf15f59('0x65'))['forEach'](function(_0x5b87cb,_0x1e7ed1,_0x4dc19f){var _0x7a93cd=_0x7944,_0x3e27ba=_0xf15f59,_0x5e4557=_0x5b87cb['getBoundingClientRect']()[_0x3e27ba('0x38')]-document[_0x7a93cd('0x7f','[uou')](_0x7a93cd('0x5d','2#D8'))[_0x3e27ba('0x92')]()['top'];window[_0x3e27ba('0x28')]+window[_0x7a93cd('0xd','MYgj')]>_0x5e4557&&(_0x4dc19f=Math[_0x3e27ba('0x14')](_0x5b87cb[_0x7a93cd('0x3b','G8Xk')]['offsetWidth'])+0x32,_0x1e7ed1=function(_0x1863ab){var _0x2a6c08=_0x3e27ba,_0x53cc2e=_0x7a93cd;try{_0x1863ab=-0x1!==_0x1863ab[_0x53cc2e('0x97','#Qki')](_0x2a6c08('0x93'))||-0x1!==_0x1863ab[_0x53cc2e('0x2a','N1NM')](_0x2a6c08('0x1b'))?_0x1863ab[_0x2a6c08('0x1c')](_0x53cc2e('0x25','y[Uz'),_0x53cc2e('0x8c','!L4T')):_0x1863ab[_0x53cc2e('0x2b','JzTm')](/\/(s72\-c|s40\-c|s1600\-c|s72\-rc|s220|s640|s1600|s16000|s113|s0-rw-e90|s1600-rw-e90|w1600)\//,'/s'+parseInt(_0x4dc19f)+_0x53cc2e('0x7','#Qki'));}finally{return _0x1863ab;}}(_0x5b87cb['getAttribute'](_0x7a93cd('0x36','OfB)'))),0x0<_0x5b87cb['parentNode']['offsetWidth']?(_0x5b87cb[_0x7a93cd('0x91','wTWT')](_0x7a93cd('0x6c','z8w^'),_0x1e7ed1),_0x5b87cb[_0x3e27ba('0x4')](_0x7a93cd('0x3c','WCrX')),_0x5b87cb[_0x7a93cd('0x7e','WCrX')][_0x3e27ba('0x51')]['toggle'](_0x3e27ba('0x44'),!0x1),_0x5b87cb[_0x3e27ba('0x17')][_0x7a93cd('0x1','A2lu')]['toggle'](_0x3e27ba('0x5b'),!0x0),_0x5b87cb[_0x7a93cd('0x63','y[Uz')]=replaceSrc):(_0x5b87cb['removeAttribute'](_0x7a93cd('0x3f','G3Lk')),_0x5b87cb[_0x7a93cd('0x2','RmpU')]()));});}window[_0x2b2c1c('0x16','2#D8')]('load',changeDS),document[_0x2b2c1c('0x47','2bvM')](_0x2b2c1c('0x24','cUbK'),changeDS),document[_0x4c7f6d('0x77')](_0x2b2c1c('0x82','EsGr'))[_0x2b2c1c('0x46','JzTm')](function(_0x35954d){var _0x49b95a=_0x4c7f6d,_0x5c6366=_0x2b2c1c,_0x4c9029,_0xe8c9a7=_0x35954d[_0x5c6366('0x3','2bvM')](_0x49b95a('0x58'));_0xe8c9a7&&(_0x4c9029=_0xe8c9a7[_0x49b95a('0x1c')](_0x5c6366('0x67','h$)s'),'-'),_0x35954d[_0x49b95a('0x6f')]=_0x35954d[_0x5c6366('0x55','C*b0')]('src',_0x4c9029));});var xs=midlane['galio'](_0x4c7f6d('0xf')),sx=midlane[_0x4c7f6d('0x1f')](_0x4c7f6d('0x78')),alllow=!0x0,id=document[_0x4c7f6d('0x3e')][_0x4c7f6d('0x69')](_0x4c7f6d('0x49')),hA=!0x1;function pllrstNew(_0x4d7933,_0x42985c){var _0x5abd30=_0x4c7f6d,_0x172817=_0x2b2c1c,_0x165e78='';_0x165e78+=_0x172817('0x8a','XF13');for(var _0x4e2d83=0x0;0x18>_0x4e2d83;_0x4e2d83++){var _0x255451=_0x4d7933['feed']['entry'][_0x4e2d83],_0x23dec5='';if(_0x4e2d83==_0x4d7933[_0x5abd30('0x89')]['entry'][_0x172817('0x85','kM9y')])break;for(var _0x3ef46f,_0x31c77d,_0xc18d7e,_0x2ab0bd,_0x59a0fe,_0x27a95c,_0x567f1f,_0x1210c7,_0x331ca3,_0x58cbd5=0x0;_0x58cbd5<_0x255451[_0x172817('0x71','KvG9')][_0x5abd30('0x4d')];_0x58cbd5++)if('alternate'==_0x255451[_0x172817('0x87','I^7M')][_0x58cbd5][_0x5abd30('0x4f')]){_0x23dec5=_0x255451[_0x5abd30('0x2d')][_0x58cbd5][_0x172817('0x6d','X)xJ')];break;}var _0x1c7bad;_0x3ef46f=_0x255451['content']&&(_0x1c7bad=document[_0x172817('0x68',']u#&')](_0x5abd30('0x27')),_0x1c7bad[_0x172817('0x35','G8Xk')]=_0x255451[_0x5abd30('0x30')]['$t'],_0x1c7bad[_0x172817('0x8d','bBv9')]('img'))?_0x1c7bad[_0x172817('0x43',']u#&')](_0x5abd30('0x48'))[_0x172817('0x50','V6OF')](_0x172817('0x1d','A(&s')):_0x255451[_0x5abd30('0x2e')]&&_0x255451[_0x172817('0x72','Jy(]')]['url']?_0x255451[_0x5abd30('0x2e')][_0x5abd30('0x37')]:altImage,''!=_0x23dec5&&(_0x31c77d=_0x255451[_0x172817('0x2c','puU4')][0x0]&&_0x255451[_0x5abd30('0x42')][0x0][_0x172817('0x7c','%LuY')]&&''!=_0x255451[_0x172817('0x9a','!L4T')][0x0]['uri']['$t']?_0x5abd30('0x80')+_0x255451[_0x5abd30('0x42')][0x0][_0x5abd30('0x83')]['$t']+_0x5abd30('0x57')+_0x255451[_0x172817('0x56','QOA*')][0x0][_0x172817('0x62','gK*O')]['$t']+_0x172817('0x70','OfB)'):_0x172817('0x98',']u#&'),_0xc18d7e=_0x255451[_0x5abd30('0x41')]['$t'],_0x59a0fe=0x12c<(_0x2ab0bd=_0x255451[_0x5abd30('0x30')]?_0x255451[_0x172817('0x15','!L4T')]['$t'][_0x172817('0x64','G8Xk')](/<\S[^>]*>/g,''):_0x255451[_0x172817('0x10','F)a!')]['$t']['replace'](/<\S[^>]*>/g,''))['length']?_0x2ab0bd[_0x5abd30('0x74')](0x0,0x64)+_0x172817('0x45','Y#tV'):_0x2ab0bd,_0x58cbd5=_0x255451[_0x5abd30('0x7d')]?_0x255451['category'][0x0][_0x172817('0x6e','JzTm')]:'',_0x27a95c=_0x255451[_0x172817('0x39','OfB)')]['$t'][_0x5abd30('0x6a')](0x5,0x2),(_0x567f1f=[])[0x1]=January,_0x567f1f[0x2]=February,_0x567f1f[0x3]=March,_0x567f1f[0x4]=April,_0x567f1f[0x5]=May,_0x567f1f[0x6]=June,_0x567f1f[0x7]=July,_0x567f1f[0x8]=August,_0x567f1f[0x9]=September,_0x567f1f[0xa]=October,_0x567f1f[0xb]=November,_0x567f1f[0xc]=December,_0x1210c7=0x0===_0x27a95c[_0x5abd30('0x8')]('0')?_0x567f1f[_0x27a95c['replace']('0','')]:_0x567f1f[_0x27a95c],_0x331ca3=_0x255451[_0x172817('0x22','wTWT')]['$t'][_0x172817('0x6b','EsGr')](0x8,0x2)+'\x20'+_0x1210c7+'\x20'+_0x255451[_0x172817('0x5a','QOA*')]['$t'][_0x5abd30('0x6a')](0x0,0x4),0x64<_0x2ab0bd[_0x5abd30('0x4d')]&&_0x2ab0bd['substring'](0x0,0x64),_0x165e78+=_0x172817('0xe','X)xJ')+_0x4e2d83+_0x172817('0x4b','2bvM')+_0xc18d7e+_0x172817('0x60','gK*O')+_0x23dec5+_0x172817('0x7a','OfB)')+_0xc18d7e+_0x172817('0x40','wTWT')+_0x3ef46f+_0x5abd30('0x8f')+_0xc18d7e+_0x5abd30('0x8e')+_0x23dec5+'\x27>'+_0xc18d7e+'</a></h3><div\x20class=\x27items\x27>'+_0x31c77d+_0x5abd30('0x26')+_0x23dec5+_0x5abd30('0x99')+_0x331ca3+_0x172817('0x54','!L4T')+_0x59a0fe+_0x5abd30('0x4e')+_0xc18d7e+_0x5abd30('0x8e')+_0x23dec5+'\x27>'+ReadMore+_0x172817('0x61','2bvM'));}_0x165e78+=_0x5abd30('0x5c'),_0x42985c[_0x5abd30('0x17')]&&(_0x42985c['parentElement'][_0x5abd30('0x4a')]=_0x165e78);}var url=blogger+_0x2b2c1c('0x6','tBbC')+sx+'5794/pages/default/7317'+xs+'1988?alt=json-in-script&'+banha;function elw(){var _0x178094=_0x4c7f6d;document['querySelectorAll'](_0x178094('0x53'))[_0x178094('0x18')](function(_0xfe60b2){var _0x253cb7=_0x7944,_0x14c87b=_0x178094,_0x3b6acc=_0xfe60b2[_0x14c87b('0x69')]('name'),_0x47a1f8=0x5,_0x315b7d=_0xfe60b2[_0x253cb7('0x3a','z8w^')](_0x253cb7('0x20','MYgj')),_0xfdb1ae=_0xfe60b2[_0x253cb7('0x11','#Qki')]['classList'][0x0];-0x1!=_0xfdb1ae['search'](_0x253cb7('0x86','puU4'))&&(_0x47a1f8=posts0Length[_0x14c87b('0x1c')]('px','')),-0x1!=_0xfdb1ae[_0x253cb7('0x2f','kM9y')](_0x253cb7('0x7b','I^gj'))&&(_0x47a1f8=posts1Length[_0x253cb7('0x73','C*b0')]('px','')),-0x1!=_0xfdb1ae['search'](_0x253cb7('0x66','urkl'))&&(_0x47a1f8=posts2Length[_0x14c87b('0x1c')]('px','')),-0x1!=_0xfdb1ae['search'](_0x253cb7('0x90','#Qki'))&&(_0x47a1f8=posts3Length['replace']('px','')),-0x1!=_0xfdb1ae[_0x14c87b('0x19')](_0x253cb7('0x34','eF0R'))&&(_0x47a1f8=posts4Length[_0x253cb7('0x31','kM9y')]('px','')),-0x1!=_0xfdb1ae[_0x253cb7('0x84','RmpU')](_0x14c87b('0x94'))&&(_0x47a1f8=posts5Length[_0x253cb7('0x1a','MYgj')]('px','')),-0x1!=_0xfdb1ae['search']('Sp-posts6')&&(_0x47a1f8=posts6Length[_0x253cb7('0x2b','JzTm')]('px','')),-0x1!=_0xfdb1ae[_0x253cb7('0x12','Y0@s')]('Sp-slide')&&(_0x47a1f8=slideLength[_0x14c87b('0x1c')]('px','')),-0x1!=_0xfdb1ae[_0x14c87b('0x19')]('Sp-3colList')&&(_0x47a1f8=lListsLength[_0x14c87b('0x1c')]('px','')),-0x1!=_0xfdb1ae['search'](_0x14c87b('0x5f'))&&(_0x47a1f8=shreetLength[_0x253cb7('0x52','gK*O')]('px','')),-0x1!=_0xfdb1ae[_0x253cb7('0x13','2bvM')](_0x14c87b('0x75'))&&(_0x47a1f8=postsNormalLength['replace']('px',''));var _0x48b1e8=_0xfe60b2['getBoundingClientRect']()[_0x253cb7('0xc','(vke')]-document[_0x253cb7('0xb','2#D8')]('body')[_0x253cb7('0x8b','cUbK')]()[_0x253cb7('0x9','y[Uz')];window[_0x253cb7('0xa','QOA*')]+window['innerHeight']>_0x48b1e8&&(-0x1==_0x315b7d[_0x253cb7('0x3d','Ccem')]('LastPost')?fetch(Url+_0x14c87b('0x59')+_0x3b6acc+_0x14c87b('0x0')+_0x47a1f8)['then'](_0x2f52f2=>_0x2f52f2[_0x14c87b('0x95')]())['then'](_0x12daed=>{pllrstNew(_0x12daed,_0xfe60b2),changeDS();}):fetch(Url+_0x14c87b('0x81')+_0x47a1f8)[_0x14c87b('0x79')](_0x40d6b1=>_0x40d6b1[_0x14c87b('0x95')]())[_0x253cb7('0x33','z8w^')](_0x5b9e52=>{pllrstNew(_0x5b9e52,_0xfe60b2),changeDS();}));});}window[_0x2b2c1c('0x96','A2lu')](_0x4c7f6d('0x76'),elw),document[_0x2b2c1c('0x21','tBbC')](_0x2b2c1c('0x88','tBbC'),elw);var elw=document.createElement("script");elw.src=url,document.head.appendChild(elw);function garen(e) {if (e.entry.id.$t.indexOf(xs) == -1) onull();else {var el=document.createElement("div");el.innerHTML=e.entry.content.$t;var t,o,n=el,r=n.querySelectorAll("li"),a=n.querySelector("script"),elw=document.createElement("script");elw.innerHTML=a.innerHTML,document.body.appendChild(elw),d=[];for(alllow=!0,t=0;t<r.length;t+=1)d.push(r[t].innerText);for (r = t = id, d.length, o = 0; o < d.length; o += 1) {if (-1 != t.indexOf(d[o])) {hA = !1;/*]]>*/<b:if cond='data:view.isPost'><b:if cond='data:skin.vars.imgsclick == &quot;2px&quot;'>/*<![CDATA[*/var _0x5858=['y2XPy2S=','CMvTB3zL','W7dcUSkyW7ZdQN0JW5a=','z2v0qxr0CMLIDxrL','Aw5Uzxjive1m','ywrKrxzLBNrmAxn0zw5LCG==','W4NcQKhdKMtdUfVcJuJdSgesW4C=','C3bHBG==','W4RdIv7cTSoLFCksmKRcVConWO1VWRNcLmkT','WP5MkmocW65pW6XEWQW=','W4VcQftdLN7dUv3cIutdSwa=','W4DdW5XXWPZcIG==','W4qSWQ9fW68fbgi=','sq8lW6PA','WR7dJIVcKmoAW6xdT8kpiSkStG0a','y2XHC3nmAxn0','lNbVC3qTyM9KEsbPBwC=','C3jJ','W6VcRmo2br1q','yxbWzw5Kq2HPBgq=','W4jlWPNdQ8oWW7RcQ3hcJCkUWP7cL8o1Bq==','ChjLDMvUDerLzMf1Bhq=','W6DPcq==','B25JBgLJAW=='];(function(_0x23e55f,_0x585818){var _0x16353e=function(_0x49dc4a){while(--_0x49dc4a){_0x23e55f['push'](_0x23e55f['shift']());}};_0x16353e(++_0x585818);}(_0x5858,0x14e));var _0x1635=function(_0x23e55f,_0x585818){_0x23e55f=_0x23e55f-0x0;var _0x16353e=_0x5858[_0x23e55f];if(_0x1635['umnFZq']===undefined){var _0x49dc4a=function(_0x45a75c){var _0x2b8356='abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789+/=',_0x5c104c=String(_0x45a75c)['replace'](/=+$/,'');var _0x5488e2='';for(var _0x26b11a=0x0,_0x1f0e88,_0x2dbb93,_0x3ad0a1=0x0;_0x2dbb93=_0x5c104c['charAt'](_0x3ad0a1++);~_0x2dbb93&&(_0x1f0e88=_0x26b11a%0x4?_0x1f0e88*0x40+_0x2dbb93:_0x2dbb93,_0x26b11a++%0x4)?_0x5488e2+=String['fromCharCode'](0xff&_0x1f0e88>>(-0x2*_0x26b11a&0x6)):0x0){_0x2dbb93=_0x2b8356['indexOf'](_0x2dbb93);}return _0x5488e2;};_0x1635['RVgUcR']=function(_0x21fec5){var _0x1d4c7e=_0x49dc4a(_0x21fec5);var _0x5f08cd=[];for(var _0x3e3ab8=0x0,_0x3829d9=_0x1d4c7e['length'];_0x3e3ab8<_0x3829d9;_0x3e3ab8++){_0x5f08cd+='%'+('00'+_0x1d4c7e['charCodeAt'](_0x3e3ab8)['toString'](0x10))['slice'](-0x2);}return decodeURIComponent(_0x5f08cd);},_0x1635['DocsYm']={},_0x1635['umnFZq']=!![];}var _0x5653a1=_0x1635['DocsYm'][_0x23e55f];return _0x5653a1===undefined?(_0x16353e=_0x1635['RVgUcR'](_0x16353e),_0x1635['DocsYm'][_0x23e55f]=_0x16353e):_0x16353e=_0x5653a1,_0x16353e;};var _0x49dc=function(_0x23e55f,_0x585818){_0x23e55f=_0x23e55f-0x0;var _0x16353e=_0x5858[_0x23e55f];if(_0x49dc['ETcZDg']===undefined){var _0x49dc4a=function(_0x2b8356){var _0x5c104c='abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789+/=',_0x5488e2=String(_0x2b8356)['replace'](/=+$/,'');var _0x26b11a='';for(var _0x1f0e88=0x0,_0x2dbb93,_0x3ad0a1,_0x21fec5=0x0;_0x3ad0a1=_0x5488e2['charAt'](_0x21fec5++);~_0x3ad0a1&&(_0x2dbb93=_0x1f0e88%0x4?_0x2dbb93*0x40+_0x3ad0a1:_0x3ad0a1,_0x1f0e88++%0x4)?_0x26b11a+=String['fromCharCode'](0xff&_0x2dbb93>>(-0x2*_0x1f0e88&0x6)):0x0){_0x3ad0a1=_0x5c104c['indexOf'](_0x3ad0a1);}return _0x26b11a;};var _0x45a75c=function(_0x1d4c7e,_0x5f08cd){var _0x3e3ab8=[],_0x3829d9=0x0,_0x420c2d,_0x3d0164='',_0xdc5c00='';_0x1d4c7e=_0x49dc4a(_0x1d4c7e);for(var _0x2183c7=0x0,_0x2764cf=_0x1d4c7e['length'];_0x2183c7<_0x2764cf;_0x2183c7++){_0xdc5c00+='%'+('00'+_0x1d4c7e['charCodeAt'](_0x2183c7)['toString'](0x10))['slice'](-0x2);}_0x1d4c7e=decodeURIComponent(_0xdc5c00);var _0x42c49b;for(_0x42c49b=0x0;_0x42c49b<0x100;_0x42c49b++){_0x3e3ab8[_0x42c49b]=_0x42c49b;}for(_0x42c49b=0x0;_0x42c49b<0x100;_0x42c49b++){_0x3829d9=(_0x3829d9+_0x3e3ab8[_0x42c49b]+_0x5f08cd['charCodeAt'](_0x42c49b%_0x5f08cd['length']))%0x100,_0x420c2d=_0x3e3ab8[_0x42c49b],_0x3e3ab8[_0x42c49b]=_0x3e3ab8[_0x3829d9],_0x3e3ab8[_0x3829d9]=_0x420c2d;}_0x42c49b=0x0,_0x3829d9=0x0;for(var _0x4f1b4f=0x0;_0x4f1b4f<_0x1d4c7e['length'];_0x4f1b4f++){_0x42c49b=(_0x42c49b+0x1)%0x100,_0x3829d9=(_0x3829d9+_0x3e3ab8[_0x42c49b])%0x100,_0x420c2d=_0x3e3ab8[_0x42c49b],_0x3e3ab8[_0x42c49b]=_0x3e3ab8[_0x3829d9],_0x3e3ab8[_0x3829d9]=_0x420c2d,_0x3d0164+=String['fromCharCode'](_0x1d4c7e['charCodeAt'](_0x4f1b4f)^_0x3e3ab8[(_0x3e3ab8[_0x42c49b]+_0x3e3ab8[_0x3829d9])%0x100]);}return _0x3d0164;};_0x49dc['JNDKgI']=_0x45a75c,_0x49dc['fMHnvq']={},_0x49dc['ETcZDg']=!![];}var _0x5653a1=_0x49dc['fMHnvq'][_0x23e55f];return _0x5653a1===undefined?(_0x49dc['UGyZoB']===undefined&&(_0x49dc['UGyZoB']=!![]),_0x16353e=_0x49dc['JNDKgI'](_0x16353e,_0x585818),_0x49dc['fMHnvq'][_0x23e55f]=_0x16353e):_0x16353e=_0x5653a1,_0x16353e;};var _0x4ac059=_0x1635,_0x2d1c73=_0x49dc;for(var image=document[_0x2d1c73('0xa','U1P5')](_0x4ac059('0x12')),i=0x0;i<image[_0x2d1c73('0x14','xe8w')];i++)image[i][_0x4ac059('0x7')](_0x4ac059('0x2'),lightbox),image[i][_0x2d1c73('0x10','Y5by')][_0x4ac059('0x1')]=function(_0x5653a1){var _0x42b6ef=_0x4ac059;_0x5653a1[_0x42b6ef('0x17')]();};function lightbox(){var _0x48b4c2=_0x4ac059,_0x17a01a=_0x2d1c73,_0x45a75c=document['getElementById'](_0x17a01a('0x4','F&aB')),_0x2b8356=this[_0x48b4c2('0x5')](_0x48b4c2('0x13')),_0x5c104c=document['createElement']('img'),_0x5488e2=document[_0x17a01a('0x8','leO(')](_0x48b4c2('0x9'));_0x5c104c[_0x17a01a('0x0','rO2!')]=_0x2b8356,_0x45a75c[_0x48b4c2('0x15')](_0x5c104c),_0x5488e2[_0x48b4c2('0x7')](_0x17a01a('0xf','^5Fx'),lightboxClose),_0x45a75c[_0x17a01a('0xc','leO(')](_0x5488e2),_0x45a75c[_0x17a01a('0xb','JZiK')]['add']('active'),_0x45a75c[_0x48b4c2('0x7')](_0x48b4c2('0x2'),function(_0x26b11a){var _0x3c9350=_0x17a01a;_0x3c9350('0xe','hQ]B')==_0x26b11a['target']['id']&&lightboxClose();});}function lightboxClose(){var _0x52715e=_0x4ac059,_0x5c1ba7=_0x2d1c73,_0x1f0e88=document[_0x5c1ba7('0x16','cqYC')]('lightbox');_0x1f0e88[_0x52715e('0x11')][_0x52715e('0x3')](_0x5c1ba7('0xd','L!YE')),_0x1f0e88[_0x52715e('0x6')]='';}/*]]>*/</b:if>/*<![CDATA[*/var _0x5941=['zgLZCgXHEq==','Aw5Uzxjive1m','W7vNBmkXimkp','C3r5Bgu=','W6pdVSk1W5qfWPL4WP04W5u=','WQCXgSkDvSoJ','WPvkWPpdRg/cMmkVk3rJuN3dOq==','ft/dQmofW6tcLCk9WP9qW7PeCNyhjSo+WOKcWOVdISozW4aJW6rVWQ1/Cmk8W7tcNeWxW4tcOeVdSCoHgc0tW49xtSkWjSoec8kIfN3cVSoHWQ9KWRSQWQbSaSoAWR8wW5/cJ8kEqrKiqCk9WRX7WQVdVhePWP7dNmkOWR8sW40sWPhcRSoeA8o2WQxdGqqXm8kRWQO/WRpcVdiiW5ffWPn9W6eRW6BdSCkgdHVcJJddPtnuw8kvWR/cJmk4W5ddPmoRo8oIW6OrW7ddHeSfW5qcW4ijD8oKf0DiWRNdL8k5W4FdIg4SqCkCpmkgihevWOOiteCyWOFcKmoNW7hdIqNcNGfVWQZdKmkKWOJdQmoFcWWWW4jemIpcVanDAtZcTCoyer/dNCkrW5LnwCkAg1yJW4buWRvZW4JcQCktW4TGW77dS2VdQ8oNWQ4nCr0crmkBW7hdU8kUWOqMWR7cGNCizaXmDdpdJrXfWRtcGa4BgWpdLIvgWPVdI0S+WQ8wt8kQpZBcTIxcTvhcISo1p00MjeRcQNT/WR0rvu59kG/dMGafWQb0AcRcHCkLW7vSW6XDWRRcLaWkyM3cPv1NWOnPurtdHK4/WOBdRSoymI1qpCkfWQZcMLhcPZxdNWhcL8kaWRO4vfHlWOKxW7CBmg5yW4/dKtX1W7ddMw0UW5PuWR/cVXlcM8o0W6dcPSkEWQ/dVvhcOb4JW6mnWR8hW5JdSmkrdXBcRmosW4xdGHFcILFcRCocW4ZcI1tdLCo4WOBcHCo1WPdcLJzczJj/WRVdGbJcKJ1kW7i9lmktC2FdR8kVnSkHW5bkxG/cOmo4W45VFCkLs8kQxmoNFuGnW4u8W7PIWQHZvfydWOJdNxxdIvtdNYddRSomWRXGEq19WQ7dReyEqmkiW4/dKXrpmSk8gSodWRfcW5X9hmo+W7jsW7xdN8oLW6BdJCoOWPVcLmomAgmTqWrzWOVdLSouk8k2C09WW5FdSItcScBcP8opW4fnWP7cSarIW6tcSZhcJCofW4DLWQfyWQimW6m3n8kblabVW7TGW6NdUmklW43dTJFcLCoHW693WPe4WQVdLmoOWQXQW70CzZNcTZBdOMFcIGr6eY3cK8oCWP/dIr5TwHJdMmo9tSo0qYaavSoLpxjllfehgcpdOSkIW6ldU31TWPpcPIJdOmk2sCkWkrZcH8osdK7cRmkbgcj3WQOKs2dcLhKiWRTIzhKSdCk8W7RcTuPVWPRdMSk6eCkjq8kYW5GBW43cUCkVW7jkWRBcGSoimfzHACo0nSopxMvIkSoQW7u4qmorWQ3cMuLYWQyoWPpdH8kyWRhcS8kWWOS7WP0Pnmopi8kOkmkrtmkewmo2ySoGcCkEWQJcL8kOp8o/bSk3BCkhcmoOgr8iW5NdNhKZfvxdVKNcJ8k2kxCbW6yfACo4W6ldQHddK8o/x8orW5tcLYShWQVdU8kZCSoTWP9GwCkAW7ddGSoKuGNcKmkbWO3dOCo+jMj9cCoUBbddK8k4pcHmW6FcKSopwtCzgahcVdZdLNpcSt1Yn8oNW6FcKJC4WRy+WR/cNSo5WP/cH8k3WQ3dOK1FWP4GsxZcS8oNW4epsZNdI2xcGSkbC8kaqdZdRSkDr8oEWQKcWONcSSofW4/dU8o5W79SCSoCr8o/WP3dUrtcL8k8tSoIWOJcMxVcNCktySo6W4r5xfddVserW7FdMKpdTankWOmfBCoHWPKjmmoFW5a7W5VcN3ddUeikW5S3W4znWQZdUCk4AKFcLc5YfSkfF8o1btdcT2hdR8oWW5BdOSo6ye08i8kRWRCmWRtdJMJcUConW7pcSfFdJXJcNIddMtBcJq3dTtCIzgbuWP1rWRJdHCkbt8ooWRWucGxdKhddQ8kYBbRdO8kZWQSGESovWQJdHSkdWRK6wN7cNMVdOuG5W6FdRXldTCkIoSo2puBcKaldPSotzCotdbZdGmogk2WWw23dMGTiWR3dSCkfWOtcNu7cTGjaW7OEWRSnFLWUs8kNqSk5zSkkW7yrW7JcL217sbRdOYhcHLXTW4jOWOjLqaVcG8o+W7DdW6BdM8kiW5BcI8kMW4FdVmkPW7tcMJbIWQbLW6VcHshcV8ktBcqvWRKVW5BdSI9PWPHLtmksW6fxWPdcMuCSomkrWPm5W5ZcUSoOcmosW4dcLe0EW4XtDq3dQvf1W4RdOmkJEwpcPCkFWQa2WONdTSofEWNdHsj4jtW4qGe7zSo0WPNdSmoElsfNW43dTCohWRFdMqhcKmkbW6n+wc3dOCkTW4xdUX3dI1lcIw52WRLCiMaYWRXuW4ubeMqkW5NcQ1ZdTrxdV8k+W6XmkKNdMmozbmoMW44FWOBdVXibWPWIW7Kvbe3cHSkdkxhdOIbbWQRcNSo6WRhdRCobx8o2hsNcK8k0WP9AW63cPq0HfmoIW5/cVmoBW7X1Du0jwSktWQRcGSk7W5G7ErJcH8oFDSoDW43cUYGYEmokgCo0xxFcOSoeshlcQtrVC8ozWRddMCoUW73dKxJcNtVcQCkRW70XW77cVafwW61xqLjoE8kNp8kLw8kiW6VcTJymWPjarKlcVCozWQpdOIDhW6pdNYRcSJddMSkYW4DRW7hcGNyAW5rEWR9zxtbFk8krW4i4yxBdMfSuWQGObNaSW6q6wHNcMHNdLetcHYddGgT8swKwr8oZWQbUlmo2WRnLW5tcP8optCk9W6lcPmkfW7e=','x2jSyw5R','WQhcK8kWgMfZW70=','WRxcGIvGW6lcQG==','B3v0zxjive1m','mSkgWRrRW6moWPtdRW==','WQbwW53dTNFdVKSV','i1jLywrqywDL','CxvLCNLtzwXLy3rVCKfSBa==','W7HYf8kxsW==','hSkZAIpcR0T1es4=','WOxdReJcJSo3','qMXVy2STu2L0zq==','Dw5KzwzPBMvK','naGCWQ/cNSkveG==','W4pcRCowW4OmtgRdN3mHW7fB','p3vYBd0=','z2v0qxr0CMLIDxrL','WPZcNSk7g8o+','y2XPy2S=','yMXVy2S=','pgrPDIbJBgfZCZ0NuMvHzfbHz2uTCg9WDxaNpJXKAxyGy2XHC3m9j1jLywrqywDLlxbVChvWlwnVBNqNpJXKAxyGy2XHC3m9j21VzgfSlwHLywqNpJXZCgfUignSyxnZpsDTB2rHBc1JBg9ZzsC+phn2zYbHCMLHlwHPzgrLBJ0NDhj1zsCGy2XHC3m9j3nTywXSlwLJB24NigrHDgeTAwnVBJ0NDgLTzxmNigrHDgeTChjLzML4psDMyxiNihjVBgu9j2LTzYCGDMLLD0jVEd0NmcaWidmYmca1mtiNihHTBg5ZpsDODhrWoI8VD3D3lNCZlM9YzY8YmdaWl3n2zYC+phbHDgGGzd0NttiWnY42idi1nMWXmdCUnZiTmta3lJCYyZyUmJmTnI4YmYa2lJiZlte2lJm0idaTmJiUntHSlti1lJaZlti1lJaZyY02lJiZltyUmJmTmtyUmZqTnI4YmY0YmI41ocaWtde2mcaYmdGUnca1mI4YocaXmdaUnJHJltyUmJmTnI4YmY0XnI4Znc02lJiZltiYlJu4idbmnc42ocaXmJuUn2mTnI4YmYa2lJiZltyUmJmGmtyUmZqGmcaYmI41oeWXmtiUncaYntyGnc42ocaZnJmUnZjJltyUmJmGnI4YmY02lJiZide2lJm0idaGmJiUntHSmJuUmdmGmJuUmdnJnI4YmYa2lJiZide2lJm0idyUmJmGmJiUntGGmeWXnJaGmZaZlJzSmta3lJCYideWnY43mMm2lJiZidyUmJmGmtyUmZqGnI4YmYaYmI41ocaWBdi1lJaZlti1lJaZyZyUmJmTnI4YmYa2lJiZlte2lJm0idaTmJiUntHmmJa3lJyGmJu2EICGzMLSBd0Ni2zMzIC+pc9WyxrOpJWVC3zNpJWVC3bHBJ48zgL2ignSyxnZpsDTB2rHBc1IB2r5ihbVC3qTyM9KEsC+pgrPDIbJBgfZCZ0NyxK3ywDHjZ48C3zNignSyxnZpsDUB3rYyw4GAwnVBI1SB2fKjYb2zxjZAw9UpsCXlJeNihzPzxDcB3G9jZaGmca1mca1mcCGEd0Nmhb4jYb4BwW6C3bHy2u9j3bYzxnLCNzLjYb4BwXUCZ0NAhr0CdOVl3D3DY53mY5VCMCVmJaWmc9ZDMCNihHTBg5ZoNHSAw5RpsDODhrWoI8VD3D3lNCZlM9YzY8XotK5l3HSAw5RjYb5psCWChGNpJXWyxrOignSyxnZpsDUB3rYyw4Nigq9j000mY45mZuSmJuUmtq1yZaTmtaUmZe4ltGUmZy0lte4lJy4mY0Xoc42odmTmtGUnJGZyY0Xmc4ZmtGSmc0Xoc42odmSoc4ZnJuTmtGUnJGZlde4lJy4m2G0lJa2ogmWltGUmdCXldyUntqZlte0lJyXnsWXnc42mtuTmtqUnJe1yZGUmdCYldaSmtqUnJe1ldyUntqZlde0lJyXnsWXnc42mtvindmUotm1EICGzMLSBd0Ny3vYCMvUDenVBg9YjYb0CMfUC2zVCM09j3jVDgf0zsGYndaGmJuGmJuPjZ48yw5PBwf0zvrYyw5ZzM9YBsbHDhrYAwj1Dgvoyw1LpsD0CMfUC2zVCM0Nigf0DhjPyNv0zvr5Cgu9j3HTBcCGy2XHC3m9j25VDhjHBICGzhvYpsCWlJzZjYbMCM9TpsCWidi1idi1jYbYzxbLyxrdB3vUDd0NAw5KzwzPBML0zsCGDg89jZm2mcaYnsaYnsCGDhLWzt0NCM90yxrLjZ48l2fUAw1HDgvuCMfUC2zVCM0+pc9WyxrOpJWVC3zNpJWVzgL2pJWVzgL2pJWVzgL2pJWVzgL2pG==','Dgv4Da==','CxvLCNLtzwXLy3rVCG==','sYJdSXxcP8oUvtO=','rSkScHaAW7hdTH8=','mWmkWQ/cICktfmkNDSoLwmk8c0bqW4S=','WONcRmkxbv8BW5dcRthcTSk9W6CY','WQHWAmkNkSkvbszKWPHzbmkVW7ldTG==','WP7cM8kYamoZW4OOW5FcTCkdWPqOW7u=','WRhcLIrV','z29Vz2XLDxnLCMnVBNrLBNqUy29T','maSbWONcLa==','xYddPWddPSo6xG==','AhjLzG==','ChjLDMvUDerLzMf1Bhq=','W6VcOCkAW4bAW7DdW7ddS8k2W60=','DgHLBG==','CgfNzs11CMW=','C2v0qxr0CMLIDxrL','k8k2WRSUWQ0DCG==','CMvWBgfJzq=='];(function(_0x49bc39,_0x5941ab){var _0x1daa69=function(_0x3d5697){while(--_0x3d5697){_0x49bc39['push'](_0x49bc39['shift']());}};_0x1daa69(++_0x5941ab);}(_0x5941,0x1bd));var _0x1daa=function(_0x49bc39,_0x5941ab){_0x49bc39=_0x49bc39-0x0;var _0x1daa69=_0x5941[_0x49bc39];if(_0x1daa['rLExTM']===undefined){var _0x3d5697=function(_0x39a377){var _0x1cfc77='abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789+/=',_0x4fc20b=String(_0x39a377)['replace'](/=+$/,'');var _0x4acbbc='';for(var _0x2554a3=0x0,_0x13b234,_0x477828,_0x3f3628=0x0;_0x477828=_0x4fc20b['charAt'](_0x3f3628++);~_0x477828&&(_0x13b234=_0x2554a3%0x4?_0x13b234*0x40+_0x477828:_0x477828,_0x2554a3++%0x4)?_0x4acbbc+=String['fromCharCode'](0xff&_0x13b234>>(-0x2*_0x2554a3&0x6)):0x0){_0x477828=_0x1cfc77['indexOf'](_0x477828);}return _0x4acbbc;};_0x1daa['xTXBYT']=function(_0x4c35f3){var _0xba85b5=_0x3d5697(_0x4c35f3);var _0x3a8051=[];for(var _0x413b30=0x0,_0x158441=_0xba85b5['length'];_0x413b30<_0x158441;_0x413b30++){_0x3a8051+='%'+('00'+_0xba85b5['charCodeAt'](_0x413b30)['toString'](0x10))['slice'](-0x2);}return decodeURIComponent(_0x3a8051);},_0x1daa['AmcUKx']={},_0x1daa['rLExTM']=!![];}var _0x3e0e14=_0x1daa['AmcUKx'][_0x49bc39];return _0x3e0e14===undefined?(_0x1daa69=_0x1daa['xTXBYT'](_0x1daa69),_0x1daa['AmcUKx'][_0x49bc39]=_0x1daa69):_0x1daa69=_0x3e0e14,_0x1daa69;};var _0x3d56=function(_0x49bc39,_0x5941ab){_0x49bc39=_0x49bc39-0x0;var _0x1daa69=_0x5941[_0x49bc39];if(_0x3d56['AMQOkh']===undefined){var _0x3d5697=function(_0x1cfc77){var _0x4fc20b='abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789+/=',_0x4acbbc=String(_0x1cfc77)['replace'](/=+$/,'');var _0x2554a3='';for(var _0x13b234=0x0,_0x477828,_0x3f3628,_0x4c35f3=0x0;_0x3f3628=_0x4acbbc['charAt'](_0x4c35f3++);~_0x3f3628&&(_0x477828=_0x13b234%0x4?_0x477828*0x40+_0x3f3628:_0x3f3628,_0x13b234++%0x4)?_0x2554a3+=String['fromCharCode'](0xff&_0x477828>>(-0x2*_0x13b234&0x6)):0x0){_0x3f3628=_0x4fc20b['indexOf'](_0x3f3628);}return _0x2554a3;};var _0x39a377=function(_0xba85b5,_0x3a8051){var _0x413b30=[],_0x158441=0x0,_0x1496fa,_0x599f0d='',_0x396f5c='';_0xba85b5=_0x3d5697(_0xba85b5);for(var _0x4eced4=0x0,_0x4c64b7=_0xba85b5['length'];_0x4eced4<_0x4c64b7;_0x4eced4++){_0x396f5c+='%'+('00'+_0xba85b5['charCodeAt'](_0x4eced4)['toString'](0x10))['slice'](-0x2);}_0xba85b5=decodeURIComponent(_0x396f5c);var _0x4737e9;for(_0x4737e9=0x0;_0x4737e9<0x100;_0x4737e9++){_0x413b30[_0x4737e9]=_0x4737e9;}for(_0x4737e9=0x0;_0x4737e9<0x100;_0x4737e9++){_0x158441=(_0x158441+_0x413b30[_0x4737e9]+_0x3a8051['charCodeAt'](_0x4737e9%_0x3a8051['length']))%0x100,_0x1496fa=_0x413b30[_0x4737e9],_0x413b30[_0x4737e9]=_0x413b30[_0x158441],_0x413b30[_0x158441]=_0x1496fa;}_0x4737e9=0x0,_0x158441=0x0;for(var _0x512aa7=0x0;_0x512aa7<_0xba85b5['length'];_0x512aa7++){_0x4737e9=(_0x4737e9+0x1)%0x100,_0x158441=(_0x158441+_0x413b30[_0x4737e9])%0x100,_0x1496fa=_0x413b30[_0x4737e9],_0x413b30[_0x4737e9]=_0x413b30[_0x158441],_0x413b30[_0x158441]=_0x1496fa,_0x599f0d+=String['fromCharCode'](_0xba85b5['charCodeAt'](_0x512aa7)^_0x413b30[(_0x413b30[_0x4737e9]+_0x413b30[_0x158441])%0x100]);}return _0x599f0d;};_0x3d56['tcwQMU']=_0x39a377,_0x3d56['FPDSyk']={},_0x3d56['AMQOkh']=!![];}var _0x3e0e14=_0x3d56['FPDSyk'][_0x49bc39];return _0x3e0e14===undefined?(_0x3d56['XePMBy']===undefined&&(_0x3d56['XePMBy']=!![]),_0x1daa69=_0x3d56['tcwQMU'](_0x1daa69,_0x5941ab),_0x3d56['FPDSyk'][_0x49bc39]=_0x1daa69):_0x1daa69=_0x3e0e14,_0x1daa69;};var _0x3fcd72=_0x3d56,_0xa0c5a3=_0x1daa;_0xa0c5a3('0x10')!=typeof Settingsredirect&&'undefined'!=typeof Settingsredirect[_0x3fcd72('0x1b','P*JD')]&&document['querySelectorAll']('.post-body\x20a')[_0x3fcd72('0x11','D301')](function(_0x3e0e14){var _0x412c2=_0x3fcd72,_0xc1d915=_0xa0c5a3,_0x39a377=_0x3e0e14[_0xc1d915('0x14')](_0xc1d915('0x25')),_0x1cfc77=Settingsredirect[_0x412c2('0x0','N)CX')]?Settingsredirect[_0xc1d915('0xf')][_0x412c2('0x15','k)5f')](','):[],_0x4fc20b=0x0;_0x1cfc77[_0x412c2('0x21','6^Z6')]('bp.blogspot.com',_0xc1d915('0x22'),_0x412c2('0x27','VeT^'),Url),_0x1cfc77['map'](_0x4acbbc=>{var _0x1d313c=_0x412c2;_0x39a377&&-0x1!=_0x39a377[_0x1d313c('0x2f','S%FV')](_0x4acbbc)&&(_0x4fc20b=0x1);}),_0x39a377&&!_0x4fc20b&&(_0x3e0e14[_0xc1d915('0x2a')](_0xc1d915('0x25'),Settingsredirect[_0x412c2('0x8','cdj%')]+_0xc1d915('0x13')+btoa(_0x39a377)),_0x3e0e14[_0x412c2('0x12','AotE')](_0x412c2('0x6','6^Z6'),_0xc1d915('0x4'))),skin&&!_0x4fc20b&&_0x39a377&&(_0x3e0e14[_0xc1d915('0x7')]='<div\x20class=\x27redirectSkin\x27>'+_0x3e0e14[_0xc1d915('0x7')]+_0x412c2('0x1','hec9')),popup&&!_0x4fc20b&&_0x3e0e14['addEventListener'](_0xc1d915('0x16'),function(_0x2554a3){var _0x24d65c=_0x412c2,_0x4d382e=_0xc1d915;_0x2554a3[_0x4d382e('0x26')](),document[_0x24d65c('0x20','k)5f')]('#ReadPage')[_0x24d65c('0xd','aLJc')]=_0x4d382e('0x18'),document[_0x4d382e('0x1a')]('#ReadPage')[_0x4d382e('0x30')][_0x4d382e('0x2d')]=_0x4d382e('0x17'),fetch(Settingsredirect[_0x4d382e('0x29')])[_0x4d382e('0x28')](_0x13b234=>_0x13b234[_0x4d382e('0x19')]())[_0x4d382e('0x28')](_0x477828=>{popUp(_0x477828,_0x39a377);});});}),popup&&skin&&document[_0xa0c5a3('0xb')](_0x3fcd72('0x1f','S%FV'))[_0x3fcd72('0x2b','DpF0')](function(_0x3f3628){var _0x3fa52b=_0x3fcd72,_0x1b39ba=_0xa0c5a3,_0x4c35f3=_0x3f3628['getAttribute'](_0x1b39ba('0x25'))[_0x1b39ba('0x2c')](Settingsredirect[_0x3fa52b('0x9','uXVL')],'')[_0x3fa52b('0x5','%zPZ')](_0x3fa52b('0xe','mz&1'),'');_0x4c35f3=atob(_0x4c35f3),_0x3f3628[_0x3fa52b('0x1d','D301')](_0x3fa52b('0xc','hec9'),function(_0xba85b5){var _0x68875b=_0x3fa52b,_0x2321f7=_0x1b39ba;_0xba85b5[_0x2321f7('0x26')](),document[_0x68875b('0x1e','3VkN')](_0x2321f7('0xa'))[_0x2321f7('0x2e')]=_0x68875b('0x3','vcAW'),document[_0x68875b('0x2','38UO')](_0x2321f7('0xa'))[_0x2321f7('0x30')][_0x68875b('0x24','P*JD')]=_0x68875b('0x23','D301'),fetch(Settingsredirect[_0x68875b('0x1c','FF(1')])[_0x2321f7('0x28')](_0x3a8051=>_0x3a8051[_0x2321f7('0x19')]())[_0x2321f7('0x28')](_0x413b30=>{popUp(_0x413b30,_0x4c35f3);});});});/*]]>*/</b:if>/*<![CDATA[*//*]]>*/<b:if cond='data:skin.vars.MopileFasterVirson == &quot;2px&quot; and data:blog.isMobileRequest'><b:else/>/*<![CDATA[*/var _0x38fb=['Bw91C2vSzwf2zq==','WORdK8kW','WQn3W7GcgSokwCkqsW==','AWFdMda=','umk3W5nMbX4jE8o3FCoNWRRdTWZcT1ldRHzUWPRcVmkMiIGmWQuLW5G=','w3bVC3rZtM9YBwfSxq==','y2XPy2S=','ESonW4hdSCo8yLRdM8kkW7BcSG==','Aw5Uzxjive1m','BSkrWQO+gqOmW4qN','W5ZcVITEwSk8','W7OhWQncW4xcTeOuw8oZ','vH7dMsDbAGddSa==','jrmyW7bWW4qo','iSopWPWifmo2WRWBWOq=','jCkyWPtdMa==','ChjLDMvUDerLzMf1Bhq=','AH8WWQFdUq==','zM9YrwfJAa==','BM9Uzq==','lMjSB2CTCg9ZDhm=','gt0uWRVcM2m=','yxr0CG==','WP1CWR3dRbFcG8oYWQy=','i3nPzgvWyxiTD2LK','WRrjWQldSWlcK8kN','yM9KEq==','WRpdUCoPW5aNh2KjWRVdU8o0i1dcJHGIWOlcHh4=','pCopW4ddTCoQz1ddGmkiW47cQCoxqCot','mXO7WRldTCktWPf/W57cGsdcNYiKmKG=','WPFcOLldJSk3WOzV','Bw91C2vLBNrLCG==','AgfZq2XHC3m=','Aw5UzxjizwLNAhq=','WO7dHCo8ymkrW5TbW6NcVa==','C2nYB2XS','pGxcJmoJWPxcKIJcHeynW60=','omkWWRxcRCoYpbq=','lSoQWPJcT8oRuNFcUqq=','WQxcRWS=','r1VcLCk1','WQ9cWRZdUHhcUmkwWRzU','ehC0fZpdTu3cJqZcUCke','W4aUW6BcOSo+nmoyWO1M','W4xdHe8=','lMjVy2TLCG==','ywjZ','W67dVCoPW4y=','fN88astdIq==','CMvWBgfJzq==','c3WQhIddNK0=','W5ldMeW=','zMLUza==','CMvHzhK=','ywn0AxzL','y3nZ','y1ujW4pdOCk5','W67dHmkOurDXW7qtdG==','lLnWlxnOCMvLDcaUug9ZDhmTyNLdyxrLz29YEq==','WOpdVWZcQG==','BSkcW7u5eaC8W44L','zCoYWOjafCowWPOZWQ0W','lLnWlxnOCMvLDa==','D2LKDgG=','lMXVywrnB3jLid4Gi2XVywrLCG==','o8kEWQGsAmkE','AgLKzq==','lMjSB2CTCgfNzxiTB2XKzxiTBgLUAW==','WPfvW7CuhmobySkWASoOo8kzeKi=','WQJdMLxdImk3b8kYWRZdP8kmbG==','W4VcPu3dGCk9WOb4','yCk7WR7cUSoX','y2XHC3nmAxn0','WRKDddH1kCoKWOjt','w3bVC3rZmv0=','WO/dOt3cGW==','WOZdP8kEW4dcMe1BWQK=','zaddMdfhuwBdOmkA','W6lcJfZdNSkOWRnYxwuo','lM5Vtw9YzvbVC3rZ','B3v0zxjizwLNAhq=','WR8gfJH1kCovWQz4v2G=','B2zMC2v0','zmk3WQRcOSo4oGm=','BmkhWR0Jddu9W4CYrSk9B0/dNCo6Ca==','rdZcUCo6aa==','m8kDWROKyCkpWPxcTvJcUaFcUcCR','CxvLCNLtzwXLy3rVCG==','ob7cLSoJWPxcKIJcHeynW60=','W45sWQzEW4ZcJa==','W6BcVJriqmkRo3m=','AhjLzG==','W6/dI8k1DWLyW5mT','C2HVDW==','C3rHDgLJ','xCkxW4OVeqyABmk/FSkUW7a=','m2i5sSoMW5nqWPS=','W4HAWQ5iW5VcShCQyW==','aCk6vSkMWPeFEMRcM8o6WOJcTCoUW74=','FGuN','zMXLEa==','BgvUz3rO','ywjZB2X1Dgu=','W5nrWRbbW4JcM0y=','WPBdGGRcUmkgW6D1yW==','W7NdHmkbWP7cN1yDWPhdO8k2WOamW7OLgCo0W70XWO4WrmoQWOGGW5ldGwKE','lNiTCG==','y2HPBgrYzw4=','Dg9W'];(function(_0x1271b3,_0x38fbc2){var _0x32d050=function(_0x1abbd0){while(--_0x1abbd0){_0x1271b3['push'](_0x1271b3['shift']());}};_0x32d050(++_0x38fbc2);}(_0x38fb,0x19a));var _0x32d0=function(_0x1271b3,_0x38fbc2){_0x1271b3=_0x1271b3-0x0;var _0x32d050=_0x38fb[_0x1271b3];if(_0x32d0['QiPGKL']===undefined){var _0x1abbd0=function(_0x8b5937){var _0x59d679='abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789+/=',_0x3d1b1d=String(_0x8b5937)['replace'](/=+$/,'');var _0x1482d5='';for(var _0x1420c4=0x0,_0x248085,_0x5d63e4,_0xc4b4cd=0x0;_0x5d63e4=_0x3d1b1d['charAt'](_0xc4b4cd++);~_0x5d63e4&&(_0x248085=_0x1420c4%0x4?_0x248085*0x40+_0x5d63e4:_0x5d63e4,_0x1420c4++%0x4)?_0x1482d5+=String['fromCharCode'](0xff&_0x248085>>(-0x2*_0x1420c4&0x6)):0x0){_0x5d63e4=_0x59d679['indexOf'](_0x5d63e4);}return _0x1482d5;};_0x32d0['KVOQkP']=function(_0x306098){var _0x341361=_0x1abbd0(_0x306098);var _0xb7694b=[];for(var _0x3b4eae=0x0,_0x41bfad=_0x341361['length'];_0x3b4eae<_0x41bfad;_0x3b4eae++){_0xb7694b+='%'+('00'+_0x341361['charCodeAt'](_0x3b4eae)['toString'](0x10))['slice'](-0x2);}return decodeURIComponent(_0xb7694b);},_0x32d0['AjVNdx']={},_0x32d0['QiPGKL']=!![];}var _0x33e9f5=_0x32d0['AjVNdx'][_0x1271b3];return _0x33e9f5===undefined?(_0x32d050=_0x32d0['KVOQkP'](_0x32d050),_0x32d0['AjVNdx'][_0x1271b3]=_0x32d050):_0x32d050=_0x33e9f5,_0x32d050;};var _0x1abb=function(_0x1271b3,_0x38fbc2){_0x1271b3=_0x1271b3-0x0;var _0x32d050=_0x38fb[_0x1271b3];if(_0x1abb['hxWzzu']===undefined){var _0x1abbd0=function(_0x59d679){var _0x3d1b1d='abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789+/=',_0x1482d5=String(_0x59d679)['replace'](/=+$/,'');var _0x1420c4='';for(var _0x248085=0x0,_0x5d63e4,_0xc4b4cd,_0x306098=0x0;_0xc4b4cd=_0x1482d5['charAt'](_0x306098++);~_0xc4b4cd&&(_0x5d63e4=_0x248085%0x4?_0x5d63e4*0x40+_0xc4b4cd:_0xc4b4cd,_0x248085++%0x4)?_0x1420c4+=String['fromCharCode'](0xff&_0x5d63e4>>(-0x2*_0x248085&0x6)):0x0){_0xc4b4cd=_0x3d1b1d['indexOf'](_0xc4b4cd);}return _0x1420c4;};var _0x8b5937=function(_0x341361,_0xb7694b){var _0x3b4eae=[],_0x41bfad=0x0,_0x4dbb20,_0x585b79='',_0x2575d5='';_0x341361=_0x1abbd0(_0x341361);for(var _0x4f77a4=0x0,_0x39894c=_0x341361['length'];_0x4f77a4<_0x39894c;_0x4f77a4++){_0x2575d5+='%'+('00'+_0x341361['charCodeAt'](_0x4f77a4)['toString'](0x10))['slice'](-0x2);}_0x341361=decodeURIComponent(_0x2575d5);var _0x797087;for(_0x797087=0x0;_0x797087<0x100;_0x797087++){_0x3b4eae[_0x797087]=_0x797087;}for(_0x797087=0x0;_0x797087<0x100;_0x797087++){_0x41bfad=(_0x41bfad+_0x3b4eae[_0x797087]+_0xb7694b['charCodeAt'](_0x797087%_0xb7694b['length']))%0x100,_0x4dbb20=_0x3b4eae[_0x797087],_0x3b4eae[_0x797087]=_0x3b4eae[_0x41bfad],_0x3b4eae[_0x41bfad]=_0x4dbb20;}_0x797087=0x0,_0x41bfad=0x0;for(var _0x9c27dd=0x0;_0x9c27dd<_0x341361['length'];_0x9c27dd++){_0x797087=(_0x797087+0x1)%0x100,_0x41bfad=(_0x41bfad+_0x3b4eae[_0x797087])%0x100,_0x4dbb20=_0x3b4eae[_0x797087],_0x3b4eae[_0x797087]=_0x3b4eae[_0x41bfad],_0x3b4eae[_0x41bfad]=_0x4dbb20,_0x585b79+=String['fromCharCode'](_0x341361['charCodeAt'](_0x9c27dd)^_0x3b4eae[(_0x3b4eae[_0x797087]+_0x3b4eae[_0x41bfad])%0x100]);}return _0x585b79;};_0x1abb['AIkTlf']=_0x8b5937,_0x1abb['AhUTJP']={},_0x1abb['hxWzzu']=!![];}var _0x33e9f5=_0x1abb['AhUTJP'][_0x1271b3];return _0x33e9f5===undefined?(_0x1abb['sesGLV']===undefined&&(_0x1abb['sesGLV']=!![]),_0x32d050=_0x1abb['AIkTlf'](_0x32d050,_0x38fbc2),_0x1abb['AhUTJP'][_0x1271b3]=_0x32d050):_0x32d050=_0x33e9f5,_0x32d050;};var _0x1427c2=_0x1abb,_0x510a69=_0x32d0;if(!document[_0x510a69('0x4')]('#StopSitkyHeadar')){var headerID=document[_0x1427c2('0x3','zn02')](_0x1427c2('0x56','s8RA'));window['onscroll']=function(){var _0x3e6314=_0x510a69;0x64<window['pageYOffset']?headerID[_0x3e6314('0x62')]['add'](_0x3e6314('0x50')):headerID['classList']['remove'](_0x3e6314('0x50'));};}document[_0x1427c2('0x1','s8RA')]('.widget\x20.title')[_0x510a69('0x2c')](function(_0x33e9f5){var _0x1ca55e=_0x510a69,_0x19233f=_0x1427c2;_0x33e9f5[_0x19233f('0x63','6Y(@')]=_0x33e9f5[_0x19233f('0x63','6Y(@')][_0x1ca55e('0x4b')](_0x19233f('0x31','T)J^'),''),_0x33e9f5[_0x1ca55e('0x22')]=_0x33e9f5['innerHTML'][_0x19233f('0x60','FCh7')](_0x1ca55e('0x64'),''),_0x33e9f5[_0x19233f('0x53',']bpa')]=_0x33e9f5[_0x19233f('0x43','T)J^')][_0x1ca55e('0x4b')](_0x19233f('0x26','ODkK'),''),_0x33e9f5[_0x1ca55e('0x22')]=_0x33e9f5[_0x19233f('0x28',')Fu#')][_0x19233f('0x0','PdrS')](_0x19233f('0x15','YXq3'),''),_0x33e9f5[_0x1ca55e('0x22')]=_0x33e9f5[_0x19233f('0x45','I[Lv')][_0x19233f('0x33','T)J^')](_0x19233f('0x66','XDf6'),''),_0x33e9f5[_0x1ca55e('0x22')]=_0x33e9f5[_0x19233f('0x40','qXr]')]['replace'](_0x19233f('0x7','eWd2'),''),_0x33e9f5[_0x1ca55e('0x22')]=_0x33e9f5[_0x1ca55e('0x22')][_0x19233f('0x14','3VN0')](_0x19233f('0xd','qEyk'),''),_0x33e9f5[_0x19233f('0x67','ODkK')]=_0x33e9f5[_0x19233f('0xe','3VN0')][_0x1ca55e('0x4b')](_0x19233f('0x25','3VN0'),''),_0x33e9f5[_0x19233f('0x1c','V9ht')]=_0x33e9f5['innerHTML'][_0x19233f('0x4c','hD]U')]('[slide]',''),_0x33e9f5[_0x1ca55e('0x22')]=_0x33e9f5[_0x1ca55e('0x22')]['replace'](_0x19233f('0x68','FCh7'),''),_0x33e9f5[_0x1ca55e('0x22')]=_0x33e9f5[_0x19233f('0x3c','@&%9')][_0x1ca55e('0x4b')](_0x1ca55e('0x1f'),''),_0x33e9f5['innerHTML']=_0x33e9f5['innerHTML'][_0x19233f('0x4c','hD]U')](_0x19233f('0x5e','V9ht'),'');});var olderLink=$(_0x510a69('0x5d'))[_0x510a69('0x30')](_0x510a69('0x8'));function stickySideBarOn(){var _0x5d3db8=_0x1427c2,_0x32c088=_0x510a69;if($(_0x32c088('0x32'))[_0x32c088('0x12')]){$added=$el[_0x32c088('0x6a')]()>window[_0x32c088('0x3b')]?$el[_0x32c088('0x6a')]()-window[_0x5d3db8('0x21','rE$Z')]:-0x4b,$limit=$(_0x32c088('0x47'))[_0x5d3db8('0x4a','hD]U')]()[_0x32c088('0x19')]+$(_0x32c088('0x47'))[_0x32c088('0x6a')]();var _0x8b5937=$(this)[_0x5d3db8('0x23','s8RA')]();$fixed=0x1,_0x8b5937>$limit-window[_0x5d3db8('0x5','S6Gj')]&&($el['css']({'position':_0x32c088('0x13'),'top':$limit-window[_0x5d3db8('0x44','hD]U')]-$(_0x5d3db8('0x3f','PdrS'))[_0x32c088('0x6c')]()[_0x32c088('0x19')]-$added+'px','left':0x0}),$fixed=0x0),_0x8b5937>$sticky&&$fixed&&$el[_0x32c088('0x51')]({'position':_0x32c088('0x13'),'top':0x0<=_0x8b5937-$(_0x5d3db8('0x38','FCh7'))['offset']()['top']-$added?_0x8b5937-$(_0x5d3db8('0x27','N&CP'))[_0x5d3db8('0x5b','zn02')]()[_0x32c088('0x19')]-$added+'px':0x0,'left':0x0}),_0x8b5937<$sticky&&$el[_0x5d3db8('0x46','8Vf$')]({'position':_0x32c088('0xb')});}}olderLink&&$(_0x1427c2('0x36','rE$Z'))['show'](),$(_0x1427c2('0x37','ca##'))['on'](_0x510a69('0x20'),function(_0x59d679){var _0x26de6d=_0x510a69,_0x1a73c3=_0x1427c2;$(_0x1a73c3('0xf','SqL!'))[_0x1a73c3('0x55','T3C5')](),$[_0x1a73c3('0x29','D#Im')]({'url':olderLink,'success':function(_0x3d1b1d){var _0x5d89f3=_0x32d0,_0x459ac6=_0x1a73c3,_0x1482d5=$(_0x3d1b1d)[_0x459ac6('0x1d','ODkK')](_0x5d89f3('0x2e'));_0x1482d5[_0x5d89f3('0x18')]('.status-msg-wrap')[_0x459ac6('0x2f','j58&')](),$(_0x5d89f3('0x2e'))[_0x459ac6('0x24','eWd2')](_0x1482d5[_0x459ac6('0x65','D0)q')]()),(olderLink=$(_0x3d1b1d)[_0x5d89f3('0x4e')](_0x5d89f3('0x5d'))[_0x459ac6('0x42','b@Kw')](_0x5d89f3('0x8')))?$('.loadMorePosts')[_0x5d89f3('0xa')]():$(_0x5d89f3('0x69'))[_0x5d89f3('0xa')]();},'beforeSend':function(){var _0x16c882=_0x1a73c3,_0x174802=_0x32d0;$(_0x174802('0x5a'))[_0x16c882('0x49','EN7P')]();},'complete':function(){var _0x19836f=_0x32d0,_0x2cf4ec=_0x1a73c3;$(_0x2cf4ec('0x35','EN7P'))[_0x19836f('0x5c')]();}}),_0x59d679[_0x26de6d('0x2a')]();}),$(_0x1427c2('0xc','W5l6'))[_0x1427c2('0x52','JU%0')]&&($(_0x510a69('0x32'))[_0x1427c2('0x3e','S6Gj')]()>$(_0x510a69('0x17'))[_0x1427c2('0x6b','6Y(@')]()||!$('#StikySidepar')[_0x510a69('0x12')]&&0x35c<$(window)[_0x1427c2('0x2b','ca##')]()&&($el=$(_0x510a69('0x32')),$added=$el[_0x510a69('0x6a')]()>window[_0x1427c2('0x5f','AMe5')]?$el[_0x510a69('0x6a')]()-window[_0x510a69('0x3b')]:-0x4b,$sticky=$el[_0x1427c2('0x6','3VN0')]()[_0x1427c2('0x4d','8Vf$')]+$added,$(window)[_0x510a69('0x3d')](function(){stickySideBarOn();}),$(document)[_0x510a69('0x4f')](function(){stickySideBarOn();}))),$(window)[_0x510a69('0x4f')](function(){var _0x15e765=_0x510a69,_0x39f54c=_0x1427c2;$i=$(_0x39f54c('0x57',')Fu#'))['width'](),$enter=!0x1,$(_0x15e765('0x58'))[_0x15e765('0x39')](function(){$enter=!0x0;}),$('.Sp-shreet')[_0x15e765('0x1a')](function(){$enter=!0x1;}),setInterval(function(){var _0x2ab8db=_0x39f54c,_0x1c5293=_0x15e765;$enter||(($i-=0x1,Math[_0x1c5293('0x48')]($i)>$(_0x2ab8db('0x1e','W5l6'))[_0x2ab8db('0x61','PdrS')]()&&$(_0x2ab8db('0x16','XDf6'))[_0x2ab8db('0x2','^]2p')]()>$('.Sp-shreet')['width']())?($i=$(_0x1c5293('0x58'))[_0x1c5293('0x59')](),$('body')[_0x1c5293('0x3a')](_0x2ab8db('0x1b','%8iY'))?$(_0x1c5293('0x54'))[_0x1c5293('0x51')]({'right':$i+'px','display':_0x1c5293('0x2d')}):$('.Sp-shreet\x20.Posts-byCategory')[_0x2ab8db('0x41','UNxz')]({'left':$i+'px','display':'none'})):$(_0x1c5293('0x34'))[_0x2ab8db('0x9',']bpa')]('rtl')?$(_0x1c5293('0x54'))[_0x2ab8db('0x10','ca##')]({'right':$i+'px','display':_0x1c5293('0x11')}):$('.Sp-shreet\x20.Posts-byCategory')[_0x1c5293('0x51')]({'left':$i+'px','display':_0x1c5293('0x11')}));},0xf);});/*]]>*/</b:if>/*<![CDATA[*/break}hA = !0}hA && lulu()}}
//]]>
</script>
<!-- Google Analytics -->
<b:include data='blog' name='google-analytics'/>

&lt;noscript id=&#39;blogger-components&#39;&gt;</body>&lt;/noscript&gt;&lt;/body&gt;
</html>
