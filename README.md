add-new-social-networj-to-digg-digg-WP-plugin
=============================================

How to add draugiem.lv social network share button to Digg Digg WP plugin at floating bar?

Developer code: http://www.draugiem.lv/applications/dev/docs/say/

Share button code:

<script type="text/javascript" src="//www.draugiem.lv/api/api.js"></script>
<div id="draugiemLike"></div>
<script type="text/javascript">
var p = {
 layout:"bubble",
};
new DApi.Like(p).append('draugiemLike');
</script>


