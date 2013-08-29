Navigationtree snippet
======================

Website navigation with tree of all visible pages.

How do I install this?
----------------------
1. Download and install [Yellow](https://github.com/markseu/yellowcms/).  
2. Download [navigationtree.php](navigationtree.php?raw=true), copy into your system/snippets folder.  
3. Use the snippet on your website, edit templates in your system/templates folder.

To uninstall delete the snippet and remove it from templates.

Example
-------
Template with top-level navigation and tree:

    <?php $yellow->snippet("header") ?>
    <?php $yellow->snippet("navigation") ?>
    <?php $yellow->snippet("navigationtree") ?>
    <?php $yellow->snippet("content", $yellow->page->getTitle(), $yellow->page->getContent()) ?>
    <?php $yellow->snippet("footer") ?>