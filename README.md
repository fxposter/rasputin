Rasputin
========

This is a gem for integration of SproutCore 2.0 with Rails 3.1 assets pipeline.

It provide direct requires for official sproutcore packages :

* sproutcore
* sproutcore-datastore
* sproutcore-statechart

And it also provides some unnoficial packages :

* sproutcore-ajax (backport form sc 1.x API but using jQuery $.ajax)
* sproutcore-jui (jQuery UI wrappers for sc 2.0)
* sproutcore-throbber (jQuery UI throbber and it's wrapper for JUI)

Rasputin also provide sprockets engine for handlebars templates. Any template in your
javascript assets folder with extention handlebars will be availabel in sproutcore.

Examples :

    todos/templates/item.handlebars >> SC.TEMPLATES['todos_item']
    todos/ui/templates/stats.handlebars >> SC.TEMPLATES['todos_ui_stats']
