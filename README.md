使用tags可以方便地为您的系统添加很酷的标签添加效果
===

### 首先在需要添加的地方放入一个div:

其中id可以随意起名，比如是:tag_container.但是class必须是ggTagContainer

    <div id="tag_container" class="ggTagContainer"></div>

调用:

    jQuery("#tag_container").tags({
       field: "tags1",                //field为保存tags的input(hidden)的name
       fieldId: "tags1",              //field为保存tags的input(hidden)的id
       tags: ["北京","上海","南京"]     //tags为预设标签
    });

您可以通过jQuery.mTags获取添加的标签，或者通过jQuery("#tags1")获取
