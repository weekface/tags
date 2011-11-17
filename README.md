使用tags可以方便地为您的系统添加很酷的标签添加效果
===

### 首先在需要添加的地方放入一个div:

class必须是ggTagContainer

    <div class="ggTagContainer"></div>

调用:

    jQuery(".ggTagContainer").tags({
       field: "tags1",                //field为保存tags的input(hidden)的name
       fieldId: "tags1",              //field为保存tags的input(hidden)的id
       tags: ["北京","上海","南京"],    //tags为热门标签
       has: ["美丽","幸福"]            //has为已经存在的标签
    });

您可以通过jQuery.mTags获取添加的标签，或者通过jQuery("#tags1")获取
