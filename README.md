# Magento2-CategoryUrlFilter
Rewrite Category filter behaviour to change category filter URL in Layered Navigation

Magento default provide category filter in layered navigation on product listing page, inside category filters all sub-categories will be listed in left side layered navigation filter section.

i.e. If we are on parent category page then it will show category child-1, category-child-2 and ... category-child-n in filter section.

When user click's on category from filter section then it will show url as below.

http://demo.website.com/parent-category/sub-parent.html?cat=clicked_selected_category's_id

Magento by default not provided feature to redirect on sub-categories link from layered navigation filter to overcome that limitation we have override code and implemented logic to redirect on sub-categorie's link from layered navigation section.

so URL will become as below

http://demo.website.com/parent-category/sub-parent/child-category.html
