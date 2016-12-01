#Tips
##Stash
	$git stash 
	$git stash apply
	$git stash drop
##Pull
	$git pull
##Tag
	$git tag
	$git tag tagName
	$git tag tagName commitID
	$git show commitID
	$git tag -a tagName -m comment commitID
	$git tag -d tagName
	$git push origin tagName
	$git push origin --tags
	$git push origin :refs/tags/tagName