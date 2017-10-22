------------------------------------------------
SEARCH is installed/updated!

• You should make a copy of any .EXAMPLE files, remove the .EXAMPLE extension and customize

• To include search on a page:
	Make sure this is inside the html <head> tag:
		{%include search_support_head.html %}

	Put one of these where you want a search box to appear:
		{% include searchbox placeholder="Search for:"%}
		{% include searchbox_small placeholder="Search for:"%}
