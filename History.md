
0.1.3 / 2013-12-20
==================

  * add favicon
  * Fix auth middleware bug (@alsotang)
  * make sure all packages name are lower case
  * select ids from tag
  * fix nodejsctl
  * fix #112 missing versions and time no sync
  * remove restart command
  * fix sync missing packages error
  * fix web/readme.md, add install
  * fix #109 pkg no times and no versions bug.

0.1.2 / 2013-12-19
==================

  * fix times not exists canot sync bug. fixed #101
  * support npm run command
  * remove before_install and install in travis, fixed #102
  * split all sub queries, fixed #104
  * fix doc, fixed #103
  * fix search too slow.
  * dont email sync log level info
  * only sync missing packages at first time
  * update dependencies
  * sync all will sync all the missing packages, fixed #97

0.1.0 / 2013-12-12
==================

  * add sync title
  * add favicon. fixed #69
  * refine sync page, fiexd #70
  * add app version
  * add test for sync
  * refine sync page
  * registry and web all use controllers/sync.js
  * sync from web, fixed #58
  * saving missing descriptions
  * add package download info. fixed #63
  * add avatar
  * use dependecies, fixed #issue62
  * support open search, fixed #60
  * make sure publish_time and author is same to source npm registry. fixed #56
  * add test for search
  * add a simple search by mysql like
  * fix This version of MySQL doesn't yet support 'LIMIT & IN/ALL/ANY/SOME subquery. fixed #54
  * update install doc, use nodejsctl to start
  * must add limit on list by author sql
  * fix sql, change test to fit my local database, fixed #46
  * use registry.cnpmjs.org
  * add install document and total package info on home page. fix #42
  * add module_id to tag table. #46
  * skip error version. fixed #43
  * sync may make a user do not exist in database, but have modules in registry
  * add user page
  * fix set license
  * ignore 404 on sync. fixed #39
  * fix module page, add test
  * update urllib to 0.5.5
  * version and tag
  * add module page
  * fix download url
  * first get tag, then try version
  * support sync triggle by install, finish #31
  * addTag error return 500
  * just one download field
  * add download total info on home page
  * add download count
  * versions empty and also check missing tags
  * remove tags on unpublish
  * add module tag. fix #6
  * add [done] flag to check sync done on client
  * get sync log #29
  * fix test in module
  * rm tmp file on down request error
  * add time for debug str
  * fix pkg not exists null bug
  * use sync module woker to handle sync process. fixed #19
  * if private mode enable, only admin can publish module
  * add alias in readme
  * fix sql, add sort by name
  * fix sql
  * add api to support npm search and auto completion
  * add npm and cnpm image
  * add registry total info on home page
  * fix mods bug in module.removeAll, change module.update => module.removeWithVersions
  * add test, fix bug. fixed #18
  * spoort unpublish
  * add web page index readme
  * switchable nfs #21
  * change file path to match npm file path
  * use qn cdn to store tarball file fixed #16
  * add GET /:name/:version, fixed #3
  * add module controller test cases; fix next module not exists logic bug.
  * publish module flow finish #11
  * add test for controllers/registry/user.js
  * add test for middleware/auth
  * add test for proxy/user
  * remove index.js
  * fix typo
  * add redis as session store
  * fix nodejsctl mod
  * add start time
  * add home page
  * remove session controller
  * adduser() finish fixed #5
  * rm app.js and routes.js
  * Mock npm adduser server response, fixing #5
  * adjust project dir, separate registry and web server
  * Init rest frame for cnpmjs.org
  * init
